<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Phạm Mai - Portfolio</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', sans-serif;
    }

    body {
      display: flex;
      background: #FFFFFF;
      color: #0F172A;
    }

    /* SIDEBAR */
    .sidebar {
      width: 280px;
      background: #F8FAFC;
      padding: 30px 20px;
      min-height: 100vh;
      border-right: 1px solid #E2E8F0;
    }

    .avatar {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      background: #ddd;
      margin: 0 auto 20px;
      border: 3px solid #2563EB;
    }

    .name {
      text-align: center;
      font-size: 22px;
      font-weight: bold;
    }

    .role {
      text-align: center;
      margin-top: 8px;
      padding: 5px 10px;
      background: #DBEAFE;
      color: #1E40AF;
      border-radius: 20px;
      font-size: 13px;
      display: inline-block;
    }

    .center {
      text-align: center;
    }

    .contact {
      margin-top: 30px;
      font-size: 14px;
    }

    .contact p {
      margin: 10px 0;
    }

    .social {
      margin-top: 20px;
    }

    .social a {
      display: inline-block;
      margin-right: 10px;
      text-decoration: none;
      color: #2563EB;
      font-weight: bold;
    }

    /* MAIN */
    .main {
      flex: 1;
      padding: 40px;
    }

    h2 {
      margin-bottom: 15px;
      color: #1E40AF;
    }

    .section {
      margin-bottom: 40px;
    }

    /* SKILL CARDS */
    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .card {
      background: #FFFFFF;
      border: 1px solid #E2E8F0;
      border-radius: 16px;
      padding: 20px;
      transition: 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 10px 25px rgba(37, 99, 235, 0.15);
    }

    .card h3 {
      margin-bottom: 10px;
      color: #2563EB;
    }

    .card p {
      font-size: 14px;
      color: #475569;
    }

  </style>
</head>

<body>

  <!-- SIDEBAR -->
  <div class="sidebar">
    <div class="avatar"></div>

    <div class="name">Phạm Mai</div>
    <div class="center">
      <div class="role">International Business</div>
    </div>

    <div class="contact">
      <h3>Contact</h3>
      <p>Email: your@email.com</p>
      <p>Phone: 0123 456 789</p>
      <p>Address: Hanoi, Vietnam</p>
    </div>

    <div class="social">
      <a href="#">Facebook</a>
      <a href="#">LinkedIn</a>
      <a href="#">GitHub</a>
    </div>
  </div>

  <!-- MAIN -->
  <div class="main">

    <!-- INTRO -->
    <div class="section">
      <h2>Giới thiệu</h2>
      <p>
        Tôi theo đuổi Kinh doanh Quốc tế với định hướng hiểu rõ cách doanh nghiệp đưa ra quyết định trong môi trường nhiều biến động. 
        Tôi tập trung vào việc phân tích dữ liệu và bối cảnh thị trường để lý giải chiến lược kinh doanh trong thực tế.
      </p>
    </div>

    <!-- INTEREST -->
    <div class="section">
      <h2>Hướng quan tâm</h2>
      <ul>
        <li>Chiến lược kinh doanh quốc tế</li>
        <li>Phân tích thị trường và người tiêu dùng</li>
        <li>Môi trường vĩ mô và tác động đến doanh nghiệp</li>
        <li>Hành vi doanh nghiệp trong bối cảnh toàn cầu</li>
      </ul>
    </div>

    <!-- SKILLS -->
    <div class="section">
      <h2>Kỹ năng</h2>

      <div class="cards">

        <div class="card">
          <h3>Data Analysis</h3>
          <p>Data cleaning, analysis & visualization using Excel, SQL, and basic Python</p>
        </div>

        <div class="card">
          <h3>Market Research</h3>
          <p>Researching market trends, consumer behavior, and competitor analysis</p>
        </div>

        <div class="card">
          <h3>Business Analysis</h3>
          <p>Analyzing business models, identifying problems, and proposing solutions</p>
        </div>

        <div class="card">
          <h3>Reporting & Presentation</h3>
          <p>Presenting insights clearly through reports and data visualization</p>
        </div>

      </div>
    </div>

    <!-- EDUCATION -->
    <div class="section">
      <h2>Học vấn</h2>
      <p>Sinh viên chuyên ngành Kinh doanh Quốc tế – Đại học Ngoại Thương (FTU)</p>
    </div>

    <!-- VIEWPOINT -->
    <div class="section">
      <h2>Quan điểm</h2>
      <ul>
        <li>Phân tích thị trường – đưa ra giả định – điều chỉnh chiến lược</li>
        <li>Chiến lược hiệu quả cần thích ứng với thực tế thị trường</li>
        <li>Luôn đặt câu hỏi và kiểm chứng giả định bằng dữ liệu</li>
      </ul>
    </div>

  </div>

</body>
</html>
