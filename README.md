# Randomizer: a simple randomization tool

This code is generated from the following prompts in ChatGPT in early 2025.
- I want a simple webapp to find randomize a set of texts
  - the texts can be added or removed
  - the randomized text should be removed
  - simple design
- Animate "Randomize & Remove" to be more exciting
- Animate the list as well. Make it look like it takes time to pick a random choice
- Remove the delay but add a pointer to show the random pick starts from one option and moves to the next. Fast at first and slow down until it stops and chooses an option
- I don't see any cycling between options
- Each option has too big bottom padding
- I am okay with margin between choices but the padding inside each option is not heavy in the bottom
- Make it possible to add an option by enter as well
- add animation to the item removal. The remaining items should slide up, not instantly moving up
- they are dissolving, not sliding up. 
- can you change it to a simple web app without React

The result was satisfying but still lacking. A major bug was that the webapp did not really pick a random choice; the first option was always removed. Also the original styling and code formatting left a room for improvement.
