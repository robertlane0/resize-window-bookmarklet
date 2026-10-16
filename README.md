# Resize Window Bookmarklet

A bookmarklet with a draggable, translucent light-red panel, live viewport dimensions, and the ability to open the same webpage in a new window at your specified size.

## Download the bookmarklet

- Ready-to-use bookmarklet — copy the contents into a bookmark's URL field
- Readable JavaScript source code 

## How to install it

1. Create a new bookmark in your browser. Name it Viewport Size.
2. Edit the bookmark and paste the entire contents of the [resize-window.min.js](resize-window.min.js) file into its URL or Address field, including the `javascript:` prefix.
3. Save the bookmark, navigate to a webpage, and click the bookmark to activate the overlay.

### Single-use:
1. Copy the contents of [resize-window.min.js](resize-window.min.js) into your clipboard and paste into the address bar of your browser.
2. Retype the `javascript:`prefix at the very beginning (modern browsers strip it out on paste to prevent self-XSS attacks).
3. Hit enter and the overlay should appear.

## How to use it

1. View live dimensions

The panel displays the current viewport width and height in pixels. It updates automatically when you resize the browser window.

2. Double-click either number

Both dimensions become editable input fields, and a Resize button appears.

3. Click Resize

The bookmarklet opens the same URL in a new window and requests your specified width and height.

## Notes:
You can drag the overlay by its header and close it with the × in the upper-right corner. Clicking the bookmarklet again removes an existing overlay.

Browser limitation: The live measurements represent the page's visible viewport, not the entire scrollable document. Opening a new window may require pop-ups to be allowed, and the browser or operating system can limit or adjust the requested dimensions.

## License:
MIT
