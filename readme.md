## CRAG = Corrective rag

# the major draw back with traditional rag is that it blindliy trusts the retrived data. Say i have a document db of all ML and user queries question about llm. then the retrival might be of XGboost or random forest.The LLM will be forced to generate the document form the retrival(false answer shown as positive). In such cases the CRAG can be used. Th

# a new concept of retrival evaluater that retrives the documnet and checks the document retived

# there might be 3 cases. Document is either relevent, or not relevent or indesisive.

# if found then found

# if not found then tools might be called like web search.

# if mixed and not sure or half info both function of rag and tools combined action will be performed
