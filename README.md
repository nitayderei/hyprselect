# HyprSelect

HyprSelect adds a desktop selection box to Hyprland, that does absolutely nothing, but is absolutely essential.

![Image of desktop selection on empty desktop](https://github.com/user-attachments/assets/309bacff-a539-466f-83fa-b92b71dd8567)

## Installation

```bash
git clone https://github.com/jmanc3/hyprselect
cd hyprselect
make
```

That should create `hyprselect.so`.

You can load it with: `hyprctl plugin load /full/qualified/path/to/hyprselect.so`.
Or unload it with: `hyprctl plugin unload /full/qualified/path/to/hyprselect.so`.

To auto start it with Hyprland, add the following to `$HOME/.config/hypr/hyprland.conf`

```bash
exec-once = hyprctl plugin load /full/qualified/path/to/hyprselect.so
```

## Config Variables

None yet.
