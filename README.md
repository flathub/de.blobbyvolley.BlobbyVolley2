Blobby Volley 2
===

This is Flatpak package for Blobby Volley 2 game, published in Flathub.org:
https://flathub.org/apps/details/de.blobbyvolley.BlobbyVolley2. 

If you are looking for the place where Blobby Volley 2 is developed, go to:
https://github.com/danielknobe/blobbyvolley2.

How to install?
---

1. Make sure you installed Flatpak and Flathub.org repository: 
   https://flatpak.org/setup/.
2. Search for `Blobby Volley 2` in GNOME Software or KDE Discover.
   You can also use this command in terminal:
   `flatpak install de.blobbyvolley.BlobbyVolley2`.
3. Click `Blobby Volley 2` icon in your desktop launcher or run this command:
   `flatpak run de.blobbyvolley.BlobbyVolley2`.

How to build?
---

Make sure you have Flatpak, Flathub.org repository and `flatpak-builder`
command installed. Then run this command:

```bash
flatpak-builder build de.blobbyvolley.BlobbyVolley2.yaml \
    --force-clean --install-deps-from=flathub
```

Use this command to install built package locally:

```bash
flatpak-builder build de.blobbyvolley.BlobbyVolley2.yaml \
    --export-only --install --user
```