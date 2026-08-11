# Fix flaky test in the scheduler suite

Profiling showed the resolver repeating identical lookups within a single request. Adds a small per-request memo.

Change #1 of 6 on branch `pr/20260811-105826-1-fix-flaky-test-in-the-scheduler-suite`.
