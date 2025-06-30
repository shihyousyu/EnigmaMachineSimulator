# Enigma Machine Simulator

This project is a simulator of the Enigma machine used during World War II. It allows users to configure rotors, initial rotor positions, and plugboard settings to encrypt individual letters, displaying the resulting cipher letter on a lampboard.

## Features

- Select from 5 different rotors and set their initial positions (0–25).
- Configure plugboard connections using paired letter swaps.
- Interactive on-screen keyboard to input letters.
- Visual lampboard showing the encrypted output letter for each input.
- Rotors automatically step with a simple notch turnover simulation.
- Reset button to clear the current state and reset rotors.

## How to Use

1. Choose rotor types for **Rotor 1**, **Rotor 2**, and **Rotor 3** from the dropdown menus.
2. Set the initial position (0–25) for each rotor.
3. Enter plugboard pairs in the input box (e.g. `AB CD EF`).
4. Click the on-screen keyboard buttons to input letters.
5. The corresponding encrypted letter will light up on the lampboard.
6. Click **Reset** to clear the state and start over.

## Technologies

- **HTML**, **CSS** for the user interface.
- **JavaScript** for simulating the Enigma encryption logic, including rotors, reflector, and plugboard.
- No external dependencies; runs fully in the browser.

## Project Structure
`index.html`  Main page with the UI layout  
`style.css`  Styles for layout, keyboard, lampboard, and controls  
`enigma.js`  Enigma machine logic and UI interaction  

## Notes

- Rotor notch positions are fixed for simplicity; real Enigma rotors had specific notch positions.
- Plugboard input format requires pairs of letters separated by spaces.
- Only uppercase English letters A–Z are supported.

## License

This project is open source and available under the MIT License.
