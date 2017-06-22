# CircleNetImageView基于Picasso的网络加载圆形头像

使用：1.在xml添加
/...
  <包名.CircleImageView
    xmlns:app="http://schemas.android.com/apk/res-auto"
    android:id="@+id/profile_image"
    android:layout_width="96dp"
    android:layout_height="96dp"
    android:src="@drawable/profile"
    app:civ_border_width="2dp"
    app:civ_border_color="#FF000000"/>
    .../
    
      2.CircleImageView imageview = (CircleImageView) findViewById(R.id.profile_image);
         imageview.loadUrl("http://www.baidu.com/test.jpg");
