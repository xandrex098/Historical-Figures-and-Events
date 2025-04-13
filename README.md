# Historical Figures and Events

This program is all about exploring significant historical figures and major events that shaped the world. It aims to inform and educate users by presenting history in an interactive and engaging way.

This project was developed as part of our defense for the 2nd semester of our 1st year in college at PHINMA Cagayan de Oro College (PHINMA COC).


This is Our Code

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>EDSA People Power Revolution</title>
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap">
    <link rel="stylesheet" href="style.css">
    <script>
        function toggleDetails(id) {
            var x = document.getElementById(id);
            if (x.classList.contains("w3-show")) {
                x.classList.remove("w3-show");
            } else {
                x.classList.add("w3-show");
            }
        }
    </script>
</head>
<body>

    <!-- Navigation Bar -->
    <div class="w3-bar w3-black w3-top w3-padding w3-card">
        <a href="#" class="w3-bar-item w3-button w3-hover-yellow">🏠 Home</a>
        <a href="#background" class="w3-bar-item w3-button w3-hover-yellow">📖 Background</a>
        <a href="#timeline" class="w3-bar-item w3-button w3-hover-yellow">📅 Timeline</a>
        <a href="#figures" class="w3-bar-item w3-button w3-hover-yellow">👥 Key Figures</a>
        <a href="#impact" class="w3-bar-item w3-button w3-hover-yellow">🌍 Impact</a>
    </div>

    <div class="w3-container w3-center w3-padding-64" 
    style="position: relative; background: url('https://tse4.mm.bing.net/th?id=OIP.zrqpcBZCjFE9-IbW8751SwHaEz&pid=Api') no-repeat center center; background-size: cover; color: white;">

    <!-- Semi-transparent overlay -->
    <div style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background: rgba(0, 0, 0, 0.5);"></div>

    <!-- Text content -->
    <div style="position: relative;">
        <h2 class="w3-text-shadow"><strong>📜 The EDSA People Power Revolution</strong></h2>
        <p class="w3-large w3-text-shadow">A peaceful movement that restored democracy in the Philippines.</p>
    </div>
</div>




    <!-- Background Section -->
<section id="background" class="w3-container w3-padding-64" 
style="position: relative; background: url('https://upload.wikimedia.org/wikipedia/commons/7/7e/EDSA_Revolution_%281986%29.jpg') no-repeat center center; background-size: cover; color: white;">

<!-- Semi-transparent overlay -->
<div style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background: rgba(0, 0, 0, 0.5);"></div>

<!-- Content -->
<div style="position: relative;">
    <h2 class="w3-center">📖 Background</h2>
    <p>
        The EDSA People Power Revolution was a historic four-day uprising in February 1986 that led to the peaceful overthrow of the dictatorship of President Ferdinand Marcos.
        This revolution was the result of decades of corruption, human rights violations, and political repression. The assassination of opposition leader 
        <strong>Benigno "Ninoy" Aquino Jr.</strong> in 1983 was a turning point that sparked mass protests, leading to widespread calls for democracy.
    </p>
    <p>
        Marcos ruled the Philippines for 21 years, declaring <strong>Martial Law in 1972</strong>, which granted him absolute power. His regime was marked by censorship, suppression of
        dissent, and a deteriorating economy due to corruption. The opposition, led by <strong>Corazon "Cory" Aquino</strong> (widow of Ninoy Aquino), gained massive public support.
        When Marcos called for <strong>snap elections in 1986</strong>, widespread fraud led to mass protests, culminating in the EDSA Revolution.
    </p>
    <p>
        Over <strong>two million Filipinos</strong> gathered along <strong>Epifanio de los Santos Avenue (EDSA)</strong> in Metro Manila, forming human barricades, praying, and peacefully
        protesting. Soldiers and tanks sent by Marcos refused to attack civilians, and on <strong>February 25, 1986, Marcos fled to Hawaii</strong>, marking the triumph of the people.
    </p>
</div>
</section>


    <!-- Interactive Timeline Section -->
