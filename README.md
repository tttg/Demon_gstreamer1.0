# Demon_gstreamer1.0  
inputs:ov5640 plus IRD camera  
outputs:lcd+hdmi  
platform:arm imx6 linux  
software:gstreamer1.0  
code:c gstreamer1.0 api  
des:cameras->output cameras->file using hard codec/ipu/h264 of gstreamer-plugin-imx.
---------------------------------------------------------------------------------------------------
[helps]  
[CAMERA0_TO_LCD] ->lcd   
[CAMERA0_TO_HDMI] ->hdmi  
[CAMERA0_TO_H264_AVI] ->h2640.avi  
[CAMERA0_TO_RAW_AVI] ->raw0.avi  
[CAMERA0_TO_JPEG] ->raw0.jpeg  
[CAMERA0_TO_LCD_APPEND] ->lcd  
[CAMERA0_TO_HDMI_APPEND] ->hdmi  
[CAMERA0_TO_H264_AVI_APPEND] ->h2640_apd.avi  
[CAMERA0_TO_RAW_AVI_APPEND] ->raw0_apd.avi  
[CAMERA0_TO_DUMMY_LCD] ->lcd  
[CAMERA0_TO_DUMMY_HDMI] ->hdmi  
[CAMERA1_TO_LCD] ->lcd  
[CAMERA1_TO_HDMI] ->hdmi  
[CAMERA1_TO_H264_AVI] ->h2641.avi  
[CAMERA1_TO_RAW_AVI] ->raw1.avi  
[CAMERA1_TO_JPEG] ->raw1_apd.jpeg  
[CAMERA1_TO_LCD_APPEND] ->lcd  
[CAMERA1_TO_HDMI_APPEND] ->hdmi  
[CAMERA1_TO_H264_AVI_APPEND] ->h2641_apd.avi  
[CAMERA1_TO_RAW_AVI_APPEND] ->raw1_apd.avi  
[CAMERA1_TO_DUMMY_LCD] ->dummy_lcd  
[RECORD_LCD_TO_FILE_PULL] ->lcd.mp4  
[RECORD_LCD_TO_FILE_PUSH] ->lcd.mp4  
[CAMERA1_OVERLAY_TO_LCD] -> lcd  
[CAMERAS_OVERLAY_TO_LCD] -> lcd  
--------------------------------------------------------------------------------------------
[srcs code]  
QQ:420788046  
Email:luwei860123@163.com  
