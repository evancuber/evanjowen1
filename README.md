<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>JE Cubes</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha2/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-aFq/bzH65dt+w6FI2ooMVUpc+21e0SRygnTpmBvdBgSdnuTN7QbdgL+OapgHtvPp" crossorigin="anonymous">
  <link rel="shorcut icon" href="image/favicon.ico" type="image/x-icon">
    
  <style>
    .feature-icon {
      width: 4rem;
      height: 4rem;
      border-radius: 0.75rem;

    }
  </style>
</head>

<body>

  <nav class="navbar navbar-expand-lg bg-body-tertiary">
    <div class="container-fluid">
      <a class="navbar-brand" href="#"><img src="image/rubik.png" alt="" height="40"> J.E Cubes</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">About</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              Services
            </a>
            <ul class="dropdown-menu">
              <li><a class="dropdown-item" href="#">3x3x3 Cubes</a></li>
              <li><a class="dropdown-item" href="#">The Cube Station</a></li>
              <li>
                <hr class="dropdown-divider">
              </li>
              <li><a class="dropdown-item" href="#">Something else here</a></li>
            </ul>
          </li>
        </ul>
        <form class="d-flex" role="search">
          <input class="form-control me-2" type="search" placeholder="Postcode" aria-label="Search">
          <button class="btn btn-outline-success" type="submit">Check</button>
        </form>
      </div>
    </div>
  </nav>


  <div class="px-4 pt-5 my-5 text-center border-bottom">
    <h1 class="display-4 fw-bold text-body-emphasis">THE CUBE STATION</h1>
    <div class="col-lg-6 mx-auto">
      <p class="lead mb-4">Cube Station supports smart cubes, normal cubes, virtual cubes and devices like GAN Robot, bluetooth timer and so on. It's the platform for cubers worldwide to battle online, train to improve and learn through AI, helping every player to enjoy the pleasure of speed cubing.
      </p>
      <div class="d-grid gap-2 d-sm-flex justify-content-sm-center mb-5">
        <button type="button" class="btn btn-primary btn-lg px-4 me-sm-3">Get a Cube</button>
        <button type="button" class="btn btn-outline-secondary btn-lg px-4">Contact Us</button>
      </div>
    </div>
    <div class="overflow-hidden" style="max-height: 30vh;">
      <div class="container px-5">
        <img src="image/deluxe.webp" class="img-fluid border rounded-3 shadow-lg mb-4" alt="Example image" width="700"
          height="500" loading="lazy">
      </div>
    </div>
  </div>

  <div class="container px-4 py-5" id="featured-3">
    <h2 class="pb-2 border-bottom">Why Cube Station?</h2>
    <div class="row g-4 py-5 row-cols-1 row-cols-lg-3">
      <div class="feature col">
        <div
          class="feature-icon d-inline-flex align-items-center justify-content-center text-bg-primary bg-white fs-2 mb-3">
          <img src="image/bar-chart-fill.svg" alt="briefcase" height="30">
        </div>
        <h3 class="fs-2">Rankings</h3>
        <p>
            Our team of Rubik's Cube solvers is dedicated to achieving peak efficiency, precision, and meticulousness.
             We recognize that each cube represents not just a puzzle, but a unique set of challenges and memories. 
             That's why we handle each cube with the utmost care,
             ensuring that every twist and turn is executed with precision and attention to detail. You can be a champion and be a one of the greatest cubers!</p>
        <a href="#" class="btn btn-outline-success">
          Get a quote
          <img src="image/arrow1-right.svg" alt="chevron-right">
        </a>
      </div>
      <div class="feature col">
        <div
          class="feature-icon d-inline-flex align-items-center justify-content-center text-bg-primary bg-white fs-2 mb-3">
          <img src="image/people.svg" alt="bus-front" height="30">
        </div>
        <h3 class="fs-2">Cubers</h3>
        <p>"Our team is well-equipped to assist with everything from solving and 
             optimizing your cube to sharing advanced techniques, so you can enhance your skills. Plus, with our straightforward 
             pricing and no concealed charges, 
            you can have confidence that you're receiving a reasonable and competitive rate for our expert guidance. To be more efficient and skilled person "</p>
        <a href="#" class="btn btn-outline-success">
          Get a quote
          <img src="image/arrow1-right.svg" alt="chevron-right">
        </a>
      </div>
      <div class="feature col">
        <div
          class="feature-icon d-inline-flex align-items-center justify-content-center text-bg-primary bg-white fs-2 mb-3">
          <img src="image/bounding-box.svg" alt="chat-square-heart" height="30">
        </div>
        <h3 class="fs-2">Efficient Cubes</h3>
        <p>At the heart of our mission lies the belief that solving a Rubik's Cube should be an exhilarating and rewarding endeavor, not a daunting one. By offering top-notch Rubik's Cube solving services, we aspire to transform the perception of cube-solving and deliver a superior, more customized experience for our clients.
             Get in touch with us today to discover how we can assist you in conquering your next Rubik's Cube challenge.</p>
        <a href="#" class="btn btn-outline-success">
          Get a quote
          <img src="image/arrow1-right.svg" alt="chevron-right">
        </a>
      </div>
    </div>
  </div>
  <div class="container">
    <div id="carouselExampleIndicators" class="carousel slide">
      <div class="carousel-indicators">
        <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active"
          aria-current="true" aria-label="Slide 1"></button>
        <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1"
          aria-label="Slide 2"></button>
        <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2"
          aria-label="Slide 3"></button>
      </div>
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="image/halloween.webp" class="d-block w-100" alt="halloween">
        </div>
        <div class="carousel-item">
          <img src="image/gan14.webp" class="d-block w-100" alt="gan14">
        </div>
        <div class="carousel-item">
          <img src="image/gan12.webp" class="d-block w-100" alt="gan12">
        </div>
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators"
        data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators"
        data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>
  </div>

  <div class="container">
    <footer class="row row-cols-1 row-cols-sm-2 row-cols-md-5 py-5 my-5 border-top">
      <div class="col mb-3">
        <a href="/" class="d-flex align-items-center mb-3 link-body-emphasis text-decoration-none">
          <svg class="bi me-2" width="40" height="32">
            <use xlink:href="#bootstrap"></use>
          </svg>
        </a>
        <p class="text-body-secondary">© 
            Evan Roi Tabar
            Jowen Diez 2023</p>
      </div>

      <div class="col mb-3">

      </div>

      <div class="col mb-3">
        <h5>Section</h5>
        <ul class="nav flex-column">
          <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">Home</a></li>
          <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">Features</a></li>
          <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">Pricing</a></li>
          <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">FAQs</a></li>
          <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">About</a></li>
        </ul>
      </div>

      <div class="col mb-3">
        <h5>Section</h5>
        <ul class="nav flex-column">
          <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">Home</a></li>
          <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">Features</a></li>
          <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">Pricing</a></li>
          <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">FAQs</a></li>
          <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">About</a></li>
        </ul>
      </div>

      <div class="col mb-3">
        <h5>Section</h5>
        <ul class="nav flex-column">
          <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">Home</a></li>
          <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">Features</a></li>
          <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">Pricing</a></li>
          <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">FAQs</a></li>
          <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">About</a></li>
        </ul>
      </div>
    </footer>
  </div>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-ENjdO4Dr2bkBIFxQpeoTz1HIcje39Wm4jDKdf19U8gI4ddQ3GYNS7NTKfAdVQSZe"
    crossorigin="anonymous"></script>
</body>

</html>