<section id="timeline" class="w3-container w3-padding-64" 
style="position: relative; background: url('https://upload.wikimedia.org/wikipedia/commons/b/b3/EDSA_Revolution_%281986%29_-_People_Power.jpg') no-repeat center center; background-size: cover; color: white;">

<!-- Semi-transparent overlay -->
<div style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background: rgba(0, 0, 0, 0.5);"></div>

<!-- Content -->
<div style="position: relative;">
    <h2 class="w3-center">📅 Timeline of Events</h2>

        <div class="w3-card w3-hover-shadow w3-padding w3-margin">
            <h4 onclick="toggleDetails('event1')" class="w3-hover-text-blue">📍 August 21, 1983 - Assassination of Ninoy Aquino ⬇️</h4>
            <div id="event1" class="w3-container w3-hide w3-padding w3-light-grey">
                <p>
                    Senator <strong>Benigno "Ninoy" Aquino Jr.</strong> was one of the fiercest critics of President <strong>Ferdinand Marcos</strong>. 
                    After three years of self-imposed exile in the United States, Aquino decided to return to the Philippines despite warnings of danger. 
                    As he disembarked from <strong>China Airlines Flight 811</strong> at <strong>Manila International Airport</strong> 
                    (now <strong>Ninoy Aquino International Airport</strong>), he was assassinated on the tarmac.
                </p>
                <p>
                    The official government report blamed the assassination on a lone gunman, <strong>Rolando Galman</strong>, but many believed it was 
                    a state-ordered execution. The public outcry was immediate, with millions mourning Aquino’s death and calling for an end to the 
                    Marcos dictatorship. His funeral procession on <strong>August 31, 1983</strong>, lasted over <strong>11 hours</strong> and was attended 
                    by <strong>over 2 million people</strong>, marking one of the largest demonstrations against Marcos at the time.
                </p>
            </div>
        </div>
        
        

        <div class="w3-card w3-hover-shadow w3-padding w3-margin">
            <h4 onclick="toggleDetails('event2')" class="w3-hover-text-blue">📍 November 3, 1985 - Marcos Calls for Snap Elections ⬇️</h4>
            <div id="event2" class="w3-container w3-hide w3-padding w3-light-grey">
                <p>
                    On <strong>November 3, 1985</strong>, during an interview on the American television program <strong>"This Week with David Brinkley"</strong>, 
                    President <strong>Ferdinand Marcos</strong> unexpectedly announced that he would hold a <strong>snap presidential election</strong> in early 1986, 
                    a year ahead of schedule. The move was seen as an attempt to prove his legitimacy and silence growing opposition, especially after increasing 
                    international pressure and domestic unrest following the assassination of <strong>Benigno "Ninoy" Aquino Jr.</strong> in 1983.
                </p>
                <p>
                    The decision came as a surprise to many, including Marcos' own political allies. It was widely believed that U.S. President <strong>Ronald Reagan</strong>, 
                    a long-time supporter of Marcos, had advised him to seek a fresh mandate to counter allegations of dictatorship and fraud. The snap election, however, 
                    would prove to be a critical moment that led to the downfall of the Marcos regime, as it triggered massive protests and exposed widespread election fraud.
                </p>
            </div>
        </div>
        
        

        <div class="w3-card w3-hover-shadow w3-padding w3-margin">
            <h4 onclick="toggleDetails('event3')" class="w3-hover-text-blue">📍 February 7, 1986 - Snap Elections Held ⬇️</h4>
            <div id="event3" class="w3-container w3-hide w3-padding w3-light-grey">
                <p>
                    On <strong>February 7, 1986</strong>, the highly anticipated <strong>snap elections</strong> took place between 
                    <strong>President Ferdinand Marcos</strong> and opposition leader <strong>Corazon "Cory" Aquino</strong>. 
                    The election was marked by widespread reports of <strong>voter intimidation, ballot tampering, and fraud</strong>, 
                    leading to accusations that Marcos was manipulating the results to stay in power.
                </p>
                <p>
                    As ballots were counted, conflicting results emerged. The <strong>Commission on Elections (COMELEC)</strong>, 
                    controlled by Marcos, declared him the winner, while the independent <strong>National Citizens' Movement for Free Elections (NAMFREL)</strong> 
                    showed <strong>Aquino leading</strong>. International observers, including the <strong>United States and the Catholic Church</strong>, 
                    condemned the elections as fraudulent.
                </p>
                <p>
                    In response to the fraud, <strong>computer technicians from COMELEC walked out</strong> in protest, publicly exposing election rigging. 
                    This event further fueled national outrage, leading to mass protests and setting the stage for the <strong>EDSA People Power Revolution</strong>.
                </p>
            </div>
        </div>
        
        
        

        <div class="w3-card w3-hover-shadow w3-padding w3-margin">
            <h4 onclick="toggleDetails('event4')" class="w3-hover-text-blue">📍 February 22, 1986 - Military Defections Begin ⬇️</h4>
            <div id="event4" class="w3-container w3-hide w3-padding w3-light-grey">
                <p>
                    On <strong>February 22, 1986</strong>, tensions within the Philippine military reached a breaking point when 
                    <strong>Defense Minister Juan Ponce Enrile</strong> and <strong>General Fidel Ramos</strong> publicly broke away from the Marcos regime. 
                    They, along with the <strong>Reform the Armed Forces Movement (RAM)</strong>—a group of reformist officers—had originally planned a coup against 
                    <strong>President Ferdinand Marcos</strong>. However, their plans were discovered, forcing them to abandon the coup and instead take refuge 
                    in <strong>Camp Aguinaldo</strong> before moving to <strong>Camp Crame</strong>.
                </p>
                <p>
                    Realizing the urgency of the situation, <strong>Jaime Cardinal Sin</strong>, the influential Archbishop of Manila, used <strong>Radio Veritas</strong> 
                    to call on the Filipino people to support the defectors. In response, thousands of civilians, including priests, nuns, and ordinary citizens, 
                    gathered along <strong>EDSA</strong>, forming a human barricade around the military camps. They brought food, flowers, and rosaries, turning what could 
                    have been a violent standoff into a peaceful demonstration of unity.
                </p>
                <p>
                    As the crowds grew, military support for Marcos began to crumble. Several key military commanders defected, refusing to follow orders to attack <strong>Camp Crame</strong>. 
                    The situation escalated when Marcos attempted to deploy tanks and heavily armed soldiers, but civilians blocked their path, kneeling in prayer and pleading for peace. 
                    Some soldiers, moved by the people’s resolve, abandoned their posts and joined the uprising.
                </p>
                <p>
                    This momentous event marked the beginning of the <strong>EDSA People Power Revolution</strong>, a four-day movement that would ultimately lead to the downfall of Marcos. 
                    Overwhelmed by the mass civilian resistance and the loss of military support, Marcos was forced to flee the country on <strong>February 25, 1986</strong>, 
                    ending his two-decade rule.
                </p>
            </div>
        </div>
        
        

        <div class="w3-card w3-hover-shadow w3-padding w3-margin">
            <h4 onclick="toggleDetails('event5')" class="w3-hover-text-blue">📍 February 23-25, 1986 - Mass Civilian Protests ⬇️</h4>
            <div id="event5" class="w3-container w3-hide w3-padding w3-light-grey">
                <p>
                    By <strong>February 23, 1986</strong>, the streets of <strong>Epifanio de los Santos Avenue (EDSA)</strong> were filled with over <strong>two million Filipinos</strong> 
                    from all walks of life—ordinary citizens, priests, nuns, students, professionals, and activists—gathering in peaceful protest against the 
                    Marcos regime. Carrying rosaries, flowers, and banners, they demanded an end to dictatorship and the recognition of <strong>Corazon "Cory" Aquino</strong> 
                    as the rightful leader.
                </p>
                <p>
                    As the protest grew, <strong>Marcos ordered troops and tanks</strong> to disperse the crowd and attack <strong>Camp Crame</strong>, where 
                    the defecting military officers, led by <strong>Juan Ponce Enrile</strong> and <strong>Fidel Ramos</strong>, had taken their stand. 
                    However, in a powerful act of nonviolent resistance, the people linked arms, knelt before the advancing tanks, and prayed. Many soldiers, 
                    moved by the courage of the protesters, <strong>refused to open fire</strong> and instead defected, joining the revolution.
                </p>
                <p>
                    On <strong>February 24</strong>, Marcos, still clinging to power, attempted to declare a <strong>state of emergency</strong> and called for 
                    reinforcements. However, the defection of key military leaders, including <strong>General Artemio Tadiar</strong> and 
                    <strong>Major General Renato de Villa</strong>, left him with dwindling support. International pressure, especially from the 
                    <strong>United States</strong>, also played a significant role in isolating Marcos.
                </p>
                <p>
                    Finally, on <strong>February 25, 1986</strong>, two historic inaugurations took place: <strong>Corazon Aquino</strong> was sworn in as the 
                    new President at Club Filipino, while <strong>Marcos held his own oath-taking ceremony</strong> at Malacañang Palace. However, by nightfall, 
                    realizing he had lost control, Marcos and his family were forced to flee to <strong>Hawaii</strong> with U.S. assistance, marking the 
                    end of his <strong>two-decade rule</strong> and the victory of the <strong>People Power Revolution</strong>.
                </p>
            </div>
        </div>
        
        <div class="w3-card w3-hover-shadow w3-padding w3-margin">
            <h4 onclick="toggleDetails('event6')" class="w3-hover-text-blue">📍 February 25, 1986 - Marcos Flees the Philippines ⬇️</h4>
            <div id="event6" class="w3-container w3-hide w3-padding w3-light-grey">
                <p>
                    On <strong>February 25, 1986</strong>, the Philippines witnessed the culmination of the <strong>People Power Revolution</strong>. 
                    As protests surged and military defections continued, it became clear that <strong>Ferdinand Marcos</strong> could no longer maintain his grip on power.
                </p>
                <p>
                    That morning, two separate presidential inaugurations took place. <strong>Corazon "Cory" Aquino</strong>, the opposition leader, was sworn in 
                    as the legitimate President of the Philippines at <strong>Club Filipino</strong> in San Juan, surrounded by thousands of supporters. Meanwhile, 
                    in a desperate attempt to cling to power, Marcos held his own inauguration at <strong>Malacañang Palace</strong>, attended by a small group of 
                    loyal followers.
                </p>
                <p>
                    However, the situation quickly deteriorated for Marcos. His remaining allies, including his defense chief, had either <strong>defected</strong> or 
                    advised him to step down. The U.S. government, under President <strong>Ronald Reagan</strong>, also withdrew its support, urging Marcos to leave 
                    peacefully to avoid bloodshed.
                </p>
                <p>
                    As night fell, Marcos and his family were escorted by U.S. helicopters to <strong>Clark Air Base</strong> in Pampanga before boarding a U.S. 
                    Air Force plane bound for <strong>Hawaii</strong>. This marked the end of his <strong>21-year rule</strong> and the triumph of the Filipino people's 
                    call for democracy.
                </p>
                <p>
                    The departure of Marcos was met with celebration across the nation. Filipinos flooded the streets, cheering, crying, and embracing one another. 
                    The dictatorship had fallen, and the Philippines had entered a new era of democracy and hope.
                </p>
            </div>
        </div>
        

    </section>

   <!-- Key Figures Section -->
