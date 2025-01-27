  <p align="center">
  <a href="https://github.com/SpotX-CLI/SpotX-Linux"><img src="https://raw.githubusercontent.com/SpotX-CLI/SpotX-commons/main/.github/Pic/Logo/logo-linux.png" />
</p>

<p align="center">        
      <a href="https://t.me/spotify_windows_mod"><img src="https://raw.githubusercontent.com/SpotX-CLI/SpotX-commons/main/.github/Pic/Shields/tg.svg"></a>
      <a href="https://discord.gg/p43cusgUPm"><img src="https://discord.com/api/guilds/807273906872123412/widget.png"></a>
      </p>

***

<center>
    <h4 align="center">A multi-featured adblocker for the Spotify Linux application.</h4>
    <p align="center">
        <strong>Last updated:</strong> 20 January 2023<br>
        <strong>Last tested version:</strong> 1.2.3.1115
    </p> 
</center>

### Features:

- Blocks all banner/video/audio ads within the app
- Blocks logging (Sentry, etc)
- Unlocks the skip function for any track
- Blocks Spotify automatic updates (optional)
- Enables [experimental features](https://github.com/SpotX-CLI/SpotX-Win/discussions/50) (optional)
- Hides podcasts, episodes and audiobooks on Home Screen (optional)

### Installation/Update:

NOTE: SpotX does not support the Spotify client from Snap 
- Close Spotify completely.
- Run The following command in Terminal:

```
bash <(curl -sSL https://raw.githubusercontent.com/SpotX-CLI/SpotX-Linux/main/install.sh)
```

#### Optional Install Arguments:
`-c`  Clear app cache -- use if UI-related patches aren't working  
`-e`  Experimental features -- enables experimental features  
`-E`  Exclude feature -- disables specified feature(s) [currently disabled]  
`-f`  Force patch -- forces re-patching if backup detected  
`-h`  Hide podcasts, episodes and audiobooks on home screen  
`-o`  Old UI -- skips forced 'new UI' patch  
`-P`  Path directory -- manually set Spotify directory if not found in PATH  
`-p`  Premium subscription setup -- use if premium subscriber  

Use any combination of flags.  
The following example clears app cache, adds experimental features and uses the new UI (if supported):
    
```
bash <(curl -sSL https://raw.githubusercontent.com/SpotX-CLI/SpotX-Linux/main/install.sh) -ce
```


### Uninstall:

- Close Spotify completely.
- Run The following command in Terminal:

```
bash <(curl -sSL https://raw.githubusercontent.com/SpotX-CLI/SpotX-Linux/main/uninstall.sh)
```

or

- Reinstall Spotify

### Notes:

- Audio/video ads during Podcast playback are currently NOT blocked with SpotX.
- Spicetify users: When using SpotX-Linux + Spicetify, the current script requires running SpotX first.

### DISCLAIMER

- Ad blocking is the main concern of this repo. Any other feature provided by SpotX-Linux or consequence of using those features will be the sole responsibility of the user, not BlockTheSpot/SpotX/SpotX-CLI/SpotX-Linux.

### Credits

- Thanks to [SpotX - amd64fox](https://github.com/amd64fox/spotx).
