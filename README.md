# first
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <link rel="stylesheet" href="style.css">
        <title>My Web Page</title>
        <script type="text/javascript" src="first.js"></script>
        


    </head>
    <body>
        <form id="regForm" action="">

            <h1>Register:</h1>
            
            <!-- One "tab" for each step in the form: -->
            <div class="tab">Name:
              <p><input placeholder="First name..." oninput="this.className = ''"></p>
              <p><input placeholder="Last name..." oninput="this.className = ''"></p>
            </div>
            
            <div class="tab">Contact Info:
              <p><input placeholder="E-mail..." oninput="this.className = ''"></p>
              <p><input placeholder="Phone..." oninput="this.className = ''"></p>
            </div>
            
            <div class="tab">Birthday:
              <p><input placeholder="dd" oninput="this.className = ''"></p>
              <p><input placeholder="mm" oninput="this.className = ''"></p>
              <p><input placeholder="yyyy" oninput="this.className = ''"></p>
            </div>
            
      
            
            <div style="overflow:auto;">
              <div style="float:right;">
                <button type="button" id="prevBtn" onclick="nextPrev(-1)">Previous</button>
                <button type="button" id="nextBtn" onclick="nextPrev(1)">Next</button>
              </div>
            </div>
            
            <!-- Circles which indicates the steps of the form: -->
            <div style="text-align:center;margin-top:40px;">
              <span class="step"></span>
              <span class="step"></span>
              <span class="step"></span>
              <span class="step"></span>
            </div> 
            
            </form>
        <form name="contact" netlify>
            <p>
              <label>Name <input type="text" name="name" /></label>
            </p>
            <p>
              <label>Email <input type="email" name="email" /></label>
            </p>
            <p>
              <button type="submit">Signup</button>
            </p>
          </form>
       
    </body>

</html>
