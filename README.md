# Recipe Viewer Demo

A simple demo app showcasing how to deploy an Express app to Netlify Functions. Displays recipes fetched from a serverless Express backend.

## Features

- Fetches and displays recipes in a table
- Buttons to filter by all recipes or specific ingredients (tomato, chicken, mushrooms)
- Uses Netlify Functions to host the Express app

## Setup

1. Clone this repo
2. Open `index.html` in a browser
3. Ensure the Netlify Functions endpoint is live at `https://remarkable-choux-9b8aab.netlify.app/.netlify/functions/server`

## Usage

Click the buttons to fetch recipes from the Express app hosted on Netlify Functions and view them in the table.

## Purpose

Demonstrates:
- Hosting an Express app on Netlify Functions
- Client-side fetching from serverless endpoints
- Basic HTML/JS integration with a serverless backend

## Notes

- Hardcoded Netlify Functions URL
- Minimal styling and error handling
- See the JavaScript in `index.html` for the fetch implementation