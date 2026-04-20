<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>Challenge_NIM Lengkap Anda</title>
</head>
<body>

    <h1>Challenge_NIM Lengkap</h1>

    <table border="1" style="border-collapse: collapse; text-align: left;" cellpadding="5">
        <tr>
            <th colspan="3" style="background-color: #FFA500; text-align: center;">Daftar Buku</th>
        </tr>
        <tr>
            <td rowspan="3" style="text-align: center;">
                <img src="buku.jpg" alt="Buku Web Programming" width="120">
            </td>
            <td>judul</td>
            <td>: Web Programming</td>
        </tr>
        <tr>
            <td>harga</td>
            <td>: Rp. 245.000,00</td>
        </tr>
        <tr>
            <td>pengarang</td>
            <td>: John Dean</td>
        </tr>
    </table>

    <br>
    
    <p><b>Isilah formulih dibawah ini</b></p>

    <form>
        <table border="0" cellpadding="3">
            <tr>
                <td>Nama:</td>
                <td><input type="text" placeholder="Nama Kamu"></td>
            </tr>
            <tr>
                <td>Password:</td>
                <td><input type="password"></td>
            </tr>
            <tr>
                <td>Jenis Kelamin:</td>
                <td>
                    <input type="radio" name="gender" id="laki" checked>
                    <label for="laki">Laki - Laki</label>
                    
                    <input type="radio" name="gender" id="perempuan">
                    <label for="perempuan">Perempuan</label>
                </td>
            </tr>
            <tr>
                <td>Hobi:</td>
                <td>
                    <input type="checkbox" id="membaca">
                    <label for="membaca">Membaca Buku</label>
                    
                    <input type="checkbox" id="menulis" checked>
                    <label for="menulis">Menulis</label>
                    
                    <input type="checkbox" id="memancing">
                    <label for="memancing">Memancing</label>
                </td>
            </tr>
            <tr>
                <td>Asal Kota:</td>
                <td>
                    <select name="kota">
                        <option value="Semarang">Semarang</option>
                        <option value="Yogyakarta">Yogyakarta</option>
                        <option value="Jakarta">Jakarta</option>
                    </select>
                </td>
            </tr>
            <tr>
                <td style="vertical-align: top;">Komentar Anda:</td>
                <td>
                    <textarea rows="4" cols="30">Silahkan katakan isi&#10;hati anda</textarea>
                </td>
            </tr>
        </table>
        
        <br>
        <input type="button" value="Mulai Proses!">
    </form>

</body>
</html>
