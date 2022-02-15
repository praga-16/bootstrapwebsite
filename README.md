# Web Design using Bootstrap Framework

## AIM:
To design a website using bootstrap framework.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using bootstrap grid system.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :
### home Page HTML :
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home Page:Bureau of Police Research And Development</title>
    <link rel="icon" href="./img/logobprd.png" type="image/x-icon" />
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous">
    </script>
    <link href="https://fonts.googleapis.com/css?family=Open+Sans:300,300i,400,400i,600,600i,700,700i|Raleway:300,300i,400,400i,500,500i,600,600i,700,700i|Poppins:300,300i,400,400i,500,500i,600,600i,700,700i" rel="stylesheet">
</head>
<body>
    <div class="container-fluid bg-light text-black text-center mt-3 mb-3">
        <img src="title.png"  class="img-fluid" style="width:100%; height:200px;" alt="BPR&D">
    </div>
    <div class="row">
        <div class="col mt-3 mb-3" style="background-color:#e6f9ff">
            <!-- ======= Left Side icons ======= -->
            <a class="rounded-circle float-start mt-1 mb-1"  href="https://twitter.com/bprdindia?lang=en" target="_blank">
                <img src="twitter.png" style="width:30px;height:30px" alt="Twitter">
            </a>
            <a class="rounded-circle float-start mt-1 mb-1"  href="https://www.facebook.com/officialBPRDIndia" target="_blank">
                <img src="facebook.png" style="width:30px;height:30px" alt="Facebook">
            </a>
            <a class="rounded-circle float-start mt-1 mb-1"  href="https://www.youtube.com/channel/UCGhrg_cnnGuhwXfCU16kYow" target="_blank">
                <img src="yt.png" style="width:30px;height:30px" alt="Youtube">
            </a>
            <a class="rounded-circle float-start mt-1 mb-1"  href="https://www.instagram.com/bprdindia/" target="_blank">
                <img src="insta.png" style="width:30px;height:30px" alt="Instagram">
            </a>

            <!-- ======= Right Side icons ======= -->
            <a class="rounded float-end ms-1 me-1" href="https://rashtragaan.in/" target="_blank"> 
                <img src="02.png" alt="SingtheNationalAnthem"  style="width:150PX; height:30px;">
            </a>
            <a class="rounded float-end mt-1 mb-1 ms-1 me-1" href="https://eustad.in" target="_blank"> 
                <img src="inpo.png" alt="e-Ustad" style="width:150PX; height:30px;">
            </a>
            <a class="rounded float-end mt-1 mb-1 ms-1 me-1" href="https://bprd.nic.in/SmartPolice1.aspx" target="_blank"> 
                <img src="04.png" alt="DataOnPoliceOrganization" style="width:150PX; height:30px;">
            </a>
            <a class="rounded float-end mt-1 mb-1 ms-1 me-1" href="https://www.youtube.com/channel/UCN2fiHd5IFWtNyu-vpAkeEA/videos" target="_blank"> 
                <img src="01.png" alt="PoliceAurSeva" style="width:150PX; height:30px;">
            </a>
        </div>
    </div>

    </div>

    <!-- ======= Navigation Tabs ======= -->
    <ul class="nav nav-tabs nav-justified">
        <li class="nav-item">
          <a class="nav-link active" href="#">Home</a>
        </li>
        <li class="nav-item">
            <div class="dropdown">
                <button type="button" class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">
                    About Us 
                </button>           
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="About-us-Evolution.html">Evolution Of BPR&D</a></li>
                    <li><hr class="dropdown-divider"></hr></li>
                    <li><a class="dropdown-item" href="#">Awards/Medals</a></li>
                    <li><hr class="dropdown-divider"></hr></li>
                    <li><a class="dropdown-item" href="#">Work Allocation</a></li>
                    <li><hr class="dropdown-divider"></hr></li>
                    <div class="dropdown dropend">
                        <button type="button" class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">
                            Organization 
                        </button>
                    <ul class="dropdown-menu">
                        <li><a class="dropdown-item" href="#">Organization chart</a></li>
                        <li><hr class="dropdown-divider"></hr></li>
                        <li><a class="dropdown-item" href="#">Division and Responsibilities</a></li>
                        <li><hr class="dropdown-divider"></hr></li>
                    </ul>
                    </div>
                    <div class="dropdown dropend">
                        <button type="button" class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">
                            Draft Legislation 
                        </button>
                        <ul class="dropdown-menu">
                            <li><a class="dropdown-item" href="#">Draft Model Police Bill</a></li>
                            <li><hr class="dropdown-divider"></hr></li>
                            <li><a class="dropdown-item" href="#">Draft Legislation On Mutual Legal Assisstance In Cr</a></li>
                            <li><hr class="dropdown-divider"></hr></li>
                        </ul>
                    </div>
                    <li><a class="dropdown-item" href="#">Contact US</a></li>
                    <li><hr class="dropdown-divider"></hr></li>
                    <li><a class="dropdown-item" href="#">Citizen's Corner</a></li>
                </ul>
            </div>
        </li>
        <li class="nav-item">
            <div class="dropdown">
                <button type="button" class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">
                    Training
                </button>
            </div>
        </li>
        <li class="nav-item">
            <div class="dropdown">
                <button type="button" class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">
                    Research & CA
                </button>
            </div>
        </li>
        <li class="nav-item">
            <div class="dropdown">
                <button type="button" class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">
                    NPM
                </button>
            </div>
        </li>
        <li class="nav-item">
            <div class="dropdown">
                <button type="button" class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">
                    SPD
                </button>
            </div>
        </li>
        <li class="nav-item">
            <div class="dropdown">
                <button type="button" class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">
                    Admin
                </button>
            </div>
        </li>
        <li class="nav-item">
            <div class="dropdown">
                <button type="button" class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">
                    SPC
                </button>
            </div>
        </li>
        <li class="nav-item">
            <div class="dropdown">
                <button type="button" class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">
                    SP Conf. & Police Expo
                </button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="">Photo Gallery Police Expo 2020</a></li>
                    <li><hr class="dropdown-divider"></hr></li>
                </ul>
            </div>
        </li>
        <li class="nav-item">
            <div class="dropdown">
                <button type="button" class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">
                    Gallery 
                </button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="">Photo Gallery</a></li>
                    <li><hr class="dropdown-divider"></hr></li>
                </ul>
            </div>
        </li>
        <li class="nav-item">
            <div class="dropdown">
                <button type="button" class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">
                    Publications/Reports
                </button>
            </div>
        </li>
        <li class="nav-item">
            <div class="dropdown">
                <button type="button" class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">
                   DOPO
                </button>
            </div>
        </li>
    </ul>
    <div class="container-fluid mt-2 mb-2 ms-2 me-2" style="background-color:#dfdfdf;">
        <div class="row">
            <div class="col-sm-3 mt-2">
                <ul class="nav nav-tabs nav-justified" style="background-color:#cccccc; font-size:larger;">
                    <li class="nav-item">
                      <a class="nav-link active" href="#">News and Events</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Press Release</a>
                    </li>
                </ul>
                <div class="container-fluid rounded bg-light p-2 mt-2 mb-2" >
                    <div class="container rounded mt-2 mb-2 border" style="background-color:  #e6f9ff; font-size:larger;">
                        <div class="container mt-2">
                            <a href="#" class="link-dark ">&#8641; Bureau Darpan</a>
                        </div>
                        <div class="container mt-2">
                            <a href="#" class="link-dark ">&#8641;Invitation of application for the paid Internship Programme at BPR&D for the year 2022-23</a>
                        </div>
                        <div class="container mt-2">
                            <a href="#" class="link-dark ">&#8641; Data on Police Organization </a>
                        </div>
                        <div class="container mt-2">
                            <a href="#" class="link-dark ">&#8641; Yoga at Workplace</a>
                        </div>
                        <div class="container mt-2">
                            <a href="#" class="link-dark ">&#8641; General Rules of AIPDM</a>
                        </div>
                        <div class="container mt-2">
                            <a href="#" class="link-dark">&#8641; Police Aur Seva</a>
                        </div>
                        <div class="container mt-2">
                            <a href="#" class="link-dark ">&#8641; Investigative Workflow Manual on Cyber Harassment Cases</a>
                        </div>
                    </div>
                </div>
                <div class="container-fluid rounded border bg-light text-center p-2 mt-2 mb-2" style="height: 300px;" >
                    <nav class="navbar navbar-expand-sm bg-light ">
                        <div class="container-fluid">
                          <ul class="navbar-nav">
                            <li class="nav-item">
                              <a class="nav-link active" href="#">Media Gallery</a>
                            </li>
                        </div>
                    </nav>
                    <ul class="nav nav-tabs justify-content-center">
                        <li class="nav-item">
                            <div class="dropdown">
                                <button type="button" class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">
                                    Years
                                </button>           
                                <ul class="dropdown-menu">
                                    <li><a class="dropdown-item" href="">Archives 2000-2010</a></li>
                                    <li><hr class="dropdown-divider"></hr></li>
                                    <li><a class="dropdown-item" href="#">Archives 2011-2019</a></li>
                                    <li><hr class="dropdown-divider"></hr></li>
                                    <li><a class="dropdown-item" href="#">Archives 2020-2021</a></li>
                                    <li><hr class="dropdown-divider"></hr></li>
                                    <li><a class="dropdown-item" href="#">2022</a></li>
                                    <li><hr class="dropdown-divider"></hr></li>
                                </ul>
                            </div>
                        </li>
                    </ul>
                </div>
            </div>
            <div class="col-sm-6 mt-2">
                <!-- Carousel -->
                <div id="demo" class="carousel slide" data-bs-ride="carousel">
                    <!-- Indicators/dots -->
                    <div class="carousel-indicators">
                        <button type="button" data-bs-target="#demo" data-bs-slide-to="0" class="active"></button>
                        <button type="button" data-bs-target="#demo" data-bs-slide-to="1"></button>
                        <button type="button" data-bs-target="#demo" data-bs-slide-to="2"></button>
                    </div>
  
                     <!-- The slideshow/carousel -->
                    <div class="carousel-inner">
                        <div class="carousel-item active">
                            <img src="homepic.png" alt="img1" class="rounded d-block w-100">
                        </div>
                        <div class="carousel-item">
                            <img src="homepic3.png" alt="img2" class="rounded d-block w-100">
                        </div>
                        <div class="carousel-item">
                            <img src="homepic2.png" alt="img3" class="rounded d-block w-100">
                        </div>
                    </div>
  
                    <!-- Left and right controls/icons -->
                    <button class="carousel-control-prev" type="button" data-bs-target="#demo" data-bs-slide="prev">
                        <span class="carousel-control-prev-icon"></span>
                    </button>
                    <button class="carousel-control-next" type="button" data-bs-target="#demo" data-bs-slide="next">
                        <span class="carousel-control-next-icon"></span>
                    </button>
                </div>
                <div class="container-fluid rounded bg-light mt-2 mb-2 p-2">
                    <div class="container">
                        <h4><u>What's New:</u></h4>
                    </div>
                    <div class="container rounded mt-2 mb-2 border" style="background-color:#e6f9ff;">
                        <div class="container mt-2">
                            <a href="#" class="link-dark">&#8641; Directory of Prison Officials in India</a>
                        </div>
                        <div class="container mt-2">
                            <a href="#" class="link-dark">&#8641; WOMEN'S SAFETY & SECURITY A handbook for First Responders and Investigators in the Police</a>
                        </div>
                        <div class="container mt-2">
                            <a href="#" class="link-dark">&#8641; Proceedings of the Webinar on Woman Safety with Sensitivity (Research & Correctional Admin Division)</a>
                        </div>
                        <div class="container mt-2">
                            <a href="#" class="link-dark">&#8641; National Police Research Repository, Golden Jubilee Edition, Volume II (2016-2020) (Research & Correctional Admin Division)</a>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-sm-3 mt-2">
                <div class="container-fluid rounded bg-light mt-2 mb-2 p-2">
                    <div class="container-fluid bg-light text-black text-center mt-3 mb-3">
                        <img src="dgb.png" class="img-fluid rounded" style="width:100%; height:400px;" alt="BPR&D">
                    </div>
                    <h6 style="text-align: center;">"Good Policing cannot be perceived without t....</h6><br>
                    <a href="General-message.html" class="link-primary float-end">&#8649;View more</a><br>
                    <div class="container-fluid rounded bg-light mt-2 mb-2 p-2"></div>
                        <h6 style="text-align: center;">BALAJI SRIVASTAVA, IPS Director General, BPR&D</h6><br>
                        <a href="#" class="link-primary float-center">Click here for Archive Messages</a>
                    </div>
                    <div class="container-fluid rounded mt-2 mb-2 p-2" style="background-color: #f2f2f2;">
                        <h5 class="float-center mt-4" style="text-align: center; font: 1em sans-serif; font-size: larger;">Smart Policing</h5><br>
                    </div>
                </div>
            </div>
        </div>
        <!-- ======= Footer ======= -->
        <footer id="footer">
            <div class="container-fluid text-center rounded bg-light p-2">
                <div class="copyright">
                    &copy; Copyright <strong><span>BPRD</span></strong>. All Rights Reserved
                </div>
                <div class="credits">
                    Designed by <a href="https://bootstrapmade.com/"> HARSHAVARDHINI M</a>
                </div>
            </div>
        </footer>
    </div>
