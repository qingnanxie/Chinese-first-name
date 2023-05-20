# Chinese-first-name
1. Distinguish the Mainland Chinese first name by checking whether the names follows the Mainland Pinyin translations system 
2. There are 21 initials(Shengmu) and 39 vowels (Yunmu) which make up to 411 valid combinations of syllables in Pinyin system of mainland China 
3. Exclude 7 syllables which are very unlikely to be part of a Chinese name: "e","o","ei","ng", "eng", "ei", "m"
4. add possible substitudes for the letter "ü": "v" or "u" and "lyu" for "lü"
5. 407 syllables are included for the permutation of possible pinyin forms of Chinese first name, which make up tp 407 1-syllable names and 407^2 2-syllable names. 
6. The example code include permutations of possible Chinese first name with 1 or 2 syllables, which covers the names used by more than 98% of populations in mainland China (see https://www.mps.gov.cn/n2254314/n6409334/c6874817/content.html)
7. To get the permutation of possible pinyin forms of Chinese first name with 3 syllables, just add another loop to the example code
