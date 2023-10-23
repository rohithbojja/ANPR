# ANPR
Automatic Number Plate Recognition (ANPR) is a cutting-edge system employing specialized cameras and optical character recognition (OCR) software to automatically capture, interpret, and record license plate information from vehicles. 
# License Plate Recognition (ANPR) Pipeline

This repository contains a simple Automatic Number Plate Recognition (ANPR) pipeline using Python. Follow the steps below to get started:

## Step 1: Install Dependencies

Install the required dependencies by running the following command:

```bash
python3 -m pip install -r requirements.txt
```

## Step 2: Prepare the Input Video

Place your desired input video in the project directory. Ensure it is named "sample.mp4". You can use a video of your choice but remember to rename it as "sample.mp4."

## Step 3: Run ANPR

Execute the main ANPR script by running:

```bash
python main.py
```

This script will process the video and extract license plate information.

## Step 4: Add Missing Data

To add any missing or additional data to the recognized license plates, run the following command:

```bash
python add_missing_data.py
```

## Step 5: Visualize the Results

To visualize the ANPR results, run the following script:

```bash
python visualize.py
```

This script will display the annotated video with recognized license plates.

## Step 6: Obtain the Output

The processed video with annotated license plates will be saved as "out.mp4" in the project directory.

Feel free to explore the code and adapt it to your specific needs. Enjoy using this ANPR pipeline!
