ruby
Copy code
# Audio Metadata Updater

This Python script updates the metadata of WAV audio files, specifically the "Title" and "Track Number" fields, to match their file names (without the file extension). The updated files are saved in a separate output folder, preserving the original files in the input folder. This can be particularly useful for managing large collections of audio files, ensuring consistency in their metadata.

## Prerequisites

Before you begin, ensure you have the following installed on your machine:

- Python 3.x
- `taglib` library

## Installation

To install the `taglib` library, run the following command:

pip install python-taglib

r
Copy code

## Usage

1. Download the `audio_metadata_updater.py` script from this repository.
2. Modify the `input_folder` and `output_folder` variables in the script to match the desired source and destination folders for your audio files. For example:

```python
input_folder = "C:\\path\\to\\your\\input\\folder"
output_folder = "C:\\path\\to\\your\\output\\folder"
Run the script using the following command:
Copy code
python audio_metadata_updater.py
The script will process the WAV files in the input_folder, update their metadata, and save the updated files in the output_folder. The original files in the input_folder will remain unchanged.
Notes
This script is designed to work with WAV files only. Other audio formats may not be compatible.
Ensure you have read and write permissions for both the input_folder and output_folder.
The script assumes that the file names are in the format "1.wav", "2.wav", etc., and will update the metadata accordingly. If your files are named differently, you may need to modify the script to suit your specific naming convention.
License
This project is licensed under the terms of the MIT license. See the LICENSE file for details.

javascript
Copy code

You can save this content as `README.md` in your project's root folder, and it will appear on you
