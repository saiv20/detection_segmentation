# detection_segmentation

This projects was built for detecting objects (especially interested in vehicles and pedestrians) and segmentation of roads. YOLOv5 was used for object detection and UNet was used for road segmentation. 

## Object Detection

The yolov5-master/ folder contains the files required to perform object detection using YOLOv5. Run detect.py to detect images as follows:

    python detect.py --source imgs/1.png --weights yolov5m.pt
    
The results observed are as follows:

![Img1](https://github.com/saiv20/detection_segmentation/blob/main/yolov5-master/runs/detect/exp/1.png)

![Img2](https://github.com/saiv20/detection_segmentation/blob/main/yolov5-master/runs/detect/exp2/2.png)

![Img3](https://github.com/saiv20/detection_segmentation/blob/main/yolov5-master/runs/detect/exp3/3.png)

## Road Segmentation

The unet/ folder contains the files required to perform road segmentation using UNet. Run test.py to perform segmentation. The results are observed as follows:

![Img4](https://github.com/saiv20/detection_segmentation/blob/main/unet/KITTI-RoadSeg-master/output/overlay_uu_000090.png)




