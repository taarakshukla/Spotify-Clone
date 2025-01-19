# Spotify Clone - Web-based Music Player

## Project Overview
A web-based music player resembling Spotify that provides the following features:

- **Core Functionalities**: Play, pause, next song, and actual playback functionalities, ensuring seamless user interaction.
- **Responsive Design**: Developed with a responsive layout and hamburger menu for improved mobile usability.
- **Folder Detection**: Automatically organizes albums based on the folder structure, enhancing user experience and navigation.



## Tech Stack
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: None (purely client-side)
- **Tools**: Any modern browser for testing and deployment

## Setting Up the Songs Folder

To organize your music collection and ensure the player works as intended, follow these steps:

### Folder Structure
1. Navigate to the `songs` folder in the project directory.
2. Create a new folder for each album or song category (e.g., `Pop`, `Rock`, `Classical`).
3. Inside each folder:
   - Add a `cover.jpg` file. This image will serve as the cover photo for the album.
   - Create a file named `info.json` with the following format:

```json
{
  "title": "Album Title",
  "description": "A brief description of the album or song category."
}
```

4. Add the audio files (.mp3) for the album inside the same folder.

### Example
If you want to create an album for `Jazz` songs:

#### Folder Structure
```
songs/
  Jazz/
    cover.jpg
    info.json
    song1.mp3
    song2.mp3
    song3.mp3
```

#### `info.json` Example
```json
{
  "title": "Smooth Jazz Collection",
  "description": "A relaxing collection of smooth jazz tracks."
}
```



## Features

### 1. Music Playback
- Play and pause songs effortlessly.
- Navigate between songs using the next button.
- Real-time playback updates.

### 2. Responsive Design
- Optimized for both desktop and mobile devices.
- Hamburger menu for enhanced navigation on smaller screens.

### 3. Automatic Album Organization
- Detects folders in the `songs` directory and organizes albums automatically.
- Displays album cover and description dynamically.


## How to Use
1. Clone this repository to your local machine using the following command:

```bash
git clone https://github.com/taarakshukla/Spotify-Clone.git
```
2. Place your organized music folders in the `songs` directory following the structure described above.
3. Open the project in your browser to enjoy your music collection.


## Future Improvements
- Adding a search functionality to quickly locate songs or albums.
- Creating playlists and saving user preferences.
- Streaming support for online music.


