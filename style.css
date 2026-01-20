function addGoal() {
    let goalText = document.getElementById("goalInput").value;
    let priority = document.getElementById("priority").value;
    let goalList = document.getElementById("goalList");

    if (goalText === "") {
        alert("Please enter a goal");
        return;
    }

    let li = document.createElement("li");
    li.innerHTML = `
        <span>${goalText} (${priority})</span>
        <span class="delete" onclick="deleteGoal(this)">❌</span>
    `;

    if (priority === "High") li.classList.add("high");
    if (priority === "Medium") li.classList.add("medium");
    if (priority === "Low") li.classList.add("low");

    goalList.appendChild(li);
    document.getElementById("goalInput").value = "";
}

function deleteGoal(element) {
    element.parentElement.remove();
}
