# Scribus Books

A collection of book design and desktop publishing projects created with **Scribus 1.6.6**, using public-domain literary works as source material.

The purpose of this repository is to demonstrate practical skills in **book layout, typography, page composition, image preparation, color management, and print/digital publishing workflows**.

## About This Project

This repository contains book projects created as a portfolio and demonstration of skills in **Scribus, desktop publishing, graphic design, and digital publishing**.

The projects use public-domain literary works as source material for creating new book layouts and visual designs.

The focus is on demonstrating the complete **book production and desktop publishing workflow**, from source material and image preparation through page layout and final PDF production.

## Location of PDF Books

Book-01-The-Picture-of-Dorian-Gray/PDF Book and Cover/The Picture of Dorian Gray - Oscar Wilde.pdf \
Book-02/PDF Book and Cover/Book 2.pdf \
Book-03/PDF Book and Cover/Book 3.pdf \
...

## Location of Scribus .sla files

Book-01-The-Picture-of-Dorian-Gray/Interior/The Picture of Dorian Gray - Oscar Wilde.sla \
Book-02/Interior/Book 2.sla \
Book-03/Interior/Book 3.sla \
...

## Screenshots of PDF Book Cover

<img src="./Book-01-The-Picture-of-Dorian-Gray/Screenshots/Screenshot Cover.png" width="840" alt="Screenshot 1">

## Screenshots of PDF Book Pages

<img src="./Book-01-The-Picture-of-Dorian-Gray/Screenshots/Screenshot 1.png" width="840" alt="Screenshot 1">

<img src="./Book-01-The-Picture-of-Dorian-Gray/Screenshots/Screenshot 2.png" width="840" alt="Screenshot 2">

## Software

The projects may use the following software:

- **Scribus 1.6.6** — book layout, typography, master pages, page numbering, text flow, and PDF production
- **GIMP** — image editing, manipulation, and color preparation

## Skills Demonstrated

### Book Layout & Desktop Publishing

- Professional book page layout
- Facing-page document setup
- Master pages
- Page numbering
- Automatic page numbers
- Page sections and numbering
- Linked text frames
- Multi-page text flow
- Paragraph styles
- Character styles
- Typography and text hierarchy
- Margins and page grids
- Chapter layouts
- Headers and footers
- Tables of contents
- Front matter and back matter
- Book cover design

### Print Production

- Print-oriented page dimensions
- Bleed and margins
- CMYK workflows
- Image resolution and preparation
- ICC color profiles
- Font management
- PDF preflight
- Print-ready PDF export
- PDF/X workflows

### Digital Publishing

- Digital PDF production
- Screen-optimized documents
- Ebook-oriented layouts
- Digital document optimization

## Repository Structure

```text
scribus-books/
│
├── README.md
├── LICENSE
├── .gitignore
│
├── Book-01-The-Picture-of-Dorian-Gray/
│   ├── Interior/
│   │   └── Book-Interior.sla
│   │
│   ├── Cover/
│   │   └── Book-Cover.sla
│   │
│   ├── Assets/
│   │   ├── Images/
│   │   └── Books/
│   │
│   └── PDF Preview/
│       ├── Book.pdf
│
├── Book-02/
│   └── ...
│
└── ...
```

The exact structure may vary between projects depending on the requirements of each book.

## Author

Created as a personal portfolio project to demonstrate skills in **Scribus, book design, desktop publishing, graphic design, and print production**.

## Cover Production Specifications

For the purposes of these portfolio and study projects, book covers are designed as a **single full-cover spread** containing the back cover, spine, and front cover.

### Standard Cover Assumptions

Unless a specific printer provides different production specifications, the following standard assumptions are used for the cover designs:

- **Book format:** A5
- **Finished page size:** 148 × 210 mm
- **Binding:** Paperback / perfect binding
- **Interior page count:** 293 pages
- **Interior paper:** 90 g/m² book paper
- **Assumed paper caliper:** approximately 0.09 mm per page
- **Calculated spine width:** 293 × 0.09 mm = 26.37 mm
- **Working spine width:** 26.4 mm
- **Bleed:** 3 mm on all outside edges
- **Cover color workflow:** CMYK-oriented print workflow
- **Target raster image resolution:** approximately 300 PPI at final physical size

### Cover Dimensions

The cover is designed as one horizontal spread:

```text
┌────────────────┬──────────┬────────────────┐
│                │          │                │
│   BACK COVER   │  SPINE   │  FRONT COVER   │
│                │          │                │
│  148 × 210 mm  │ 26.4 mm  │  148 × 210 mm  │
│                │          │                │
└────────────────┴──────────┴────────────────┘
```

Finished trim dimensions:

- Back cover: 148 × 210 mm
- Spine: 26.4 × 210 mm
- Front cover: 148 × 210 mm
- Total finished cover spread: **322.4 × 210 mm**

With 3 mm bleed on all sides:

- Total PDF/artwork area including bleed: **328.4 × 216 mm**

The cover background and other artwork that reaches the trim edge should extend through the bleed area.

Important text, logos, and other essential elements should remain safely inside the trim area and away from the edges. The exact safe area may be adjusted according to the requirements of the intended printer.

### Cover File Structure

Each book uses a separate Scribus cover document from the interior document:

```text
Book-01-The-Picture-of-Dorian-Gray/
├── Interior/
│   └── The Picture of Dorian Gray - Oscar Wilde.sla
│
├── Cover/
│   └── The Picture of Dorian Gray - Oscar Wilde - Cover.sla
│
├── Assets/
│   ├── Images/
│   └── Books/
│
└── PDF Preview/
    ├── Book.pdf
    └── Cover.pdf
```

The cover Scribus document contains the **back cover, spine, and front cover as one continuous spread** and is exported as one print-ready cover PDF.

### Cover Image Preparation

Raster images used for print covers should preferably be supplied as high-quality TIFF or PSD files, although high-quality JPEG files are also acceptable when appropriate.

Raster images should normally provide approximately **300 PPI at their final placed size**, including any area that extends into the bleed.

PNG files may be used when transparency or other characteristics make PNG appropriate, but they are not the preferred general-purpose format for photographic print artwork.

### Production Note

The spine width of **26.4 mm** is an assumed value for these study projects, calculated from the assumed 90 g/m² paper and an approximate 0.09 mm page caliper.

For an actual commercial print run, the printer's supplied cover template, paper specification, binding specification, bleed requirement, color profile, and PDF export requirements take precedence over these portfolio assumptions.
