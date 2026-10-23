# Matcha Reader assets

Fonts, dictionaries and language packs for [Matcha Reader](https://github.com/eszter007/matcha-reader). They change much less often than the firmware, so they live here and get their own versions. Firmware updates don't need new fonts or dictionaries unless the firmware release notes say so.

Every zip unpacks to the right place: unzip it and copy what's inside to the root of the SD card.

## Fonts

Download from the [latest fonts release](https://github.com/eszter007/matcha-reader-assets/releases/tag/fonts-2.0).

| You read | Zip | Fonts |
| --- | --- | --- |
| Japanese | [`japanese-fonts.zip`](https://github.com/eszter007/matcha-reader-assets/releases/download/fonts-2.0/japanese-fonts.zip) | Noto Sans JP, Noto Serif JP |
| Mandarin, simplified | [`chinese-fonts-simplified.zip`](https://github.com/eszter007/matcha-reader-assets/releases/download/fonts-2.0/chinese-fonts-simplified.zip) | Noto Sans SC, Noto Serif SC |
| Mandarin, traditional, and Cantonese | [`chinese-fonts-traditional.zip`](https://github.com/eszter007/matcha-reader-assets/releases/download/fonts-2.0/chinese-fonts-traditional.zip) | Noto Sans TC, Noto Serif TC |
| Noto Sans as a reading font (pairs with the Chinese Sans fonts) | [`noto-sans-font.zip`](https://github.com/eszter007/matcha-reader-assets/releases/download/fonts-2.0/noto-sans-font.zip) | Noto Sans |

## Dictionaries

Download from the [latest dictionaries release](https://github.com/eszter007/matcha-reader-assets/releases/tag/dictionaries-2.0).

| Language | Zip | Ends up in |
| --- | --- | --- |
| Japanese | [`japanese-dictionaries.zip`](https://github.com/eszter007/matcha-reader-assets/releases/download/dictionaries-2.0/japanese-dictionaries.zip) | `dictionaries/jp/` |
| Mandarin, simplified | [`dictionaries-zh-simplified.zip`](https://github.com/eszter007/matcha-reader-assets/releases/download/dictionaries-2.0/dictionaries-zh-simplified.zip) | `dictionaries/zh/` |
| Mandarin, traditional | [`dictionaries-zh-traditional.zip`](https://github.com/eszter007/matcha-reader-assets/releases/download/dictionaries-2.0/dictionaries-zh-traditional.zip) | `dictionaries/zh/` |
| Cantonese | [`dictionaries-yue.zip`](https://github.com/eszter007/matcha-reader-assets/releases/download/dictionaries-2.0/dictionaries-yue.zip) | `dictionaries/yue/` |

Install only one of the two Mandarin packs, since both use `dictionaries/zh/`.

Want a different dictionary? [Matcha Reader Tools](https://eszter007.github.io/matcha-reader-tools/) converts dictionary files in your browser, e.g. a newer JMdict or CC-CEDICT, or one for another language. A StarDict dictionary for any other language can go straight onto the card in its own folder, e.g. `dictionaries/fr/larousse/`. See the [dictionary guide](https://github.com/eszter007/matcha-reader/blob/develop/docs/dictionary-setup.md).

## Language packs

Each firmware version has its own `language-packs-<version>` release, e.g. [language-packs-2.0.0-rc-2](https://github.com/eszter007/matcha-reader-assets/releases/tag/language-packs-2.0.0-rc-2). A pack only works with the firmware it was built for, so pick the release that matches the version in Settings. Download the `.cplang` file for your language and copy it to `/.crosspoint/lang/` on the SD card.

## Licences

The fonts are under the SIL Open Font License. Each dictionary zip has a README.txt with its sources and licences.
