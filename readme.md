# Person Marking in South-Central Trans-Himalayan: Mizo

This PARALEX set contains person markers in Mizo, including inflected verbal forms and pronouns. It constitutes part of the PMST (Person Marking in South-Central Trans-Himalayan) database.
The PMST database is a collection of person forms from a broad sample of South-Central Trans-Himalayan languages collected with a common methodology and published as PARALEX sets. PMST sets can be used both for describing and analyzing language-internal distributions and for comparison of person forms.

The general design principles of PMST are described in Auderset et al. 2026. Files and columns are described here only where they deviate from the PARALEX standard.
For more details about the data, please consult the data\_sheet.md in the docs folder.

* PMST diverges most from the PARALEX standard and design principles in that the verb forms are abstract and do not contain a lexical verb stem. In its place, we use Σ
as a placeholder (as is common in Trans-Himalayan linguistics). This means that there is no lexeme table and the data set cannot be used to study variation in verb stems.
* The source\_form column in the forms file contains the data exactly as it appears with in the source. This may include a lexical verb stem (listed in lexemes). In the orthographic and phonological representation, the lexical verb is replaced by a Σ (as there are no inflectional classes). This placeholder also appears in the graphemes and sounds files for validation purposes.
* The lexemes file is kept relatively minimal and only lists each lexical stem in orthographic form and its meaning. This is because we do not always have access to forms with stems. For pronouns, "no\_stem" is indicated in the lexeme column in the forms file and verb forms without a stem are labeled "abstract\_entry". These are also listed in the lexemes file (for validation purposes).
* To facilitate comparison across PMST data sets, each file has an additional column with a language identifier. This means that files can be combined from different PMST sets without losing information.
* The morphs file contains a list of all morphs that appear in the data set (apart from the stem) in tokenized IPA. For each morph there is a list of all the forms and cells it appears in.
* The docs folder contains the data sheet with more extensive description of how the data was gathered.

## Additional information specific to Mizo

* Tone: Mizo has four contrastive lexical tones: high, low, falling, and rising. In this database, high tone is marked by an acute accent, low tone by a grave accent, falling tone by a caron, and rising tone by a circumflex. Two phonological tone processes are observed in the data: tonal polarity in the proclitics and rising tone sandhi in the context of 1PL, 2PL, and 3PL subject pronouns. In terms of tonal polarity, the proclitics in CV and V syllable structures (1SG, 2SG, 3SG) are assigned the opposite tone of the last constituent of the following stem. On the other hand, the proclitics with VC and CVC syllables (1PL, 2PL, 3PL) bear a rising tone when followed by a root with a low tone. However, due to rising tone sandhi, when these proclitics precede a root with a high tone, the rising tone is realized as a low.
* Mapping between database paradigm labels and Mizo descriptive labels (Chhangte 1993):
Database label = Language-specific descriptive label
fut.aff = future affirmative
fut.neg = future negative
nfut.aff = present and past affirmative
nfut.neg = present and past negative







## References

Auderset, Sandra, Hunter L. Brown, Jonathan Reich, Pascal Gerber, Muhammad Zakaria, and Linda Konnerth. 2026. “A Database of Person Marking in South-Central Trans-Himalayan”. *Journal of Open Humanities Data* 12 (1): 58. https://doi.org/10.5334/johd.505.



Chhangte, Lalnunthangi. 1993. Mizo syntax. PhD Thesis. Eugene: University of Oregon.

