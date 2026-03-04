# Image Basics Test 9 Assignment

In this assignment, you will modify a Jupyter Notebook to enhance your understanding of image processing fundamentals. By progressing from the starter code to the solution code, you will learn to manipulate image data effectively.

## Learning Objectives
- Implement image loading and displaying functionalities.
- Perform basic image transformations and filtering.

## Your Coding Environment
- You will be using a Jupyter Notebook interface where you can edit the code in the cells.
- The notebook consists of several tabs related to your assignment.
- Use the **Run button** to execute your code and test your changes.
- After making your changes, click the **Commit button** to save your work and check for feedback.
- The autograder will provide you with a ✅ for correct implementations or a ❌ for errors.

## Workflow
1. Edit the code in your Jupyter Notebook.
2. Click the **Run button** to execute the code and check the output.
3. Press the **Commit button** to save and validate your code.
4. Review the autograder feedback (✅/❌).

## Implementation Instructions
Below are the modifications you need to implement to transition from the starter code to the solution code:

1. **Add Image Loading Functionality**:
   - Implement a function named `load_image` which accepts a file path as its parameter and uses `PIL` to open the image. It should return the image object.

   ```python
   def load_image(file_path):
       # Add code to load an image using PIL
   ```

2. **Display the Image**:
   - Below the image loading function, create a function called `display_image` that takes an image object as an argument and uses `matplotlib` to display it.
   
   ```python
   def display_image(img):
       # Add code to display the image using matplotlib
   ```

3. **Image Transformation**:
   - Add a new function `rotate_image` that takes the image object and an angle in degrees as parameters and returns the rotated image.
   
   ```python
   def rotate_image(img, angle):
       # Add code to rotate the image by the specified angle
   ```

4. **Integrate Code into Main Execution Block**:
   - In the main execution block (make sure it’s under `if __name__ == '__main__':`), call `load_image` with a path to the image file, then call `display_image` to show the loaded image, and subsequently call `rotate_image`, followed by `display_image` again to show the transformed image.

   ```python
   if __name__ == '__main__':
       # Place your function calls in the appropriate order here
   ```

## Example Usage
Make sure to specify the correct path for the image you are testing with. For example:
```python
image_path = 'path/to/your/image.jpg'
```  

## Hints & Tips
- Ensure you have the necessary libraries (`PIL` and `matplotlib`) imported at the top of your notebook.
- Verify the image path is correct to avoid file not found errors.
- Use print statements to debug and see the output at each stage if you encounter issues.