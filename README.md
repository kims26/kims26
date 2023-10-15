<!DOCTYPE html>
<html>
<head>
    <title>동적 HTML 예제</title>
</head>
<body>
    <h1>동적 HTML 생성 예제</h1>
    <div id="dynamic-content">
     김상현
    </div>

    <script>
        // JavaScript를 사용하여 동적으로 HTML 생성
        var dynamicContent = document.getElementById("dynamic-content");

        var paragraph = document.createElement("p");
        paragraph.textContent = "이 문단은 JavaScript를 사용하여 동적으로 생성되었습니다.";
        dynamicContent.appendChild(paragraph);

        var link = document.createElement("a");
        link.textContent = "동적 링크";
        link.href = "https://www.example.com";
        dynamicContent.appendChild(link);
    </script>
</body>
</html>
