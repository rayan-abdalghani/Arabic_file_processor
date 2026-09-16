# 📊 Arabic File Processor

A simple Google Colab tool for reading, editing, and exporting files that contain Arabic text.

The tool automatically detects the file type and handles different sources, including Google Sheets, Google Drive files, CSV, XLSX, and XLS.

## 🚀 Open in Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/USERNAME/arabic-file-processor/blob/main/arabic_file_processor.ipynb)

## ✨ What does it do?

The tool allows you to:

- Load a file using a link.
- Automatically detect the file type.
- Read Arabic text correctly.
- View and edit the data.
- Download the modified file.

## 📂 Supported Sources

- Google Sheets
- Google Drive
- Direct file links
- CSV
- XLSX
- XLS

## ⚠️ Before You Start

If your file is stored on Google Drive or Google Sheets, make sure its sharing settings allow access to anyone with the link.

Set the sharing option to:

**Anyone with the link → Viewer**

Otherwise, the tool may not be able to access the file.

## 📝 How to Use

1. Click **Open in Google Colab**.
2. Run the installation cell.
3. Run the remaining cells.
4. Paste your file link.
5. Click **Load File**.
6. Edit the data if needed.
7. Click **Save & Download**.
8. Download your processed file.

## 🔐 Privacy

The tool processes the file through the Google Colab session.

Do not use the tool with sensitive or confidential data unless you understand how your Colab environment and the linked file are being accessed.

## 🛠️ Built With

- Python
- Pandas
- OpenPyXL
- Gradio
- Google Colab