# Lyric Website
Create a simple lyric website based on Flask.

创建一个基于Flask 框架的简易歌词网站。

## Data Models

Artist
* ID
* Title
* Avatar
* Albums (1 to Many relationship)

Album
* ID
* Title
* Cover (image url)
* Tracks (1 to Many relationship)
* ArtistID (Foreign Key)

Track
* ID
* Title
* Content
* AlbumID (Foreign Key)

## Views

Artist Page
* Show basic info of a single Artist
* Show album list of a single Artist

Album Page
* Show basic info of a single Album
* Show track list of a single Album
* Show the link to the Artist for this Album

Track Page
* Show lyric content of a single Track
* Show the link to the Album for this Track
* Show the link to the Artist for this Track

## Advanced Features
* Amin
* Search
* Cache

This will be much simplified version of [Mulanci](https://www.mulanci.org/)

参照歌词网：[木兰词 Mulanci.org](https://www.mulanci.org/)
