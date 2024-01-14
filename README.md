Battery Polarity Simulation README

This Python program simulates a battery configuration and provides operations to change the polarity of batteries based on specific conditions. The simulation includes spinning the batteries, peeking at their initial orientation, and changing the orientation according to predefined rules.

Program Overview

The program includes the following components:

Battery Configuration
The initial battery configuration is represented by the list battery, where 'N' stands for negative and 'P' stands for positive.
The obscured battery configuration is represented by the list obscured_battery, where '-' indicates an obscured battery.
The initial peek at the battery configuration is represented by the list initial_peek, where '?' indicates an unknown orientation.
Operations
Spin Operation: Randomly reorders the batteries in the configuration.
Peek Operation: Reveals the orientation of specific batteries in the configuration based on the initial peek. The number of peeks is limited.
Change Operation: Changes the orientation of batteries based on the revealed orientations from the peek operation.
Output
The program provides information about the battery configuration and the operations performed, including the peek list and the last operation.
