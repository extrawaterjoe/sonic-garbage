# sonic-garbage

**All credit goes to [Colugo](https://twitter.com/ColugoMusic)**

## Overview

The YouTube Audio Downloader is a Python script that automates the process of generating audio samples from YouTube videos. It randomly selects search phrases from a provided word list, downloads corresponding YouTube videos, and processes the audio to create one-shot and looped versions. The processed audio files are then saved in designated directories.

## Features

- **Random Search Phrases:** The script generates random search phrases by selecting two words from a provided word list.
- **YouTube Video Download:** Utilizes the `yt_dlp` library to download YouTube videos based on the generated search phrases.
- **Audio Processing:** Creates both one-shot and looped versions of the downloaded audio, applying fade-in, fade-out, and normalization.
- **Batch Processing:** Executes the entire process in batches, allowing for the creation of multiple audio samples in one run.

## Prerequisites

- Python 3
- Required Python libraries (`pydub`, `yt_dlp`, `isodate`)
- FFmpeg (See [FFmpeg Installation](https://ffmpeg.org/download.html))

## Usage

1. Clone the repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the script using `python sonic-garbage.py`.
4. Check the `wavs/processed/loop` and `wavs/processed/oneshot` directories for the processed audio files.

## Disclaimer

Please ensure that your use of this script complies with YouTube's terms of service. Downloading YouTube videos may be subject to legal and ethical considerations.
