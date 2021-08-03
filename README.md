## Overview:

A datacenter is made of rooms, rows, and racks.

At a glance the user is able to:

```
1. See the rooms in a given datacenter
2. Clearly see the room structure (room --> rows --> racks)
3. View the status of every rack:
        - green color cells for passing
        - red color cells for failing
4. Access any rack and view detaile TOR/s info

```

## Challenges:

Several:)

I have used Redux before and thought I'd peak into React hooks this time - took me a second to make sense of those. A rewarding learning curve - turns out hooks are far less verbose.

I did CSS manually to get some practice - even a smaller project like this one takes time to tweak. In production, a UI framework (e.g. Material UI) would probably be easier/cleaner.

## Potential things to improve/add:

###### Visualization

What is now a one page visualization (as per assignment), could be broken down to a few. Datacenters --> Rooms in a selected DC --> Room view --> TOR profile.

###### Database

With real-world database, cells would eventually fill up with life dynamic data. I would love to add a profile feature for an Admin (maybe a regular profile to for general access), who will be able to update, add and clear racks.

###### Code

I am yet to learn some ins and outs of React, there is always room for cleaner, compact yet readable code. I would get a second pair of eyes on a project right after submission.

## Thank you for your time and have a great day!
