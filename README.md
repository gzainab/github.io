<!DOCTYPE html>
<html>
    <head>
        <title>CV ZAIN</title>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
        <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
        <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.5.0/css/all.css" integrity="sha384-B4dIYHKNBt8Bc12p+WXckhzcICo0wtJAoU8YZTY5qE0Id1GSseTk6S+L3BlXeVIU" crossorigin="anonymous">
        <style>
            body,
            h1,
            h2,
            h3,
            h4,
            h5,
            h6 {
                font-family: "Lato", sans-serif;
            }

            body,
            html {
                height: 100%;
                color: #777;
                line-height: 1.8;
            }

            /* Create a Parallax Effect */
            .bgimg-1,
            .bgimg-2,
            .bgimg-3 {
                background-attachment: fixed;
                background-position: center;
                background-repeat: no-repeat;
                background-size: cover;
            }

            /* First image (Logo. Full height) */
            .bgimg-1 {
                background-image: url('photo.png');
                min-height: 100%;
            }

            /* Second image (Portfolio) */
            .bgimg-2 {
                background-image: url("photo1.png");
                min-height: 400px;
            }

            /* Third image (Contact) */
            .bgimg-3 {
                background-image: url("https://www.w3schools.com/w3images/parallax3.jpg");
                min-height: 400px;
            }

            .w3-wide {
                letter-spacing: 10px;
            }

            .w3-hover-opacity {
                cursor: pointer;
            }

            /* Turn off parallax scrolling for tablets and phones */
            @media only screen and (max-device-width: 1600px) {

                .bgimg-1,
                .bgimg-2,
                .bgimg-3 {
                    background-attachment: scroll;
                    min-height: 400px;
                }
            }

        </style>
    </head>
<body>

    <!-- Navbar (sit on top) -->
    <div class="w3-top">
        <div class="w3-bar" id="myNavbar">
            <a class="w3-bar-item w3-button w3-hover-black w3-hide-medium w3-hide-large w3-right"
                href="javascript:void(0);" onclick="toggleFunction()" title="Toggle Navigation Menu">
                <i class="fa fa-bars"></i>
            </a>
            <a href="#home" class="w3-bar-item w3-button">HOME</a>
            <a href="#about" class="w3-bar-item w3-button w3-hide-small"><i class="fa fa-user"></i> A PROPOS</a>
            <a href="#experience" class="w3-bar-item w3-button w3-hide-small"><i class='fa fa-suitcase'></i> EXPERIENCES PROFESIONNELLES</a>
            <a href="#formations" class="w3-bar-item w3-button w3-hide-small"><i class='fas fa-book-open'></i> FORMATIONS</a>
            <a href="#portfolio" class="w3-bar-item w3-button w3-hide-small"><i class="fa fa-th"></i> PORTFOLIO</a>
            <a href="#contact" class="w3-bar-item w3-button w3-hide-small"><i class="fa fa-envelope"></i> CONTACT</a>
            </a>
        </div>

        <!-- Navbar on small screens -->
        <div id="navDemo" class="w3-bar-block w3-white w3-hide w3-hide-large w3-hide-medium">
            <a href="#about" class="w3-bar-item w3-button" onclick="toggleFunction()">A PROPOS</a>
            <a href="#experience" class="w3-bar-item w3-button" onclick="toggleFunction()">EXPERIENCES PROFESIONNELLES</a>
            <a href="#formations" class="w3-bar-item w3-button" onclick="toggleFunction()">FORMATIONS</a>            
            <a href="#portfolio" class="w3-bar-item w3-button" onclick="toggleFunction()">PORTFOLIO</a>
            <a href="#contact" class="w3-bar-item w3-button" onclick="toggleFunction()">CONTACT</a>
        </div>
    </div>

    <!-- First Parallax Image with Logo Text -->
    <div class="bgimg-1 w3-display-container w3-opacity-min" id="home">
        <div class="w3-display-middle" style="white-space:nowrap;">
            <span class="w3-center w3-padding-large w3-black w3-xlarge w3-wide w3-animate-opacity">ZAINABE<span
                    class="w3-hide-small"> GOULAMHOUSSEN</span> </span>
                    
        </div>
    </div>

    <!-- Container (About Section) -->
    <div class="w3-content w3-container w3-padding-64" id="about">
        <h2 style="text-align: center;"><span style="color: #ff0000; font-family: symbol;">A PROPOS DE MOI </span></h2><br>
        
