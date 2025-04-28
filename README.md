## GradeMate

### Abstract
This project aims to revolutionize exam grading by developing GradeMate, an AIpowered automated grading system for exam papers. It addresses the challenge of
manual, time-consuming, and inconsistent exam evaluation processes in educational
institutions. The motivation behind this work is to enhance grading efficiency,
fairness, and scalability.
We utilized NLP techniques, LLMs (Large Language Models), and RAG (RetrievalAugmented Generation) methodologies. The system architecture includes a
frontend dashboard, backend grading engine, and custom RAG pipelines.
Results show that GradeMate achieves high semantic grading accuracy compared to
manual grading, drastically reducing grading time and offering consistent
evaluation across different answer styles.
In conclusion, GradeMate successfully demonstrates the feasibility of AI-driven
descriptive exam evaluation and opens avenues for future work, such as expanding
support for subjective creativity assessment and multilingual grading.

### Objectives
- Develop an AI-powered platform for descriptive exam grading.
- Minimize human effort and grading time.
- Ensure grading fairness and consistency across exams.
- Integrate RAG pipelines to improve answer understanding.
- Provide an intuitive web-based dashboard for educators.

### Tech Stack
- Python, JavaScript, Django, Django Templating, SQL
- LangChain, Chroma, GroqCloud, RAG (Query Expansion, Reranking, Maximal
Marginal Relevance etc.)

### Workflow
- Upload key material and solved papers.
- Generate answers from knowledge base using reference material.
- Compare student answers semantically.
- Assign and display grades.

### System Architecture
![system architecture figure](https://github.com/safwanhamza/GradeMate/blob/main/assets/sys_arch.png)
More on System Architecture [here](https://github.com/safwanhamza/GradeMate/blob/main/docs/architecture.md).

### Design
App design and user journey is available [here.](https://www.figma.com/proto/uSEp5kuYOc9btq1ibraodO/GradeMate-UI%2FUX-Design?node-id=9-2&node-type=canvas&t=uGmNmkSIPeQ5EZkZ-0&scaling=scale-down&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=9%3A2)

### User Stories
User Stories are available [here.](https://github.com/safwanhamza/GradeMate/blob/main/docs/User_Stories.md)

### Documentation
Project Documentation is available [here.](https://github.com/safwanhamza/GradeMate/tree/main/docs)
