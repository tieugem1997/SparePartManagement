# SparePartManagement

## Introduction
SparePartManagement is a PowerApps application designed to efficiently manage spare parts inventory. The application consists of four main screens: Main Screen, Stock Screen, Historical Screen, and FormScreen. It integrates with SharePoint List for data storage and provides functionalities for parts withdrawal, refill, and inventory history tracking.

## Main Screens

### 1. Main Screen
- **Dashboard**: Displays an overview of the stock for all tools.
- **Buttons**:
  - **Part WithDraw**: Function for withdrawing parts.
  - **Refill**: Function for refilling parts.
  - **Historical Record**: View transaction history.
  - **Stock Status**: View stock status.

### 2. Stock Screen
- **ComboBoxSearchBox**: Search tools and sort by stock status.
- **Details**: View quantity for each Part Number and Full Stock.

### 3. Historical Screen
- **Update Button**: Update transaction history.
- **Holdover**: Shows the last record date.
- **Buttons**:
  - **Withdraw**: Withdraw parts.
  - **Refill**: Refill parts.
- **Filters**: Filter by date, shift, PartNumber, Check, Sort direction by date, part name.

### 4. FormScreen
- **Refill and Withdraw Entry**: Function for entering refill and withdraw details.
- **Submit**: Automatically updates the quantity for the Part Number.
- **Update Historical**: Allows updating history based on previous and current quantities without affecting current stock. This is a unique feature of the system.

## Database
Data is stored in SharePoint List. You can import the app from the PowerApps source with two files:
- **WidgetOnly**: For customizing the app.
- **Final App**: The final version of the app.

## Import Instructions
- **SharePoint List**: Import from the Import folder.
- **Images**: Images used in the app are stored in the Image folder.

## Video Demo
[Link Video Demo](#)

## Usage Instructions
1. **Import SharePoint List**:
   - Open SharePoint and navigate to the Import folder.
   - Follow the import steps as guided.

2. **Import PowerApps**:
   - Download the WidgetOnly or Final App file.
   - Open PowerApps and import the application.

We hope you find the SparePartManagement app useful and customizable to your needs!