<table style="width: 100%; border-collapse: collapse;" border="0">
	<tbody>
		<tr>
			<td style="width: 11.536%;"><img class="responsive" src="https://cvzain.w3spaces.com/profil.png" alt="" width="115" height="108" /></td>
			<td style="width: 67.764%;">
				<h5 style="text-align: center;"><span style="font-family: 'comic sans ms', sans-serif;">VOTRE ATOUT </span></h5>
				<h5 style="text-align: center;"><span style="font-family: 'comic sans ms', sans-serif;">COMMERCIAL / MARKETING&nbsp;</span></h5>
				<h5 style="text-align: center;"><span style="font-family: 'comic sans ms', sans-serif;">&nbsp; &nbsp;DISPONIBLE LE 03 OCTOBRE 2022</span></h5>
			</td>
			<td style="width: 20.6999%;">
				<h5 class="w3-large w3-margin-bottom" style="text-align: center;"><span style="font-family: 'comic sans ms', sans-serif;">&nbsp; &nbsp; &nbsp; &nbsp;</span></h5>
			</td>
		</tr>
	</tbody>
</table>
<p style="text-align: left;">Katie Holmes a dit<span style="font-family: verdana, geneva, sans-serif;"> <em>&laquo; Nous sommes tous des r&ecirc;veurs. Heureusement, les r&ecirc;ves deviennent parfois r&eacute;alit&eacute;. &raquo;</em>. </span></p>
<p style="text-align: left;">J'ai retenu cette citation car elle repr&eacute;sente parfaitement mon &eacute;tat d'esprit. Pour moi il est important de s'&eacute;panouir dans la vie et le meilleur moyen est de trouver <em>&laquo;&nbsp;un r&ecirc;ve&nbsp;&raquo;</em> qui nous passionne. <br /><br />23 ans, ambitieuse, d&eacute;termin&eacute;e et curieuse, je recherche toujours des moyens d'en apprendre plus. <br /><br />Finalisant mon master en Marketing, je suis &agrave; la recherche d'un poste dans le domaine du Commerce / Marketing&nbsp; en r&eacute;gion parisienne et banlieue proche.</p>
            </div>
        </div>
        <h2 style="text-align: center;"><span style="color: #ff0000; font-family: symbol;">COMPETENCES LINGUISTIQUES </span></h2>
        <p class="w3-wide">🇨🇵&nbsp;Français</p>
        <div class="w3-light-grey">
            <div class="w3-container w3-padding-small w3-dark-grey w3-center" style="width:100%">100%</div>
        </div>
        <p class="w3-wide">🇮🇳&nbsp;Gujarati</p>
        <div class="w3-light-grey">
            <div class="w3-container w3-padding-small w3-dark-grey w3-center" style="width:100%">100%</div>
        </div>
        <div>
	        <div>🇬🇧 Anglais(Score Toeic : 800)</div>
        </div>
        <div class="w3-light-grey">
            <div class="w3-container w3-padding-small w3-dark-grey w3-center" style="width:70%">70%</div>
        </div>
        <p class="w3-wide">🇲🇬Malgache</p>
        <div class="w3-light-grey">
            <div class="w3-container w3-padding-small w3-dark-grey w3-center" style="width:65%">65%</div>
        </div>
        <p class="w3-wide">🇪🇸Espagnol</p>
        <div class="w3-light-grey">
            <div class="w3-container w3-padding-small w3-dark-grey w3-center" style="width:60%">60%</div>
        </div> 
        <h2 style="text-align: center;"><span style="color: #ff0000; font-family: symbol;">AUTRES COMP&Eacute;TENCES</span></h2> 
