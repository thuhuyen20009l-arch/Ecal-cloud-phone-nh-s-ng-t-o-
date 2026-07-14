# Ecal-cloud-phone-nh-s-ng-t-o-<!DOCTYPE html>
<html>
<head>
    <!-- 1. Tiêu đề + CSS -->
</head>

<body>

    <!-- 2. Giao diện web -->
    <h1>ECAL Creator</h1>

    <button onclick="register()">Đăng ký</button>
    <button onclick="login()">Đăng nhập</button>
    <button onclick="logout()">Đăng xuất</button>

    <p id="user"></p>


    <!-- 3. Firebase code đặt gần cuối -->
    <script type="module">

    // Import Firebase
    import { initializeApp } 
    from "https://www.gstatic.com/firebasejs/12.16.0/firebase-app.js";

    import { 
    getAuth,
    createUserWithEmailAndPassword,
    signInWithEmailAndPassword,
    signOut,
    onAuthStateChanged
    } 
    from "https://www.gstatic.com/firebasejs/12.16.0/firebase-auth.js";


    // Dán firebaseConfig của bạn ở đây

    const app = initializeApp(firebaseConfig);
    const auth = getAuth(app);


    // Code đăng ký
    // Code đăng nhập
    // Code đăng xuất


    </script>

</body>
</html>
