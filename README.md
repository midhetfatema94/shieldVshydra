# Shield Vs Hydra

The SHIELD is a secretive organization entrusted with the task of guarding the world against any disaster. Their arch nemesis is the organization called HYDRA. Unfortunately some members from HYDRA had infiltrated into the SHIELD camp. SHIELD needed to find out all these infiltrators to ensure that it was not compromised.

Nick Fury, the executive director and the prime SHIELD member figured out that every one in SHIELD could send a SOS signal to every other SHIELD member he knew well. The HYDRA members could send bogus SOS messages to others to confuse others, but they could never receive a SOS message from a SHIELD member. Every SHIELD member would receive a SOS message ateast one other SHIELD member, who in turn would have received from another SHIELD member and so on till NickFury. SHIELD had a sophisticated mechanism to capture who sent a SOS signal to whom. Given this information, Nick needed someone to write a program that could look into this data and figure out all HYDRA members.

#H3 Sample Input
Nick Fury : Tony Stark, Maria Hill, Norman Osborn

Hulk : Tony Stark, HawkEye, Rogers

Rogers : Thor

Tony Stark: Pepper Potts, Nick Fury

Agent 13 : Agent-X, Nick Fury, Hitler

Thor: HawkEye, BlackWidow

BlackWidow: Hawkeye

Maria Hill : Hulk, Rogers, Nick Fury

Agent-X : Agent 13, Rogers

Norman Osborn: Tony Stark, Thor


#H3 Sample Output
Agent 13, Agent-X, Hitler
