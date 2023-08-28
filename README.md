body, h1, h2, p {
	margin: 0;
	padding: 0;
  }
  
  header {
	background-color: #333;
	color: white;
	text-align: center;
	padding: 20px 0;
  }
  
  header h1 {
	font-size: 35px;

  }
  
     
  .menu {
	display: flex;
	flex-flow: row wrap;
	justify-content: space-between;
	padding: 20px;
	margin:5px 0;


  }
  
.menu-items {
	width: 33%;
	margin-bottom: 10px;
	padding: 10px;
	padding-top: 0;
	background-color: #f7f7f7;
	border: 1px solid black;
	box-sizing: border-box;
	display: inline-block;
	flex: 1;
	transition: 0.3s;
	text-align: right;
  }


.menu-items2 {
	width: 33%;
	margin-bottom: 10px;
	margin-left: 0;
	padding: 10px;
	padding-top: 0;
	background-color: #f7f7f7;
	border: 1px solid black;
	box-sizing: border-box;
	display: inline-block;
	text-align: right;
  }


.menu-items3 {
	width: 33%;
	margin-bottom: 10px;
	padding: 10px;
	padding-top: 0;
	background-color: #f7f7f7;
	border: 1px solid black;
	box-sizing: border-box;
	display: inline-block;
	text-align: right;
  }

  
 .menuh2 {
	color: #f7f7f7;
	display:inline-block; 
	box-sizing: border-box;
	background-color: #e74c3c;
	border:1px solid black;

  }
  
.menuh22 {
	color: #f7f7f7;
	display:inline-block; 
	box-sizing: border-box;
	background-color: #ff309f;
	border:1px soli black;
}

.menuh23 {
	color: #f7f7f7;
	display:inline-block; 
	box-sizing: border-box;
	background-color: #7f95d1;
	border:1px solid black;
	
}



  .menu-items p {
	margin-top: 20px;
	text-align: center;

  }  

  .menu-items2 p {
	margin-top: 20px;
	text-align: center;
}

  .menu-items3 p {
	margin-top: 20px;
	text-align: center;
}
  
  @media screen and (max-width: 980px) {
	.menu-items {
	 flex-basis: 50%;
	}

    .menu-items2 {
    	flex-basis: 50%;
    }
	.menu-items3 {
		flex-basis: 100%;}

  @media screen and (max-width: 780px) {
  	.menu-items .menu-items2 .menu-items3{ 
  		flex-basis:100%;
  	 }
  }
	
  }
  
