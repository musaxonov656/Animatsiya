<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Animatsiya</title>
    <style>
        /* CSS animatsiya uchun stil */
        @keyframes example {
            0%   { transform: translateY(0); }
            25%  { transform: translateY(-20px); }
            50%  { transform: translateY(0); }
            75%  { transform: translateY(20px); }
            100% { transform: translateY(0); }
        }

        /* Element uchun animatsiya stilini tanlash */
        .animated {
            animation: example 2s infinite ease-in-out;
            color: darkblue;     
            font-family: Arial, sans-serif; 
            text-align: center;    
            margin-top: 100px;     
        }

        /* Body uchun orqa fon qo‘shamiz */
        body {
            background: linear-gradient(135deg, #89f7fe, #66a6ff);
            height: 100vh;
            margin: 0;
            display: flex;
            align-items: center;
            justify-content: center;
        }
    </style>
</head>
<body>

    <h2 class="animated">QO'TOQQA  QARASOSSANMI</h2>

</body>
</html>
# Animatsiya
