---
layout: page
title: Linking to Books
permalink: /content/books
parent: Linking to Our Content
---

## Book Content
### Book Structure
The main and beta site both primarily host scans of books in PDF and image formats.
The primary identity for any given book is a six digit number ranging between
1 and 999,999, known as the "book ID". Each book consists of
a number of pages, identified by a four digit number ranging from 1 to 9,999.
These should NOT include leading zeroes.

Some books may include additional structural elements such
as categories and tables of content, but these are not yet available
to developers.

### Book Metadata
Each book has a number of metadata fields such as title, author, year of publication,
page count, etc. These are displayed on the main book information page for each book
and some are searchable via search forms on our sites.

### Book Viewers
Both sites offer users ability to view books page by page, or to download the entire
book as a PDF. While both sites offer a PDF-based viewer for page by page turning,
the beta site also has an experimental image-based viewer that allows faster
browsing through the book.

## Constructing Links
When constructing links to our content, please be aware of the following:
   * Do not add additional parameters
   * Do not pad book IDs or page numbers with leading zeros
   * Do not link directly to the PDFs or images of the books or their pages

### Linking to Book Information Pages
Each book has a primary information page which includes the image of the title
page and the book metadata. The canonical way to link to an information page for
a given book is a follows:
   * Main site: **https://www.hebrewbooks.org/XXXXXX** where XXXXXX is the book ID
   * Beta site: **https://beta.hebrewbooks.org/XXXXXX** where XXXXXX is the book ID

Examples of valid links:
   * https://hebrewbooks.org/1
   * https://beta.hebrewbooks.org/6788
   * https://hebrewbooks.org/45463

### Linking to a Specific Page Number
It is possible to link to a specific page number which will then open the book
to that page in the book viewer. To canonical way to construct page viewer links
is as follows:
   * Main site: **https://hebrewbooks.org/pdfpager.aspx?req=XXXXX&pgnum=YYYY** where XXXXXX is the book ID and YYYY is the page number
   * Beta site (PDF viewer): **https://beta.hebrewbooks.org/pdfpager.aspx?req=XXXXX&pgnum=YYYY** where XXXXXX is the book ID and YYYY is the page number
   * Beta site (experimental image viewer): **https://beta.hebrewbooks.org/reader/reader.aspx?sfid=XXXXX#p=YYYY** where XXXXXX is the book ID and YYYY is the page number

Examples of valid links to specific page numbers in the viewer:
   * https://hebrewbooks.org/pdfpager.aspx?req=1&pgnum=10
   * https://beta.hebrewbooks.org/pdfpager.aspx?req=1&pgnum=10
   * https://beta.hebrewbooks.org/reader/reader.aspx?sfid=6788#p=36

