<a id="ascii-tabellen-deutsch"></a>

# ASCII-Tabellen

*[English version below / englische Version weiter unten](#ascii-tables-english)*

Dieser Ordner enthält druckfertige ASCII-Tabellen als PNG-Dateien. Sie dienen als Nachschlagewerk und Anschauungsmaterial in Seminaren zu Zeichenkodierung, Zahlensystemen und Internet-Grundlagen (z. B. URL-Encoding nach RFC 3986).

## Dateibenennung

Die Dateinamen folgen dem Schema:

```
TT-A<Variante><Format>-<Leserichtung> - ASCII table <Inhalt>
```

- **TT-A0…AB** – fortlaufender Code der Tabellenvariante (siehe Liste unten)
- **P / L** – Portrait (Hochformat) oder Landscape (Querformat)
- **T2B / L2R** – Leserichtung der Bit-Spalten: Top-to-Bottom (von oben nach unten) oder Left-to-Right (von links nach rechts)

## Varianten

Jede Tabelle stellt den druckbaren ASCII-Zeichensatz in unterschiedlichen Zahlensystemen bzw. Zusammenstellungen dar:

| # | Inhalt |
|---|--------|
| 0 | Nachbildung der Originalskizzen von 1963 bzw. 1968<br>[TT-A0P-T63](TT-A0P-T63%20-%20ASCII%20table%20BIN%201963%20replica.png)<br>[TT-A0P-T68](TT-A0P-T68%20-%20ASCII%20table%20BIN%201968%20replica.png) |
| 1 | Binär (BIN)<br>[TT-A1L-L2R](TT-A1L-L2R%20-%20ASCII%20table%20BIN.png)<br>[TT-A1L-T2B](TT-A1L-T2B%20-%20ASCII%20table%20BIN.png)<br>[TT-A1P-L2R](TT-A1P-L2R%20-%20ASCII%20table%20BIN.png)<br>[TT-A1P-T2B](TT-A1P-T2B%20-%20ASCII%20table%20BIN.png) |
| 2 | Hexadezimal (HEX)<br>[TT-A2L-L2R](TT-A2L-L2R%20-%20ASCII%20table%20HEX.png)<br>[TT-A2P-T2B](TT-A2P-T2B%20-%20ASCII%20table%20HEX.png) |
| 3 | Oktal (OCT)<br>[TT-A3L-T2B](TT-A3L-T2B%20-%20ASCII%20table%20OCT.png)<br>[TT-A3P-L2R](TT-A3P-L2R%20-%20ASCII%20table%20OCT.png) |
| 4 | Dezimal (DEC)<br>[TT-A4L-T2B](TT-A4L-T2B%20-%20ASCII%20table%20DEC.png)<br>[TT-A4P-L2R](TT-A4P-L2R%20-%20ASCII%20table%20DEC.png) |
| 5 | Binär + Hex<br>[TT-A5L-L2R](TT-A5L-L2R%20-%20ASCII%20table%20BIN-HEX.png)<br>[TT-A5P-T2B](TT-A5P-T2B%20-%20ASCII%20table%20BIN-HEX.png) |
| 6 | Binär + Hex + Dezimal<br>[TT-A6L-L2R](TT-A6L-L2R%20-%20ASCII%20table%20BIN-HEX-DEC.png)<br>[TT-A6P-T2B](TT-A6P-T2B%20-%20ASCII%20table%20BIN-HEX-DEC.png) |
| 7 | Binär + Hex + Dezimal + Oktal<br>[TT-A7L-L2R](TT-A7L-L2R%20-%20ASCII%20table%20BIN-HEX-DEC-OCT.png)<br>[TT-A7P-T2B](TT-A7P-T2B%20-%20ASCII%20table%20BIN-HEX-DEC-OCT.png) |
| 8 | Binär + Hex + Dezimal, zusätzlich mit RFC-3986-Kennzeichnung (reservierte/unreservierte Zeichen fürs URL-Encoding)<br>[TT-A8L-L2R](TT-A8L-L2R%20-%20ASCII%20table%20BIN-HEX-DEC-RFC3986.png)<br>[TT-A8P-T2B](TT-A8P-T2B%20-%20ASCII%20table%20BIN-HEX-DEC-RFC3986.png) |
| 9 | Binär + Hex + Dezimal, Fassung von 1963<br>[TT-A9L-L2R](TT-A9L-L2R%20-%20ASCII%20table%20BIN-HEX-DEC-1963.png)<br>[TT-A9P-T2B](TT-A9P-T2B%20-%20ASCII%20table%20BIN-HEX-DEC-1963.png) |
| A | Binär + Hex + Dezimal, Fassung von 1968<br>[TT-AAL-L2R](TT-AAL-L2R%20-%20ASCII%20table%20BIN-HEX-DEC-1968.png)<br>[TT-AAP-T2B](TT-AAP-T2B%20-%20ASCII%20table%20BIN-HEX-DEC-1968.png) |
| B | Binär + Hex + Dezimal, Vergleich 1963 vs. 1968<br>[TT-ABL-L2R](TT-ABL-L2R%20-%20ASCII%20table%20BIN-HEX-DEC-1963+1968.png)<br>[TT-ABP-T2B](TT-ABP-T2B%20-%20ASCII%20table%20BIN-HEX-DEC-1963+1968.png) |

Zwei ergänzende Tabellen:

- **6th digit / Prefixe** – hebt Prefixe und sechste Stelle hervor.<br>[TT-APL-L2R](TT-APL-L2R%20-%20ASCII%20table%20BIN-HEX-DEC%20-%206th%20digit.png)
- **für Medien** – eine speziell für Workshops erstellte Variante (zum Erklären und erarbeiten von weiteren Teilen).<br>[TT-AVL-L2R](TT-AVL-L2R%20-%20ASCII%20table%20BIN-HEX-DEC%20-%20for%20media.png)

### Warum zwei Fassungen (1963 / 1968)?

ASCII wurde nach der ersten Verabschiedung 1963 mehrfach überarbeitet. Die
Fassung von 1963 definiert z. B. an den Codepunkten 0x5E/0x5F noch Pfeile
(`↑`, `←`) statt der später (1968er-Revision) üblichen Zeichen `^` und `_`.
Die Tabelle "1963+1968" stellt beide Fassungen direkt gegenüber.

---

<a id="ascii-tables-english"></a>

# ASCII Tables (English)

*[Deutsche Version oben / German version above](#ascii-tabellen-deutsch)*

This folder contains print-ready ASCII tables as PNG files. They serve as a reference and visual aid in workshops on character encoding, number systems, and internet fundamentals (e.g. URL encoding per RFC 3986).

## File naming

File names follow this pattern:

```
TT-A<variant><format>-<reading direction> - ASCII table <content>
```

- **TT-A0…AB** – sequential code for the table variant (see list below)
- **P / L** – Portrait or Landscape
- **T2B / L2R** – reading direction of the bit columns: Top-to-Bottom or Left-to-Right

## Variants

Each table shows the printable ASCII character set in different number systems or combinations thereof:

| # | Content |
|---|---------|
| 0 | Recreation of the original 1963/1968 sketches<br>[TT-A0P-T63](TT-A0P-T63%20-%20ASCII%20table%20BIN%201963%20replica.png)<br>[TT-A0P-T68](TT-A0P-T68%20-%20ASCII%20table%20BIN%201968%20replica.png) |
| 1 | Binary (BIN)<br>[TT-A1L-L2R](TT-A1L-L2R%20-%20ASCII%20table%20BIN.png)<br>[TT-A1L-T2B](TT-A1L-T2B%20-%20ASCII%20table%20BIN.png)<br>[TT-A1P-L2R](TT-A1P-L2R%20-%20ASCII%20table%20BIN.png)<br>[TT-A1P-T2B](TT-A1P-T2B%20-%20ASCII%20table%20BIN.png) |
| 2 | Hexadecimal (HEX)<br>[TT-A2L-L2R](TT-A2L-L2R%20-%20ASCII%20table%20HEX.png)<br>[TT-A2P-T2B](TT-A2P-T2B%20-%20ASCII%20table%20HEX.png) |
| 3 | Octal (OCT)<br>[TT-A3L-T2B](TT-A3L-T2B%20-%20ASCII%20table%20OCT.png)<br>[TT-A3P-L2R](TT-A3P-L2R%20-%20ASCII%20table%20OCT.png) |
| 4 | Decimal (DEC)<br>[TT-A4L-T2B](TT-A4L-T2B%20-%20ASCII%20table%20DEC.png)<br>[TT-A4P-L2R](TT-A4P-L2R%20-%20ASCII%20table%20DEC.png) |
| 5 | Binary + Hex<br>[TT-A5L-L2R](TT-A5L-L2R%20-%20ASCII%20table%20BIN-HEX.png)<br>[TT-A5P-T2B](TT-A5P-T2B%20-%20ASCII%20table%20BIN-HEX.png) |
| 6 | Binary + Hex + Decimal<br>[TT-A6L-L2R](TT-A6L-L2R%20-%20ASCII%20table%20BIN-HEX-DEC.png)<br>[TT-A6P-T2B](TT-A6P-T2B%20-%20ASCII%20table%20BIN-HEX-DEC.png) |
| 7 | Binary + Hex + Decimal + Octal<br>[TT-A7L-L2R](TT-A7L-L2R%20-%20ASCII%20table%20BIN-HEX-DEC-OCT.png)<br>[TT-A7P-T2B](TT-A7P-T2B%20-%20ASCII%20table%20BIN-HEX-DEC-OCT.png) |
| 8 | Binary + Hex + Decimal, additionally marked with RFC 3986 info (reserved/unreserved characters for URL encoding)<br>[TT-A8L-L2R](TT-A8L-L2R%20-%20ASCII%20table%20BIN-HEX-DEC-RFC3986.png)<br>[TT-A8P-T2B](TT-A8P-T2B%20-%20ASCII%20table%20BIN-HEX-DEC-RFC3986.png) |
| 9 | Binary + Hex + Decimal, 1963 edition<br>[TT-A9L-L2R](TT-A9L-L2R%20-%20ASCII%20table%20BIN-HEX-DEC-1963.png)<br>[TT-A9P-T2B](TT-A9P-T2B%20-%20ASCII%20table%20BIN-HEX-DEC-1963.png) |
| A | Binary + Hex + Decimal, 1968 edition<br>[TT-AAL-L2R](TT-AAL-L2R%20-%20ASCII%20table%20BIN-HEX-DEC-1968.png)<br>[TT-AAP-T2B](TT-AAP-T2B%20-%20ASCII%20table%20BIN-HEX-DEC-1968.png) |
| B | Binary + Hex + Decimal, 1963 vs. 1968 comparison<br>[TT-ABL-L2R](TT-ABL-L2R%20-%20ASCII%20table%20BIN-HEX-DEC-1963+1968.png)<br>[TT-ABP-T2B](TT-ABP-T2B%20-%20ASCII%20table%20BIN-HEX-DEC-1963+1968.png) |

Two additional special tables:

- **6th digit / prefixes** – highlights prefixes and the sixth digit.<br>[TT-APL-L2R](TT-APL-L2R%20-%20ASCII%20table%20BIN-HEX-DEC%20-%206th%20digit.png)
- **for media** – a variant created specifically for workshops (for explaining and working through further parts).<br>[TT-AVL-L2R](TT-AVL-L2R%20-%20ASCII%20table%20BIN-HEX-DEC%20-%20for%20media.png)

### Why two editions (1963 / 1968)?

ASCII was revised several times after its initial adoption in 1963. The 1963
edition still defines code points 0x5E/0x5F as arrows (`↑`, `←`), whereas the
later 1968 revision assigns them the now-familiar `^` and `_`. The
"1963+1968" table places both editions side by side for comparison.
