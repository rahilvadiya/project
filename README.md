<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>batton</title>
    <style>
        .container{
            border: 2px solid red;
            background-color: rgb(244, 234, 122);
            padding: 34px;
            margin: 34px auto;
            width: 666px;
        }
        a{
            /* text-decoration: none; */
        }
        a:hover{
                                      
            background-color: #190074;
        }
        a:visited{
           background-color: yellow ;
        }
        a:active{
            background-color:brown ;
        }   
        .btn{
            background-color: #7441de;
            color: black;
            padding: 6px;
            border: none;
            cursor: pointer;
            border-radius: 4px;
            font-size: 13px;
            font-family:Georgia, 'Times New Roman', Times, serif;
        }
       
    </style>
</head>
<body>
    <div class="container" id="con1">
        <h3>This is my heading</h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatum, ad sint magnam labore deserunt pariatur tenetur, eaque amet illum ea voluptatibus vitae? Voluptates, a commodi! Incidunt voluptatibus vel ea accusantium accusamus dicta ad qui?</p>
        <a href="http://facebook.com" class="btn">Red more</a>
        <button class="btn">Submit</button>
    </div>
</body>
</html>
