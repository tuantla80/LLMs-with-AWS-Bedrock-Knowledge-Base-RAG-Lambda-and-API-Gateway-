LLMs with AWS Bedrock Knowledge Base, RAG (Retrieval Augmented Generation), Lambda and API Gateway 
#### 1. Data source  
- S3 bucket: to store data such as pdf files
#### 2. AWS Bedrock Knowledge Base: build vector store database  
- Data source
- Transform data: Chunking
- Create vector embeddings: Ex. Titan text, Cohere models
- Vector Store database
  - Amazon OpenSearch (recommended by AWS)
  - Amazon Aurora Postgresql
  - Pinecone
  - Redis Enterprise Cloud     
#### 3. AWS Lambda function  
- IAM role
- RetrieveAndGenerate API
- Model arn
#### 4. AWS API Gateway  
- Create REST API
#### 5. Integrate the whole system with AWS Lambda and API Gateway
  
