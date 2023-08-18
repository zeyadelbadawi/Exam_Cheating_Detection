<!DOCTYPE html>
<html>

<head>
    <title>Exam Cheating Detection System</title>
</head>

<body>

    <h1>Exam Cheating Detection System</h1>

    <h2>Description</h2>
    <p>The Exam Cheating Detection System is a Python-based application designed to enhance the integrity of online exams. It employs face recognition technology to verify the identity of students and monitors their behavior during the exam to detect potential cheating attempts.</p>

    <h2>Features</h2>
    <ol>
        <li><strong>Login:</strong> Students are required to log in to the system using their credentials.</li>
        <li><strong>Face Recognition:</strong> The system uses face recognition to match the student's face with their database picture for identity verification.</li>
        <li><strong>Exam Start:</strong> Once the student's identity is confirmed, the exam begins.</li>
        <li><strong>Gaze Detection:</strong> The system monitors the student's gaze and alerts if they look away for an extended period (e.g., 3 seconds or more).</li>
        <li><strong>Warning System:</strong> If a student receives three warnings for suspicious behavior (e.g., looking away excessively), the exam is terminated.</li>
        <li><strong>Emotion Analysis:</strong> The system analyzes the student's facial expressions to determine emotions (happy, sad, afraid) during the exam.</li>
    </ol>

    <h2>Prerequisites</h2>
    <ul>
        <li>Python 3.x</li>
        <li>Required libraries (specified in <code>requirements.txt</code>)</li>
    </ul>



    <h2>Configuration</h2>
    <ul>
        <li>Configure system settings in <code>config.py</code>.</li>
        <li>Update the student database in <code>student_database.csv</code>.</li>
    </ul>

    <h2>Contributing</h2>
    <p>Contributions are welcome! If you find any issues or want to add new features, please open an issue or submit a pull request.</p>

    <h2>Credits</h2>
    <p>[Your Name]</p>

    <h2>License</h2>
    <p>This project is licensed under the <a href="LICENSE">MIT License</a>.</p>

</body>

</html>
