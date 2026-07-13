<!DOCTYPE html>
<html lang="en"><head><meta charset="UTF-8"><meta name="viewport" content="width=device-width,initial-scale=1">
<title>Krishna Portfolio</title>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
<style>
body{font-family:Poppins,sans-serif;background:linear-gradient(135deg,#2563eb,#60a5fa,#3b82f6)}
.navbar,.footer{background:#fff}.glass{background:rgba(255,255,255,.15);backdrop-filter:blur(18px);border:1px solid rgba(255,255,255,.25);border-radius:20px;color:#fff;box-shadow:0 8px 24px rgba(0,0,0,.15)}
.profile-card{background:#fff;border-radius:20px}
.edu-card{background:rgba(255,255,255,.12);backdrop-filter:blur(25px);border:1px solid rgba(255,255,255,.25);border-radius:18px;color:#fff;padding:25px;height:100%;transition:.3s}
.edu-card:hover{transform:translateY(-5px)}
.badge{margin:4px}
.font-size {
    font-size: 25px;
}
.font-size {
    font-size: 25px;
}
    </style>
</head>
<body>
<nav class="navbar navbar-expand-lg shadow-sm sticky-top">
<div class="container">
<a class="navbar-brand fw-bold text-primary fs-3" href="#">KRISHNA PORTFOLIO</a>
<button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
<span class="navbar-toggler-icon"></span>
</button>
<div class="collapse navbar-collapse" id="navbarNav">
<ul class="navbar-nav ms-auto">
<li class="nav-item"><a class="nav-link" href="#about">About</a></li>
<li class="nav-item"><a class="nav-link" href="#education">Education</a></li>
<li class="nav-item"><a class="nav-link" href="#skills">Skills</a></li>
<li class="nav-item"><a class="nav-link" href="#experience">Experience</a></li>
<li class="nav-item"><a class="nav-link" href="#footer">Contact</a></li>
</ul></div></div></nav>
<div class="container my-4"><div class="profile-card p-4 shadow"><div class="row align-items-center"><div class="col-md-3 text-center">
    <img src="profile.jpeg"class="rounded-circle border border-3 border-primary" style="width:170px;height:170px;object-fit:cover"></div>
    <div class="col-md-9"><h2 class="text-primary fw-bold">Krishna Vasista CR</h2>
        <h5 class="text-secondary">BCA Student • Web Developer</h5>
        <a href="#footer" class="btn btn-primary mt-3"><i class="bi bi-envelope-fill me-2"></i>Contact Me</a>
    </div>
</div>
</div>
</div>
<div class="container pb-4">
<div class="glass p-4 mb-4" id="about"><h2>About Me</h2>
    <p>
    I am a Final Year BCA student with a strong foundation in computer fundamentals, programming, and web development.
     I have good knowledge of C, Java, Python, HTML, CSS, and SQL gained through my academic coursework.
      I am a fast learner, highly motivated, and passionate about technology.
       I am looking for an entry-level opportunity where I can apply my skills, learn from experienced professionals, and grow as a software developer.
    </p>
    </div>
<div class="glass p-5 mb-5" id="education"><h2 class="text-center mb-5">Education</h2>
    <div class="row g-6">
        <div class="col-md-4">
            <div class="edu-card text-center">
                <h2>SSLC</h2>
                <hr><b>School</b>
                <b>Vidyanekthan High School</b>
            </div>
        </div>
        <div class="col-md-4">
            <div class="edu-card text-center">
                <h2>PUC</h2>
            <hr><b>College</b>
            <b>Sarvodaya PU College</b>
        </div>
    </div>
    <div class="col-md-4">
        <div class="edu-card text-center">
        <h2>Degree</h2>
        <hr><b>University</b>
        <b>University College of Science, Tumkur</b>
    </div>
</div>
</div>
</div>
<div class="glass p-3 mb-3" id="skills">
    <h2 class="text-center mb-4">Skills</h2>
    <div class="row g-6"><div class="col-md-6">
        <div class="edu-card text-center">
            <h2>Technical Skills</h2>
            <div class ="font-size">
            <hr><span class="badge bg-primary">HTML</span>
            <span class="badge bg-success">Python</span>
            <span class="badge bg-warning text-dark">Java</span>
            <span class="badge bg-info text-dark">MySQL</span>
            <span class="badge bg-danger">C/C++</span>
            <span class="badge bg-dark">MS Office</span>
            </div>
        </div>
    </div>
    <div class="col-md-6">
        <div class="edu-card text-center">
            <h2>Soft Skills</h2>
        <div class ="font-size">
        <hr><span class="badge bg-secondary">Communication</span>
        <span class="badge bg-secondary">Teamwork</span>
        <span class="badge bg-secondary">Problem Solving</span>
        <span class="badge bg-secondary">Leadership</span>
        <span class="badge bg-secondary">Time Management</span>
        <span class="badge bg-secondary">Adaptability</span>
    </div>
        </div>
</div>
</div>
</div>
<div class="glass p-4 mb-4" id="experience"><h2 class="text-center mb-4">Experience</h2>
    <div class="edu-card text-center"><h3>Web Development Intern</h3>
        <hr>
        <h4>Sriin5Net Solutions</h4>
        <p>Currently pursuing a Web Development Internship at 
            <b>Sriin5Net Solutions</b>, 
            gaining practical experience in HTML, CSS, Bootstrap, JavaScript and responsive website development.</p>
        </div>
    </div>
</div>
<footer id="footer" class="footer text-center py-4 border-top">
    <div class="container"><h5 class="text-primary fw-bold">Krishna Portfolio</h5>
        <p>
            <b>Email:</b> <a href="mailto:krishnavasistac@gmail.com">krishnavasistac@gmail.com</a>
        </p>
        <p><b>Phone:</b> 9019804919</p>
        <p><b>Location:</b> Tumkur, India</p>
        <small class="text-muted">&copy; 2026 Krishna Vasista CR. All Rights Reserved.</small>
    </div>
</footer>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
