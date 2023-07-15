<!DOCTYPE html>
<html>
<head>
    <title>Plan Alimentar</title>
    <style>
        body {
            background-image: url('https://i.pinimg.com/originals/d2/5f/16/d25f1660d6909a7c82f3eb182573c36b.jpg');
            background-size: cover;
            background-position: center;
            font-family: "Courier New", Courier, monospace;
            color: rgba(255, 255, 255, 0.8);
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: rgba(0, 0, 0, 0.5);
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
        }
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid rgba(255, 255, 255, 0.5);
            padding: 8px;
            text-align: left;
        }
        th {
            background-color: rgba(242, 242, 242, 0.8);
        }
        h1 {
            text-align: center;
            font-size: 32px;
        }
        h2 {
            font-size: 24px;
            color: #f9ba32;
        }
        .motivation {
            margin-top: 10px;
            text-align: center;
            font-style: italic;
            color: #f9ba32;
        }
        .ziua1 {
            background-color: rgba(255, 0, 0, 0.2);
        }
        .ziua2 {
            background-color: rgba(0, 255, 0, 0.2);
        }
        .ziua3 {
            background-color: rgba(0, 0, 255, 0.2);
        }
        .ziua4 {
            background-color: rgba(255, 255, 0, 0.2);
        }
        .ziua5 {
            background-color: rgba(255, 0, 255, 0.2);
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Plan Alimentar</h1>
        <div class="motivation">
            <p>Mănâncă sănătos, trăiește sănătos!</p>
        </div>
        
        <h2>
            <button onclick="toggleContent('ziua1')">Ziua 1 (Luni)</button>
        </h2>
        <div id="ziua1" style="display: none;" class="ziua1">
            <table>
                <tr>
                    <th>Masă</th>
                    <th>Mâncare</th>
                    <th>Gramaj</th>
                </tr>
                <tr>
                    <td>Mic dejun</td>
                    <td>3 ouă întregi</td>
                    <td>215 g</td>
                </tr>
                <tr>
                    <td>Snack</td>
                    <td>Iaurt grecesc + semințe chia</td>
                    <td>150 g</td>
                </tr>
                <tr>
                    <td>Prânz</td>
                    <td>Piept de pui la grătar + orez integral/quinoa</td>
                    <td>150 g + 100 g</td>
                </tr>
                <tr>
                    <td>Snack</td>
                    <td>Nuci și migdale</td>
                    <td>30 g</td>
                </tr>
                <tr>
                    <td>Cină</td>
                    <td>Somon la cuptor + legume la cuptor</td>
                    <td>150 g + 200 g</td>
                </tr>
                <tr>
                    <td>Snack</td>
                    <td>Baton de proteine/proteină LC</td>
                    <td>-</td>
                </tr>
            </table>
        </div>
        
        <h2>
            <button onclick="toggleContent('ziua2')">Ziua 2 (Marți)</button>
        </h2>
        <div id="ziua2" style="display: none;" class="ziua2">
            <table>
                <tr>
                    <th>Masă</th>
                    <th>Mâncare</th>
                    <th>Gramaj</th>
                </tr>
                <tr>
                    <td>Mic dejun</td>
                    <td>Pâine integrală prăjită + unt de arahide</td>
                    <td>50 g + 30 g</td>
                </tr>
                <tr>
                    <td>Snack</td>
                    <td>Iaurt grecesc + semințe de in</td>
                    <td>150 g</td>
                </tr>
                <tr>
                    <td>Prânz</td>
                    <td>Piept de curcan la grătar/tofu</td>
                    <td>150 g</td>
                </tr>
                <tr>
                    <td>Snack</td>
                    <td>Semințe de dovleac/floarea-soarelui</td>
                    <td>30 g</td>
                </tr>
                <tr>
                    <td>Cină</td>
                    <td>Piept de pui la cuptor cu ierburi</td>
                    <td>150 g</td>
                </tr>
                <tr>
                    <td>Snack</td>
                    <td>Baton de proteine/proteină LC</td>
                    <td>-</td>
                </tr>
            </table>
        </div>
        
        <h2>
            <button onclick="toggleContent('ziua3')">Ziua 3 (Miercuri)</button>
        </h2>
        <div id="ziua3" style="display: none;" class="ziua3">
            <table>
                <tr>
                    <th>Masă</th>
                    <th>Mâncare</th>
                    <th>Gramaj</th>
                </tr>
                <tr>
                    <td>Mic dejun</td>
                    <td>Omletă cu legume și brânză</td>
                    <td>200 g</td>
                </tr>
                <tr>
                    <td>Snack</td>
                    <td>Iaurt grecesc + semințe de in</td>
                    <td>150 g</td>
                </tr>
                <tr>
                    <td>Prânz</td>
                    <td>Ton la grătar/tofu + salată de legume</td>
                    <td>150 g + 200 g</td>
                </tr>
                <tr>
                    <td>Snack</td>
                    <td>Mână de nuci</td>
                    <td>30 g</td>
                </tr>
                <tr>
                    <td>Cină</td>
                    <td>Cotlet de porc la cuptor + sparanghel/dovlecei</td>
                    <td>150 g + 200 g</td>
                </tr>
                <tr>
                    <td>Snack</td>
                    <td>Măr sau altă fructă proaspătă</td>
                    <td>-</td>
                </tr>
            </table>
        </div>
        
        <h2>
            <button onclick="toggleContent('ziua4')">Ziua 4 (Joi)</button>
        </h2>
        <div id="ziua4" style="display: none;" class="ziua4">
            <table>
                <tr>
                    <th>Masă</th>
                    <th>Mâncare</th>
                    <th>Gramaj</th>
                </tr>
                <tr>
                    <td>Mic dejun</td>
                    <td>3 ouă întregi</td>
                    <td>215 g</td>
                </tr>
                <tr>
                    <td>Snack</td>
                    <td>Iaurt grecesc + semințe chia</td>
                    <td>150 g</td>
                </tr>
                <tr>
                    <td>Prânz</td>
                    <td>Piept de pui la grătar + orez integral/quinoa</td>
                    <td>150 g + 100 g</td>
                </tr>
                <tr>
                    <td>Snack</td>
                    <td>Nuci și migdale</td>
                    <td>30 g</td>
                </tr>
                <tr>
                    <td>Cină</td>
                    <td>Somon la cuptor + legume la cuptor</td>
                    <td>150 g + 200 g</td>
                </tr>
                <tr>
                    <td>Snack</td>
                    <td>Baton de proteine/proteină LC</td>
                    <td>-</td>
                </tr>
            </table>
        </div>
        
        <h2>
            <button onclick="toggleContent('ziua5')">Ziua 5 (Vineri)</button>
        </h2>
        <div id="ziua5" style="display: none;" class="ziua5">
            <table>
                <tr>
                    <th>Masă</th>
                    <th>Mâncare</th>
                    <th>Gramaj</th>
                </tr>
                <tr>
                    <td>Mic dejun</td>
                    <td>Pâine integrală prăjită + unt de arahide</td>
                    <td>50 g + 30 g</td>
                </tr>
                <tr>
                    <td>Snack</td>
                    <td>Iaurt grecesc + semințe de in</td>
                    <td>150 g</td>
                </tr>
                <tr>
                    <td>Prânz</td>
                    <td>Piept de curcan la grătar/tofu</td>
                    <td>150 g</td>
                </tr>
                <tr>
                    <td>Snack</td>
                    <td>Semințe de dovleac/floarea-soarelui</td>
                    <td>30 g</td>
                </tr>
                <tr>
                    <td>Cină</td>
                    <td>Piept de pui la cuptor cu ierburi</td>
                    <td>150 g</td>
                </tr>
                <tr>
                    <td>Snack</td>
                    <td>Baton de proteine/proteină LC</td>
                    <td>-</td>
                </tr>
            </table>
        </div>
    </div>
    
    <script>
        function toggleContent(day) {
            var content = document.getElementById(day);
            if (content.style.display === "none") {
                content.style.display = "block";
            } else {
                content.style.display = "none";
            }
        }
    </script>
</body>
</html>
