# LiveStreaming_Application_TestCase
Website Test Case Plan - Positive Scenarios
Website URL: https://cinemawebapplication.netlify.app/

1. Introduction
This document outlines the positive test cases designed to verify the core, expected functionality of the CinemaWeb application. All test cases listed below have been validated and marked as "Pass".

2. Test Case Suite
2.1. Functional Test Cases (Positive)
This section verifies that the main features of the website work as intended.

Test Case ID

Feature

Test Scenario

Steps to Reproduce

Expected Result

Actual Result

Status

FT-001

Homepage

Verify "Book Now" button on the main banner.

1. Navigate to the homepage. <br> 2. Click the "Book Now" button on the sliding banner.

User should be redirected to the details page for that specific movie.

Same as Expected

Pass

FT-002

Movie Search

Verify search with a valid, existing movie title.

1. Type an existing movie name (e.g., "Endgame") into the search bar. <br> 2. Press Enter or click the search icon.

The search results should display the correct movie.

Same as Expected

Pass

FT-004

Movie Details

Verify that clicking a movie poster navigates to the details page.

1. On the homepage, click on any movie poster in the "Now Showing" section.

The page should navigate to the detailed view for that movie, showing its trailer, summary, etc.

Same as Expected

Pass

FT-005

Movie Trailer

Verify that the "Watch Trailer" button works.

1. Navigate to any movie's detail page. <br> 2. Click the "Watch Trailer" button.

A video player should open and play the movie's trailer.

Same as Expected

Pass

FT-006

Ticket Booking

Verify initiation of the booking process.

1. Navigate to a movie's detail page. <br> 2. Click the "Book Tickets" button.

The user should be taken to the seat selection screen for that movie.

Same as Expected

Pass

FT-007

Seat Selection

Verify selecting and deselecting a seat.

1. Go to the seat selection page. <br> 2. Click on an available seat. <br> 3. Click on the same seat again.

The seat should highlight when selected and return to its original state when deselected. The "Seats Selected" and "Total Price" should update accordingly.

Same as Expected

Pass

FT-009

Booking Process

Verify proceeding to payment after seat selection.

1. Select one or more seats. <br> 2. Click the "Proceed to Pay" button.

The user should be taken to a payment or confirmation page, showing the selected seats and total price.

Same as Expected

Pass

2.2. UI/UX Test Cases
Test Case ID

UI Element/Page

Test Scenario

Expected Result

Actual Result

Status

UI-001

All Pages

Check for a consistent header and footer.

The header with the logo, navigation links, and search bar, and the footer should be present and consistent on all pages.

Same as Expected

Pass

UI-002

Navigation

Verify all main navigation links are working.

Clicking on "Home," "Events," and "Contact us" should navigate to the respective sections/pages.

Same as Expected

Pass

UI-003

Homepage

Check movie carousels for "Now Showing" and "Coming Soon".

The carousels should be scrollable, and the movies should be correctly categorized.

Same as Expected

Pass

UI-004

Seat Selection

Verify the seat legend/key is clear.

The page must clearly indicate what the colors/styles for "Available," "Booked," and "Selected" seats mean.

Same as Expected

Pass

2.3. Responsiveness Test Cases
Test Case ID

Device/Screen Size

Test Scenario

Expected Result

Actual Result

Status

RT-001

Mobile (e.g., 375px width)

Check the layout of the homepage.

The layout should be single-column. The movie posters should stack vertically. Text should be readable without zooming.

Same as Expected

Pass

RT-002

Mobile (e.g., 375px width)

Check the navigation menu.

The navigation should collapse into a hamburger menu, which should be functional when tapped.

Same as Expected

Pass

RT-003

Tablet (e.g., 768px width)

Check the seat selection screen.

The seat map should be clearly visible and usable. It should not require horizontal scrolling.

Same as Expected

Pass
