# Dynamo Script: Coordinate Extraction

This Dynamo script (`Coordinate extraction.dyn`) is designed to extract the 3D coordinates (X, Y, Z) of model elements within a Revit project. It is useful for BIM workflows that require geometric data export for downstream processing, such as fabrication, structural analysis, or point cloud comparison.

## 🧩 Features

- Automatically extracts **XYZ coordinates** of selected elements
- Supports batch processing of multiple model components
- Outputs coordinates in a structured list format
- Ready for further export (e.g., to Excel, CSV, or database)

## 🛠️ Requirements

- Autodesk Revit (2019 or newer recommended)
- Dynamo (2.0+)
- (Optional) [Data Shapes](https://dynamopackages.com/Data-Shapes) or [BimorphNodes](https://dynamopackages.com/BimorphNodes) if your script uses advanced selection or export nodes

## 🚀 How to Use

1. Open your Revit model
2. Launch Dynamo and load the script:  
   `Coordinate extraction.dyn`
3. Select the target elements:
   - Use built-in selection nodes (e.g., "Select Model Elements")
   - Or automate by category/filter
4. Run the script
5. View or export the extracted XYZ coordinates

## 📤 Output Format

The output is typically a list or table with the following structure:
