# OCTA Task Page: Full User Guide

## Introduction
This document serves as a comprehensive user guide for the Task page within the OCTA platform. The Task page is designed to help users efficiently manage and automate their accounts receivable processes by providing tools for creating, tracking, and organizing tasks and rules related to financial operations. This guide will walk you through every feature and section, offering step-by-step instructions, tips for efficiency, and troubleshooting advice.

## 1. Navigation Overview
The OCTA Task page is accessible after logging into the OCTA platform. The top bar provides general navigation and account information, while the main content area focuses on task and rule management.

### 1.1 Header Elements
* **Language Selector (EN):** Located at the top right, this allows users to switch the interface language. Currently set to English.
* **Company Name Display :** Shows the name of the currently logged-in company or account.
* **Demo Data Toggle Switch:** A switch to enable or disable demo data, useful for testing features without affecting live data.
* **Notification Bell Icon:** Displays alerts and notifications relevant to the user's account or tasks.

## 2. Task Management Interface
The core of the Task page is divided into two primary tabs: Task and Rule. These tabs allow users to switch between managing individual tasks and defining automated rules.

### 2.1 Task Tab
This tab provides an overview and management interface for all individual tasks. When you first navigate to the Task page, this tab is active by default.

**Screenshot: Task Tab Overview**
![Task Tab Overview](Image_Page_2.png)
Description: The main view of the Task tab, showing the search bar, filter button, and the task list table.

### 2.2 Rule Tab
This tab is dedicated to setting up and managing automated rules that can trigger tasks or other actions within the OCTA platform. Rules help automate repetitive processes and ensure consistency.

**Screenshot: Rule Tab Overview**
![Rule Tab Overview](Image_Page_3.png)
Description: The main view of the Rule tab, showing the search bar, filter button, and the rule list table.

## 3. Search and Filter Functionality
Both the Task and Rule tabs offer robust search and filter capabilities to help users quickly find specific tasks or rules.

### 3.1 Search Bar
**Purpose:** The search bar allows users to quickly find tasks or rules by typing in keywords. It performs a real-time search across relevant fields such as task name or rule name.

**How to Use:**
1. Navigate to either the Task or Rule tab.
2. Locate the input field labeled "Search".
3. Type your desired keywords into the search bar.
4. The list of tasks or rules will automatically update to show only those matching your search query.

**Screenshot: Search Bar**
![Search Bar](Image_Page_4.png)
Description: The search bar located above the task/rule list, used for quick filtering.

### 3.2 Filter Button
**Purpose:** The filter button provides advanced filtering options, allowing users to narrow down their task or rule list based on multiple criteria such as creation date, assigned user, or status.

**How to Use:**
1. Click the "Filter" button next to the search bar.
2. A modal dialog will appear, presenting various filtering options (e.g., Rule, Created by, Assigned to, Status, Created on, Deadline).
3. Select the desired criteria and values for your filter.
4. Click "Apply" to apply the filters and update the task/rule list.
5. To clear all applied filters, click the "Clear all" button within the filter modal.

**Screenshot: Filter Modal**
![Filter Modal](Image_Page_5.png)
Description: The filter modal showing various options for refining the task or rule list.

**Tips for Efficiency:**
* Use the search bar for quick, general searches.
* Combine filters for highly specific queries to quickly locate particular tasks or rules.

## 4. Task Creation
Creating new tasks is a fundamental feature of the OCTA Task page, allowing users to define and assign specific actions related to their accounts receivable.

### 4.1 Creating a New Task
**Purpose:** This feature enables users to manually create individual tasks, specifying details such as the task name, description, assignee, and deadline.

**How to Use:**
1. On the Task tab, click the "New task" button, located on the right side above the task list.
2. A modal dialog titled "Add task" will appear.
3. Fill in the required fields:
    * **Task name:** Enter a concise and descriptive name for the task.
    * **Task details:** Provide a more detailed description of the task, including any necessary instructions or context.
    * **Assigned to:** Select an existing customer or user from the dropdown list who will be responsible for completing the task.
    * **Deadline:** Choose a due date for the task using the date picker.
    * **Type:** Select the type of task from the dropdown list.
4. After filling in all the details, click the "Add task" button to create and save the new task.
5. To cancel the task creation process, click the "Cancel" button.

**Screenshot: Add Task Modal**
![Add Task Modal](Image_Page_6.png)
Description: The modal dialog for adding a new task, showing all input fields and options.

**Key Functionalities:**
* **Required Fields:** Ensure all fields marked with an asterisk (*) are completed before attempting to save the task.
* **Dropdown Selections:** The 'Assigned to' and 'Type' fields utilize dropdown menus for easy selection of predefined options.
* **Date Picker:** The 'Deadline' field offers a user-friendly date picker to ensure accurate date entry.

