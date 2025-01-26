# livetune
Audio Waveform Analyzer


Goal of the program

Live tune is a program that can take as input an audio waveform and output the key that the vocalist/instrument is playing at during various parts of the waveform. Using this information a voice type should also be reported - assuming that the input is a vocal.

Challenges
UNderstanding how sound is transduced and stored digitally
understanding how to obtain how to calculate a key of an instrument/vocal given the likely constant sound variation
How to manipulate with audio waveforms in C/C++

my idea of a solution
For a relatively small interval of the waveform I will analyze the base frequency, then I will mark the point at which a certain base frequency appears to the point where it transitions to be a certain key

to find the vocal type of a singer I simply need to identify what frequency range it most closely falls into, the basic categories are
bass: f2 - f4
baritone: a2 - a4
tenor: c3 - c5

alto: f3 - f5
mezz-soprano: a3 - a5
soprano: c4 - c6



Learning Opportunities

Physics of sound
sound transduction
Libraries for manipulating audio waveforms
Deeper understanding of audio file structures