<section id="figures" class="w3-container w3-padding-64 w3-dark-grey">
    <h2 class="w3-center">👥 Key Figures of the EDSA Revolution</h2>
    
    <div class="w3-row-padding w3-center">
        
        <!-- Corazon Aquino -->
        <div class="w3-third w3-padding">
            <div class="w3-card w3-hover-shadow w3-white">
                <img src="Corazon_Aquino_1986.jpg" 
                     alt="Corazon Aquino" class="responsive-img">
                <div class="w3-container">
                    <h4><b>Corazon Aquino</b></h4>
                    <p><b>Role:</b> 11th President of the Philippines (1986-1992)</p>
                    <p><b>Born:</b> January 25, 1933</p>
                    <p><b>Died:</b> August 1, 2009</p>
                    <p><b>Contributions:</b> Led the opposition against Marcos, became the first female president of the Philippines, and restored democracy.</p>
                </div>
            </div>
        </div>

        <!-- Ferdinand Marcos -->
        <div class="w3-third w3-padding">
            <div class="w3-card w3-hover-shadow w3-white">
                <img src="Ferdinand_Marcos_(cropped).jpg" 
                     alt="Ferdinand Marcos" class="responsive-img">
                <div class="w3-container">
                    <h4><b>Ferdinand Marcos</b></h4>
                    <p><b>Role:</b> 10th President of the Philippines (1965-1986)</p>
                    <p><b>Born:</b> September 11, 1917</p>
                    <p><b>Died:</b> September 28, 1989</p>
                    <p><b>Contributions:</b> Ruled the Philippines under Martial Law; his dictatorship led to the rise of the People Power movement.</p>
                </div>
            </div>
        </div>

        <!-- Benigno "Ninoy" Aquino Jr. -->
        <div class="w3-third w3-padding">
            <div class="w3-card w3-hover-shadow w3-white">
                <img src="220px-Ninoy_Aquino.jpg" 
                     alt="Ninoy Aquino" class="responsive-img">
                <div class="w3-container">
                    <h4><b>Benigno "Ninoy" Aquino Jr.</b></h4>
                    <p><b>Role:</b> Opposition Leader</p>
                    <p><b>Born:</b> November 27, 1932</p>
                    <p><b>Died:</b> August 21, 1983</p>
                    <p><b>Contributions:</b> Marcos' top critic; his assassination ignited national protests and led to the downfall of the Marcos regime.</p>
                </div>
            </div>
        </div>
    </div> <!-- End of First Row -->

    <div class="w3-row-padding w3-center w3-margin-top">
        <!-- Juan Ponce Enrile -->
        <div class="w3-third w3-padding">
            <div class="w3-card w3-hover-shadow w3-white">
                <img src="Juan_Ponce_Enrile_COC_2019_elections_filing_(cropped).jpg" 
                     alt="Juan Ponce Enrile" class="responsive-img">
                <div class="w3-container">
                    <h4><b>Juan Ponce Enrile</b></h4>
                    <p><b>Role:</b> Minister of National Defense</p>
                    <p><b>Born:</b> February 14, 1924</p>
                    <p><b>Contributions:</b> Initially a Marcos ally, he defected during the EDSA Revolution and helped lead the military uprising.</p>
                </div>
            </div>
        </div>

        <!-- Fidel V. Ramos -->
        <div class="w3-third w3-padding">
            <div class="w3-card w3-hover-shadow w3-white">
                <img src="Fidel_Valdez_Ramos_Official_Photo_as_President_of_the_Philippines_(1995).jpg" 
                     alt="Fidel V. Ramos" class="responsive-img">
                <div class="w3-container">
                    <h4><b>Fidel V. Ramos</b></h4>
                    <p><b>Role:</b> Vice Chief of Staff of the Armed Forces</p>
                    <p><b>Born:</b> March 18, 1928</p>
                    <p><b>Died:</b> July 31, 2022</p>
                    <p><b>Contributions:</b> Defected from Marcos' forces and played a key role in the success of the EDSA Revolution.</p>
                </div>
            </div>
        </div>

        <!-- Jaime Cardinal Sin -->
        <div class="w3-third w3-padding">
            <div class="w3-card w3-hover-shadow w3-white">
                <img src="Cardinal_Jaime_Sin_in_1988.jpg" 
                     alt="Jaime Cardinal Sin" class="responsive-img">
                <div class="w3-container">
                    <h4><b>Jaime Cardinal Sin</b></h4>
                    <p><b>Role:</b> Archbishop of Manila</p>
                    <p><b>Born:</b> August 31, 1928</p>
                    <p><b>Died:</b> June 21, 2005</p>
                    <p><b>Contributions:</b> Used radio broadcasts to call people to support the military defectors, making him a key figure in the revolution.</p>
                </div>
            </div>
        </div>

        <!-- The Filipino People -->
