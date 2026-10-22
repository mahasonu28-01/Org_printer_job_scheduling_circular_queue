PRINTER JOB SCHEDULING — DYNAMIC CIRCULAR QUEUE

Files
- dynamic_circular_queue_printer_scheduler.html: the complete website in one HTML file.

How to run
1. Extract this ZIP file.
2. Open dynamic_circular_queue_printer_scheduler.html in Chrome, Edge, Firefox, or another modern browser.
3. Enter a printer job name and choose Enqueue, or press Enter in the input field.
4. Use the queue operation buttons to test enqueue, dequeue, Process Job, peek, size, empty checking, display, and clear.

Process Job
- Simulates printing the job at the Front of the queue.
- Removes that oldest job from the queue, increases the Jobs processed counter, and records the action in Operation history.
- This is a software simulation; it does not send files to a physical printer.
- The Jobs processed counter is cumulative for the current page session and does not reset when Clear Queue is clicked.

Circular queue details
- The circular array expands automatically when full and can shrink as it becomes sparse.
- Front/Rear positions wrap using modulo arithmetic.
- The full queued job names are also shown in the Front-to-Rear list.
- The Algorithm section documents the queue operations and their time complexities.
