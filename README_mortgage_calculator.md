# Mortgage Planner

A production-ready, single-page mortgage calculator that runs entirely in the browser using HTML, CSS, and vanilla JavaScript.

## Features

- Home purchase price, down payment amount, and down payment percentage inputs
- 15-year and 30-year quick-select loan terms, plus additional term options
- Annual interest rate input and slider
- Property tax, homeowners insurance, PMI, and HOA fee estimates
- Estimated monthly payment breakdown
- Total interest paid over the life of the loan
- Total estimated lifetime cost including principal, interest, taxes, insurance, PMI, and HOA fees
- Monthly and yearly amortization schedule
- Interactive canvas-based amortization chart showing principal, interest, and remaining balance
- CSV export for amortization schedules
- Print-friendly summary
- Responsive UI for desktop, tablet, and mobile

## Files

- `index.html` — the complete app. No build step or external JavaScript libraries are required.

## Deploying on GitHub Pages

1. Create a new GitHub repository.
2. Rename `mortgage_calculator.html` to `index.html`.
3. Upload or commit `index.html` to the root of the repository.
4. Go to the repository on GitHub.
5. Open **Settings**.
6. In the left sidebar, open **Pages**.
7. Under **Build and deployment**, choose **Deploy from a branch**.
8. Select the `main` branch and the root folder `/`.
9. Save the settings.
10. After GitHub Pages finishes deploying, open the Pages URL shown in the repository settings.

## Local Preview

You can open `index.html` directly in a browser, or run a simple local server:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Notes

This calculator is intended for planning and educational purposes. Actual lender payments, escrow costs, PMI rules, taxes, insurance, HOA fees, and closing costs can vary.
