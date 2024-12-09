<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>광운대학교 로그인</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .login-container {
            background-color: white;
            padding: 40px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            width: 300px;
        }
        h1 {
            text-align: center;
            color: #800020; /* 버건디 색상 */
            font-size: 20px;
            line-height: 1.4;
            margin-bottom: 20px;
        }
        label {
            color: #800020; /* 버건디 색상 */
            font-weight: bold;
            margin-bottom: 8px;
            display: block;
        }
        input[type="text"], input[type="password"], input[type="submit"] {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 4px;
            font-size: 14px;
            box-sizing: border-box; /* 패딩과 보더 포함한 너비 계산 */
        }
        input[type="submit"] {
            background-color: #800020; /* 버건디 색상 */
            color: white;
            border: none;
            border-radius: 4px;
            font-size: 16px;
            cursor: pointer;
        }
        input[type="submit"]:hover {
            background-color: #6a001f; /* 더 어두운 버건디 */
        }
        .small-links {
            text-align: center;
            font-size: 12px;
            margin-top: 10px;
        }
        .small-links a {
            color: #800020; /* 버건디 색상 */
            text-decoration: none;
        }
        .small-links a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="login-container">
        <h1>광운대학교 2024학년 2학기<br>수업평가 결과 열람</h1>
        <form action="/login" method="POST">
            <label for="student-id">ID (학번 또는 사번)</label>
            <input type="text" id="student-id" name="student-id" placeholder="학번 또는 사번을 입력하세요" required>

            <label for="password">비밀번호</label>
            <input type="password" id="password" name="password" placeholder="비밀번호를 입력하세요" required>

            <input type="submit" value="로그인">

            <div class="small-links">
                <p><a href="#">비밀번호 찾기</a> | <a href="#">개인정보처리방침</a></p>
            </div>
        </form>
    </div>
</body>
</html>
