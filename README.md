An Image captioning web application combines the power of React.js for front-end, Flask and Node.js for back-end, utilizing the MERN stack. Users can upload images and instantly receive automatic captions. Authenticated users have access to extra features like translating captions and text-to-speech functionality.

HOME PAGE

<img width="1139" height="624" alt="image" src="https://github.com/user-attachments/assets/4c1e5cd5-15b4-406d-93ae-8ecfadfc6abf" />

Upload page (Guest)
<img width="1135" height="636" alt="image" src="https://github.com/user-attachments/assets/5f0d83b1-daf2-4386-a54d-22338973e019" />

Upload page (Logged In)
<img width="1128" height="631" alt="image" src="https://github.com/user-attachments/assets/daa06960-0dce-47d4-98af-d05e06251f3d" />

Result Page
The users can get the generated captions on this page. To get the access to the features of text-to-speech and caption translation they need to get authenticate by logging in. The link is provided below the generated caption which get navigated to the login page.
<img width="1139" height="645" alt="image" src="https://github.com/user-attachments/assets/5d13e2dd-17d0-4f04-a49b-98a7e8056601" />

.

After successfully Logging in, the user can see the text-to-speech and translation feature as shown in the image below. For text-to-speech, react-speech-kit library is used. For translation, Translation Api provided by RapidApi has been used. User can chooses its preferred language from the dropdown to translate caption.
<img width="1128" height="642" alt="image" src="https://github.com/user-attachments/assets/abc1676c-5a0a-4886-9dae-72963d87ea13" />
<img width="1123" height="630" alt="image" src="https://github.com/user-attachments/assets/904902c8-9bfc-4852-b3a6-fcb9540561ff" />
<img width="1129" height="635" alt="image" src="https://github.com/user-attachments/assets/4dfb2d75-c627-4e47-9798-468d9a599fa9" />
<img width="1124" height="651" alt="image" src="https://github.com/user-attachments/assets/0d33bfb0-86f0-48b5-b9ec-428c2935d6b9" />

Login Page
<img width="1151" height="653" alt="image" src="https://github.com/user-attachments/assets/4fd9f2c4-d264-493f-82f1-053538ffc3ef" />

Signup page

<img width="1124" height="645" alt="image" src="https://github.com/user-attachments/assets/a15a814e-8902-41a4-a125-4b99618f5797" />



### 1. Frontend (React)

1. Open a terminal (**Terminal-1**)
2. Navigate to the frontend directory:

   ```bash
   cd frontend
     ```
3. Install dependencies:

   ```bash
   npm install
   ```
4. Start the React development server:

   ```bash
   npm start
   ```

---

###  2. Backend (Flask – Image Captioning API)

1. Open another terminal (**Terminal-2**)
2. Navigate to the server directory:

   ```bash
   cd server
   ```
3. Start the Flask server:

   ```bash
   python app.py
   ```

---

###  3. MongoDB Setup (Optional – For Login / Signup / Extra Features)

> Required only if you want to use **login/signup, text-to-speech, or translation features**.

1. Open a new terminal (**Terminal-3**)

2. Navigate to the backend directory:

   ```bash
   cd backend
   ```

3. Start the Node.js server:

   ```bash
   node app.js
   ```

4. Open another terminal (**Terminal-4**) and start MongoDB:

   ```bash
   mongod
   ```

5. (Optional) Open Mongo shell (**Terminal-5**):

   ```bash
   mongo
   ```

---

### 4. Access the Application

Open your web browser and visit:

```
http://localhost:3000
```

---
