# Parsing-spoken-sentences-with-MAUS
Examples for parsing spoken sentences with the Munich AUtomatic Segmentation toolbox using Python, subprocess and curlcall. 

An empty "targetfile" is required, there is one uploaded that is fit for purpose.

# BASICS
Covers how to upload audio files (.wav) and transcripts (.txt) to parse spoken sentences for word onsets and offsets and how to parse for phonemes. This is an especially useful way to identify onsets (or offsets) of target words.

An example for cutting audiofiles based on parsed speech is given. This is especially useful as an automated mechanism for removing silences at the start and the end of audio recordings. This can also very easily be adapted for inserting silences into segments of speech, removing pauses, words, segments of speech etc.
