# cheatcodelnd
<!-- MODEL 1 - EXERCISE 1 (Justo debajo de header) -->
<section id="exercise-one-section" class="exercise-one">
    <h2 class="exercise-one-title">Ejercicio 1</h2>
    <div class="exercise-one-container">
        <article class="exercise-one-box">
            <h3 class="box-title-centered">Tareas para Halloween</h3>
            <ul class="unordered-task-list">
                <li>Ir de fiesta</li>
                <li>Divertirse mucho</li>
                <li>No pasar miedo</li>
                <li>Hacer una página web de Halloween</li>
                <li>Reírse al leer la tarea anterior</li>
            </ul>
        </article>
        <article class="exercise-one-box">
            <h3 class="box-title-centered">Tareas para los Finaos</h3>
            <ol class="ordered-task-list">
                <li>Ir al cementerio</li>
                <li>Vivir momentos entrañables</li>
                <li>Acordarse de los seres queridos</li>
                <li>Comer dulces</li>
                <li>Ser feliz</li>
            </ol>
        </article>
    </div>
</section>
//--------------------------------------------------------------------------------------------------------------------//
<!-- MODEL 1 - EXERCISE 2 (Justo antes de footer) -->
<section id="exercise-two-section" class="exercise-two">
    <h2 class="exercise-two-title">Ejercicio 2</h2>
    <div class="exercise-two-container">
        <article class="exercise-two-box">
            <h3 class="box-title-left">Primera caja</h3>
            <p class="box-text-left">Este es el texto de la primera caja.</p>
        </article>
        <article class="exercise-two-box">
            <h3 class="box-title-left">Segunda caja</h3>
            <p class="box-text-left">Este es el texto de la segunda caja.</p>
        </article>
        <figure class="exercise-two-media">
            <img src="img/village-street.jpg" alt="Calle estrecha con edificios históricos" class="exercise-two-img">
        </figure>
    </div>
</section>

/* MODEL 1 STYLES */
.exercise-one {
    padding: 24px 0;
}

.exercise-one-title {
    text-align: center;
    margin-bottom: 20px;
}

.exercise-one-container {
    display: flex;
    flex-direction: column;
    gap: 20px;
    margin-left: 32px;
    margin-right: 32px;
}

.exercise-one-box {
    flex: 1;
    padding: 20px;
    background-color: #90ee90;
    color: #111111;
}

.box-title-centered {
    text-align: center;
    margin-bottom: 12px;
}

.unordered-task-list,
.ordered-task-list {
    padding-left: 24px;
}

.exercise-two {
    padding: 24px 0;
}

.exercise-two-title {
    text-align: center;
    margin-bottom: 20px;
}

.exercise-two-container {
    display: flex;
    flex-direction: column;
    gap: 20px;
    margin-left: 32px;
    margin-right: 32px;
}

.exercise-two-box {
    width: 100%;
    padding: 20px;
    background-color: #add8e6;
    color: #111111;
}

.box-title-left,
.box-text-left {
    text-align: left;
}

.box-title-left {
    margin-bottom: 8px;
}

.exercise-two-media {
    width: 100%;
    margin: 0;
}

.exercise-two-img {
    display: block;
    width: 100%;
    height: auto;
}

@media (min-width: 768px) and (max-width: 1024px) {
    .exercise-one-container {
        flex-direction: row;
    }

    .exercise-one-box {
        background-color: #e57373;
    }

    .exercise-two-container {
        flex-direction: row;
        flex-wrap: wrap;
    }

    .exercise-two-box {
        width: calc(50% - 10px);
    }

    .exercise-two-media {
        width: 100%;
    }
}

@media (min-width: 1025px) {
    .exercise-one-container {
        flex-direction: row;
    }

    .exercise-one-box {
        background-color: #add8e6;
    }

    .exercise-two-container {
        flex-direction: row;
        align-items: flex-start;
    }

    .exercise-two-box,
    .exercise-two-media {
        flex: 1;
        width: auto;
    }
}
//--------------------------------------------------------------------------------------------------------------------//
<!-- MODEL 2 - EXERCISE 1 (Justo debajo de header) -->
<section id="exercise-one-section" class="festival-section">
    <h2 class="festival-heading">Ejercicio 1 - Music Festival</h2>
    <div class="festival-container">
        <article class="festival-card concerts-card">
            <h3 class="festival-card-title">Concerts</h3>
            <ul class="festival-list">
                <li>Friday night</li>
                <li>Saturday night</li>
                <li>Sunday afternoon</li>
            </ul>
        </article>
        <article class="festival-card artists-card">
            <h3 class="festival-card-title">Artists</h3>
            <ol class="festival-list">
                <li>The Echoes</li>
                <li>Blue Moon</li>
                <li>North Star</li>
            </ol>
        </article>
        <article class="festival-card tickets-card">
            <h3 class="festival-card-title">Tickets</h3>
            <p class="festival-text">Book your festival pass online.</p>
        </article>
    </div>
