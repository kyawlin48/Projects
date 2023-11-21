## Invoice Creator Tool using Excel VBA & Macros

## Purpose

The Invoice Generator Tool is designed to streamline the invoice generation process and provide a centralized overview of the status of all invoices. This tool aims to make invoice creation an efficient administrative task, reducing the time spent on each invoice from 20-30 minutes to just a few clicks, taking approximately 2-3 minutes. By consolidating invoice information in one place, users can easily track completed jobs, monitor open invoices, and assess overall revenue.

## Getting Started

### Steps

1. **Update Master Data**
   - Input the original customer master data in the master data tab.
   - Add new customers from the Dashboard tab by clicking on the "Add Customer" button.
   - Edit customer information by clicking on the "Edit Master Data" button.

2. **Update the Template**
   - Customize the template by adding your own logo.
   - Double-check the VBA code if you wish to modify other parts of the template.

3. **Update Folder Paths**
   - Create two folders to store PDF and Excel versions for each invoice.
   - Ensure the folders are in the same directory where the tool is saved.
   - VBA uses `thisworkbook.path` to find the directory and looks for specified folders on the dashboard page inside this directory.

4. **Adding Invoice Information**
   - Input project information on the invoice tab.
   - Start typing the customer's name in column B, then select the correct customer from the list.
   - Complete the remaining information.
   - After completing a job, click on the "Create Invoice" button.
   - Select the invoice with a blank status and click "Create Invoice."
   - To create an email with the customer's email address and a PDF attachment, click on "Create Email" (Note: This creates a draft email for further customization).

5. **Calculations for Dashboard**
   - The "Calculations" tab contains the data preparation table for the chart on the "Dashboard" tab.
   - The technique used here is included in the online Excel Dashboards course.

**Note**: Change the data in cell C1 of the Dashboard tab to `=TODAY()` to make it dynamic.

Feel free to explore and optimize your invoice generation process with this tool. If you have any questions or suggestions, please reach out. Happy invoicing! 🚀
