# KK_DL_PYTHON
Reason for Checking Pixel Data in DICOM Images:
=================================
Image Integrity: Ensure the image isn’t corrupted and the pixel values fall within expected ranges.
Modality-Specific Values: Pixel values vary by modality (e.g., CT uses Hounsfield Units, MRI uses signal intensity).
Rescale Slope/Intercept: Apply these to convert raw pixel data to meaningful values (e.g., HU in CT).
Pixel Spacing: Verify physical spacing between pixels for accurate measurements.

This code is base fundamental checking of pixel data is available in your dataset
