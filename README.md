# Forgotten Brilliance
### *Women Scientists Who Shaped the World — and Didn't Get the Credit*

> *"Science and everyday life cannot and should not be separated."*
> — **Rosalind Franklin**

---

A typeset research report and motivational document celebrating fourteen women scientists whose discoveries changed the world — many of whom were denied credit, excluded from Nobel Prizes, or had their work published under someone else's name. Compiled for educational use, with a dedicated chapter on the **Hidden Figures** of NASA's Apollo programme.

---

## Contents of this Repository

```
forgotten-brilliance/
│
├── women_scientists_final.pdf      ← Compiled report (ready to read)
├── women_scientists_final.tex      ← Full LaTeX source
│
├── rosalind_franklin.jpg
├── lise_meitner.jpg
├── emmy_noether.jpg
├── cecilia_payne.jpg
├── chien_shiung_wu.jpg
├── jocelyn_bell_burnell.jpg
├── hedy_lamarr.jpg
├── alice_ball.jpg
├── katherine_johnson.jpg
├── nettie_stevens.jpg
├── esther_lederberg.jpg
├── hertha_ayrton.jpg
├── dorothy_vaughan.jpg
└── mary_jackson.jpg
```

---

## The Scientists Covered

| Scientist | Years | Field | What Was Taken |
|---|---|---|---|
| **Rosalind Franklin** | 1920–1958 | Chemistry / X-ray Crystallography | Photo 51 used without consent; Nobel denied |
| **Lise Meitner** | 1878–1968 | Nuclear Physics | Co-discovered fission; Nobel given to Hahn alone |
| **Emmy Noether** | 1882–1935 | Mathematics | Barred from positions for years; lectured under a man's name |
| **Cecilia Payne-Gaposchkin** | 1900–1979 | Astrophysics | Forced to retract her own discovery; credit taken by supervisor |
| **Chien-Shiung Wu** | 1912–1997 | Experimental Physics | Proved parity violation; Nobel went to Lee & Yang |
| **Jocelyn Bell Burnell** | 1943– | Radio Astronomy | Discovered pulsars; Nobel awarded to supervisor Hewish |
| **Hedy Lamarr** | 1914–2000 | Communications Engineering | Invented the basis of Wi-Fi; patent expired, no royalties |
| **Alice Ball** | 1892–1916 | Pharmaceutical Chemistry | First leprosy treatment; renamed "Dean Method" by supervisor |
| **Nettie Stevens** | 1861–1912 | Genetics | Discovered XY chromosomes; credit diluted by Morgan & Wilson |
| **Esther Lederberg** | 1922–2006 | Microbiology | Lambda phage, replica plating; Nobel given to husband Joshua |
| **Hertha Ayrton** | 1854–1923 | Physics / Engineering | Rejected from Royal Society for being a married woman |
| **Katherine Johnson** | 1918–2020 | Mathematics / Orbital Mechanics | Calculated Apollo 11 trajectory; invisible for decades |
| **Dorothy Vaughan** | 1910–2008 | Mathematics / Programming | NASA's first Black supervisor; credit obscured by segregation |
| **Mary Jackson** | 1921–2005 | Aerospace Engineering | NASA's first Black female engineer; had to petition to attend class |

---

## Report Structure

The PDF is a fully typeset LaTeX document (~45 pages) with the following sections:

- **Cover Page** — typeset in deep plum and gold
- **Foreword** — a direct message to students
- **Individual Profiles** — one page per scientist, with portrait, key facts, pull-quotes, and Wikipedia links
- **The Hidden Figures** — dedicated chapter on Katherine Johnson, Dorothy Vaughan, and Mary Jackson and their role in the Apollo programme
- **Structural Barriers** — an analysis of *why* this kept happening (the Nobel structure, the "assistant trap", compounding exclusions)
- **Motivational Lessons** — seven lessons drawn from these stories, addressed to students
- **Quick Reference Table** — all fourteen scientists at a glance
- **Further Reading** — books, academic papers, documentaries, and online resources
- **Full References** — 26 cited sources in academic format
- **Back Cover**

---

## Compiling from Source

