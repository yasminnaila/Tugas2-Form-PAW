<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="description" content="Praktikum modul 2">
    <title>Form Registrasi</title>
    <style>
        fieldset {
            margin-bottom: 20px;
            border: 1px solid black;
        }


        legend {
            font-size: 1.2em;

        }

        h1 {
            font-size: 2em;
        }

        .label-container {
            display: flex;
            justify-content: flex-start;
            align-items: center;
            margin-bottom: 5px;
        }

        .label-container label {
            display: inline-block;
            width: 200px;
            text-align: left;
        }

        .label-container span {
            display: inline-block;
            width: 5px;
        }

        .gender label,
        .skills label {
            display: inline-block;
            width: auto;
        }

        input[type="text"],
        input[type="email"],
        input[type="password"],
        input[type="url"],
        textarea {
            width: 200px;
        }

        .buttons {
            margin-top: 20px;
        }

        input[type="submit"],
        input[type="reset"],
        input[type="button"] {
            margin-right: 1px;
        }

    </style>
</head>

<body>
    <h1>Form Registrasi</h1>
    <form>
        <fieldset>
            <legend>Biodata</legend>
            <div class="label-container">
                <label for="nama">Nama Mahasiswa</label>
                <span>:</span>
                <input type="text" id="nama" name="nama" placeholder="Nama Anda">
            </div>

            <div class="label-container">
                <label for="nim">No Induk Mahasiswa (NIM)</label>
                <span>:</span>
                <input type="text" id="nim" name="nim" value="123456789">
            </div>

            <div class="label-container">
                <label for="alamat">Alamat Mahasiswa</label>
                <span>:</span>
                <textarea id="alamat" name="alamat" rows="4" placeholder="Alamat Anda"></textarea>
            </div>

            <div class="label-container">
                <label for="tanggal-lahir">Tanggal Lahir</label>
                <span>:</span>
                <select id="tanggal-lahir" name="tanggal-lahir">
                <option value="01">01</option>
                <option value="02">02</option>
                <option value="03">03</option>
                <option value="04">04</option>
                <option value="05">05</option>
                <option value="06">06</option>
                <option value="07">07</option>
                <option value="08">08</option>
                <option value="09">09</option>
                <option value="10">10</option>
                <option value="11">11</option>
                <option value="12">12</option>
                <option value="13">13</option>
                <option value="14">14</option>
                <option value="15">15</option>
                <option value="16">16</option>
                <option value="17">17</option>
                <option value="18">18</option>
                <option value="19">19</option>
                <option value="20">20</option>
                <option value="21">21</option>
                <option value="22">22</option>
                <option value="23">23</option>
                <option value="24">24</option>
                <option value="25">25</option>
                <option value="26">26</option>
                <option value="27">27</option>
                <option value="28">28</option>
                <option value="29">29</option>
                <option value="30">30</option>
                <option value="31">31</option>

                    <!-- Add more date options here -->
                </select>
                <select id="bulan-lahir" name="bulan-lahir">
                    <option value="Januari">Januari</option>
                    <option value="Februari">Februari</option>
                    <option value="Maret">Maret</option>
                    <option value="April">April</option>
                    <option value="Mei">Mei</option>
                    <option value="Juni">Juni</option>
                    <option value="Juli">Juli</option>
                    <option value="Agustus">Agustus</option>
                    <option value="September">September</option>
                    <option value="Oktober">Oktober</option>
                    <option value="November">November</option>
                    <option value="Dsember">Desember</option>
                   

                    <!-- Add more month options here -->
                </select>
                <select id="tahun-lahir" name="tahun-lahir">
                    <option value="1990">1990</option>
                    <option value="1991">1991</option>
                    <option value="1992">1992</option>
                    <option value="1993">1993</option>
                    <option value="1994">1994</option>
                    <option value="1995">1995</option>
                    <option value="1996">1996</option>
                    <option value="1997">1997</option>
                    <option value="1998">1998</option>
                    <option value="1999">1999</option>
                    <option value="2000">2000</option>
                    <option value="2001">2001</option>
                    <option value="2002">2002</option>
                    <option value="2003">2003</option>
                    <option value="2004">2004</option>
                    <option value="2005">2005</option>
                    <option value="2006">2006</option>
                    <option value="2007">2007</option>
                    <option value="2008">2008</option>
                    <option value="2009">2009</option>
                    <option value="2010">2010</option>
                    <option value="2011">2011</option>
                    <option value="2012">2012</option>
                    <option value="2013">2013</option>
                    <option value="2014">2014</option>
                    <option value="2015">2015</option>
                    <option value="2016">2016</option>
                    <option value="2017">2017</option>
                    <option value="2018">2018</option>
                    <option value="2019">2019</option>
                    <option value="2020">2020</option>
                    <option value="2020">2020</option>
                    <option value="2021">2021</option>
                    <option value="2022">2022</option>
                    <option value="2023">2023</option>
                    <option value="2024">2024</option>    
                </select><br>

                    <!-- Add more year options here -->
                </select>
            </div>

            <div class="label-container">
                <label>Jenis Kelamin</label>
                <span>:</span>
                <input type="radio" id="pria" name="jenis-kelamin" value="Pria">
                <label for="pria">Pria</label>
                <input type="radio" id="wanita" name="jenis-kelamin" value="Wanita">
                <label for="wanita">Wanita</label>
            </div>

            <div class="label-container">
                <label for="foto">Upload Foto</label>
                <span>:</span>
                <input type="file" id="foto" name="foto">
            </div>

            <div class="label-container">
                <label for="website">URL Website</label>
                <span>:</span>
                <input type="url" id="website" name="website" placeholder="URL Website Anda">
            </div>

            <div class="label-container">
                <label for="pt">Perguruan Tinggi</label>
                <span>:</span>
                <input type="text" id="pt" name="pt">
            </div>
        </fieldset>

        <fieldset>
            <legend>Info Akun</legend>
            <div class="label-container">
                <label for="email">Email</label>
                <span>:</span>
                <input type="email" id="email" name="email" placeholder="Email Anda">
            </div>

            <div class="label-container">
                <label for="username">Username</label>
                <span>:</span>
                <input type="text" id="username" name="username" placeholder="Username Anda">
            </div>

            <div class="label-container">
                <label for="password">Password</label>
                <span>:</span>
                <input type="password" id="password" name="password" placeholder="Password Anda">
            </div>

            <div class="label-container">
                <label for="ulang-password">Ulangi Password</label>
                <span>:</span>
                <input type="password" id="ulang-password" name="ulang-password" placeholder="Ulangi Password Anda">
            </div>
        </fieldset>

        <fieldset>
            <legend>Kemampuan Dasar</legend>
            <div class="skills">
                <input type="checkbox" id="html" name="skills" value="HTML">
                <label for="html">HTML</label>

                <input type="checkbox" id="css" name="skills" value="CSS">
                <label for="css">CSS</label>

                <input type="checkbox" id="javascript" name="skills" value="Javascript">
                <label for="javascript">Javascript</label>

                <input type="checkbox" id="php" name="skills" value="PHP">
                <label for="php">PHP</label>

                <input type="checkbox" id="mysql" name="skills" value="MySQL">
                <label for="mysql">MySQL</label>

                <input type="checkbox" id="laravel" name="skills" value="Laravel">
                <label for="laravel">Laravel</label>

                <input type="checkbox" id="react-native" name="skills" value="React Native">
                <label for="react-native">React Native</label>
            </div>
        </fieldset>

        <div class="buttons">
            <input type="reset" value="Reset">
            <input type="submit" value="Simpan">
            <input type="button" value="Button">
        </div>
    </form>
</body>

</html>
