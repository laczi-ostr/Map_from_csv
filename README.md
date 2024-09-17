# Map_from_csv
Map_from_csv
WiFi Map Generator
Description

WiFi Map Generator is a Python-based tool that reads a CSV file containing WiFi data (including latitude and longitude) and generates an interactive map with markers representing each WiFi point. The map is saved as an HTML file that can be opened in any web browser.
Features

    Generates a map based on latitude and longitude from a CSV file.
    Adds markers for each WiFi point with customizable popups displaying details like SSID, AuthMode, Channel, RSSI, etc.
    User-friendly GUI for selecting input and output files.

Installation
Requirements

    Python 3.x
    pandas library
    folium library
    tkinter library (comes pre-installed with Python)

Windows Installation

    Install Python:
        Download and install Python from the official website: Python.org.
        Make sure to check the box "Add Python to PATH" during installation.

    Clone the repository:
        Open a command prompt and run:

        bash

    git clone https://github.com/your-username/wifi-map-generator.git
    cd wifi-map-generator

Install required libraries:

    Run the following command in the command prompt:

    bash

    pip install pandas folium

Run the application:

    Execute the script by running:

    bash

        python wifi_map_generator.py

Linux Installation

    Install Python:
        Most Linux distributions come with Python pre-installed. Verify it by running:

        bash

python3 --version

If Python is not installed, install it using your package manager. For example, on Ubuntu:

bash

    sudo apt update
    sudo apt install python3 python3-pip

Clone the repository:

    Open a terminal and run:

    bash

    git clone https://github.com/your-username/wifi-map-generator.git
    cd wifi-map-generator

Install required libraries:

    Run the following command in the terminal:

    bash

    pip3 install pandas folium

Run the application:

    Execute the script by running:

    bash

        python3 wifi_map_generator.py

Usage

    Open the application by running the script as described in the installation steps.
    Use the "Browse..." buttons to select the input CSV file and the output HTML file.
    Click "Create Map" to generate the map. A success message will be displayed when the map is created.
    Open the generated HTML file in your web browser to view the map.

License

This project is licensed under the MIT License. See the LICENSE file for details.
Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have any suggestions or improvements.
