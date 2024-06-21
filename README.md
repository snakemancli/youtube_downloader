# SnakemanCLI - Bulk Video Downloader

This module bulk downloads videos from YouTube using a specified keyword and processes them into smaller clips. Only tested on Arch and Gentoo.

## License

This project is licensed under the Zero-Clause BSD license. See the [LICENSE](LICENSE) file for more details.

## Requirements

- Python 3.x
- google-api-python-client
- yt-dlp
- moviepy
- ffmpeg-python

## Setup

### Using a Virtual Environment

It is recommended to use a virtual environment to manage dependencies. Follow these steps to set up the project:

1. **Create a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate
   pip install google-api-python-client yt-dlp moviepy ffmpeg-python
   export YOUTUBE_API_KEY=your_api_key_here
Usage
To bulk download and process videos:

bash
Copy code
python video_downloader.py [keyword]
# keyword: The keyword to search for on YouTube (optional). If not provided, you will be prompted to enter it.
