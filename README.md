
<h1><center>VideoLSP10</center></h1>
The sign dataset for Peruvian Sign Language  was created with the objective of encouraging students and researchers to find better solutions to reduce the gap that exists between the deaf community and normal people, also to be used as training data for different learning models this dataset include 3 dataset called depthLSP, skeletonLSP10 and LSP10. <br>
<a href="https://drive.google.com/drive/folders/1Bx3vP_ATx6DMBKhIUSh_3hocAAoNa6i6?usp=sharing">You can download VideoLSP10 dataset here</a>

## DepthLSP
This dataset contains only depth frame divided into 14 classes, it was obtained by the Kinect sensor v1 at a resolution of 480x640 in closed environments. Each depth frame have both hands in different position according to label.

|Nro| <big>Label</big> | <big>#Images </big>  |
|------|------ |------     |
|1|pos1   | 173       |  
|2|pos2    |210        | 
|3|pos3  | 160       |
|4|pos4 | 60        |
|5|pos5  | 185       |
|6|pos6 |152    | 
|7|pos7  |195        |
|8|pos8  |96         |
|9|pos9  | 152       |  
|10|pos10 | 99      |
|11| pos11  | 135       |  
|12| pos12 | 230      |
|13|pos13   | 99        |  
|14|pos14    | 99        | 
|<b>TOTAL</b>|-|    <b>2045</b> |


<h3>
<strong>Samples:</strong>
</h3>
<br>
<div class="row">
  <div class="column" style="float: left; width: 33.33%;  text-align:center">
      <div>
          <img src="./img/depth/pos9.png" alt="Snow" >
      </div>
      <span>pos9</span>
  </div>
  <div class="column" style="float: left; width: 33.33%;  text-align:center">
     <div>
          <img src="./img/depth/pos12.png" alt="Snow">
      </div>
      <span>pos12</span>
  </div>
  <div class="column" style="float: left; width: 33.33%;  text-align:center">
     <div>
          <img src="./img/depth/pos2.png" alt="Snow" >
      </div>
      <span>pos2</span>
  </div>
</div>
<h3><a href="https://drive.google.com/open?id=1ll9QGjXHGcWHlFhK_F_1FPy6y0vy1uOc">Download depthLSP from Google drive</a></h3><br>

## SkeletonLSP
This dataset contains 1701 skeleton movements that are divided into 21 classes, each class has 81 sequences of movement where each frame of a movement is composed of 10 coordinates (<strong>x, y, z</strong>), the coordinates are points of union of the upper body (hand right, wrist right, elbow right, shoulder right, head, shoulder center, shoulder left, elbow left, wrist left and hand left). The character <strong>"l"</strong> (left hand), <strong>"r"</strong> (right hand) and <strong>"b"</strong> (both hands) are prefixed to each tag as a reference to the hand that executes an action or movement. The movements are directed to certain directions (up, front, left, right, head, mouth and chest).

|Nro| <big>Label</big> | <big>#Videos </big>  |Nro| <big>Label</big> | <big>#Videos </big>  |
|------|------ |------     |------|------ |------       |
|1|l-up | 81               |11| r-right   | 81          |   
|2|r-up   |81              |12| b-right   | 81          |
|3|b-up  | 81              |13|l-head     | 81          | 
|4|l-front | 81            |14|r-head     | 81          | 
|5|r-front | 81            |15|b-head     | 81          | 
|6|b-front |81             |16|l-mouth    | 81          |  
|7|l-left  |81             |17|r-mouth    | 81          | 
|8|r-left |81              |18|b-mouth    | 81          | 
|9|b-left  | 81            |19|l-chest    | 81          |  
|10|l-right | 81           |20|r-chest    | 81          | 
| - |-   | -               |21|b-chest    | 81          |
| <b>TOTAL</b> |-   | -| - | - |    <b>1701</b> |

<h3>
<strong>sample sequence:</strong>
</h3> <br>

<div class="row">
  <div class="column" style="width: 100%;  text-align:center">
      <div>
          <img src="./img/join/aarriba.png" alt="Snow" style="width:100%">
      </div>
      <span>b-up</span>
  </div>
