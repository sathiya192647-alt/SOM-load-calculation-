# SOM-load-calculation-
Strength of material load calculation 
/* ================= BEAM CALCULATION ================= */

.beam-category {
    margin: 20px 0;
    padding: 20px;
    border-radius: 12px;
    background: #f5f5f5;
}

.beam-category h3 {
    margin-bottom: 15px;
}

.option-grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 12px;
}

.option-grid button {
    padding: 14px;
    border: none;
    border-radius: 8px;
    cursor: pointer;
    font-size: 15px;
}

.option-grid button:hover {
    transform: scale(1.02);
}

.selected-beam {
    margin: 20px 0;
    padding: 20px;
    border-radius: 12px;
    background: #eeeeee;
}

.beam-input-area {
    margin: 20px 0;
    padding: 20px;
    border-radius: 12px;
    background: #f5f5f5;
}

.beam-input-area label {
    display: block;
    margin-top: 12px;
    margin-bottom: 5px;
}

.beam-input-area input {
    width: 100%;
    padding: 12px;
    border-radius: 7px;
    border: 1px solid #ccc;
    box-sizing: border-box;
}

.beam-input-area button {
    margin-top: 18px;
    padding: 12px 20px;
    border: none;
    border-radius: 8px;
    cursor: pointer;
}

.beam-result {
    margin-top: 20px;
    padding: 20px;
    border-radius: 12px;
    background: #f5f5f5;
}

@media (max-width: 600px) {

    .option-grid {
        grid-template-columns: 1fr;
    }

}
