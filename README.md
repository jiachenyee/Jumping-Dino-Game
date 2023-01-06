# Jumping Dino Game
Ok what if, you were the space bar?

A glorified space bar so you can play the Chrome Dino game by physically jumping. Possibly a good way to force yourself to exercise.

![image](https://user-images.githubusercontent.com/36725840/211043109-548e60fe-0bf6-4780-bae0-f71f007d81dc.png)

# Requirements
- Xcode 14.2
- Minimum system version (run project): macOS Catalina, 10.15
- Minimum system version (build project): macOS Ventura, 13.2
- Google Chrome

# Running the Project
1. Open the `.xcodeproj` and run the project
2. Open Chrome and go to [`chrome://dino`](chrome://dino).
3. Bring the app into the foreground
4. Get the player to stand back, making sure their face is fully visible with some space towards the top of their head
5. When the face tracking locks onto the player, click the `C` key or press Callibrate. This will add a red line just above their head. 
6. If the centre of their head passes the line, it is detected as a jump and the space bar will be pressed
7. Bring the Chrome window to the foreground and get the player to jump to start the game

> Note: there would be a slight lag between detection and the actual space bar being pressed depending on the Mac running it

# Permissions
- Camera: Track face to track jumps
- Accessibility: Press the space bar automatically

Built for NP Open House 2023.
