# Custom Dashboard Builder

A modern, responsive, and customizable dashboard builder application.

## Prerequisites

- **Node.js** (v18 or higher recommended)
- **npm** (comes with Node.js)

## Getting Started

Since the environment did not have Node.js installed, the dependencies have not been installed yet.

1. **Install Node.js**: Download and install from [nodejs.org](https://nodejs.org/).
2. **Open Terminal**: Navigate to this project directory: `d:\Shagi Project`.
3. **Install Dependencies**:
   ```bash
   npm install
   ```
4. **Run Development Server**:
   ```bash
   npm run dev
   ```
5. **Open Application**: The terminal will show a local URL (usually `http://localhost:5173`). Open it in your browser.

## Features

- **Dashboard Builder**: Drag and drop widgets (Charts, KPIs, Tables) to create your custom view.
- **Customer Orders**: Manage orders with a full CRUD interface (Create, Read, Update, Delete).
- **Date Filtering**: Filter dashboard data by date ranges.
- **Responsive Layout**: Works on Desktop, Tablet, and Mobile.
- **Types of Widgets**:
    - **KPI**: Display single aggregations (Sum/Avg/Count) of metrics.
    - **Charts**: Bar, Line, Area, Scatter, and Pie charts.
    - **Table**: View raw data in a tabular format.

## Technology Stack

- **Framework**: React + Vite + TypeScript
- **Styling**: Tailwind CSS
- **State Management**: Zustand
- **Visualization**: Recharts
- **Grid Layout**: React Grid Layout
- **Icons**: Lucide React
