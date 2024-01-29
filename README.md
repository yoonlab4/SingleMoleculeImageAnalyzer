# SingleMoleculeImageAnalyzer


Follow these steps to use the analyzer:

1. Run trotsky.m

2. Load Image Files or Folder to Analyze
 - Ensure your input images are 512x512 pixel uint8 CCD images in *.tif format.
 - If organizing images in folders, create an outer folder and load it for analysis.
 - For co-localization analysis, create a reference map aligning the left and right windows.

3. Set Analysis Options
 - Imag. for Peak Finding: Define the area of your image for analysis. The left half (256x512) is recognized as Donor, and the right half (256x512) is recognized as Acceptor.
 - Mask Type: Choose a mask type to match the Point Spread Function (PSF) in your image.
 - Peak Finding: Detect PSF peaks with specified settings.
 - Background: Set background level to median or a fixed value.a
 - Image Display: Adjust dynamic range for donor and acceptor images.
 - Output: Save results in a subfolder or extract time traces. Uncheck "Extract time trace" for count and intensity only.

4. Process Data
 - Click "Process all" to initiate data processing.

5. Extract Statistics Data
 - Use "Show statistics" to view overall statistics in subfolders.
 - Check the graph in the new window and inspect raw count and intensity data in txt format.

Written by SHL, 24.01.29.
