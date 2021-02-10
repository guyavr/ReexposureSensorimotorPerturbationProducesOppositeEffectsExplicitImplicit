# ReexposureSensorimotorPerturbationProducesOppositeEffectsExplicitImplicit
Data for the paper Re-exposure to a sensorimotor perturbation produces opposite effects on explicit and implicit learning processes

The .mat files include the raw data collected during the experiments:  
Exp1.mat- Experiment 1  
Exp2_test.mat- Experiment 2, Test group  
Exp2_control.mat- Experiment 2, Control group  
Exp2S.mat- Experiment 2S  

Each data file contain a Table T with the following variables (columns):  
SN- subject number  
TN- trial number  
CCW- rotation direction during learning: 1- Counterclockwise; 0- Clockwise  
ti- target location  
stage- block number  
fbi- feedback: 1- cursor presented; 0- no cursor  
ri- rotation size and direction with respect to the movement of the hand (Experiment 1) or with respect to the target location (Experiments 2 and 2S): positive values- counterclockwise rotation; negative values- clockwise rotation.
(clampi- meaningless variable)  
breaks- break duration between trials (in minutes)  
hand_theta- hand movement direction with respect to the target location at the radial distance to the target (this variable was used as the 'hand angle' measure in the paper)  
raw_ep_hand_ang- actual hand movement direction at the radial distance to the target (without subtracting target location)  
MT- movement time (the interval between the time at which the amplitude of the movement exceeded 1 cm from the start location to the time at which the amplitude reached the radial distance of the target)  
RT- reaction time (the interval between the appearance of the target and the time that the hand position exceeded a distance of 1 cm from the start location)  
ST- search time (the time required to move back to the start location)  
CN- cycle number  

Note the table in Exp2S.mat does not include all variables.



More details on how the data was processed and analyzed can be found in the Methods section of the paper.
