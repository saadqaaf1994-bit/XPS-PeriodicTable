# 🧪 XPS Periodic Table Reference

An interactive, web-based periodic table designed for rapid, offline-capable lookup of X-ray Photoelectron Spectroscopy (XPS) data. This tool aggregates binding energies, core levels, and chemical shifts into a single, easy-to-use interface.

## 🚀 Features

- **Complete Core Level Database**: Access primary photoemission lines for K, L, M, N, O, and P shells for elements Hydrogen (1) through Lawrencium (103).

- **Fingerprint Identification (✦)**: Primary lines used for element identification in survey scans are clearly distinguished with a ✦ symbol for rapid analysis.

- **Extensive Chemical Shifts**: A built-in database of binding energy shifts for oxides, nitrides, carbides, and organic functional groups for over 60 key elements.

- **Integrated Analysis Guide**: A slide-out panel featuring a step-by-step protocol for practical XPS analysis, covering:
  - Survey Scan Identification
  - Charge Correction (Calibration)
  - Background Subtraction
  - Peak Fitting & Constraints
  - Quantification

- **Smart Search**: Instantly locate elements by symbol (e.g., "Au"), name ("Gold"), or atomic number ("79").

## 🛠️ Usage

This tool is built as a Single-File Application (SPA). It requires no installation, build process, or backend server.

### Run Locally

1. Download the `index.html` file from this repository.
2. Double-click the file to open it in any modern web browser (Chrome, Firefox, Edge, Safari).

### Host Online (GitHub Pages)

1. Fork or upload this repository to your GitHub account.
2. Go to **Settings** > **Pages**.
3. Under **Build and deployment**, select `main` from the branch dropdown and click **Save**.
4. Your tool will be live at:
   ```
   https://saadqaaf.github.io/XPS-PeriodicTable/
   ```

## 📊 Data Sources

The data compiled in this tool is aggregated from standard XPS reference literature:

- **Core Levels**: Derived from standard reference tables (e.g., Table 1-1) for elements in their natural forms.
- **Transuranic Elements**: Standard reference values for Np (93) through Lr (103).
- **Reference Point**: All binding energies are referenced to Adventitious Carbon (C 1s) at 284.8 eV.

## 🤝 Contributing

Contributions are welcome! If you find missing peaks, wish to add more chemical shift data, or improve the UI:

1. Fork the repository.
2. Edit the `elementsData` object within the `index.html` file.
3. Submit a Pull Request.

## 📄 License

This project is licensed under the MIT License. You are free to use, modify, and distribute this software.

---

**Note**: This tool is intended for educational and research purposes. Always verify critical data against primary literature sources.
