<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Latihan DOM</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" 
    integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
    <script defer src="https://use.fontawesome.com/releases/v5.8.1/js/all.js" 
    integrity="sha384-g5uSoOSBd7KkhAMlnQILrecXvzst9TdC09/VM+pjDTCM+1il8RHz5fKANTFFb+gQ" crossorigin="anonymous"></script>
</head>
<body>
    <div class="container">
        <nav class="navbar navbar-light bg-light">
            <a class="navbar-brand">Mini Ecommerce</a>
            <form class="form-inline" id="formItem">
                <input class="form-control mr-sm-2" type="search" placeholder="Search"  id="keyword" aria-label="Search">
                <button class="btn btn-outline-success my-2 my-sm-0" type="submit" id="searchItem">Search</button>
            </form>
            <button class="btn btn-primary" id="cart"><i class="fas fa-shopping-cart"></i>(0)</button>
        </nav>

        <div class="row">
            <div class="row col-md-12 mt-2"  id="listBarang" > 
            </div> 
        </div>
        <div class ="col-4 mt-2"> 
            <div class="card" style="width: 18rem;">
            <img src="jerry.jpg" class="card-img-top" height="200px" width="200px" alt="...">
            <div class="card-body">
                <h5 class="card-title" id="itemName">Mouse Jerry</h5>
                <p class="card-text" id="itemDesc">Mouse yang disukai kucing</p>
                <p class="card-text">Rp 30.000</p>
                <a href="#" class="btn btn-primary" id="addCart">Tambahkan ke keranjang</a>
            </div>
            </div>
</div>
    </div>
    </div>
        </div>
    </div>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" 
    integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
</body>
</html>
