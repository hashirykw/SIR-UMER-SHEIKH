# Sir Umar Sheikh · Islamiyat website

A multi-page site for Sir Umar Sheikh: Cambridge O Level Islamiyat 2058, IGCSE 0493 and AS & A Level Islamic Studies 9488, Karachi and online. Every page is one self-contained HTML file in one flat folder: styles, scripts and graphics are inside each page. No admin panel, no database.

## Files

| File | What it is |
|---|---|
| `index.html` | Home: Sūrah al-Ikhlāṣ in Arabic and English as the hero beside a hand-drawn geometric rosette, the “same answer, with its evidence” reference switch, both papers mark by mark, the 15 set passages explorer, the Seerah and Caliphs timeline (570–661), where he teaches, demo-class call to action |
| `courses.html` | Paper 1 and Paper 2 question by question, assessment objectives, the four 9488 papers, how classes run |
| `syllabus.html` | All 15 set passages (Arabic for al-Fātiḥah, al-Ikhlāṣ and al-Kawthar), all 20 set hadith, the 8 topics, the Articles of Faith and the Pillars, with a progress tracker and search |
| `past-papers.html` | Every 2058 session 2018–2026, 9488 archives, score log by variant with grade estimates and trend chart, June 2026 grade thresholds, a mark-weighted exam timer |
| `study-room.html` | Passage sorter (group A/B/C), hadith match, Seerah ordering drill, 20 key-term flashcards |
| `about.html` | His method, experience and social links |
| `contact.html` | Enrolment / demo-class form that opens a ready-written WhatsApp message, FAQ |
| `404.html` | Not-found page |
| `umar-sheikh.jpg` | Share image for WhatsApp and social previews (1200 × 630) |
| `vercel.json`, `robots.txt`, `sitemap.xml` | Hosting and search files |

Every page also has dark (default) and light themes, a `/` or Ctrl K search over pages, passages, hadith and tools, an “Ask a question” helper with WhatsApp hand-off, smooth scrolling and view transitions.

## Confirm with Sir Umar before launch

1. **WhatsApp 0334 344 5972** (main, from his Facebook and Instagram) and **0330 672 3344** (second, from Instagram). To change, find and replace `923343445972` / `0334 344 5972` across the HTML files.
2. **Photo.** No downloadable photo was available, so the site is designed without one (the rosette and the verse carry the hero). If he wants his photo, send a clear portrait and it can go into the hero and the About page.
3. **Institutions.** Alpha College and the Alpha Schools Network, Studere Academy, Cambridge Online, Averroes Institute, Kashan’s Academy (May/June 2024 batch), Signature Institute, and earlier Beaconhouse and The City School: all from public pages. Remove any he no longer teaches at.
4. **“More than fifteen years”** is from Studere Academy and Cambridge Online.
5. **Fees** are never shown; every fee question goes to WhatsApp.
6. **Domain.** Canonical links, the sitemap and robots use `https://sir-umar-sheikh.vercel.app`.

## Content notes

- Passage and hadith lists follow the appendices of the Cambridge 2058 syllabus for 2026–2027. Themes, hadith meanings, card definitions and the zakāt example paragraph are written for this site; the hadith page asks students to learn the exact wording from their notes.
- Qur’an translation: Marmaduke Pickthall (1930). Arabic text is shown for al-Fātiḥah, al-Ikhlāṣ and al-Kawthar.
- 9488 details are from Cambridge’s 2024–2026 and 2027–2029 syllabuses.
- Grade thresholds are Cambridge’s June 2026 2058 table.
- Past papers link to PapaCambridge session pages (© UCLES) with PastPapers.co as a mirror; 9488 papers link to Save My Exams and CIE Notes.
- Visitor progress is saved in the visitor’s browser only.

## Deploy

Upload every file to the root of a GitHub repo and import it on Vercel (Framework preset: Other, no build command). `vercel.json` turns on clean URLs.

Website by Nexlyr Solutions.
