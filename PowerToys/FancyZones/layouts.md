# Fancy zones

All the fancyZones Layouts are stored in `%LocalAppData%\Microsoft\PowerToys\FancyZones\zones-settings.json` file you can use it to directly copy from net.

## Layouts I liked

This places multiple placeholders that I frequently use into a layout.
Place this in `custom-zone-sets` array.

```json
{
      "uuid": "...",
      "name": "All Possible Settings",
      "type": "canvas",
      "info": {
        "ref-width": 2560,
        "ref-height": 1410,
        "zones": [
          { "X": 0, "Y": 0, "width": 1024, "height": 705 },
          { "X": 0, "Y": 705, "width": 1024, "height": 705 },
          { "X": 0, "Y": 0, "width": 1281, "height": 705 },
          { "X": 0, "Y": 705, "width": 1281, "height": 705 },
          { "X": 1281, "Y": 0, "width": 1279, "height": 705 },
          { "X": 1281, "Y": 705, "width": 1279, "height": 705 },
          { "X": 1536, "Y": 0, "width": 1024, "height": 705 },
          { "X": 1536, "Y": 705, "width": 1024, "height": 705 },
          { "X": 576, "Y": 0, "width": 1411, "height": 1029 },
          { "X": 0, "Y": 0, "width": 2560, "height": 1410 },
          { "X": 0, "Y": 0, "width": 1281, "height": 1410 },
          { "X": 1281, "Y": 0, "width": 1279, "height": 1410 },
          { "X": 0, "Y": 0, "width": 2560, "height": 705 },
          { "X": 0, "Y": 705, "width": 2560, "height": 705 }
        ],
        "sensitivity-radius": 20
      }
    }
```

If you want to manually make something like this just create a custom layout of type canvas. `Canvas` allows you to define arbitary positions for your windows.

This works best with the PowerToys setting `Move windows based on` set to `Relative Position` and using `Windows` + `arrow keys`.