</section>

<!-- MODEL 2 - EXERCISE 2 (Justo antes de footer) -->
<section id="exercise-two-section" class="nature-section">
    <h2 class="nature-heading">Nature Explorer</h2>
    <div class="nature-container">
        <figure class="nature-media">
            <img src="img/nature-lake.jpg" alt="Montañas, bosque verde y lago cristalino" class="nature-img">
        </figure>
        <div class="nature-cards-group">
            <article class="nature-card">
                <h3 class="nature-card-title">Mountains</h3>
                <p class="nature-card-text">Discover scenic hiking routes.</p>
            </article>
            <article class="nature-card">
                <h3 class="nature-card-title">Forests</h3>
                <p class="nature-card-text">Enjoy peaceful woodland walks.</p>
            </article>
            <article class="nature-card">
                <h3 class="nature-card-title">Lakes</h3>
                <p class="nature-card-text">Relax by the water.</p>
            </article>
        </div>
    </div>
</section>
//--------------------------------------------------------------------------------------------------------------------//
/* MODEL 2 STYLES */
.festival-section {
    padding: 24px 0;
}

.festival-heading {
    text-align: center;
    margin-bottom: 20px;
}

.festival-container {
    display: flex;
    flex-direction: column;
    gap: 20px;
    margin-left: 2rem;
    margin-right: 2rem;
}

.festival-card {
    width: 100%;
    padding: 20px;
    background-color: #90ee90;
    color: #111111;
}

.festival-card-title {
    margin-bottom: 10px;
}

.festival-list {
    padding-left: 22px;
}

.festival-text {
    margin: 0;
}

.nature-section {
    padding: 24px 0;
}

.nature-heading {
    text-align: center;
    margin-bottom: 20px;
}

.nature-container {
    display: flex;
    flex-direction: column;
    gap: 20px;
    margin-left: 2rem;
    margin-right: 2rem;
}

.nature-media {
    width: 100%;
    margin: 0;
}

.nature-img {
    display: block;
    width: 100%;
    height: auto;
}

.nature-cards-group {
    display: flex;
    flex-direction: column;
    gap: 20px;
    width: 100%;
}

.nature-card {
    width: 100%;
    padding: 20px;
    background-color: #add8e6;
    color: #111111;
    text-align: left;
}

.nature-card-title {
    margin-bottom: 8px;
}

.nature-card-text {
    margin: 0;
}

@media (min-width: 768px) and (max-width: 1024px) {
    .festival-container {
        flex-direction: row;
        flex-wrap: wrap;
    }

    .festival-card {
        background-color: #e57373;
    }

    .concerts-card {
        width: 100%;
    }

    .artists-card,
    .tickets-card {
        width: calc(50% - 10px);
    }

    .nature-cards-group {
        flex-direction: row;
    }

    .nature-card {
        flex: 1;
        width: auto;
    }
}

@media (min-width: 1025px) {
    .festival-container {
        flex-direction: row;
        flex-wrap: wrap;
    }

    .festival-card {
        background-color: #add8e6;
    }

    .concerts-card,
    .artists-card {
        width: calc(50% - 10px);
    }

    .tickets-card {
        width: 100%;
    }

    .nature-container {
        flex-direction: row;
        align-items: stretch;
    }

    .nature-media {
        flex: 1;
        width: auto;
    }

    .nature-img {
        height: 100%;
        object-fit: cover;
    }

    .nature-cards-group {
        flex: 1;
        width: auto;
    }
}
//--------------------------------------------------------------------------------------------------------------------//
<!-- MODEL 3 - EXERCISE 1 (Justo debajo de header) -->
<section id="exercise-one-section" class="paths-section">
    <h2 class="paths-heading">Exercise 1 - Learning Paths</h2>
    <div class="paths-container">
        <article class="paths-card paths-web">
            <h3 class="paths-card-title">Web Development</h3>
            <ul class="paths-list">
                <li>HTML</li>
                <li>CSS</li>
                <li>JavaScript</li>
            </ul>
        </article>
        <article class="paths-card paths-programming">
            <h3 class="paths-card-title">Programming</h3>
            <ol class="paths-list">
                <li>Python</li>
                <li>Java</li>
                <li>PHP</li>
            </ol>
        </article>
        <article class="paths-card paths-databases">
            <h3 class="paths-card-title">Databases</h3>
            <ul class="paths-list">
                <li>SQL</li>
                <li>Tables</li>
                <li>Queries</li>
            </ul>
        </article>
        <article class="paths-card paths-cybersecurity">
            <h3 class="paths-card-title">Cybersecurity</h3>
            <ol class="paths-list">
                <li>Passwords</li>
                <li>Networks</li>
                <li>Backups</li>
            </ol>
        </article>
    </div>
