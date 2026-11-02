# Lab8_repo_design_SMT

Product Management System built with **ASP.NET Core Razor Pages** implementing the **Repository Design Pattern** and ADO.NET (`Microsoft.Data.SqlClient`) connecting to SQL Server LocalDB (`BMS_DB`).

## Features
- **Repository Pattern**: Clean separation of data access logic in `ProductRepository`.
- **Image Handling**: File validation and storage via `ProductImageService`.
- **Full CRUD Operations**:
  - Add new products with title, description, image, price, quantity, and status.
  - View all products in a responsive tabular view.
  - View full product details.
  - Edit existing products with optional image replacement.
  - Delete products with automatic cleanup of associated uploaded image files.
- **Robust Validation**: Server-side and client-side validation for required fields, numeric constraints, and file types/sizes.
- **Resilient Error Handling**: Graceful error handling preventing unhandled application crashes.

## Technologies Used
- ASP.NET Core
- Razor Pages
- ADO.NET (`Microsoft.Data.SqlClient`)
- Microsoft SQL Server LocalDB
- Bootstrap 5
