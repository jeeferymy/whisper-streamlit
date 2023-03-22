# Whisper with Streamlit UI
This project is a tool that was developed as part of a Master's thesis in cooperation with the University Clinic of Psychoanalysis and Psychotherapy of Vienna. It is based on the Whisper automatic speech recogniton system and is embedded into a Streamlit Web App. 

## Features

- Pause detection: The tool can detect pauses in the audio.
- Speaker detection: The tool can also detect different speakers in the audio and label them accordingly.
- Streamlit UI: The tool includes a user-friendly interface that allows you to upload multiple audio files and get a nicely formated transcript.

## Data Privacy

- Whisper is used locally as well as offline (no internet connection needed)
- Nothing is being uploaded to the cloud
- Therefore safe clinical use 

## User Interface

![Up![streamlit_2](https://user-images.githubusercontent.com/65357373/226928411-82b9731d-9463-4924-add4-09b3b0d9f590.png)
![streamlit_2](https://user-images.githubusercontent.com/65357373/226928478-94adfbd5-414c-4a05-965d-3cde6c1c26fc.png)

## Getting Started

To use this tool, you will need to install the required dependencies and run the Streamlit app. You can do this by following these steps:

1. Clone the repository: git clone https://github.com/your-repo
2. Install dependencies: pip install -r requirements.txt
3. Run the Streamlit app: streamlit run Transcribe.py (you can also launch it from a desktop shortcut following these instructions: https://discuss.streamlit.io/t/launching-streamlit-webapp-from-desktop-shortcut/26297)

## How to Use

1. Upload one or multiple audio files 
2. Select a model (large for the best result) and set additional parameters 
3. Download the resulting transcript

## Contact

If you have any questions or feedback about this project, please feel free to contact us by email at johanna.jaeger89@icloud.com.

## Sources

This project includes code from multiple different sources, each licensed under the MIT License:

* [Source A] (https://github.com/openai/whisper)
* [Source A] (https://github.com/pyannote/pyannote-audio)
* [Source C] (https://github.com/hayabhay/whisper-ui)

See the LICENSE file for the full text of the licenses.
