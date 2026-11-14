# ENSLD Exam Simulator

A free, mobile-first practice exam simulator for the **Designing Cisco Enterprise Networks (300-420 ENSLD) v1.1** exam. It is one self-contained HTML file. No install, no account, no server.

> Not affiliated with or endorsed by Cisco. All questions are original practice items written from public study material and current vendor documentation. They are not real exam questions and contain no exam content.

## Features

### Question pool
- **491 original questions** across all five blueprint domains, weighted like the exam (25 / 25 / 20 / 20 / 10 %)
- **Question types:** single answer, multiple response (Choose two or Choose three), and drag and drop (order and match)
- **217 questions with a topology or exhibit.** 77 of them need the exhibit to be answered, the rest show it for context only
- **Three difficulty levels** (102 easy, 220 standard, 169 hard), including 40 multi-constraint design scenarios
- **Detailed explanations** with a reason for every wrong option, 45 step-by-step diagrams (BGP best path, inbound vs outbound steering, PIM, SSM, RPF, STP guards, OSPF area types, SD-WAN bring-up and more), and Further reading links to Cisco design guides, white papers and RFCs

### Practice and exam modes
- **Pick your weak areas** by domain, subtopic or fine-grained tag (BGP path attributes, FHRP, STP, GETVPN, QoS, multicast, automation and more)
- **Mix options:** Weak only, 70 / 30, Blueprint weights, Due for review, Hard only
- **Practice mode** with instant feedback, or **exam simulation** with a timer and no going back
- **Full mock exam:** 60 random questions, 90 minutes, blueprint weights
- **Practice exams A-E:** five fixed 60-question exams with no overlap, so scores are comparable between attempts. Exams D and E are held back from every other mode until you take them, so they stay a clean final check
- **Spaced review:** missed questions come back first, and correct answers return after 1, 3, 7 and 21 days
- **Flag questions** and practise only the flagged ones

### Progress and results
- **Results** by domain and subtopic, time per question (slowest, over budget, rushed misses), and an answer review with your pick next to the correct one
- **Readiness check** per domain: at least 80 % of questions seen and at least 85 % correct on the first try (a rule of thumb, not a pass prediction)
- **Score history and trend chart** for practice exams A-E
- **Progress is saved in your browser** and survives updates to the file. Backup and restore by download (local file) or copy and paste (anywhere)

## How to use

1. Open `index.html` in any modern browser, on a phone or a computer. Or use the live version above.
2. On **Setup**, pick your weak areas, a mix and a mode, then press **Start**.
3. Work through practice sessions, Due for review and Hard only for the subtopics your results flag.
4. Take practice exams A-C under exam conditions to measure progress.
5. Keep **exams D and E for the end.** When their first attempts reach about 85 %, you are in good shape to book. This is a rule of thumb, not a guarantee.

Progress is stored per browser and per copy. To move it to another device or copy, use **Progress → Copy backup text** and **Paste backup text**.

## Host it yourself

Rename the file to `index.html`, push it to this repository and enable **GitHub Pages** (Settings → Pages → Deploy from branch → `main` / root). The simulator then runs at `https://<user>.github.io/<repo>/`.

## Exam facts

| | |
|---|---|
| Exam | 300-420 ENSLD v1.1 |
| Duration | 90 minutes |
| Question count | not published by Cisco (estimates: 55-65) |
| Pass mark | not published by Cisco |
| Blueprint | [Exam topics PDF](https://learningcontent.cisco.com/documents/marketing/exam-topics/300-420-ENSLD-v1.1.pdf) · [Exam page](https://www.cisco.com/c/en/us/training-events/training-certifications/exams/current-list/ensld-300-420.html) |

## Sources

Questions are based on the CCNP Enterprise Design ENSLD 300-420 Official Cert Guide (2nd ed.), the CCDP ARCH guides, the CCDE 400-007 Official Cert Guide and the ENSLD course guide. Facts were checked against current Cisco documentation, Cisco Validated Designs and RFCs. Where newer documentation differs from the books, the newer value is used.

## Versioning

The version badge in the app opens the changelog. Question IDs never change, so saved progress carries over to new versions. When a question's meaning changes, only its own saved result is reset.

## Feedback

Found a wrong answer or a broken link? Open an issue with the question ID shown under the question (for example `b05` or `hd17`).

## License

Suggested: code under the MIT License and question content under CC BY-NC 4.0. Choose what fits your plans before publishing.

Cisco, CCNP and other Cisco marks are trademarks of Cisco Systems, Inc. This project is an independent study aid.
