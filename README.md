# A Long-Term Archival Pipeline for the Forschungsdatenplattform Stadt.Geschichte.Basel

**DaSCHCon 2025 Conference Contribution**

This repository contains the abstract and presentation for our contribution to DaSCHCon 2025, discussing the implementation of a transition pipeline to archive metadata and files from Omeka to DaSCH for long-term preservation.

[![GitHub issues](https://img.shields.io/github/issues/maehr/daschcon2025-omeka2dsp.svg)](https://github.com/maehr/daschcon2025-omeka2dsp/issues)
[![GitHub forks](https://img.shields.io/github/forks/maehr/daschcon2025-omeka2dsp.svg)](https://github.com/maehr/daschcon2025-omeka2dsp/network)
[![GitHub stars](https://img.shields.io/github/stars/maehr/daschcon2025-omeka2dsp.svg)](https://github.com/maehr/daschcon2025-omeka2dsp/stargazers)
[![Code license](https://img.shields.io/github/license/maehr/daschcon2025-omeka2dsp.svg)](https://github.com/maehr/daschcon2025-omeka2dsp/blob/main/LICENSE-AGPL.md)

## Conference Information

- **Event**: DaSCHCon 2025 – Cultural Institutions in the Digital Age: The Future of Infrastructures
- **Date**: October 15, 2025
- **Location**: Museum für Kommunikation, Bern
- **Website**: [dasch.swiss](https://www.dasch.swiss/post/daschcon-2025-cultural-institutions-in-the-digital-age-the-future-of-infrastructures/)

## Repository Structure

```
.
├── abstract/           # Conference abstract
│   └── abstract.qmd   # Quarto document with full abstract
├── presentation/      # Presentation slides
│   └── presentation.qmd # Quarto RevealJS presentation
├── CITATION.cff       # Citation metadata
└── ...                # Standard repository files
```

## Abstract Summary

The [Forschungsdatenplattform](https://forschung.stadtgeschichtebasel.ch) by Stadt.Geschichte.Basel provides open access to diverse historical materials relating to the city of Basel. While technically robust, our current infrastructure (Omeka-S → CollectionBuilder → GitHub Pages) faces critical sustainability and scalability limitations.

This presentation discusses our implementation of a [transition pipeline](https://dokumentation.stadtgeschichtebasel.ch/omeka2dsp) to archive all metadata and associated files with DaSCH, leveraging its infrastructure for versioned, durable, and FAIR-compliant research data publication.

### Key Topics

1. **Current Challenges**: Institutional control, persistence, and FAIR compliance
2. **Pipeline Architecture**: Metadata harvesting, automated deposit, identifier management
3. **Technical Implementation**: REST API integration, version control, relationship preservation
4. **Lessons Learned**: Crosswalks, file handling, minimal computing vs. robust backends
5. **Broader Implications**: Infrastructure independence, platform scalability, FAIR principles

## Authors

- **Moritz Mähr** - [ORCID: 0000-0002-1367-1618](https://orcid.org/0000-0002-1367-1618) - Universität Basel / Universität Bern
- **Moritz Twente** - [ORCID: 0009-0005-7187-9774](https://orcid.org/0009-0005-7187-9774) - Universität Basel

## Related Links

- [Forschungsdatenplattform Stadt.Geschichte.Basel](https://forschung.stadtgeschichtebasel.ch)
- [omeka2dsp Documentation](https://dokumentation.stadtgeschichtebasel.ch/omeka2dsp)
- [Stadt.Geschichte.Basel](https://stadtgeschichtebasel.ch)
- [Conference Program](https://ark.dasch.swiss/ark:/72163/1/0810/UEtpksyaRPeobZ_S41IhnA5.20250827T145742276838562Z)
- [Abstract Booklet](https://ark.dasch.swiss/ark:/72163/1/0810/YCULyZnMSImhHrRPqrMZwwh.20250827T145812592171563Z)

## Use

Check that all files are properly formatted.

```bash
npm run check
```

Format all files.

```bash
npm run format
```

Run the wizard to write meaningful commit messages.

```bash
npm run commit
```

Run the wizard to create a CHANGELOG.md.

```bash
npm run changelog
```

Preview the documentation.

```bash
quarto preview
```

## Installation

We recommend using **[GitHub Codespaces](https://github.com/features/codespaces)** for a reproducible setup with all dependencies pre-installed.

Alternatively, install the following locally:

- [Quarto](https://quarto.org/docs/get-started/)
- [Node.js](https://nodejs.org/)

Then run:

```bash
npm install
```

## Roadmap

- [x] Create abstract document
- [x] Create presentation slides
- [ ] Finalize presentation content with examples
- [ ] Add images and diagrams
- [ ] Publish to GitHub Pages

## Contributing

Please see [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

## Authors and credits

- **Moritz Mähr** - _Initial work_ - [maehr](https://github.com/maehr)
- **Moritz Twente** - _Co-author_ - [mtwente](https://github.com/mtwente)

This repository is based on the [open-research-data-template](https://github.com/maehr/open-research-data-template).

## License

The code in this project is licensed under the [AGPL-3.0 license](LICENSE-AGPL.md), and the data/content is licensed under the [CC-BY-4.0 license](LICENSE-CCBY.md).
