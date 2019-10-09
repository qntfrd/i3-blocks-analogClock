Displays the current date time like so

```bash
w42 📅 2019-05-10 🕖 07:55
```

## Usage

Just add the following block to your `~/.i3/i3blocks.conf`

```
[time]
command=<path to this repo>/clock.sh
interval=60
```

You can lower the interval as this one may give a 1mn diff
between real time and display time in the worst case scenario
_e.g._ it's 8:00 but it display 7:59.
