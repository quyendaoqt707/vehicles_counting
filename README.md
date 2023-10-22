# Vehicels Counting
Detection: YOLOV3-Tiny

Tracking: OpenCV

Video step by step: https://www.youtube.com/watch?v=ZRC2nzP1w_4&list=PLUzMg0FYFJETawSkez0b9C41ByOo6_N5L&index=2

# Fix bugs:
- conflict open-cv version: `AttributeError: module 'cv2' has no attribute 'TrackerKCF_create'`
  - run `pip uninstall opencv-contrib-python opencv-python opencv-contrib-python-headless`
  - then `pip install opencv-contrib-python`