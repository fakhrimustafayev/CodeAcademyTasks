# EmailSender
This project demonstrates a simple C# application to send emails using Gmail's SMTP server. The application utilizes the System.Net.Mail and Scriban libraries to construct and send HTML-based email templates.

Features
Email Sending: Sends personalized HTML emails using a provided template.
Customizable Template: Easily customize the email template by modifying the HTML structure and content.
Prerequisites
.NET Core SDK: Ensure you have .NET Core SDK installed to compile and run the application.
Gmail Account: A Gmail account is required to send emails. Enable access for less secure apps or generate an app password for the sender's email.
Getting Started
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/EmailSenderExample.git
Open the solution in your preferred C# IDE.

Replace the following placeholders in Program.cs with your Gmail credentials:

csharp
Copy code
string senderEmail = "your-email@gmail.com"; // Gmail address
string senderPassword = "your-password"; // Gmail password
string receiverEmail = "recipient-email@example.com"; // Email address of the recipient
Run the application.

Follow the on-screen prompts to input the recipient's name and send the email.

Usage
The SendEmail() method in Program.cs is responsible for sending emails. Modify the GenerateEmailBody() method to customize the content of the email template.

Contributing
Contributions are welcome! If you'd like to improve this project, feel free to open a pull request. Please follow the contributing guidelines.

License
This project is licensed under the MIT License.

Acknowledgments
Scriban: Used for templating HTML content in emails.
Support
For any questions or issues, please open an issue or contact maintainer's name.
