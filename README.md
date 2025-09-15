# 2024/2025 School Timetable

This project recreates the 2024/2025 academic year timetable for Years 7-11 using HTML tables and CSS, as specified in the assignment. The timetable is a fixed, centered layout with merged cells for breaks, lunch, and activities, styled for readability and accessibility.

## Accessibility Considerations
- Semantic HTML structure with `<table>`, `<thead>`, `<tbody>`, and `<th>` elements.
- `<th>` tags use `scope="col"` for time slots and `scope="row"` for days/years to ensure screen-reader compatibility.
- A `<caption>` element labels the table as "2024/2025 School Timetable."
- Alt text for the preview image: "Screenshot of a weekly school timetable for Years 7-11, showing days (Monday to Friday), time slots (8:00-4:00), subjects with teacher names, and merged cells for breaks, lunch, and activities."

## Files
- `index.html`: Main HTML file with the timetable structure.
- `style.css`: External stylesheet for layout and styling.
- `timetable_preview.png`: Screenshot of the rendered timetable.
- `README.md`: This file with project details and accessibility notes.