<div class="w3-third w3-padding">
    <div class="w3-card w3-hover-shadow w3-white">
        <img src="edsa_people_power_revolution_1986-1.jpg" 
             alt="The Filipino People" class="responsive-img">
        <div class="w3-container">
            <h4><b>The Filipino People</b></h4>
            <p><b>Role:</b> Heroes of the People Power Revolution</p>
            <p><b>Contribution:</b> Millions of ordinary citizens—students, workers, priests, nuns, professionals, and entire families—took to the streets of EDSA in peaceful protest. Their unity, courage, and faith brought down a dictatorship without violence and restored democracy in the Philippines.</p>
        </div>
    </div>
</div>
    </div> <!-- End of Second Row -->
</section>

<style>
/* Responsive Image Styling */
.responsive-img {
    width: 100%; /* Image takes full width of the container */
    height: auto; /* Keeps the aspect ratio */
    object-fit: cover; /* Ensures it fills the container properly */
    border-top-left-radius: 5px; /* Slight rounded corners */
    border-top-right-radius: 5px;
}
</style>

<!-- Multimedia Gallery Section -->
<section id="multimedia" class="w3-container w3-padding-64 w3-light-grey">
    <h2 class="w3-center">🎞️ Multimedia Gallery</h2>
    <p class="w3-center w3-large">Experience the EDSA Revolution through photos, videos, and audio.</p>

    <!-- EDSA Timeline Slideshow -->
