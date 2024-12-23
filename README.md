# Color-Detection-Model
# Color Detection Model with RGB Values

## Overview

This repository contains a simple color detection model that identifies colors in an image based on their RGB (Red, Green, Blue) values. The model uses computer vision techniques to analyze an input image and extract the dominant colors present.

## Features

- **RGB Color Detection:** The model extracts RGB values from the image and identifies the dominant colors.
- **User-friendly Interface:** The provided script can be easily integrated into your projects or used as a standalone tool with a user-friendly interface.

## Getting Started

### Prerequisites

- Python 3.x
- OpenCV
- Numpy

Install the required dependencies using the following command:

```bash
pip install opencv-python numpy
```

### Usage

1. Clone the repository to your local machine:

```bash
git clone https://github.com/mynkchaudhry/Color-Detection-Model.git
```

2. Navigate to the project directory:

```bash
cd color-detection
```

3. Run the color detection script:

```bash
python color_detection.py --image path/to/your/image.jpg
```

Replace `path/to/your/image.jpg` with the path to the image you want to analyze.

4. The script will display the dominant colors along with their RGB values.

## Example

```bash
python color_detection.py --image samples/sample_image.jpg
```

Output:

![output](/output.png)


