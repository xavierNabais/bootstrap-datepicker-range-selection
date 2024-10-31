
# 📅 Bootstrap Datepicker Range Date

## Overview

This project implements a date range selection feature using a modal and the [Bootstrap Datepicker](https://bootstrap-datepicker.readthedocs.io/en/latest/). The goal is to allow users to select a date range, highlighting the selected range directly in the calendar.

## Description

The project allows users to choose a date range using two calendar views. Key features include:

- **📆 Date Range Selection**: Users can select a start date and an end date, with the selected range visually highlighted.
- **🔄 Calendar View Synchronization**: Both calendars are automatically updated to reflect the selected dates.
- **✨ Custom Range Highlighting**: Dates within the selected range are highlighted for better visibility.

## How to Implement

To implement the datepicker modal in your project, follow these steps:

1. **📦 Include Necessary Libraries**: Ensure you include Bootstrap, jQuery, and the Bootstrap Datepicker in your HTML file:

   ```html

   <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap-datepicker/1.9.0/css/bootstrap-datepicker.min.css">
   <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
   <script src="https://cdnjs.cloudflare.com/ajax/libs/bootstrap-datepicker/1.9.0/js/bootstrap-datepicker.min.js"></script>

2. **🖼️ HTML Structure**: Include the modal HTML structure in your body section:

    ```html

    <div class="modal-window" id="open-datepicker-modal">
        <div class="modal-content row col-5">
            <div class="col-12 d-flex">
                <div class="datapickerhidden col-6" id="modal-data-1"></div>
                <div class="datapickerhidden col-6" id="modal-data-2"></div>

            </div>
            <span class="data" style="margin-top: 10px; display: block;">Date?</span>
            <input type="hidden" name="data" class="datapicker hidden" value="">
        </div>
    </div>

3. **🛠️ JavaScript Functionality**: Add the provided JavaScript code to handle date selection, synchronization between calendars, and marking the selected date ranges.

4. **👥 Usage**: The calendar will open automatically when the page loads. Users can later add a button to display the modal if they wish.

**Conclusion**
This datepicker modal provides an easy way to select date ranges using the capabilities of the Bootstrap Datepicker creatively. Feel free to customize the functionalities according to your project's needs.
