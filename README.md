1. Put `EventStoryLine`, `CausalTM`, `EventCausalityData`, `SemEval`, and `FrameNet` datasets in the current directory. 
`EventStoryLine: https://github.com/cltl/EventStoryLine`
`EventCausalityData: https://cogcomp.seas.upenn.edu/page/resource_view/27`

2. Run `read_document.py` to build all intra-sentence examples for `EventStoryLine`.

3. Run `preprecess_*.py` to generate BERT-based examples for difference datasets and settings.'
- Also download word2vec file `https://drive.google.com/file/d/0B7XkCwpI5KDYNlNUTTlSS21pQmM/edit` and convert to txt

4. Run `train_mix.py` to train the model, with different settings.

