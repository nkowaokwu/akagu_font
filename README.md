# Akagu Font

Editing the Akagu font to support Nsibidi in PUA range. This font will be used to submit our final proposal
to Unicode to add Akagu and Nsibidi script.

## FontForge

In order to move the Nsibidi glyphs into the PUA code point range, we use [FontForge](https://fontforge.org/en-US/)

## FontForge Fonts

There are two files in this project that represent the current working state of this project:

- `Akagu_compressed_PUA.sfd` - all the Nsibidi characters have been moved to the PUA code point range
  and includes no empty code points in the PUA range.
- `Akagu_raw_PUA.sfd` - all Nsibidi characters have been copied and pasted into the PUA code point range
  but have empty code points in the PUA range.

## About Nsibidi

Within the [Igbo API](https://igboapi.com), we hold approximately 2,572 unique Nsibidi characters.

As of August 4, 2024, we have approximately 2,567 Nsibidi characters in the PUA code points range.

This means that we need to make sure that include the last 6 characters.

## What is `.sfd`?

Files that end in `.sfd` are the working file type that FontForge works with. If we upload an `.sfd`
font into FontForge, we can edit the font.

## Acknowledgements

Thank you to the following contributors of editing the Akagu font.

- Cynthia Ellis
- Udochi Okeke
- Ijemma Onwuzulike
- Adaeze Umezurike
- Jordan Williams
- Oreen Yousuf
