# AndroidOpenCV
教Lab同學建立OpenCV Camera App的範例程式

# 關於OpenCV 3.0.0

在程式初始化OpenCV時，要指定目前的OpenCV版本為3.0.0 <br/>
OpenCVLoader.initAsync(OpenCVLoader.OPENCV_VERSION_3_0_0, this, mLoaderCallback); <br/>

並且要安裝OpenCV Manager於Android行動裝置中 <br/>
adb install [apk位置] <br/>
例如： <br/>
adb install D:\OpenCV-android-sdk\apk\OpenCV_3.0.0_Manager_3.00_armeabi-v7a.apk

如果沒安裝對應版本(在這裡是3.0.0)的OpenCV Manager <br/>
則會出現：<b>Package not found</b> <br/>
OpenCV Manager package was not found! Try to Install it?