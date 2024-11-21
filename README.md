# Neural Networks and Decision Making  

Welcome to the **Neural Networks and Decision Making** repository! This project implements and analyzes spiking neural networks, focusing on synaptic connectivity schemes and decision-making processes. Using the `pymonntorch` framework, this repository explores network structures such as fully connected, random connectivity, homogeneous, and balanced networks. Additionally, it investigates how spiking neural networks can perform decision-making tasks.  

---

## Features  

- **Connectivity schemes:**  
  - Full and random synaptic connectivity.  
  - Homogeneous and balanced networks.  

- **Decision-making models:**  
  - Simulations of neural network-based decision-making processes.  
  - Analysis of spiking activity and network dynamics during decision-making.  

- **Interactive notebook:** A single Jupyter notebook (`Neural-Networks-and-Decision-Making.ipynb`) combines implementation, visualization, and analysis.  

- **Visualization resources:** Pre-generated plots and figures included in the `resources/` folder.  

- **Detailed report:** A well-documented `report.pdf` provides the theoretical background, results, and insights.  

---

## Installation  

1. Clone this repository:  
   ```bash  
   git clone https://github.com/yourusername/Neural-Networks-and-Decision-Making.git  
   cd Neural-Networks-and-Decision-Making  
   ```  

2. Install dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  

   **Note:** Ensure you have Python 3.8 or higher installed.  

---

## Usage  

### Running the Jupyter Notebook  

1. Open the Jupyter notebook:  
   ```bash  
   jupyter notebook Neural-Networks-and-Decision-Making.ipynb  
   ```  

2. Follow the step-by-step implementation for each connectivity scheme and decision-making task.  
3. Generate plots and analyze the results directly within the notebook.  

---

## Directory Structure  

```plaintext  
Neural-Networks-and-Decision-Making/  
│  
├── Neural-Networks-and-Decision-Making.ipynb  # Jupyter notebook containing all implementations and analysis  
│  
├── report.pdf                                 # Detailed report including results and analysis  
│  
├── resources/                                 # Folder for visualization resources  
│   ├── full_connectivity.png                  # Visualization of fully connected network  
│   ├── random_connectivity.png                # Visualization of random connectivity network  
│   ├── balanced_network.png                   # Visualization of balanced network  
│   ├── decision_making_results.png            # Visualization of decision-making dynamics  
│  
├── requirements.txt                           # Python dependencies  
├── LICENSE                                    # License information  
├── README.md                                  # Project documentation  
└── .gitignore                                 # Git ignored files  
```  

---

## Results  

The `resources/` folder contains pre-generated plots and visualizations, including:  
- Synaptic connectivity matrices for full and random networks.  
- Spike raster plots and firing rates for different network structures.  
- Decision-making dynamics and outcomes.  

Refer to the `report.pdf` for a comprehensive discussion of these results.  

---

## Dependencies  

- Python 3.8+  
- `pymonntorch`
- `pytorch`
- `numpy`  
- `matplotlib`   

Install all dependencies using the provided `requirements.txt` file.  

---

## Contributing  

Contributions are welcome! To contribute:  
1. Fork the repository.  
2. Create a feature branch.  
3. Submit a pull request with your changes.  

For major changes, please open an issue to discuss your ideas.  

---

## Acknowledgements  

This project leverages the [pymonntorch](https://github.com/cnrl/PymoNNtorch) framework for spiking neural network simulations.  

Happy experimenting with neural networks and decision-making models!
