# Rock Player
A cross-platform video player based on `electron` and `ffmpeg`.

## Feature

- Cross platform(Mac, Windows).
- Plays most video files(mp4, webm, ogg, mkv, rmvb...).

## Snapshot

![](doc/snapshot.png)

## To Use

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
git clone https://github.com/deverabit/rockplayer-electron
# Go into the repository
cd rockplayer
# Install dependencies
npm install
# Run the app
npm start
```
package mac app:

```bash
npm run package:mac:app
```

package mac dmg:

```bash
npm run package:mac:dmg
```

package windows app:

```bash
npm run package:win32
```
