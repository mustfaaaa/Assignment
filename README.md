 <h2>1️⃣ Document Class</h2>
    <p>
        The Document class holds basic details about a document. It has two fields: <strong>name</strong> and <strong>content</strong>.
    </p>
    <h2>2️⃣ Feedback Class</h2>
    <p>
        This class lets students provide feedback. Feedback can be created directly with a message and name or interactively by typing a message during runtime.
    </p>
    <h2>3️⃣ Project Class</h2>
    <p>
        Helps students start a new project by entering a <strong>title</strong> and <strong>description</strong>. It shows a success message with project details after creation.
    </p>
    <h2>4️⃣ StudentClass</h2>
    <p>
        Represents a student with an ID, name, and password. It supports <strong>login</strong> and <strong>logout</strong> with printed messages for confirmation.
    </p>

  <h2>5️⃣ StudentStorage</h2>
    <p>
        Saves student data to a file named <strong>students.txt</strong> and can load the list of students from that file. Each student's info is saved on a new line.
    </p>

  <h2>✅ How to Run This Java Project</h2>
    <ol>
        <li>Make sure Java is installed on your system (check using <code>java -version</code>).</li>
        <li>Save each Java class in the <strong>student</strong> package inside separate <code>.java</code> files (e.g., <code>Document.java</code>, <code>Feedback.java</code>, etc.).</li>
        <li>Open your terminal and navigate to the folder where your files are saved.</li>
        <li>Compile the code using: <code>javac student/*.java</code></li>
        <li>Create a <code>Main.java</code> file with a <code>main</code> method to test your classes.</li>
        <li>Run the program using: <code>java student.Main</code></li>
    </ol>
    <p><strong>Tip:</strong> You can also test each class by adding <code>main</code> methods temporarily in the classes themselves.</p>
