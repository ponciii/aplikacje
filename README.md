<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Selektory CSS</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
div + p { 
	color:blue;
}
<div>
<p>Paragraph 1 in the div.</p>  
<p>Paragraph 2 in the div.</p>   
<section><p>Paragraph 3 in the div.</p></section>  
</div>
<p>Paragraph 4 not in the div.</p>   


</body>
</html>
