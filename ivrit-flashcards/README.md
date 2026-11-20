# Ivrit Flashcards

Flashcards for practising Hebrew: cards, matching, spelling and multiple-choice tests, Hebrew → English, English → Hebrew or both ways.

**Open the app:** `https://<github-username>.github.io/<repository-name>/`

## Adding or changing study sets

Every `.csv` file in the `sets` folder appears in the app as a shared set. Subfolders become groups, for example `sets/Ivrit Class 2/`.

To add a set on github.com: open the `sets` folder (or a subfolder) → **Add file → Upload files** → commit. To fix a word, open the file → pencil icon → edit → commit. Reopen the app or tap **Refresh**.

### CSV format

One card per line: `word,translation`. A third column is optional and is shown as a note.

```
hebrew,english,note
שלום,hello / peace,Shalom
תודה,thank you,Todah
```

- The header row is optional. Recognised header names include `hebrew`, `english`, `word`, `translation`, `note`.
- A column named `handwritten` is shown in Hebrew handwriting; a column named `letter` shows print and handwriting side by side.
- Put text with commas in quotes: `בית,"house, home"`.
- In answers, `/` separates alternatives that all count as correct: `sorry / excuse me`.
- Save as UTF-8 (Excel: *CSV UTF-8*).

## Credits

Handwriting font: Gveret Levin by AlefAlefAlef, SIL Open Font License 1.1.