<p>&nbsp;</p>
<table style="width: 100.001%; border-collapse: collapse; height: 161px;" border="0">
	<tbody>
		<tr style="height: 51px;">
			<td style="width: 63.968%; height: 51px;">
				<h3 style="text-align: center;">Logiciels Informatiques</h3>
			</td>
			<td style="width: 36.032%; height: 51px;">
				<h3 style="text-align: left;">Commerce</h3>
			</td>
		</tr>
		<tr style="height: 110px;">
			<td style="width: 63.968%; height: 110px;">
				<p style="padding-left: 30px; text-align: center;"><span style="font-family: 'book antiqua', palatino, serif;"><em>Microsoft Pack Office</em></span></p>
				<p style="padding-left: 30px; text-align: center;"><span style="font-family: 'book antiqua', palatino, serif;"><em>Renderforest</em></span></p>
				<p style="padding-left: 30px; text-align: center;"><span style="font-family: 'book antiqua', palatino, serif;"><em>Jimdo</em></span></p>
				<p style="padding-left: 30px; text-align: center;"><span style="font-family: 'book antiqua', palatino, serif;"><em>Xmind</em></span></p>
				<p style="padding-left: 30px; text-align: center;"><span style="font-family: 'book antiqua', palatino, serif;"><em>Instagram</em></span></p>
				<p style="padding-left: 30px; text-align: center;"><span style="font-family: 'book antiqua', palatino, serif;"><em>Photoshop</em></span></p>
				<p style="padding-left: 30px; text-align: center;"><span style="font-family: 'book antiqua', palatino, serif;"><em>Adobe Indesign</em></span></p>
				<p style="padding-left: 30px; text-align: center;"><span style="font-family: 'book antiqua', palatino, serif;"><em>Canva</em></span></p>
			</td>
			<td style="width: 36.032%; height: 110px;">
				<p style="text-align: left;"><span style="font-family: 'book antiqua', palatino, serif;"><em>N&eacute;gociation Internationale</em></span></p>
				<p style="text-align: left;"><span style="font-family: 'book antiqua', palatino, serif;"><em>Marketing</em></span></p>
				<p style="text-align: left;"><span style="font-family: 'book antiqua', palatino, serif;"><em>&Eacute;tudes&nbsp;</em><em>de march&eacute;</em></span></p>
				<p style="text-align: left;"><span style="font-family: 'book antiqua', palatino, serif;"><em>Gestion du budget</em></span></p>
			</td>
		</tr>
	</tbody>
</table> 
    <div class="w3-content w3-container w3-padding-64" id="experience">        
        <div class="container">
            <div class="red-divider"></div>
            <div class="heading">
                <h1 class="w3-center">EXPERIENCES PROFESIONNELLES</h1>
            </div>
            <p>&nbsp;</p>
