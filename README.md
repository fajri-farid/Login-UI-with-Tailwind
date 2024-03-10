This project is where I learned about tailwind CSS and tried to slice UI from Figma to the website I made. 

Disini dalam penggunaan tailwind saya menggunakan cdn, bukan install tailwind pada code saya.


<h2>Problem</h2>
I have some problems and challenges in this project
<ol>
  <li>nggk tahu kenapa custom color di tailwind itu tidak bekerja, kek bg-[#32a852]. itunya tidak bekerja dan ketika saya coba besoknya ntah kenapa dia bisa.</li>
  <li>dicode ini saya menggunakan absolute dan ini berakibat ketika height layarnya kecil sehingga dia akan mengganggu bagian lain karena seperti namanya absolute dia akan tetap posisinya. </li>
  <img width="278" alt="image" src="https://github.com/fajri-farid/Login-UI-with-Tailwind/assets/139946709/fb9d034a-ee84-4b13-8469-c14aa9c43acd">
  <li>
    kenapa saya tidak bisa menggunakan <br>
  <p>
    
    <script src="https://cdn.tailwindcss.com"></script> 
  </p>
   sehingga saya cari solusi dan coba-coba dan akhirnya bisa pakai ini:
   <p>
    
     <link
      href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css"
      rel="stylesheet"
    />
  </p>
  </li> 
</ol>


<h2>What i learned</h2>
<ol>
  <li>Belajar menggunakan tailwind CSS</li>
  <li>
    Belajar beberapa hal baru seperti, ketika dia non-mobile version dia itu terdiri dari 2 kolom (kiri dan kanan). Kiri tempatnya tulisan tulisan dan kirinya itu lalu ketika dia mobile gambar akan diatas dan 
    tulisan-tulisan tadi berada dibawahnya. <br> 
    <h4>Non Mobile</h4>
    Yang mana dalam non-mobilenya saya menggunakan ini agar dia bisa terbagi dua
  <p>   
    
    class= md:grid md:grid col-2
  </p>
  lalu pada tiap pembungkus grid itu yang mana div nya image dan divnya tulisan-tulisan itu kutambahkan
  <p>

    order-1
    order-2
  </p>
  order-1 dia akan di kiri order-2 dia akan di kanan jadi dia nggk sesuai urutan code saya yang mana duluan image dulu baru tulisan-tulisan. yang tanpa order ini gambar akan di kiri dan tulisan-tulisan dia di kanan.
  <h4>Mobile</h4>
  lalu mobile itu sudah sesuai dengan code yang awalnya, gambar diawal tulisan kedua.
    
  </li>
  <li>Belajar menerapkan font dari <a href="https://fonts.google.com/"> google font </a></li>
</ol>

--- 
<h2>here is the preview</h2><br>
Desktop:
<img width="1280" alt="Screenshot 2024-03-10 105246" src="https://github.com/fajri-farid/Login-UI-with-Tailwind/assets/139946709/1de3023e-c081-424c-bd41-446e17ae89c7">

Mobile:
<br>
<img width="288" alt="Screenshot 2024-03-10 105622" src="https://github.com/fajri-farid/Login-UI-with-Tailwind/assets/139946709/9ff1a206-be43-406d-b7d1-f03c43dbc0b2">


