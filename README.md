# DoubleEyes
语音播报判断
1.首先判断是否有障碍物，也就是UVCPreview.cpp
line:1515 获取是否有障碍 return 0(no) 1(yes）如果返回1，那么判断水平方向的值（1到10）和垂直方向的值(垂直方向1，2)
如水平方向的值是2，垂直方向是1，那么此时会播报左;如水平方向的值是5，垂直方向的值是2，此时会播报上....

开始人脸识别 UVCPreview.cpp  line 1530
void UVCPreview::start_face_recognition(){
    LOGE("start_face_recognition");
    .............
}
实现之后在程序主页点击右边的capture就可以看到效果
