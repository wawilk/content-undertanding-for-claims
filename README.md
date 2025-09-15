# content-understanding-for-claims
## Medical claim form submissions are typically made up of several different types of supporting documents all bundled into a single PDF file.

### The challenges:
1. ✅ The first is to split the documents out of the bundle.  
2. ✅ Then determine the document type of each document in the bundle.  
1. ✅ Finally extract the required fields from each document based on its type.  

### How Content Understanding (CU) solves these challenges
- ✅ CU has built-in mechanism to logically split the  the document (or pages) from the bundle based on your defined document types.
- ✅ You can define a schema for each document type detailing which fields you want to extract.  
- ✅ For each field in the schema, you specify if you want the value extracted using OCR or if you want CU to use an LLM to generate the value based on some criteria you supply.  
