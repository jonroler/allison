<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Chrome, Firefox OS, Opera and Vivaldi -->
	<meta name="theme-color" content="#196143">
	<!-- Windows Phone -->
	<meta name="msapplication-navbutton-color" content="#196143">
	<!-- iOS Safari -->
	<meta name="apple-mobile-web-app-status-bar-style" content="#196143">
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
<title>Conservation Research</title>
    

    <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
    <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
      <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
    <![endif]-->
  <link rel="icon" type="image/png" href="/images/core/rbg-favicon-leaf-32x32.png" />
  <link rel="stylesheet" href="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/css/bootstrap.min.css">
  <link rel="stylesheet" type="text/css" href="http://fonts.googleapis.com/css?family=Open+Sans" /> <!-- Font 'Open Sans' Hosted by Google -->
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/2.2.2/jquery.min.js"></script>
  <script src="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/js/bootstrap.min.js"></script>
  <link rel="stylesheet" href="/CSS/summer.css?v=1"> <!-- Additional local CSS -->
  
<!-- Begin Search Bar Toggle Script-->
	<script type="text/javascript"> 
	
	$(function(){
		$(".searchbar").hide();
		
	
		
		$(".searchicon").on("click", 
			function(){
		
				if( $( ".searchbar" ).is( ":hidden" ) ) {
				
				    $(".navbutton, .searchbar").toggle(300);
				    $(".searchicon").css("background-color", "#196143");
				    
				    return;
				
				}
				
				else if ( $( ".navbutton" ).is( ":hidden" ) ) { 
					
					$(".searchbar, .navbutton").toggle(300);
					$(".searchicon").css("background-color", "transparent");
					$('.searchicon').hover(
					    function() {
					      var $this = $(this);
					      $this.data('transparent', $this.css('background-color')).css('background-color', '#196143');
					    },
					    function() {
					      var $this = $(this);
					      $this.css('background-color', $this.data('transparent'));
					    }
					); 	
					
				}
		});
	
	});
	</script>
<!-- End Search Bar Toggle Script -->
  
</head>
<body>
<!-- Begin Navbar -->
<div class="navbar-wrapper">
		
		<nav class="navbar navbar-inverse navbar-static-top" role="navigation">

		  <div id="navbarbg" class="container-fluid">
		    
		    <div id="rbgnavbar" class="container-fluid">    
		    
				<div class="navbar-header">
			      <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
			        <span class="icon-bar"></span>
			        <span class="icon-bar"></span>
			        <span class="icon-bar"></span>                        
			      </button>
			      <a id="logo" class="pull-left" href="/index"><img src="/images/core/logo.png" class="hover" alt="Red Butte Garden" title="Red Butte Garden" /></a>
			    </div>
			    
			    <div class="collapse navbar-collapse" id="myNavbar">
			      
			      <ul class="nav navbar-nav">
			        
			        <li class="dropdown">
			          <a class="dropdown-toggle" data-toggle="dropdown" href="#">VISIT <span class="caret"></span></a>
			          <ul class="dropdown-menu">
						<a href="/general-info"><li>GENERAL INFO</li></a>
						<a href="/about-us"><li>ABOUT US</li></a>
			            <a href="/garden-maps"><li>GARDEN MAPS</li></a>
			            <a href="/gift-shop"><li>GIFT SHOP</li></a>
			            <a href="/free-garden-events"><li>FREE DAYS<br />&amp; EVENTS</li></a>
			            <a href="/garden-tours"><li>GARDEN TOURS</li></a>
						<a href="/taleblazer"><li>PLAY TALEBLAZER</li></a>
			            <a href="/poetry"><li>POETRY IN <br />THE GARDEN</li></a>
			            <a href="/whats-happening"><li>WHAT'S HAPPENING BLOG</li></a>
			          </ul>
			        </li>
			        
					<li class="dropdown">
			          <a class="dropdown-toggle" data-toggle="dropdown" href="#">PLANTS &amp; GARDENS <span class="caret"></span></a>
			          <ul class="dropdown-menu">
			            <a href="/gardens"><li>OUR GARDENS</li></a>
			            <a href="/plant-collections"><li>PLANT COLLECTIONS</li></a>
			            <a href="http://plants.redbuttegarden.org"><li>INTERACTIVE<br/>PLANT MAP</li></a>
			            <a href="/conservation-research"><li>CONSERVATION<br />RESEARCH</li></a>
			            <a href="/gardening-in-utah"><li>GARDENING IN UTAH</li></a>
			            <a href="/whats-blooming"><li>WHAT'S BLOOMING<br /> NOW BLOG</li></a>
			          </ul>
			        </li>
					
			        <li class="dropdown">
			          <a class="dropdown-toggle" data-toggle="dropdown" href="#">EVENTS <span class="caret"></span></a>
			          <ul class="dropdown-menu">
			            <a href="/concerts"><li class="concert-li">OUTDOOR CONCERT SERIES</li></a>
			            <a href="/spring"><li>SPRING EVENTS</li></a>
			            <a href="/summer"><li>SUMMER EVENTS</li></a>
			            <a href="/fall"><li>FALL EVENTS</li></a>
			            <a href="/winter"><li>WINTER EVENTS</li></a>
			            <a href="/calendar"><li>EVENT CALENDAR</li></a>
			          </ul>
			        </li>
					
					<li class="dropdown">
			          <a class="dropdown-toggle" data-toggle="dropdown" href="#">EDUCATION <span class="caret"></span></a>
			          <ul class="dropdown-menu">
			            <a href="/adult-education"><li>EDUCATION &amp; WORKSHOPS<br/ >FOR ADULTS</li></a>
			            <a href="/summer-camp"><li>SUMMER CAMP</li></a>			            
			            <a href="/kids-classes"><li>KIDS CLASSES</li></a>
				        <a href="/lectures"><li>LECTURES</li></a>
			            <a href="/teachers-and-students"><li>TEACHERS & STUDENTS</li></a>
			          </ul>
			        </li>
			        
					<li class="dropdown">
			          <a class="dropdown-toggle" data-toggle="dropdown" href="#">GET INVOLVED <span class="caret"></span></a>
			          <ul class="dropdown-menu">
			            <a href="/volunteer"><li>VOLUNTEER</li></a>			          
			            <a href="https://55218.blackbaudhosting.com/55218/Annual-Gift"><li>GIVE</li></a>
			            <a href="/memberships"><li>MEMBERSHIP</li></a>
			            <a href="/current-fundraisers"><li>CURRENT FUNDRAISERS</li></a>
			            <a href="/corporate-sponsorship"><li>CORPORATE <br />SPONSORSHIP</li></a>
			            <a href="/employment"><li>EMPLOYMENT</li></a>
			          </ul>
			        </li>
		
			        <li class="dropdown">
			          <a class="dropdown-toggle" data-toggle="dropdown" href="#">PRIVATE EVENTS <span class="caret"></span></a>
			          <ul class="dropdown-menu">
			            <a href="/weddings-and-receptions"><li>WEDDINGS<br />&amp; RECEPTIONS</li></a>
			            <a href="/private-parties"><li>CORPORATE EVENTS <br />&amp; PRIVATE PARTIES</li></a>
			            <a href="/rental-sites"><li>RENTAL SITES</li></a>
			            <a href="/rental-availability"><li>RENTAL AVAILABILITY</li></a>
			            <a href="/rental-rates-and-catering"><li>RENTAL RATES<br />& CATERING</li></a>
			          </ul>
			        </li>
			        
			        <li class="dropdown search" id="navhide4">
			          	<span class="dropdown-toggle searchicon"><a href="/search"><img src="/images/search.png"></a></span>

			        </li>
					<br class="br-hide-lg" />
					<li class="dropdown navbutton" id="navhide1">
			        	<a class="dropdown-toggle" href="https://55218.blackbaudhosting.com/55218/Annual-Gift">GIVE</a>
			        </li>  
			           
			        <li class="dropdown navbutton" id="navhide2">
			         	 <a class="dropdown-toggle" href="/memberships">JOIN</a>
			        </li>
			        
			        <li class="dropdown navbutton" id="navhide3">
			         	 <a class="dropdown-toggle" href="/volunteer">VOLUNTEER</a>
			        </li>
			        
			      </ul>
			     
			    </div>
		    
		    </div>
		      
		  </div>
		  
		</nav>
