## My GitHub Account

> ### Content

```python
class Account(Projects):
  def __init__(self):
    '''
    This is my personal GitHub account, which hosts all the projects I'm working on.
    
    Projects
    ---
      Robotics:
        ROS, Reinforcement Learning, Computer Vision, Perception
        
      Data Science:
        Data processing and analysis with Python (Numpy, Pandas, etc.)
        
      Artificial Intelligence:
        Machine and Deep Learning based on Torch, Keras and TensorFlow
      
      Web Development:
        JavaScript (Node.js, Three.js, React.js, etc.), SQL, Python (Flask, Dash, etc.), HTML, CSS
    '''
    
    super().__init__(self)
    self.start()
    
  def start(self):
    self.robotics()
    self.data_science()
    self.artificial_intelligence()
    self.web_development()
```

<br>

<details>

<summary>Show projects</summary>

<br>

> ### Projects

```python
class Projects:
  def __init__(self):
    pass
    
  def robotics(self):
    import rospy
    
    rospy.init_node('robotics')
    
  def data_science(self):
    import numpy as np
    import pandas as pd
    
    df = pd.DataFrame({
      'name': ['Jon'],
      'surname': ['Martínez de Aguirre']
    })
    
  def artificial_intelligence(self):
    from torch import nn
    import tensorflow as tf
    
    torch_model = nn.Module()
    tf_model = tf.Model()
    
  def web_development(self):
    from flask import Flask
    
    app = Flask(__name__)
```

</details>

# 

<img align="right" src="https://github-readme-stats.vercel.app/api?username=jonmartinezdeaguirre&show_icons=true&icon_color=a80000&text_color=505050&bg_color=e0e0e0&title_color=003f61&custom_title=Stats"/>

### Contact me

<br>

> [![Gmail](https://img.shields.io/badge/-Gmail-red?style=for-the-badge&logo=Gmail&logoColor=white)](mailto:mtzjon10@gmail.com)
> 
> [![Linkedin](https://img.shields.io/badge/-LinkedIn-blue?style=for-the-badge&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/jon-martinez-de-aguirre-yeregui/)
