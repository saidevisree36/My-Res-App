<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous" />
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
</head>

<body>
    <nav class="navbar navbar-expand-md fixed-top mb-4 bg-danger">
        <div class="container">
            <a class="navbar-brand" href="#">
            </a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                <div class="navbar-nav  ml-auto">
                    <a class="nav-link active" id="navItem1" href="#">Home <span class="sr-only">(current)</span></a>
                    <a class="nav-link ml-2" id="navItem2" href="#">Order</a>
                    <a class="nav-link ml-2" id="navItem3" href="#">Food</a>
                    <a class="nav-link ml-2" id="navItem4" href="#">Restaurant</a>
                    <a class="nav-link ml-2" id="navItem5" href="#">Testimonals</a>
                    <a class="nav-link ml-2" id="navItem6" href="#">Contact Us</a>
                    <a class="nav-link ml-2" id="navItem7" href="#">
                        <img class="nav-bar-icon" src="https://res.cloudinary.com/djryeehgj/image/upload/v1704355339/menu-bar_jjoyu3.png" />
                    </a>
                </div>
            </div>
        </div>
    </nav>

    <div class="bottom-card-container-1 d-flex justify-content-start mt-5">
        <div class="row">
            <div class="col-12 col-md-6">
                <div class="card-container-1 d-flex flex-column justify-content-start mt-5">
                    <h1 class="heading">LOREM IPSUM</h1>
                    <p class="paragraph">
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamusid est vitae dolor rhoncus tristique. Maecenas metus quam,rhoncus euismod lorem in, sollicitudin viverra eros. Donecdictum luctus quam ut tristique. Curabitur nec faucibus purus.Quisque congue sem nec justo mollis, in tincidunt erat pretium.Sed pulvinar, massa ac porta viverra.
                    </p>
                    <button class="btn">Click Me</button>
                </div>
            </div>

            <div class="col-12 col-md-6">
                <div class="card-container-2">
                    <img class="img" src="https://res.cloudinary.com/djryeehgj/image/upload/v1704348980/pexels-robin-stickel-70497_cfrdmb.jpg" />
                </div>
            </div>
        </div>
    </div>

    <div class="next-page-container mt-5">
        <div class="row">
            <div class="col-12 col-md-6 d-flex flex-row justify-content-start ">
                <div class="left-side-container  d-flex flex-row justify-content-start mr-4">
                    <div class="two-pics-container d-flex flex-column justify-content-start">
                        <img class="pic-1" src="https://res.cloudinary.com/djryeehgj/image/upload/v1704359087/pexels-rachel-claire-6752433_iwmn1g.jpg" />
                        <img class="pic-2" src="https://res.cloudinary.com/djryeehgj/image/upload/v1704359154/pexels-eva-bronzini-6141651_r2xzri.jpg" />
                    </div>
                    <div class="one-pic-container d-flex flex-column justify-content-start">
                        <img class="pic-3" src="https://res.cloudinary.com/djryeehgj/image/upload/v1704359286/pexels-mister-mister-3434523_as5b41.jpg" />
                    </div>
                </div>
            </div>
            <div class="col-12 col-md-6">
                <div class="right-container ml-2 d-flex flex-column justify-content-start">
                    <div class="right-side-container d-flex flex-column justify-content-start p-2">
                        <h1 class="next-page-heading">LOREM IPSUM</h1>
                        <p class="nxt-page-paragraph">
                            LOREM IPSUM
                            <br />SET ADEMIR
                        </p>
                        <div class="button-icon-container">
                            <button class="btn-1">Click</button>
                            <img class="arrow-icon" src="https://res.cloudinary.com/djryeehgj/image/upload/v1704359694/icons8-arrow-30_i0ifzj.png" />
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>

</html>

css:
@import url('https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap');

.next-page-container {
    min-height: 100vh;
    min-width: 150vw;
    background-image: linear-gradient(to right, #fcfbb3, #eebcf5, #e0b79b);
    background-size: cover;
    margin-top: 20px;
}

.right-container {
    min-height: 500px;
    min-width: 500px;
    margin-top: 80px;
    background-color: transparent;
}

.nxt-page-paragraph {
    color: #000000;
    font-size: 60px;
    font-family: "Roboto";
    font-weight: bold;
}

.right-side-container {
    height: 300px;
    min-width: 500px;
    background-color: #c9766d;
    color: #000000;
    text-align: center;
    margin-top: 80px;
}

.button-icon-container {
    height: 100px;
    width: 200px;
    background-color: transparent;
}

.btn-1 {
    border: none;
    color: #000000;
    font-size: 20px;
    background-color: transparent;
}

.next-page-heading {
    align-self: flex-start;
    margin-left: 5px;
    font-size: 25px;
    font-family: "Roboto";
}

.left-side-container {
    height: 650px;
    min-width: 500px;
    background-color: transparent;
}

.two-pics-container {
    height: 650px;
    width: 250px;
    background-color: transparent;
    margin-top: 25px;
}

.one-pic-container {
    height: 650px;
    width: 250px;
    background-color: transparent;
    margin-top: 25px;
}

.top-card-container {
    background-size: cover;
    width: 80vw;
    margin: 0;
}

.card-container-1 {
    background-color: transparent;
    padding: 15px;
}

.heading {
    color: #000000;
    font-size: 40px;
    text-align: center;
    font-family: "Roboto";
    font-weight: bold;
}

.paragraph {
    font-size: 25px;
    color: #000000;
}

.btn {
    height: 50px;
    width: 200px;
    background-color: #c23e34;
    color: #ffffff;
    font-size: 20px;
    align-self: flex-start;
    border: none;
}

.img {
    height: 800px;
    width: 550px;
}

.bottom-card-container-1 {
    min-height: 830px;
    min-width: 150vw;
    background-color: #000000;
    background-image: linear-gradient(to right, #fcfbb3, #eebcf5, #e0b79b);
    background-size: cover;
}

.image-1 {
    height: 50vh;
    width: 40vw;
}

.navbar-toggler {
    height: 50px;
    color: #ffffff;
    border: 5px solid #ffffff;
}

#navItem1 {
    font-size: 20px;
    color: #000000;
}

#navItem2 {

    font-size: 20px;
    color: #000000;

}

#navItem3 {
    font-size: 20px;
    color: #000000;
}

#navItem4 {
    font-size: 20px;
    color: #000000;
}

#navItem5 {
    font-size: 20px;
    color: #000000;
}

#navItem6 {
    font-size: 20px;
    color: #000000;
}

#navItem7 {
    font-size: 20px;
    color: #000000;
}

.nav-bar-icon {
    height: 35px;
    width: 35px;
}

.pic-1 {
    height: 300px;
    width: 250px;
    margin-bottom: 5px;
}

.pic-2 {
    height: 300px;
    width: 250px;
}

.pic-3 {
    height: 600px;
    width: 250px;
    margin-left: 10px;
}
