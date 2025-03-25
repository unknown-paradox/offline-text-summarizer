# Offline Text Summarizer

An offline text summarizer application built with Python and Tkinter. The tool uses the `facebook/bart-large-cnn` model from the Hugging Face Transformers library to generate concise summaries of longer texts.

## Features
- Summarizes text input offline.
- Customizable summary length.
- User-friendly interface using Tkinter.

## Installation

### Requirements:
1. **Python 3.6+**
2. **Tkinter** (UI)
3. **Transformers** (for model)

### For macOS Users:
If you prefer to use the precompiled `.app` version, you can download the latest release from the [Releases section](https://github.com/yourusername/offline-text-summarizer/releases).

**Important Note for macOS Users:**
Since this `.app` file is **not signed** with an official Apple developer certificate, macOS will prevent it from running by default due to security settings. You will need to allow the app to open by following these steps:

1. **Download the `.app` file from the Releases section**.
2. **Double-click the `.app` to try to open it**.
3. **If you see a warning message** saying the app can't be opened because it is from an unidentified developer, follow these steps:
    - Go to **System Preferences** > **Security & Privacy**.
    - Under the **General** tab, look for a message about the blocked app.
    - Click **Open Anyway**.
    - You may need to enter your **administrator password**.
    - After that, you should be able to run the app.
   
   **Note:** Please be patient as the app may take a few seconds to open. If the app doesn't open immediately, give it a moment to load and start.

### For Windows/Linux Users:
1. Clone the repository and install dependencies as described above.
2. Run the application using the `python app.py` command.

## Usage
1. Enter the text you want to summarize into the input field.
2. Click **Generate Summary** to see the output summary.
3. You can click **Clear** to reset the input and output fields.

## Release Information
- **Version 1.0.0**: First stable release with basic summarization functionality and offline capability.

## License

This project is licensed under the **CC0 1.0 Universal (CC0 1.0) Public Domain Dedication**. You can use, modify, and distribute the project without any restrictions.

See the [LICENSE](LICENSE) file for more details.
