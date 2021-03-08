# NegationScopeAnnotation_for_Chinese_as_a_Second_Language
## Corpus Description
This is a new moderate-sized Chinese corpus that contains manual negation annotations for 8000 sentences written by non-native speakers (i.e., Japanese and English), as well as their corrections by native speakers (i.e., Chinese). 
Negation sentences are crawled from Lang-8 (https://lang-8.com/) which is a language-exchange social networking platform, where second language learners of different languages can put their essays and receive modifications from native speakers. 
The following is an example of negation annotation for Chinese written by Japanese native speakers and the correction by Chinese native speakers. We annotated the negation cues and negation scopes.

1.1 Chinese written by Japanese native speakers： 换 言 说 ， 【没有】 [宗教 生活 与 日常 生活 差距]。
1.2 the correction by Chinese native speakers：   换 言 说 ， [宗教 生活 与 日常 生活 之间] 【没有】 [距离]。

## File Description
english_orig_conll.txt: the annotated negation Chinese sentences as a Second Language written by English native speakers.
english_corr_conll.txt: the corresponding Chineses sentence corrected by Chinese native speakers. 
english_orig_conll.txt and english_corr_conll.txt are parallel files.

japanese_orig_conll.txt: the annotated negation Chinese sentences as a Second Language written by japanese native speakers.
japanese_corr_conll.txt: the corresponding Chineses sentence corrected by Chinese native speakers. 
japanese_orig_conll.txt and japanese_corr_conll.txt are parallel files.

## Format Description
The Corpus is in a CoNLL format. Column description is in the following.

column 1: sentence number
column 2: word number
column 3: language
column 4: placeholder
column 5: word
column 6: POS generate by StanfordCoreNLP
column 7: placeholder
column 8-10: the first negation expression; column 8 is negation cue; column 9 is negation scope; column 10 is a placeholder;
column 11-13: the second negation expression; column11 is negation cue; 12 is negation scope; 13 is a placeholder;
...


