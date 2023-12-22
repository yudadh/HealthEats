# HealthEats
## Bangkit 2023 Batch 2 Capstone Product
HealthEats is an application used to diagnose the possibility of developing non-communicable diseases and provide food recommendations that can prevent these diseases. This application has hopes and goals to reduce mortality from non-communicable diseases to create a better sustainable life.

## Our Team
### Team ID: CH2-PS313
| Name                    | Bangkit ID  | Learning Path      |
| :---                    |    :----:   |          :---      |
| Miftakhul Ilmiyah       | M356BSX0960 | Machine Learning   |
| Layla Indah Pradita     | M200BSX0876 | Machine Learning   | 
| Putri Maharani Suta     | M315BSX1851 | Machine Learning   |
| Muhammad Adithya Warman | A315BSY2346 | Mobile Development |
| Alfi Nur Inayati Ningrum| A284BSX2357 | Mobile Development |
| Indra Budi Styawan      | C183BSY3089 | Cloud Computing    |
| I Putu Yuda Dharmawan   | C014BSY3974 | Cloud Computing    |

## Project Documentation
- [Project Brief here!](https://docs.google.com/document/d/1MR1Yxh-zCZV1Mic5aCKdqdmvJxICzmYz/edit)
- [Presentation here!](https://docs.google.com/presentation/d/1DZyOQYUs8PaMJ8HUwSgcHmb-qaGFf_Ss/edit#slide=id.p1)

### Machine Learning


Before building the model, we have to clean the dataset from missing values, outlier data, data imbalances, etc. We also use feature selection to find the most influential attributes. Then we use encoding techniques so that the input can be understood and processed by the computer. When building the model, we used a model architecture consisting of an input layer with 8 input features, two hidden layers with 8 neurons each, and an output layer with 3 neurons for classification. The activation function used in the hidden layer is ReLU, and softmax is used in the output layer with 3 classes.


[Our Model structure here!](https://github.com/yudadh/HealthEats/blob/main/ML/Modelling_fix.ipynb) .

### Cloud Computing
#### - Cloud Architecture
![This is our Architecture!](https://github.com/yudadh/HealthEats/blob/main/Github%20Assets/Architecture.png)
#### - Setup Project
- Clone the project
- Open CC folder
- Open terminal
- Run the command
  - `npm install`
  - `npx prisma introspect`
  - `npx prisma migrate` 
- For the API Documentation check it here -> [Documentation](https://documenter.getpostman.com/view/29695288/2s9YkobgDu).

### Mobile Development

In this application we use the Model-View-ViewModel (MVVM) concept, which is an architectural pattern that prioritizes separation of interests, separation of graphical interfaces and business logic processes (back-end logic).

![This is our UI!](https://github.com/yudadh/HealthEats/blob/main/Github%20Assets/Capstone%20project%20-%20presentation.pptx.png)

[MD Repository](https://github.com/alfinur063/Capstone)
#### - Feature
- Interraction with API
- Using Android Architecture Component(ViewModel and LiveData)
- Using library Retrofit for networking
- A page display a list foods
- A page display a recomendation foods
- display result recomendation

