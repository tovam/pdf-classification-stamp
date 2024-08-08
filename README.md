# PDF Confidentiality Stamp

This project is a web-based application that allows users to add confidentiality stamps to PDF files. Users can upload individual PDF files or ZIP archives containing multiple PDFs, and apply different confidentiality levels to the documents. The application also supports handling of file name collisions and offers preview functionality before marking the PDFs.

## Features

- **Drag-and-Drop Upload**: Easily upload individual PDF files or a ZIP file containing multiple PDFs.
- **Confidentiality Levels**: Choose from different levels of confidentiality (`Public`, `Internal`, `Restricted`, `Confidential`) and apply them to the documents.
- **Customizable Text**: Customize the text that accompanies the confidentiality stamp. The current timestamp can be automatically inserted using `{now}`.
- **File Name Collision Handling**: Handle file name collisions by either keeping the original file or replacing it.
- **Preview PDFs**: Preview the PDF with the confidentiality stamp before saving.
- **Batch Processing**: Download all processed files as a ZIP archive.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/pdf-confidentiality-stamp.git
   ```
2. Navigate to the project directory:
   ```bash
   cd pdf-confidentiality-stamp
   ```
3. Serve the project using a local server. If you have Python installed, you can use:
   ```bash
   python -m http.server
   ```
4. Open the application in your web browser by navigating to `http://localhost:8000/pdf-stamp.html`.

## Usage

1. **Upload Files**: Drag and drop PDF files or a ZIP archive containing multiple PDFs into the upload area. Alternatively, click the upload area to select files from your computer.
2. **Set Confidentiality Levels**: Choose a confidentiality level for each file. You can also customize the accompanying text.
3. **Handle File Name Collisions**: If any file name collisions occur, choose whether to keep the old files or replace them.
4. **Preview and Mark**: Preview the stamped PDFs. Once satisfied, you can either download individual stamped PDFs or download all as a ZIP archive.
5. **Settings**: Customize the default text used in the confidentiality stamp from the settings menu.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the GPLv3 License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [PDFLib](https://pdf-lib.js.org/) for the awesome PDF manipulation library.
- [JSZip](https://stuk.github.io/jszip/) for the ZIP file support.