</div>
<h3><a href="https://drive.google.com/open?id=1ZP4vaRWslEalqQF8TsWiYI7DpiCOOyd1">Download skeletonLSP from Google drive</a> </h3><br>

## LSP10
This data set contains 10 Peruvian phrases most used in daily life and selected according to our criteria. Each phrase consists of 60 videos stored in <strong>rgb</strong>, <strong>depth</strong> and <strong>skeleton</strong> format which were captured in different environments with natural light, artificial and with different intensities. The number of frames in each phrase varies in a range of 17 to 197 depending on the gesture complexity.
Recorded data was made to 25 individuals who were taught each phrase before recording. 
Dataset LSP10 was recorded using the Kinect sensor v1, for <strong>rgb</strong> and <strong>depth</strong> data were recorded at a resolution of <strong>480 x 640</strong> and for <strong>skeleton</strong> data was considered 10 points of union (hand right, wrist right, elbow right, shoulder right, head, shoulder center, shoulder left, elbow left, wrist left, hand left).

|Nro| <big>Label</big> | <big>#Videos </big>  |
|------|------ |------     |
|1|Help me             | 60       |  
|2|Please              |60        | 
|3|I am sorry          | 60       |
|4|¿What are your name? | 60        |
|5|I do not understand | 60       |
|6|¿Where do you live? |60    | 
|7|¿What are you do?  |60        |
|8|Hello, ¿How are you? |60         |
|9|Thank you           | 60      |
|10| See you tomorrow   | 60       |  
|-|<b>TOTAL</b>|    <b>600</b> |

<h3>
<strong>sample phrase which show 3 data types contained in LSP10:</strong>
</h3> <br>
<div class="row">
  <div class="column" style="width: 100%;  text-align:center">
      <div>
          <img src="./img/total/3.png" alt="Snow" style="width:50%">
      </div>
      <div>
          <img src="./img/total/1.png" alt="Snow" style="width:50%">
      </div>
      <div>
          <img src="./img/total/2.png" alt="Snow" style="width:50%">
      </div>
      <span>See you tomorrow </span>
  </div>
</div>
<h3><a href="https://drive.google.com/open?id=157J-0IQ6L_LKiRLPXk3WM1s3gpoGxmsM">Download LSP10 data from Google drive</a> </h3><br>

## structure of the datasets VideoLSP10
<ul>
    <li><strong>DepthLSP</strong></li>
    The file depthLSP.rar contains <b>xml</b> files which stores the depth information of a frame, inside the rar file there is a file <b>label.txt</b> which stores the tag which belongs a certain range of xml files.
    <li><strong>SkeletonLSP</strong></li>
    The skeletonLSP.rar contains a set of folders with the same name as the tag to which they belong; each folder contains files in txt format that store the coordinates (<strong>x, y, z</strong>) of each captured frame.
    <li><strong>LSP10</strong></li>
    The LSP10 dataset is divided in 3 directories. The file label.txt into directory contains the labels for the 3 directories.
    <ul>
        <li>rgb:</li>
        Contains only rgb data for each phrase recorded.
        <li>depth:</li>
        Contains only depth data for each phrase recorded.
        <li>skeleton:</li>
        Contains only skeleton data for each phrase recorded.
    </ul>
</ul>

## Tools for preprocessing
Coming soon...

## License
<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Licencia de Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Dataset" property="dct:title" rel="dct:type">VideoLSP10</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/videoLSP/VideoLSP10.git" property="cc:attributionName" rel="cc:attributionURL">Yuri Vladimir Huallpa Vargas</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Reconocimiento-NoComercial 4.0 Internacional License</a>.<br />Creado a partir de la obra en <a xmlns:dct="http://purl.org/dc/terms/" href="https://github.com/videoLSP/VideoLSP10.git" rel="dct:source">https://github.com/videoLSP/VideoLSP10.git</a>.

If you use this work, you must comply with the following:
<ul>
    <li>Academic, educational or personal use is allowed without restrictions</li>
    <li>You must share any derivative works under the same license (ie, preprocessed versions of the dataset, subsets, supersets using other datasets).</li>
    <li>You must mention this website</li>
    <li>Commercial uses of the dataset are not allowed.</li>
</ul>

##  Contact

<b>Yuri Vladimir Huallpa Vargas</b> yurihuallpavargas@gmail.com
