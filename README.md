# IPEI / IPUI Converter

A web based tool for converting and validating DECT handset
identifiers (IPEI / IPUI-O) between the formats different systems use to
display them:

- Mitel OMM decimal display (`12880 0036989 7`), accepted with or without
  its trailing weighted mod-11 check digit (validated automatically when present)
- Raw EMC (Equipment Manufacturer Code) and PSN (Portable Serial Number)
- 9-digit hex IPEI
- 10-digit hex IPUI-O (4-bit PUT nibble + 36-bit IPEI body)
- 36-bit binary
- Plain decimal integer

Developed with AI - tested by a human

## Usage

Open `index.html` directly, or host it anywhere static (GitHub Pages, etc).

## License

MIT - see [LICENSE](LICENSE).
