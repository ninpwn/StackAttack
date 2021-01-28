# StackAttack
A tool written in python3 to exploit simple stack-based buffer overflows.

### Todo
- [ ] Remove unneeded os module import 
- [ ] Fix typo on line 281. \\x00\\x01 = 0102 should be \\x01\\x02 = 0102.
- [ ] Remove nops variable from line 305. Previously the nops were passed to msfvenom but they are now separate.
- [ ] Add additonal error handling. I.e. detect if chars.txt is missing when badchars is run.
- [ ] Add color class to make stdout easier to decipher.

### Completed ✓
- [x] Created Todo