<div class="w3-content w3-display-container w3-margin-top" style="max-width:800px">
    <div class="mySlides w3-center">
        <img src="Ninoy-funeral-from-Time-mag.jpeg" style="width:100%">
        <p class="w3-padding w3-white">📍 August 1983 - Filipinos begin rallying after the assassination of Ninoy Aquino.</p>
    </div>
    
    <div class="mySlides w3-center">
        <img src="1986-snap-election-sham.jpg" style="width:100%">
        <p class="w3-padding w3-white">📍 February 1986 - Citizens protest alleged fraud after the snap elections.</p>
    </div>

    <div class="mySlides w3-center">
        <img src="18135048-edsa002-a_cover_2000x1491.webp" style="width:100%">
        <p class="w3-padding w3-white">📍 February 22, 1986 - First protesters gather outside Camps Crame and Aguinaldo to protect rebel soldiers.</p>
    </div>

    <div class="mySlides w3-center">
        <img src="image-asset.png" style="width:100%">
        <p class="w3-padding w3-white">📍 February 23, 1986 - The crowd on EDSA grows rapidly, including priests, nuns, students, and civilians.</p>
    </div>

    <div class="mySlides w3-center">
        <img src="1986_Peopple_Power_Nuns_Rosary.jpg" style="width:100%">
        <p class="w3-padding w3-white">📍 February 24, 1986 - Protesters form human barricades and pray in front of military tanks.</p>
    </div>

    <div class="mySlides w3-center">
        <img src="marcos_flees.jpg" style="width:100%">
        <p class="w3-padding w3-white">📍 February 25, 1986 - Celebration erupts as Marcos flees the country; People Power triumphs.</p>
    </div>

    <button class="w3-button w3-black w3-display-left" onclick="plusDivs(-1)">❮</button>
    <button class="w3-button w3-black w3-display-right" onclick="plusDivs(1)">❯</button>
