# Age_Gender_Detection   <img alt="GitHub" src="https://img.shields.io/github/license/smahesh29/Gender-and-Age-Detection">


<h2>Project aim :</h2>
<p>To build a age and gender detector that can approximately guess the gender and age of the person (face) in a picture or through webcam.</p>


<h2>Dataset :</h2>
<p>For this python project, I had used the Adience dataset; the dataset is available in the public domain and you can find it <a href="https://www.kaggle.com/ttungl/adience-benchmark-gender-and-age-classification">here</a>.</p>

<h2> Libraries Required :</h2>
<ul>
  <li>OpenCV</li>
  
       pip install opencv-python
</ul>


 <h2>Usage :</h2>
 <ul>
  <li>Open your Command Prompt or Terminal and change directory to the folder where all the files are present.</li>
  <li><b>Detecting Gender and Age of face in Image</b> Use Command :</li>
  
      python detect.py --image <image_name>



<h2>Examples :</h2>


    >python detect.py --image girl2.jpg
    Gender: Female
    Age: 8-12 years
    
<img src="Example/Detecting age and gender girl2.png">

    >python detect.py --image kid1.jpg
    Gender: Male
    Age: 4-6 years    
    
<img src="Example/Detecting age and gender kid1.png">

    >python detect.py --image kid2.jpg
    Gender: Female
    Age: 4-6 years  
    
<img src="Example/Detecting age and gender kid2.png">

    >python detect.py --image man1.jpg
    Gender: Male
    Age: 38-43 years
    
<img src="Example/Detecting age and gender man1.png">


    >python detect.py --image girl1.jpg
    Gender: Female
    Age: 25-32 years
    
<img src="Example/Detecting age and gender girl1.png">

   
              
