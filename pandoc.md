# Pandoc

```bash
pandoc -s -o JB-2023-08-22.docx JB-2023-08-22.md
```

```bash
pandoc -s -o JB-2023-09-05.docx JB-2023-09-05.md
```

```bash
pandoc -s -o JB-2023-09-21.docx JB-2023-09-21.md
```

```bash
pandoc -s -o JB-2023-09-21.pdf JB-2023-09-21.md
```

```bash
pandoc JB-2023-11-03.md -o JB-2023-11-03.pdf --pdf-engine=xelatex -V colorlinks -V urlcolor=blue
```

```bash
pandoc JB-2023-11-03.md -o JB-2023-11-03.pdf --pdf-engine=xelatex -V geometry:"top=1in, bottom=1in, left=1.25in, right=1.25in"
```

```bash
pandoc JB-2023-11-03.md -o JB-2023-11-03.pdf --pdf-engine=xelatex \
-V geometry:"top=1in, bottom=1in, left=0.75in, right=0.75in" \
-V colorlinks -V urlcolor=blue
```

```bash
pandoc JB-2023-11-03.md -o JB-2023-11-03.pdf --pdf-engine=xelatex \
-V geometry:"top=1in, bottom=1in, left=0.5in, right=0.5in" \
-V colorlinks -V urlcolor=blue -V pagestyle=empty
```

```bash
pandoc JB-2024-01-31.md -o JB-2024-01-31.pdf --pdf-engine=xelatex \
-V geometry:"top=1in, bottom=1in, left=0.5in, right=0.5in" \
-V colorlinks -V urlcolor=blue -V pagestyle=empty
```

```bash
pandoc JB-2024-02-12.md -o JB-2024-02-12.pdf --pdf-engine=xelatex \
-V geometry:"top=1in, bottom=1in, left=0.5in, right=0.5in" \
-V colorlinks -V urlcolor=blue -V pagestyle=empty
```

```bash
pandoc JB-2024-02-12.md -o JB-2024-02-12.docx --pdf-engine=xelatex \
-V geometry:"top=1in, bottom=1in, left=0.5in, right=0.5in" \
-V colorlinks -V urlcolor=blue -V pagestyle=empty
```