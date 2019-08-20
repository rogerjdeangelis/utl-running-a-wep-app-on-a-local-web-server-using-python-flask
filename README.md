# utl-running-a-wep-app-on-a-local-web-server-using-python-flask
Running a wep app on a local web server using python flask
    Running a wep app on a local web server using python flask                                                    
                                                                                                                  
    This is the "heelo World" example from                                                                        
    https://pythonspot.com/flask-hello-world/                                                                     
                                                                                                                  
    github                                                                                                        
    https://tinyurl.com/y56znugn                                                                                  
    https://github.com/rogerjdeangelis/utl-running-a-wep-app-on-a-local-web-server-using-python-flask             
                                                                                                                  
    macros                                                                                                        
    https://tinyurl.com/y9nfugth                                                                                  
    https://github.com/rogerjdeangelis/utl-macros-used-in-many-of-rogerjdeangelis-repositories                    
                                                                                                                  
                                                                                                                  
    You need python 3                                                                                             
                                                                                                                  
    What can you do with Flask? (or full package DJANGO.                                                          
                                                                                                                  
    From blog applications to cloning facebook/twitter, almost everything is possible in Flask.                   
    There are many libraries like flask-sockets, flask-google-maps etc. where you can embed                       
    several features in your application. Flask supports MySQL, Postgresql, MongoDB and other                     
    few databases and based on the use case we need to choose the most suitable database.                         
                                                                                                                  
    *_                   _                                                                                        
    (_)_ __  _ __  _   _| |_                                                                                      
    | | '_ \| '_ \| | | | __|                                                                                     
    | | | | | |_) | |_| | |_                                                                                      
    |_|_| |_| .__/ \__,_|\__|                                                                                     
            |_|                                                                                                   
    ;                                                                                                             
                                                                                                                  
    open an administrator command window                                                                          
                                                                                                                  
    cd to where pip is instanned                                                                                  
                                                                                                                  
    cd  C:\Program Files\Python37\Scripts                                                                         
                                                                                                                  
    pip install flask                                                                                             
                                                                                                                  
    You also need macro from link above                                                                           
                                                                                                                  
    utl_submit_py64_37                                                                                            
                                                                                                                  
    %let hw="Hellow World";                                                                                       
                                                                                                                  
    *            _               _                                                                                
      ___  _   _| |_ _ __  _   _| |_                                                                              
     / _ \| | | | __| '_ \| | | | __|                                                                             
    | (_) | |_| | |_| |_) | |_| | |_                                                                              
     \___/ \__,_|\__| .__/ \__,_|\__|                                                                             
                    |_|                                                                                           
    ;                                                                                                             
                                                                                                                  
                                                                                                                  
     _____________________                                                                                        
    /                     \                                                                                       
    | localhost:5000      |                                                                                       
     -----------------------------------------------------------------                                            
     <- -> @  (localgost:5000                                         )                                           
               -------------------------------------------------------                                            
                                                                                                                  
       Hello World                                                                                                
                                                                                                                  
    *          _       _   _                                                                                      
     ___  ___ | |_   _| |_(_) ___  _ __                                                                           
    / __|/ _ \| | | | | __| |/ _ \| '_ \                                                                          
    \__ \ (_) | | |_| | |_| | (_) | | | |                                                                         
    |___/\___/|_|\__,_|\__|_|\___/|_| |_|                                                                         
                                                                                                                  
    ;                                                                                                             
                                                                                                                  
                                                                                                                  
    %let hw=Hello World!;                                                                                         
                                                                                                                  
    %utl_submit_py64_37("                                                                                         
    from flask import Flask;                                                                                      
    app = Flask(__name__);                                                                                        
    @app.route('/');                                                                                              
    def hello():;                                                                                                 
    .   return '&hw';                                                                                             
    if __name__ == '__main__':;                                                                                   
    .   app.run();                                                                                                
    ");                                                                                                           
                                                                                                                  
                                                                                                                  
    * your sas session will wait;                                                                                 
                                                                                                                  
    Open http://localhost:5000/ in your webbrowser, and “Hello World!” should appear.                             
                                                                                                                  
    To terminate 'hello world' type cntl-alt-delete and end the following task                                    
    c:/windows/sysyem21/cmd.exe                                                                                   
                                                                                                                  
    This will then appear in your SAS log                                                                         
                                                                                                                  
    * Serving Flask app "py_pgm" (lazy loading)                                                                   
    * Environment: production                                                                                     
      WARNING: This is a development server. Do not use it in a production deployment.                            
      Use a production WSGI server instead.                                                                       
    * Debug mode: off                                                                                             
                                                                                                                  
                                                                                                                  
                                                                                                                  
