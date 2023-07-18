# Letter_Classification
A project to classify handwritten letters using a CNN:

- Load CSV: Read CSV files containing handwritten letter pixel values.
- Split Data: Split data into training and test sets.
- Create CNN Model: Initialize a CNN model with ResNet18 architecture and train it.
- Define Function: Create a function to preprocess input images for inference.
- Define Function: Create a function to classify handwritten letters using the pre-trained model.
- Use preprocessed tensors for inference.
- Export Model: Save the trained model as a .pkl file for later use.
- Modify Function: Update the preprocessing function to return the preprocessed PIL image.
- Display: Visualize the original and preprocessed images side by side.