<table style="height: 1231px; width: 100%; border-collapse: collapse;" border="0">
	<tbody>
		<tr style="height: 368px;">
			<td style="width: 0.900901%; height: 368px;"><img class="responsive" src="https://media-exp1.licdn.com/dms/image/C4E0BAQE2aQcdE7REbA/company-logo_200_200/0/1647883519559?e=1671062400&amp;v=beta&amp;t=pfViqhjTZCM9I1fK9whwn7daIqMxAQjRfww_olaXDvE" alt="" width="208" height="208" /></td>
			<td style="width: 99.0991%; height: 368px;">
				<h4 style="text-align: center;"><span style="color: #ff0000; font-family: verdana, geneva, sans-serif;">Alternance-Assitante Commerciale</span></h4>
				<div class="red-divider" style="text-align: center;">
					<h5><span style="color: #808080; font-family: terminal, monaco, monospace;">Septembre 2019-Septembre 2022</span></h5>
				</div>
				<div class="timeline-body">
					<p style="text-align: center;"><span style="font-family: 'courier new', courier, monospace;"><em>Gestion de la relation client</em></span></p>
					<p style="text-align: center;"><span style="font-family: 'courier new', courier, monospace;"><em>R&eacute;alisation de commandes</em></span></p>
					<p style="text-align: center;"><span style="font-family: 'courier new', courier, monospace;"><em>Aide ou d&eacute;veloppement des collections &eacute;ditoriales</em></span></p>
					<p style="text-align: center;"><span style="font-family: 'courier new', courier, monospace;"><em>Analyses et restitutions des statistiques avec GFK</em></span></p>
					<p style="text-align: center;"><span style="font-family: 'courier new', courier, monospace;"><em>Gestion du site web</em></span></p>
					<p style="text-align: center;"><span style="font-family: 'courier new', courier, monospace;"><em>R&eacute;alisation Newsletter</em></span></p>
					<p style="text-align: center;"><span style="font-family: 'courier new', courier, monospace;"><em>Etudes de march&eacute;</em></span></p>
					<p style="text-align: center;"><span style="font-family: 'courier new', courier, monospace;"><em>Benchmark</em></span></p>
				</div>
			</td>
		</tr>
		<tr style="height: 258px;">
			<td style="width: 0.900901%; height: 258px;"><img class="responsive" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSNYkmp27wWw40QlyVudcgnYJApUxuoT0vx_Q&amp;usqp=CAU" alt="" /></td>
			<td style="height: 258px;">
				<h3 style="text-align: center;"><span style="color: #ff0000;">La petite Venise - Versailles</span></h3>
				<h4 style="text-align: center;">Restaurant - Extra - Chef de rang</h4>
				<div class="red-divider" style="text-align: center;">
					<h5><span style="color: #808080; font-family: terminal, monaco, monospace;">Mars 2022-Septembre 2022</span></h5>
				</div>
				<div class="timeline-body">
					<p style="text-align: center;"><em><span style="font-family: 'comic sans ms', sans-serif;">Service</span></em></p>
					<p style="text-align: center;"><em><span style="font-family: 'comic sans ms', sans-serif;">Relation et satisfaction client</span></em></p>
					<p style="text-align: center;"><em><span style="font-family: 'comic sans ms', sans-serif;">Vente/Encaissement</span></em></p>
				</div>
			</td>
		</tr>
		<tr style="height: 136px;">
			<td style="width: 0.900901%; height: 164px;"><img class="responsive" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSht1TgsU8rOaHf2pYaHMkAtFciGm2Y0S4rEw&amp;usqp=CAU" alt="" width="207" height="133" /></td>
			<td style="width: 99.0991%; height: 164px;">
				<h4 style="text-align: center;"><span style="color: #ff0000;">African Wax Clothes</span></h4>
				<div class="red-divider" style="text-align: center;">
					<h5><span style="font-family: terminal, monaco, monospace; color: #808080;">Mars 2020-D&eacute;cembre 2021</span></h5>
				</div>
				<p style="text-align: center;"><em><span style="font-family: 'comic sans ms', sans-serif;">Technique de commercialisation</span></em></p>
			</td>
		</tr>
		<tr style="height: 187px;">
			<td style="width: 0.900901%; height: 282px;"><img class="responsive" src="https://www.hippopotamus.fr/themes/custom/hippopotamus/images/logos/logo-hippopotamus-rouge.svg" alt="" width="208" height="70" /></td>
			<td style="width: 99.0991%; height: 282px;">
				<h3 style="text-align: center;"><span style="color: #ff0000;">Hipopotamus - Paris</span></h3>
				<h4 style="text-align: center;"><span style="color: #000000;">Restaurant - Chef de rang</span></h4>
				<div class="red-divider" style="text-align: center;">
					<h5><span style="font-family: terminal, monaco, monospace; color: #808080;">Mars 2018-Aout 2019</span></h5>
				</div>
				<div class="timeline-body">
					<p style="text-align: center;"><em><span style="font-family: 'comic sans ms', sans-serif;">Service</span></em></p>
					<p style="text-align: center;"><em><span style="font-family: 'comic sans ms', sans-serif;">Relation et satisfaction client</span></em></p>
					<p style="text-align: center;"><em><span style="font-family: 'comic sans ms', sans-serif;">Vente/Encaissement</span></em></p>
				</div>
			</td>
		</tr>
		<tr style="height: 159px;">
			<td style="width: 0.900901%; height: 159px;"><img class="responsive" src="https://media-exp1.licdn.com/dms/image/C4D0BAQFlVbiuYpjtSA/company-logo_200_200/0/1582042504571?e=1671062400&amp;v=beta&amp;t=kbyr3B4kCVdLESXPtYCwnu-x3V0zX2t8-pkDM3r7LdQ" alt="" /></td>
			<td style="width: 99.0991%; height: 159px;">
				<h4 style="text-align: center;"><span style="color: #ff0000;">Stage - Assistante Commerciale</span></h4>
				<div class="red-divider" style="text-align: center;">
					<h5><span style="color: #808080; font-family: terminal, monaco, monospace;">Avril 2019-Juin 2019</span></h5>
				</div>
				<div class="timeline-body">
					<p style="text-align: center;"><span style="font-family: 'comic sans ms', sans-serif;"><em>Prospection t&eacute;l&eacute;phonique</em></span><br /><span style="font-family: 'comic sans ms', sans-serif;"><em>R&eacute;alisation d'une plaquette commerciale Travail d'&eacute;quipe</em></span><br /><span style="font-family: 'comic sans ms', sans-serif;"><em>Gestion de la relation client</em></span></p>
				</div>
			</td>
		</tr>
	</tbody>
