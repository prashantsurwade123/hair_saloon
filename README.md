# Luxe Hair Studio

A responsive, frontend-only React/Vite salon website.

## Run locally

`npm install`

`npm run dev`

## Production

`npm run build` generates the static site in `dist/`. Use `npm run preview` to preview it.

## Features

Responsive navigation, six service details, pricing, gallery filters and lightbox, review slider, a booking form with native validation, contact links and WhatsApp CTA. Dialogs support keyboard focus containment, Escape and backdrop dismissal. Reduced-motion preferences are respected.

## Sample content

All business details, prices, reviews, statistics, team profiles and offers are sample content. Replace them before launch. Instagram and Facebook links currently point to their platforms; update them with the studio’s accounts. The map is an illustrative placeholder linked to a Google Maps search. Photography is remotely loaded from Unsplash and fonts from Google Fonts, requiring an internet connection. Product brand names are illustrative and do not imply affiliation.

The booking form does not send or store information. Its completion screen explicitly says the appointment is not confirmed and provides a call link. There is no backend, authentication or database.

## Validation

Production build passed. Compiled-app DOM checks passed for internal anchors, mobile menu toggling, booking submission and demo disclosure, service booking selection, gallery filters/lightbox, testimonial controls and dialog cancellation. All 11 photography URLs returned HTTP 200. Real-browser visual checks could not be run because browser access was unavailable in the execution session.
