**Welcome to SemiColon!**

# Inspiration

Through our friend's experiences working at doctors' offices, we were reminded how deadly colon cancer can be—and how a single miss by a radiologist can change a life. We believe technology should reduce that risk, not add to it. We named the project Semicolon because we don’t want to stop at colon cancer; our goal is to expand to many cancers.

# What it does

Semicolon lets a user input clinical data about a colon tumor, upload a tumor scan, or use both together. The system predicts whether the tumor is malignant or benign, with the option to fuse modalities for higher confidence.

# How we built it

We built the backend with Python and FastAPI, using TensorFlow to train and test our computer-vision model and to serve predictions to the frontend. The UI is built with Vite + React and Tailwind CSS for a fast, clean user experience.

# Challenges we ran into

Time was our biggest constraint. Connecting the frontend to the backend reliably under hackathon pressure was tricky, and getting a model trained, tuned, and evaluated quickly required careful prioritization.

# Accomplishments that we’re proud of

We shipped a smooth, responsive frontend and successfully ran our computer-vision model on tumor images end-to-end. Seeing the full flow—from input to prediction—working was a major milestone.

# What we learned

We deepened our understanding of TensorFlow, improved our TypeScript/React skills, and learned how to stand up a lightweight FastAPI service to bridge ML and the web app.

What’s next for Semicolon

Next, we’ll implement the clinical-data ML component and fuse it with imaging for stronger predictions. We plan to benchmark our model against Gemini to compare accuracy and reliability. We’ll also complete the patient-to-doctor connection: matching users to nearby specialists in their specific cancer type and factoring in location, insurance, and other compatibility signals.

#Try it Out:

To run the backend, be in the project/backend and run:
    uvicorn main:app --reload --port 8000

To run the application, start the frontend by going to frontend: npm run dev
