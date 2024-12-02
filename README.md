<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title id="pageTitle">Ổ rắn độc không hồi kết</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-image: url('https://example.com/sunset-background.jpg'); /* Thay link ảnh nền hoàng hôn */
            background-size: cover;
            background-position: center;
            color: white;
        }
        header {
            background-color: rgba(0, 0, 0, 0.7);
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            gap: 20px;
            margin: 20px;
        }
        .photo-card {
            width: 200px;
            border: 2px solid #ccc;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .photo-card img {
            width: 100%;
            height: auto;
        }
        .content {
            padding: 10px;
            background-color: rgba(0, 0, 0, 0.7); /* Nền mờ cho phần nội dung */
            text-align: center;
        }
        .content input[type="text"] {
            width: 100%;
            padding: 5px;
            font-size: 14px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .content input[type="file"] {
            margin-top: 10px;
        }
        h2 {
            text-align: center;
            color: #fff;
        }
        footer {
            background-color: rgba(0, 0, 0, 0.7);
            color: white;
            text-align: center;
            padding: 10px;
        }
        footer a {
            color: #fff;
            text-decoration: none;
        }
    </style>
</head>
<body>

<header>
    <h1 id="pageTitle">Ổ rắn độc không hồi kết</h1>
</header>

<!-- Nhóm 1 -->
<section class="group1">
    <h2 class="group-title">
        <input type="text" value="Nhóm 1: Những khoảnh khắc đáng nhớ" id="groupTitle1" oninput="changeGroupTitle(1)">
    </h2>
    <div class="gallery">
        <!-- Các ảnh trong nhóm 1 -->
        <div class="photo-card">
            <img id="image1" src="images/group1_1.jpg" alt="Ảnh 1">
            <div class="content">
                <input type="file" id="file1" onchange="changeImage(1)">
            </div>
        </div>
        <div class="photo-card">
            <img id="image2" src="images/group1_2.jpg" alt="Ảnh 2">
            <div class="content">
                <input type="file" id="file2" onchange="changeImage(2)">
            </div>
        </div>
        <div class="photo-card">
            <img id="image3" src="images/group1_3.jpg" alt="Ảnh 3">
            <div class="content">
                <input type="file" id="file3" onchange="changeImage(3)">
            </div>
        </div>
        <div class="photo-card">
            <img id="image4" src="images/group1_4.jpg" alt="Ảnh 4">
            <div class="content">
                <input type="file" id="file4" onchange="changeImage(4)">
            </div>
        </div>
        <div class="photo-card">
            <img id="image5" src="images/group1_5.jpg" alt="Ảnh 5">
            <div class="content">
                <input type="file" id="file5" onchange="changeImage(5)">
            </div>
        </div>
        <div class="photo-card">
            <img id="image6" src="images/group1_6.jpg" alt="Ảnh 6">
            <div class="content">
                <input type="file" id="file6" onchange="changeImage(6)">
            </div>
        </div>
        <div class="photo-card">
            <img id="image7" src="images/group1_7.jpg" alt="Ảnh 7">
            <div class="content">
                <input type="file" id="file7" onchange="changeImage(7)">
            </div>
        </div>
    </div>
</section>

<!-- Nhóm 2 -->
<section class="group2">
    <h2 class="group-title">
        <input type="text" value="Nhóm 2: Những kỷ niệm khác" id="groupTitle2" oninput="changeGroupTitle(2)">
    </h2>
    <div class="gallery">
        <div class="photo-card">
            <img id="image8" src="images/group2_1.jpg" alt="Ảnh 1">
            <div class="content">
                <input type="file" id="file8" onchange="changeImage(8)">
            </div>
        </div>
        <div class="photo-card">
            <img id="image9" src="images/group2_2.jpg" alt="Ảnh 2">
            <div class="content">
                <input type="file" id="file9" onchange="changeImage(9)">
            </div>
        </div>
        <div class="photo-card">
            <img id="image10" src="images/group2_3.jpg" alt="Ảnh 3">
            <div class="content">
                <input type="file" id="file10" onchange="changeImage(10)">
            </div>
        </div>
        <div class="photo-card">
            <img id="image11" src="images/group2_4.jpg" alt="Ảnh 4">
            <div class="content">
                <input type="file" id="file11" onchange="changeImage(11)">
            </div>
        </div>
        <div class="photo-card">
            <img id="image12" src="images/group2_5.jpg" alt="Ảnh 5">
            <div class="content">
                <input type="file" id="file12" onchange="changeImage(12)">
            </div>
        </div>
        <div class="photo-card">
            <img id="image13" src="images/group2_6.jpg" alt="Ảnh 6">
            <div class="content">
                <input type="file" id="file13" onchange="changeImage(13)">
            </div>
        </div>
        <div class="photo-card">
            <img id="image14" src="images/group2_7.jpg" alt="Ảnh 7">
            <div class="content">
                <input type="file" id="file14" onchange="changeImage(14)">
            </div>
        </div>
    </div>
</section>

<!-- Footer -->
<footer>
    <p>Liên hệ với người tạo trang: <a href="mailto:hieu642007vb@gmail.com">hieu642007vb@gmail.com</a></p>
    <p>Facebook: <a href="https://www.facebook.com/profile.php?id=61553972216070" target="_blank">Trần Hiếu</a></p>
</footer>

<script>
    function changeGroupTitle(groupNumber) {
        var groupTitle = document.getElementById('groupTitle' + groupNumber).value;
        document.getElementById('groupTitle' + groupNumber).value = groupTitle;
    }

    function changeImage(imageNumber) {
        var fileInput = document.getElementById('file' + imageNumber);
        var file = fileInput.files[0];
        var reader = new FileReader();

        reader.onload = function (e) {
            document.getElementById('image' + imageNumber).src = e.target.result;
        };

        if (file) {
            reader.readAsDataURL(file);
        }
    }
</script>

</body>
</html>
