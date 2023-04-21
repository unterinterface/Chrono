// Déclaration des variables pour stocker l'état du chronomètre
let timer;
let hours = 0;
let minutes = 0;
let seconds = 0;

// Fonction pour mettre à jour le temps écoulé
function updateTime() {
    // Incrémentation des secondes
    seconds++;

    // Gestion du passage des secondes aux minutes et des minutes aux heures
    if (seconds >= 60) {
        seconds = 0;
        minutes++;

        if (minutes >= 60) {
            minutes = 0;
            hours++;
        }
    }

    // Mise à jour de l'affichage du temps écoulé dans l'élément HTML avec l'ID 'timer'
    document.getElementById('timer').innerHTML = `${pad(hours)}:${pad(minutes)}:${pad(seconds)}`;
}

// Fonction pour ajouter un zéro devant les nombres inférieurs à 10
function pad(number) {
    return number.toString().padStart(2, "0");
}

// Fonction pour démarrer le chronomètre
function startTimer() {
    // Appel régulier de la fonction updateTime() toutes les secondes
    timer = setInterval(updateTime, 1000);

    // Désactivation du bouton "Démarrer" et activation des boutons "Arrêter" et "Réinitialiser"
    document.getElementById("start").disabled = true;
    document.getElementById("stop").disabled = false;
    document.getElementById("reset").disabled = false;
}

// Fonction pour arrêter le chronomètre
function stopTimer() {
    // Arrêt de l'appel régulier à updateTime()
    clearInterval(timer);

    // Activation du bouton "Démarrer" et désactivation du bouton "Arrêter"
    document.getElementById("start").disabled = false;
    document.getElementById("stop").disabled = true;
}

// Fonction pour réinitialiser le chronomètre
function resetTimer() {
    // Arrêt du chronomètre
    stopTimer();

    // Réinitialisation des variables d'état
    seconds = 0;
    minutes = 0;
    hours = 0;

    // Mise à jour de l'affichage du temps écoulé
    document.getElementById("timer").innerHTML = "00:00:00";

    // Désactivation du bouton "Réinitialiser"
    document.getElementById("reset").disabled = true;
}

// Ajout d'écouteurs d'événements aux boutons "Démarrer", "Arrêter" et "Réinitialiser"
document.getElementById("start").addEventListener("click", startTimer);
document.getElementById("stop").addEventListener("click", stopTimer);
document.getElementById("reset").addEventListener("click", resetTimer);
