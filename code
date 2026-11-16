def find_top_word(text):
  words = text.lower().split()
  word_count = {}
  for word in words:
    if word in word_count:
      word_count[word] += 1
    else:
      word_count[word] = 1
  highest_count = 0  
  top_word = ""  
  for word in word_count:
    if word_count[word] > highest_count:
      highest_count = word_count[word]
      top_word = word
  return f"我們的冠軍是: {top_word}，出現了 {highest_count} 次！"
