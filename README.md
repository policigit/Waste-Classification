# Waste Classification using CNN

This project uses Convolutional Neural Networks (CNN) to classify images of waste into different categories, helping automate waste sorting for better recycling and environmental management.

## Project Structure
- **WasteClassification.ipynb**: Main notebook implementing a simple CNN for waste classification.
- **WasteClassification_IncepV3.ipynb**: Uses InceptionV3 model for transfer learning.
- **WasteClassification_ResNet152.ipynb**: Uses ResNet152 model for transfer learning.

## Dataset
- Images of waste items, organized in folders by class (e.g., plastic, metal, organic, etc.).
- Data is loaded and split into training and validation sets using TensorFlow utilities.

## Workflow
1. **Data Loading & Preprocessing**: Images are resized, normalized, and augmented.
2. **Model Building**: A CNN is built from scratch, and transfer learning is explored with InceptionV3 and ResNet152.
3. **Training**: Models are trained and validated.
4. **Evaluation**: Performance is measured using accuracy, loss curves, confusion matrix, and classification report.

## How to Run
1. Install required libraries (TensorFlow, NumPy, Matplotlib, scikit-learn).
2. Open the notebook in Jupyter or Google Colab.
3. Set the dataset path and run all cells.

## Results
- The project compares a simple CNN with advanced pre-trained models.
- Visualizations help understand model performance and learning behavior.

## Usage
This project can be used as a template for image classification tasks or as a starting point for waste management automation using AI.

## Author
- [Your Name]

---

## How to Push Changes to GitHub
1. Save your changes in VS Code or your editor.
2. Open a terminal in your project directory.
3. Run the following commands:

```powershell
git add README.md
git commit -m "Add project README"
git push
```

This will upload the README file and your changes to your GitHub repository.