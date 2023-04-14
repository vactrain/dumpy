# Dumpy
This is a simple GitHub Actions workflow that retrieves the Pixel Factory image specified in the 'temp' file, extracts its boot image, and uploads it as an artifact.

## Usage
To use this workflow, you need to specify the direct download URL for your preferred Pixel device factory image in the 'temp' file. The Pixel images can be found over at https://developers.google.com/android/images.

Once you have updated the 'temp' file with your desired URL, simply trigger the workflow, and it will automatically retrieve the factory image, extract the boot image, and upload it as an artifact.

The artifact can be accessed by clicking on the "Artifacts" tab in the GitHub Actions interface.

## Contributions
Contributions to this workflow are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or a pull request.