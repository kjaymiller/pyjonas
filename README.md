# pyjonas
Classic Tetris Analysis Tool


## Related projects
- [Sheshkon/TetrisAI](https://github.com/Sheshkon/TetrisAI)

    When bot started he tries to find game aplication and wait until game is started. When game is started bot detectes the board, the tetrominoes in the game using Opencv. Grabs the images in realtime and transfroms board to bollean matrix (0 - empty cell , 1 - occupied cell) and identify current tetromino.

    When all information about the board is known, AI determines all possible positions of the current tetromino on the board. Choose the best possible position via fitness function and transmits all the necessary moves by emulating keystrokes on the keyboard.
- [Real-time inferencing FPGA hardware](http://www.pynq.io/)
- [TetrisAI](https://github.com/dguostanford/Machine-Learning-Tetris-)
- [Deep Q-learning for playing Tetris](https://pythonawesome.com/deep-q-learning-for-playing-tetris-game/)
- [Example of coaching Tetris](https://www.youtube.com/playlist?list=PLjvvUIYe8rKW3HDvoRiBohQdfBW6J3BXj)
