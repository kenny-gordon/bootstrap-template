# bootstrap-template

Use this Template as a way to quickly start any new project.
All you get is this text and a mostly barebones HTML document.

**Contains:**

 - [Fontawesome](https://fontawesome.com/) **-** *5.5.0*
 - [jQuery](https://jquery.com/) **-** *3.3.1*
 - [Bootstrap.bundle.min](https://getbootstrap.com/) **-** *4.1.3*
	- *Including* **-** [popper.js](https://popper.js.org/) 
 - [Chart.bundle.min](https://www.chartjs.org/) **-** *2.7.3*
	- *Including* **-** [Moment.js](http://momentjs.com/)
	
  **Please Note!**
  
Many of the bootstrap 4 components require the use of JavaScript to function. 
Specifically, they require jQuery, Popper.js, and bootstrap 4's own JavaScript plugins. 
Place the following <script>s near the end of your pages, right before the closing </body> tag, to enable them. 
jQuery must come first, then Popper.js, and then the bootstrap 4 JavaScript plugins.
  
## Optional CDNs
~~~html
<!-- FontAwesome Core CSS -->
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.5.0/css/all.css" integrity="sha384-B4dIYHKNBt8Bc12p+WXckhzcICo0wtJAoU8YZTY5qE0Id1GSseTk6S+L3BlXeVIU" crossorigin="anonymous">

<!-- Bootstrap Core CSS -->
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
~~~~
~~~html
<!-- Bootstrap core JavaScript (Including jQuery dependency)
      ================================================== -->
<!-- Placed at the end of the document so the pages load faster -->

<!-- jQuery first, then Popper, then Bootstrap and Chart -->
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/2.7.3/Chart.bundle.min.js" integrity="sha256-MZo5XY1Ah7Z2Aui4/alkfeiq3CopMdV/bbkc/Sh41+s=" crossorigin="anonymous"></script>
~~~~

# Custom Theme Style sheet can be removed at discretion.
~~~html
  <!-- Custom CSS -->
  <link href="/assets/css/bootstrap.sleek.min.css" rel="stylesheet">
  <link href="/assets/css/main.css" rel="stylesheet">
~~~~

## Index.html

~~~html 
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="utf-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <!-- The above 3 meta tags *must* come first in the head; any other head content must come *after* these tags -->
  <meta name="description" content="">
  <meta name="keywords" content="">
  <meta name="author" content="">
  <title>Bootstrap Template</title>
  <link rel="shortcut icon" href="/assets/img/favicon/favicon.ico">

  <!-- FontAwesome core CSS -->
  <link href="/assets/vendor/fontawesome/css/all.css" rel="stylesheet">

  <!-- Bootstrap core CSS -->
  <link href="/assets/vendor/bootstrap/css/bootstrap.min.css" rel="stylesheet">

  <!-- Custom CSS -->
  <link href="/assets/css/bootstrap.sleek.min.css" rel="stylesheet">
  <link href="/assets/css/main.css" rel="stylesheet">

  <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
  <!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
  <!--[if lt IE 9]>
    <script src="https://oss.maxcdn.com/html5shiv/3.7.3/html5shiv.min.js"></script>
    <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
  <![endif]-->

</head>

<body>

  <!-- Header -->
  <header>
    <nav class="navbar navbar-expand-md fixed-top navbar-light bg-light">
      <a class="navbar-brand" href="#">
        <img src="/assets/img/brand/bootstrap-solid.svg" width="30" height="30" class="d-inline-block align-top" alt="Bootstrap">
        Bootstrap
      </a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarCollapse" aria-controls="navbarCollapse" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarCollapse">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item">
            <a class="nav-link active" href="#">Home<span class="sr-only">(current)</span></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Link</a>
          </li>
          <li class="nav-item">
            <a class="nav-link disabled" href="#">Disabled</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="http://example.com" id="dropdown" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">Dropdown</a>
            <div class="dropdown-menu" aria-labelledby="dropdown">
              <a class="dropdown-item" href="#">Action</a>
              <a class="dropdown-item" href="#">Another action</a>
              <a class="dropdown-item" href="#">Something else here</a>
            </div>
          </li>
        </ul>
        <form class="form-inline mt-2 mt-md-0">
          <input class="form-control mr-sm-2" type="text" placeholder="Search" aria-label="Search">
          <button class="btn btn-primary my-2 my-sm-0" type="submit"><i class="fas fa-search"></i> Search</button>
        </form>
      </div>
    </nav>
  </header>
  <!-- ./Header -->

  <!-- Main Content -->
  <main role="main" class="container">
    <div class="row">
      <div class="mx-auto text-center col-md-12">
        <div>
          <h1>Bootstrap starter template</h1>
          <p class="lead">Use this document as a way to quickly start any new project.<br> All you get is this text and a mostly barebones HTML document.</p>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col-md-3">
      </div>
      <div class="col-xs-12 col-md-6">
        <div class="w-50 py-3 mx-auto">
          <ul>
            <li><a href="https://fontawesome.com/">Fontawesome - 5.5.0</a></li>
            <li><a href="https://jquery.com/">jQuery - 3.3.1</a></li>
            <li><a href="https://getbootstrap.com/">Bootstrap.bundle.min - 4.1.3</a><br>Including - popper.js</li>
            <li><a href="https://www.chartjs.org/">Chart.bundle.min - 2.7.3</a><br>Including - Moment.js</li>
          </ul>
        </div>
      </div>
      <div class="col-md-3">
      </div>
    </div>
  </main>
  <!-- ./Main -->

  <!-- Footer -->
  <footer>
    <div class="footer bg-light">
      <div class="container">
        <div class="text-muted text-center">&#169; <script>
            document.write(new Date().getFullYear())

          </script> All rights reserved.<a class="text-green ml-2" href="http://www.example.com" target="_blank">www.example.com</a></div>
      </div>
    </div>
  </footer>
  <!-- ./Footer -->

  <!-- Bootstrap core JavaScript (Including jQuery dependency)
         ================================================== -->
  <!-- Placed at the end of the document so the pages load faster -->
  <script src="/assets/vendor/jquery/js/jquery-3.3.1.min.js"></script>
  <script src="/assets/vendor/charts/js/Chart.bundle.min.js"></script>
  <script src="/assets/vendor/bootstrap/js/bootstrap.bundle.min.js"></script>
  <script src="/assets/js/main.js"></script>

</body>

</html>

~~~~

