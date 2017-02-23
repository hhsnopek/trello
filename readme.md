# trello

## Definition
```
# {pipeline}
- [{label}] {title} - {description}
  Due: ({date} @ {time}])
  Assignee: {assignee}
  - [ ] {sub-task}
  - [ ] {sub-task}
```

## Example:
```
# Todo
- [High Priority] File Based Trello - Create file based trello board
  Due: (March 5, 2017 @ 16:00)
  Assignee: (Henry Snopek <hhsnopek@gmail.com>)
    - [ ] Connect to API
    - [ ] Build out parser

+ [Blue] Another Issue - With Description
+ [Yellow] QA: Fix blah - Not again...
```


### Vim-Folding
```

# Todo
+ [Blue] Another Issue - With Description
+ [Yellow] QA: Fix blah - Not again...
- [High Priority] File Based Trello - Create file based trello board
  Due: (March 5, 2017 @ 16:00)
  Assignee: (Henry Snopek <hhsnopek@gmail.com>)
    - [ ] Connect to API
    - [ ] Build out parser

# {pipeline}
+ [{label}] {title} - {description}
+ [{label}] {title} - {description}
- [{label}] {title} - {description}
  Due: ({date} @ {time}])
  Assignee: {assignee}
  - [ ] {sub-task}
  - [ ] {sub-task}
```
