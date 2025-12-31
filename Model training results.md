**Training Results:**

A simple PyTorch training loop was implemented for 5 epochs. The model showed strong learning progression, with training loss steadily decreasing and validation loss improving overall:

- **Epoch 1:** Train loss = 1.5594, Validation loss = 0.4131
- **Epoch 2**: Train loss = 0.5610, Validation loss = 0.2373
- **Epoch 3:** Train loss = 0.3503, Validation loss = 0.1352
- **Epoch 4:** Train loss = 0.2424, Validation loss = 0.1937
- **Epoch 5:** Train loss = 0.2104, Validation loss = 0.1391


**Observations:**
- Training loss consistently decreased, showing effective optimization.
- Validation loss decreased quickly in early epochs, suggesting the model learned meaningful features.
- Slight fluctuation in validation loss in epoch 4 indicates minor overfitting or sensitivity to batch data.
- Overall, the model achieved good convergence and generalization after just 5 epochs.
