# **Network Protocol Classification Using Machine Learning**

## **Project Overview**

This project uses Machine Learning algorithms to classify network packets based on packet length and time-related features.

The objective is to predict the network protocol, such as UDP, TCP, DNS and TLS, using packet information.

## **Dataset**

Dataset: KT\_GameBox

The dataset contains the following columns:

* No.  
* Time  
* Source  
* Destination  
* Protocol  
* Length  
* Info

For this implementation, 100,000 records were used from `KT_GameBox_3.csv`.

## **Technologies Used**

* Python 3  
* Pandas  
* NumPy  
* Matplotlib  
* Seaborn  
* Scikit-learn  
* Google Colab

## **Machine Learning Algorithms**

1. Logistic Regression  
2. K-Nearest Neighbors (KNN)  
3. Decision Tree  
4. Random Forest

## **Features Used**

* Packet Length  
* Hour  
* Minute  
* Second

Target variable: Protocol

## **Model Performance**

| Algorithm | Accuracy |
| :---- | :---- |
| Logistic Regression | 93.09% |
| KNN | 99.16% |
| Decision Tree | 99.44% |
| Random Forest | 99.31% |

Decision Tree achieved the highest accuracy in this experiment.

The dataset is highly imbalanced, so accuracy should be interpreted alongside precision, recall and F1-score.

## **Project Outputs**

* Protocol distribution graph  
* Packet length distribution graph  
* Model comparison graph  
* Confusion matrices  
* Decision Tree visualization  
* Random Forest feature importance  
* New packet prediction

## **Sample Prediction**

Input:

* Length: 64  
* Hour: 10  
* Minute: 30  
* Second: 15

Predicted Protocol: UDP

## **Project Structure**

```
Network-Protocol-Classification/
│
├── dataset/
├── outputs/
│   └── graphs/
├── reports/
├── screenshots/
├── Network_Protocol_Classification.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## **How to Run**

1. Install Python 3\.  
2. Install the required libraries:

```
pip install -r requirements.txt
```

3\.  
Open the Jupyter Notebook in Google Colab or Jupyter.

4. Connect the dataset.  
5. Run the notebook cells sequentially.

## **Conclusion**

This project demonstrates the application of supervised Machine Learning algorithms for network protocol classification. Four algorithms were trained and evaluated, and Decision Tree achieved the highest observed accuracy of 99.44% on the selected test set.

---

**Project:** Network Protocol Classification Using Machine Learning  
**Course:** BCA (Hons)  
**University:** Brainware University

&nbsp;