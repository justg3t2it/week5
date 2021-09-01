Assignment: Anagrams Problem

Given two words, tell me if one is an anagram of the other
examples: 

cats, tacs => true
fast, fats => true

Pseudocode: 

Sort through cats then sort through tacs
    compare sorts (are the same characters present?)

        If yes: 
            True, inputted strings are anagrams 
        If no: 
            False, inputted strings are not anagrams
        If not a string:
            Error, enter a proper intput 

