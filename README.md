# Hang In There

A Javascript project refactored by Nathan Darrington from original Hang In There Project with Jeff Woltjen.

## Introduction
This project entailed constructing a motivational poster that could be created from preset values, or a user could construct their own. The project allows the user to save poster and remove saved posters. This was the first project for the 2006FE cohort at the Turing School of Software and Design. The project spanned approximately eight days.

## Progression

### Iteration 0 - Main Page

Objective: When the page loads, we should see a poster with a randomly selected image, title, and quote.

### Iteration 1 - Switching Views
Objectives:
   When a user clicks the "Make Your Own Poster" button, we should see the form, and the main poster should be hidden
   When a user clicks the "View Saved Posters" button, we should see the saved posters area, and the main poster should be hidden
   When a user clicks the "Nevermind, take me back!" or "Back to Main" buttons, we should only see the main poster section

### Iteration 2 -

On the new poster form view, users should be able to fill out the three input fields and then hit the save button
When the save button is clicked, several things will happen:

    Save the submitted data into the respective arrays (image URL into the images array, etc) so that future random posters can use the user-created data

    Use the values from the inputs to create a new instance of our Poster class
    Change back to the main poster view (hiding the form view again)
    Display the newly created poster image, title, and quote in the main view

### Iteration 3 -
Objectives:

    When a user clicks the "Save This Poster" button, the current main poster will be added to the savedPosters array.
    If a user clicks the "Save This Poster" more than once on a single poster, it will still only be saved once (no duplicates)
    When a user clicks the "Show Saved Posters" button, we should see the saved posters section
    All the posters in the savedPosters array should be displayed in the saved posters grid section

### Iteration 4 -
Objectives:

From the saved posters view, if a user double clicks a saved poster, it will be deleted

Project spec & rubric can be found [here](https://frontend.turing.io/projects/module-1/hang-in-there.html)
