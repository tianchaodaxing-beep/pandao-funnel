# Customer funnel analyzer

[简体中文](README.md) · English

Compare customer stage conversion and won value within one reporting scope.

Runs locally in your browser. No account or paid API is required. Demo data is fictional.

[Open online](https://tianchaodaxing-beep.github.io/pandao-funnel/?lang=en) · [Download](https://github.com/tianchaodaxing-beep/pandao-funnel/releases/latest) · [All projects](https://github.com/tianchaodaxing-beep/pandao-open-tools)

## Getting started

Download and extract the ZIP, then open `index.html`. On Windows you can double-click `Start-tool.cmd`. Keep the entire extracted folder together. Click **English** in the header; click **中文** to return to Chinese. Language selection preserves current inputs. Use `?lang=en` for a direct English page.

1. Choose one currency and reporting groups.
2. Enter leads, contacted customers, quoted customers, won customers and won value.
3. Analyze conversion, compare groups and export.

## Files and data

Spreadsheet import supports `.xlsx`, `.xls`, `.csv` and `.tsv`. Only the first worksheet is read. A spreadsheet is limited to 20,000 rows and 10 MB. Text-file support varies by tool.

Spreadsheet templates and export headers follow the selected language. Chinese and English template headers can both be imported. User-entered content and numeric results are retained as entered. Data is processed on your device and is not uploaded by the tool. External feedback links open GitHub. Export any data you need before closing: inputs are not saved automatically.

## Supported scope

All stages must use the same reporting scope, with non-increasing counts. Do not count the same customer in multiple groups. The tool does not determine advertising credit. Rates with a zero denominator are blank.

## Development and licensing

Run `npm test` with Node.js 20 or later. Using the page requires no Node.js installation or runtime dependency.

MIT licensed. Commercial use, modification and redistribution are allowed while retaining the license notice. SheetJS Community Edition 0.20.3 uses Apache-2.0; see `THIRD_PARTY_NOTICES.md` and `vendor/SheetJS-LICENSE`.

## Feedback

Use the [issue tracker](https://github.com/tianchaodaxing-beep/pandao-funnel/issues) to describe your use case and expected result. Use fictional examples in public reports; do not post customer data or credentials.
