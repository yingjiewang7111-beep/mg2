# minigame 2
## Devlog


1. An issue I encountered: 

When writing the sixth step of the ColorChange code, I wanted to output value and string as a single line of text, so I instinctively used "," as the concatenation symbol in Python. Then the console showed that this line has a compile error. It wasn't until I saw the standard code in the Inspector that I remembered to use "+" for concatenation in C#.


2. My guess about "_spriteRenderer.color = new Color(r, 0.2f, 0.2f);" : 

First of all, this line of code triggers the corresponding color change when the chest's health decreases. It is because the variable r takes different values when the chest's health values are 3, 2, and 1, respectively. 
For the period ".", I guess it is used to indicate the type of the parameter within parentheses is float. "float" cannot be recognized as a type in the name, so I think this might be using symbols as substitutes.
For "new," as I explained at the beginning, since r is a parameter with different values, it generates new RGB color combinations that replace the previous colors.


## Open-Source Assets
- Pixel art environment & character sprites: https://assetstore.unity.com/packages/2d/environments/pixel-art-top-down-basic-187605
