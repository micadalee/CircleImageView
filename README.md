# CircleImageView
带边框的圆形头像,可自定义颜色值,边框宽度

可添加依赖直接使用

	allprojects {
		repositories {
			...
			maven { url 'https://www.jitpack.io' }
		}
	}

  	dependencies {
	        compile 'com.github.micadalee:CircleImageView:1.0.0'
	}
	
xml使用代码如下:

   <com.example.micadalee.library.CircleImageView
       android:id="@+id/image_1"
       android:layout_width="400px"
       android:layout_height="400px"
       android:src="@mipmap/timg"/>

    <com.example.micadalee.library.CircleImageView
        android:layout_below="@+id/image_1"
        android:layout_width="400px"
        android:layout_height="400px"
        android:layout_marginTop="100px"
        app:border_outside_color="#e40000"
        app:border_thickness="2dp"
        android:src="@mipmap/timg"/>
	
效果图:
![image](https://github.com/micadalee/CircleImageView/blob/master/Screenshot.png)
