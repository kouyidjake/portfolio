<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>portfolio de Godwin</title>
    <link rel="stylesheet" href="mon portfolio.css">
</head>
<body>
    <header>
        <h3>KOUYIDJAKE YAO GODWIN</h3>
        <nav>
            <ul>
                <li><a href="#accueil"></a>Accueil</li>
                <li><a href="#about">A propos</a></li>
                <li><a href="#projets"> Projets</a></li>
                <li><a href="#commpetences">Competences</a></li>
                <li><a href="#interêt">Centre d'interêt</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section class="presentation">
    
            <div class="bienvenue">
                <h1>Bienvenue sur Mon portfolio</h1>
                <p>Je suis <span class="prenom">Godwin</span>, Développeur en devenir passioné par la creation de sites web modernes et le design!</p>
                <a href="#projets" class="btn"> Voir mes projets</a>
                
            </div>
            <div class="page-image">
                <img src="image.jpg.jpg" alt="image" width="" height="">

            </div>  
       
    </section>
    <section class="about" id="#about">
        <H2 class="propos">A propos</H2>
        <div class="content">
            
            <div class="police">
                <p> Je m'appelle <span class="prenom" >Godwin</span>, passionné par la création <br> de sites web modernes et interactifs.</p>
                <p> Je suis actuellement étudiant en développement <br> web et je cherche à développer mes commpetences <br> en javascript, HTML et CSS.</p>
                <a href="#" class="bnt">Télécharger mon CV</a>
            </div>
            <img src="god.jpg.jpg" class="profile-img" alt="Ma photo" width="300" height="200">
        </div>
    </section>

    <section class="projets" id="#projets" >
        <h2>Mes Projets</h2>
        <div class="projets">
            <div class="projet-card">
                <h3>Un mini-jeu interactif en JavaScript</h3>
                <p>Un mini-jeu développé en JavaScript qui utilise DOM.</p>
                <a href="#" class="btn"> Voir </a>
            </div>
            <div class="projet-card">
        <h3>Un mini-site interactif</h3>
        <p>Un mini-site développé en javascript qui affiche des informations dynamiques.</p>
        <a href="#" class="btn"> Voir</a>
        </div>
        </div>
    </section>
    
    <section id="skills" class="skills-section">
        <h2 class="competence">Mes Competences</h2>
        
        
    <div class="skills">
        <div>
            <div>
                <h3>Soft skills</h3>
                
            </div>
            
            <div class="skills-box">
                <span>gestion de Projet</span>
                <div class="progress-bar">
                    <div class="progress"style="width: 70%;"></div>
                </div>
            </div>
            
            <div class="skills-box">
                <span>Resolution de Problème</span>
                <div class="progress-bar">
                    <div class="progress"style="width: 70%;"></div>
                </div>
            </div>
            
                <div class="skills-box">
                    <span>Adaptabilité</span>
                    <div class="progress-bar">
                    <div class="progress"style="width: 60%;"></div>
                </div>
                </div>
            
            
                <div class="skills-box">
                    <SPan>Creaivité</SPan>
                    <div class="progress-bar">
                        <div class="progress"style="width: 90%;"></div>
                    </div>
                </div>
            </div>
            
        </div>
    
        <div class="hardskills">
            <div>
                <h3>Hard skills</h3>
                
            </div>
            
            <div class="skills-box">
                <span>HTML</span>
                <div class="progress-bar">
                    <div class="progress"style="width: 90%;"></div>
                </div>
            </div>
            
            <div class="skills-box">
                <span>CSS</span>
                <div class="progress-bar">
                    <div class="progress"style="width: 90%;"></div>
                </div>
            </div>
            
                <div class="skills-box">
                    <span>JavaScript</span>
                    <div class="progress-bar">
                    <div class="progress"style="width: 80%;"></div>
                </div>
                </div>
            
            
                <div class="skills-box">
                    <SPan>Vs code </SPan>
                    <div class="progress-bar">
                        <div class="progress"style="width: 90%;"></div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    </section>

    <section class="interêt">
            <h2 class="center">Centre d'interêt</h2>
            <div class="centre">
                <div class="containe-interêt">
        <ul>
            <li> Lecteure</li>
            <li>Sport</li>
            <li>Football</li>
            <li> Tourisme</li>
        </ul>

                </div>

            </div>

    </section>

    
    <section class="contact">
        <div class="text-contact"></div>
             <h2>Vous avez un projet en tête ?<br><span class="t-prenom">N'hésitez pas à me contacter</span></h2>
        
        <form action="">
            <label for="name">Nom</label>
            <input type="text" id="name"required>

            <label for="email">Email</label>
            <input type="email" id="email" required>

            <label for="message">Message</label>
            <textarea id="message" rows="4" required></textarea>
            <button type="submit" class="btn"> Envoyer</button>
        </form>
    </section>

    <footer>
        <p>Designed by Godwin. All rights reserved &copy;2019</p>
    </footer>
</body>
</html>
