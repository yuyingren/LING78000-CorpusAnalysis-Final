# LING78000-CorpusAnalysis-Final

<br />Files description:

<br />JMdata:
<br />
<br />      kata_cmu.csv: contains the katakana words extrated from JM dictionary and Their English conterparts plus their pronunciations from CMU dictionary
<br />      JMdict_annot.tsv: the katakana dictionary from above but manually cleaned up
<br />      JMdict_aligned.csv: the katakana dictionary, but the katakana chracters and English pronunciations are aligned
<br />      JMDataTrainResult: the train, dev, test data of the JM katakana dictionary and it prediction result with Transformer
<br />
<br />
<br />Edict:
<br />
<br />      Edict_annot.tsv: the katakana dictionary from above but manually cleaned up
<br />      Edict_aligned.csv: the katakana dictionary, but the katakana chracters and English pronunciations are aligned
<br />      EDataTrainResult: the train, dev, test data of the katakana dictionary extracted from Edictionary and it prediction result with Transformer
<br />
<br />
<br />TrainJMED:
<br />
<br />      contains all 12 train, dev, test datafiles, the aligned CMU pronunciation is marked as xxx.kcmu; the unaligned CMU pronunciation is marked as xxx.cmu
<br />
<br />
<br />ResultJMED:
<br />
<br />      contains the results of all the experiments:
<br />      kata-phone-eng: the back transliteration from katakana to English (using phonological feature as medium)
<br />      eng-phone-kata: the transliteration from English to Katakana (using phonological feature as medium)
<br />      orthography-based: the transliteration/back transliteration between Katakana and English (directly from characters to letters)
