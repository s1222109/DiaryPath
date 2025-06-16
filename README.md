# DiaryPath
日記系統的網址

<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8" />
  <title>Redirecting...</title>
  <script>
    // ✅ 在這裡只改一次網址
    const targetURL = "https://f128ea1af328cd39ea.gradio.live/";
    // 自動跳轉
    window.location.replace(targetURL);
  </script>
</head>
<body>
  <p>Redirecting to <a id="link" href="#">這裡</a></p>

  <script>
    // 將網址寫入超連結（如果跳轉失敗可手動點）
    document.getElementById("link").href = targetURL;
  </script>
</body>
</html>
