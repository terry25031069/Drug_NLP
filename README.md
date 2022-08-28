#model load and use

model = Doc2Vec.load("model.bin")
vector = model.infer_vector([list of string])

# Law NLP is on github!