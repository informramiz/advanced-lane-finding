# Advanced Lane Finding

![Sample output video](animated.gif)

In this project, the goal was to write a software pipeline to identify the lane boundaries in a video.

The goals/steps of this project are the following:

- Compute the camera calibration matrix and distortion coefficients given a set of chessboard images.
- Apply a distortion correction to raw images.
- Use color transforms, gradients, etc., to create a thresholded binary image.
- Apply a perspective transform to rectify binary image ("birds-eye view").
- Detect lane pixels and fit to find the lane boundary.
- Determine the curvature of the lane and vehicle position with respect to the center.
- Warp the detected lane boundaries back onto the original image.
- Output visual display of the lane boundaries and numerical estimation of lane curvature and vehicle position.

The images for camera calibration are stored in the folder called `camera_cal`.

# Getting Started

All the code is written in Jupyter Notebook in steps so running them sequentially should work fine. It also shows each step in action with an example output result. You can also look at [sample input video](project_video.mp4) and [sample output video](project_video_lanes_detected.mp4) to see project in action on a video.

# License 

This code is licensed under [MIT License](https://opensource.org/licenses/MIT)
