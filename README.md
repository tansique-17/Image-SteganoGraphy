# Image-Stegano-Graphy
Here’s the final draft of your `README.md`:

This Python-based GUI application allows users to encode secret messages into images and decode hidden messages from images using steganography. The application is built with the `tkinter` library and supports common image formats like PNG, JPEG, and JPG.

---

## Features
- **Encode Messages**: Hide a secret message within an image.
- **Decode Messages**: Extract hidden messages from an image.
- **User-Friendly Interface**: Simple GUI with easy-to-follow steps.
- **Image Support**: Works with `.png`, `.jpeg`, and `.jpg` image formats.
- **ASCII Art**: Fun ASCII art included in the GUI for aesthetics.

---

## Requirements

- Python 3.6 or higher
- The following Python libraries:
  - `Pillow`

You can install the required libraries using:
```bash
pip install -r requirements.txt
```

**Note:**  
- `tkinter` is a standard library module and should already be installed with Python on most systems.  
- If you're using Linux and encounter issues, install `tkinter` manually using your package manager:
  ```bash
  sudo apt-get install python3-tk
  ```

---

## Usage

### Run the Application
1. Clone this repository or download the script.
2. Execute the script using Python:
   ```bash
   python steganography.py
   ```

### Encoding a Message
1. Click on **Encode** in the application.
2. Select the image where you want to hide a message.
3. Enter the message in the provided text box.
4. Save the resulting image file.

### Decoding a Message
1. Click on **Decode** in the application.
2. Select the image with the hidden message.
3. The hidden message will be displayed in a text box.

---

## Application Overview

The application uses steganography techniques to encode text into the least significant bits of an image's pixel data. When decoding, it extracts and reconstructs the message from the pixel data.


## Known Issues and Limitations
- Large messages might exceed the capacity of smaller images.
- Only supports 24-bit color images.
- Does not support animated images or transparency channels.

---

## License
This project is licensed under the [MIT License](LICENSE).

---

## Author
Created by **[Tansique Dasari](https://github.com/Tansique-17)**.  

Feel free to contribute or raise issues in the repository!
```
