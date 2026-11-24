<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tanya Gupta - Resume</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f4f6f9;
            color: #222;
            line-height: 1.5;
            padding: 20px;
        }
        .resume-container {
            max-width: 850px;
            margin: 0 auto;
            background: #ffffff;
            padding: 40px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.08);
            border-radius: 4px;
        }
        .header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 24px;
            border-bottom: 2px solid #e1e8f0;
            padding-bottom: 20px;
        }
        .header-text {
            flex: 1;
            text-align: center;
            padding-right: 20px;
        }
        .header-text h1 {
            font-size: 28px;
            color: #16325c;
            letter-spacing: 1px;
            margin-bottom: 6px;
        }
        .header-text .subtitle {
            font-size: 13px;
            font-weight: 700;
            color: #333;
            margin-bottom: 6px;
        }
        .header-text .contact-info {
            font-size: 13px;
            color: #444;
        }
        .header-text .contact-info a {
            color: #16325c;
            text-decoration: none;
        }
        .header-text .contact-info a:hover {
            text-decoration: underline;
        }
        .profile-photo {
            width: 110px;
            height: 130px;
            object-fit: cover;
            border: 1px solid #ccc;
            border-radius: 4px;
            background-color: #eee;
        }
        .section {
            margin-bottom: 20px;
        }
        .section-title {
            background-color: #e9eff7;
            color: #16325c;
            font-size: 14px;
            font-weight: 700;
            padding: 6px 12px;
            border: 1px solid #d0dceb;
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }
        .section-content {
            border: 1px solid #d0dceb;
            border-top: none;
            padding: 12px 16px;
            font-size: 13.5px;
        }
        .section-content p {
            margin-bottom: 6px;
        }
        .section-content p:last-child {
            margin-bottom: 0;
        }
        ul {
            list-style-type: disc;
            padding-left: 20px;
        }
        li {
            margin-bottom: 5px;
        }
        li:last-child {
            margin-bottom: 0;
        }
        .job-header {
            font-weight: 700;
            color: #16325c;
            margin-bottom: 8px;
        }
        .job-header span {
            font-weight: 400;
            color: #444;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            font-size: 13.5px;
        }
        th, td {
            border: 1px solid #d0dceb;
            padding: 8px 12px;
            text-align: left;
        }
        th {
            background-color: #f3f7fc;
            color: #16325c;
            font-weight: 700;
        }
        @media (max-width: 600px) {
            .resume-container {
                padding: 20px;
            }
            .header {
                flex-direction: column-reverse;
                gap: 15px;
            }
            .header-text {
                padding-right: 0;
            }
            table, th, td {
                font-size: 12px;
                padding: 6px;
            }
        }
        @media print {
            body {
                background: none;
                padding: 0;
            }
            .resume-container {
                box-shadow: none;
                padding: 0;
                max-width: 100%;
            }
        }
    </style>
</head>
<body>

    <div class="resume-container">
        <!-- Header Section -->
        <header class="header">
            <div class="header-text">
                <h1>TANYA GUPTA</h1>
                <div class="subtitle">BBA – DIGITAL MARKETING | E-COMMERCE, MARKETING &amp; BUSINESS OPERATIONS</div>
                <div class="contact-info">
                    Email: <a href="mailto:2024bbatanya18418@poornima.edu.in">2024bbatanya18418@poornima.edu.in</a> | Phone: <a href="tel:7355301632">7355301632</a><br>
                    LinkedIn: <a href="https://linkedin.com/in/tanya-gupta-39a59b329" target="_blank">linkedin.com/in/tanya-gupta-39a59b329</a> | Jaipur, Rajasthan
                </div>
            </div>
            <!-- Replace 'profile.jpg' with your actual image file path -->
            <img src="profile.jpg" alt="Tanya Gupta" class="profile-photo">
        </header>

        <!-- Career Objective -->
        <section class="section">
            <div class="section-title">Career Objective</div>
            <div class="section-content">
                <p>BBA Digital Marketing student interested in e-commerce, digital marketing and brand building. Familiar with social media marketing, basic data handling, communication and coordination. Brings practical experience in maintaining records and professional follow-ups through an HR Recruiter internship. Eager to learn marketplace operations, product cataloguing, campaign support and business performance analysis.</p>
            </div>
        </section>

        <!-- Key Skills -->
        <section class="section">
            <div class="section-title">Key Skills</div>
            <div class="section-content">
                <ul>
                    <li>Digital marketing and social media marketing fundamentals</li>
                    <li>Interest in e-commerce platforms, online marketplaces and product listings</li>
                    <li>Basic MS Excel / Google Sheets, data entry and record management</li>
                    <li>Communication, teamwork, coordination and professional follow-up</li>
                    <li>Research, attention to detail, time management and willingness to learn</li>
                    <li>Customer-focused approach and sales/service awareness</li>
                </ul>
            </div>
        </section>

        <!-- Internship Experience -->
        <section class="section">
            <div class="section-title">Internship Experience</div>
            <div class="section-content">
                <div class="job-header">
                    HR Recruiter Intern | ShreenathjiNaukri.org <span>(Remote | 1 May – 31 July 2026)</span>
                </div>
                <ul>
                    <li>Sourced candidate profiles, screened resumes and shortlisted applicants according to role requirements.</li>
                    <li>Communicated with candidates, coordinated interview updates and completed follow-ups.</li>
                    <li>Maintained candidate information and recruitment records with attention to detail.</li>
                    <li>Built transferable skills in communication, coordination, documentation and task management.</li>
                </ul>
            </div>
        </section>

        <!-- Educational Qualifications -->
        <section class="section">
            <div class="section-title">Educational Qualifications</div>
            <div class="section-content" style="padding: 0; border: none;">
                <table>
                    <thead>
                        <tr>
                            <th>QUALIFICATION</th>
                            <th>INSTITUTE</th>
                            <th>RESULT</th>
                            <th>YEAR</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>BBA – Digital Marketing</td>
                            <td>Poornima University</td>
                            <td>CGPA: 8.83</td>
                            <td>2024–2027</td>
                        </tr>
                        <tr>
                            <td>Class 12th</td>
                            <td>Asha Public School</td>
                            <td>74.2% (CBSE)</td>
                            <td>2024</td>
                        </tr>
                        <tr>
                            <td>Class 10th</td>
                            <td>Kapil Muni Children's Academy</td>
                            <td>62.2% (CBSE)</td>
                            <td>2022</td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </section>

        <!-- Relevant Certifications & Courses -->
        <section class="section">
            <div class="section-title">Relevant Certifications &amp; Courses</div>
            <div class="section-content">
                <ul>
                    <li>Digital Marketing Foundations – LinkedIn Learning</li>
                    <li>Social Media Marketing – HP</li>
                    <li>Executive Diploma in Sales and Service Management – Udemy</li>
                    <li>Effective Leadership – HP</li>
                </ul>
            </div>
        </section>

        <!-- Activities & Additional Details -->
        <section class="section">
            <div class="section-title">Activities &amp; Additional Details</div>
            <div class="section-content">
                <ul>
                    <li>Coordinated academic group presentations and assignments; took responsibility for team tasks.</li>
                    <li>Assisted with university/hostel cultural activities and participated in group discussions.</li>
                </ul>
            </div>
        </section>

        <!-- Languages -->
        <section class="section">
            <div class="section-title">Languages</div>
            <div class="section-content">
                <p>Hindi, English, French (Beginner)</p>
            </div>
        </section>
    </div>

</body>
</html>
