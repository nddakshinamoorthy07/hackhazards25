![image](https://github.com/user-attachments/assets/c385ab51-21c1-49a1-aec3-1d27df8ad342)![github-submission-banner](https://github.com/user-attachments/assets/a1493b84-e4e2-456e-a791-ce35ee2bcf2f)

# 🚀 Project Title

**MathMentor**

## 📌 Problem Statement

![image](https://github.com/user-attachments/assets/1720ff40-b081-48b9-9231-07e05ed56a2e)


## 🎯 Objective
**Problem Statement:**

Many students face challenges in solving math problems due to limited access to personalized tutoring and difficulties in interpreting complex problem statements. Traditional learning methods may not cater to diverse learning styles, leading to decreased engagement and understanding.

**Target Audience:**

- Students seeking personalized assistance in mathematics.
- Educators looking for tools to supplement teaching.
- Parents aiming to support their children's learning at home.

**Real-World Use Case:**

Consider a student struggling with a math problem in their textbook. Instead of waiting for the next class or seeking external help, they can:

1. **Voice Input:** Speak the problem aloud, and the system transcribes and processes it.
2. **Image Input:** Take a picture of the problem, and the system extracts the text using OCR.
3. **Solution Generation:** The extracted problem is sent to the Groq API, which returns a step-by-step solution.
4. **Feedback:** The student receives immediate feedback, enhancing understanding and retention.

**Value Provided:**

- **Immediate Assistance:** Reduces the waiting time for help, allowing continuous learning.
- **Personalized Learning:** Caters to individual learning styles through multimodal inputs.
- **Enhanced Engagement:** Interactive methods increase student interest and motivation.
- **Resource Accessibility:** Provides a readily available tool for students without access to personal tutors.

By integrating voice and image inputs with the Groq API, this educational tutor offers an innovative solution to common learning challenges in mathematics, promoting a more inclusive and effective learning environment. 

## 🧠 Team & Approach

### Team Name:  
CODX

### Team Members:  
- Name 1 DAKSHINA MOORTHY N D 
- Name 2  VIGNESH
- Name 3 DEEPAK
- Name 4 KIRTHICK

### Your Approach:  
Certainly! Here's a comprehensive overview of our approach to developing the Groq-powered educational tutor:

---

## 🎯 **Our Approach**

### **Why We Chose This Problem**

We aimed to create an educational tool that leverages advanced technologies to assist students in solving math problems. By integrating voice and image inputs, we sought to make math learning more interactive and accessible, especially for students who benefit from multimodal learning experiences.

### **Key Challenges Addressed**

1. **Multimodal Input Integration**: Combining voice and image inputs required seamless integration of speech recognition and optical character recognition (OCR) technologies.

2. **Real-time Feedback**: Ensuring that the system provides instant and accurate feedback necessitated efficient processing and response generation.

3. **User-Friendly Interface**: Designing an intuitive interface that allows users to easily input problems and receive solutions was crucial for user adoption.

### **Pivots, Brainstorms, and Breakthroughs**

- **Pivot to Groq API**: Initially, we considered using traditional machine learning models for problem-solving. However, we pivoted to using the Groq API, which provided more accurate and context-aware solutions.

- **Brainstorming Input Methods**: We brainstormed various input methods and settled on voice and image inputs to cater to different user preferences and situations.

- **Breakthrough in Integration**: Successfully integrating speech recognition, OCR, and the Groq API into a cohesive system was a significant breakthrough, enabling the tool to function effectively.

---

This approach allowed us to develop a robust educational tutor that provides instant feedback on math problems through voice and image inputs, enhancing the learning experience for students. 

## 🛠️ Tech Stack
Certainly! Here's a comprehensive overview of the core technologies utilized in the development of the **MathMentor** project:

---

### **Frontend:**

- **Framework:** React.js  
  Chosen for its component-based architecture, facilitating the creation of dynamic and responsive user interfaces.

- **Styling:** Tailwind CSS  
  Employed for its utility-first approach, enabling rapid UI development with a consistent design system.

- **Voice Input Integration:** Web Speech API  
  Utilized to capture and transcribe user-spoken math problems directly within the browser.

- **Image Input Integration:** HTML5 File Input & Webcam Access  
  Implemented to allow users to upload images or capture photos of handwritten or printed math problems.

---

### **Backend:**

- **Framework:** Node.js with Express.js  
  Selected for its non-blocking, event-driven architecture, suitable for handling multiple simultaneous requests efficiently.

- **OCR Processing:** Tesseract.js  
  Integrated to perform optical character recognition on uploaded images, extracting textual math problems for processing.

- **Voice Transcription:** Google Cloud Speech-to-Text API  
  Leveraged to convert audio inputs into text, ensuring accurate transcription of spoken math problems.

- **Math Problem Solving:** Groq API  
  Employed to analyze and solve extracted math problems, providing step-by-step solutions and explanations.

---

### **Database:**

- **Database System:** MongoDB  
  Chosen for its flexibility in handling unstructured data, storing user interactions, problem histories, and solution logs.

---

### **APIs:**

- **Groq API:** For processing and solving math problems.
- **Google Cloud Speech-to-Text API:** For transcribing spoken inputs.
- **Tesseract.js:** For extracting text from images.

---

### **Hosting:**

- **Frontend Hosting:** Netlify  
  Selected for its seamless integration with Git repositories and continuous deployment capabilities.

- **Backend Hosting:** Heroku  
  Utilized for its simplicity in deploying Node.js applications and managing environment variables.

- **Database Hosting:** MongoDB Atlas  
  Chosen for its managed database services, offering scalability and security features.

---

This technology stack ensures a responsive, efficient, and user-friendly experience for students seeking instant feedback on math problems through voice and image inputs. 

### Sponsor Technologies Used (if any):
- [✅] **Groq:** _How you used Groq_  
- [ ] **Monad:** _Your blockchain implementation_  
- [ ] **Fluvio:** _Real-time data handling_  
- [ ] **Base:** _AgentKit / OnchainKit / Smart Wallet usage_  
- [ ] **Screenpipe:** _Screen-based analytics or workflows_  
- [ ] **Stellar:** _Payments, identity, or token usage_
*(Mark with ✅ if completed)*
---

## ✨ Key Features


---

### ✅ **1. Voice-Enabled Math Problem Solving**

MathMentor allows users to verbally state math problems, which are transcribed using speech recognition technology. This feature caters to users who prefer auditory learning or have difficulties with typing.

*Example:* A student says, "What is the derivative of x squared?" and receives an immediate, step-by-step solution.

---

### ✅ **2. Image-Based Problem Recognition**

Users can capture or upload images of handwritten or printed math problems. MathMentor employs Optical Character Recognition (OCR) to extract the text and process the problem.

*Example:* A student takes a photo of a textbook problem, and MathMentor provides a detailed solution.

---

### ✅ **3. Real-Time, Step-by-Step Solutions**

Leveraging the Groq API, MathMentor delivers instantaneous, detailed solutions to math problems. The system breaks down each step, enhancing comprehension and learning.

*Example:* For an integral calculus problem, MathMentor outlines each integration step, explaining the rationale behind them.

---

### ✅ **4. Interactive Conversational Interface**

MathMentor features a chat-based interface, allowing users to engage in a dialogue with the tutor. Users can ask follow-up questions, request clarifications, or explore related problems, fostering an interactive learning environment.

*Example:* After solving a problem, a student asks, "Can you explain why we used this method?" and receives a tailored explanation.

---

These features collectively make MathMentor a versatile and accessible tool for students seeking assistance with math problems, accommodating various learning preferences and promoting a deeper understanding of mathematical concepts. 

---

## 📽️ Demo & Deliverables

- **Demo Video Link:** [Paste YouTube or Loom link here]  
- **Pitch Deck / PPT Link:** [Paste Google Slides / PDF link here]  

---

## ✅ Tasks & Bonus Checklist

- [✅] **All members of the team completed the mandatory task - Followed at least 2 of our social channels and filled the form** (Details in Participant Manual)  
- [✅] **All members of the team completed Bonus Task 1 - Sharing of Badges and filled the form (2 points)**  (Details in Participant Manual)
- [✅] **All members of the team completed Bonus Task 2 - Signing up for Sprint.dev and filled the form (3 points)**  (Details in Participant Manual)

*(Mark with ✅ if completed)*

---

## 🧪 How to Run the Project
Certainly! Here's a comprehensive guide to setting up and running the **MathMentor** project, which provides instant feedback on math problems through voice and image inputs using the Groq API.

---

## 🧪 How to Run the Project

### ✅ Requirements

- **Programming Languages & Tools:**
  -[Node.js](https://nodejs.org/) (v18 or higher
  -[Python](https://www.python.org/) (v3.8 or higher
  -[Docker](https://www.docker.com/) (optional, for containerized deployment

- **APIs & Services:**
  -[Groq API](https://groq.com/
  -[Google Cloud Speech-to-Text API](https://cloud.google.com/speech-to-text
  -[MongoDB Atlas](https://www.mongodb.com/cloud/atlas) (for database management

- **Environment Configuration:**
  -`.env` file to store API keys and configuration variables securely

---

### 📁 Project Structure

```
MathMentor/
├── backend/               # Node.js backend
│   ├── server.js
│   ├── routes/
│   └── .env
├── frontend/              # React.js frontend
│   ├── src/
│   └── .env
├── python_modules/        # Python scripts for OCR and processing
│   ├── ocr_processor.py
│   └── .env
├── docker-compose.yml     # Docker configuration (optional)
└── README.md
``


---

### ⚙️ Setup Instructions

#### 1. **Clone the Repository**

```bash
git clone https://github.com/yourusername/MathMentor.git
cd MathMentor
``


#### 2. **Configure Environment Variables**

Create a `.env` file in each of the `backend/`, `frontend/`, and `python_modules/` directories with the following structure:

```env
# Common variables
GROQ_API_KEY=your_groq_api_key
GOOGLE_CLOUD_API_KEY=your_google_cloud_api_key
MONGODB_URI=your_mongodb_connection_string

# Backend specific
PORT=5000

# Frontend specific
REACT_APP_BACKEND_URL=http://localhost:5000
``


> **Note:* Ensure that `.env` files are added to `.gitignore` to prevent sensitive information from being committed to version contro.

#### 3. **Install Dependencies**

- **Backend (Node.js):**

 
```bash
  cd backend
  npm install
  ``


- **Frontend (React.js):**

 
```bash
  cd ../frontend
  npm install
  ``


- **Python Modules:**

 
```bash
  cd ../python_modules
  pip install -r requirements.txt
  ``


#### 4. **Run the Application**

- **Backend Server:**

 
```bash
  cd backend
  npm start
  ``


- **Frontend Application:**

 
```bash
  cd ../frontend
  npm start
  ``


- **Python OCR Processor:**

 
```bash
  cd ../python_modules
  python ocr_processor.py
  ``


> **Optional:* To run the entire application using Docke:

```bash
docker-compose up --build
``


---

### 🛠️ Additional Configuration

- **Google Cloud Speech-to-Text API:**
 - Enable the API in your [Google Cloud Console](https://console.cloud.google.com).
 - Create a service account and download the JSON key fie.
 - Set the `GOOGLE_APPLICATION_CREDENTIALS` environment variable to point to this key fie:

    ```bash
    export GOOGLE_APPLICATION_CREDENTIALS="/path/to/your/keyfile.json"
    ```

- **MongoDB Atlas:**
 - Set up a cluster and obtain the connection strig.
 - Replace `your_mongodb_connection_string` in the `.env` files with this strig.

---

### ✅ Verification

After completing the setup:

. Navigate to `http://localhost:3000` in your browsr.
. Test the voice input feature by speaking a math problm.
. Test the image input feature by uploading a picture of a math problm.
. Verify that the application provides instant feedback with step-by-step solutios.

--

By following these steps, you can successfully set up and run the MathMentor project, providing users with an interactive platform to solve math problems using voice and image inpus. 

### Local Setup:
```bash
# Clone the repo
git clone https://github.com/your-team/project-name

# Install dependencies
cd project-name
npm install

# Start development server
npm run dev
```

Provide any backend/frontend split or environment setup notes here.

---

## 🧬 Future Scope
Certainly! Building upon the current capabilities of **MathMentor**, here are potential avenues for future development to enhance its effectiveness and accessibility:

---

## 🧬 Future Scope

### 📈 Enhanced Integrations

- **Learning Management Systems (LMS) Integration** Incorporate MathMentor into popular LMS platforms like Moodle or Canvas to streamline assignment submissions and feedbac.

- **Educational Tools Compatibility** Ensure seamless interaction with tools such as Google Classroom and Microsoft Teams to facilitate collaborative learning environment.

### 🛡️ Advanced Security Measures

- **Data Privacy Compliance*: Implement robust data protection protocols to comply with regulations like GDPR and FERPA, ensuring user data is handled responsiby.

- **Secure Authentication*: Adopt multi-factor authentication and encryption standards to protect user accounts and sensitive informatin.

### 🌐 Localization and Accessibility

- **Multilingual Support*: Expand language options to cater to a diverse user base, making the platform accessible to non-English speakrs.

- **Accessibility Features*: Incorporate features like screen reader compatibility and adjustable text sizes to support users with disabilites.

### 🤖 Adaptive Learning Capabilities

- **Personalized Learning Path**: Utilize AI to analyze user performance and tailor learning experiences to individual needs and progess.

- **Real-Time Feedbac**: Enhance the system's ability to provide immediate, context-aware feedback to guide learners effectiely.

### 🎓 Educational Content Expansion

- **Curriculum Alignmet**: Align MathMentor's content with various educational standards to ensure relevance across different educational sytems.

- **Subject Diversificatin**: Extend support beyond mathematics to include other STEM subjects, broadening the platform's utlity.
---

By pursuing these enhancements, MathMentor can evolve into a more comprehensive educational tool, offering personalized, secure, and accessible learning experiences to a global audence. 
## 📎 Resources / Credits
Certainly! Here's a comprehensive list of resources and acknowledgments for the **MathMentor** project:

---

## 📎 Resources / Credits

### 🔌 APIs and Services Used

- **Groq API** Utilized for processing and solving math problems with high-speed inference and low latenc.  
  Documentation: linkturn0search0

- **Google Cloud Speech-to-Text API** Employed to transcribe spoken math problems into text, supporting multiple languages and real-time transcriptio.  
  Documentation: linkturn0search1

### 📚 Open Source Libraries and Tools

- **Tesseract.js*: A pure JavaScript OCR engine used to extract text from images of handwritten or printed math probles.  
  Documentation: linkturn0search2

- **React.js*: A JavaScript library for building user interfaces, used to develop the frontend of MathMentr.  
  Documentation: linkturn0search3

- **Node.js*: A JavaScript runtime environment that executes server-side code, forming the backbone of MathMentor's backed.  
  Documentation: linkturn0search4

- **Express.js*: A minimal and flexible Node.js web application framework used to build the backend AI.  
  Documentation: linkturn0search5

- **MongoDB Atlas*: A cloud-based NoSQL database service used to store user data, problem histories, and solution los.  
  Documentation: linkturn0search6

### 🙌 Acknowledgements

- **OpenAI*: For providing the foundational language models and APIs that inspired the development of MathMenor.

- **Community Contributors*: Thanks to the developers and contributors of the open-source libraries and tools that made this project possile.

--

These resources and tools collectively enabled the creation of MathMentor, providing users with an interactive platform to solve math problems using voice and image inpts. 

## 🏁 Final Words
Absolutely! Reflecting on the journey of developing **MathMentor**—a Groq-powered educational tutor that provides instant feedback on math problems through voice and image inputs—has been both challenging and rewarding. Here's a glimpse into our hackathon experience:

---

## 🛠️ Challenges Faced

- **Integrating Diverse Technologies**:Combining Groq's high-performance inference capabilities with Google Cloud's Speech-to-Text API and Tesseract.js for OCR posed significant technical challenges. Ensuring seamless communication between these components required meticulous planning and testing

- **Real-Time Processing Demands**:Achieving low-latency responses for both voice and image inputs necessitated optimizing each module for performance, ensuring that users received instant feedback without noticeable delays

- **User Experience Design**:Creating an intuitive interface that accommodates both voice and image inputs, while maintaining clarity and simplicity, demanded thoughtful design and iterative user testing

---

## 📚 Key Learnings

- **Importance of Modular Architecture** Designing the system with modular components allowed for easier troubleshooting and future scalability. Each module—voice recognition, image processing, and mathematical inference—could be developed and optimized independentl.

- **User-Centric Development** Prioritizing user feedback during the development process led to a more intuitive and accessible application. Understanding the diverse needs of learners helped in tailoring features that enhance the learning experienc.

- **Collaborative Problem Solving** Working closely with team members from different technical backgrounds fostered a collaborative environment where innovative solutions emerged through collective brainstorming and knowledge sharin.

---

## 🎉 Memorable Moments

- **First Successful Integration*: The moment when voice input was successfully transcribed and processed to generate a mathematical solution was a significant milestone, validating our approach and boosting team morae.

- **User Testing Feedback*: Observing users interact with MathMentor and receiving positive feedback about its ease of use and effectiveness reinforced the impact of our wok.

- **Team Celebrations*: Celebrating small victories, whether it was resolving a complex bug or implementing a new feature, strengthened team cohesion and made the journey enjoyabe.

---

## 🙌 Acknowledgments

- **Mentors and Advisors*: Their guidance and expertise were invaluable in navigating technical challenges and refining our approch.

- **User Testers*: The insights provided by early users helped in fine-tuning the application to better meet educational neds.

- **Collaborative Team*: The dedication and hard work of each team member were instrumental in bringing MathMentor to lfe.

--

Developing MathMentor was a journey of innovation, collaboration, and learning. It underscored the power of technology in transforming education and the importance of perseverance in overcoming challenes.

--- 
