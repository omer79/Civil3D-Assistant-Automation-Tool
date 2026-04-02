# Civil3D Assistant Automation Tool (Python + Dynamo)

## Description
Civil3D Assistant is a Dynamo-based automation tool that runs inside Autodesk Civil 3D to automate engineering calculations and report generation for road design and surface data.

The tool automatically detects elements in the drawing, allows the user to select the required objects, and generates multiple engineering reports in a structured Excel file in a single run.

This tool replaces hours of manual work and report extraction with a fully automated workflow that completes in minutes.

---

## Features
- Runs directly inside Civil3D using Dynamo
- Simple and user-friendly interface
- Automatically detects available drawing elements
- Allows selecting elements to generate reports for
- Generates multiple reports at once
- Exports all reports into a structured Excel file
- Handles drawing errors and avoids common issues automatically

---

## Generated Reports
The tool generates the following engineering reports:

1. **Design Slopes Report**
   - More accurate and easier to obtain than built-in Civil3D reports

2. **Offset Distance from Road Centerline**
   - Calculates distance of each element from road center without generating multiple reports manually

3. **Road Points Report**
   - Extracts and organizes all road points without exporting multiple reports and merging them manually

4. **Centerline Coordinates Report**
   - Extracts centerline coordinates for both:
     - Design surface
     - Existing surface

5. **Non-Design Slopes Report**
   - Extracts slopes from actual surface edges
   - This report does not exist in Civil3D and is usually calculated manually

All reports are generated **at once** after selecting the required elements.

---

## Output
- Organized Excel file
- All reports in one file
- Includes all required engineering data
- Saves hours of manual work
- Report generation time: about 1 minute instead of several hours

---

## Tech Stack
- Python
- Dynamo
- Autodesk Civil 3D
- Excel Automation
- Engineering Calculations
- Data Processing

---

## Workflow
1. Open Civil3D drawing.
2. Run Dynamo script.
3. Tool automatically detects drawing elements.
4. Select elements to analyze.
5. Select required reports.
6. Tool generates all reports automatically.
7. Reports are exported to a structured Excel file.

---

## Benefits
- Automates repetitive Civil3D reporting workflows
- Reduces manual calculations
- Reduces human error
- Saves several hours of work
- Generates organized engineering reports automatically
- Improves engineering workflow productivity

---

## Use Cases
- Road design projects
- Surface analysis
- Engineering report generation
- Quantity and slope analysis
- Civil engineering automation workflows