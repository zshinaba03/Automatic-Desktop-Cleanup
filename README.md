# Automatic Desktop Cleanup Script
This Python script automates the organization of files on your desktop by monitoring a specified directory (e.g., Downloads) and moving files to designated folders based on their file types. It uses the watchdog library to track file changes in real-time and sorts files into pre-defined categories such as images, videos, audio, and documents.
## Features
1. Real-Time Monitoring: Automatically detects new files in the specified directory.
   
3. File Organization: Moves files into categorized folders based on their extensions:
   * Images (e.g., .jpg, .png)
   * Videos (e.g., .mp4, .avi)
   * Audio (e.g., .mp3, .wav)
   * Documents (e.g., .pdf, .docx)
     
4. Conflict Resolution: If a file with the same name already exists, the script renames the new file to avoid overwriting.
   
6. Customizable Directory Paths: Modify the source and destination directories to suit your needs.

## Usage
1. Clone the repository
   
3. Install the required dependencies: pip install watchdog
   
5. Update the source_dir and destination directories in the script to match your file paths.
   
7. Run the script: python desktop_cleanup.py
   
9. The script will run in the background, automatically organizing your files as they are downloaded or created.