</table>
        </div>
    <div class="w3-content w3-container w3-padding-64" id="formations">           
        <div class="container">
            <div class="red-divider"></div>
            <div class="heading">
                <h1 class="w3-center">FORMATIONS</h1>
            </div>
            <p>&nbsp;</p>
<p>&nbsp;</p>
<table style="height: 2027px; width: 100%; border-collapse: collapse;" border="0">
	<tbody>
		<tr style="height: 306px;">
			<td style="width: 18.7722%; height: 306px;"><img class="responsive" src="https://media-exp1.licdn.com/dms/image/C4D0BAQHKaTdbaXr3dA/company-logo_200_200/0/1634027408758?e=1671062400&amp;v=beta&amp;t=VpyY0PfZVYrJJjJEkwHJaqz9DFze-DcxVFQ7uFQn1mM" alt="" /></td>
			<td style="width: 81.2278%; height: 306px;">
				<h5 style="text-align: center;"><span style="color: #808080;">2020-2022</span></h5>
				<h3 style="text-align: center;"><span style="color: #ff0000;">INSEEC - Paris</span></h3>
				<h4 style="text-align: center;"><span style="color: #993366;">Bussiness School</span></h4>
				<p style="text-align: center;"><span style="color: #33cccc;">Master 1 - Sp&eacute;cification Luxe</span></p>
				<p style="text-align: center;"><span style="color: #33cccc;">Master 2 - Majeur Marketing &agrave; l'&egrave;re contemporaine</span></p>
			</td>
		</tr>
		<tr style="height: 693px;">
			<td style="width: 18.7722%; text-align: center; height: 693px;"><img class="responsive" src="https://media-exp1.licdn.com/dms/image/C4E0BAQFQBI8284On6w/company-logo_200_200/0/1569925296545?e=1671062400&amp;v=beta&amp;t=htkjrgZTFgDohrV539DRKY4BDYr2BnIN9sN064HQEmM" alt="" /></td>
			<td style="width: 81.2278%; height: 693px;">
				<h5 style="text-align: center;"><span style="color: #808080;">2019-2020</span></h5>
				<h3 style="text-align: center;"><span style="color: #ff0000;">ICD - Paris</span></h3>
				<h4 style="text-align: center;"><span style="color: #993366;">Bussiness School</span></h4>
				<p style="text-align: center;"><span style="color: #33cccc;">Bachelor</span></p>
				<p style="text-align: center;"><span style="color: #33cccc;">Business Developpent</span></p>
				<p style="text-align: center;"><span style="color: #ff6600;"><em>-Apprentissage sur le monde commercial<br />-R&eacute;alisation d'un business plan &agrave; la fin du cursus<br />-Formation &agrave; l'entrepreneuriat </em></span></p>
			</td>
		</tr>
		<tr style="height: 801px;">
			<td style="width: 18.7722%; height: 801px;"><img class="responsive" src="https://media-exp1.licdn.com/dms/image/C560BAQHh8K8-khWRWg/company-logo_200_200/0/1613376386860?e=1671062400&amp;v=beta&amp;t=YeUc7B1B44t17-5_LiD1CS6xWrSLq4LxJQljyT1SeGo" alt="" /></td>
			<td style="width: 81.2278%; height: 801px;">
				<h5 style="text-align: center;"><span style="color: #808080;">2017-2019</span></h5>
				<h3 style="text-align: center;"><span style="color: #ff0000;">IUT DE SCEAUX</span></h3>
				<h4 style="text-align: center;"><span style="color: #993366;">DUT</span></h4>
				<p style="text-align: center;"><span style="color: #33cccc;">Technique de commercialisation</span></p>
				<p style="text-align: center;"><span style="color: #ff6600; font-size: 10pt;"><em>-Plusieurs enseignements permettant d'avoir les comp&eacute;tences n&eacute;cessaires au domaine commercial (communication, marketing, techniques de commercialisation) <br />-Stages r&eacute;alis&eacute;s tout au long du cursus ainsi que plusieurs projets li&eacute;s &agrave; des &eacute;tudes de march&eacute;s, des entreprises partenaires.</em></span></p>
			</td>
		</tr>
		<tr style="height: 227px;">
			<td style="width: 18.7722%; height: 227px;"><img class="responsive" src="https://media-exp1.licdn.com/dms/image/C4E0BAQFFnwBsi6bMZw/company-logo_200_200/0/1609783173982?e=1671062400&amp;v=beta&amp;t=fltRkf9yczNFMclLwTl_7aeyxTRX2u1UnXI-Nf0AAOM" alt="" /></td>
			<td style="width: 81.2278%; height: 227px;">
				<h5 style="text-align: center;"><span style="color: #808080;">2016-2017</span></h5>
				<h3 style="text-align: center;"><span style="color: #ff0000;">Lyc&eacute;e Fran&ccedil;ais-Tananarive</span></h3>
				<h4 style="text-align: center;"><span style="color: #993366;">Baccalaur&eacute;at</span></h4>
				<p style="text-align: center;"><span style="color: #33cccc;">&Eacute;conomie et Sociale</span></p>
				<p style="text-align: center;"><span style="color: #33cccc;">Mention Bien</span></p>
			</td>
		</tr>
	</tbody>
