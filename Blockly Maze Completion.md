# After you complete the 10th level, what is the JavaScript code you got? 

How many blocks did you have left? 
Assign it to the variable remaining_blocks.

``` level_10_code = '''while (notDone()) {
  if (isPathForward()) {
    moveForward();
  }
  if (isPathRight()) {
    turnRight();
  }
  if (isPathForward()) {
    moveForward();
  } else {
    turnRight();
  }
  if (isPathLeft()) {
    turnLeft();
  }
}'''




# Transfer the value from Level 10 "blocks remaining"
# to the variable below 

remaining_blocks = 0 


print("JavaScript code for Level 10")
print(level_10_code)

print("Number of blocks remaining", remaining_blocks) ```
