##### General questions
- What is the shortcut for selecting the next or all instances of the same text as highlighted?

##### About_strings.rb
Line 39-42: Really interesting to see that \n (new line characters) count as characters
- But why is the correct answer "$/" when the check says "Expected FILL ME IN to equal \n"? [Stackoverflow](https://stackoverflow.com/questions/6323274/why-does-n-not-work-and-what-does-mean)
    - Figured it out, "\n" has to be in quotes
- Why is there a difference in the answers from 43-45 and 53-55? Seems like the same strings. 
    - Figured it out, the beginning of the string in the second one is the "I" and not the new line string. [Stackoverflow](https://stackoverflow.com/questions/14893722/why-is-the-inline-string-block-in-ruby-named-eos)

Line 119: so '\\\'', '\\'', "\\\'", and "\\'" all print as the same string ("\'"), but why? And then why are "\'" and '\'' different? 

##### About_symbols.rb
Line 88: why does throwing a NameError work for the check?

##### About_arrays.rb
Line 42-44: why are the answers for array at 4,0 and 5,0 different? They are both our of the range of the array, so they should either both be empty or both nil
Line 48: didn't know there was a Range object!
Line 51: extra dot in the Range is noninclusive on the top end
