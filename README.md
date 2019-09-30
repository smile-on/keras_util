# Set of simple helpers for Keras

Some functions that should be included in [Keras](https://keras.io) for user convenience but are too small and forgotten.

Example:  

- Keras training history visualization
```python
import keras_util as u

history = model.fit(..)
u.plot_history(history)

fig, axs = plt.subplots(4,1)
custom_axs = [axs[1], axs[3]]
u.plot_history(history, custom_axs)
````

