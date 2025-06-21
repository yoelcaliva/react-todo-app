
---

## Project Name: react-todo-app

## Author: Iosef Yoel Caliva – QA Analyst

**Date:** 2025-05-22

**Version:** 1.0

**Status:** Final

---

## 1. Executive Summary

The TODO App is a lightweight, user-friendly task management application built in React. It enables users to create, read, update, and delete tasks (CRUD operations). The goal is to provide a clean interface for managing personal and professional tasks with features such as task filtering, and local storage.

---

## 2. Goals and Objectives

| Goal | Description |
| --- | --- |
| G1 | Allow users to create and manage TODO items efficiently |
| G2 | Provide a responsive UI for mobile and desktop users |
| G3 | Ensure accessibility (WCAG 2.1 compliance where applicable) |
| G4 | Persist tasks using local storage |
| G5 | Guarantee a high level of reliability and usability via thorough QA testing |

---

## 3. Scope

### In Scope:

- React-based frontend interface
- Add, edit, delete, and mark tasks as completed
- Filter tasks (All / Active / Completed)
- Set task priority levels (Low, Medium, High)
- Store tasks locally or via a REST API
- Basic user feedback (e.g., toast notifications)
- Functional, UI, usability, accessibility testing

### Out of Scope:

- User authentication
- Multi-user collaboration
- Syncing across devices

---

## 4. Functional Requirements (FRs)

| ID | Requirement | Priority | Notes |
| --- | --- | --- | --- |
| FR1 | The user must be able to add a new task with a title and optional description | High |  |
| FR2 | The user must be able to mark a task as complete/incomplete | High |  |
| FR3 | The user must be able to delete a task | High |  |
| FR4 | The user must be able to edit an existing task | High |  |
| FR5 | The app must allow filtering by All, Active, Completed | Medium |  |
| FR6 | The app must allow setting a priority for each task | Medium |  |
| FR7 | All tasks must persist using localStorage or API | High |  |
| FR8 | The app must be responsive on desktop and mobile | High |  |
| FR9 | The app should show visual feedback (e.g., toasts) | Low | Optional |

---

## 5. Non-Functional Requirements (NFRs)

| ID | Requirement | Priority |
| --- | --- | --- |
| NFR1 | The app must load in < 2 seconds on broadband | High |
| NFR2 | The UI must follow accessibility guidelines | High |
| NFR3 | The app must handle invalid inputs gracefully | High |
| NFR4 | The codebase must follow best practices (React + ESLint + Prettier) | Medium |
| NFR5 | The application must support the latest 2 versions of major browsers (Chrome, Firefox, Edge, Safari) | High |

---

## 6. User Stories

| ID | User Story | Acceptance Criteria |
| --- | --- | --- |
| US1 | As a user, I want to add a task so I can remember what to do | Task appears immediately in the list; inputs are cleared |
| US2 | As a user, I want to mark a task complete so I can track progress | Completed tasks are visually differentiated |
| US3 | As a user, I want to delete a task so I can remove unneeded items | Deleted task disappears immediately |
| US4 | As a user, I want to filter tasks to focus on what matters | Selected filter updates the list accordingly |
| US5 | As a user, I want to edit tasks in case I made a mistake | Edits save without full reload; form is pre-filled |

---

## 7. Assumptions

- The project will be developed in React.
- Testing will be automated (unit and integration) where applicable.
- Manual testing will be executed for UI, usability, and edge case scenarios.

---

## 8. Constraints

- LocalStorage may limit persistent data storage on some browsers.
- No backend authentication is planned for MVP.
- Real-time collaboration features are excluded.

---

## 9. Success Metrics

- 100% pass rate on regression suite before production
- < 2% bug reopen rate post-launch
- App has < 1 second interaction latency on typical hardware
- Accessibility score ≥ 90 (Lighthouse)

---

## 10. QA Artifacts to Be Produced

| Artifact | Description |
| --- | --- |
| Test Plan | High-level QA strategy covering scope, tools, and schedule |
| Test Cases | Detailed scenarios including inputs, steps, expected results |
| RTM (Requirement Traceability Matrix) | Links requirements to test cases |
| Bug Reports | Detailed issues with steps to reproduce, severity, and attachments |
| Test Summary Report | Outcome of test execution with metrics and analysis |

---

## 11. Risks & Mitigations

| Risk | Impact | Mitigation |
| --- | --- | --- |
| Task data loss due to localStorage clearing | High | Suggest backup/export feature |
| Incomplete cross-browser compatibility | Medium | Add browser compatibility testing |
| UI inconsistency on mobile | Medium | Add responsive design testing |

---

## 12. QA Tools and Frameworks

| Area | Tools |
| --- | --- |
| Test Case Management | Notion |
| Bug Tracking | GitHub Issues |
| Automation | Jest, React Testing Library, Playwrite |
| Performance | Lighthouse |
| Accessibility | Lighthouse |
| Manual Testing | Real devices |

---

## 13. Approval

| Role | Name | Date | Signature |
| --- | --- | --- | --- |
| QA Analyst | – | – | ✅ |
| Developer | – | – | ✅ |

---
