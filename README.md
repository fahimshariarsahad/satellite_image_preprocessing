# satellite_image_preprocessing
The objective is to analyze Sentinel-2 satellite images for differentiating vegetation types using spectral signatures for environmental monitoring and data extraction.

## Executive summary

Project involves tools such as NumPy, Pandas, Matplotlib, scikit-image, OpenCV, and Rasterio were used to process TIFF and JP2 files. Preprocessing involved normalization, resizing, and splitting images into fragments for model building.


## Technical overview

Below I outline briefly the main steps in the workflow that i have done with the  Jupyter notebook.

| Task | Summary |
| --- | --- |
| Image acquisition | Obtained Sentinel-2 satellite images from [Copernicus]([https://www.copernicus.eu/en]) in TIFF and JP2 formats. |
| Feature extraction | Preprocessing Normalization, resizing, and fragmenting the images for analysis. |
| Extracted spectral signatures | Extracted spectral signatures from the satellite images of different bands including B02, B04, B08, TCI, WVP etc. |
| Model building | Data splitting	Divided the dataset into 80% training and 20% testing data. |






## Future work

for future work there is still many things we can work on, for now these issues could be addressed by:

* Acquiring more diverse satellite imagery,
* Extracting additional features that may enhance image processing,or
* More ways to visualize and analyze the satellite image to find more valuable insights.
