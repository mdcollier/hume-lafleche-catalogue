La Flèche pages of the Historical Libraries Project: public data files

Public registers of the La Flèche pages of the Historical Libraries Project: works, their witnesses, studies, comparisons with Hume, open questions in the project's records, and the coverage counts. Each value is shown as the site's pages show it. The texts the pages name are working machine-read texts produced by optical character recognition; they have not been verified against the page images and are not editions.

These pages record textual relations that may warrant historical investigation. They are not evidence that Hume read, used, borrowed from, recalled or replied to any of these books.

To cite the site, see the About / Citation page.

Generated from the works register and the study register of the La Flèche pages, as the pages display them. Data of 2026-11-17.
In the CSV files, lists are joined with "|" and statistics are given as "label: value". The JSON files hold the same rows, with lists as lists.

works.csv, works.json (104 rows): One row per indexed work: the works with a page, then the works selected and not yet processed (these have no page, and only what the works index shows of them is given).
  id: the work's identifier, as in its page address (works with a page only)
  author: author, as on the work page or the works index
  author_short: short form of the author's name, as in the works index
  title: title
  date: date of the catalogue entry or, for a contextual text, of the work
  holding: what the catalogue records of the work, as the work page states it
  catalogue_entry: catalogue entry
  catalogue_section: catalogue section
  date_as_catalogued: date as catalogued
  period: period, as the work page states it
  stage: how far the project's work on it has gone, as the works index states it
  screening_outcome: outcome of the first screening against Hume's texts, as the works index states it
  paragraphs: paragraphs of the current machine-read text
  current_witnesses: number of current witnesses
  text_status: whether a text is published on this site, as the work page states it
  work_page: address of the work page
  published_text: address of the published text, where there is one
  comparisons_held: comparisons with Hume held, as the works index shows it
  comparisons_read_in_context: of those, read in context, where the work page states it
  reason_not_processed: for a work selected and not yet processed, the reason recorded

witnesses.csv, witnesses.json (64 rows): One row per witness (a machine-read text made from one scan) shown on a work page.
  work_id: the work
  label: label of the witness
  date_in_record: date in the text's record
  status: status of the witness
  scan_address: address of the scan
  scan_held_at: where the scan is held
  copy_record: date and imprint in the holder's record of the scanned copy
  copy_record_source: that record, and when it was looked up
  copy_differs: the work page's mark where the copy's date differs from the date in the text's record
  holdings_or_provenance: what the holder's catalogue says of its holdings, or, for an Internet Archive text published here, what the Archive's record gives as imprint and date
  catalogue_record: address of the catalogue record
  paragraphs: paragraphs of this witness
  note: note on the witness

studies.csv, studies.json (78 rows): One row per study listed on the studies page. Corrections are on the study pages and the corrections page.
  id: the study's identifier, as in its page address
  title: title
  kind: kind of study
  question: the question
  what_was_done: what was done
  result: result
  result_summary: summary of the result
  status: status
  works: works the study concerns (identifiers)
  hume_scope: the part of Hume concerned
  period: when the study was made
  lessons: lessons
  statistics: methodological statistics, as label: value

comparisons.csv, comparisons.json (53 rows): One row per comparison, as the comparisons page shows it.
  id: project record of the comparison
  work_id: the work
  source_paragraphs: paragraphs of the French text, numbered as in the project's machine-read text
  hume_passage: Hume passage nominated, exactly as shown (by section only where no paragraph is shown)
  inventory_status: inventory status
  reading: whether the comparison was read in context
  zones: zones the comparison belongs to
  paragraph_links: addresses of the source paragraphs in the published working text, where they are linked

open_questions.csv, open_questions.json (10 rows): One row per open question in the project's records, as the corrections page lists them.
  id: identifier
  opened: date opened
  status: status
  statement: the question
  works: works it concerns (identifiers)
  studies: studies it concerns (identifiers)

coverage.csv, coverage.json (8 rows): The coverage counts of 'How the numbers fit together', with their terms.
  step: the step
  count: the count
  label: what is counted
  definition: the definition of the term, where the block gives one
  also: the further counts the block gives

