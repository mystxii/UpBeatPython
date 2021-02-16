<div align="center">
  <img src="https://media.discordapp.net/attachments/810107756421709827/810114469295685642/download.png" width="128px" style="max-width: 100%;">
  <h1>UpBeat Python</h1>
  <a href="https://ubpy.danieldot.xyz/discord/"><img src="https://discord.com/api/guilds/810107755943297024/widget.png?style=shield"></a> <img src="https://img.shields.io/badge/Version-V1.0-blue">
  <br>
  <b>Documentation</b>
  <br>
</div>
<br>

## upbeat.version()
Returns the UpBeat Python Module version installed.<br>Type: `str`.

## upbeat.stats.listeners()
Returns the listener count.<br>Type: `str`.

## upbeat.stats.updated()
Returns the last time the API updated.<br>Type: `str`.

## upbeat.stats.song.title()
Returns the song title.<br>Type: `str`.

## upbeat.stats.song.artist()
Returns the song artist.<br>Type: `str`.

## upbeat.stats.song.combined()
Returns the song information in the format `{title} - {artist}`.<br>Type: `str`.

## upbeat.stats.song.cover()
Returns the song cover image URL.<br>Type: `str`.

## upbeat.stats.song.mp3preview()
Returns the song MP3 preview URL.<br>If there is none, it will return `Not Available`<br>Type: `str`.

## upbeat.stats.song.spotifyid()
Returns the Spotify ID.<br>If there is none, it will return `Not Available`<br>Type: `str`.

## upbeat.stats.song.likes()
Returns the number of likes the song has.<br>Type: `str`.

## upbeat.stats.song.dislikes()
Returns the number of dislikes the song has.<br>Type: `str`.

## upbeat.stats.song.favourites()
Returns the number of favourites the song has.<br>Type: `str`.

## upbeat.stats.song.played()
Returns the number of times the song has been played.<br>Type: `str`.

## upbeat.stats.presenter.name()
Returns the presenter's name.<br>If AutoDJ is on, it will return `UpBeat Stream`<br>Type: `str`.

## upbeat.stats.presenter.likes()
Returns how many likes the presenter has.<br>If AutoDJ is on, it will return `Not Available`<br>Type: `str`.

## upbeat.stats.presenter.profileurl()
Returns the presenter's profile URL.<br>Type: `str`.

## upbeat.stats.presenter.avatar()
Returns the presenter's avatar URL.<br>Type: `str`.

## upbeat.stats.presenter.userid()
Returns the presenter's user id.<br>Type: `str`.

## upbeat.stats.presenter.show()
Returns true if the current slot is a weekly show.<br>Type: `str`.

## upbeat.stats.presenter.socials.snapchat()
Returns the Snapchat of the presenter.<br>If there is none, it will return `Not Available`<br>Type: `str`.

## upbeat.stats.presenter.socials.spotify()
Returns the Spotify of the presenter.<br>If there is none, it will return `Not Available`<br>Type: `str`.

## upbeat.stats.presenter.socials.twitter()
Returns the Twitter of the presenter.<br>If there is none, it will return `Not Available`<br>Type: `str`.

## upbeat.stats.presenter.socials.instagram()
Returns the Instagram of the presenter.<br>If there is none, it will return `Not Available`<br>Type: `str`.

## upbeat.stats.presenter.socials.youtube()
Returns the YouTube of the presenter.<br>If there is none, it will return `Not Available`<br>Type: `str`.

## upbeat.stats.booking.day()
Returns the day of the current slot in UTC.<br>Type: `str`.

## upbeat.stats.booking.hour()
Returns the hour of the current slot in UTC.<br>Type: `str`.

## upbeat.stats.booking.combined()
Returns the slot information in the format `{day} at {hour}`.<br>Type: `str`.
