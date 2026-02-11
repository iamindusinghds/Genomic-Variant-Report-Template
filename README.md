Genomic Variant Report Template

This project demonstrates a structured HTML/CSS-based genomic reporting template designed for WES/WGS variant summaries.

Features:

Tabular variant representation (Gene, Chromosome, Position, Classification)

Severity-based classification styling:

🔴 Pathogenic

🟢 Benign

🟠 VUS (Variant of Uncertain Significance)

Clean clinical-style formatting

Designed for integration with Python-based NGS pipelines

Purpose:

To simulate the reporting layer of genomic diagnostics workflows, where variant data (e.g., from VCF files) is formatted into clinician-readable reports.



Clinical WES Report Template

This repository includes a structured Whole Exome Sequencing (WES) clinical report template designed to simulate the reporting layer of an NGS pipeline.

Report Components:

Patient & test information

Variant summary table

ACMG-style classification (Pathogenic, Benign, VUS)

Interpretation section

Methodology description

Professional formatting using HTML & CSS

Pipeline Context:

The template represents the final reporting stage of a genomics workflow:

FASTQ → Alignment → Variant Calling → Annotation → Classification → HTML-based Clinical Report Generation

This structure can be integrated with Python scripts that parse VCF files and automatically generate clinician-readable genomic reports.
