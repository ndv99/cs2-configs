# cs2-configs
My CFG files for Counter-Strike 2.


To use:

1. Clone this repo
2. Go to your CS2 game files (right click in steamm, "Manage" --> "Browse local files")
3. For Linux enjoyers: `ln -s /path/to/this/repo/cs2-configs/autoexec.cfg autoexec.cfg`
4. For Windows prisoners: just copy and paste the files into your game directory

### `autoexec.cfg`

To be automatically executed each time the game launches. This includes equipment purchasing binds for my numpad, some cheat commands for practice mode (e.g. re-throw last grenade, clear smokes, noclip), and a bind for toggling follow-recoil crosshair.

To use, add the following lines to your CS2 launch options:

```sh
+exec autoexec.cfg
```

### `buybinds.cfg`

Creates binds for buying, dropping, and refunding weapons. Requires a numpad.

Default binds:

- `/`: Pistol 4
- `*`: Zeus
- `-`: Pistol 2
- `7`: Kevlar
- `8`: Kevlar + helmet
- `9`: Defuse kit
- `+`: Rifle 5
- `Enter`: Rifle 3
- `4`: Rifle 1
- `5`: Mid-tier 5
- `6`: Pistol 5
- `1`: Flash
- `2`: Smoke
- `3`: Molly/incendiary
- `0`: HE grenade
- `.`: Decoy grenade

You can hold `ALT` to drop any of these (except kevlar + defuse) to teammates, and `SHIFT` to refund.

`F3` will refund all purchases.

This assumes that your `SHIFT` key is what you use to walk as well. 

### `prac.cfg`

A config for multiplayer practice on any map. This script:

- Enables cheats
- Disables team limits and auto balance
- Gives $60k money
- Enables buying equipment at any time from anywhere
- Sets round time to 60 minutes
- Enables respawn on death
- Enables infinite ammo
- Shows grenade trajectories and previews
- Allows carrying all 5 grenade types at once
- Kicks bots

To use:

1. Load up any map in practice competitive mode
2. Open your console by pressing the ` or ~ key on your keyboard
3. `exec prac.cfg`
