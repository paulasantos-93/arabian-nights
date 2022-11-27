# arabian-nights

# Magic Lamp

- Releases a new genie every time it is rubbed
- When enchanted (instantiated), the maximum number of genies is set
- Genies can be Friendly (even) or Grumpy (odd)
- When the number of genies is exhausted, it releases a recyclable demon
- Has the ability to recharge itself by recycling a demon
- We can compare two lamps by their capacity, number of remaining genies and number of times it has been recharged

# Friendly Genie

- When released from the lamp (instantiated), the maximum number of wishes is set
- It can only grant one wish at a time
- It can grant wishes if the maximum has not been reached

# Grumpie Genie

- When released from the lamp (instantiated), the maximum number of wishes is set
- It can only grant one wish at a time
- Grants ONLY ONE wish, even if the maximum has not been reached

# Recyclable Demon

- When released from the lamp (instantiated), the maximum number of wishes is set
- It can only grant one wish at a time
- Grants ALL wishes, even if the maximum has already been reached
- It can recharge a magic lamp, if recycled
- It will not grant any more wishes after being recycled
- It can only be recycled once
