### Weekly Update - 4.26 - 5.2

Done:
1. Two walking experiments and collected synchronous data from two Myos
2. Figured out the x, y, z orientations for gyro and acc data
3. Steps can be identified clearly from gyro data on a specific axis (the gyro data lokks very similar to the 'Stride Length Estimation' Paper)

Questions:
1. Did many experiments but what angles the orientation data represent are still not very clear

Next Step:
1. Try the method on 'Stride Length Estimation' Paper to do integration (it's better to have orientation data, but it might be dorable by just using integration of gyro data), time frame, 2 weeks

### Weekly Update - 5.3 - 5.16

Done:
1. Interpolation of discrete gyro and acc data
2. Peak finders on gyro data for segmentation
3. Integration performed to get horizontal velocity and stride length for cycle 1 and cycle 2

Question:
1. The acc data seems to have great impact on the stride length estimation, need to find out the reason for cycle 2 result

Next Step:
1. Debug the code for stride length estimation, time frame, 2 weeks