This is a relatively simple templating engine I developed for another project (forthcoming).  This was originally written in Common Lisp (code available on request), back in January 2019 for something I call variable pathing.  I've used this for a couple different projects now.

After consideration, I'm releasing this early as its usefulness far extends beyond my other project.

Future Plans:

  Documentation and Examples!

  Variable globbing (or regex?)

There are no plans of adding branching or looping, as this is intended on being
as light as possible.

Contributions welcome!

3/1/2020 - Syntax Update, Part I
  Updated syntax to make it cleaner, and more inline with jinga2/django.  Spaces are now
  supported around variable names and filters.  Also, the double bars have been replaced with single bars.
  Part II will focus on filters, and bringing them more in line with jinga2/django.
  This is to hopefully make them more interchangeable, and hopefully a cleaner syntax.

11/5/2019 - Hot, security related, update:
  Padding functionality has been removed (commented out), due to unsafe use of Python string format method.  Functionality will be reintroduced later.  See issue #1.
