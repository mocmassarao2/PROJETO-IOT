# 🐾 Smart Pet Feeder

Um alimentador pet automatizado e inteligente utilizando **ESP32**, simulado no **Wokwi** e integrado com o **Firebase**.

Projeto desenvolvido para a disciplina de Fundamentos de IoT no curso Técnico em Desenvolvimento de Sistemas (SENAI A. Jacob Lafer).

---

## ⚙️ Como Funciona

1. Você pressiona o **botão**.
2. O **servo motor** abre a comporta por 5 segundos para liberar a ração.
3. O **LCD 16x2** e o **LED RGB** indicam o estado da operação.
4. O **ESP32** busca a hora exata via servidor NTP e envia o registro da alimentação para o **Firebase**.

---

## 🔌 Conexões (Pinos ESP32)

* **Botão:** `GPIO 4`
* **Servo Motor:** `GPIO 13`
* **LED RGB:** `GPIO 25` (R), `GPIO 26` (G), `GPIO 27` (B)
* **LCD 16x2:** `GPIO 19, 23, 17, 16, 5, 15`

---

## 🌐 Testar no Wokwi

Acesse a simulação rodando diretamente no navegador:  
👉 [Abrir Projeto no Wokwi](https://wokwi.com/projects/476797194471556097)

---

## 👥 Autores

* Arthur Massarão Marcomini
* Gabriela de Oliveira
* Maria Eduarda Rocha Castro
* Mateus Aristóteles Fernandes
