# InkDeck KPM repository

This repository distributes InkDeck for jailbroken Kindle Basic 11 / Kids devices using Véra and Mesquite. It does not require KOReader.

## Add the repository

In a Kindle terminal, add this repository with:

```sh
/var/local/kmc/bin/kpm add-repo https://raw.githubusercontent.com/juliankaluga27-ux/InkDeck-KPM/main/manifest.json
```

Then install InkDeck with:

```sh
/var/local/kmc/bin/kpm install inkdeck
```

The KPM package installs the launcher in `documents` and the Mesquite app in `extensions/InkDeck`. Removing the package removes only InkDeck's launcher and application files; uploaded files in `documents/Uploads` are retained.
