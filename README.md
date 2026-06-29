body{
margin:0;
font-family:Arial;
background:#f5f0e1;
color:#333;
}

header{
background:#5c4033;
color:white;
padding:20px;
text-align:center;
}

nav a{
color:white;
text-decoration:none;
margin:10px;
font-weight:bold;
}

.banner{
background:url("https://images.unsplash.com/photo-1500382017468-9049fed747ef") center/cover;
height:400px;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
color:white;
text-shadow:2px 2px 5px black;
}

section{
padding:40px;
}

h2{
color:#2e6b2e;
}

.contadores{
display:flex;
justify-content:space-around;
background:#d8c3a5;
text-align:center;
}

.contadores h3{
font-size:45px;
color:#2e6b2e;
}

.galeria{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:15px;
}

.galeria img{
width:100%;
height:220px;
object-fit:cover;
border-radius:10px;
}

footer{
background:#5c4033;
color:white;
text-align:center;
padding:20px;
}
