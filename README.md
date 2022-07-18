
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:layout_gravity="center"
    android:background="@drawable/ic_background"
    tools:context=".MainActivity">

    <ImageView
        android:layout_width="76dp"
        android:layout_height="76dp"
        android:layout_gravity="center"
        android:layout_marginTop="310dp"
        android:src="@drawable/logo"
        android:id="@+id/img_1"/>

    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:textAlignment="center"
        android:text="@string/power"
        android:id="@+id/text_b"
        android:textSize="18sp"
        android:textStyle="bold"
        android:textColor="@color/black"
        android:layout_marginTop="270dp"/>

    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:textAlignment="center"
        android:text="@string/pembuat"
        android:id="@+id/text1"
        android:textSize="18sp"
        android:textStyle="normal"
        android:textColor="@color/black"
        android:layout_marginTop="5dp"/>

</LinearLayout>
