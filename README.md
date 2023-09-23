# ColorMyViews project - Kotlin
 # ColorMyViews Android App

ColorMyViews is an Android Studio project that serves as a hands-on tutorial for learning about Android layout design and constraints. This README provides a step-by-step guide for creating the ColorMyViews app.

## Step 1: Create the ColorMyViews Project and Style the First Box

1. Create an Android Studio project named **ColorMyViews** with the following configurations:
   - Language: Kotlin
   - Minimum SDK: 29
   - Template: Empty Activity

2. Run the app to ensure it displays "Hello World!" in a TextView.

3. Open `activity_main.xml` in Design view and make the following changes:
   - Set the default margin to 16dp.
   - Turn off Autoconnect.

4. Play with the "Hello World" box by moving it, changing its dimensions, and exploring attributes.

5. Move the box to the upper-left corner with 16dp margins, and give it an id of `box_one_text`. Create a string resource named `box_one` with the value "Box One" for the text.

6. Adjust the size and constraints of the box to match the provided instructions.

7. Add a style named "WhiteBox" and apply it to the box. Ensure you have added the Roboto font to your project.

8. Run the app to confirm it matches the provided image.

## Step 2: Add Four More Aligned Boxes and Implement Click Handling

1. Add "Box Two" to your layout with a width and height of 130dp. Align it below "Box One" and to the left edge of the screen.

2. Add boxes Three, Four, and Five below "Box One" and to the right of "Box Two." Align them as instructed.

3. Implement a click handler in the `MainActivity` class using the provided code snippet.

4. Update the "WhiteBox" style as described to ensure the boxes start with white backgrounds and white font.

## Step 3: Finalize ColorMyViews Functionality

1. Below the boxes, add two TextViews for a label and information. Customize font sizes and layout constraints as per the provided instructions.

2. Test your layout by trying different devices and orientations.

3. Add the provided code to the click handler.