**Tips for Efficiency:**
* Use clear and specific task names to make tasks easily identifiable at a glance.
* Break down complex tasks into smaller, manageable sub-tasks if the 'Task details' field becomes too long.

## 5. Task List View
The Task List View displays all created tasks in a structured table format, allowing for easy overview and management.

### 5.1 Understanding the Task Table
**Purpose:** The task table provides a clear, organized display of all tasks, with sortable columns to help users quickly find and prioritize information.

**Table Columns:**
* **Task name:** The name given to the task.
* **Type:** The category or type of the task.
* **Created by:** The user who created the task.
* **Rule:** If the task was generated by an automated rule, the name of that rule will be displayed here.
* **Assigned to:** The customer or user assigned to complete the task.
* **Status:** The current status of the task (e.g., Pending, In Progress, Completed).
* **Created on:** The date the task was created.
* **Deadline:** The due date for the task.

**Screenshot: Task List Table**
![Task List Table](Image_Page_8.png)
Description: The table displaying all tasks with various columns for task details.

**Tips for Efficiency:**
* **Sorting:** Click on any column header (e.g., "Task name", "Deadline") to sort the table by that column in ascending or descending order. This is useful for prioritizing tasks or finding overdue items.
* **"No data" Message:** If the table shows "No data", it means there are no tasks currently created or matching your applied filters. Use the "New task" button to add tasks.

## 6. Rule Creation
Automated rules are a powerful feature in OCTA, allowing users to define conditions that trigger specific actions or tasks. This section details how to create and manage these rules.

### 6.1 Creating a New Rule
**Purpose:** This feature allows users to define custom rules and conditions to automate various aspects of their accounts receivable process. Rules can be set up to automatically create tasks, send notifications, or perform other predefined actions when certain criteria are met.

**How to Use:**
1. Navigate to the Rule tab on the Task page.
2. Click the "New rule" button, located on the right side above the rule list.
3. A modal dialog titled "Set rules" will appear.
4. Fill in the required fields:
    * **Rule name:** Enter a clear and descriptive name for your rule.
    * **Condition:** Select the condition that will trigger this rule from the dropdown list. This could be based on various factors such as invoice status, payment terms, or customer behavior.
5. After defining the rule name and condition, click the "Save" button to create and activate the new rule.
6. To cancel the rule creation process, click the "Cancel" button.

**Screenshot: Set Rules Modal**
![Set Rules Modal](Image_Page_9.png)
Description: The modal dialog for setting up a new rule, showing the rule name and condition fields.

**Key Functionalities:**
* **Custom Automation:** Rules enable powerful automation, reducing manual effort and ensuring consistent application of business logic.
* **Condition-Based Triggers:** The ability to select specific conditions ensures that rules are only activated when relevant criteria are met.

**Tips for Efficiency:**
* Design rules carefully to avoid unintended consequences. Test new rules with demo data before applying them to live operations.
* Use descriptive rule names that clearly indicate the rule's purpose and the conditions it addresses.

## 7. Troubleshooting Common Issues
This section addresses common issues users might encounter while using the OCTA Task page and provides solutions.

### 7.1 "No data" in Task or Rule List
**Issue:** The task or rule table displays "No data" even when you expect to see tasks or rules.

**Possible Causes & Solutions:**
* **No Tasks/Rules Created Yet:** If you are a new user or have not yet created any tasks or rules, the table will naturally be empty. Use the "New task" or "New rule" buttons to add your first entries.
* **Filters Applied:** You might have active filters that are hiding all entries. Check the filter modal (by clicking the "Filter" button) and click "Clear all" to remove any active filters. This will display all available tasks or rules.
* **Search Query:** A search term might be entered in the search bar that doesn't match any existing tasks or rules. Clear the search bar to see all entries.

### 7.2 Unable to Save a New Task or Rule
**Issue:** When attempting to save a new task or rule, the system does not allow it, or an error message appears.

**Possible Causes & Solutions:**
* **Missing Required Fields:** Ensure all fields marked with an asterisk (*) are filled out. These are mandatory fields (e.g., Task name, Rule name, Condition).
* **Invalid Input Format:** Check if the input for fields like "Deadline" (for tasks) is in the correct format (dd/mm/yyyy). The system might reject incorrect date formats.
* **Network Connectivity:** A temporary internet connection issue might prevent the data from being saved. Check your internet connection and try again.

### 7.3 Interface Not Responding
**Issue:** The buttons or input fields on the page are unresponsive.

**Possible Causes & Solutions:**
* **Browser Cache:** Sometimes, old cached data can interfere with page functionality. Try clearing your browser's cache and cookies, then refresh the page.
* **Browser Compatibility:** Ensure you are using a supported and up-to-date web browser (e.g., Chrome, Firefox, Edge). Outdated browsers might have compatibility issues.
* **Temporary Glitch:** Occasionally, web applications can experience minor glitches. Try refreshing the page (F5 or Ctrl+R) or logging out and logging back in.

