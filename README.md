<!DOCTYPE HTML>
<html lang="en">

<head>
</head>

<body>
    <script>
        var arr = [];
        while (arr.length < 10) {
            var a = Math.round(Math.random() * 10);
            arr.push(a);
        }
        arr.sort();
        document.write(arr);
    </script>
</body>

</html>
