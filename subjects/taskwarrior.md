
- links
   - [docs](https://taskwarrior.org/docs/)
   - [advanced date stuff](https://taskwarrior.org/docs/using_dates.html)
   - [modifying tasks](https://taskwarrior.org/docs/commands/modify.html)
   - [date formats](https://taskwarrior.org/docs/dates.html)
   - [reports graphical stuff](https://taskwarrior.org/docs/report.html)

- commands
   - `task completed`
      - show completed tasks
   - `task ghistory`
      - graphical stuff
   - `task list`
      - unordered list
   - `task` or `task next`
      - order by priority
   - `task add <task text>`
      - `priority:H` - high priority
      - `due:friday` - mark priority
   - `task 2 done`
      - mark task with id 2 as complete
   - `task <id> delete`
   - `task modify`
      - `task 1 modify <new description>`
      - `task 1 modify /teh/the/`
      - `task status:pending modify +home priority:H due:eom`
         - make all tasks due end of month
   - `task <id> info`


- modifiers/filters/etc
   - recurring
      - `task add brush teeth recur:monthly due:21:00`

   - by project
      - `task <add/list/next project:<project_name>`
   - task time format (due)
      - `task ... due:<time>`
      - exact date or ISO-8601 - `7/14/2008`, `2013-03-14T22:30:00Z`
      - relative - `now`, `today`, `yesterday`, `tomorrow`
      - time - `hh:mm`

