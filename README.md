# ruby-crystal

A cheatsheet to migrate from Ruby to Crystal.

## Time

| Class | Ruby           | Crystal     |
|-------|----------------|-------------|
| Time  | #strftime(fmt) | #to_s(fmt)  |
|       | .at(sec)       | .epoch(sec) |
|       |                |             |

