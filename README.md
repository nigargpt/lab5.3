# lab5.3


<!DOCTYPE html>
<html lang="az">
<head>
    <meta charset="UTF-8">
    <title>Box Model</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="margin">
    <p class="label top">Margin</p>

    <div class="border">
        <p class="label">Border</p>

        <div class="padding">
            <p class="label">Padding</p>

            <div class="content">
                Content
            </div>

        </div>
    </div>
</div>

</body>
</html>


css hisse

body {
    background: #eee;
    font-family: Arial, sans-serif;
}

/* Margin sahəsi */
.margin {
    border: 2px dashed #999;
    width: 600px;
    margin: 50px auto;
    padding: 20px;
    position: relative;
}

/* Border sahəsi */
.border {
    background: #821c9c;
    padding: 20px;
}

/* Padding sahəsi */
.padding {
    background: #e5e5e5;
    padding: 30px;
    text-align: center;
}

/* Content */
.content {
    border: 2px dashed #aaa;
    padding: 30px;
    background: #f5f5f5;
}

/* Yazılar */
.label {
    text-align: center;
    font-weight: bold;
    margin-bottom: 10px;
}

.top {
    position: absolute;
    top: -25px;
    left: 50%;
    transform: translateX(-50%);
    background: #eee;
    padding: 0 10px;
}
