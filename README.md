# Stack-Undo-Feature-in-Text-Editor-program-27


stack = []

# Typing actions
stack.append("Type 'Hello'")
stack.append("Type 'World'")
stack.append("Delete 'World'")

print("Actions Stack:", stack)

# Undo last action
last_action = stack.pop()
print("Undo:", last_action)
print("Stack now:", stack)




Actions Stack: ["Type 'Hello'", "Type 'World'", "Delete 'World'"]
Undo: Delete 'World'
Stack now: ["Type 'Hello'", "Type 'World'"]