</section>

<!-- MODEL 3 - EXERCISE 2 (Justo antes de footer) -->
<section id="exercise-two-section" class="guide-section">
    <h2 class="guide-heading">Exercise 2 - City Guide</h2>
    <div class="guide-container">
        <div class="guide-left-column">
            <div class="guide-top-boxes">
                <article class="guide-card">
                    <h3 class="guide-card-title">Discover</h3>
                    <p class="guide-card-text">Explore interesting streets and landmarks.</p>
                </article>
                <article class="guide-card">
                    <h3 class="guide-card-title">Activities</h3>
                    <p class="guide-card-text">Find places to visit and things to do.</p>
                </article>
            </div>
            <article class="guide-card guide-food-card">
                <h3 class="guide-card-title">Food</h3>
                <p class="guide-card-text">Try traditional dishes and local cafes.</p>
            </article>
        </div>
        <figure class="guide-media">
            <img src="img/city-street.jpg" alt="Calle estrecha con edificios históricos y puerta azul" class="guide-img">
        </figure>
    </div>
</section>
//--------------------------------------------------------------------------------------------------------------------//
/* MODEL 3 STYLES */
.paths-section {
    padding: 24px 0;
}

.paths-heading {
    text-align: center;
    margin-bottom: 20px;
}

.paths-container {
    display: flex;
    flex-direction: column;
    gap: 20px;
    margin-left: 2rem;
    margin-right: 2rem;
}

.paths-card {
    width: 100%;
    padding: 20px;
    background-color: #90ee90;
    color: #111111;
}

.paths-card-title {
    margin-bottom: 10px;
}

.paths-list {
    padding-left: 22px;
}

.guide-section {
    padding: 24px 0;
}

.guide-heading {
    text-align: center;
    margin-bottom: 20px;
}

.guide-container {
    display: flex;
    flex-direction: column;
    gap: 20px;
    margin-left: 2rem;
    margin-right: 2rem;
}

.guide-left-column {
    display: flex;
    flex-direction: column;
    gap: 20px;
    width: 100%;
}

.guide-top-boxes {
    display: flex;
    flex-direction: column;
    gap: 20px;
    width: 100%;
}

.guide-card {
    width: 100%;
    padding: 20px;
    background-color: #add8e6;
    color: #111111;
    text-align: left;
}

.guide-card-title {
    margin-bottom: 8px;
}

.guide-card-text {
    margin: 0;
}

.guide-media {
    width: 100%;
    margin: 0;
}

.guide-img {
    display: block;
    width: 100%;
    height: auto;
}

@media (min-width: 768px) and (max-width: 1024px) {
    .paths-container {
        flex-direction: row;
        flex-wrap: wrap;
    }

    .paths-card {
        background-color: #e57373;
        width: calc(50% - 10px);
    }

    .guide-top-boxes {
        flex-direction: row;
        flex-wrap: wrap;
    }

    .guide-top-boxes .guide-card,
    .guide-food-card {
        flex: 1;
        width: auto;
    }
}

@media (min-width: 1025px) {
    .paths-container {
        flex-direction: row;
        flex-wrap: wrap;
    }

    .paths-card {
        background-color: #add8e6;
    }

    .paths-web,
    .paths-programming,
    .paths-databases {
        width: calc((100% - 40px) / 3);
    }

    .paths-cybersecurity {
        width: 100%;
    }

    .guide-container {
        flex-direction: row;
        align-items: stretch;
    }

    .guide-left-column {
        flex: 1;
        width: auto;
        justify-content: space-between;
    }

    .guide-top-boxes {
        flex-direction: row;
    }

    .guide-top-boxes .guide-card {
        flex: 1;
        width: auto;
    }

    .guide-food-card {
        flex: 1;
        width: auto;
    }

    .guide-media {
        flex: 1;
        width: auto;
    }

    .guide-img {
        height: 100%;
        object-fit: cover;
    }
}
