# Stampa: orders, estimates and costs of print jobs placed with printers

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23398774.svg)](https://doi.org/10.5281/zenodo.23398774)

*Ordini, preventivi e costi dei lavori di stampa affidati agli stampatori*

**db** · 1996–1999 · version 1.0  
Author: **Massimo Sbarbaro** ([ORCID 0009-0006-8965-9013](https://orcid.org/0009-0006-8965-9013))

## Overview

Stampa follows the print jobs that a packaging company commissions from external printers. Each job records printer, customer, material, subject, quantity and order number, purchase and sale price of the printing cylinders and of the set-up, reel width and inner and outer diameters, number of colours, coverage, repeat length, proof, pallet, weight and labels, with estimate and job dates. The jobs can be searched by customer, printer, order, estimate and job number.

I designed and programmed this application in 1996–1999. It is published here in 2026 as part of the documented record of my software work, with a permanent DOI on Zenodo.

## Main functions

- Print-job record with technical data, cylinder and set-up costs and prices (`SDati`).
- Searches by customer, printer, order, estimate and job (`SRCliente`, `SRStampatore`, `SROrdine`, `SRPreventivi`, `SRLavori`).
- Notes and packaging details (`SNote`, `SScatola`).
- Printed list of the jobs (`RGenerale`, `Rstampe`).

## Data

Table `TGenerale` (print jobs).

## Technology

db, 2.0 format (.mdb), forms, reports and macros.

## Repository contents

| Path | Content |
|---|---|
| `database/` | The database application, emptied of all data. |
| `source/queries/` | SQL of the saved queries. |
| `docs/schema.md` | Tables and fields. |

## What is not included

The database is published **empty**: every table has been emptied, the file compacted and the unused space inside its pages overwritten with zeros, so no record of the original data survives. Logos of the organisations for which the program was built have been blanked inside the forms, and the names of organisations, people and places in captions and code have been replaced with neutral text of the same length; the application is otherwise the original file. The file is in the version 2.0 db format (1994): it opens with versions 2.0, 95 and 97 of the database software and can be converted by the 97–2003 versions; later versions cannot open it.

## How to cite

Use the citation metadata in [`CITATION.cff`](CITATION.cff) (GitHub: *Cite this repository*). The release is archived on Zenodo with the DOI [10.5281/zenodo.23398774](https://doi.org/10.5281/zenodo.23398774).

> Sbarbaro, Massimo. 1999. *Stampa: orders, estimates and costs of print jobs placed with printers*. Software (db, 1996–1999), version 1.0. Zenodo. https://doi.org/10.5281/zenodo.23398774.

## License

Released under the [MIT License](LICENSE). © 1996 Massimo Sbarbaro.
