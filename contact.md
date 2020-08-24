---
layout: page
#title: Contact
subtitle:
---
<html>
  <head>
    <style>
      * {
      box-sizing: border-box;
      }
      html, body {
      min-height: 100vh;
      padding: 0;
      margin: 0;
      font-size: 14px;
      color: #000000;
      }
      input, textarea {
      outline: none;
      }
      body {
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 20px;
      background: #FFFFFF;
      }
      h1 {
      margin-top: 0;
      font-weight: 500;
      }
      form {
      position: relative;
      width: 80%;
      border-radius: 30px;
      background: #fff;
      }

      .circle {
      position: absolute;
      bottom: 80px;
      left: -55px;
      width: 20px;
      height: 20px;
      border-radius: 50%;
      background: #fff;
      }
      .form-inner {
      padding: 40px;
      }
      .form-inner input,
      .form-inner textarea {
      display: block;
      width: 100%;
      padding: 15px;
      margin-bottom: 10px;
      border: none;
      border-radius: 20px;
      background: #F6F5F3;
      }
      .form-inner textarea {
      resize: none;
      }
      button {
      width: 100%;
      padding: 10px;
      margin-top: 20px;
      border-radius: 20px;
      border: none;
      border-bottom: 4px solid #9AD3B3;
      background: #81b598;
      font-size: 16px;
      font-weight: 400;
      color: #fff;
      }
      button:hover {
      background: #466353;
      }
      @media (min-width: 568px) {
      form {
      width: 60%;
      }
      }
    </style>
  </head>
  <body>
<form action="https://formspree.io/maypkjgq" method="POST">
<div class="circle"></div>
      <div class="form-inner">
        <h1>Contact Me</h1>
        <input type="text" placeholder="Name" name="name">
        <input type="email" placeholder="Email" name="_replyto">
        <textarea placeholder="Message..." name="message" rows="5"></textarea>
        <input type="hidden" name="_next" />
        <button type="submit" href="/">Submit</button>

      </div>
    </form>
  </body>
</html>
