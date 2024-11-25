### Financial Data Visualization and Analysis using GNN


Financial Data Visualization and Analysis using Graph Neural Networks (GNN)

This project uses Graph Neural Networks (GNNs) to analyze and visualize financial data. Stock data is modeled as a graph, where nodes represent individual stocks, and edges represent relationships (e.g., correlations). The model predicts stock movement trends and visualizes data interactively for financial analysis.

---

## Features
- **Data Modeling:** Represent stocks as graph nodes and their relationships as edges.
- **Visualization:** Generate heatmaps and interactive graphs to explore stock data.
- **Predictive Analytics:** Utilize GNN models to forecast stock trends based on relationships.

---

## Requirements

- Python 3.7+
- PyTorch
- PyTorch Geometric
- yfinance
- pandas
- numpy
- matplotlib

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/financial-gnn.git
   cd financial-gnn
   ```

2. Set up a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## Usage

1. Fetch financial data:
   ```bash
   python fetch_data.py --tickers "AAPL MSFT GOOG" --start "2020-01-01" --end "2023-01-01"
   ```

2. Construct the graph:
   ```bash
   python construct_graph.py --input data/stock_prices.csv
   ```

3. Train the GNN model:
   ```bash
   python train.py
   ```

4. Visualize results:
   ```bash
   python visualize.py --output visualizations/
   ```



## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.
