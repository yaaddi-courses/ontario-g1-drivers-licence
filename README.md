# Ontario G1 Driver's Licence

Get ready for the Ontario G1 knowledge test and the road ahead: licensing steps, traffic signs, lights and markings, rules of the road, safe and legal driving, and what the road tests check.

Part of the [Yaaddi](https://github.com/yaaddi-courses) course catalog: a spaced-repetition flashcard course, ready to build and validate with the standard Yaaddi course tooling.

## Sources and accuracy

- Rules, distances, speeds and penalties come from the Official MTO Driver's Handbook on ontario.ca (checked 2026-10-02).
- The format of the G1 knowledge test (40 questions, 20 on signs and 20 on rules, 16 correct in each section) is taken from secondary sources because the official site could not be read; check DriveTest or ServiceOntario for the current format and fees.
- Road sign images are Ontario Traffic Manual designs from Wikimedia Commons (public domain); traffic light, pedestrian signal and pavement marking diagrams are original drawings. See `ATTRIBUTIONS.md`.
- Ontario only. Other provinces use different rules and tests. This course is study help, not an official test.

This course is study help, not professional advice. See the [Terms of use](https://courses.yaaddi.com/terms/).

## Structure

- `meta.json`: course metadata (title, description, cover image, version)
- `source/`: authoring source (`meta.csv`, `units.csv`, `cards.csv`, `glossary.csv`, images)
- `plan.csv`: table of contents (not shipped in the zip)
- the built `.zip`: generated from `source/` via `build_course_zip.py`

## Editing this course

```bash
python validate_course.py . --source
python build_course_zip.py .
```
