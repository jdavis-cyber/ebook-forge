# eBook Forge: The Protocol Standardization Engine

## Executive Summary

eBook Forge is a zero-dependency, single-file document authoring environment designed specifically for **Program Analysts**, **Governance Leads**, and **SOP Authors** who operate in IT-restricted environments. It transforms chaotic input from various sources (Word, PDF, raw text) into standardized, professional-grade Standard Operating Procedures (SOPs), policy documents, and compliance artifacts.

## The Problem

Program Analysts often face a "Tooling Gap" in enterprise environments:

1. **Restricted Execution**: Inability to install modern software due to strict IT policies (no admin rights, blocked installations).
2. **Inconsistent Output**: Team members submit content in various fonts, sizes, and formats, leading to "Frankenstein" documents that lack professional authority.
3. **Formatting Fatigue**: Valuable time is wasted manually fixing line breaks, margins, and typography instead of focusing on the governance content itself.

## The Solution

**eBook Forge** eliminates these friction points by providing a "Gold Master" rendering engine that enforces standardization automatically. It acts as a forcing function for consistency.

### Key Capabilities

* **Zero-Install Architecture**: The entire application is a single HTML file. If you have a web browser, you have the tool. No IT ticket required. No install wizard. No admin privileges needed.
* **Enforced Standardization**:
  * **Typography**: Locked to industry-standard **Merriweather** (serif) for readability and authority.
  * **Layout**: Fixed US Letter (8.5" x 11") dimensions with professional margins (0.5").
  * **Pagination**: Live, dynamic page break indicators show exactly where physical printing will cut content, eliminating "widows and orphans" in printed SOPs.
* **Universal Ingestion**:
  * **Word (.docx)**: Import legacy SOPs while stripping out messy, inconsistent styling.
  * **PDF**: Extract raw text from locked PDFs to repurpose content.
* **Governance-Ready Output**: Exports directly to clean, paginated PDF/Print readiness without watermarks or proprietary formats.
* **AI-Assisted Remediation** (Optional): Integrated Gemini API hook to "repair" broken text, garbled OCR, or malformed tables from legacy imports.

## Technical Specifications

* **Platform**: Universal Web Standards (HTML5 / CSS3 / ES6). Runs in Chrome, Edge, Firefox, Safari.
* **Security**: Local-only execution. Your data never leaves the browser's secure sandbox (IndexedDB).
* **Persistence**: Auto-saves work to the browser's local storage. Documents survive tab closures and browser restarts.

## Usage Guide

### 1. Launch

Simply double-click `index.html`. The specific version of the tool is "frozen" in that file, ensuring that an SOP written today can be edited on the same tool 5 years from now.

### 2. Import & Organize

* **Import**: Drag and drop existing `.docx` or `.pdf` files directly onto the canvas.
* **Structure**: Use the sidebar to treat each file as a "Chapter" or "Section". Drag and drop to reorder sections of your document.

### 3. Refine

* **Edit**: Use the WYSIWYG editor to apply semantic formatting (Headers, Lists, Bold/Italic).
* **Images**: Insert images that automatically resize to fit the column width defined by the governance standard.

### 4. Publish

Click the **Print/PDF** icon in the toolbar. The application generates a print-ready view that browsers can save directly as a standardized PDF.

---
**eBook Forge** — *Built for the disciplined author.*
