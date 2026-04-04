# Database Schema

## Tables

### auth.users

System table.

Stores account data.

Fields:

- id
- email
- password
- email_confirmed
- created_at

---

### profiles

Stores user profile data.

Fields:

- id
- nickname
- age
- gender
- city
- bio
- profile_completed

---

## Relationships

auth.users.id = profiles.id

One user has one profile.
