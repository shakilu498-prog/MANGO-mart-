<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8">
  <title>MANGO MART BD - Order Form</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #fff8e1;
      margin: 0;
      padding: 0;
    }
    .container {
      max-width: 420px;
      margin: 50px auto;
      background: white;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0px 0px 10px #ddd;
    }
    h2 {
      text-align: center;
      color: #ff9800;
    }
    label {
      font-weight: bold;
      margin-top: 10px;
      display: block;
    }
    input, textarea {
      width: 100%;
      padding: 10px;
      margin-top: 5px;
      border-radius: 8px;
      border: 1px solid #ccc;
    }
    button {
      width: 100%;
      padding: 12px;
      background: #ff9800;
      color: white;
      border: none;
      border-radius: 8px;
      margin-top: 15px;
      font-size: 16px;
      cursor: pointer;
    }
    button:hover {
      background: #e68900;
    }
    .note {
      text-align: center;
      font-size: 13px;
      color: gray;
      margin-top: 10px;
    }
  </style>
</head>
<body>

<div class="container">
  <h2>🥭 Mango Order Form</h2>

  <form>
    <label>নাম</label>
    <input type="text" placeholder="আপনার নাম লিখুন">

    <label>মোবাইল নাম্বার</label>
    <input type="text" placeholder="01XXXXXXXXX">

    <label>ঠিকানা</label>
    <textarea rows="3" placeholder="আপনার সম্পূর্ণ ঠিকানা লিখুন"></textarea>

    <label>আমের পরিমাণ (kg / box)</label>
    <input type="text" placeholder="যেমন: ৫ কেজি">

    <button type="submit">অর্ডার কনফার্ম করুন</button>
  </form>

  <div class="note">
    📢 অর্ডার নিশ্চিত করতে আমরা আপনাকে কল করবো
  </div>
</div>

</body>
</html>
