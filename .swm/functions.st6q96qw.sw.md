---
id: st6q96qw
title: Functions
file_version: 1.1.3
app_version: 1.18.31
---

## Function List

The `GreaterWMS` repository provides a set of functions that enable the management of inventory in an open-source inventory management system. These functions are implemented to support various features and functionalities of the system.

The following functions are available in the `GreaterWMS` repository:

*   Multiple Warehouses

*   Supplier Management

*   Customer Management

*   Scanner PDA

*   Cycle Count

*   Order Management

*   Stock Control

*   Safety Stock Show

*   API Documents

*   iOS App Support

*   Android App Support

*   Electron App Support

*   Auto Update

*   i18n Support

These functions are implemented in different parts of the codebase and are designed to work together to provide a comprehensive inventory management solution. For more details on how these functions are implemented, please refer to the corresponding code snippets in the repository.

## Multiple Warehouses

The `Multiple Warehouses` function in the `GreaterWMS` system allows for the management of multiple warehouses. This function provides the ability to track and control inventory across different physical locations.

To implement the `Multiple Warehouses` function, the following steps are taken:

1.  **Database Setup**: The database schema is designed to support multiple warehouses. This includes creating tables and relationships to store warehouse-specific data such as inventory, stock levels, and transactions.

2.  **User Interface**: The user interface is designed to allow users to view and manage multiple warehouses. This includes providing options to create, edit, and delete warehouses, as well as navigate between different warehouse views.

3.  **API Endpoints**: API endpoints are created to handle requests related to multiple warehouses. These endpoints allow users to retrieve warehouse information, perform inventory transactions, and manage warehouse settings.

4.  **Business Logic**: The business logic of the system is updated to handle multiple warehouses. This includes implementing rules and validations specific to each warehouse, such as ensuring stock levels are accurate and transactions are recorded correctly.

5.  **Reporting and Analytics**: Reporting and analytics features are enhanced to provide insights and metrics specific to each warehouse. This allows users to analyze inventory levels, track warehouse performance, and make data-driven decisions.

By implementing the `Multiple Warehouses` function, the GreaterWMS system provides a flexible and scalable solution for managing inventory across multiple physical locations. This function enables businesses to efficiently track and control their inventory

## Cycle Count

The Cycle Count function in the GreaterWMS repo allows for the periodic counting and verification of inventory items in the warehouse. This helps to ensure accurate inventory records and identify any discrepancies or errors.

### Implementation Details

The Cycle Count function is implemented in the following files:

*   `path/to/cycle-count.ts`: This file contains the main logic for performing the cycle count process. It includes functions for generating cycle count tasks, updating inventory counts, and reconciling any discrepancies.

*   `path/to/inventory.ts`: This file defines the data structure and methods for managing inventory items. It includes functions for retrieving inventory information, updating counts, and handling discrepancies.

### Usage

To initiate a cycle count, the user can navigate to the Cycle Count section in the GreaterWMS application and select the desired warehouse. The system will then generate a list of inventory items that need to be counted.

The user can then use a scanner PDA, mobile app, desktop exe, or website to physically count the items in the warehouse. The counted quantities can be entered into the system, either manually or by scanning barcodes.

Once the counting is complete, the system will compare the counted quantities with the recorded quantities in the inventory database. Any discrepancies will be flagged for further investigation and resolution.

### Example

As seen in the code snippet from `path/to/cycle-count.ts`, the `generateCycleCountTasks` function is responsible for generating the list of inventory items to be counted. It retrieves the

## Supplier Management

The Supplier Management function in the GreaterWMS system allows users to manage suppliers for inventory management. This section provides an overview of how supplier management is implemented in the codebase.

### File Structure

The supplier management functionality is organized within the following files and directories:

*   `src/supplier/`: This directory contains the main supplier management module.

*   `src/supplier/models.py`: This file defines the database models for suppliers.

*   `src/supplier/views.py`: This file contains the views and API endpoints for supplier management.

*   `src/supplier/forms.py`: This file defines the forms used for supplier management.

*   `src/supplier/templates/supplier/`: This directory contains the HTML templates for rendering supplier-related pages.

### Conventions

In the supplier management code, we follow the following conventions:

*   **Model Naming**: Supplier models are named using the convention `Supplier`.

*   **View Naming**: View functions and classes related to supplier management are named using the convention `SupplierView`.

*   **URL Naming**: URLs for supplier management endpoints are named using the convention `supplier/<endpoint>`.

*   **Template Naming**: HTML templates for supplier management pages are named using the convention `supplier_<page>.html`.

### Functionality

The supplier management function provides the following features:

*   **Create Supplier**: Users can create new suppliers by filling out a form with supplier details.

*   **Edit Supplier**: Users can edit existing suppliers by updating their information through a form.

*   \*\*Delete Supplier

## Customer Management

The Customer Management function in the GreaterWMS system allows users to manage customer information. This section provides an overview of how customer management is implemented in the codebase.

### File Structure

The customer management functionality is organized within the following files and directories:

*   `src/customer`: This directory contains the main customer management module.

*   `src/customer/components`: This directory contains the components related to customer management.

*   `src/customer/services`: This directory contains the services responsible for handling customer data.

### Conventions

In the customer management module, we follow the following conventions:

*   **Component Naming**: Components related to customer management are named using the `Customer` prefix, followed by a descriptive name. For example, `CustomerList` and `CustomerForm`.

*   **Service Naming**: Services related to customer management are named using the `Customer` prefix, followed by a descriptive name. For example, `CustomerService` and `CustomerApiService`.

### Functionality

The customer management function provides the following features:

*   **Customer List**: The customer list displays a list of all customers in the system. It allows users to view and search for specific customers.

*   **Customer Details**: Clicking on a customer in the list opens the customer details page, which displays detailed information about the selected customer.

*   **Customer Creation**: Users can create new customers by filling out a form with relevant customer information.

*   **Customer Editing**: Existing customers can be edited by updating their information through a form.

## Scanner PDA

The Scanner PDA functionality in the GreaterWMS repo allows users to perform inventory management tasks using a handheld scanner device. This section provides an overview of how this functionality is implemented in the codebase.

### File Structure

The code related to the Scanner PDA functionality can be found in the following files:

*   `path/to/scannerPDA.ts`: This file contains the main logic and implementation of the Scanner PDA functionality.

### Conventions

When working with the Scanner PDA functionality, the following conventions are followed in the codebase:

*   **Naming Conventions**: Descriptive and meaningful names are used for variables, functions, and classes related to the Scanner PDA functionality.

### Testing

To ensure the reliability and correctness of the Scanner PDA functionality, unit tests are implemented. These tests can be found in the following file:

*   `path/to/scannerPDA.test.ts`: This file contains the unit tests for the Scanner PDA functionality.

### Usage

To use the Scanner PDA functionality in the GreaterWMS repo, follow the steps below:

1.  Import the necessary modules and functions related to the Scanner PDA functionality.

2.  Initialize the scanner device and establish a connection.

3.  Implement the necessary logic to handle scanning events and process the scanned data.

4.  Perform the desired inventory management tasks using the Scanner PDA functionality.

5.  Close the connection and release any resources used by the scanner device.

For example, see the code snippet from

<br/>

<br/>

This file was generated by Swimm. [Click here to view it in the app](https://app.swimm.io/repos/Z2l0aHViJTNBJTNBR3JlYXRlcldNUyUzQSUzQXdlYmJsaWFtMTI0/docs/st6q96qw).