</table>


    <!-- Second Parallax Image with Portfolio Text -->
    <div class="bgimg-2 w3-display-container w3-opacity-min">
        <div class="w3-display-middle">
            <span class="w3-xxlarge w3-text-white w3-wide">PORTFOLIO</span>
        </div>
    </div>

    <!-- Container (Portfolio Section) -->
    <div class="w3-content w3-container w3-padding-64" id="portfolio">
        <h3 class="w3-center">La cuisine de Zain 🧁</h3>
        <div class="pvs-list__outer-container">
	<h4><span style="font-family: 'times new roman', times, serif;"><em>Gr&acirc;ce &agrave; mes connaissances et exp&eacute;riences dans le digital ainsi que dans la cuisine, je me suis lanc&eacute;e dans la cr&eacute;ation d'une page instagram dans laquelle je partage mes cr&eacute;ations ainsi que des recettes.</em></span></h4>
	<h4><span style="font-family: 'times new roman', times, serif;"><em> Je poste r&eacute;guli&egrave;rement du contenu afin de rendre ma page attractive et dynamique, cela me permet de g&eacute;n&eacute;rer plusieurs abonn&eacute;s en quelques jours. </em></span></h4>
	<h4><span style="font-family: 'times new roman', times, serif;"><em>Je ma&icirc;trise de ce fait tous les outils instagram n&eacute;cessaires &agrave; augmenter la visibilit&eacute; de ma page. </em></span></h4>
	<h4><span style="font-family: 'times new roman', times, serif;"><em>Cette activit&eacute; me permet de d&eacute;velopper et renforcer mes connaissances et comp&eacute;tences sur la ma&icirc;trise des r&eacute;seaux sociaux.</em></span></h4>
	<h4><span style="font-family: 'times new roman', times, serif;"><em> La cr&eacute;ation de cette page m'a permis d'avoir une meilleure gestion et optimisation de mon temps.</em></span></h4>
	<h4>&nbsp;</h4>
        </div>

        <!-- Responsive Grid. Four columns on tablets, laptops and desktops. Will stack on mobile devices/small screens (100% width) -->
        <div class="w3-row-padding w3-center">
            <div class="w3-col m3">
                <img src="bouf1.png" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity"
                    alt="The mist over the mountains">
            </div>

            <div class="w3-col m3">
                <img src="bouf2.png" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity"
                    alt="Coffee beans">
            </div>

            <div class="w3-col m3">
                <img src="bouf3.png" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity"
                    alt="Bear closeup">
            </div>

            <div class="w3-col m3">
                <img src="bouf4.png" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity"
                    alt="Quiet ocean">
            </div>
        </div>

        <div class="w3-row-padding w3-center w3-section">
            <div class="w3-col m3">
                <img src="bouf5.png" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="The mist">
            </div>

            <div class="w3-col m3">
                <img src="bouf6.png" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity"
                    alt="My beloved typewriter">
            </div>

            <div class="w3-col m3">
                <img src="bouf7.png" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity"
                    alt="Empty ghost train">
            </div>

            <div class="w3-col m3">
                <img src="bouf8.png" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Sailing">
            </div>
            
        </div>
    </div>

    <!-- Modal for full size images on click-->
    <div id="modal01" class="w3-modal w3-black" onclick="this.style.display='none'">
        <span class="w3-button w3-large w3-black w3-display-topright" title="Close Modal Image"><i
                class="fa fa-remove"></i></span>
        <div class="w3-modal-content w3-animate-zoom w3-center w3-transparent w3-padding-64">
            <img id="img01" class="w3-image">
            <p id="caption" class="w3-opacity w3-large"></p>
        </div>
    </div>

    <!-- Third Parallax Image with Portfolio Text -->

    <!-- Container (Contact Section) -->
    <div class="w3-content w3-container w3-padding-64" id="contact">
