<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Sederhana</title>
</head>
<body>
    <header>
        <h1>Kelas Konsep Bahasa Pemrograman</h1>
        <hr>
    </header>

    <section>
        <h2>Foto Sedang Di Kelas</h2>
        <img src="kelas KBP.jpg" alt="Inspirasi" width="300">

    </section>

    <section>
        <h2>Formulir</h2>
        <form action="#" method="post">
            <label for="name">Nama:</label><br>
            <input type="text" id="name" name="name" placeholder="Masukkan Nama Anda" required><br>

            <label for="NIM">NIM:</label><br>
            <input type="text" id="NIM" name="NIM" placeholder="Masukkan NIM Anda" required><br>

            <label for="message">Komentar:</label><br>
            <input type="text" id="message" name="message" placeholder="Tulis Komentar Anda" required><br>

            <button type="submit">Kirim</button>
        </form>
    </section>

    <section>
        <h2>Materi Belajar</h2>
        <table border="1">
            <thead>
                <tr>
                    <th>No</th>
                    <th>Materi</th>
                    <th>Jadwal</th>
                    <th>Tempat</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>1</td>
                    <td>Praktikum PHP</td>
                    <td>Kamis Jam 08:50 - 10:35</td>
                    <td>Lab RPL</td>
                </tr>
                <tr>
                    <td>2</td>
                    <td>Praktikum Javascript</td>
                    <td>Kamis Jam 08:50 - 10:35</td>
                    <td>Lab RPL</td>
                </tr>
                <tr>
                    <td>3</td>
                    <td>Membuat Website Dasar</td>
                    <td>Kamis Jam 08:50 - 10:35</td>
                    <td>Lab RPL</td>
                </tr>
            </tbody>
        </table>
    </section>
</body>
</html>

