# SheetFill — Fill Web Forms from Excel & CSV

**Turn spreadsheet data into web-form entries with a simple, structured workflow.**

SheetFill is a Chrome extension designed to connect your **Excel/CSV spreadsheet data with web forms**. Instead of repeatedly switching between a spreadsheet and browser, copying values, and pasting them into individual fields, SheetFill helps you map web-form fields, create a matching spreadsheet template, load your data, select a row, and fill the mapped fields.

## 🚀 How SheetFill Works

SheetFill follows a simple workflow:

**Map Fields → Get Template → Add Data → Load Data → Select Row → Fill Current Row**

### 1. Smart Auto Selection

Open the webpage containing your form and use **Smart Auto Selection** to identify and select the available form fields.

Instead of manually selecting every field one by one, SheetFill can automatically map supported fields on the current webpage.

You can also manually adjust the selection when needed.

### 2. Download Form Template

Once your fields are mapped, download a spreadsheet template based on the selected form fields.

The generated template provides the structure you need to follow when preparing your data.

For example, a student enrollment form may contain fields such as:

* Student Name
* Father's Name
* Mother's Name
* Date of Birth
* Address
* Mobile Number
* Email
* Other supported form fields

Add your records to the downloaded template and save the spreadsheet.

### 3. Load Your Spreadsheet Data

Upload your prepared spreadsheet using the **Load Data** option.

SheetFill supports:

* XLS
* XLSX
* CSV

After loading the file, you can preview and work with your spreadsheet data.

### 4. Select Your Data

SheetFill lets you work with the required row and column from your loaded spreadsheet.

Select the record you want to use and review the corresponding data before filling the webpage.

This gives you control over which spreadsheet record is used.

### 5. Fill Current Row

Once your web fields are mapped and your spreadsheet data is loaded, use **Fill Current Row**.

SheetFill takes the values from the selected spreadsheet row and fills them into their corresponding mapped web-form fields.

For example:

**Spreadsheet Row → Student Name → Father's Name → Mother's Name → Address → Mobile Number**

becomes:

**Selected Row → Corresponding Web Form Fields**

This helps reduce repetitive copy-and-paste work.

## 📊 Supported Spreadsheet Workflow

SheetFill is designed for workflows where information already exists in a spreadsheet and needs to be entered into a web form.

A typical workflow looks like:

**Excel/CSV Data**

↓

**SheetFill**

↓

**Mapped Web Form**

↓

**Select Record**

↓

**Fill Current Row**

This can be useful for repetitive data-entry tasks involving structured spreadsheet information.

## 🎯 Key Features

### Smart Auto Selection

Automatically identify supported form fields on the current webpage.

### Manual Field Selection

Adjust your mapped fields when automatic selection does not match your requirements.

### Form-Based Excel Template

Download a spreadsheet template based on the fields selected from your webpage.

### XLS / XLSX / CSV Support

Work with commonly used spreadsheet formats.

### Spreadsheet Preview

Review loaded spreadsheet information before using it with the form.

### Row & Column Selection

Select the required spreadsheet data and work with a specific record.

### Fill Current Row

Fill mapped webpage fields using the currently selected spreadsheet row.

### Clear Selection

Remove the current webpage field selection when you want to start again.

### Reset Settings

Reset SheetFill configuration and selections when needed.

## 💡 Example Use Case: Student Enrollment

Imagine you have student information stored in Excel.

Your spreadsheet contains:

| Student     | Father's Name | Mother's Name | Mobile |
| ----------- | ------------- | ------------- | ------ |
| Rahul Kumar | Raj Kumar     | Sunita Kumar  | ...    |
| Priya Patel | Amit Patel    | Neha Patel    | ...    |

The website contains a student enrollment form.

Instead of manually copying each value from Excel and pasting it into the browser:

1. Open the enrollment webpage.
2. Open SheetFill.
3. Use **Smart Auto Selection**.
4. Review and adjust the selected fields.
5. Download the **Form Template**.
6. Add your spreadsheet data according to the template.
7. Load the spreadsheet into SheetFill.
8. Select the required row.
9. Click **Fill Current Row**.
10. Complete any unsupported fields manually.
11. Submit the web form.

## 🧩 Designed for Structured Data Entry

SheetFill can be useful for people who regularly work between spreadsheets and browser-based forms, including workflows involving:

* Student enrollment
* Registration forms
* Administrative data entry
* Structured records
* Repetitive browser-based form filling
* Excel-to-web data entry
* CSV-to-web data entry
* Office and educational workflows
* Internal data-entry processes

Your actual workflow may vary depending on the website and form structure.

## ⚠️ Current Limitations

SheetFill is designed around supported standard web-form elements.

Some website components may not work as expected because websites can use custom controls, dynamically generated elements, shadow DOM, cross-origin frames, or other browser/security restrictions.

### File Uploads

At present, SheetFill does **not automatically handle photograph, signature, or other file-selection fields**.

For example, if a form contains:

**Student Name → Automatically filled**

**Father's Name → Automatically filled**

**Mother's Name → Automatically filled**

**Photograph → Manual upload**

the supported text/form fields can be filled through SheetFill, while the file field must be completed manually.

### Custom Web Components

Compatibility may vary with:

* Custom dropdowns
* Complex JavaScript components
* Dynamically generated forms
* Shadow DOM
* Cross-origin iframes
* Website-specific controls
* Browser security restrictions

SheetFill does not guarantee compatibility with every website or every type of form control.

## 🔐 Privacy & Data Handling

SheetFill is designed around a user-controlled browser workflow.

Your spreadsheet data is used to perform the actions you request in the browser. The core workflow does not require creating a SheetFill cloud account.

SheetFill does not need your spreadsheet data to be publicly shared in order to use the extension.

Always review the website you are using and make sure you are authorized to enter and process the information.

## 🔑 Permissions Explained

SheetFill requests browser permissions required for its functionality.

### activeTab

Allows SheetFill to interact with the currently active webpage when you use the extension.

### scripting

Used to identify supported webpage form elements and perform the requested field-filling actions.

### storage

Used to save extension settings and configuration.

### unlimitedStorage

Used when additional browser storage capacity is required for the extension's local configuration or workflow data.

### Website Access

SheetFill needs access to webpages where you choose to use its form-mapping and filling functionality.

Permissions are requested to support the extension's core functionality.

## 🛡️ Use Responsibly

SheetFill is intended for legitimate, authorized data-entry workflows.

Do not use the extension to bypass:

* CAPTCHA systems
* Authentication mechanisms
* Access restrictions
* Security controls
* Website usage restrictions
* Anti-automation protections

Always follow the terms, policies, and rules of the website where you use SheetFill.

## ⚡ Why SheetFill?

The idea is simple:

**Your spreadsheet already has the data.**

**Your website already has the form.**

**SheetFill connects them.**

Instead of:

**Copy → Switch → Paste → Repeat**

use:

**Map → Template → Load → Select → Fill**

SheetFill helps turn repetitive spreadsheet-to-web-form entry into a more structured workflow.

## 🚀 SheetFill

**Spreadsheet → Web Form**

**Smart Auto Selection**
**Download Form Template**
**Load XLS / XLSX / CSV**
**Select Row & Column**
**Fill Current Row**
**Clear Selection**
**Reset Settings**

Install SheetFill and simplify repetitive spreadsheet-to-web-form data entry.

---

**Keywords:** Excel form filler, Excel autofill, CSV form filler, web form filler, Excel to web form, spreadsheet form filler, web form automation, Excel data entry, CSV data entry, form autofill, browser form filler, spreadsheet automation, Excel web form, data entry extension
