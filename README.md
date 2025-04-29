<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>jquery</title>
    
    <link rel="stylesheet" href="https://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.css" />
    <script src="https://code.jquery.com/jquery-1.11.1.min.js"></script>
    <script src="https://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.js"></script>
</head>
<body>
    <!----home-->
    <div data-role="page" id="home">
        <div data-role="header">
            <h1>Sinhgad college of engineering</h1>
            <h4>hgfygljbgulhskvghn,sdfghjlk</h4>
        </div>

        <div data-role="navbar" data-grid="c">
            <ul>
            <li><a href="#home" class="ui-btn-active">Home</a></li>
            <li><a href="#about">about</a></li>
            <li><a href="#dept">dept</a></li>
            <li><a href="#contact">contact</a></li>
            </ul>
        </div>

        <!------content----->

        <div data-role="content">
            <h3>Welcome to skn</h3>
            <p>NAAC Accredited With Grade-"A+"
                Center of Excellence for Best institution in Western Zone
                Center of Excellence for Best institution in Maharashtra and
                Certificate of merit for Third Best institution in India
                (ref.: http://www.thehrclub.net) 2014
            </p>
        </div>

        <div data-role="content">
            <h3 style="color: green;">Mission</h3>
            <P>“Holistic development of students and teachers in what we believe in and work for. We strive to achieve this by imbibing a unique value system, transparent work culture, excellent academic and physical environment conducive to learning, creativity and technology transfer. Our mandate is to generate, preserve and share knowledge for developing a vibrant society”.</P>
        </div>

        <div data-role="content">
            <h3>Vision</h3>
            <p>We are committed to produce not only good engineers but good human beings, also.</p>
        </div>


        <div data-role="footer">
            <h3>Quick links</h3>
            <center>
                <a href="#home">home</a></br>
                <a href="#about">about</a></br>
                <a href="#dept">department</a></br>
                <a href="#contact">contact</a></br>
            </center>
        </div>
    </div>



    <!----about-->
    <div data-role="page" id="about">
        <div data-role="header">
            <h1>Sinhgad college of engineering</h1>
            <h4>hgfygljbgulhskvghn,sdfghjlk</h4>
        </div>

        <div data-role="navbar" data-grid="c">
            <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about" class="ui-btn-active">about</a></li>
            <li><a href="#dept">dept</a></li>
            <li><a href="#contact">contact</a></li>
            </ul>
        </div>

        <!------content----->

        <div data-role="content">
            <div class="row">
                <img src="image1.jpeg" width="40%" height="250">
                <img src="image2.jpeg" width="40%" height="250">
            </div>
            
        </div>


        <div data-role="footer">
            <h3>Quick links</h3>
            <center>
                <a href="#home">home</a></br>
                <a href="#about">about</a></br>
                <a href="#dept">department</a></br>
                <a href="#contact">contact</a></br>
            </center>
        </div>
    </div>



<!----Dept-->
<div data-role="page" id="dept">
    <div data-role="header">
        <h1>Sinhgad college of engineering</h1>
        <h4>hgfygljbgulhskvghn,sdfghjlk</h4>
    </div>

    <div data-role="navbar" data-grid="c">
        <ul>
        <li><a href="#home" >Home</a></li>
        <li><a href="#about">about</a></li>
        <li><a href="#dept" class="ui-btn-active">dept</a></li>
        <li><a href="#contact">contact</a></li>
        </ul>
    </div>
    

    <!------content----->

    <div data-role="content">
        <div dat-role="listview">
           <li><a href="#">Computer </a></li>
           <li><a href="#">Mech </a></li>
           <li><a href="#">Information (IT) </a></li>
           <li><a href="#">Civil </a></li>
           <li><a href="#">Entc </a></li>
        </div>
        </div>
    


    <div data-role="footer" >
        <h3>Quick links</h3>
        <center>
            <a href="#home">home</a></br>
            <a href="#about">about</a></br>
            <a href="#dept">department</a></br>
            <a href="#contact">contact</a></br>
        </center>
    </div>
</div>


<!---Contact--->
<div data-role="page" id="contact">
    <div data-role="header">
        <h1>Sinhgad college of engineering</h1>
        <h4>hgfygljbgulhskvghn,sdfghjlk</h4>
    </div>

    <div data-role="navbar" data-grid="c">
        <ul>
        <li><a href="#home" >Home</a></li>
        <li><a href="#about">about</a></li>
        <li><a href="#dept">dept</a></li>
        <li><a href="#contact" class="ui-btn-active">contact</a></li>
        </ul>
    </div>
    

    <!------content----->

    <div data-role="content">
        <label for="text-basic">Name:</label>
        <input type="text" name="text-basic" id="text-basic" value="">

        <label for="text-basic">email:</label>
         <input type="text" name="text-basic" id="text-basic" value="">

         <label for="text-basic">Address:</label>
<input type="text" name="text-basic" id="text-basic" value="">
          
<label for="text-basic">contact:</label>
<input type="text" name="text-basic" id="text-basic" value="">

              <button class="u1-btn-active">submit</button>
        
    </div>


    <div data-role="footer">
        <h3>Quick links</h3>
        <center>
            <a href="#home">home</a></br>
            <a href="#about">about</a></br>
            <a href="#dept">department</a></br>
            <a href="#contact">contact</a></br>
        </center>
    </div>
</div>

</body>
</html>
