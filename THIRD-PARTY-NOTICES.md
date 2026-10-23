# Third-party software

FileAction is MIT-licensed (see [LICENSE](LICENSE)). It uses the following software. Each keeps its own license.

| Component | Used for | License |
|---|---|---|
| [Magick.NET](https://github.com/dlemstra/Magick.NET) / ImageMagick | Images | Apache-2.0 / ImageMagick License |
| [PDFtoImage](https://github.com/sungaila/PDFtoImage) / PDFium / SkiaSharp | PDF → images | MIT / BSD-3-Clause / MIT |
| [PdfPig](https://github.com/UglyToad/PdfPig) | PDF text | Apache-2.0 |
| [PDFsharp](https://github.com/empira/PDFsharp) 6.2 | Merge, split, rotate PDF | MIT |
| [ClosedXML](https://github.com/ClosedXML/ClosedXML) | XLSX | MIT |
| [ExcelDataReader](https://github.com/ExcelDataReader/ExcelDataReader) | XLS | MIT |
| [SharpCompress](https://github.com/adamhathcock/sharpcompress) | RAR, 7z, TAR… | MIT |
| [FFmpeg](https://ffmpeg.org) (Windows: bundled in the installer, “essentials” build by [gyan.dev](https://www.gyan.dev/ffmpeg/builds/)) | Audio and video | GPL-3.0 – source: https://github.com/FFmpeg/FFmpeg |
| [Pandoc](https://pandoc.org) (Windows: bundled in the installer from [its releases](https://github.com/jgm/pandoc/releases)) | Documents | GPL-2.0-or-later – source: https://github.com/jgm/pandoc |
| [LibreOffice](https://www.libreoffice.org) (optional, installed separately) | Office files → PDF | MPL-2.0 |

On Windows, FFmpeg and Pandoc are embedded directly within the application installation (under the `{app}\tools` folder); on Linux they come from your distribution. They run as separate programs; FileAction only calls them on the command line.
