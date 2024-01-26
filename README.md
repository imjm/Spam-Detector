
<h1 align="center"> 👋EnjoyTrip </h1>
<h3 align="center"> 전정민 이주호 </h3>
<h5 align="center"> JAVA과정 관통PJT  </h5>

<p align="center"> 
<img src="gif/spam detector.gif" alt="Animated gif pacman game" height="382px">
</p>

<p align="center">관광지에 대한 정보를 찾을 수 있는 어플리케이션입니다!</p>

<h2> :floppy_disk:기본 기능</h2>

<h4>검색 기능:</h4>
<ul>
  <li>관광지명, 주소 등 검색 조건을 통해 검색할 수 있습니다.</li>
  <li><b>train.py</b> - Uses the functions defined in the spam_detector.py file and generates the model.txt file after execution.</li>
  <li><b>test.py</b> - Uses the functions defined in the spam_detector.py file and, after execution, generates the result.txt as well as evaluation.txt files.</li>
</ul>

<h4>Output Files:</h4>
<ul>
  <li>관광지명, 주소 등 검색 조건을 통해 검색할 수 있습니다.</li>
  <li><b>result.txt</b> - Contains information about the classified emails of the test set.</li>
  <li><b>evaluation.txt</b> - Contains evaluation results table as well as Confusion Matrix of Spam and Ham classes.</li>
</ul>

<h4>Source Directories:</h4>
<ul>
  <li><b>train directory</b> - Includes all emails for the training phase of the program.</li>
  <li><b>test directory</b> - Includes all emails for the testing phase of the program.</li>
</ul>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :book: 추가 기능</h2>

<p>In machine learning, naive Bayes classifiers are a family of simple "probabilistic classifiers" based on applying Bayes' theorem with strong (naive) independence assumptions between the features.
Abstractly, naive Bayes is a conditional probability model: given a problem instance to be classified, represented by a vector
<img src="image/1.png" alt="Formula 1" style="max-width:100%;"></p>

<p>representing some n features (independent variables), it assigns to this instance probabilities
<img src="image/2.png" alt="Formula 2" style="max-width:100%;"></p>

<p>The problem with the above formulation is that if the number of features n is large or if a feature can take on a large number of values, then basing such a model on probability tables is infeasible. We therefore reformulate the model to make it more tractable. Using Bayes' theorem, the conditional probability can be decomposed as
<img src="image/3.png" alt="Formula 3" style="max-width:100%;"></p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

