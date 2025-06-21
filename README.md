# Camera to Gemini

A simple Python program that listens for keyboard input and captures images from your camera to send to the Gemini API for analysis.

## Features

- Listens for any keyboard input
- Captures images from your default camera when a key is pressed
- Sends images to the Gemini API endpoint for analysis
- Displays the API response in the console
- Simple and error-resistant design

## Setup

1. **Install Python dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

2. **Make sure your camera is connected and working**

## Usage

1. **Run the program:**
   ```bash
   python camera_listener.py
   ```

2. **The program will:**
   - Initialize your camera
   - Start listening for keyboard input
   - Display status messages in the console

3. **Press any key to:**
   - Capture an image from your camera
   - Send it to the Gemini API
   - Display the analysis response

4. **Exit the program:**
   - Press `Ctrl+C` to safely shut down

## Notes

- The program uses your default camera (usually camera index 0)
- Images are captured at 640x480 resolution
- Each key press triggers a new image capture and API request
- The program prevents multiple simultaneous requests to avoid overloading
- All errors are handled gracefully with informative messages

## Troubleshooting

- **Camera not working**: Make sure no other applications are using your camera
- **API errors**: Check your internet connection and the API endpoint status
- **Permission errors**: On some systems, you may need to grant camera permissions 