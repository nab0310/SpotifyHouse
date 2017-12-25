Will all go through my Spotify Account
1. User Accounts Plan
 - Admin User (authenticated) -> 
     - Can add or remove Host Users
     - All priviliges of Host User
 - Host User (authenticated) -> 
     - Can Approve/Disprove songs?
     - Can pick playlist to play from when we run out of songs
     - Can add or remove Trusted Users?
     - All priviliges of Trusted User
 - Trusted User (authenticated) -> 
     - Can modify play queue
     - Can skip tracks
     - All priviliges of Guest User
 - Guest User (authenticated/unauthenticated) ->
     - Can add tracks to play queue
 
 2. Layout Plan
 
 - Main Page -> 
    - Login
    - Add track to queue (button)
    
 - If the user logs in, he/she is either a Trusted or Admin User
 - Admin/Trusted Page -> 
    - Add track to queue (button)
    - Skip track (button)
    - Select a track to play in queue?
    - playlist picker (button)
 - Add track page -> 
    - Search bar. After search, the results show up in a table below. Have little + to add them to the queue.
 
 
 Also, look into bluetooth options on the pi to connect to speaker.
