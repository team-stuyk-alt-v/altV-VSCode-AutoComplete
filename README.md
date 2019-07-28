# alt:V - Auto Completion Extension

---

This is an in-progress vs-code extension that will enable auto-completion for working with https://atv.mp/ on the Javascript side. It works in a similar way to Typescript Definitions; but without using Typescript.

This is essential if you want to write your alt:V gamemodes much quicker.

alt:V is a Grand Theft Auto: V custom multiplayer client that supports up to 1000+ users at a time.

---

### VERY IMPORTANT

When you're importing 'alt', 'natives' and 'chat' please use only the following methods:
```
import * as alt from 'alt';
import * as native from 'natives';
import * as chat from 'chat';
```

After press enter on the selection of your auto-fill; it will automatically default to `alt.`, `native.` and `chat.`.

### Usage

Its quite simply really; just type some of the following in a javascript file and the rest should pop up.

* alts
* natives
* player
* vehicle
* weather
* pos
* chat

After press enter on the selection of your auto-fill; it will automatically default to `alt.`, `native.` and `chat.`.

---

### Extra

I stream alt:V development from time to time; you can check me out on twitch [twitch.tv/stuykgaming](https://www.twitch.tv/stuykgaming).