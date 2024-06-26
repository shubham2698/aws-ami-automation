<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body style="font-family: Arial, sans-serif; line-height: 1.6; padding: 20px; max-width: 800px; margin: 0 auto;">
    <h1 style="margin-top: 30px;">README</h1>
    <p style="margin-top: 30px;">This README provides information about the project.</p>
    <h2 style="margin-top: 30px;">Automation for AWS AMI Creation</h2>
    <p>Automating the creation of AWS AMIs involves the following steps:</p>
    <ol>
        <li>Get a list of all instances.</li>
        <li>Identify instances based on certain conditions (e.g., tag == your_tag).</li>
        <li>Create an AMI using CLI commands for the identified instances.</li>
    </ol>
    <h2 style="margin-top: 30px;">Input File</h2>
    <p>The input file is separated by blank spaces and includes the following fields:</p>
    <ul>
        <li style="background-color: #f4f4f4; padding: 5px; border-radius: 4px; font-family: Courier, monospace;">f1: AWS region</li>
        <li style="background-color: #f4f4f4; padding: 5px; border-radius: 4px; font-family: Courier, monospace;">f2: AWS profile</li>
        <li style="background-color: #f4f4f4; padding: 5px; border-radius: 4px; font-family: Courier, monospace;">f3: Project name tag</li>
    </ul>
    <h2 style="margin-top: 30px;">Output</h2>
    <p>The script generates a report containing the following information:</p>
    <ul>
        <li>Instance ID</li>
        <li>Instance name</li>
        <li>AMI ID</li>
    </ul>
    <h2 style="margin-top: 30px;">Usage</h2>
    <p>To execute the script, follow these steps:</p>
    <pre><code>./your_script.sh</code></pre>
    <h2 style="margin-top: 30px;">Contributing</h2>
    <p>If you'd like to contribute to this project, follow these steps:</p>
    <ol>
        <li>Fork the repository</li>
        <li>Create a new branch: <code>git checkout -b feature</code></li>
        <li>Make your changes</li>
        <li>Commit your changes: <code>git commit -am 'Add feature'</code></li>
        <li>Push to the branch: <code>git push origin feature</code></li>
        <li>Submit a pull request</li>
    </ol>
    <h2 style="margin-top: 30px;">License</h2>
    <p>This project is licensed under the MIT License.</p>
</body>
</html>
