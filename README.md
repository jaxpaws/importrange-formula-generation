# importrange-formula-generation
A one-file HTML web page that can be used to generate Google Sheets IMPORTRANGE formulas to import data from multiple similarly structured spreadsheets into one spreadsheet.

## How to Use
1. Download the _importrange-formula-builder.html_ file.
2. Open the file in your browser of choice. If you have disabled JavaScript in your browser, you may need to enable it.
3. Enter the appropriate values in the input fields on the page. It is assumed that there is a name for each spreadsheet you are importing data from, whether that be a person's name a place name or a simple identifier.
4. Click "Generate Spreadsheet Formulas" to generate the formulas.
5. The generated formulas will appear below the input fields under the "Output" heading. Each column will be listed separately because Google Sheets cannot handle multiple columns of formulas being pasted at once, and will just paste all the columns into a single cell.
6. Select the copy buttons to copy each column to your clipboard or manually select and copy each column of formulas.
7. Paste each column into your spreadsheet and check to make sure that the data imports properly

## Tips
### Google Sheets says you don't have access to the spreadsheet
If Google Sheets gives an error and says that you don't have access to the spreadsheet you are trying to import data from, first check the permissions of that spreadsheet. If you should have access to that spreadsheet, then make sure that it is saved as a Google Sheets spreadsheet, and not an XLSX or XLS. To change an XLSX or XLS to a Google Sheets spreadsheet, simply go the spreadsheet you want to convert, select "File", then select "Save as Google Sheets", and it will create a copy of the file as a Google Sheets spreadsheet. It will not have the same URL, so you will need to get the URL of that new Google Sheets spreadsheet.
