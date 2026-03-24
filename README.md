<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Romadoro | Launching Soon</title>
  <meta name="description" content="Romadoro is a luxury jewelry brand launching soon." />
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: Arial, Helvetica, sans-serif;
      background: linear-gradient(180deg, #070707 0%, #111111 100%);
      color: #f5f1e8;
      min-height: 100vh;
    }

    .wrapper {
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      padding: 40px 20px;
      text-align: center;
    }

    .brand {
      font-size: 14px;
      letter-spacing: 6px;
      color: #c9a24a;
      margin-bottom: 24px;
      text-transform: uppercase;
    }

    h1 {
      font-size: clamp(38px, 7vw, 82px);
      letter-spacing: 4px;
      font-weight: 600;
      margin-bottom: 18px;
    }

    .subtitle {
      font-size: clamp(18px, 2.2vw, 26px);
      color: #d8c08a;
      margin-bottom: 20px;
    }

    .text {
      max-width: 680px;
      font-size: 16px;
      line-height: 1.7;
      color: #ddd6c8;
      margin-bottom: 36px;
    }

    .badge {
      display: inline-block;
      border: 1px solid #c9a24a;
      color: #c9a24a;
      padding: 12px 24px;
      border-radius: 999px;
      font-size: 14px;
      letter-spacing: 2px;
      text-transform: uppercase;
      margin-bottom: 48px;
    }

    .box {
      width: 100%;
      max-width: 760px;
      border: 1px solid rgba(201, 162, 74, 0.35);
      background: rgba(255, 255, 255, 0.03);
      padding: 28px 22px;
      border-radius: 18px;
      backdrop-filter: blur(4px);
    }

    .box-title {
      color: #c9a24a;
      font-size: 13px;
      letter-spacing: 3px;
      text-transform: uppercase;
      margin-bottom: 14px;
    }

    .box p {
      color: #e8e0d2;
      line-height: 1.7;
      font-size: 15px;
    }

    .footer {
      margin-top: 40px;
      font-size: 13px;
      color: #9b927f;
    }

    .footer a {
      color: #d8c08a;
      text-decoration: none;
    }

    .footer a:hover {
      text-decoration: underline;
    }

    @media (max-width: 640px) {
      .wrapper {
        padding: 30px 16px;
      }

      .box {
        padding: 22px 18px;
      }
    }
  </style>
</head>
<body>
  <div class="wrapper">
    <div class="brand">Romadoro</div>

    <h1>Luxury Jewelry</h1>
    <div class="subtitle">Launching Soon</div>

    <p class="text">
      Romadoro is a modern jewelry brand focused on timeless elegance, refined design,
      and a premium shopping experience. Our collection is being prepared with care and will be revealed soon.
    </p>

    <div class="badge">Coming Soon</div>

    <div class="box">
      <div class="box-title">About the Brand</div>
      <p>
        Discover a world of elevated jewelry style inspired by classic beauty and contemporary sophistication.
        Romadoro is being built to offer a polished, luxurious destination for customers who appreciate
        distinctive pieces and elegant presentation.
      </p>
    </div>

    <div class="footer">
      © 2026 Romadoro. All rights reserved.
    </div>
  </div>
</body>
</html>
