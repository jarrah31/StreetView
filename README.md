# Google StreetView API Publish

This project helps you publish and view Google StreetView photosphere photos onto Google Maps.

Unlike the Google Maps app, publishing photospheres without an associated listing is possible, and if you do choose a listing, it won't snap the blue dot to that location.

Features include:
- Local web server presenting a web GUI to interact with the API
- Publish photosphere to Google Maps
- View all your photospheres, showing their viewcount, publish and capture dates, and place names.
- Edit existing photosphere maps by changing it's location and placeID.
- Delete your photosphere

You will need:
- To create a Google Cloud Developer Project
- Create an API Key and OAuth 2.0 Client IDs. 
- Add your credit card for API billing. (tbh I haven't been charged yet because I think interacting with your own photos doesn't cost anything, and Google lets you spend up to $200 for free a month anyway. Don't hold me to this though!)
- Run this Python script within a venv environment on your local machine

The following instructions are a work in progress...

## Python Virtual Environment Setup Guide

This README provides instructions on how to set up a Python virtual environment (venv) on macOS and Windows.

### macOS

1. Open your terminal.

2. Navigate to the project directory:
    ```bash
    cd /path/to/your/project
    ```

3. Check your Python version by typing:
    ```bash
    python3 --version
    ```
    This command should return Python 3.5 or higher. If not, you'll need to install a more recent version of Python.

4. To create a virtual environment, use the following command:
    ```bash
    python3 -m venv venv
    ```
    Replace `venv` with the name you wish to give to your virtual environment.

5. To activate the virtual environment, type:
    ```bash
    source venv/bin/activate
    ```
    Again, replace `venv` with the name of your virtual environment.

Now, you're inside your Python virtual environment!

### Windows

1. Open the Command Prompt.

2. Navigate to the project directory:
    ```cmd
    cd \path\to\your\project
    ```

3. Check your Python version by typing:
    ```cmd
    python --version
    ```
    This command should return Python 3.5 or higher. If not, you'll need to install a more recent version of Python.

4. To create a virtual environment, use the following command:
    ```cmd
    python -m venv venv
    ```
    Replace `venv` with the name you wish to give to your virtual environment.

5. To activate the virtual environment, type:
    ```cmd
    venv\Scripts\activate
    ```
    Again, replace `venv` with the name of your virtual environment.

Now, you're inside your Python virtual environment!

Remember to always activate the virtual environment whenever you're working on your project. When you're done, you can leave the virtual environment with the `deactivate` command. 