</div>


    <!-- Embedded Videos -->
    <div class="w3-container w3-padding-32">
        <h3 class="w3-center">🎥 People Power Revolution Documentary</h3>
        <div class="w3-center">
          <iframe width="100%" height="415" 
                  src="https://www.youtube.com/embed/1EYu9wlBCxs?start=02"
                  title="People Power Revolution 1986 Documentary" 
                  frameborder="0" 
                  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
                  allowfullscreen>
          </iframe>
        </div>
      </div>
      <div class="w3-container w3-padding-32">
        <h3 class="w3-center">🎥 Cory Aquino Speech - 1986</h3>
        <div class="w3-center">
          <iframe width="100%" height="415" 
                  src="https://www.youtube.com/embed/9bavnuT4RlU?start=13"
                  title="Corazon Aquino - U.S. Congress Speech (Audio Enhanced)" 
                  frameborder="0" 
                  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
                  allowfullscreen>
          </iframe>
        </div>
      </div>

    <!-- Audio Clips -->
    <div class="w3-row-padding w3-margin-top">
        <div class="w3-third w3-padding">
            <div class="w3-card w3-white w3-padding">
                <h5>🎙️ Radyo Veritas Broadcast 1</h5>
                <audio controls>
                    <source src="People Power Revolution of 1986 February 23 Sunday Part 2 of 2.mp3" type="audio/mpeg">
                    Your browser does not support the audio element.
                </audio>
            </div>
        </div>

        <div class="w3-third w3-padding">
            <div class="w3-card w3-white w3-padding">
                <h5>🎙️ Radyo Veritas Broadcast 2</h5>
                <audio controls>
                    <source src="Jaime Cardinal Sin urging people to go to EDSA in 1986.mp3" type="audio/mpeg">
                    Your browser does not support the audio element.
                </audio>
            </div>
        </div>

        <div class="w3-third w3-padding">
            <div class="w3-card w3-white w3-padding">
                <h5>🎙️ People Power Chant</h5>
                <audio controls>
                    <source src="Bayan ko - Freddie Aguilar (EDSA REVOLUTION FEB.22-25, 1986).mp3" type="audio/mpeg">
                    Your browser does not support the audio element.
                </audio>
            </div>
        </div>
    </div>
