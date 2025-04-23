# ExamGenerator
## Object
The goal of this project is to let user generate exams for students with:
1. specified field, like medical, Math, physics, science etc,
2. specified level, like beginner, middle, and senior,
3. specified number of problems,

   For example, create an MCAT exam, with 10 beginner multiple choice questions, covering basics of science, biology, and math.
The system will consists of multiple parts:
1.  ETL, for example a python program, scrap web for existing questions, (or other sources). Parse the questions, find the knowledge elements,
   Save to database (vector DB?)
3. embedding.. RAG, local training, using existing LLM?
4. Create Model
5. Expose APIs.
6. Some minimal Web UI