</div>
<!-- End Navbar -->


<div id="rbgdefaultbody" class="container-fluid">
  <div class="row">
  	  <div class="col-sm-12">
        <div class="eventdivide">
	<hr>
		<div class="grid-header">CONSERVATION RESEARCH</div>		
	<hr>
</div>

<br />

<!-- Begin Panel for Projects -->
<div class="row">
		
	<div class="col-sm-12">
	
		<span class="no-button-outline">
			<button class="volbutton hover green-bg" data-target="#conservationResearch" data-toggle="collapse">CURRENT AND RECENT PROJECTS</button>
		</span>
		
		<div class="collapse panel-border" id="conservationResearch">
			<br />
			<p class="text-center">Our work focuses on the flora of the Intermountain West, with a particular focus on two ecoregions in Utah - the Colorado Plateau and the Great Basin. The majority of our projects occur within Utah, although we do occasionally venture into neighboring states.</p>
			
			<hr width="98%">
			
			<!-- Begin Rana Project -->
			<br />
			<div class="row-fluid">
			
				<div class="col-sm-2">
				
					<img src="/images/misc/con-rana-project.jpg" class="responsive" alt="Monitoring Pollinator Activity with Rana" title="Monitoring Pollinator Activity with Rana" />
				
				</div>
				
				<div class="col-sm-10">
					<br />
					<p><strong>Project: <span class="green">Monitoring Pollinator Activity with Rana</span></strong></p>
					<p><strong>Duration:</strong> Ongoing</p>
					<p><strong>Summary:</strong> We are using a new automated motion-capture technology <a href="http://www.tumblingdice.co.uk/rana">(Rana)</a> to track and record pollinator activity on selected native plant species. This project will allow us to determine the diversity and frequency of insect visits on certain types of flowers, and help answer important questions about pollinator services and "pollinator-friendly" plants in Utah. We set up cameras at the Rio Mesa Center outside of Moab, UT as well as the Natural Area and Children's Garden here at Red Butte Garden, and recorded visits of many different kinds of native bees, butterflies, and even hummingbirds. To watch a video of pollinators visiting flowers at Red Butte Garden, <a href="https://www.youtube.com/watch?v=L6_vPnhdot0">click here!</a></p>
					
				</div>
				
			</div>
			<br />
			<hr width="98%">
			<!-- End Rana Project -->
			
			<!-- Begin Seeds of Success Project -->
			<br />
			<div class="row-fluid">
			
				<div class="col-sm-2">
				
					<img src="/images/misc/con-seeds-of-success-project.jpg" class="responsive" alt="Seeds of Success" title="Seeds of Success" />
				
				</div>
				
				<div class="col-sm-10">
					<br />
					<p><strong>Project: <span class="green">Seeds of Success (SOS)</span></strong></p>
					<p><strong>Partners:</strong> BLM and Colorado Plateau Native Plant Program (CPNPP)</p>
					<p><strong>Duration:</strong> Ongoing</p>
					<p><strong>Summary:</strong> Each year we survey an ecological region for abundant, native plants from which seed can be collected. In 2015, we completed nearly 30 collections totaling 1.2 million seeds from 14 native Great Basin plant species. Seeds are stored at the Bend Seed Extractory for future use in habitat restoration and rehabilitation. Herbarium specimens are also collected, which are divvied up between Red Butte Garden, the University of Utah, Brigham Young University, and the Smithsonian Institute. <a href="https://seedsofsuccess.smugmug.com/Bureau-of-Land-Management/BLM-CP2/">Click here</a> for photo highlights from past SOS Collection years!</p>
					
				</div>
				
			</div>
			<br />
			<hr width="98%">
			<!-- End Seeds of Success Project -->
			
			<!-- Begin Blackrock Gypsum Project -->
			<br />
			<div class="row-fluid">
			
				<div class="col-sm-2">
				
					<img src="/images/misc/con-vegetation-survey-project.jpg" class="responsive" alt="Blackrock Gypsum Vegetation Surveys and Rehabilitation Analysis" title="Blackrock Gypsum Vegetation Surveys and Rehabilitation Analysis" />
				
				</div>
				
				<div class="col-sm-10">
					<br />
					<p><strong>Project: <span class="green">Blackrock Gypsum Vegetation Surveys and Rehabilitation Analysis</span></strong></p>
					<p><strong>Partners:</strong> BLM, U.S. Fish and Wildlife Service, and Blackrock Gypsum</p>
					<p><strong>Duration:</strong> Completed in 2015</p>
					<p><strong>Summary:</strong> We surveyed habitat surrounding the Endangered Gierisch's globemallow (Sphaeralcea gierischii) population in Arizona to piece together the rehabilitation history of post-gypsum mining landforms. We compared vegetation structure and composition between rehab and adjacent undisturbed control sites to examine the effects of past practices, seed mixes and the gypsum-rich substrate on the success of restoration in this area.</p>
					
				</div>
				
			</div>
			<br />
			<hr width="98%">
			<!-- End Blackrock Gypsum Project -->
			
			<!-- Begin Seed Banking Project -->
			<br />
			<div class="row-fluid">
			
				<div class="col-sm-2">
				
					<img src="/images/misc/con-seed-banking-project.jpg" class="responsive" alt="Seed Banking" title="Seed Banking" />
				
				</div>
				
				<div class="col-sm-10">
					<br />
					<p><strong>Project: <span class="green">Rare and endangered seed collection for ex-situ conservation, a.k.a. seed banking</span></strong></p>
					<p><strong>Partner:</strong> BLM and Center for Plant Conservation (CPC)</p>
					<p><strong>Duration:</strong> Ongoing</p>
					<p><strong>Summary:</strong> Seed banking is a long-term method for conserving the diversity of plant species. Seeds of rare, threatened and endangered plants are collected and stored with low moisture content at low temperatures, thereby extending their lifespan. These collections preserve genetic material away from the threat of habitat destruction. We store a portion of seed in our on-site seed bank; another portion is sent to the <a href="http://www.ars.usda.gov/main/site_main.htm?modecode=54-02-05-00">National Center for Genetic Resources Preservation</a> in Fort Collins, CO.</p>
					
				</div>
				
			</div>
			<br />
			<hr width="98%">
			<!-- End Seed Banking Project -->
			
			<!-- Begin Germination and Propagation Trials Project -->
			<br />
			<div class="row-fluid">
			
				<div class="col-sm-2">
				
					<img src="/images/misc/con-germination-propagation-project.jpg" class="responsive" alt="Germination and Propagation Trial" title="Germination and Propagation Trial" />
				
				</div>
				
				<div class="col-sm-10">
					<br />
					<p><strong>Project: <span class="green">Germination and Propagation Trials</span></strong></p>
					<p><strong>Partner: </strong>BLM and Center for Plant Conservation (CPC)</p>
					<p><strong>Duration: </strong>Ongoing</p>
					<p><strong>Summary: </strong>At the garden, we are currently testing seeds from our seed bank in order to develop the best protocols for germinating rare plant species. Once seeds have germinated, we maintain them in our greenhouses and track their growth each month in order to pinpoint the best methods for propagation. Many of the species we work with require very specific conditions for growth, and by sustaining these species in our greenhouses, we can determine the feasibility of growing seedlings for future outplanting and restoration studies. <a href="http://redbuttegarden.org/current-projects/lestum">Learn more about our current trials here!</a></p>
					
				</div>
				
			</div>
			<br />
			<hr width="98%">
			<!-- End Germination and Propagation Trials Project -->
			
			<!-- Begin Sphaeralcea gierischii Project -->
			<br />
			<div class="row-fluid">
			
				<div class="col-sm-2">
				
					<img src="/images/misc/con-globemallow-project.jpg" class="responsive" alt="Sphaeralcea gierischii (Gierisch's globemallow) propagation and reintroduction" title="Sphaeralcea gierischii (Gierisch's globemallow) propagation and reintroduction" />
				
				</div>
				
				<div class="col-sm-10">
					<br />
					<p><strong>Project: <span class="green">Sphaeralcea gierischii (Gierisch's globemallow) propagation and reintroduction</span></strong></p>
					<p><strong>Plant Status: </strong>Listed Endangered</p>
					<p><strong>Threats: </strong>Gypsum mining and off-road vehicle recreation</p>
					<p><strong>Partner: </strong>BLM, U.S. Fish and Wildlife Service</p>
					<p><strong>Duration: </strong>Completed in 2015</p>
					<p><strong>Summary: </strong>We conducted in-situ germination studies at a trial reintroduction site to assess the feasibility of reintroducing this species to rehabilitated mining substrates from seed. We monitored seedling establishment and tracked seedling survivorship from 2013-2015 on study sites in Arizona. We also collected seed for long-term ex-situ conservation and developed greenhouse propagation protocols. This species was listed as endangered in 2013, a decision that was informed by our data.</p>
					
				</div>
				
			</div>
			<br />
			<hr width="98%">
			<!-- End Sphaeralcea gierischii Project -->
			
			<!-- Begin Penstemon grahamii Project -->
			<br />
			<div class="row-fluid">
			
				<div class="col-sm-2">
				
					<img src="/images/misc/con-penstemon-project.jpg" class="responsive" alt="Penstemon Monitoring" title="Penstemon Monitoring" />
				
				</div>
				
				<div class="col-sm-10">
					<br />
					<p><strong>Project: <span class="green">Penstemon grahamii (Graham’s beardtongue) and Penstemon scariosus var. albifluvis (White River beardtongue) long-term demographic and population monitoring</span></strong></p>
					<p><strong>Threats: </strong>Oil and gas exploration, tar sand and oil shale mining, off-road vehicle use, and grazing. All threats are exacerbated by small population sizes and limited distribution.</p>
					<p><strong>Partner: </strong>BLM</p>
					<p><strong>Duration: </strong>Initiated in 2004, completed in 2015</p>
					<p><strong>Summary: </strong>Over the ten consecutive years of this monitoring project, we have collected demographic and population trend data from these species to inform management decisions. The project has grown to include propagation studies, ex-situ care of living specimens, and seed collection for ex-situ conservation.</p>
					
				</div>
				
			</div>
			<br />
			<hr width="98%">
			<!-- End Penstemon grahamii Project -->
			
			<!-- Begin Project Template
			<br />
			<div class="row-fluid">
			
				<div class="col-sm-2">
				
					<img src="/images/misc/.jpg" class="responsive" alt="" title="" />
				
				</div>
				
				<div class="col-sm-10">
					<br />
					<p><strong>Project: <span class="green"></span></strong></p>
					<p><strong>Partner: </strong></p>
					<p><strong>Duration: </strong></p>
					<p><strong>Summary: </strong></p>
					
				</div>
				
			</div>
			<br />
			<hr width="98%">
			End Project Template -->	
									
			<br />
		
		</div>
			
	</div>

	
</div>

<!-- End Panel for Projects -->

<br />

<!-- Begin intro grid--> 
<div class="row">
	
	<div class="col-sm-4">
	
		<h3 class="green text-center">What is biodiversity?</h3>
		<p>Biodiversity is the number of different species of plants and animals found within a particular region, or ecosystem. The more diverse an ecosystem, meaning the more plants, animals, insects, and bacteria living within it, the healthier it is. A diverse ecosystem has more resources to draw on that allow it to bounce back from disturbances, adapt to long-term changes, and support the communities within it, wild or cultivated.</p>
		
	</div>
	
	<div class="col-sm-4">
	
		<h3 class="green text-center">Why does it matter?</h3>
		<p>While biodiversity is critical for the sake of the environment in and of itself, there are a number of reasons biodiversity should matter to our species. To focus just on plant diversity: plants provide us with key ingredients and products that feed us, shelter us, keep us healthy, and fuel our economy. To destroy a species, actively or unknowingly, is to destroy its potential for tomorrow and for generations to come.
		Read "Why Diversity Matters" from NatureServe.</p>
	
	</div>
	
	<div class="col-sm-4">
	
		<h3 class="green text-center">What are our goals?</h3>
		<p>We are stewards of the at-risk plants in our region, and protecting them is a key component of Red Butte Garden’s mission. We hope to mitigate threats and preserve genetic information so that rare populations may recover in their native habitats, thereby conserving the diversity of our native flora.</p>
	
	</div>
	
</div>

<br />

<div class="row">
	
	<div class="col-sm-4">
	
		<img src="/images/misc/con-fieldwork-01.jpg" alt="Conservation Team Doing Field Work" title="Conservation Team Doing Field Work" class="responsive" />
	
	</div>
	
	<div class="col-sm-4">
	
		<h3 class="green text-center">What kind of work do we do?</h3>
		
		<p><strong>In-situ conservation</strong> is work that is done on site, in the area where the plant naturally grows. We collect plant samples and seeds to study later, monitor populations, transplant endangered species out of harm’s way, and re-vegetate with seeds or seedlings in their native habitats.</p>
		
		<p><strong>Ex-situ conservation</strong> is work that is done off site, at our garden facility or other facilities around the West. This work involves storing seeds in seed banks to preserve the genetic material, testing seed germination and viability to better understand how to propagate a species, and caring for living specimens that have been propagated or salvaged from project sites.</p>
	
	</div>
	
	<div class="col-sm-4">
	
		<img src="/images/misc/con-fieldwork-02.jpg" alt="Conservation Team Doing MORE Field Work" title="Conservation Team Doing MORE Field Work" class="responsive" />
	
	</div>

</div>
<!-- End intro grid -->

<br />

<!-- Begin Bottom Panels -->
<div class="row">
	
	<!-- BEGIN WHAT CAN YOU DO PANEL -->
	<div class="col-sm-6">
		
		<span class="no-button-outline">
			<button class="volbutton hover green-bg" data-target="#contribute" data-toggle="collapse">WHAT CAN YOU DO?</button>
		</span>
		
		<div class="collapse panel-border" id="contribute">
			<br />
			
			<div class="row-fluid">
				<div class="col-xs-12">
					<h5 class="green">Volunteer:</h5>
					<p>Your time and experience are valuable to us. Whether you’re a novice naturalist or a committed conservationist, we can use your help! If you’re interested in volunteering in Conservation or anywhere else at Red Butte Garden, contact our Volunteer Coordinator, Lauren Miller, or check out the <a href="/volunteer">Volunteer Opportunities page</a>.</p>
		
					<p><strong>Lauren Miller</strong>, <em>Volunteer Coordinator</em>
					<br /><strong>Email:</strong> <a href="mailto:lauren.miller@redbutte.utah.edu">lauren.miller@redbutte.utah.edu</a>
					<br /><strong>Phone: <span class="green">801-585-5853</span></strong></p>
		
					<p>Volunteers help with a wide variety of projects, many of which are seasonal. They include plant surveying and seed collection; cleaning, sorting, and banking seeds; rare plant curation and propagation; and general greenhouse and office help. Training in the field is provided. Volunteers must be 18 years or older.</p>
								
					<h5 class="green">Plant Natives, Pull Invasives:</h5>
					<p>Your land, however small, can be an important piece of habitat for native plants, pollinators, and other wildlife. As our cities expand outward, eating up true native habitats, these oases become critical to support native populations.</p>
					
					<h5 class="green">What to Plant:</h5> 
					
					<ul>
						<li><a href="http://www.ars.usda.gov/SP2UserFiles/Place/54280500/Gardening.pdf">Gardening for Native Bees in Utah from USU Cooperative Extension</a></li>
						<li><a href="http://www.pollinator.org/guides.htm">Ecoregional Planting Guides from The Pollinator Partnership</a></li>
						<li><a href="http://www.unps.org/index.html?PAGES/cohortlist.html">Native Plant Resources from the Utah Native Plant Society</a></li>
					</ul>
					
					<h5 class="green">What to Pull:</h5>
					<p><a href="http://www.utahweed.org/weeds.htm">Utah’s Noxious Weed List from the Utah Weed Control Association</a></p>
					
					<h5 class="green">Donate:</h5>
					<p>We can’t do it without your support. Making a donation to the Garden supports our efforts to protect and restore threatened plant communities throughout Utah.</p>
					
					<center>
						<a href="https://55218.blackbaudhosting.com/55218/Annual-Gift">
						<form method="POST" action="https://55218.blackbaudhosting.com/55218/Annual-Gift">
							<input class="green-button" type="button" value="Make a Donation"/>
						</form>
						</a>
					</center>
					
					<br />
				
				</div>
			</div>
			<br />
		
		</div>
			
	</div>
	<!-- END WHAT CAN YOU DO PANEL -->
	
	<!-- BEGIN COLLABORATORS PANEL -->
	<div class="col-sm-6">
		
		<span class="no-button-outline">
			<button class="volbutton hover green-bg" data-target="#collaborators" data-toggle="collapse">COLLABORATORS</button>
		</span>
		
		<div class="collapse panel-border" id="collaborators">
			<br />

			<ul>
				<li><a href="http://www.centerforplantconservation.org/">Center for Plant Conservation</a></li>
				<li><a href="http://www.blm.gov/wo/st/en/prog/more/fish__wildlife_and/plants/seeds_of_success.htm">Seeds of Success</a></li>		
				<li><a href="http://www.unps.org/index.html">Utah Native Plant Society</a></li>			
				<li><a href="http://dwrcdc.nr.utah.gov/ucdc/">Utah Natural Heritage Program</a></li>			
				<li><a href="http://www.blm.gov/pgdata/content/ut/en.html">U.S. Department of the Interior, Bureau of Land Management</a></li>			
				<li><a href="http://www.fws.gov/offices/Directory/ListOffices.cfm?statecode=49">U.S. Fish and Wildlife Service</a></li>			
				<li><a href="http://www.fs.usda.gov/r4">U.S. Forest Service</a></li>		
				<li><a href="http://www.nps.gov/state/ut/index.htm?program=all">National Parks Service</a></li>			
				<li><a href="http://www.ars-grin.gov/ncgrp/index.htm">National Center for Genetic Resources Preservation</a></li>			
				<li><a href="http://www.blm.gov/ut/st/en/prog/more/CPNPP.html">Colorado Plateau Native Plant Program</a></li>			
				<li><a href="http://riomesa.utah.edu/">Rio Mesa Center</a></li>		
			</ul>
			
			<br />
		
		</div>
			
	</div>
	<!-- END COLLABORATORS PANEL -->
	
</div>

<span class="br-hide"><br /></span>

<div class="row">
	
	<!-- BEGIN NEWS AND LINKS PANEL -->
	<div class="col-sm-12">
	
		<span class="no-button-outline">
			<button class="volbutton hover" data-target="#newslinks" data-toggle="collapse">NEWS & LINKS</button>
		</span>
		
		<div class="collapse panel-border" id="newslinks">
			<br />
			
			<div class="row-fluid">
			
				<div class="col-sm-12">			
					<h5 class="green">RED BUTTE GARDEN CONSERVATION DEPARTMENT</h5>
		
					<p>Red Butte Garden Conservation Efforts at The University of Utah <a href="http://attheu.utah.edu/facultystaff/conservation-efforts/">Read the article</a></p>
					
					<hr width="98%">
					
					<h5 class="green">NATIVE PLANT MATERIALS RESEARCH</h5>
					
					<ul>
					
						<li>February 2016, "To Prevent Another Dust Bowl, the US Must Sow the Right Seeds." <a href="http://www.livescience.com/53574-if-wrong-seeds-planted-after-fires-us-could-face-modern-dust-bowl.html">Read the article</a></li>
						
						<li>January 2016, "The Promise and Peril of Wild Seed Harvesting." <a href="http://blog.nature.org/science/2016/01/14/promise-peril-wild-seed-harvesting-prairie-restoration/">Read the article</a></li>
						
						<li>August 2015, the U.S. Interior Department Releases the National Seed Strategy for Landscape Scale Rehabilitation and Restoration. <a href="http://www.blm.gov/wo/st/en/prog/more/fish__wildlife_and/plants/seedstrategy.html">The National Seed Strategy</a> outlines a comprehensive plan to guide ecological restoration across lands damaged by rangeland fires, invasive species, severe storms and drought. The Strategy emphasizes the importance of planting appropriate seeds to help grow plant life and pollinator habitat, which are critical natural defenses against climate change. The vision of the strategy is to ensure that the "right seed is in the right place at the right time". <a href="http://www.doi.gov/news/pressreleases/interior-department-releases-national-seed-strategy-for-landscape-scale-rehabilitation-and-restoration.cfm">Department of the Interior Press Release</a></li>
						
						<li>June 2014, President Obama released a memorandum creating a federal strategy to promote the health of honeybees and other pollinators. This “Pollinator Health Task Force” specifically includes recommendations for the use of native plants and their materials, which directly pertains to our department’s participation in the BLM Seeds of Success program. <a href="http://www.whitehouse.gov/the-press-office/2014/06/20/presidential-memorandum-creating-federal-strategy-promote-health-honey-b">White House Press Release</a></li>
						
						<li>June 2014, A response to the presidential memorandum on pollinators was published by NatureServe entitled <a href="“Confronting the Plight of Pollinators”">“Confronting the Plight of Pollinators”</a></li>
						
					</ul>
					
					
					<h5 class="green">SEED BANKING</h5>
					
					<ul>
					
						<li>March 2016, "Seed Banks: The living libraries that hold answers to disease, pest and climate problems." Dr. Christina Walters, researcher at the USDA, discusses seed banking at the National Center for Genetic Resources Preservation. <a href="http://www.abc.net.au/news/2016-03-28/seedbank-the-living-library-releasing-plants-in-emergencies/7263122">Read the article</a></li>
						
						<li>September 2015, The Washington Post reports on the Svalbard Global Seed Vault, and how it is already being used to restore plant genetic diversity to conflict-torn countries. According to Svalbard Director Cary Fowler "… You don’t have to have some kind of global catastrophe for this thing to be useful. We’re losing biodiversity right now, and it isn’t necessarily because of some global catastrophe.” <a href="http://www.washingtonpost.com/news/morning-mix/wp/2015/09/23/the-doomsday-seed-vault-that-preserves-the-food-of-the-past-and-ensures-its-future/">Read the article</a></li>
						
						<li>May 2013, Photography professor Dornith Doherty shares her work documenting international efforts for preserving biodiversity through seed banks, or as she calls them, “libraries of life”, in a 15-minute TEDx talk entitled <a href="https://www.youtube.com/watch?v=M79V10prO90">“Archiving Eden”</a></li>
					
					</ul>
					
					<h5 class="green">PLANTS IN THE NEWS</h5>
					
					<p><strong>Rare and Endangered Cacti:</strong></p>
					<p>February 2016, <a href="http://www.theatlantic.com/science/archive/2016/02/cactus-thieves/470070/">"Busting Cactus Smugglers in the American West"</a> from The Atlantic.</p>
					
					<p><strong>Holmgren's milkvetch (Astragalus holmgreniorum):</strong></p>
					<p>February 2016, researchers from Utah Valley University and the U.S. Forest Service installed seeds of this Endangered Species along the Utah/Arizona state line. Read the article and <a href="http://www.thespectrum.com/story/news/2016/02/12/saving-endangered-holmgren-milk-vetch/80312924">watch the video from The Spectrum here</a></p>
					
					<p><strong>Graham’s beardtongue (Penstemon grahamii) and White River beardtongue (Penstemon scariosus var. albifluvis):</strong></p>
					<p>August 2014, the U.S. Fish and Wildlife Service withdrew their proposal to list Graham’s beardtongue and White River beardtongue under the Endangered Species Act. A conservation agreement has been finalized between county, state and federal partners to reduce threats and promote the long-term persistence of these two species across their ranges in the Uinta Basin of Utah and Colorado.</p>
					
					<p>For more information, please visit:</p>
					
					<p><a href="https://www.fws.gov/mountain-prairie/species/plants/2utahbeardtongues/">U.S. Fish and Wildlife Service Penstemon Webpage</a></p>
					
					<p><a href="https://www.fws.gov/mountain-prairie/species/plants/2utahbeardtongues/Penstemon_Conservation_Agreement_2014Jul22_final_signed.pdf">Copy of the Final Conservation Agreement</a></p>
					
					<p><strong>Local Penstemon News Articles:</strong></p>
					
					<ul>
						<li>Salt Lake Tribune, <a href="http://www.sltrib.com/sltrib/mobile3/57909183-219/beardtongue-oil-plants-shale.html.csp">“Deal Reached to halt endangered listing for Utah flowers”</a></li>
						<li>Courthouse News Service, <a href="http://www.courthousenews.com/2013/08/09/60169.htm">“Oil Shale Development Threatens Rare Plants”.</a></li>
						<li>KUER, <a href="http://kuer.org/post/wildflowers-proposed-endangered-species-list">“Wildflowers Proposed for Endangered Species List”</a></li>
						<li>Salt Lake Tribune, <a href="http://www.sltrib.com/sltrib/politics/56693328-90/beardtongue-federal-graham-habitat.html.csp">“Feds propose listing two plants found only over Utah oil shale”</a></li>
					</ul>
					
					<p><strong>Gierisch’s globemallow (Sphaeralcea gierischii):</strong></p>
					<ul>
						<li>August 2013, The Salt Lake Tribune reports that the globemallow was listed as endangered due to threats from gypsum mining and motorized recreation. <a href="http://www.sltrib.com/sltrib/news/56729949-78/endangered-utah-mallow-gierisch.html.csp">Read the article.</a></li>
					</ul>
					
					<h5 class="green">Plant Resources:</h5>
					
					<ul>
						<li><a href="http://www.plants.usda.gov/java/">USDA Plants Database</a></li>
						<li><a href="http://www.natureserve.org/explorer/">NatureServe Explorer: An Online Encyclopedia of Life</a></li>
						<li><a href="http://www.wildflower.org/explore.php">NPIN: Native Plant Information Network</a></li>
					</ul>	
				
				</div>
				
			</div>
						
			<br />
		
		</div>
			
	</div>
	<!-- END NEWS AND LINKS PANEL -->
	
</div>


    </div>
  </div>
</div>

<!-- Google Analytics Code -->

<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-252478-3', 'auto');
  ga('send', 'pageview');

</script>

</body>

<!-- Begin Footer Code-->
<div id="prefooterbg">
	
	<div id="prefooter" class="container">
	
		<div class="row">
			<div id="empty1" class="col-sm-2">&nbsp;</div>
			<div class="col-sm-2"><a href="/memberships"><div class="footer-membership"></div></a></div>
			<div class="col-sm-4"><a href="https://55218.blackbaudhosting.com/55218/Annual-Gift"><div class="footer-donate"></div></a></div>
			<div class="col-sm-2"><a href="/volunteer"><div class="footer-volunteer"></div></a></div>
			<div id="empty2" class="col-sm-2">&nbsp;</div>
		</div>
		
	</div>
	
</div>

<div id="rbgfooterbg">

	<div id="rbgfooter" class="container">
	
			<br />
	
			<div id="social-media-wrapper">
				
				<ul>
					<li><a href="http://www.yelp.com/biz/red-butte-garden-and-arboretum-salt-lake-city"><div class="yelp"></div></a></li>
					<li><a href="http://www.tripadvisor.com/Attraction_Review-g60922-d269627-Reviews-Red_Butte_Garden-Salt_Lake_City_Utah.html"><div class="tripadvisor"></div></a></li>
					<li><a href="https://plus.google.com/115349740133726957245/about"><div class="googleplus"></div></a></li>
					<li><a href="https://www.facebook.com/redbutte"><div class="facebook"></div></a></li>
					<li><a href="https://instagram.com/redbuttegarden/"><div class="instagram"></div></a></li>
					<li><a href="https://twitter.com/redbuttegarden"><div class="twitter"></div></a></li>
					<li><a href="https://www.youtube.com/user/RedButteGarden"><div class="youtube"></div></a></li>
					<li><a href="http://www.redbuttegarden.org/social-media"><div class="snapchat"></div></a></li>
					<li><a href="http://www.reddit.com/r/redbuttegarden"><div class="reddit"></div></a></li>
					<li><a href="https://www.pinterest.com/redbuttegarden/"><div class="pinterest"></div></a>
				</ul>
				
			</div>
	
			<div class="space"><hr></div><div class="space"><hr></div><div class="space"><hr></div>
			
			<div class="rbgfooterlinks">
				<ul>
					<li><a href="/contact">CONTACT US</a>&nbsp;&nbsp;&nbsp;&nbsp;<span class="hide-mobile">|</span>&nbsp;&nbsp;&nbsp;</li>
					<li><a href="/advisory-board">BOARD</a>&nbsp;&nbsp;&nbsp;&nbsp;<span class="hide-mobile">|</span>&nbsp;&nbsp;&nbsp;</li>
					<li><a href="/local-retail-partners">LOCAL RETAIL PARTNERS</a>&nbsp;&nbsp;&nbsp;&nbsp;<span class="hide-mobile">|</span>&nbsp;&nbsp;&nbsp;</li>
					<li><a href="/press">PRESS</a>&nbsp;&nbsp;&nbsp;&nbsp;<span class="hide-mobile">|</span>&nbsp;&nbsp;&nbsp;</li>
					<li><a href="/publications">PUBLICATIONS</a>&nbsp;&nbsp;&nbsp;&nbsp;<span class="hide-mobile">|</span>&nbsp;&nbsp;&nbsp;</li>
					<li><a href="/general-info">INFO &amp; POLICIES</a>&nbsp;&nbsp;&nbsp;&nbsp;<span class="hide-mobile">|</span>&nbsp;&nbsp;&nbsp;</li>
					<li><a href="/employment">EMPLOYMENT</a>&nbsp;&nbsp;&nbsp;&nbsp;<span class="hide-mobile">|</span>&nbsp;&nbsp;&nbsp;</li>
					<li><a href="https://redbuttegarden.formstack.com/forms/donation_request_form" target="_blank">DONATION REQUEST</a>&nbsp;&nbsp;&nbsp;&nbsp;<span class="hide-mobile">|</span>&nbsp;&nbsp;&nbsp;</li>
					<li><a href="https://55218.blackbaudhosting.com/55218/page.aspx?pid=201" target="_blank">SIGN UP FOR OUR NEWSLETTER</a></li>
				</ul>
			</div>
			
		<div class="space"><hr></div>		
		
		<div class="row">
				
			<div id="uofu" class="col-lg-2"><a href="http://www.utah.edu"><div class="uofu"></div></a></div>
			<div id="footerlogo" class="col-lg-8"><a href="http://www.redbuttegarden.org"><div class="footerlogo"></div></a></div>
			<div id="zap" class="col-lg-2"><a href="http://www.zapisyou.org"><div class="zap"></div></a></div>
			
		</div>
		<div class="space"><hr></div>
		<div class="space"><hr></div>
		<div class="row">
	
			<div id="contactinfo1" class="col-sm-12">801.525.0556 | 300 WAKARA WAY, SALT LAKE CITY, UT 84108</div>
			<div id="contactinfo2" class="col-sm-12">Copyright &copy2016 Red Butte Garden</div>	
	
		</div>
		<div class="space"><hr></div>
		
		<div class="rbgfooterlinks">
			<ul>
				<li><a href="http://www.utah.edu/nondiscrimination/">NONDISCRIMINATION & ACCESSIBILITY</a>&nbsp;&nbsp;&nbsp;<span class="hide-mobile">|</span>&nbsp;&nbsp;&nbsp;</li>
				<li><a href="http://www.utah.edu/disclaimer/">DISCLAIMER</a>&nbsp;&nbsp;&nbsp;<span class="hide-mobile">|</span>&nbsp;&nbsp;&nbsp;</li>
				<li><a href="http://www.utah.edu/privacy/">PRIVACY</a>&nbsp;&nbsp;&nbsp;<span class="hide-mobile">|</span>&nbsp;&nbsp;&nbsp;</li>
				<li><a href="http://www.utah.edu/credits.php">CREDITS & ATTRIBUTIONS</a>&nbsp;&nbsp;&nbsp;</li>
			</ul>									
		</div>
		
	</div>

</div>
<!-- End Footer Code -->
<script>

// Code to load new CSS file to change dropdown colors for different seasons

function getStylesheet() {

  	var month = new Date().getMonth() + 1;

	if ( (month == 9) || (month == 10 ) || (month == 11) ) {
		document.write("<link rel='stylesheet' href='/CSS/fall.css?v=1' type='text/css'>");
	}
	
	if ( (month == 12) || (month == 1 ) || (month == 2) ) {
		document.write("<link rel='stylesheet' href='/CSS/winter.css?v=1' type='text/css'>");
	}
	
	if ( (month == 3) || (month == 4 ) || (month == 5) ) {
		document.write("<link rel='stylesheet' href='/CSS/spring.css?v=1' type='text/css'>");
	}
	
}

getStylesheet();

</script>

<noscript><link href="CSS/summer.css" rel="stylesheet"></noscript>