Knowledge Access Chatbot: Project ECHO
Solution Name: Project ECHO AI Chatbot
Customer: Project ECHO
Overview
The Arizona State University Artificial Intelligence Cloud Innovation Center, powered by Amazon Web Services (AWS), collaborated with Project ECHO to develop an AI-powered knowledge access chatbot that simplifies how frontline healthcare workers, educators, and community leaders retrieve expert-approved information from ECHO’s training programs.
This initiative focused on transforming ECHO’s manual document-based content retrieval into an automated system that allows users to quickly search and apply knowledge in real time — even in low-connectivity environments. The AI assistant was built to parse training materials, protocols, and checklists across healthcare, education, and agriculture domains, providing instant, cited responses in a mobile-friendly chat interface. Powered by Amazon Bedrock and serverless AWS architecture, the solution enhances learning retention, reduces knowledge gaps, and supports critical decision-making for field workers in underserved communities.
Problem
Project ECHO supports thousands of professionals through virtual training and mentorship programs worldwide. However, frontline workers often struggled to recall specialized protocols and apply training content in the field due to limited internet access, heavy workloads, and fragmented resources.
Traditional training materials were distributed through multiple channels and formats, making it difficult to access timely, expert-verified information. Project ECHO needed a centralized and intuitive solution that could deliver accurate answers instantly without compromising content authenticity or usability in low-bandwidth regions.
Student Spotlight
The AI CIC is powered by ASU student workers. The following students collaborated with AWS mentors to design and develop this open-source solution for Project ECHO.

Sahjapreet Kharisa - Full stack Developer
Apoorv Singh - Full stack Developer
Jenny Nguyen -  UI/UX Designer

Client Quote (Placeholder)
Partnering with the Cloud Innovation Center has been a masterclass in purposeful innovation. Together, we built a production-ready RAG system for our first S3 Vector Store deployment, achieving 94% accuracy and 90% cost reduction. This collaborative approach accelerates our Digital Public Good journey, enabling frontline workers across health, agriculture, and education to access trusted expertise instantly, sustainably, and at a global scale.
Ankit Nakar, Deputy General Manager Product and Innovation, ECHO India
PROJECT ECHO please provide a quote about your experience working with the Cloud Innovation Center, what you learned through the process, how the solution developed meets your needs, etc… See examples on the CIC website: https://smartchallenges.asu.edu/solutions

Approach
The ASU CIC team developed a mobile-first AI chatbot that enables users to search, retrieve, and interact with expert-validated Project ECHO content in real time. The system integrates data from training materials, protocols, and reference guides into a secure knowledge base accessible through a chat interface optimized for reduced feature devices and limited connectivity.
The solution was built using a scalable serverless architecture featuring key AWS services:
●	Amazon Bedrock (Nova Lite) – Generates context-aware responses using ECHO’s approved content.
●	Amazon Bedrock Titan Multimodal Embeddings and Data Automation – Processes text and multimedia training files into searchable vector embeddings.
●	Amazon API Gateway & AWS Lambda – Enable secure, event-driven communication between the frontend and backend.
●	Amazon DynamoDB – Stores user feedback and session metadata for continuous improvement.
●	Amazon S3 – Hosts the document repository and vector store for the knowledge base.
●	AWS Amplify – Supports the React-based frontend and automated deployment pipeline.
●	Amazon EKS Fargate & CloudWatch – Manage containerized tasks and provide system observability.
The chatbot delivers fast, cited answers drawn from vetted materials and features an offline-friendly design that ensures continued access for users in low-connectivity areas.

Industry Impact 
This project demonstrates how AI and cloud technologies can bridge knowledge gaps for frontline workers worldwide by delivering accurate, contextual information instantly to support critical field decisions. It improves retention and application of training content across Project ECHO’s global programs while reducing dependence on manual document searches and offline reference materials. Additionally, the chatbot expands accessibility for healthcare and education professionals working in remote regions, ensuring that vital, expert-approved knowledge is always within reach even in low-connectivity environments.

Wider Application
The Project ECHO chatbot is redefining how organizations access and apply expert knowledge at scale. Beyond Project ECHO’s global training network, this AI-powered framework has broad potential across multiple sectors. In healthcare and public health, it can serve as a secure digital assistant for clinicians and frontline workers who need instant access to treatment protocols and reference materials. Educational institutions can adapt the chatbot to deliver interactive, on-demand learning experiences for students and teachers, while government agencies and NGOs can leverage its multilingual capabilities to train and inform diverse communities in real time.
By combining AI-driven knowledge retrieval with a cloud-native, mobile-first design, this solution has the potential to transform how institutions deliver information—making it more accessible, consistent, and impactful across industries.
Supporting Artifacts
●	Solution Architecture Diagram 
●	Chatbot Demo
●	Cost Analysis Document
Drive Document
Next Steps
With 20+ years of trusted knowledge, our next step is to bring ethical Agentic-RAG to everyone, not just as a tool, but as a personal guide. Built on vetted expertise and local languages, it will empower frontline workers and teams to learn, make informed decisions, and act with confidence. This journey is shaping our AI leadership and opening new possibilities with AWS to serve the world at scale.

Project ECHO team  please provide a short paragraph about your anticipated next steps from this project … See examples on the CIC website: https://smartchallenges.asu.edu/solutions
About Us: ASU Artificial Intelligence Cloud Innovation Center (AI CIC)
The ASU Artificial Intelligence Cloud Innovation Center (AI CIC), powered by AWS is a no-cost design thinking and rapid prototyping shop dedicated to bridging the digital divide and driving innovation in the nonprofit, healthcare, education, and government sectors.
Our expert team harnesses Amazon’s pioneering approach to dive deep into high-priority pain points, meticulously define challenges, and craft strategic solutions. We collaborate with AWS solutions architects and talented student workers to develop tailored prototypes showcasing how advanced technology can tackle a wide range of operational and mission-related challenges. 
Discover how we use technology to drive innovation. Visit our website at ASU AI CIC or contact us directly at ai-cic@amazon.com.
Photos
(Insert demo screenshots, student headshots, and architecture visuals here before publication, included demo screenshots in the above blue link)
