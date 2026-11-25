# ANNOUNCEMENT SYSTEM PRD
Nov 25, 2026 · *Omoju Oluwamayowa Samuel*
## Document info

| Field | Value |
| --- | --- |
| Product / feature name | Announcement System |
| Author / owner | SEN Group III |
| Team / contributors | Ilori Inioluwa, Albert Jeremiah, Abdulqayyum Olaoye, Adedeji Adebayo, Oyedokun Martins, Omoju Oluwamayowa, Samuel Oluwafeyifunmi, OLAPADE ABDULWAKIL, Oredawi Muhammad, Nwadimkpa Jennifer |
| Status | In Progress |
| Version | 0.1 |
| Created | Friday, 20th of November, 2026  |
| Last updated | Nill |
| Reviewers / approvers | Lecturer(s) |

## 1. Overview

Announcement System

Used for passing information regarding lectures, projects, timetable changes directly to students via a whatsapp message. 

## 2. Problem statement

- **Who has the problem:** University Students.
- **What the problem is:** Passing information is not done orderly and most methods like whatsapp groups have other unimportant information often mixed in.
- **How they cope now:** Whatsapp Group chats.
- **Why it matters:** Unimportant info mixed in, Multiple tags over and over.
- **Evidence:** // No clue. Speculative from me but here's an example: We had a class on Wednesday 25th November that was originally 10am - 12pm but it was moved forward to 8am - 10am and no information was passed along.

## 3. Goals, non-goals and success metrics
**Goals**

1. Students learn about timetable changes within a short duration (especially since it's sent to regular DM's)
2. Logs and previous messages can be preserved better than a whatsapp group chat
3. Information can be organized and made as clean as possible

**Non-goals (out of scope for this version)**

- No payments
- No app
- No complicated user system

## 4. Target users and user stories

| Persona | Who they are | Main need | Pain today |
| --- | --- | --- | --- |
| \[e.g. Student\] | \[200-level undergraduate\] | \[Know class times and changes\] | \[Updates get lost in busy group chats\] |
| \[e.g. Course rep\] | \[Student who relays info\] | \[Reach the whole class quickly\] | \[Unorganized information\] |
| \[e.g. Lecturer / admin\] | \[Staff member\] | \[Announce changes once\] | \[No direct channel to students\] |

**User stories**

- As a \[student\], I want to \[get a reminder before each class\] so that \[I never miss one\].
- As a \[course rep\], I want to \[post one update to everyone\] so that \[I don't message people individually\].

## 5. Functional requirements

| ID | Requirement | Linked user story | Priority | Acceptance criteria |
| --- | --- | --- | --- | --- |
| FR-01 | \[e.g. Course rep can post a timetable update\] | \[Course rep\] | Must have | \[Update visible to all class members immediately\] |
| FR-02 | \[e.g. Students get a reminder when there's a chleange in schedu\] | \[Student\] | Should have | \[Immediately notifies student(s) of changes\] |

## 6. Non-functional requirements

| ID | Category | Requirement |
| --- | --- | --- |
| NFR-01 | Security | \[Passwords hashed; only course reps can post updates\] |
| NFR-02 | Compatibility | \[Works on Android, iOS and desktop browsers\] |

## 7. User flows, design and technical notes

**Key user flows**

1. &#91;Flow name, e.g. Receiving a class update\]
   1. &#91;Course rep logs in\]
   2. &#91;Posts the change\]
   3. &#91;System notifies every student in that class\]

**Design**

- Wireframes / mockups: \[Link to Figma or images\]

**Technical considerations**

- Proposed stack: \[Frontend, backend, database, local deployment\]
- Integrations / APIs: Meta Business API(testing)
- Data to store: announcements, timetable
- Constraints: API limits in testing /  sandbox mode

## 8. Scope and release plan

| Phase | What ships | Owner | Target date |
| --- | --- | --- | --- |
| MVP | \[Must-have requirements only\] | Group 3 | Friday, 27th November, 2026 |

## 9. Risks and dependencies

| Risk or dependency | Impact | Likelihood | Mitigation |
| --- | --- | --- | --- |
| \[e.g. Messaging API approval is slow\] | \[High\] | \[Medium\] | \[Fall back to email notifications\] |

## 10. Team and task assignments


**Team roles**

| Name | Role | Responsibilities | Contact |
| --- | --- | --- | --- |
| \[Omoju Oluwamayowa\] | \[Project lead\] | \[Coordinates the team, owns this PRD\] |
| \[Nwadimkpa Jennifer, Oredawi Muhammad\] | \[Frontend developer\] | \[Builds screens and UI\] |
| \[Albert Jeremiah, Oyedokun Martins\] | \[Backend developer\] | \[APIs, database(Prefferable to just use JSON), integrations\] |
| \[Samuel Oluwafeyifunmi\] | \[UI/UX designer\] | \[Wireframes and mockups\] |
| \[Abdulqayyum Olaoye,  Adedeji Adebayo\] | \[Tester / QA\] | \[Tests against acceptance criteria\] |  |
| \[Ilori Inioluwa, OLAPADE ABDULWAKIL\] | \[Documentation / research\] | \[Survey, report, presentation\] |

**Task tracker**

| ID | Task | Assigned to | Linked requirement | Status | Due date | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| T-01 | Run student survey on the problem | Ilori Inioluwa, Olapade Abdulwakil | Problem statement | Not started | Thursday 26th November | |
| T-02 | Design wireframes and mockups for sign-up and home screens | Samuel Oluwafeyifunmi | FR-01 | Not started | Thursday 26th November | Do before T-03 |
| T-03 | Build frontend screens from the mockups | Nwadimkpa Jennifer, Oredawi Muhammad | FR-01, FR-02 | Not started | Thursday 26th November | |
| T-04 | Set up backend and JSON data storage | Albert Jeremiah, Oyedokun Martins | FR-01, FR-02 | Not started | Thursday 26th November | |
| T-05 | Build notification feature | Albert Jeremiah, Oyedokun Martins | FR-03 | Not started | Thursday 26th November | |
| T-06 | Test MVP and log bugs | Abdulqayyum Olaoye, Adedeji Adebayo | All Must-haves | Not started | Thursday 26th November | Start once first screens work |
| T-07 | Write project report and prepare presentation | Ilori Inioluwa, Olapade Abdulwakil | — | Not started | Thursday 26th November | |
| T-08 | Write PRD, coordinate team and track progress | Omoju Oluwamayowa | — | Not started | Thursday 26th November | |


## 12. Appendix
- Research and survey results: \[Link\]
- Project link: https://github.com/nox-codes/sen-grp-3/