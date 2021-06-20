# Search Bar Component

Search Bar built using HTML, CSS, Javascript

### Things to consider

- User keyboard events - translate user event to a js event
- Grabbing all the "elements" of the list to be searched from the DOM
- Getting the user's search query from the DOM
- Ensuring everything is in lowercase to ensure proper search
- Showing close matches; not showing none matches

**IMPORTANT**

- `document.querySelectorAll()` returns a <u>static</u> NodeList.
- `document.getElementsByClassName()` returns a <u>live</u> HTMLCollection.