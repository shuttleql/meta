## User Schema

- Unique ID
- Name
- IsAdmin
- Gender
- Email
- Salted Password
- Level
- Preference: singles/doubles
- IsActive

## Session Schema

- Unique ID
- ctime

## UserToSession Schema

- session FK
- user FK
- checked in time
- checked out time - Nullable

### Note: Current matches will be stored in memory

## MatchLog Schema

- Court Id/name 
- team1
- team2
- ctime

### Other Notes
Club configuration will be stored in JSON configuration files. They will include information such as:

- rotation time
- max players
- courts
