#Showdown Star Plugin

##Usage

    var converter = new showdown.Converter({ extensions: ['star'] });
    var result = converter.makeHtml('<level1> <br/> <level1.5> <br/> <level3> <br/> <level3.5>');
    document.getElementById('show').innerHTML = result;
    
##ScreenShot    

![ScreenShot](./screenshot.jpg)
