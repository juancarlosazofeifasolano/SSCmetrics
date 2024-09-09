# SSCmetrics

Objective
The goal of this MATLAB live file is to show and explain all the processing steps and Matlab commands required to compute the five metrics of the Soundscape Code (Wilford et al. 2021). The example below uses data from a SoundTrap ST600 (Ocean Instruments, New Zealand) deployed in Lizard Island, Great Barrier Reef, Australia. The example audio file (.wav) is a five minute recording, using high gain, and 48 kHz sampling rate. The audio file is calibrated and processed into four one-minute segments, following the one-minute length files in Wilford et al. (2021). Thus, this code computes and stores the Soundscape Code metrics for each one-minute segment. Consider that this code is meant to show how the code works on a single example and for our instrument. For batch processing and other instruments, the code should be modified to consider noise removal, instrument-specific calibration, and loops for batch processing. Below we provide the code with a brief exaplanation, following the equations in Wilford et al. (2021) and updates of terminology in ISO (2017).
References:
Wilford DC, Miksis-Olds JL, Martin SB, Howard DR, Lowell K, Lyons AP, Smith MJ. 2021. Quantitative soundscape analysis to understand multidimensional features. Frontiers in Marine Science 8, 672336. 10.3389/fmars.2021.672336.
ISO. 2017. 18405.2. Underwater Acoustics—Terminology. International Organization for Standardization, Geneva.

https://drive.mathworks.com/sharing/c684502f-8cc2-4922-bc5e-bbdf0b36ee9a 
