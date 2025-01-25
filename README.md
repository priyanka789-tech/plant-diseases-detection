import tensorflow as tf
import matplotlib.pyplot as plt
import pandas as pd
import seaborn as sns
---------------------------------------------------------------------------
ModuleNotFoundError                       Traceback (most recent call last)
Cell In[2], line 1
----> 1 import tensorflow as tf
      2 import matplotlib.pyplot as plt
      3 import pandas as pd

ModuleNotFoundError: No module named 'tensorflow'
import tensorflow as tf
import matplotlib.pyplot as plt
import pandas as pd
import seaborn as sns
---------------------------------------------------------------------------
ModuleNotFoundError                       Traceback (most recent call last)
Cell In[13], line 1
----> 1 import tensorflow as tf
      2 import matplotlib.pyplot as plt
      3 import pandas as pd

ModuleNotFoundError: No module named 'tensorflow'
import tensorflow as tf
import matplotlib.pyplot as plt
import pandas as pd
import seaborn as sns
---------------------------------------------------------------------------
ModuleNotFoundError                       Traceback (most recent call last)
Cell In[14], line 1
----> 1 import tensorflow as tf
      2 import matplotlib.pyplot as plt
      3 import pandas as pd

ModuleNotFoundError: No module named 'tensorflow'
training_set = tf.keras.utils.image_dataset_from_directory(
    'Dataset/train',
    labels="inferred",
    label_mode="categorical",
    class_names=None,
    color_mode="rgb",
    batch_size=32,
    image_size=(128, 128),
    shuffle=True,
    seed=None,
    validation_split=None,
    subset=None,
    interpolation="bilinear",
    follow_links=False,
    crop_to_aspect_ratio=False
)
---------------------------------------------------------------------------
NameError                                 Traceback (most recent call last)
Cell In[15], line 1
----> 1 training_set = tf.keras.utils.image_dataset_from_directory(
      2     'Dataset/train',
      3     labels="inferred",
      4     label_mode="categorical",
      5     class_names=None,
      6     color_mode="rgb",
      7     batch_size=32,
      8     image_size=(128, 128),
      9     shuffle=True,
     10     seed=None,
     11     validation_split=None,
     12     subset=None,
     13     interpolation="bilinear",
     14     follow_links=False,
     15     crop_to_aspect_ratio=False
     16 )

NameError: name 'tf' is not definedvalidation_set = tf.keras.utils.image_dataset_from_directory(
    'Dataset/valid',
    labels="inferred",
    label_mode="categorical",
    class_names=None,
    color_mode="rgb",
    batch_size=32,
    image_size=(128, 128),
    shuffle=True,
    seed=None,
    validation_split=None,
    subset=None,
    interpolation="bilinear",
    follow_links=False,
    crop_to_aspect_ratio=False
)
validation_set = tf.keras.utils.image_dataset_from_directory(
    'Dataset/valid',
    labels="inferred",
    label_mode="categorical",
    class_names=None,
    color_mode="rgb",
    batch_size=32,
    image_size=(128, 128),
    shuffle=True,
    seed=None,
    validation_split=None,
    subset=None,
    interpolation="bilinear",
    follow_links=False,
    crop_to_aspect_ratio=False
)
