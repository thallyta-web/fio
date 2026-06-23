# fio
/*PÁGINA AGENDAMENTOS*/

/*BARRA DEPOIS DO BANNER*/
.barrainicio{
    background-color: #7B1D50;
    width: 100%;
    height: 60px;
}

/*CARD*/
.card-agendamentos{
    background-image: url(img/background.jpg);
    padding: 70px 70px 100px;
    border-left: 60px solid var(--rosa);
    border-right: 60px solid var(--rosa);
    align-items: center;
}


.card-agendamentos-conteudo {
    background-color: floralwhite;
    height: auto;
    width: 900px;
    margin: auto;
    padding: auto;
    text-align: center;
    align-items: center;
    border-radius: 5%;
    box-shadow: 0px 8px 15px 0px #C24585;
    animation: surgir 1.5s ease;
}

/*CONTEUDO DO CARD*/
#pag-agendamentos h1{
    font: 3rem "Itim", cursive;
    color: #5A331E;
    text-align: center;
    margin-top: 30px;
    margin-bottom: 30px;
}

#pag-agendamentos p{
  text-align: center;
  margin-bottom: 20px;  
}

form{
    width: 400px;
    margin: 0 auto;
}

input, select, textarea{
    width: 100%;
    height: 30px;
    margin-bottom: 10px;
    padding-left: 5px;
    box-sizing: border-box;
    border: 1px solid #C4C4C4;
    color: #777;
}

label, fieldset, input, select, textarea{
    font: 1rem "Istok Web", sans-serif;
}

fieldset{
   border: 1px solid #CCC;
   margin-bottom: 10px;
   padding: 10px;
}

#data-hora-num{
    display: flex;
}

input[type="radio"], input[type="checkbox"]{
    width: 15px;
    height: 15px;
    margin-left: 50px;
}

textarea{
    height: 80px;
}

#botoes-form{
    display: flex;
}

input[type="submit"],input[type="reset"]{
    margin: 20px;
    background-color: #8bc34a;
    color: #FFF;
    border: 0;
    border-radius: 5px;
}

input[type="reset"]{
    background-color: #F47E7E;
}