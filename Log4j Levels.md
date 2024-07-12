Logging levels are used to categorize the entries in your log file

> You can filter your log files during the search.

> You can manage the amount of information that you log.

Let's consider that as the following rank order for the levels:

## ALL < TRACE < DEBUG < INFO < WARN < ERROR < FATAL < OFF  

if, for instance, the logging framework level is set to WARN, requests with any of the levels WARN, FATAL, and ERROR will be accepted, while the rest will be denied.
