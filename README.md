# React + ag-Grid Demo

A minimal React app demonstrating ag-Grid's client-side data grid: sortable/filterable columns, inline cell editing, and programmatic row/data updates via the grid API.

## What's inside

- A single-page app (`src/App.js`) rendering an ag-Grid (Balham theme) with editable, sortable, and filterable columns
- Sample tabular data (car make/model/price) used to demonstrate grid features
- Buttons wired to the grid API to update a cell value, replace a row's data, and trigger client-side sort/filter refreshes
- Sass styles for app-level layout (`src/assets/scss`)
- Bootstrapped with Create React App (`react-scripts`)

## Tech stack

- React
- ag-grid-community / ag-grid-react
- Sass
- Create React App (react-scripts)

## Quickstart

Dependencies are managed with Bun (see `bun.lock`).

```
bun install
bun run start
```

Then open http://localhost:3000.

### Build

```
bun run build
```

Build output is written to `build/`.

### Test

```
bun run test
```

## Screens

- Single main view: a full-height data grid with a control bar (top-left) exposing "Set Price on Toyota", "Set Data on Ford", "Sort", and "Filter" actions that call the ag-Grid API directly.
