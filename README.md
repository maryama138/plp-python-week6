# PLP Python Week 6 - Safe Functions

This assignment practices using try/except to catch errors and keep Python programs running.

### Files

* `safe_tools.py` - Contains safe functions for division, converting text to numbers, and looking up dictionary fields.
* `unbreakable.py` - Contains the additional error-handling practice for this assignment.
* `README.md` - Describes the assignment and the files.

### Why can the if check not catch "abc" on its own?

An `if` check can test conditions, but converting `"abc"` with `int()` causes Python to raise a `ValueError`. The `try/except` block catches this error and prevents the program from crashing.
