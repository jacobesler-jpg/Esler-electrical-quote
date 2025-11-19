<!DOCTYPE html>  
<html lang="en">  
<head>  
    <meta charset="UTF-8">  
    <meta name="viewport" content="width=device-width, initial-scale=1.0">  
    <title>Esler Electrical - Get a Quote</title>  
    <style>  
        body {  
            font-family: Arial, sans-serif;  
            margin: 0;  
            padding: 20px;  
            background: #ffffff;  
            color: #000;  
        }  
        h1 {  
            text-align: center;  
            border-bottom: 2px solid #000;  
            padding-bottom: 10px;  
        }  
        form {  
            max-width: 500px;  
            margin: 0 auto;  
        }  
        input, textarea {  
            width: 100%;  
            padding: 12px;  
            margin: 10px 0;  
            border: 1px solid #000;  
            border-radius: 5px;  
            font-size: 16px;  
        }  
        button {  
            width: 100%;  
            padding: 14px;  
            background: #000;  
            color: #fff;  
            border: none;  
            border-radius: 5px;  
            font-size: 18px;  
            cursor: pointer;  
        }  
        button:hover {  
            opacity: 0.8;  
        }  
        .footer {  
            text-align: center;  
            margin-top: 20px;  
            font-size: 14px;  
            opacity: 0.7;  
        }  
    </style>  
</head>  
<body>  
  
<h1>Esler Electrical</h1>  
<p style="text-align:center;">Request a Quote</p>  
  
<form action="mailto:eslerelectrical@hotmail.com" method="POST" enctype="text/plain">  
    <label>Name</label>  
    <input type="text" name="Name" required>  
  
    <label>Email</label>  
    <input type="email" name="Email" required>  
  
    <label>Phone</label>  
    <input type="text" name="Phone" required>  
  
    <label>Job Details</label>  
    <textarea name="Job Details" rows="5" required></textarea>  
  
    <button type="submit">Send Quote Request</button>  
</form>  
  
<div class="footer">  
    © Esler Electrical – Geelong, Bellarine & Surf Coast  
</div>  
  
</body>  
</html>  