</section>

<!-- Legacy & Impact Section -->
<section id="legacy" class="w3-container w3-padding-64">
    <h2 class="w3-center">📜 Legacy & Impact of the EDSA Revolution</h2>

    <!-- Before & After Comparison -->
    <div class="w3-row-padding w3-margin-top">
        <div class="w3-half">
            <h3 class="w3-center">Before EDSA</h3>
            <ul class="w3-ul w3-border w3-white">
                <li>🛑 Dictatorship under Ferdinand Marcos</li>
                <li>🚫 Suspension of civil rights during Martial Law</li>
                <li>💰 Rampant corruption and economic decline</li>
                <li>🩸 Political killings and suppression of media</li>
            </ul>
        </div>
        <div class="w3-half">
            <h3 class="w3-center">After EDSA</h3>
            <ul class="w3-ul w3-border w3-pale-green">
                <li>✅ Democracy restored under Corazon Aquino</li>
                <li>🗳 Free elections resumed</li>
                <li>📰 Freedom of speech and the press returned</li>
                <li>👥 Rise of civil society and activism</li>
            </ul>
        </div>
    </div>


    <!-- Engagement Section -->
    <div class="w3-margin-top w3-padding-32 w3-light-grey">
        <h3 class="w3-center">🗣 Testimonials & Reflections</h3>
        <div class="w3-panel w3-leftbar w3-border-blue w3-pale-blue">
            <p>"I stood at EDSA with my family, praying and hoping. It was the most powerful moment of unity I've ever felt." – <i>Luz B., protester</i></p>
        </div>
        <div class="w3-panel w3-leftbar w3-border-green w3-pale-green">
            <p>"EDSA taught us that people united can never be defeated." – <i>Mark R., student leader</i></p>
        </div>
    </div>

