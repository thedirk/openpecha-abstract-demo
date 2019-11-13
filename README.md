# openpoti-abstract-demo

## Terminology

**Etext** is a general term for any document that is read in digital form, and especially a document that is mainly text. For example, a computer based book of art with minimal text, or a set of photographs or scans of pages, would not usually be called an "e-text".

**Work** a single publication released at a point in time. For example, the Derge Kangyur, despite its 103 volumes, more than 1,000 texts, and hundreds of authors, is a single work.

**Text** is the main body of a book or other piece of writing, as distinct from other material such as notes, appendices, and illustrations. For eg, the སྤྱོད་འཇུག is a text.

**Volume** is a book forming part of a work or series. It can also be a single book or a bound collection of printed. sheets.

**Pecha** ( དཔེ་ཆ་) in Tibetan is a traditional Tibetan-style book with long, loose-leaf pages. In OpenPecha, it is the digital equivalent of a physical volume.

**Collection** is a group of volumes or texts. For eg, the kangyur is both collection of texts and volumes, while a prayer book is collection of texts in a single volume.

**Abstract Text** refers to a text regarded in terms of its content rather than its version, edition or physical form. For eg, the སྤྱོད་འཇུག in general is an abstract text, which exists in many expressions such as any printed edition, epub, text file  or even the སྤྱོད་འཇུག in the mind of a monk who knows it by heart.

**Expression** refers to any specific edition, publication or version of a text as opposed to its abstract text. For eg, the སྤྱོད་འཇུག found in the volume 106 of the derge Tengyur and the OpenPecha W1OP000001 are two expressions of the same text.

**Default Expression** is the digital version of a text which was selected to represent it by default. Usually the most authoritative and best proofread expression. For eg, the etext of the སྤྱོད་འཇུག found in the digital edition of the tengyur proofread by Esukhia was selected as the default expression of the སྤྱོད་འཇུག 

**Verbal Text** is the string of characters in a text that corresponds—as closely as is possible—to the message of the original work. Since it represents the communicative intent of the author(s), it does not contain formatting or illustrations or glossaries or other content specific to "being a book". Since it roughly aligns with what would be communicated orally, it's called the "verbal text". 

**Base Text** is the base layer or source text of an OpenPecha. It is the string of unicode characters in plain text format that is the best-possible representation of the verbal text—the main body or core message of the text. It does not include tools like tables of content or figures or formatting or decorative punctuation. However, it does include punctuation that stands for prosody. (Importantly, texts are "taken at their word" in the base text; just as listeners interpret and auto-correct speakers who mis-speak, error correction is an interpretation of the base text, and thus a separate layer). 

**Witness** in phylology, any published expression of a text.

**Edition** is a particular form or version of a published text.

**Publication** refers to any printed copy of a text.

## Example Potis Description
### potis/a.opf
- single volume
- 5 texts
- section titles not in base
- toc.yaml with section titles

### potis/b.opf
- single volume
- 5 texts
- preface, contents, apendix
- section titles + chapters in base
- toc.yaml

### potis/c.opf
- single volume
- 1 text # First Text
- section titles in base
- toc.yaml

### potis/d.opf
- volume 1/2
- 2.5 texts
- section titles in base
- toc.yaml

### potis/e.opf
- volume 2/2
- 2.5 texts
- section titles in base
- toc.yaml

### potis/f.opf
- single volume
- 1 text # First Text
- chapters in base  # 3 chapters, 1&2 different than b.opf
- toc.yaml

### potis/g.opf
- single volume
- 1 partial text # half of Second text
- chapters in base
- toc.yaml

### potis/h.opf
- single volume
- 1 text # Second text with many spelling differences
- chapters in base
- toc.yaml
