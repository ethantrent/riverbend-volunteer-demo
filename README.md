# Riverbend volunteer signup demo

A standalone HTML/CSS/JavaScript demonstration of a volunteer-shift signup interface. The names, shifts, capacity indicators, waiver copy, and weather-cancellation banner are part of the demo; this repository does not establish a real organizational engagement.

## Try it

Open [index.html](index.html) in a browser. There is no dependency installation or build step. Use fictional names and contact details when exploring the form.

The interface shows available shifts, a signup modal, capacity updates, and a manually toggled weather notice. Its confirmation text mentions a reminder, but **no SMS or email delivery integration is implemented**.

## Storage and limits

When the host provides `window.storage`, the page uses it for signup records; otherwise it falls back to an in-memory store that resets on reload. This fallback is not a shared signup database. The demo has no server-side capacity enforcement, authentication, or operational reminder service, and should not be used to collect real volunteer information as-is.

The entire implementation is in `index.html`. This repository remains available as a UI demonstration, not a production service.
