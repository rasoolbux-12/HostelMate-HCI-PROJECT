# HostelMate

## University Hostel Updates & Complaints Management System

HostelMate is a Human-Computer Interaction (HCI) course project for university students living in hostels. It brings hostel announcements and personal complaint management into one student-facing interface.

The screens were designed in Figma and converted into interactive HTML prototypes so users can experience the navigation, forms, feedback, and task flows in a browser. Two versions demonstrate how different interface decisions affect usability: **Good HCI** and **Bad HCI**.

## Live Demos

* Good HCI Prototype
* Bad HCI Prototype

## The Problem

Hostel announcements shared through separate notices or informal channels can be difficult to find. Students may also struggle to report an issue or understand what happened after submitting a complaint.

HostelMate explores a clearer experience for reading updates, reporting issues, and checking complaint progress. The student dashboard and complaint list focus on the current student’s own records.

## Student Features

* Login and signup interactions with input validation.
* A dashboard with announcements and personal complaint information.
* Search and category filters for hostel updates.
* Detailed announcements with timing and action information.
* A personal complaint list with status filters.
* Complaint submission with category, location, description, and priority.
* Submission confirmation with a reference number and summary.
* Complaint tracking through visible progress stages.
* Profile review and account-related interactions.

## Screens

Both versions cover the same ten core screens:

| # | Screen | Purpose |
| :--- | :--- | :--- |
| **1** | Login | Access the student interface |
| **2** | Signup | Demonstrate account registration |
| **3** | Student Dashboard | Review updates and personal complaint progress |
| **4** | Hostel Updates | Browse, search, and filter announcements |
| **5** | Update Details | Read the complete announcement |
| **6** | My Complaints | Review the student’s submitted complaints |
| **7** | Submit Complaint | Describe and submit a hostel issue |
| **8** | Complaint Confirmation | Verify submission and identify the complaint |
| **9** | Complaint Status | Follow the complaint’s progress |
| **10** | Profile | Review personal and hostel information |

## Good HCI vs. Bad HCI

The Good HCI version uses a forest-green and cream theme, consistent components, labeled navigation, structured content, and meaningful feedback. The Bad HCI version intentionally introduces weaknesses for comparison and learning.

| Aspect | Good HCI | Bad HCI |
| :--- | :--- | :--- |
| **Labels** | Familiar, task-specific wording | Ambiguous labels such as “Secret Key” and “Go” |
| **Navigation** | Named destinations and selected states | Unlabeled icons that require interpretation |
| **Action hierarchy** | Clear primary and secondary actions | Competing or misplaced emphasis |
| **Update details** | Separate, readable information groups | Compressed and faint content |
| **Complaint information** | Consistent totals and progress messages | Unexplained totals and contradictory statuses |
| **Confirmation** | Reference, summary, and next steps | Generic success feedback with limited detail |
| **Validation** | Specific guidance beside affected fields | Generic errors that leave corrections unclear |
| **Profile** | Visible editing and aligned information | Faint actions and weaker alignment |

## HCI Principles Applied

* **Visibility of system status:** Current states, filters, and complaint progress are visible.
* **Consistency and standards:** Components and navigation follow repeated patterns.
* **Recognition rather than recall:** Labels and references reduce guessing and memory demands.
* **Error prevention and recovery:** Instructions and field-specific validation guide input.
* **User control and freedom:** Back routes and confirmation choices support recovery from unintended actions.
* **Feedback:** Submission results explain what happened and what to do next.
* **Accessibility considerations:** Text accompanies icons, status colors, and validation cues.

> **Note:** The report presents a qualitative interface analysis. Usability effects are reasoned expectations; participant testing and a formal accessibility audit have not been conducted.

## Design and Implementation

* **Figma:** Screen layouts, components, typography, spacing, colors, and design states.
* **HTML, CSS, and JavaScript:** Browser-based interactive demonstrations of the designs.

This is a demonstration prototype with sample data and simulated account access. It does not provide production authentication, a backend, or a database. Complaint submissions and status views demonstrate interface behavior rather than a live hostel service.

## Try the Project

Open either live demo above to explore the student experience. Try browsing updates, submitting an incomplete form, and reviewing complaint feedback to compare the two versions.

For local use, download the repository and open the relevant prototype’s HTML entry file in a browser. Keep its accompanying styles, scripts, and assets in their original locations.

## Project Report

The accompanying HostelMate HCI Project Report documents the screens, HTML screenshots, design decisions, validation states, HCI principles, and 13 comparison aspects.

## Metadata & Contributors

### Contributors
* **Rasool Bux** — 24SW134
* **Misbah** — 24SW022

### Academic Context
* **Course:** Human-Computer Interaction (HCI)
* **Department:** Department of Software Engineering
* **University:** Mehran University of Engineering & Technology, Jamshoro
* **Semester / Year:** 5th Semester / 3rd Year
* **Instructor:** Ma’am Amrita Dewani

### References
* Course-provided HCI project submission guidelines.
* Nielsen’s 10 Usability Heuristics
* Web Content Accessibility Guidelines (WCAG) 2.2
