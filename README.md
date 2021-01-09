# virtual-cricket-umpire
Virtual cricket umpire (VCU) system designed to umpire cricket matches  with a single camera.

## How it will work
With advancements in computer vision and AI, it has become much easier to track and obtain information like position or velocity from an image set or video from only one perspective.  This precision is further enhanced by the improvements in the quality of cameras.  Because most of the rules of cricket are judged by the position and movement of the player, bat, ball and bails being able to track, predict and project what these people and objects are doing allows us to create a highly accurate umpiring system to either check or replace human umpires.  While there is currently a system in place that checks for LBW decisions, it is not completely accurate (especially in terms of where the ball impacted the pads).  The VCU is being designed to check for more than just LBW reviews.

## Why do we want to do this?
We believe that cricket is a sport of great skill with the momentum of the game being completely changed in seconds.  Because cricket is likely the most difficult mainstream sport to umpire, there is a lot of room for humans to make mistakes which can change the outcome of games, series or even tournaments.  With VCU, the human element is replaced by an advanced computer system that can watch the delivery thousands of times before the on field umpire could even raise their finger to give us an extremely accurate decision.

This system is also being designed so more people can play cricket because they don't need to find an umpire and can just use a phone instead.   

## Technical Aspects
The main software packages used to build VCU will be:

- PyTorch ( for the Neural Networks )
- OpenCV ( for the computer vision )

This will help us to accurately track and predict the position  of the ball.

