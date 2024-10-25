# Onboarding

* [X] User Creation
  * [ ] User Validation
    * [ ] User Exists
    * [ ] SteamId In use
    * [ ] Discord Id in use
* [ ] Profile Info
* [ ] User Deletion
  * [ ] Remove GDPR Data
  * [ ] Set user as deleted
  * [ ] Retain stats

# Admin

* [ ] Ban Player
* [ ] Kick Player
* [ ] Unban Player
* [ ] Assign Role
* [ ] Create Fake User
* [ ] Delete Fake User

# Leagues and Seasons

> Leagues and seasons should not by their very nature be able to be removed, if a league is no longer active in a channel it can be disabled, and league should be disassociated with a channel. but records should not be deleted.
>
> Season can only be deleted, if and only if it has not been active yet (i.e, no gather has taken place in the season)

* [ ] Update League
* [ ] Disable League
* [ ] Add Season
* [ ] Update Season
* [ ] End Season

# Stats and Info

* [ ] Show Rank / Points
* [ ] Whois command
* [ ] Live Game List
* [ ] Live Game by Id
* [ ] Live Game by Player

# Gathers

> Gather creation is done in 2 steps, first a signup is created, then when signup is complete, a gather is generated based on the information from the signup. If teams are predetermined, the signup step should be able to be skipped. (to mostly be used in API and not with discord bot)
>
> a Bo3 is simply a collection of 3 gathers, with a thin wrapper that only holds the aggregate score of the individual gathers.

* [ ] Create Signup
* [ ] Create Gather based on Signup
* [ ] Create Gather without signup (for predetermined teams)
* [ ]

# Challenging

* [ ] Challenge Player
  * [ ] Accept
  * [ ] Decline
  * [ ] Error Handling
    * [ ] Player Already in Gather
    * [ ] Player Sanctioned
    * [ ] Player in another signup
    * [ ] Insufficient Privileges

# Signup

* [ ] Player Signup
  * [ ] Error Handling
    * [ ] No Gather
    * [ ] Sanctioned Player
    * [ ] In pick phase
    * [ ] In another signup

# Select

# Pre-Start

# Start

# End

# Stats

* [X] Kill
* [X] Assist
* [ ] Damage
* [ ] Bomb Plant
* [ ] Round Start
* [ ] Bomb Defuse
  * [ ] With Kit
  * [ ] Without Kit
  * [ ] Defuse Completed
* [ ] Round Won
* [ ] Send Score Update
* [ ] Gather Start
* [ ] Gather End
* [ ] Gather Paused

# Post-Game
