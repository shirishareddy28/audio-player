# Audio Player Using React 

## Overview

The React-powered Audio Player App is a web-based application designed for users to effortlessly upload and play audio files. With a user-friendly interface, it offers seamless playlist management, allowing users to upload new audio files, delete specific ones, and enjoy audio playback using the standard HTML audio player.


```markdown
## Features

1. **Effortless File Upload**

   - Facilitates the easy upload of audio files, supporting formats such as mp3.
   - Implements the FileUploader component for seamless file uploads.

2. **Secure Audio Storage**

   - Utilizes built-in Browser APIs for secure storage of audio files.
   - Leverages localStorage to persistently store the playlist and individual audio files.

3. **Dynamic Playlist and Now Playing View**

   - Presents a dynamic playlist within the Playlist component.
   - Showcases an elegant now playing view through the AudioPlayer component.

4. **Intuitive Playback Control**

   - Enables users to effortlessly play any file from the playlist.
   - Ensures smooth playback transition to the next file upon completion.
   - Implements standard HTML audio player controls for an intuitive playback experience.

5. **Persistent State Management**

   - Saves the last played audio file and its position in localStorage.
   - Restores the app to the last playing audio file and continues playback from the previous position upon page reload.

6. **Utilizes Standard HTML Audio Player**

   - Incorporates the native HTML audio player for a standardized experience.
   - Avoids reliance on third-party players, ensuring simplicity and a lightweight application.

7. **Responsive Design**

   - Implements Tailwind CSS for a responsive and mobile-friendly user interface.
   - Guarantees a consistent and enjoyable user experience across a variety of devices.
```


## Installation

1. Clone the repository:

  git clone

2. Navigate to the project directory:

   ```bash
   cd audio-player-app
   ```

3. Install the dependencies:

   ```bash
    npm install
   ```

4. Start the development server:

   ```bash
   npm run dev
   ```

5. Open the browser and visit `http://localhost:5173/` to view the app.

