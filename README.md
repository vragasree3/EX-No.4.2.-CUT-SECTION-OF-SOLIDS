# EX No.4.2. CUT SECTION OF SOLIDS
## DATE:

## AIM: 
To create the solid model from given drawing and section the solid model

## REQUIREMENTS: 
1. Autodesk fusion 360
2. Windows 10
3. 16 GB of RAM (integrated graphics recommend 1 GB or more)
4. 2.5 Mbps or faster download; 500 Kbps or faster upload 

## PROCEDURE:

1. Start a New Design

Open Autodesk Fusion 360 and create a new design. Set the document units to match the units specified in the drawing’s title block. Save the design with an appropriate name, such as EX 4.2 Cup and Stand.
<img width="237" height="482" alt="Screenshot 2026-11-13 210155" src="https://github.com/user-attachments/assets/bf008cb4-c667-40d1-80d6-3d2324d63c74" />


2. Select the Sketch Plane

●In the Design workspace, select Create Sketch.
●Choose the Front plane (XZ plane) so the cup and stand’s side profile is visible in the sketch.
●Turn on the origin and sketch grid if they are not visible. The model will be symmetrical about a vertical centerline.

3. Draw the Revolve Axis

●Select the Line tool and draw a vertical line through the origin.
●Convert the line to Construction geometry, or use the sketch’s center axis.
●This line will be the axis around which the side profile is revolved.

4. Sketch the Base Profile

●Begin at the centerline near the bottom of the model and draw one half of the base’s cross-section.
●Draw the short flat bottom and the sloped outer edge shown in the front view.
●Use the Line tool for straight edges and apply the slope angle shown in the drawing.
●Dimension the base using the given measurements, including the Ø2.73 diameter and the 6.79° slope.
●Add the 1.25 dimension where it applies to the base profile.
●Close the base outline back to the centerline so it forms part of a closed cross-section.

5. Sketch the Stem

●From the center of the base, draw the two vertical edges of the narrow stem.
●Keep the stem centered on the revolve axis.
●Dimension its height and width according to the drawing. The front view shows the stem joining the base to the underside of the cup.
●Connect the top of the stem to the bottom of the cup profile, ensuring the whole cross-section remains closed.

6. Sketch the Cup’s Outer Profile

●From the top of the stem, draw the underside of the cup and the outer curved wall.
●Use Arc or Three-Point Arc to create the rounded bowl profile shown in the drawing.
●Dimension the curve using the radius marked R12.
●Draw the top rim and set its outside diameter to Ø2.41 as shown.
●Use constraints such as Tangent, Coincident, and Horizontal to keep the curve and rim connected smoothly.

7. Sketch the Cup’s Inner Profile

●Starting at the inside edge of the rim, draw the inner curved wall of the cup.
●Shape it to follow the outer curve while preserving the wall thickness shown by the dashed line in the front view.
●Set the inner opening diameter to Ø2.11.
●Connect the inside wall to the bottom of the cavity, then connect the cavity back toward the rim.
●Check that the inside and outside curves form a single closed profile and that the cup opening remains hollow.

8. Complete and Constrain the Sketch

●Use Trim to remove extra lines or arc segments.
●Check that all profile endpoints meet and there are no gaps.
●Apply the dimensions shown in the drawing, including the overall height of 2.56, the vertical measurement of 1.36, and the indicated .36 and .15 measurements.
●Add constraints to keep the profile aligned with the revolve axis and maintain its symmetry.
●Select Finish Sketch.
<img width="364" height="173" alt="Screenshot 2026-11-09 171520" src="https://github.com/user-attachments/assets/23146be0-0911-46eb-8792-ec965ab30097" />

9. Revolve the Profile

●Select Create > Revolve.
●Select the closed cross-section of the cup, stem, and base as the Profile.
●For Axis, select the vertical construction line through the center.
●Set the revolve angle to 360° and the operation to New Body or Join, as appropriate.
●Select OK. The revolved result should form a circular base, centered stem, and hollow round cup.

10. Inspect the Model

●Rotate the model to an isometric view and compare it with the isometric drawing.
●Check the side view to confirm the base slope, stem position, cup height, and overall height.
●Check the top view to confirm the circular rim and the Ø2.11 and Ø2.41 diameters.
●If the cup is not hollow, edit the sketch to correct the inner profile and revolve it again.

11. Apply Finishing Details

Add fillets or small edge rounds only where they are shown in the drawing. Keep the cup rim, base edge, and stem junction smooth while preserving the specified dimensions.
<img width="311" height="417" alt="Screenshot 2026-11-13 210611" src="https://github.com/user-attachments/assets/84c2fce9-4d94-4246-b0d0-e80424082d0b" />

12. Save the Design

Select Save, enter the project name, and save the completed Fusion 360 design


## INPUT:

![image](https://user-images.githubusercontent.com/113594316/199409656-c021c100-857a-4ae4-9752-9ae59465c9c2.png)

## OUTPUT:
<img width="988" height="706" alt="Screenshot 2026-11-22 134557" src="https://github.com/user-attachments/assets/68288275-38a9-49f1-9dd8-89a40c8130be" />


## RESULT:
Thus, the cut section for solid model is created.


