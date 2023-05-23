# Virtual Artist 

Created alongside team members (Alan Kusparmakov, Minh Duc Vo, Onur Yararbas) at UCDavis Hackathon 2023. 

# What is Virtual Artist? 

The virtual artist is a platform that allows one to draw on a small canvas. Users can write with their index finger, erase with their index and middle finger side by side, and change the colors of the drawing by moving their fingers to the corner of the canvas. All of the recognition is recorded using the user's web camera, drawing pictures composed from x, and y coordinates gathered from hand-landmark analysis. This allows the user to draw on their computer screen by simply drawing in the air in front of them.


# What could Virtual Artist be used for?
Virtual artist can be used for a number of things, ranging from personal free-hand drawing all the way to a classroom adaptation where teachers can draw in the air, reducing the need to turn around to a white board. When we started this idea, we wanted to make a program that could interpret motion through webcam and draw it down onto a canvas.


# How does Virtual Artist run?

Virtual artist runs off of Google's OpenCV and Mediapipe, and is implemented in Python. When the user runs the code, a display of the user's webcam shows up, alongside a blank canvas (with colored borders to switch pen colors). The user can now draw in the air and through OpenCV and Mediapipe, and can customize their pen size and color, all while drawing purely in the air!


# Next steps

If given more time, our next steps would be to implement, using an AI trained through ML on datasets exclusively on ASL, an interface where an ASL interpreter could have their signs be translated live back into written language.

# Note To Users

The platform is slightly laggy/buggy when approaching the corners of the canvas. DEBUG NOTES: If the color turns white randomly (without instruction), move your fingers to one of the corners of the canvas to change the color back. Make sure you really go deep into the "Color" region to choose/select your pen color (slightly missing the "color region" might not change the color) Make sure your fingers/gestures that you are making with your fingers be explicit so the program can recognize. One finger up - Drawing/Writing, 4 Fingers Up (thumb at palm) - Erase. One hand in the frame at a time. Click 'q' to cancel out of the program. 
