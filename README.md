# spp-tools

# macOS

setup

```console
# echo export PATH='"'$(pwd)'/macOS:$PATH"' >> ~/.$(basename $SHELL)rc
# chmod a+x macOS/*
```

command list

|command|usage|description|
|-|-|-|
|`pdf-compact`|`pdf-compact -1 in.pdf out.pdf`|compress pdf|
|`codomon-get-pict-large`|`codomon-get-pict-large　https://...`|download large image from codomon|
|`exif-set-date`|`exif-set-date 20250125120000 *.jpg`|set picture date|
|`exif-set-gps`|`exif-set-gps 34.649394 135.001478 *.jpg`|set picture location|

