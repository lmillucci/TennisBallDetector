TennisBallDetector
==================

Detect tennis ball using OpenCV + C++ 

Compile:

g++ main.cpp -o main -lopencv_calib3d -lopencv_contrib -lopencv_core -lopencv_features2d -lopencv_flann -lopencv_gpu -lopencv_highgui -lopencv_imgproc -lopencv_legacy -lopencv_ml -lopencv_objdetect  -lopencv_video -lopencv_features2d -L/usr/lib 

Execute
./main --> video from source
./main 680 480 --> video from webcam at 680x480 pixel
