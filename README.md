# Financial Freedom Calculator & Scenarios

A responsive, client-side web application designed to help users calculate their Financial Independence target and project multi-year wealth accumulation or distribution scenarios. Built with modern web standards and clean styling, this tool supports inflation-adjusted computations and alternative investment return simulations.

## Features

- **Financial Freedom Target Calculation**: Automatically computes your core financial independence number based on monthly living expenses, annual inflation, and a specified target fund period.
- **Optional Golden Age Adjustment**: Fine-tune calculations by accounting for your birth year and a targeted milestone age, applying dynamic inflation scaling across the pre-retirement timeline.
- **Dynamic Themes**: Fully equipped with a Dark/Light mode toggle switch utilizing a clean minimalist layout that respects system preferences and saves state locally.
- **Comprehensive Scenarios Tables**: Generates three sequential projection paradigms instantly:
  1. **Annual Golden Days (Table 1)**: A detailed 25-year multi-column compound projection detailing baseline living expenses, investment fund portions, final fund outputs, and dynamic year-on-year inflation metrics.
  2. **5-Year Golden Days Block (Table 2)**: Consolidated 5-year multi-period benchmarks with built-in variation percentage variance comparisons.
  3. **Double Investment Returns Block (Table 3)**: An advanced simulation illustrating a double investment return matrix split cleanly into a standard baseline cushion and dual distribution components (Aspect 1 & 2).
- **Interactive Formula Breakdowns**: Built-in mathematical explanations structured inside clean accordion tabs to break down compound sequences and base mappings step by step.

## Technologies Used

- **HTML5**: Semantic and modern markup layout.
- **Tailwind CSS**: A utility-first CSS framework used for rapid, fully-responsive styling alongside custom dark-mode classes.
- **Vanilla JavaScript**: Pure client-side calculations, real-time input formatting, multi-currency display simulation, and event listeners.
- **SVG Favicon**: Embedded native SVG favicon rendering a clean emoji icon (`💰`) seamlessly without requiring external asset fetches.

## Getting Started

### Installation & Deployment

Since this application runs entirely on the client-side within the browser, there are no heavy external system dependencies or server environments to configure.

1. Clone or download the repository containing the `index.html` file.
2. Open `index.html` directly inside any modern web browser (Google Chrome, Mozilla Firefox, Microsoft Edge, Safari, etc.).
3. Alternatively, drop the single file into any static hosting service (GitHub Pages, Vercel, Netlify) for rapid global deployment.

## Usage Guide

1. **Enter Monthly Living Expenses**: Provide your estimated basic monthly outflow. The input fields automatically handle currency grouping format for seamless typing.
2. **Set Annual Inflation**: Customize the project baseline inflation rate (defaults to `7.50%`).
3. **Set Fund Period**: Define how many years the final target cash reserves are built or optimized for.
4. **(Optional) Golden Age Setup**: Provide your birth year and milestone age target to unlock real-time pre-retirement scaling variables.
5. **Analyze the Projections**: Review the real-time calculated target box alongside the interactive mathematical accordions and multi-column comparison matrix below the form layout.

## Codebase Architecture

- **`index.html`**: Contains the core logic, layout architecture, calculation algorithms, numerical input intercept filters, and dynamic tailwind theme handling.
  - **Styles Block**: Handled primarily via Tailwind utility utilities. Custom transitions manage accordion height curves and dark-theme smooth transitions.
  - **Form Validation & Input Masking**: Intercept functions (`formatNumberInput`, `formatDecimalInput`) strip non-numeric parameters dynamically as users type to guarantee smooth execution without runtime application errors.
  - **Sequence Formula Framework**: Embedded logic dynamically updates Table 1, 2, and 3 simultaneously through a structured compound execution cascade whenever an input change is registered.

## License

This project is open-source and free to adapt, optimize, or distribute for personal and educational utilities.
