# matching
### Matching Mentors Mentees
#### [sentence-transformers/all-MiniLM-L6-v2](https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2)
"This is a sentence-transformers model: It maps sentences & paragraphs to a 384 dimensional dense vector space and can be used for tasks like clustering or semantic search."

#### About
I've generated 2 example CSV files with 60 mentors and 375 mentees.
Mentors and mentees have a "name_id" and "keywords"
I've used a sentence transformer to extract features and do the pairing.
In this example, the all-MiniLM-L6-v2 transformers looks for semantic similarities and evaluates "keywords". It could also extract features from longer sentences, so it could evaluate sentence similarities for "statements" or "descriptions" from mentors and mentees, eventually. 
