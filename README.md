# AI Flappy Bird

Using the NEAT python module, I implemented a genetic learning algorithim that teaches itself how to play flappy bird <br>
<img width="300" alt="Screenshot 2025-01-11 at 1 12 37 AM" src="https://github.com/user-attachments/assets/959def9c-af2c-4d35-8927-a9197a29bb9b" />

## Fitness Function
- Outputs: Should the bird jump or do nothing?
- Inputs: Distance from Top Pipe, Bottom Pipe, Floor
- The birds are rewarded for each second they are alive, and each pipe the successfully traverse. The birds lose fitness everytime they collide with an object
- Config-Feed Forward has more information about the exact functions used, generation information, and parameters.

## How to Run
1. Open the file in VS Code or preferred editor
2. Run `pip3 install -r requirements.txt` into the terminal
3. Ensure that all elements of the project are in the same directory

