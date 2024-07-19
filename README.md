# Folders Synchronization
Synchronizes two folders - Test Task

## Description
The Folder Synchronizer program ensures that the replica folder is always an exact copy of the source folder.

## Program and Version
- **Programming Language**: Python
- **Version**: 3.9.7
- **Development Environment**: Spyder (Anaconda 3)

## Features
- **Full Synchronization**: Makes the replica folder an identical copy of the source folder.
- **Add Files**: Copies any new files from the source to the replica.
- **Delete Files**: Removes files from the replica if they no longer exist in the source.
- **Update Files**: Updates files in the replica if they have been changed in the source.
- **Handle Subfolders**: Ensures all subfolders and their contents are synchronized.

## Usage
How to run the project:
  python sync_folders_task.py /path/to/source /path/to/replica syncInterval /path/to/logfile.log
  Note: the syncInterval must be entered in seconds

## Author:
Tânia Gonçalves

## FAQ
Q1: What happens if a file is deleted from the source folder?
A1: The file will also be deleted from the replica folder.

Q2: Are subfolders synchronized as well?
A2: Yes, all subfolders and their contents are synchronized.