<!-- Impact of EDSA Revolution -->
<section id="impact" class="w3-container w3-padding-64 w3-light-grey">
    <h2 class="w3-center">🌏 Impact of the EDSA Revolution</h2>
    
    <div class="w3-row-padding w3-center">
        
        <!-- End of Dictatorship -->
        <div class="w3-third w3-padding">
            <div class="w3-card w3-hover-shadow w3-white w3-padding">
                <h4><b>End of Dictatorship</b></h4>
                <p>The revolution successfully ousted Ferdinand Marcos, ending his 20-year rule and paving the way for a democratic government.</p>
            </div>
        </div>

        <!-- Restoration of Democracy -->
        <div class="w3-third w3-padding">
            <div class="w3-card w3-hover-shadow w3-white w3-padding">
                <h4><b>Return of Democratic Institutions</b></h4>
                <p>EDSA restored democratic processes, allowing free elections, press freedom, and judicial independence.</p>
            </div>
        </div>

        <!-- Global Influence -->
        <div class="w3-third w3-padding">
            <div class="w3-card w3-hover-shadow w3-white w3-padding">
                <h4><b>Inspiration for Other Movements</b></h4>
                <p>The peaceful revolution inspired similar uprisings in countries like South Korea, Taiwan, and Eastern Europe.</p>
            </div>
        </div>
    </div> <!-- End of First Row -->

    <div class="w3-row-padding w3-center w3-margin-top">
        <!-- Economic Impact -->
        <div class="w3-third w3-padding">
            <div class="w3-card w3-hover-shadow w3-white w3-padding">
                <h4><b>Economic Struggles</b></h4>
                <p>Despite political success, the Philippines faced economic challenges due to debt, corruption, and unstable governance.</p>
            </div>
        </div>

        <!-- Continued Political Challenges -->
        <div class="w3-third w3-padding">
            <div class="w3-card w3-hover-shadow w3-white w3-padding">
                <h4><b>Ongoing Political Issues</b></h4>
                <p>Political dynasties and corruption remained major problems despite the revolution's success.</p>
            </div>
        </div>

        <!-- People's Power Legacy -->
        <div class="w3-third w3-padding">
            <div class="w3-card w3-hover-shadow w3-white w3-padding">
                <h4><b>Legacy of People Power</b></h4>
                <p>EDSA proved that peaceful protests could bring real change, influencing future generations of activists.</p>
            </div>
        </div>
    </div> <!-- End of Second Row -->
</section>

<!-- Sources / References -->
<section id="sources" class="w3-container w3-padding-64 w3-dark-grey">
    <h2 class="w3-center">📚 Sources & References</h2>
    
    <div class="w3-container w3-padding-32">
        <ul class="w3-ul w3-card w3-white">
            <li><b>Books & Articles:</b> 
                - "The Philippines: A Past Revisited" by Renato Constantino  
                - "The Aquino Revolution" by Nick Joaquin  
            </li>
            <li><b>Government & Academic Sources:</b>  
                - Official Gazette of the Republic of the Philippines  
                - University of the Philippines - Diliman Research Archives  
            </li>
            <li><b>News & Reports:</b>  
                - BBC News - "EDSA People Power: A Look Back"  
                - CNN Philippines - "The Legacy of EDSA Revolution"  
                - Philippine Daily Inquirer Archives  
            </li>
            <li><b>Images & Media:</b>  
                - National Historical Commission of the Philippines  
                - Public domain images from government archives  
                - Various licensed sources for historical images  
            </li>
        </ul>
    </div>
</section>

    <!-- Footer -->
    <footer class="w3-container w3-black w3-padding-16 w3-center">
        <p>📜 EDSA Revolution | Educational Website | Made for Students</p>
    </footer>

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>EDSA Revolution</title>
        <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
        <style>
            /* Back to Top Button */
            .back-to-top {
                position: fixed;
                bottom: 20px;
                right: 20px;
                background-color: #4CAF50;
                color: white;
                border: none;
                padding: 15px;
                border-radius: 50%;
                font-size: 20px;
                cursor: pointer;
                display: none;
            }
    
            .back-to-top:hover {
                background-color: #45a049;
            }
    
            /* For smoother scrolling */
            html {
                scroll-behavior: smooth;
            }
        </style>
    </head>
    <body>
    
    <!-- Back to Top Button -->
    <button class="back-to-top" onclick="scrollToTop()">↑</button>
    
    <!-- JavaScript to show/hide Back to Top button -->
    <script>
        // Get the button
        var mybutton = document.getElementsByClassName("back-to-top")[0];
    
        // When the user scrolls down 20px from the top of the document, show the button
        window.onscroll = function() {
            if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
                mybutton.style.display = "block";
            } else {
                mybutton.style.display = "none";
            }
        };
    
        // When the user clicks the button, scroll to the top of the document
        function scrollToTop() {
            document.body.scrollTop = 0; // For Safari
            document.documentElement.scrollTop = 0; // For Chrome, Firefox, IE, and Opera
        }
    </script>
    
    </body>
    </html>
    

</body>
</html>
