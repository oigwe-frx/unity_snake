
Use a UI Canvas (Screen Space - Camera)

If you want a background that automatically stretches to cover the screen dimensions regardless of aspect ratio:
1. Right-click in the Hierarchy and go to UI > Canvas.
2. Select the Canvas, go to the Canvas component in the Inspector, and set Render Mode to Screen Space - Camera.
3. Drag your Main Camera into the Render Camera field.
4. Right-click the Canvas in the Hierarchy and choose UI > Image (this will be your background).
5. Assign your background texture to the Source Image slot on the Image component.
6. Click the Rect Transform anchor preset box (top-left of the Rect Transform component) and hold Alt + Shift while clicking the stretch-to-full (bottom-right) preset so the image locks to all edges of the screen.
