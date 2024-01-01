         _    ____   ____ ___ ___ _____                   
        / \  / ___| / ___|_ _|_ _|_   _|___ _ __ _ __ __  
       / _ \ \___ \| |    | | | |  | |/ _ | '__| '_ ` _ \ 
      / ___ \ ___) | |___ | | | |  | |  __| |  | | | | | |
     /_/   \_|____/ \____|___|___| |_|\___|_|  |_| |_| |_|
         ASCIITerm - NDI Viewer for Terminal Windows  
Display NDI Video as ASCII Output in Terminal

## Description
`ASCIITerm.py` is a Python script for rendering video frames as ASCII art live in Terminal. 

This allows you to watch any movie or other recording in full, text-based glory.

This is designed to provide a "graphics" driver to old serial terminals, inspired by this project:
https://www.youtube.com/watch?v=xQTr9ZOJkC0

It uses OpenCV for image processing, NumPy for numerical operations, and NDIlib for network device interface capabilities.

## Setup
1. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```
2a. Run the script with default resolution of 80 columns and 24 rows:
   ```
   python ASCIITerm.py
   ```
2b. Run the script with a custom column and row resolution:
   ```
   python ASCIITerm.py 100 30

   ```

## Usage

