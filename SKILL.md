---
name: early-music-ipa-guide
description: Apply an intermediate-level, historically informed IPA pronunciation workflow to uploaded early-music sheet music, producing a singer-ready text/IPA/English guide.
---

# Early Music IPA Guide

## Trigger

Use when the user uploads a score or sheet-music image/PDF and asks for an IPA guide, historical pronunciation, or a singer's pronunciation worksheet. Apply the workflow to the uploaded music immediately; do not merely explain the workflow. Default to **intermediate** level unless the user requests beginner or expert.

## Objective

Create a practical, historically informed pronunciation guide that an early-music singer can rehearse from. The deliverable should preserve the score's printed text, provide IPA appropriate to its language and historical setting, and explain the sounds that matter for performance.

## Workflow

### 1. Inspect the source

Read all supplied pages, including title, composer attribution, date, editorial notes, and all vocal text. Identify voices, verses, repetitions, and syllabic underlay. Do not guess at illegible words or missing notes. Mark uncertain readings and request a clearer crop only if needed to proceed responsibly.

### 2. Establish a pronunciation brief

Identify the language and historical stage (not merely its modern name), approximate date, likely geographic or liturgical tradition, and relevant source/editorial context. Select and name a defensible pronunciation convention. For Latin, specify Italianate, French, German, English, or other tradition as appropriate; do not assume one universal Latin sound. For historical vernaculars, do not silently substitute modern pronunciation.

Label the IPA as a **historically informed reconstruction** when appropriate. Note meaningful regional variation, competing reconstructions, and the confidence of the selected convention. Do not claim scholarly certainty that the source does not warrant.

### 3. Transcribe faithfully

Preserve original spelling, capitalization, punctuation, word order, and repetitions in the text column. Do not silently normalize archaic spellings. Keep line and phrase boundaries aligned with the music where practical. Distinguish printed text from editorially supplied syllabification or reconstructed readings.

### 4. Produce intermediate IPA

For each line or short musical phrase, supply:

- **Original text:** exactly as printed.
- **IPA:** consistent transcription in the chosen historical convention.
- **English:** concise meaning or translation.

Use IPA rather than English respelling. Mark syllable boundaries where helpful for singing. Indicate stress, nasalization, consonant values, elision, vowel quality, and length only where supported and relevant. Preserve the printed syllabic underlay rather than reshaping it to fit modern speech. If a historically plausible alternative changes how the singer would pronounce a word, show it briefly.

### 5. Add a piece-specific pronunciation key

Explain only the distinctive sounds and rules actually present in the music. Prioritize vowel placement, consonants, historical sound changes, final consonants, nasal vowels, diphthongs, stress, and liaison/elision as relevant. Use words from the score as examples. Make explanations usable by an intermediate singer, not a phonology specialist.

### 6. Add performance notes

Note melismas, repeated syllables, word-to-note underlay ambiguities, and consonant preparation/release when the score supports them. Never invent precise note-to-syllable alignment if the image is too unclear. If the score has multiple voices with different text, treat each distinct text passage appropriately.

### 7. Verify and disclose limits

Check that every visible sung word and repetition is represented; that IPA matches the chosen language/period/tradition; that similar spellings are handled consistently; and that translations do not invent meaning. Distinguish source readings, editorial interpretation, and historical reconstruction. Cite actual historical/linguistic references if consulted; do not invent citations. If no external references were consulted, say that the IPA is a working reconstruction.

## Default deliverable

Create a clean, singer-friendly guide with these sections:

1. **Work and pronunciation brief** — title, attribution as printed, language, approximate period, selected tradition, confidence and caveats.
2. **Text | IPA | English** — three-column table, one musical phrase per row where possible; preserve printed spelling.
3. **Pronunciation key** — short practical explanations illustrated with the work's own words.
4. **Performance notes** — underlay, melismas, elision, consonant timing if applicable.
5. **Uncertainties / alternate readings** — only significant ones.
6. **Basis / references** — actual sources used and reconstruction status.

If the user requests a downloadable document, make a clean, editable DOCX (Google Docs compatible) and optionally a PDF. Otherwise present the guide in chat. Never claim a file has been made without creating and verifying it.

## Levels

- **Beginner:** include articulation descriptions and simple comparisons; explain IPA symbols while keeping the transcription.
- **Intermediate (default):** accurate, readable IPA, important historical differences, focused singer notes, minimal scholarly digression.
- **Expert:** discuss historical phonology, dialect/source variants, alternate reconstructions, editorial choices, and scholarly evidence in greater depth.

## Interaction policy

Start work from the uploaded score without requesting a separate transcription. If a key choice is unresolved, choose the best-supported provisional option and disclose it; ask one focused question only when that choice materially changes the outcome. Do not automatically assume the score is Latin, Italian, or modern French. Do not mistake repertoire attribution for text or language evidence.

## Suggested invocation

“Apply the early-music-ipa-guide skill to this score at intermediate level. Preserve the printed text, identify its historical pronunciation tradition, and give me a singer-ready Original / IPA / English guide with a concise pronunciation key.”
