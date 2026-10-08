function updateCard() {
    const name = document.getElementById("name").value;
    const age = document.getElementById("age").value;
    const message = document.getElementById("message").value;
    const color = document.getElementById("color").value;

    document.getElementById("cardName").innerText =
        name || "Dein Name";

    document.getElementById("cardAge").innerText =
        age
        ? "Alles Gute zum " + age + ". Geburtstag! 🎉"
        : "Alles Gute zum Geburtstag! 🎂";

    document.getElementById("cardMessage").innerText =
        message || "Deine Nachricht erscheint hier.";

    document.getElementById("card").style.backgroundColor = color;
}


// CardBot
function createCardText() {
    const keywords = document.getElementById("keywords").value.toLowerCase();

    let text = "Alles Gute zum Geburtstag! 🎉 ";

    if (keywords.includes("lustig")) {
        text += "Ich wünsche dir ganz viel Spaß und einen richtig lustigen Tag! 😂 ";
    }

    if (keywords.includes("fußball")) {
        text += "Ich wünsche dir viele Tore und einen tollen Geburtstag! ⚽ ";
    }

    if (keywords.includes("freund")) {
        text += "Danke, dass du so ein toller Freund bist! 🥳 ";
    }

    if (keywords.includes("familie")) {
        text += "Genieß deinen besonderen Tag mit deiner Familie! ❤️ ";
    }

    if (keywords.includes("geschenk")) {
        text += "Hoffentlich bekommst du tolle Geschenke! 🎁 ";
    }

    if (keywords.trim() === "") {
        text = "Schreib ein paar Stichwörter hinein, zum Beispiel: Fußball, lustig, Freund.";
    }

    document.getElementById("message").value = text;

    updateCard();
}


// Design auswählen
function changeDesign(color) {
    document.getElementById("card").style.backgroundColor = color;
}


// Karte speichern
function saveCard() {
    alert("🎉 Deine HappyCard ist fertig!");
}