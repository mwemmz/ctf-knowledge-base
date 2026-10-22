# CTF Knowledge Base

A personal, private archive of CTF/pentest writeups and notes, aggregated from
several public GitHub repositories and sorted by technique/category for quick
reference.

See **[INDEX.md](INDEX.md)** for the full categorized listing (810 items across
10 categories).

## What this is

- Only text and code artifacts were kept: writeups (`.md`/`.txt`), notes, and
  solver/exploit scripts. Screenshots, packet captures, and other binary
  evidence were intentionally left out to keep this lightweight.
- Every item folder has its own `SOURCE.md` pointing back to the original
  repo, the original file path, and which category it was auto-sorted into.
- Categorization (`active-directory`, `web`, `pwn`, `reverse-engineering`,
  `crypto`, `forensics`, `privilege-escalation`, `network`, `osint`, `misc`)
  was done automatically via keyword + path heuristics, **not hand-reviewed
  per item**. Expect some miscategorized items, especially under `misc` --
  treat this as a first draft to refine over time, not a finished product.

## Structure

```
challenges/<category>/<source-repo>__<item-name>/   -- solved CTF challenges & box writeups
reference/<category>/<source-repo>__<item-name>/    -- cheat sheets / general notes (not tied to one challenge)
INDEX.md                                             -- full linked listing
```

## Attribution

All content originates from the public repositories listed in
[INDEX.md](INDEX.md#sources) and remains the work of their original authors.
This archive is for personal/private reference only; each item retains a
link back to its source. Nothing here is republished or claimed as original
work.

## Source repositories

- [Ciyah/CTFChall-Writeups](https://github.com/Ciyah/CTFChall-Writeups)
- [Ben-Ammar-Sabri/pentest-labs-writeups](https://github.com/Ben-Ammar-Sabri/pentest-labs-writeups)
- [Adamkadaban/CTFs](https://github.com/Adamkadaban/CTFs)
- [Drew-Alleman/write-ups](https://github.com/Drew-Alleman/write-ups)
- [Ednas/WriteUps](https://github.com/Ednas/WriteUps)
- [The-Viper-One/Pentest-Everything](https://github.com/The-Viper-One/Pentest-Everything)
- [edoardottt/tryhackme-ctf](https://github.com/edoardottt/tryhackme-ctf)
- [kurohat/writeUp](https://github.com/kurohat/writeUp)
- [migueltc13/TryHackMe](https://github.com/migueltc13/TryHackMe)
- [sarperavci/CTF-Writeups](https://github.com/sarperavci/CTF-Writeups)

Note: `sckull/sckull.github.io` was excluded -- it's a fully rendered static
blog (4.3GB, ~2,600 HTML pages, no raw markdown source available), not a
practical fit for this archive. Link: https://github.com/sckull/sckull.github.io