</body>
</html>
~~~
### Home Page Extension :
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bureau of Police Research And Development</title>
    <link rel="icon" href="./img/logobprd.png" type="image/x-icon" />
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous">
    </script>
    <link href="https://fonts.googleapis.com/css?family=Open+Sans:300,300i,400,400i,600,600i,700,700i|Raleway:300,300i,400,400i,500,500i,600,600i,700,700i|Poppins:300,300i,400,400i,500,500i,600,600i,700,700i" rel="stylesheet">
</head>
<body>
    <div class="container-fluid bg-light text-black text-center mt-3 mb-3">
        <img src="title.png" class="img-fluid" style="width:101%; height:300px;" alt="BPR&D">
    </div>
    <div class="row">
        <div class="col mt-3 mb-3" style="background-color:#cecece">
            <!-- ======= Left Side icons ======= -->
            <a class="rounded-circle float-start mt-1 mb-1"  href="https://twitter.com/bprdindia?lang=en" target="_blank">
                <img src="twitter.png" style="width:30px;height:30px" alt="Twitter">
            </a>
            <a class="rounded-circle float-start mt-1 mb-1"  href="https://www.facebook.com/officialBPRDIndia" target="_blank">
                <img src="facebook.png" style="width:30px;height:30px" alt="Facebook">
            </a>
            <a class="rounded-circle float-start mt-1 mb-1"  href="https://www.youtube.com/channel/UCGhrg_cnnGuhwXfCU16kYow" target="_blank">
                <img src="yt.png" style="width:30px;height:30px" alt="Youtube">
            </a>
            <a class="rounded-circle float-start mt-1 mb-1"  href="https://www.instagram.com/bprdindia/" target="_blank">
                <img src="insta.png" style="width:30px;height:30px" alt="Instagram">
            </a>

            <!-- ======= Right Side icons ======= -->
            <a class="rounded float-end ms-1 me-1" href="https://rashtragaan.in/" target="_blank"> 
                <img src="02.png" alt="SingtheNationalAnthem"  style="width:150PX; height:30px;">
            </a>
            <a class="rounded float-end mt-1 mb-1 ms-1 me-1" href="https://eustad.in" target="_blank"> 
                <img src="inpo.png" alt="e-Ustad" style="width:150PX; height:30px;">
            </a>
            <a class="rounded float-end mt-1 mb-1 ms-1 me-1" href="https://bprd.nic.in/SmartPolice1.aspx" target="_blank"> 
                <img src="04.png" alt="DataOnPoliceOrganization" style="width:150PX; height:30px;">
            </a>
            <a class="rounded float-end mt-1 mb-1 ms-1 me-1" href="https://www.youtube.com/channel/UCN2fiHd5IFWtNyu-vpAkeEA/videos" target="_blank"> 
                <img src="01.png" alt="PoliceAurSeva" style="width:150PX; height:30px;">
            </a>
        </div>
    </div>

    <!-- ======= Navigation Tabs ======= -->
    <ul class="nav nav-tabs nav-justified">
        <li class="nav-item">
          <a class="nav-link active" href="homepage.html">Home>DGP</a>
        </li>
        <li class="nav-item">
            <div class="dropdown">
                <button type="button" class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">
                    About Us 
                </button>           
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="About-us-Evolution.html">Evolution Of BPR&D</a></li>
                    <li><hr class="dropdown-divider"></hr></li>
                    <li><a class="dropdown-item" href="#">Awards/Medals</a></li>
                    <li><hr class="dropdown-divider"></hr></li>
                    <li><a class="dropdown-item" href="#">Work Allocation</a></li>
                    <li><hr class="dropdown-divider"></hr></li>
                    <div class="dropdown dropend">
                        <button type="button" class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">
                            Organization 
                        </button>
                    <ul class="dropdown-menu">
                        <li><a class="dropdown-item" href="#">Organization chart</a></li>
                        <li><hr class="dropdown-divider"></hr></li>
                        <li><a class="dropdown-item" href="#">Division and Responsibilities</a></li>
                        <li><hr class="dropdown-divider"></hr></li>
                    </ul>
                    </div>
                    <div class="dropdown dropend">
                        <button type="button" class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">
                            Draft Legislation 
                        </button>
                        <ul class="dropdown-menu">
                            <li><a class="dropdown-item" href="#">Draft Model Police Bill</a></li>
                            <li><hr class="dropdown-divider"></hr></li>
                            <li><a class="dropdown-item" href="#">Draft Legislation On Mutual Legal Assisstance In Cr</a></li>
                            <li><hr class="dropdown-divider"></hr></li>
                        </ul>
                    </div>
                    <li><a class="dropdown-item" href="#">Contact US</a></li>
                    <li><hr class="dropdown-divider"></hr></li>
                    <li><a class="dropdown-item" href="#">Citizen's Corner</a></li>
                </ul>
            </div>
        </li>
        <li class="nav-item">
            <div class="dropdown">
                <button type="button" class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">
                    Training
                </button>
            </div>
        </li>
        <li class="nav-item">
            <div class="dropdown">
                <button type="button" class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">
                    Research & CA
                </button>
            </div>
        </li>
        <li class="nav-item">
            <div class="dropdown">
                <button type="button" class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">
                    NPM
                </button>
            </div>
        </li>
        <li class="nav-item">
            <div class="dropdown">
                <button type="button" class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">
                    SPD
                </button>
            </div>
        </li>
        <li class="nav-item">
            <div class="dropdown">
                <button type="button" class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">
                    Admin
                </button>
            </div>
        </li>
        <li class="nav-item">
            <div class="dropdown">
                <button type="button" class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">
                    SPC
                </button>
            </div>
        </li>
        <li class="nav-item">
            <div class="dropdown">
                <button type="button" class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">
                    SP Conf. & Police Expo
                </button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="">Photo Gallery Police Expo 2020</a></li>
                    <li><hr class="dropdown-divider"></hr></li>
                </ul>
            </div>
        </li>
        <li class="nav-item">
            <div class="dropdown">
                <button type="button" class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">
                    Gallery 
                </button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="">Photo Gallery</a></li>
                    <li><hr class="dropdown-divider"></hr></li>
                </ul>
            </div>
        </li>
        <li class="nav-item">
            <div class="dropdown">
                <button type="button" class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">
                    Publications/Reports
                </button>
            </div>

        </li>
        <li class="nav-item">
            <div class="dropdown">
                <button type="button" class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">
                   DOPO
                </button>
            </div>
        </li>
    </ul>
    <div class="container-fluid mt-2 mb-2 ms-2 me-2" style="background-color:#cecece;">
        <div class="row">
            <div class="col-sm-5 mt-2 mb-2">
                <img src="./dgb.png" class="img rounded float-end" style="width:490px; height:610px;" alt="BPR&D">
            </div>
            <div class="col-sm-6 mt-2 mb-2 me-2">
                <table class="table">
                    <thead>
                      <tr>
                        <th style="font-size: larger;">Message from Director General</th>
                      </tr>
                    </thead>
                </table>
                <table class="table">
                    <thead>
                        <tr>
                            <th style="font-size:medium;">Hon’ble Union Home Minister and Minister of Cooperation Shri Amit Shah ji said this on the eve of the 50th anniversary of the BPR&D.
                                As we enter the 51st year, our endeavour will be to redefine policing with cutting edge research. The mandate of the BPR&D has provided meaningful space for all stakeholders in policing and correctional administration. The collective wisdom of the practitioners, the academia and the civil society has culminated in inputs for policy imperatives in policing and prisons. The verticals of the BPR&D on Research, Modernization, Capacity Building and the National Police Missions have contributed substantially in studying problems and defining solutions by Promoting Good Practices and Standards.<br>
                                For the millions of citizens, the police station is the temple of justice. They come to a police station with the confidence that it will deliver them justice. In many ways, it is the highest court of justice for the voiceless. Our promise to them is we will do everything in our endeavour to reform and modernise policing through research that will help policy makers transform Indian police system into World’s leading modern police.<br>
                                We recognise that policing is fast evolving. Today, the police has to deal not only with traditional crime but modern day cyber crime and state sponsored terrorism. This has significantly increased the risks and responsibilities of the uniformed men and women on the streets. At the BPR&D, our efforts will be to provide our frontline defenders of national security with skill, knowledge and tools that enable them to serve our national interest better.<br>
                                We also recognise that investing in our uniformed men and women is the surest way to serve better and speedy
                                justice to our citizens. Empowering our police force means empowering our citizens and nation.<br>
                            
                                Transformation starts at home. As the team leader of the BPR&D family, my humble efforts will be to facilitate a thriving working environment for us to come up with the best practices that befit a modern day police.<br>
                            
                                I call upon my colleagues from all rank and file to join me in this nation building endeavour.
                            </th>
                        </tr>
                    </thead>
                </table>
                <p class="float-end" style="font-size: large;">BALAJI SRIVASTAVA, IPS DG BPR&D</p>
            </div>
        </div>
    </div>
    <!-- ======= Footer ======= -->
    <footer id="footer">
        <div class="container-fluid rounded bg-light p-2 text-center">
            <div class="copyright">
                &copy; Copyright <strong><span>BPRD</span></strong>. All Rights Reserved
            </div>
            <div class="credits">
                Designed by <a href="https://bootstrapmade.com/"> HARSHAVARDHINI M</a>
            </div>
        </div>

    </footer>
