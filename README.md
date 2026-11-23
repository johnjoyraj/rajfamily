# 🌳 FamilyRoots • Multi-Generational Family Heritage & Connect Portal

> **Discover Your Roots. Connect Your Generations.**  
> A multi-generational genealogy, family-tree creation, and family heritage network platform for extended and vast family groups.

---

## 📖 Project Overview

**FamilyRoots** is a complete family heritage platform designed to preserve lineage records, celebrate family milestones, and connect distributed family branches across generations. It accommodates vast family networks across various branches and regions without limiting scope to any single family group.

This project repository contains:
1. **Interactive Web Application (`index.html`)**: Fully functional client-side heritage portal connected to Firebase Cloud Firestore for real-time synchronization.
2. **Comprehensive Technical Blueprint (`FamilyRoots_Complete_Project_Blueprint.docx`)**: A 22-section enterprise-grade product specification covering system architecture, privacy rules, data modeling, ER diagrams, REST APIs, and rollout milestones.
3. **One-Click Launcher (`OPEN_FAMILYROOT_PORTAL.bat`)**: Quick desktop launcher.

---

## ✨ Live Web Application Features (`index.html`)

The interactive web portal features a modern, accessible responsive interface:

| Module / Feature | Capabilities |
| :--- | :--- |
| **🌳 Family Tree & Lineage** | Hierarchical ancestral tree, collapsible branches (`Show Branch` / `Hide Branch`), birth sequence ordering, and node cards |
| **✨ Front-and-Center Popup Modal** | Add & Edit form opens in a prominent, centered popup modal dialog with blurred backdrop instead of hidden at the bottom |
| **📘 Comprehensive User Manual** | Step-by-step interactive manual with bilingual guidance for non-technical and elderly family members |
| **📖 Members Directory & Live Search** | Real-time searchable member catalog with instant filtering by name, spouse, native place, current city, and occupation |
| **💬 Direct WhatsApp Integration** | 1-click private WhatsApp chat for both members and their spouses, plus direct link to join the Family WhatsApp Group |
| **🎂 Upcoming Birthdays & Anniversaries** | Automatic real-time detection of celebrations and milestones occurring this month |
| **📢 Live Community Board** | Real-time broadcast messages, blessings, and announcements stored in Firestore with optional WhatsApp sharing |

---

## ☁️ Cloud Backend Configuration

The application is pre-configured with Firebase Firestore for persistent cloud storage:
- **Firebase Project ID**: `raj-family-33299`
- **Firestore Collections**:
  - `familyTree`: Individual family profiles, parent IDs, birth dates, photos, and generation numbers.
  - `familyMessages`: Community board broadcast posts, sender emails, and timestamps.

---

## 🚀 Quick Launch

- **Double-click [`OPEN_FAMILYROOT_PORTAL.bat`](file:///e:/MYWORKSPACE/familyroot/OPEN_FAMILYROOT_PORTAL.bat)** to immediately launch `index.html` in your default web browser.
- **Direct Web Access**: Open `index.html` directly in any web browser.
