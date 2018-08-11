# Royale Verify 
![Royale Verify](https://i.imgur.com/5s60HnM.png)

A Discord bot that verifies users based on their Clash Royale account

Invite the bot: https://bit.ly/RoyaleVerify
# User Commands
  - `!verify <new, confirm> <Player Tag>`
    * `!verify new <Player Tag>`
      * If you are a part of the server's clans (!clans), you will recieve a deck link
      * You need to play a match with it (1v1, 2v2 or challenge) 
        * Don't worry, this is your deck with shuffled cards!
      * After the match wait 1-2 min(s) for the deck to register
      * Then go back to Discord and type...
    * `!verify confirm`
      * If you played the match and waited a bit you will get your rank
      * Rank is based on your rank in-game (Member, Elder, Co-Leader, Leader)
      * The rank roles **must** be assigned by a server admin!
  
  - `!clans`
    * Displays the server's clans
      * Name
      * Tag
      * Member count (in case you want to join!)
  
  - `!users`
    * Displays the server's verified users
  
  - `!help` (or `!commands`)
    * Displays the help menu
    
  - `!info`
    * Displays info about the bot

# Admin Commands
  - All of the above
  
  - `!setrole <member, elder, co-leader, leader> <Role Name>`
    * This command is used to set a role per rank
    * The Role Name must __NOT__ contain the `@` symbol!
    * Eg: `!setrole elder Epic Team - Elder`
  
  - `!clan <add, remove> <Clan Tag>`
    * This command is used to add or remove clans from the server's clan list
    * Eg: `!clan add GGQQUU` and `!clan remove GGQQUU` 
  
  - `!editusers <add, remove> <amount>`
    * This command is use to add/remove users from the verified users list, of the server.
