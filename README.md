# ABOUT THIS PROJECT
#
Developed the backend infrastructure for a cryptocurrency data-fetching and analysis system using Flask, Python, and APScheduler, with plans to deploy as a fully functional web application. The system fetches and analyzes real-time cryptocurrency data for Bitcoin, Dogecoin, and Ethereum, providing insights on pricing trends.
#
This allows users to fetch real-time and historical cryptocurrency data from multiple sources (including Binance, CoinGecko, and CoinMarketCap) using their respective APIs. The data is then processed and visualized to aid in analysis.
#
**Key Features:**
* Fetches OHLCV (Open, High, Low, Close, Volume) data for cryptocurrencies.
* Supports multiple cryptocurrency exchanges like Binance and Kraken.
* Data visualization using matplotlib.
* Includes retry logic for handling temporary API issues or rate limits.


## Installation

To set up the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/maicaalmonte/cryptic.git
   cd cryptic
2. Create virtual environment
   ```bash
   python -m venv .venv

2.  Activate the virtual environment:
   * On Windows:
 
      ``` bash
       .venv\Scripts\activate
   
 * On macOS/Linux:
      ```bash
      source .venv/bin/activate

5. Install Requirement
      ```bash
      pip install -r requirements.txt
    
6. Run the script:
      ``` bash
         python maica.py
#
**Usage**

Once you've set up the project and installed all the dependencies, you can run the script to fetch and visualize cryptocurrency data.

For example, to fetch data from Kraken for the BTC/USD pair, you can run:
    
      
      python your_script_name.py

![Screenshot 2024-12-22 002443](https://github.com/user-attachments/assets/30d8b44d-5911-441e-852c-e3910bc4bc5b)
![Screenshot 2024-12-22 002624](https://github.com/user-attachments/assets/ad6d4b9b-0768-4af8-8fd8-a9095ba08ee5)
![Screenshot 2024-12-22 002721](https://github.com/user-attachments/assets/6f5b5f8d-2b88-44f4-ab59-3a6414f8d970)
![Screenshot 2024-12-22 002811](https://github.com/user-attachments/assets/045bd778-ad07-49b3-87a8-4588d27e8058)
![Screenshot 2024-12-22 002945](https://github.com/user-attachments/assets/7db4c04b-8627-47ba-960a-340ce685a96a)
![Screenshot 2024-12-22 003005](https://github.com/user-attachments/assets/760b6d81-36ec-4d78-9974-36c59c952e1f)
![Screenshot 2024-12-22 003153](https://github.com/user-attachments/assets/890a054e-6efd-40c9-aa8f-f55d29ae0bdf)
![Screenshot 2024-12-22 003213](https://github.com/user-attachments/assets/7d2f1a4f-704f-4732-9957-983139d11e97)
![Screenshot 2024-12-22 004529](https://github.com/user-attachments/assets/a9a56e95-151c-438b-b0f9-a356707fa859)
![Screenshot 2024-12-22 003241](https://github.com/user-attachments/assets/c80c255b-819a-4e86-b7ee-70323b4ae53f)


