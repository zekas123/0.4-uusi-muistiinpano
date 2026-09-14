```mermaid
graph TD;
    html["HTML DOCUMENT"] --> css["CSS FILE"];
    css --> js["JS"];
    js --> btn["Odotetaan painikkeen painallusta"];
    btn --> send["lähetä lomake palvelimelle"];
    send --> take["Suorita JS (Lisää elementti HTML:ään)"];
    take --> update["päivitä HTML"]
    
