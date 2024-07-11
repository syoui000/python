# Parse WoS .txt files in Python
- Parse WoS full records and references (.txt files), in batches, and save to .json.
- It is a simple function, which is to put the full records and references (.txt files) exported in WoS into a folder, which includes such like '1-500.txt', '501-1000.txt', '1001-1500.txt', and then directly use this folder location to read and parse it into a dict, also it can be a single File, each field is a key and the content is a value.
- There are 2 functions in .ipynb, one is parse a single .txt file, and the other one is parse multiple .txt files in one fold. 
