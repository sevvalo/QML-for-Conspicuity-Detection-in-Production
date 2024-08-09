# QML-for-Conspicuity-Detection-in-Production
Womanium Quantum+AI 2024 Projects

**Please review the participation guidelines [here](https://github.com/womanium-quantum/Quantum-AI-2024) before starting the project.**

_**Do NOT delete/ edit the format of this read.me file.**_

_**Include all necessary information only as per the given format.**_

## Project Information:

### Team Size:
  - Maximum team size = 2
  - While individual participation is also welcome, we highly recommend team participation :)

### Eligibility:
  - All nationalities, genders, and age groups are welcome to participate in the projects.
  - All team participants must be enrolled in Womanium Quantum+AI 2024.
  - Everyone is eligible to participate in this project and win Womanium grants.
  - All successful project submissions earn the Womanium Project Certificate.
  - Best participants win Womanium QSL fellowships with Fraunhofer ITWM. Please review the eligibility criteria for QSL fellowships in the project description below.

### Project Description:
  - Click [here](https://drive.google.com/file/d/1AcctFeXjchtEhYzPUsHpP_b4HGlI4kq9/view?usp=sharing) to view the project description.
  - YouTube recording of the project description - [link](https://youtu.be/Ac1ihFcTRTc?si=i6AIVfQQh8ymYQYp)

## Project Submission:
All information in this section will be considered for project submission and judging.

Ensure your repository is public and submitted by **August 9, 2024, 23:59pm US ET**.

Ensure your repository does not contain any personal or team tokens/access information to access backends. Ensure your repository does not contain any third-party intellectual property (logos, company names, copied literature, or code). Any resources used must be open source or appropriately referenced.

### Team Information:
Team Member 1:

* Full Name: Ahmet Alperen TEKİN
* Womanium Program Enrollment ID: WQ24-nMbUmOCjHyDbRAK

Team Member 2:

* Full Name: Şevval ÖZDEMİR
* Womanium Program Enrollment ID: WQ24-jEy2lgI4HZ4PiG8


### Project Solution:
This project explores the application of quantum machine learning techniques, specifically quantum variational classifiers and quantum convolutional neural networks, to the problem of conspicuity detection in production. The project utilizes PennyLane, a quantum machine learning library, and TensorFlow for classical machine learning tasks.

In our solution, after completing the required PennyLane Codebooks, we continued with Task 2. In this task, quantum variational classifier is implemented. 
The process includes:
*Device Setup: Using the default.qubit device in PennyLane.
*Quantum Circuit Design: The circuit consists of a series of rotation gates applied to qubits, followed by CNOT gates for entanglement.
*State Preparation: Inputs are encoded into the quantum circuit using basis states.
*Training: The classifier is trained using the NesterovMomentumOptimizer over 100 epochs. The performance is evaluated using accuracy and mean square error loss metrics.
*Evaluation: After training, the model is tested on a validation dataset, showing promising results in classifying parity data.


The third task explores quantum convolutional neural networks (QCNN) through a Quanvolutional Neural Network model:
*Data Preparation: The MNIST dataset is normalized and downsized for computational feasibility.
*Quantum Circuit Design: A quantum circuit encodes the input images and applies random layers to process the data.
*Quanvolutional Layer: This layer applies quantum operations in a sliding window manner over the input images, effectively simulating the function of classical convolutional layers.
*Integration with Classical Neural Networks: The outputs from the quanvolutional layer are fed into a classical neural network for final classification.

At the forth task, we have followed the following approach to model and predict the sine function:
*Dataset Creation: This section has also three subparts, generation of a datasetof sine function values over [0,2π], ploting the original data for reference, and splitting the dataset into training and test sets.
*Quantum Circuit Definition: To encode input data amplitude embedding is applied and a quantum circuit is defined with parameterized rotations and entangling gates.
*Model Training: Nesterov Momentum optimizer is used to train the quantum model.

The fifth task asks us to do the task 4 with real-world data and compare a classical neural network and a hybrid quantum-classical model. The task has two sub-parts so we first build the CNN and then Hybrid Quantum-Classical model.



#### Conclusion

The project demonstrates the potential of quantum machine learning in enhancing conspicuity detection models in production environments. The quantum variational classifier and the Quanvolutional Neural Network both exhibit promising results, indicating that quantum machine learning could offer advantages in tasks requiring high precision and novel data processing techniques. However, further exploration is needed to fully understand the scalability and practical implementation of these quantum models in real-world production systems. 

### Project Presentation Deck:
_Upload/ Link a 3min. presentation deck here._

See project presentation guidelines [here](https://docs.google.com/document/d/13nWF8AxFAfFYTWEYPT3BpPdYkqtxxSAjmuXj_zcMh-E/edit?usp=sharing)

