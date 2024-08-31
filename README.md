# Project Title: Hand Gesture-Based Drawing Application

## Description

This project is a hand gesture-based drawing application that allows users to create digital artwork using hand movements tracked by a webcam. Leveraging computer vision techniques, this interactive application provides an intuitive and fun way to draw colorful patterns and designs on a canvas.

## Key Features

### Hand Tracking

- The application utilizes the MediaPipe library to accurately track the user's hand movements in real-time.

### Gesture Recognition

- Users can interact with the drawing canvas by performing specific hand gestures. Key gestures include:

  - **Multiple Color Selection**: By positioning the hand over predefined color zones, users can switch between different colors (teal, yellow, purple, and green).
  - **Canvas Clear**: A "CLEAR" button gesture erases the canvas, providing a clean slate for new artwork.

### Drawing Canvas

- A canvas is displayed on the screen where users can draw with their hands. The application records and displays drawings in real-time.

### Flexible Drawing

- Users can draw freehand on the canvas by moving their hand in various directions, creating colorful strokes and patterns.

## Technical Stack

- **Python**: The project is implemented in Python, utilizing its extensive libraries and tools for computer vision and user interface development.
- **OpenCV**: Used for webcam access, video frame manipulation, and rendering.
- **NumPy**: Employed for efficient array operations and data handling.
- **MediaPipe**: The backbone for hand tracking and landmark detection.
- **Deque**: Deques are used for managing and storing the coordinates of drawing points.
- **GitHub**: The project is hosted on GitHub, providing version control, collaboration, and code sharing.

## Usage

This project can be used as an interactive educational tool, an art creation platform, or a demonstration of hand gesture recognition and computer vision concepts. Users can explore their creativity by drawing with their hands in a novel and engaging way.

## How to Run?

### Prerequisites

- Python installed on your system.
- Required Python libraries (OpenCV, NumPy, and MediaPipe) installed. You can install them using pip if not already installed.

