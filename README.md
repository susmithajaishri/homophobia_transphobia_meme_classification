# Multimodal Homophobia and Transphobia Meme Classification

This repository contains the implementation for our submission to the **LT-EDI @ ACL 2026** shared task. 

## Project Overview
- **Title:** Identifying Homophobia and Transphobia in Multimodal Memes
- **Author:** N.P.SUSMITHA JAISHRI
- **Institution:** M.Tech AI & ML, NITTTR Chennai
- **Status:** Rank 3 (Chinese), Rank 4 (English), Rank 7 (Hindi)

## Methodology
We utilize a dual-stream late-fusion architecture:
- **Textual Encoder:** XLM-RoBERTa
- **Visual Encoder:** ResNet-50
- **Loss Function:** Weighted Cross-Entropy (to handle class imbalance)

## Installation & Usage
1. Clone the repository: `git clone https://github.com/susmithajaishri/homophobia_transphobia_meme_classification.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run training: `python homophone.py`

## Data Setup
1. Create a folder named `data` in the project root.
2. Place the `english`, `hindi`, and `chinese` dataset folders inside `/data`.
3. The script will automatically detect the local path.
  
