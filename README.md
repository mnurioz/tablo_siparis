<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

    <style>
        table,tr,th,td{
            margin: 20px;
            padding: 12px;
            text-align: center;
            border: 0px solid black;
            border-radius: 5px;            
        }

        .nando{
            background-color: lightgreen;
            text-shadow: 1px;
        }

        .kc{
            background-color: hwb(165 37% 27% / 0.904);
        }

        .no{
            background-color: aqua;
        }
    
        .sln{
            background-color: gray;
        }

        .nu{
            background-color: lightgrey;
        }

    </style>
</head>
<body>

    <table>
        <tr class="no">
            <th>Sipariş Tarihi</th>
            <th>Sipariş Numarası</th>
            <th>Sipariş Adedi</th>
            <th>Sipariş Durumu</th>
            <th>İsim Soyisim</th>
            <th>Adres</th>
            <th>Kargo Durumu</th>
        </tr>

        <tr class="sln">
            <td>12.10.2023</td>
            <td class="kc">587411</td>
            <td>5</td>
            <td>Gönderildi</td>
            <td>KadirCan Tüfek</td>
            <td>İstanbul</td>
            <td class="nando">Teslim Edildi</td>
        </tr>

        <tr class="sln">
            <td>12.10.2023</td>
            <td class="kc">354589</td>
            <td>2</td>
            <td>Gönderildi</td>
            <td>KadirCan Tüfek</td>
            <td>İstanbul</td>
            <td class="nando">Teslim Edildi</td>
        </tr>

        <tr class="nu">
            <td>15.10.2023</td>
            <td class="kc">558421</td>
            <td>3</td>
            <td>Gönderildi</td>
            <td>Nuri ÖZ</td>
            <td>Bursa</td>
            <td class="nando">Teslim Edildi</td>
        </tr>

        <tr class="nu">
            <td>15.10.2023</td>
            <td class="kc">128421</td>
            <td>1</td>
            <td>Gönderildi</td>
            <td>Nuri ÖZ</td>
            <td>Bursa</td>
            <td class="nando">Teslim Edildi</td>
        </tr>

        <tr class="nu">
            <td>15.10.2023</td>
            <td class="kc">564861</td>
            <td>7</td>
            <td>Gönderildi</td>
            <td>Nuri ÖZ</td>
            <td>Bursa</td>
            <td class="nando">Teslim Edildi</td>
        </tr>
    </table>
    
</body>
</html>
