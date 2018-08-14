0. Install miniconda, with python2.7 environment
1. Enter the dev notebook with the following commands:
   source actiave py2.7
   jupyter notebook
2. Install protoc, refer to https://github.com/google/protobuf/releases
3. Generate python stub of proto
   $protoc --python_out=. chat.proto 
