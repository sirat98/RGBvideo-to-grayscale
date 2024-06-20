---
# **RSB FILE to grayscale file**

-1. We import the OpenCV library.
-
-2.We open the input RGB video file using cv2.VideoCapture().
-
-3.We check if the video file was opened successfully.
-
-4.We get the video properties (fps, width, height) from the input video.
-
-5.We create a VideoWriter object for the output grayscale video. Note that isColor=False specifies that we're creating a grayscale video.
-
-6.We enter a loop to process each frame of the video:
-

-7.Read a frame from the input video
-
-8.Convert the frame to grayscale using cv2.cvtColor (frame, cv2.COLOR_BGR2GRAY)-
-
-9.Write the grayscale frame to the output video
-


-10. After processing all frames, we release the video objects.
-
-11. Finally, we print a message indicating that the conversion is complete.
-
-To use this code:
-
-Replace "path/to/input_video.mp4" with the actual path to your input RGB video file.
-
-Run the script. It will create a new file named 'grayscale_output.mp4' in the same directory as your script.


