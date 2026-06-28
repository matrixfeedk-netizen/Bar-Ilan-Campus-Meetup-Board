# Bar-Ilan Campus Meetup Board

A simple campus meetup board for Bar-Ilan students who want to post and discover informal events across campus.

## What it does

- Lets a student post a meetup with a building number, room number, time, and free-text event description.
- Validates empty or incorrect inputs with friendly messages.
- Shows the newest meetups at the top of the page.
- Saves posted meetups in the browser with localStorage, so they remain after refreshing on the same device.
- Allows a student to delete a local meetup card from the board.

## Live link

https://matrixfeedk-netizen.github.io/Bar-Ilan-Campus-Meetup-Board/

## How to use it

1. Open the live link or open `index.html` in a web browser.
2. Fill in the building number, room number, time, and event description.
3. Click **Post meetup** to add the event to the board.

## Known limitations

This is a simple version of the app. Events are saved only in the user's browser using localStorage. This means posts are not shared between all students yet. A future version could use a real database so that all students can see the same events.

