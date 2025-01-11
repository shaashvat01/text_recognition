# Image Text Recognition

A Python-based project leveraging OpenCV and EasyOCR to detect and extract text from images. The project identifies text regions in an image, highlights them with bounding boxes, and displays the extracted text along with confidence scores. It is a simple yet powerful demonstration of computer vision and text recognition capabilities.

## Features
- Detect and extract text from images.
- Highlight detected text regions with bounding boxes.
- Display confidence scores for recognized text.
- Easy-to-use and customizable.

## Technologies Used
- **Python**: Core programming language.
- **OpenCV**: For image processing and visualization.
- **EasyOCR**: For Optical Character Recognition (OCR).
- **Matplotlib**: For displaying the processed image.

## Prerequisites
Before you start, ensure you have the following installed:
- Python 3.7+
- pip (Python package manager)

## Installation
1. Clone the repository:
   ```bash
   git clone <repository-link>
   cd <repository-folder>
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Place your test images in the `testing/` folder.
2. Update the `image_path` variable in `main.py` to point to your test image:
   ```python
   image_path = 'testing/your_image.jpg'
   ```
3. Run the script:
   ```bash
   python main.py
   ```
4. The script will:
   - Detect text in the specified image.
   - Highlight text regions with bounding boxes.
   - Display the processed image.
   - Print the detected text and their confidence scores in the terminal.

## Example Output
An example of the processed image with highlighted text regions and bounding boxes will be displayed. The terminal will output detected text along with confidence scores.

## Future Improvements
- Add support for multiple languages using EasyOCR.
- Implement GPU acceleration for faster processing.
- Enhance the visualization with advanced bounding box styles.
- Allow batch processing of multiple images.

## Contributing
Contributions are welcome! Feel free to submit issues or pull requests to improve the project.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Start extracting text from images today! If you find this project useful, give it a ⭐ on GitHub!