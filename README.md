# Simple Torrent Downloader (Google Colab + Gradio) 🚀

A straightforward tool to download torrents directly within a Google Colab environment using a simple web interface powered by Gradio. No local installation needed!

## ✨ Features

*   **Easy to Use:** Simple interface, just upload your `.torrent` file.
*   **Web UI:** Uses Gradio to provide an accessible web interface.
*   **Cloud-Powered:** Leverages Google Colab's infrastructure for downloading.
*   **No Local Software:** Runs entirely in your browser via Google Colab.
*   **Direct Download:** Downloads files to the Colab runtime's temporary storage and get your files as zip file.

## 📝 How to Use

1.  **Open the Notebook:** Click the "Open In Colab" badge above or open the provided `.ipynb` file in Google Colab.
2.  **Run the Cells:** Execute the cells in the notebook sequentially.
    *   The first cell installs necessary libraries.
    *   The subsequent cells set up the download logic and start the Gradio interface.
3.  **Get the Gradio Link:** After running the final cell, a public Gradio link (usually ending in `.gradio.live`) will be printed in the output. Click this link.
    *   Example Output: `Running on public URL: https://xxxxxxxxxxxx.gradio.live`
4.  **Access the Interface:** The link will open the Simple Torrent Downloader interface in a new browser tab.
5.  **Upload `.torrent` File:** Click the "Upload File" button/area and select the `.torrent` file you want to download from your local machine.
6.  **Start Download:** The download should start automatically once the file is uploaded.
7.  **Monitor Progress:** Check the output of the Colab cell where Gradio is running. It will typically show download progress, speed, peers, etc.
