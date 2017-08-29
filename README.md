# AuCT
(Audio Capture Tool)

South Africa has eleven official languages. Building out tools to support small-scale voice recognition across a large number of languages requires having a large amount of labeled audio files for training and testing. Your task is to create a web-based, or combination web- and mobile-based tool to support the collection and in situ segmentation and labeling of audio data. The use case is: a participant would use your tool to record a set of words from a list. These would then be segmented, with some control to throw out mistakes that may have been made during data capture, resulting in a set of individual, labeled audio files.

## Core features
- [ ] Input/select the word list that user will read aloud
- [ ] Record audio while user reads the list
- [ ] Editor to sample audio files and label (at researcher or user side, we decide) which word they correspond to
- [ ] Some way to save the fragmented audio files (database, zip download, etc)
- [ ] Audio playback
- [ ] UNICODE text support

## Optional features
- “Whatever you want”
- Can be Algorithmic or User-based splicing (or a combination)
  - [ ] ALGO : Record big chunks and process
  - [ ] USER : Capture button presses for words and mistakes WHILST recording audio
- [ ] Adjust playback speed, scrubbing, skipping
- [ ] Optional downloading at lower audio quality (bitrate change) 
- [ ] Customise UI for other languages
- [ ] Choose language when first visiting site (on landing page)
- [ ] Support different unit sizes (words, phrases, sentences)
- [ ] Trim silent ends of words to remove all silence from a clip
