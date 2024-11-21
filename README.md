## Make passport ID photos
1. Rotation image
2. Remove the background
3. Finds a face - crops the photo to 3x4 and 4x6 cm
## How to run
  Add all of yor images in the "inpic" folder and run "python run face_crop.py"
    it will first remove background of the images and save to rmbg folder
    and then processed to passport size images and will save the final output to "outpic" outpic
    outpic folder: 3x4 and 4x6 output photos
  
Make Sure first run pip install -r requirements.txt to install all the requirements

