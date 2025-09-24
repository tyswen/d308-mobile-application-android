# Vacation Planner Android App

## Title and Purpose
The Vacation Planner application allows users to plan vacations and manage associated excursions. Users can input vacation details (title, hotel, start/end dates), schedule and share their plans, and attach excursions to each vacation. Built using Android Studio.

---

## How to Operate the Application

### Clone the project (link below)
- Open in Android Studio
- Run the app in the Android emulator or using your personal device

### Home Screen
- Launches with navigation options to view all vacations.

### Vacation List
- Displays all saved vacations.
- Tap a vacation to view/edit details.
- Use the add button (if implemented) to add a new vacation.

### Vacation Detail View
- Add or edit a vacation.
- Fields include title, hotel, start date, and end date.
- Save button validates that all fields are filled and dates are correctly formatted.
- A vacation cannot be deleted if excursions are assigned.
- Vacation alerts are set for both the start and end dates.

### Excursion List View
- View all excursions associated with a selected vacation.
- Tap an excursion to view or edit.
- Use the add button to add a new excursion.

### Excursion Detail View
- Add or edit excursion details.
- Excursion must have a valid date within the vacation's start and end dates.
- Alarm is set for the excursion date.
- Date format is validated (`yyyy-MM-dd`).
- Excursion info can be shared via external apps.


---

## Target Android Version
The signed APK was built and tested for Android 8.0 (API level 26) and above.

---

## Git Repository Link
https://gitlab.com/wgu-gitlab-environment/student-repos/tswenck/d308-mobile-application-development-android