</body>
</html>
~~~
### About Us Page HTML :
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bureau of Police Research And Development</title>
    <link rel="icon" href="./img/logobprd.png" type="image/x-icon" />
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous">
    </script>
    <link href="https://fonts.googleapis.com/css?family=Open+Sans:300,300i,400,400i,600,600i,700,700i|Raleway:300,300i,400,400i,500,500i,600,600i,700,700i|Poppins:300,300i,400,400i,500,500i,600,600i,700,700i" rel="stylesheet">
</head>
<body>
    <div class="container-fluid bg-light text-black text-center mt-3 mb-3">
        <img src="title.png" class="img-fluid" style="width:100%; height:200px;" alt="BPR&D">
    </div>
    <div class="row">
        <div class="col mt-3 mb-3" style="background-color:#e6f9ff">
           <!-- ======= Left Side icons ======= -->
           <a class="rounded-circle float-start mt-1 mb-1"  href="https://twitter.com/bprdindia?lang=en" target="_blank">
            <img src="twitter.png" style="width:30px;height:30px" alt="Twitter">
            </a>
            <a class="rounded-circle float-start mt-1 mb-1"  href="https://www.facebook.com/officialBPRDIndia" target="_blank">
            <img src="facebook.png" style="width:30px;height:30px" alt="Facebook">
            </a>
            <a class="rounded-circle float-start mt-1 mb-1"  href="https://www.youtube.com/channel/UCGhrg_cnnGuhwXfCU16kYow" target="_blank">
            <img src="yt.png" style="width:30px;height:30px" alt="Youtube">
            </a>
            <a class="rounded-circle float-start mt-1 mb-1"  href="https://www.instagram.com/bprdindia/" target="_blank">
            <img src="insta.png" style="width:30px;height:30px" alt="Instagram">
            </a>

            <!-- ======= Right Side icons ======= -->
            <a class="rounded float-end ms-1 me-1" href="https://rashtragaan.in/" target="_blank"> 
            <img src="02.png" alt="SingtheNationalAnthem"  style="width:150PX; height:30px;">
            </a>
            <a class="rounded float-end mt-1 mb-1 ms-1 me-1" href="https://eustad.in" target="_blank"> 
            <img src="inpo.png" alt="e-Ustad" style="width:150PX; height:30px;">
            </a>
            <a class="rounded float-end mt-1 mb-1 ms-1 me-1" href="https://bprd.nic.in/SmartPolice1.aspx" target="_blank"> 
            <img src="04.png" alt="DataOnPoliceOrganization" style="width:150PX; height:30px;">
            </a>
            <a class="rounded float-end mt-1 mb-1 ms-1 me-1" href="https://www.youtube.com/channel/UCN2fiHd5IFWtNyu-vpAkeEA/videos" target="_blank"> 
            <img src="01.png" alt="PoliceAurSeva" style="width:150PX; height:30px;">
            </a>
        </div>
    </div>
