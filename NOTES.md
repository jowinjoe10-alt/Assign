## Summary of changes

- Fixed search requests so older results do not replace the latest search.
- Reset pagination when the search text or status filter changes.
- Updated search to include the assignee.
- Fixed the search SQL logic and filtering conditions.
- Added validation for page, page size, and status values.
- Cleared old frontend errors when a new request starts.

## What I chose not to change

I did not rewrite the application structure or make large UI changes. I focused on fixing the functional issues found during testing.

I also did not make larger performance or architecture changes .

 I tested the changes locally and made the final changes based on the application's behavior.