# CalmProctor – Low-Anxiety Online Proctoring

Advanced UI/UX | V Semester B.E. | Problem No. 30

**Student:** Laxmi Mantageri (1EP24CS068), Dept. of CSE
**College:** East Point College of Engineering & Technology
**Faculty:** Prasanth, Assistant Professor

## Links
- Live demo: https://<your-username>.github.io/calmproctor/
- Report: docs/report.pdf
- Slides: docs/slides.pptx
- UI design: docs/ui-design.pdf

## Problem
Online proctoring tools deter cheating but make honest students anxious
through constant surveillance and unexplained automatic flags. This project
designs an exam experience that keeps exams fair while reducing anxiety and
respecting home privacy.

## Key Features
- Plain-language consent: what is and is not recorded
- On-device camera, microphone and network check
- Practice mode before the exam
- Calm status bar with timer and connection state
- Soft check-ins instead of accusations; a human reviews every flag
- Pause and help options; offline auto-save
- Receipt with an appeal option

## Design Principles
1. Be transparent: always show what is recorded and why
2. Ask, don't accuse: flags are gentle check-ins
3. Humans decide: no automatic penalties, appeals built in
4. Recoverable: pause, auto-save and rejoin after failures

## Design Process
Discover, Define, Ideate, Prototype, Test, Reflect.
Accessibility target: WCAG 2.2 AA.

## Tech Stack
HTML, CSS, JavaScript (no frameworks)

## Run Locally
Open the folder in VS Code and use Live Server on `index.html`.
The camera check needs localhost or HTTPS.

## Project Structure
- index.html – page shell
- style.css – styles
- script.js – exam flow logic
- docs/ – report, slides and UI design

## Note
This is a design prototype. It does not record or analyse anything.
