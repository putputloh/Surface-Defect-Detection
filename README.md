# Surface-Defect-Detection
<h3>Introduction:</h3>
🙅‍♂️ Human quality inspection <br>
  &emsp; ➣ Some defects tend to be miniature and difficult to identify <br>
  &emsp; ➣ Various appearances and characteristics of defects often lead to misclassification of their categories <br>
🙆 AI inspection using deep learning semantic segmentation models <br>
  &emsp; ➣ Segment and classify defects in the input image by predicting pixel-labelled segmentation masks <br>
<h3>Objectives:</h3>
  &emsp; ➣ Research and develop deep learning semantic segmentation models for automatic defect detection <br>
  &emsp; ➣ Evaluate and compare CNN-based, Transformer-based and hybrid CNN-Transformer models in various aspects <br>
  &emsp; ➣ Explore and implement advanced weakly supervised semantic segmentation algorithms / frameworks <br>
<h3>Datasets</h3>
  &emsp; ➣ <a href="https://www.vicos.si/resources/kolektorsdd2/">Kolektor Surface-Defect Dataset 2 (KolektorSDD2/KSDD2)</a> <br>
  &emsp; ➣ <a href="https://www.kaggle.com/datasets/alex000kim/magnetic-tile-surface-defects"> Magnetic Tile Surface Defects</a> <br>
<h3>Results:</h3>
<table>
  <tr><th colspan=6>RANKINGS</th></tr>
  <tr><th rowspan=2>Fully-Supervised</td>
      <td colspan=2>mIoU</td>
      <th rowspan=2>Weakly-Supervised</td>
      <td colspan=2>mIoU</td></tr>
  <tr><td>Magnetic Tile</td>
      <td>KolektorSDD2</td>
      <td>Magnetic Tile</td>
      <td>KolektorSDD2</td></tr>
  <tr><td><b>🥇TransDAU-Net</b></td>
      <td>83.58</td>
      <td>79.36</td>
      <td><a href="https://arxiv.org/abs/2004.04581">🥇SEAM</a></td>
      <td>-</td>
      <td>67.00</td></tr>
  <tr><td><a href="https://arxiv.org/abs/2102.04306">🥈TransU-Net</a></td>
      <td>83.19</td>
      <td>78.92</td>
      <td><a href="https://ieeexplore.ieee.org/document/7780688">😩CAM</a></td>
      <td>-</td>
      <td>39.84</td></tr>
  <tr><td><b>🥉Double U-Net</b></td>
      <td>82.81</td>
      <td>78.43</td>
      <td colspan=3></td></tr>
  <tr><td><a href="https://arxiv.org/abs/1505.04597v1">🏅U-Net</a></td>
      <td>80.65</td>
      <td>78.21</td>
      <td colspan=3></td></tr>
  <tr><td><a href="https://ieeexplore.ieee.org/document/9578646">😩SETR</a></td>
      <td>74.25</td>
      <td>72.98</td>
      <td colspan=3></td></tr>
  <tr><td><a href="https://ieeexplore.ieee.org/document/8812894">😩FCN</a></td>
      <td>66.95</td>
      <td>-</td>
      <td colspan=3></td></tr>
  <tr><td><a href="https://arxiv.org/abs/1511.07122">😩DilatedNet</a></td>
      <td>62.64</td>
      <td>-</td>
      <td colspan=3></td></tr>
</table>
<b>** Highlighted models = Self-designed models</b>