</div>
    </div>

    <!-- ======= Navigation Tabs ======= -->
    <ul class="nav nav-tabs nav-justified">
        <li class="nav-item">
          <a class="nav-link" href="homepage.html">Home</a>
        </li>
        <li class="nav-item active">
            <div class="dropdown">
                <button type="button" class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">
                    About Us >> Evolution 
                </button>           
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item active" href="#">Evolution Of BPR&D</a></li>
                    <li><hr class="dropdown-divider"></hr></li>
                    <li><a class="dropdown-item" href="#">Awards/Medals</a></li>
                    <li><hr class="dropdown-divider"></hr></li>
                    <li><a class="dropdown-item" href="#">Work Allocation</a></li>
                    <li><hr class="dropdown-divider"></hr></li>
                    <div class="dropdown dropend">
                        <button type="button" class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">
                            Organization 
                        </button>
                    <ul class="dropdown-menu">
                        <li><a class="dropdown-item" href="#">Organization chart</a></li>
                        <li><hr class="dropdown-divider"></hr></li>
                        <li><a class="dropdown-item" href="#">Division and Responsibilities</a></li>
                        <li><hr class="dropdown-divider"></hr></li>
                    </ul>
                    </div>
                    <div class="dropdown dropend">
                        <button type="button" class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">
                            Draft Legislation 
                        </button>
                        <ul class="dropdown-menu">
                            <li><a class="dropdown-item" href="#">Draft Model Police Bill</a></li>
                            <li><hr class="dropdown-divider"></hr></li>
                            <li><a class="dropdown-item" href="#">Draft Legislation On Mutual Legal Assisstance In Cr</a></li>
                            <li><hr class="dropdown-divider"></hr></li>
                        </ul>
                    </div>
                    <li><a class="dropdown-item" href="#">Contact US</a></li>
                    <li><hr class="dropdown-divider"></hr></li>
                    <li><a class="dropdown-item" href="#">Citizen's Corner</a></li>
                </ul>
            </div>
        </li>
        <li class="nav-item">
            <div class="dropdown">
                <button type="button" class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">
                    Training
                </button>
            </div>
        </li>
        <li class="nav-item">
            <div class="dropdown">
                <button type="button" class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">
                    Research & CA
                </button>
            </div>
        </li>
        <li class="nav-item">
            <div class="dropdown">
                <button type="button" class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">
                    NPM
                </button>
            </div>
        </li>
        <li class="nav-item">
            <div class="dropdown">
                <button type="button" class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">
                    SPD
                </button>
            </div>
        </li>
        <li class="nav-item">
            <div class="dropdown">
                <button type="button" class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">
                    Admin
                </button>
            </div>
        </li>
        <li class="nav-item">
            <div class="dropdown">
                <button type="button" class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">
                    SPC
                </button>
            </div>
        </li>
        <li class="nav-item">
            <div class="dropdown">
                <button type="button" class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">
                    SP Conf. & Police Expo
                </button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="">Photo Gallery Police Expo 2020</a></li>
                    <li><hr class="dropdown-divider"></hr></li>
                </ul>
            </div>
        </li>
        <li class="nav-item">
            <div class="dropdown">
                <button type="button" class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">
                    Gallery 
                </button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="">Photo Gallery</a></li>
                    <li><hr class="dropdown-divider"></hr></li>
                </ul>
            </div>
        </li>
        <li class="nav-item">
            <div class="dropdown">
                <button type="button" class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">
                    Publications/Reports
                </button>
            </div>
        </li>
        <li class="nav-item">
            <div class="dropdown">
                <button type="button" class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown">
                   DOPO
                </button>
            </div>
        </li>
    </ul>
    <div class="container-fluid mt-2 mb-2 ms-2 me-2" style="background-color:#dbdbdb;">
        <div class="row">
            <div class="col-sm mt-2 mb-2 me-2 ms-2 text-center">
                <table class="table text-center">
                    <thead>
                      <tr>
                        <th style="font-size: larger;">Evolution of the BPR&D</th>
                      </tr>
                    </thead>
                </table>
                <table class="table text-center">
                    <thead>
                        <tr>
                            <th style="font-size:medium; font: 1em sans-serif;"><strong>CREATION</strong><br>
                                1. The Government of India vied Resolution No.8/136/68-P.I (Pers.I) dated 28.08.1970 formally 
                                established the Bureau of Police Research and Development (BPR&D), under the Ministry of Home 
                                Affairs giving a new orientation to then existing Police Research and Advisory Council (1966) 
                                for the following reasons and with the primary objective of modernization of police force:<br>

                                1.    To take direct and active interest in the issues<br>

                                2.    To promote a speedy and systematic study of the police problems<br>

                                3.    To apply science and technology in the methods and techniques used by police.<br>

                                In addition and as a secondary, the Resolution mandated an advisory role also for the Bureau.<br>
                                2. The Bureau was established with the following two divisions initially with a well laid out charter
                                 of duties<br>
                                1.    Research, Statistics and Publication<br>
                                2.    Development<br>
                                3. Training is a vital and growing requirement to improve the competency of police forces in the country.
                                 The Gore-Committee (1971) set up by the Government of India studied the training aspects of police and gave
                                  several recommendations. The government of India in accepting its recommendations created a Training Division
                                   (1973) in addition to the two divisions already existing to function under the Bureau.<br>
                                4. The forensic science services uncompromising & Geese under the Development Division grew over 
                                a period and a separate Directorate of Forensic Sciences under the BPR&D came into existence in 1983.<br>
                                5. Further in 1995 Government of India decided to entrust issues relating to Correctional Administration 
                                Work to the BPR&D so that problems relating to prisons and implementation of deemed prison reforms can be
                                 taken up by the Bureau in a cohesive manner. This set up is operating out of the existing manpower resources.<br>
                                 6. During the year 2008, the Government of India further decided to create National Police Mission under the 
                                 administrative control of BPR&D to transform the police forces in the country into effective instrument for 
                                 maintenance of internal security and facing the challenges in future, by equipping them with the necessary 
                                 material, intellectual and organizational resources.<br>
                            </th>
                        </tr>
                    </thead>
                </table>
                <table class="table text-center">
                    <thead>
                        <tr>
                            <th style="font-size:medium; font: 1em sans-serif;"><strong>SEPARATION</strong><br>
                                1.    Though the Institute of Criminology and Forensic Science (ICFS) was established under 
                                the overall supervision and guidance of BPR&D as part of the same exercise, it was allowed to 
                                function as a separate entity in 1976; since the ultimate objective of setting up the Institute 
                                was to develop a full-fledged academic institution for furthering studies in Criminology and 
                                forensic science. The same which has been re-christened in the year 1991 is now functioning as 
                                Lok Nayak Jai Prakash Narayan (LNJN), National Institute of Criminology and Forensic Science 
                                from 1982. The institute provides training courses for officers of the criminal justice system 
                                in the two subjects i.e. Criminology and Forensic Science and carries out research.<br>
                                2.    Growth dynamics took over and the need to specialize in each area arose. The National 
                                Police Commission (1977) also recommended certain measures requiring implementation. Simultaneously,
                                 technological innovations particularly computers held promises of support to many areas of crime 
                                 control and crime detection besides processing statistical data for the purpose of analysis. 
                                 The Government of India, therefore, decided to establish a National Crime Records Bureau in 1986 
                                 build another Resolution and entrusted statistics and publications work of the Research Division 
                                 to the newly constituted Bureau along with the plans for their computerization.<br>
                                 3.    In an identical move brought about by compulsions of growth, the Government of India decided 
                                 to give an independent status to the Forensic Science Division by creating a Forensic Science 
                                 Directorate having an autonomous status under the direct control of the Ministry of Home Affairs.<br>
                            </th>
                        </tr>
                    </thead>
                </table>
                <p class="float-end" style="font-size: large;"> Last Updated On: 03/01/2019</p>
            </div>
        </div>
    </div>
    <!-- ======= Footer ======= -->
    <footer id="footer">
        <div class="container-fluid rounded bg-light p-2 text-center">
            <div class="copyright">
                &copy; Copyright <strong><span>BPRD</span></strong>. All Rights Reserved
            </div>
            <div class="credits">
                Designed by <a href="https://bootstrapmade.com/">HARSHAVARDHINI M</a>
            </div>
        </div>
    </footer>
</body>
</html>
~~~



## OUTPUT:
### Home Page:
![doc](https://user-images.githubusercontent.com/93427208/153766200-976a6813-931b-4ec7-9ae8-b532a5cb67ed.png)

### Home Page bottom:
![doc](https://user-images.githubusercontent.com/93427208/153766208-8c7f4f2e-ece6-4cd0-ad51-46be2d8c61be.png)

### Home Page Extension:
![doc](https://user-images.githubusercontent.com/93427208/153766217-8cc6aa2e-68fd-4c97-a573-cf5092dec1f4.png)

### About us: 
![doc](https://user-images.githubusercontent.com/93427208/153766223-80c03fe0-2d6b-4d45-b23a-51a65e8fd70e.png)


## Result:
Thus a website is designed using bootstrap framework.

