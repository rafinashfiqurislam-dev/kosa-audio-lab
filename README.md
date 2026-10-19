# KOSA Audio Lab

A funny, math-themed, browser-based audio mixer.

## Files
- `index.html` — the complete website (HTML, CSS, and JavaScript in one file).

## Use it on your computer
1. Open `index.html` in a modern browser.
2. Upload the first audio file under **Kosaman Music**.
3. Upload the second audio file under **Sona Baba Music**.
4. Adjust volumes and the second voice's start time.
5. Click **Create the chaos**, preview the mix, then click **Download mix (.wav)**.

Audio is processed in the browser; this page does not upload the audio to a server.

## Publish with GitHub Pages
1. Create a GitHub repository.
2. Upload `index.html` to the repository's root and name it exactly `index.html`.
3. In the repository, open **Settings → Pages**.
4. Under build/deployment, choose **Deploy from a branch**, select your main branch and `/ (root)`, then save.
5. Wait for GitHub Pages to publish the site; the Pages section will show the website URL.

## Audio files
The site lets visitors choose audio files from their own device. You do not need to upload the audio files into the repository unless you specifically want to distribute them publicly. If you do upload them, anyone with access to the repository may be able to download them. Only share recordings you have permission to use.

## Notes
- Uses browser-supported audio formats (commonly MP3, WAV, and M4A; support can vary by browser).
- The combined output is a stereo 16-bit WAV file.
- Large or long audio files may take longer to process, especially on phones.
