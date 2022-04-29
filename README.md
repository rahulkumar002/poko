# poko
fund
<?xml version="1.0" encoding="utf-8"?>
<androidx.coordinatorlayout.widget.CoordinatorLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".toolbarActivity"
    android:background="@color/black">

<!--    height below will be more so that cards view layout could be added-->
    <com.google.android.material.appbar.AppBarLayout
        android:layout_width="match_parent"

        android:layout_height="wrap_content"
        android:theme="@style/Theme.PocketO.AppBarOverlay"
        android:layout_marginTop="20dp"
        android:layout_marginLeft="20dp"
        android:layout_marginRight="20dp"
        android:background="@color/black">

        <androidx.appcompat.widget.Toolbar
            android:id="@+id/toolbar"
            android:layout_width="match_parent"
            android:layout_height="?attr/actionBarSize"
            android:background="@drawable/toolbar_background_shadow"
            app:popupTheme="@style/Theme.PocketO.PopupOverlay"
            app:menu="@menu/toolbar"/>

        <include layout="@layout/content_toolbar" />

    </com.google.android.material.appbar.AppBarLayout>

</androidx.coordinatorlayout.widget.CoordinatorLayout>
