# Vehicle Detection and Counting System

## Overview
This is a real-time vehicle detection and counting system built with Python, OpenCV, and Flask. The application detects and counts vehicles using computer vision techniques and provides a web-based interface for monitoring.

## Current State
- ✅ Successfully converted from desktop OpenCV application to web-based Flask application
- ✅ Working demo mode with simulated vehicle detection when camera is not available
- ✅ Web interface running on port 5000
- ✅ Real-time vehicle counting with statistics display
- ✅ Flask server properly configured with CORS support
- ✅ Deployment configured for autoscale

## Project Architecture
- **Backend**: Flask web server with OpenCV processing
- **Frontend**: HTML/CSS/JavaScript interface with live video streaming
- **Computer Vision**: MOG2 background subtraction for vehicle detection
- **Demo Mode**: Synthetic vehicle simulation when camera unavailable

## Recent Changes (Sept 17, 2025)
- Created Flask web application (app.py) from original OpenCV desktop app (main.py)
- Added HTML template with real-time statistics and video streaming
- Implemented demo mode with synthetic moving vehicles
- Set up workflow to run on port 5000 with webview output
- Configured deployment for autoscale mode
- Added requirements.txt with all dependencies

## Technical Features
- **Real-time Processing**: ~30 FPS video processing and streaming
- **Multi-threaded**: Separate threads for video processing and web serving
- **Responsive Design**: Clean web interface with live statistics
- **Auto-fallback**: Switches to demo mode when camera unavailable
- **REST API**: Stats endpoint for vehicle count and active tracks
- **Reset Functionality**: Ability to reset counter via web interface

## Dependencies
- opencv-python==4.8.1.78
- numpy==1.24.3
- matplotlib==3.7.2
- flask==2.3.3
- flask-cors==4.0.0

## User Preferences
- Web-based interface preferred over desktop application
- Real-time streaming and statistics display
- Clean, professional UI with vehicle counting visualization