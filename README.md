<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive Card</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background-color: #f3f4f6;
            margin: 0;
        }
        .card {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            border-radius: 10px;
        }
        .card:hover {
            transform: scale(1.05);
            box-shadow: 0 0 20px rgba(0, 123, 255, 0.8);
        }
    </style>
</head>
<body>
    <div class="card" style="width: 22rem;">
        <img src="https://via.placeholder.com/400" class="card-img-top" alt="">
        <div class="card-body">
            <h5 class="card-title">Responsive Card</h5>
            <p class="card-text">This is a modern responsive card with hover animation.</p>
            <a href="#" class="btn btn-primary">Click to Open</a>
        </div>
    </div>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
