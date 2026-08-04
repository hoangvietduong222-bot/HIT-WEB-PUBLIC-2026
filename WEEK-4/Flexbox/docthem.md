/* ==========================
   CARD
========================== */
.card{
    width:300px;
    background:white;
    padding:40px 25px;
    border-radius:20px;
    box-shadow:0 5px 15px rgba(0,0,0,0.2);

    /* Hiệu ứng chuyển động mượt trong 0.3 giây */
    transition:0.3s;
}

/* ==========================
   ICON
========================== */
.icon{
    font-size:60px;
    color:#1f6fff;
    margin-bottom:25px;

    /* Đổi màu icon mượt */
    transition:0.3s;
}

/* ==========================
   BUTTON
========================== */
.btn{
    display:inline-block;
    padding:10px 28px;
    background:#1f6fff;
    color:white;
    text-decoration:none;
    border-radius:8px;

    /* Đổi màu nút mượt */
    transition:0.3s;
}

/* ===================================================
   Khi đưa chuột vào CARD thì thực hiện các hiệu ứng
=================================================== */
.card:hover{

    /* Đổi màu nền card */
    background:#eaf3ff;

    /* Card nhấc lên trên 8px */
    transform:translateY(-8px);
}

/* Khi chuột ở trên CARD thì ICON bên trong đổi màu */
.card:hover .icon{
    color:#ff6600;
}

/* Khi chuột ở trên CARD thì BUTTON bên trong đổi màu */
.card:hover .btn{
    background:#ff6600;
}