<table style="width: 100%; border-collapse: collapse; border-style: ridge;" border="5">
	<tbody>
		<tr>
			<td style="width: 100%;">
				<h1 style="text-align: center;">CONTACT</h1>
				<p style="text-align: center;">&nbsp;</p>
				<p style="text-align: center;">🏚️ 92140 CLAMART</p>
				<p style="text-align: center;">📞 0660365135</p>
				<p style="text-align: center;">📩 <a href="mailto:gzainab99@gmail.com">gzainab99@gmail.com</a></p>
			</td>
		</tr>
	</tbody>
</table>
<br><br><br>
    <footer class="w3-center w3-black w3-padding-64 w3-opacity w3-hover-opacity-off">
        <a href="#home" class="w3-button w3-light-grey"><i class="fa fa-arrow-up w3-margin-right"></i>To the top</a>
                <h5><div class="copyright" class="text-center p-3">© 2022 Copyright : Aucun droits réservés</div></h5>
    </footer>

    <script>
        // Modal Image Gallery
        function onClick(element) {
            document.getElementById("img01").src = element.src;
            document.getElementById("modal01").style.display = "block";
            var captionText = document.getElementById("caption");
            captionText.innerHTML = element.alt;
        }

        // Change style of navbar on scroll
        window.onscroll = function () { myFunction() };
        function myFunction() {
            var navbar = document.getElementById("myNavbar");
            if (document.body.scrollTop > 100 || document.documentElement.scrollTop > 100) {
                navbar.className = "w3-bar" + " w3-card" + " w3-animate-top" + " w3-white";
            } else {
                navbar.className = navbar.className.replace(" w3-card w3-animate-top w3-white", "");
            }
        }

        // Used to toggle the menu on small screens when clicking on the menu button
        function toggleFunction() {
            var x = document.getElementById("navDemo");
            if (x.className.indexOf("w3-show") == -1) {
                x.className += " w3-show";
            } else {
                x.className = x.className.replace(" w3-show", "");
            }
        }
    </script>

</body>

</html>
