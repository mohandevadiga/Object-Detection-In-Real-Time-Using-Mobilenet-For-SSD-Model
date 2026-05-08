# Object Detection In Real Time

This workspace contains an object detection project for real-time image detection using pre-trained models.

## Contents

- `NoteBookCoCo.ipynb` - Jupyter notebook for experimenting with COCO object detection and image samples.
- `MobileNetSSD_deploy.caffemodel` / `MobileNetSSD_deploy.prototxt` - MobileNet SSD model files.
- `ssd_mobilenet_v3_large_coco_2020_01_14.pbtxt` / `frozen_inference_graph.pb` - TensorFlow SSD model files.
- `coco.names` - COCO class labels file.
- `images/` - image asset folder.
- `redmi.jpg` - added sample image for detection tests.

## Usage

1. Open `NoteBookCoCo.ipynb` in Jupyter or VS Code.
2. Load the desired model and label files.
3. Run the notebook cells to perform detection on sample images or live video.

## Notes

- This repository appears to be focused on quick prototyping, image testing, and model evaluation.
- Add more images to `images/` as needed for testing.
