# Detection of Sarcoptic Mange in Dogs Using Artificial Intelligence

This is a project for detecting sarcoptic mange in dogs using artificial intelligence. The project consists of a frontend that interacts with a JavaScript API, developed with the Express.js framework, to send requests to the Python API responsible for performing the detection.

## Prerequisites

- Python 3.x installed on your computer.
- Pip package installed in Python.
- Basic knowledge of Python and command line/terminal.

## Installation

Follow the steps below to set up the project on your computer:

1 - Clone or download this repository to your computer.

2 - In the terminal or command prompt, navigate to the project directory.

3 - Create a virtual environment to isolate the project dependencies:

   On Windows:
   ```
   mkdir myproject
   cd myproject
   py -3 -m venv .venv
   ```

   On Linux/Mac:
   ```
   mkdir myproject
   cd myproject
   python3 -m venv .venv
   ```

4. After creating the virtual environment, move the files contained in this repository to the .venv folder.

5. Activate the virtual environment:

   On Windows:
   ```
   .venv\Scripts\activate
   ```

   On Linux/Mac:
   ```
   source .venv/bin/activate
   ```

6. Install the project dependencies:

   ```
   pip install -r requirements.txt
   ```

## Configuration

1. Open the file function.py located in the .venv folder.

2. On line 27 of the file, change the path to the dogHealthClassifier.h5 file to the correct path on your system.

## Execution

Important: do not execute the main.py file, as this will cause the system to not function properly.

After completing the installation and configuration, execute the following command in the terminal or command prompt to start the Flask server:

```
python function.py
```

The Flask server will start and will be ready to receive requests.

Next, execute the front-end to use this API.

