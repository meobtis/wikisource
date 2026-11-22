# wikisource

Transcriptions of Nepal Bhasa (Newar) manuscripts from [Wikisource](https://wikisource.org/wiki/Wikisource:Main_Page/%E0%A4%AE%E0%A5%81%E0%A4%96%E0%A5%8D%E0%A4%AF_%E0%A4%AA%E0%A5%83%E0%A4%B7%E0%A5%8D%E0%A4%A0/%E0%A4%A8%E0%A5%87%E0%A4%AA%E0%A4%BE%E0%A4%B2_%E0%A4%AD%E0%A4%BE%E0%A4%B7%E0%A4%BE)
(Category: Nepal bhasa), converted to Markdown for the [MEOBTIS](https://meobtis.github.io) index of Buddhist texts in Sanskrit.

The pages are manuscripts in Prachalit and Devanāgarī script digitised with UNESCO and the Asha Archives, transcribed
by volunteers (some by automatic transcription, some proofread). Of the 87 Index pages in the category, 57 have
transcribed pages and are converted here, one file per Index with its pages in order and page markers
(`<!-- page N -->`). Each file's front matter gives the Wikisource Index page, the scan, the number of pages and
their proofreading levels (Wikisource's levels 1–4; level 3 is proofread, level 4 validated).

Wikisource labels the whole category `new` (Nepal Bhasa), but the manuscripts are in several languages. For the 16
Buddhist texts the `language` field was assessed by reading samples: `sa` (Sanskrit: the Tārā stotra, Pañcarakṣā,
Amoghapāśahṛdaya, Nāmasaṅgīti, the Mahāyāna sūtra on the Dharmarāja story, the Karuṇāmaya path, the Divyāvadāna
story collection and the Uposadha vrata), `mixed` (Sanskrit with Newar glosses or songs: Caryāgīti, Bali Rāja
sambodhana, Guṇakāruṇamaya) or `new` (Newar prose with Sanskrit verses: Svayambhū Purāṇa, Aṣṭamī vrata kathā, Kapiśa
and Vicitrakarṇī avadāna, Vasundharā kathā). The other 41 files are `unassessed` (they are not Buddhist; most are
Newar songs and tales). The automatic Nepali and English machine translations that Wikisource's transcription adds
after the manuscript text on each page were removed from these 16 files (the count is `machine_translations_removed`);
they remain in the first commit. The pages Wikisource had left as unproofread OCR in five of the Sanskrit and mixed texts (Pañcarakṣā, Kāraṇḍavyūha,
Uposadha vrata, Bali Rāja, Guṇakāruṇamaya; 194 pages) were re-read against the manuscript scans and rewritten; the
front matter says `proofread` and the corrections are in `errata/`. The manuscripts are in difficult hands (several
of them Prachalit), so some readings are uncertain, `…` marks illegible words, and the pages should still be
checked by a second reader. The IAST files were regenerated from the corrected text.

Each file has `buddhist: true` or `false`; the MEOBTIS index lists the Sanskrit
Buddhist ones.

See [CATALOG.md](CATALOG.md) for the list.
