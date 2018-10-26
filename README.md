 

<html>
<h1><img src="https://cdn.pbrd.co/images/HKbWC0P.png" alt="Encode logo" title="Encode Logo" style="float:right" width="160">   Welcome to encode!</h1> 
</html>

# Design aspect
 
<html>


<body>

<table style="width:100%">
  
  <tr>
    <td> <font size="10">01 </td>    
    <td>Allows users to either copy the code into the text box provided on the homescreen or upload their code as a file.</td>    
  </tr>
 
  <tr>
    <td><font size="10">02</td>   
    <td>	If a user wants a personalized experience, the user can in this case login to save all the uploaded code and have a look at 				their coding profile and history of logins.
    </td>    
  </tr>
  
  <tr>
    <td><font size="10"><strike>03</strike></td>     
    <td> <strike>Allows users to include header files/packages/modules from the internet on the go if not present in our environment.</strike>
    </td>    
  </tr>
  
  <tr>
    <td><font size="10">04</td>    
    <td>Monetizes the platform to keep the servers alive by displaying advertisements on the right panel of the screen.
    </td>    
  </tr>
  
</table>

</body>
</html>


 

# Layout of the website

Layout of the website would be very simple and minimal. On the client side their would only be a couple of web pages, which  
include one for uploading code and input, second one would be for analysing and comparing the result. If the user is logged in then two additional screens would be there., one for login history and other for submission history. On each and every page of the website the right panel would contain advertisements and the panel at the bottom would contain contact info, site search, and social networks button. On server side the server environment would allow compilation of programs/code. The server will also maintain the login history and visitor count.

## Screenshots

### Homepage
![Encode Online Judge Home page](https://cdn.pbrd.co/images/HK5SJV6.png)
### Statistics
![Encode Online Judge Statistics page](https://cdn.pbrd.co/images/HK5Tp5K.png)

## Steps to get started

This application is designed for windows server.
Then for each language supported by the compiler you have to link the php file to your local compiler. To accomplish this task you can follow these steps:

 1. You should have the compiler for the desired languge on your local server machine.
 2. Then in the environment variables in to **"path"**  variable add the path to the compiler.
 3. In this last step, you should in the php file corresponding to the desired language you should  assign the variable **"putenv"** the path of the compiler in your local server machine.

> For example for C/C++ you have to follow these steps: The windows
> server should have **[MinGW](http://bit.ly/2O6hbNt)** installed (or can
> be downloaded
> [here](http://bit.ly/2ArXcoI)
> with all its packages. Then open the directory in which the MinGW is
> installed, open bin folder and copy this directory path (which should
> be `...\MinGW\bin`) Add this path to the environment variable `path`
> on the local server machine. Similarly in the compilers folder of the
> project and in the `c.php` file to the variable putenv assign the path
> (`...\MinGW\bin`). `putenv("PATH=...\MinGW\bin")`
<html>
<h2> License and copyright</h2>
Copyright &copy; 2018 <a href="http://bit.ly/2Ji3kmj" title="Go to my profile" target="_blank">Priyansh Saxena</a> Licensed under <a href="https://github.com/llcodeAlphall/EncodeOJ/blob/master/LICENSE" target="_blank" title="View complete licensing information"><b>GNU Lesser General Public License version 2.1 (LGPL-2.1)</b></a>
</html>
