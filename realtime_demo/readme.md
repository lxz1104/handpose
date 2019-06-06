# This is a realtime demo for CrossInfoNet

**The original demo is from [deepprior++](https://github.com/moberweger/deep-prior-pp/tree/master/src)**



## realsense-lib install

You can use pip install pyrealsense2 esaily.

   sudo pip install pyrealsense2
  
Or you can also built the python lib from [source](https://github.com/dumyy/librealsense/tree/master/wrappers/python) 

In this demo, we use Realsense SR300 device.

## realtime running

just `cd realtime_demo` and `run` the command in you Terminal:

   python real_time_show_demo.py --dataset ${dataset_name}

eg. You want to load nyu model for realtime testing, use `nyu` to replace `${dataset_name}`,just like follow:

   python real_time_show_demo.py --dataset nyu
   python real_time_show_demo.py --dataset msra
 
## Something else

when you are testing, 30cm -40 cm is a good choice for your hand to the camera.

The end 


