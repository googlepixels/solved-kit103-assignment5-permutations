Download Link: https://assignmentchef.com/product/solved-kit103-assignment5-permutations
<br>
<h1>Question 1: Permutations</h1>

<ol>

 <li>(*) How many strings of length three are possible using characters from ‘AUGC’ (characters may be reused)? Write Python code to calculate the number.</li>

 <li>(*) Write a set comprehension to generate those strings.</li>

 <li>How many three-word sentences can be created from the words ‘cat’, ‘sat’, ‘hat’, ‘mat’, and ‘pat’, using each word at most once? (Most of the sentences won’t make sense.) Write Python code to</li>

</ol>

calculate the number.

<ol>

 <li>Write a set comprehension to generate tuples (not single strings) of the di erent arrangements described in part (c).</li>

</ol>

<h1>Question 2: Combinations</h1>

You should use the de nitions of toy droid names and Star Trek species provided in the assignment script in your answers.

<ol>

 <li>(*) How many di erent combinations of two distinct colours are possible given the set of colour names { ‘red’, ‘orange’, ‘yellow’, ‘green’, ‘blue’, ‘indigo’, ‘violet’ }? Write Python code to calculate the</li>

</ol>

number. Do not directly call factorial or fact in your solution.

<ol>

 <li>(*) Given the list of colour names de ned in the script le, write a set comprehension to generate those combinations. (The answer will be a set of 2-tuples, or pairs.)</li>

 <li>(*) How many di erent groups of three students can be formed from a class of 12? (Assume that only a single group is to be formed.) Write Python code to calculate the number.</li>

 <li>(*) Assuming the students are named ‘Student k’ for k <sub>∈</sub> {1, 2, …, 12}, write a set comprehension to generate the possible compositions of a single group.</li>

</ol>

<h1>Question 3: You choose which</h1>

The following information is used in all parts of this question. Jodie has 18 books in her collection at home. They all have short titles: ‘A’, ‘B’, ‘C’, …, ‘R’ (there is a list of these in the assignment script).

<ol>

 <li>(*) Jodie is going on holiday, but can only take ve books with her. What are her options? Write a set comprehension to generate them all.</li>

 <li>(*) All of Jodie’s books t on a single shelf. How many di erent ways can she arrange them? Write Python code to calculate the number.</li>

 <li>Jodie sometimes likes to reread books, and may even reread a book she has just nished. What are the possible sequences of book titles of the last three books she has read? Write a set comprehension to generate the alternatives.</li>

 <li>Write Python code to calculate how many such sequences there are. (Do not use the len function on your previous answer; doing so will receive 0 marks.)</li>

</ol>

<h1>Question 4: Lovers of anagrams know words are mightier than the sword</h1>

An <u>anagram</u> is a word whose letters, when rearranged, form another word. They are a common feature of <u>cryptic crosswords</u>, but you do not need to know how to solve a cryptic crossword to solve this question. An anagram solver nds the alternative arrangements of a word’s letters that represent valid words. Your task is to write the two components of a basic anagram solver: the rst part generates the set of all possible permutations of the letters in a given word; the second part restricts this set to contain only those permutations that are valid words.

There are two stub functions for you to complete:

<ol>

 <li>word_perms(word): should generate and <strong>return</strong> all permutations of the letters in the string represented by word (each permutation will be a single string, not a tuple). It will probably be one line of code.</li>

 <li>anagrams(word): should <strong>return</strong> a set of all the permutations of the letters in word that are valid (that is, that appear in one of the collections of words described below), including the original word. The input can be assumed to be in lower case.</li>

</ol>

Not all solutions to this task will receive full marks; an ideal solution will look very short, but still be readable.

The assignment script le contains code to load collections of words of di erent lengths (between 2 and 10) into two Python dictionaries, one that holds the words in sorted lists and another that holds them in sets. To use the list of words of length n, use word_lists[n], whereas to use the set of words of length n, use word_sets[n] (you will probably not have a variable called n but an expression instead). You do not necessarily have to use both of these. Select whichever you believe is best-suited to the task.

In order for these words to be loaded in your program you must download and unzip the le containing the words, words.2-10.txt, that accompanies this document on MyLO. Do not submit this

le with your assignment; we already have a copy.

Warning: The list of words has only been ltered to remove entries that do not contain ordinary letters ‘a’ to ‘z’, so o ensive words will be present. The list also contains many proper nouns and acronyms, so you might not recognise every output from your anagram solver.

<h2>Testing your anagram solver</h2>

To test word_perms, call it with very short words for which you can enumerate all the possible permutations. To test anagrams try it on the word ‘lovers’. Other good words you could try include ‘alerts’, ‘heart’, ‘parsec’ and ‘spare’.