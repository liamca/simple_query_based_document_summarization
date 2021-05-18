# Simple Query Based Document Summarization

Very simple example of how to do query based documentation summarization.

This works by leveraging Question-Answer Retrieval as found in [Sentence Transformers](https://www.sbert.net/docs/pretrained_models.html#question-answer-retrieval-msmarco) to take a query and find the passages or sentences that best represent the answer to this query within the document.

Tested using Python 3.7 and sentence transformers:
pip install sentence-transformers
