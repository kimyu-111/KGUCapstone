<img src="https://github.com/user-attachments/assets/f6124040-bb97-4a0a-b6af-45725521e352" width="300"/>

# 💊 Dosing (복용이)
> **AI-Powered Medication Assistant & Reminder App for the Elderly**

<br>

## 📖 Project Overview
**Dosing** is an Android application designed to ensure safe medication practices for the elderly, addressing the challenges of an aging society approaching 2025.

Elderly individuals often face "polypharmacy" (taking multiple medications), which significantly increases the risk of confusion and duplicate dosing. **Dosing** leverages **Large Language Model (LLM) systems, Optical Character Recognition (OCR), and Voice Recognition technology** to help seniors easily access accurate drug information and manage their medication schedules independently.

### 🎯 Development Goals
* **Senior-Friendly UX:** Provides information via voice and intuitive UI instead of complex text.
* **AI-Driven Analysis:** Identifies medication and analyzes drug interactions with a single photo.
* **Safe Medication Management:** Prevents misuse/abuse and provides regular medication reminders.

<br>

## 💡 Key Features

### 1. 📸 Medication Recognition & Info Extraction
* Recognizes the user's medication when scanning pills with a smartphone camera.
* Extracts complex pharmaceutical information and converts it into an easy-to-understand format for the elderly.

### 2. ⚠️ Drug Interaction Warning
* Analyzes the interaction between newly prescribed drugs and existing medications.
* Displays warning messages for contraindications (drugs that shouldn't be taken together) or potential side effects.

### 3. 🎙️ Voice-Based Information Search
* Supports voice recognition for users who find typing difficult.
* AI answers spoken questions such as "When should I take this?" or "Are there any side effects?"

### 4. ⏰ Smart Medication Reminders
* Automatically registers medication schedules based on analyzed drug information.
* Provides **Push Notifications** at set times (Breakfast, Lunch, Dinner, Before Bed, etc.).

### 5. 📖 Easy Medication Guide
* Uses LLM to paraphrase difficult medical terminology into simple language.
* Features a senior-friendly UI with large text and intuitive icons.

<br>

## 🆚 Competitive Analysis

| Feature | App A (Existing) | App B (Existing) | **Dosing** |
| :--- | :---: | :---: | :---: |
| **Medication Reminder** | ✅ | ❌ | **✅** |
| **Camera Recognition** | ✅ | ✅ | **✅** |
| **Voice Search & Guide** | ❌ | ❌ | **✅** |
| **Simplified Info (LLM)** | ❌ | ✅ | **✅** |
| **AI Pattern/Symptom Analysis** | ❌ | ❌ | **✅** |
| **Drug Interaction Warning** | ❌ | ❌ | **✅** |
| **Senior-Friendly UI** | ❌ | ❌ | **✅** |

<br>

## 🛠️ Tech Stack

| Category | Technology | Description |
| :--- | :--- | :--- |
| **Mobile** | ![Android](https://img.shields.io/badge/Android-3DDC84?style=flat&logo=android&logoColor=white) | Android Native App Development |
| **AI / ML** | ![OpenAI](https://img.shields.io/badge/Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white) | Voice Recognition (STT) & Text Conversion |
| **AI / Vision** | ![OCR](https://img.shields.io/badge/OCR_&_Vision-FF9900?style=flat) | Text Extraction & Image Analysis from pill photos |
| **Database** | ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=white) | Storage for medication records, symptoms, and drug info |
| **Design** | ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=figma&logoColor=white) | Senior-customized UI/UX Design |

<br>

## 📱 System Flow
1. **User Input:** Camera capture (pill photo) or Voice question.
2. **AI Analysis:** Text extraction via OCR, Image analysis, and Speech-to-Text conversion.
3. **Processing:** Drug information matching, Interaction analysis, and simplification via LLM.
4. **Output:** Medication guide display, Auto-registration of reminders, Warning pop-ups.
5. **DB Storage:** Update medication records and user data in Firebase.

<br>

## 👥 Team Info (Team Solstice)
**Kyonggi University, Dept. of AI Computer Science**

* **Advisor:** Gwansang Na
* **Members:** Yu Kim, Junho Kim, Mincheol Shin, Junyoung Park, Jiyoung Eom, Jeongeun Park
* **Planning:** Yu Kim, Junyoung Park
* **Development:** Mincheol Shin
* **Design:** Junho Kim, Junyoung Park, Jiyoung Eom, Jeongeun Park
* **Paper Writing:** Yu Kim, Junyoung Park, Mincheol Shin

---
*This project was planned to solve social issues through technology in preparation for the elderly population reaching 20% in 2025.*