You will need a LaTeX distribution installed:
- **Linux:** `sudo apt install texlive-full`
- **macOS:** [MacTeX](https://www.tug.org/mactex/)
- **Windows:** [MiKTeX](https://miktex.org/) or [TeX Live](https://www.tug.org/texlive/)

Clone the repository and compile:

```bash
git clone https://github.com/your-username/forgotten-brilliance.git
cd forgotten-brilliance

# Compile twice — first pass builds content, second resolves TOC and references
pdflatex women_scientists_final.tex
pdflatex women_scientists_final.tex
```

The portrait JPGs must be in the **same directory** as the `.tex` file. If any image is missing, the document compiles with a labelled placeholder box instead.

### Packages required

The document uses standard packages available in any full TeX Live / MiKTeX installation:

`xcolor` · `graphicx` · `tcolorbox` · `fancyhdr` · `titlesec` · `hyperref` · `enumitem` · `multicol` · `mdframed` · `tabularx` · `booktabs` · `colortbl` · `geometry` · `setspace` · `tikz` · `eso-pic`

---

## Image Credits

All portrait photographs are sourced from **Wikimedia Commons** under their respective licences (public domain, CC BY-SA, or CC BY). Each image URL is documented in a comment in the `.tex` source file above the relevant scientist's section.

| Image | Source |
|---|---|
| Rosalind Franklin | Wikimedia Commons — MRC Laboratory of Molecular Biology |
| Lise Meitner | Wikimedia Commons — Public Domain |
| Emmy Noether | Wikimedia Commons — Public Domain |
| Cecilia Payne-Gaposchkin | Wikimedia Commons — Smithsonian Institution |
| Chien-Shiung Wu | Wikimedia Commons — Public Domain (US Government) |
| Jocelyn Bell Burnell | Wikimedia Commons — CC BY-SA 2.0 |
| Hedy Lamarr | Wikimedia Commons — Public Domain |
| Alice Ball | Wikimedia Commons — University of Hawaii |
| Katherine Johnson | Wikimedia Commons — NASA (Public Domain) |
| Nettie Stevens | Wikimedia Commons — Public Domain |
| Esther Lederberg | Wikimedia Commons — Stanford University |
| Hertha Ayrton | Wikimedia Commons — Public Domain |
| Dorothy Vaughan | Wikimedia Commons — NASA (Public Domain) |
| Mary Jackson | Wikimedia Commons — NASA (Public Domain) |

---

## Motivation

This document was created as an educational and motivational resource — particularly for **female students in STEM** who may feel that the field was not built for them. The history documented here is a history of injustice, but also of extraordinary persistence. Every scientist in these pages kept working despite institutions that locked their doors, committees that handed prizes to the wrong people, and colleagues who published their discoveries under different names.

The truth eventually surfaces. Their names are known now.

---

## A Note of Apology — and an Invitation

This report contains fourteen profiles. History contains thousands more.

We are aware — and deeply sorry — that this list is incomplete. The women featured here are among the most documented cases of overlooked genius in science, but the true extent of this history is far wider than any single document can hold. For every name on these pages, there are many more whose contributions were absorbed into institutions that did not acknowledge them, whose papers were filed under someone else's name, or whose records were simply never kept.

**The absence of a name from this report is not a judgement of importance.**

---

### Do You Know Someone We Missed?

**Help us grow this list.**

If you know of a woman scientist whose story belongs here — a researcher whose credit was taken, a mathematician who was barred from the room, an engineer whose name was erased — we want to hear from you.

- **Open an issue** with the scientist's name, field, and a brief description of her contribution and the injustice she faced
- **Submit a pull request** with a new profile written in the same style, with at least two verifiable sources cited
- **Share this document** with students, teachers, and researchers who may know names that we do not

The only requirement is accuracy. Every claim must be sourced. These women deserve to be remembered correctly.

Some names already waiting to be added:

> Williamina Fleming · Vera Rubin · Maryam Mirzakhani  
> Sau Lan Wu · Wangari Maathai · Françoise Barré-Sinoussi  
> Chandra Prescod-Weinstein · Tu Youyou · Rosalyn Yalow  
> Mileva Marić · Trotula of Salerno · Eunice Newton Foote  
> *…and countless others whose names we do not yet know.*

---

Corrections to biographical details, additional scientists to include, or improvements to the LaTeX typesetting are all welcome via pull request. Please include a source citation for any factual additions.

---

## Licence

The **LaTeX source and compiled PDF** are released under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). You are free to share, adapt, and build upon this work for any purpose, including commercial use, provided appropriate credit is given.

Portrait images retain their **original Wikimedia licences** — see the table above.

---

## Acknowledgement

This report was researched, written, typeset, and fact-checked using **[Claude Sonnet 4.6](https://www.anthropic.com)** by Anthropic, on **23 March 2026**.

---

*Compiled for educational use, 2026 · Contributions welcome*
