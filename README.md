# Mini-Project 3: Steane's Code under random Pauli error

Gabriella Torres Nothaft

The notebook mini_project_3.ipynb takes in a boolean  $x\in \mathbf{F}_2$  and an error probability  $p$, and outputs a quantum circuit. It prepares the logical  $|x_L>$  state using Steane's code, adds a random error for each qubit with probability  $p$, measures syndromes, measures the data qubits, and decodes the results. It also outputs the final quantum state based on the initial $x$ and $p$. Lastly, the notebook includes a part which sweeps through multiple values of $p$, outputting the success probability and plotting it against $p$.


The sources used are Steane (1996), Nielsen & Chuang (2010), and ErrorCorrectionZoo (https://errorcorrectionzoo.org/c/steane#citation-9)

