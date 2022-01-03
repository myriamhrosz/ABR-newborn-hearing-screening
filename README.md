# ABR-newborn-hearing-screening
Analysis on Auditory Brain Response (ABR) to sound.

Consider the problem of measuring the auditory brainstem response (ABR) to brief sounds, a
procedure that is used in newborn hearing screening in hospitals across the country. Two electrodes
are affixed to the baby’s head; one on the high forehead, and another behind the ear to which sounds
are played. The voltage difference between those electrodes are recorded for about 3 − 4 minutes,
while about 1000 repetitions of the sound are played to the ear. The ∼ 3 − 4-min-long recording
is then bandpass filtered, and broken down into 1000 segments, one per presentation, in a timelocked manner. The segments are then averaged together to obtain the neural response to sounds.
Here, we will carry out these processing steps using the data contained in the file eegdata.mat.
The file contains the raw recording in a variable called raw, the sampling rate fs, and a variable
called clicks which contains the sample numbers of the raw recording at which a brief sound was
initiated.
