# MP3 Media Player

![Media Player Window](https://user-images.githubusercontent.com/91011302/225108873-ad187cd6-6790-4a17-b5be-83b4cab1c914.png)

## Overview

The MP3 Media Player is a JavaFX application designed to provide users with a user-friendly and visually appealing interface for playing MP3 audio files. It offers essential features such as play, pause, stop, skip, and volume control. The application is developed to ensure smooth playback of locally stored MP3 files, delivering a seamless and efficient user experience.

## Features

- **Play:** Allows users to play MP3 audio files.
- **Pause:** Allows users to pause playback of MP3 audio files.
- **Stop:** Stops playback of the currently playing MP3 audio file.
- **Skip:** Enables users to skip to the next or previous MP3 audio file in the playlist.
- **Volume Control:** Users can adjust the volume level of the audio being played.

## Interface

The interface of the MP3 Media Player is designed to be intuitive and visually appealing. It consists of the following components:

- **Song Label:** Displays the name of the currently playing MP3 audio file.
- **Play Button:** Initiates playback of the MP3 audio file.
- **Pause Button:** Pauses the playback of the MP3 audio file.
- **Reset Button:** Resets the playback of the MP3 audio file to the beginning.
- **Next Button:** Skips to the next MP3 audio file in the playlist.
- **Previous Button:** Skips to the previous MP3 audio file in the playlist.
- **Speed Selector:** Allows users to adjust the playback speed of the audio.
- **Volume Slider:** Enables users to control the volume level of the audio.
- **Progress Bar:** Indicates the progress of the currently playing MP3 audio file.

## Implementation

### Main Application Class

The `Application` class initializes the JavaFX application and sets up the primary stage with the main scene.

### Controller Class

The `Controller` class handles user interactions and manages the playback of MP3 audio files. It initializes the media player, controls playback functions, adjusts playback speed, and updates the progress bar.

### FXML File (hello-view.fxml)

The FXML file defines the layout and components of the user interface using JavaFX Scene Builder. It establishes the visual structure of the MP3 Media Player window.

## Usage

1. **Launching the Application:**
   - Run the `Application` class to start the MP3 Media Player.
2. **Playing MP3 Files:**
   - Click the "Play" button to start playback of the currently selected MP3 file.
3. **Pausing Playback:**
   - Click the "Pause" button to temporarily pause playback of the MP3 file.
4. **Stopping Playback:**
   - Click the "Stop" button to stop playback of the MP3 file.
5. **Skipping Tracks:**
   - Use the "Next" and "Previous" buttons to skip to the next or previous MP3 file in the playlist.
6. **Adjusting Volume:**
   - Drag the volume slider to adjust the volume level of the audio.
7. **Changing Playback Speed:**
   - Select a playback speed from the dropdown menu to adjust the speed of audio playback.

## Dependencies

- JavaFX: Required for building the graphical user interface.
- MediaPlayer: Used for playing MP3 audio files.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please read the [CONTRIBUTING.md](CONTRIBUTING.md) file for details on how to contribute to this project.

## Conclusion

The MP3 Media Player provides a simple yet effective solution for playing MP3 audio files with essential playback controls and an intuitive user interface. It aims to enhance the user experience of listening to music on a desktop environment while maintaining a visually appealing design.

---

*This project is licensed under the [MIT License](LICENSE).*
