# GitHub Markdown Lesson 1
For lesson 1, the goal is to learn how to format text using github flavor of markdown,
create lists **(numbered and bulletted)**, create tables and add links and images to the
document.
# Simple Text
Simple text is easy. Start with a new line and add your text.
## Second Level Header
You can add different levels of headers easily.
### Third Level Header
#### Fourth Level
##### Fifth Level
For creating **bold** simply add ** before and after the characters.<br/>
For creating ~~StrikeThrough~~ add ~~ around text. Make sure not to leave **any spaces<br/> between text and these special characters**<br/>
For creating *italics* simply use * or _ around text<br/>
These can be combined around \_\_\*\*text\*\*\_\_ to create _**italic bold**_<br/>
## Lists
The text in the previous secon can be turned into list with bullets or numbers
## As bulletted list
- For creating **bold** simply add ** before and after the characters.
- For creating ~~StrikeThrough~~ add ~~ around text. Make sure not to leave **any spaces<br/> between text and these special characters**
- For creating *italics* simply use * or _ around text
- These can be combined around \_\_\*\*text\*\*\_\_ to create _**italic bold**_
## As a numbered list
1. For creating **bold** simply add ** before and after the characters.
2. For creating ~~StrikeThrough~~ add ~~ around text. Make sure not to leave **any spaces<br/> between text and these special characters**
3. For creating *italics* simply use * or _ around text
4. These can be combined around \_\_\*\*text\*\*\_\_ to create _**italic bold**_
## Task lists
- [X] Task 1
- [X] Task 2
- [X] Task 3
- [ ] Task 4 is not complete
## Quotes
Remember:<br/>
> **Markdown** has many flavors. For GitHub readme files, remember to use the related
syntax.
## Tables
c1 | c2 | c3
-- | -- | --
a1 | b1 | c1
a2 | b2 | c2
a3 | b3 | c3
## Python Code Example
```Python
import unittest
class TestSum(unittest.TestCase):
  def test_list_int(self):
    """
    Test that it can sum a list of integers
    """
    data = [1,2,3]
    result = sum(data)
    self.assertEqual(result, 6)
if __name__ = '__main__'
  unittest.main()
```
