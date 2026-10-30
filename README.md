# Project Music

Project Music is a personal music player and lyrics companion that connects to Spotify and displays synchronized lyrics in a local web interface.

It brings playback information, lyric timing, and optional lyric enhancements together in one place. The project is independently developed and is not affiliated with or endorsed by Spotify.

## Features

- Connects to Spotify to display the current track and playback state.
- Shows synchronized lyrics from supported lyric sources.
- Supports line-synchronized lyrics (Linesync) and word-synchronized lyrics (Richsync) where the source provides timing data.
- Imports local TTML and LRC lyric files.
- Displays available lyric translations and pronunciation guides when those enhancements are available.
- Supports switching between available lyric sources for a track.

Lyrics and timing availability depend on the selected source and track. Project Music does not guarantee that every track has Richsync data, translations, or pronunciation guides.

## Technology

- Node.js server
- HTML, CSS, and vanilla JavaScript
- Python utilities for local lyric translation and pronunciation workflows
- Spotify Web API integration

## Lyrics and data sources

Project Music currently includes lyric lookup and fallback paths for supported sources such as Unison, BetterLyrics, and LRCLIB, as well as local lyric imports.

TTML and LRC files can be imported locally. Richsync or Linesync behavior depends on the timing data present in the file.

**lrc.red is not currently integrated as an automatic lyric provider.** Any future integration will depend on confirming the service’s requirements and configuring the project’s identity and contact information.

Lyrics are provided by their respective sources and rights holders. Project Music does not claim ownership of lyric content.

## Personal project

Project Music is maintained as a personal development project. It is provided as-is, without guarantees of availability or compatibility.

## Contact

Project maintainer: [qazmlpk12](https://github.com/qazmlpk12)

Project page: [Project Music on GitHub](https://github.com/qazmlpk12/Project-Music-Info)
