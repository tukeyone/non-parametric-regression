# Python examples

I will be using [**Spyder**](https://pythonhosted.org/spyder/) to run the examples for locally weighted regression (lwr).

## lwr_1D_example1.py

After opening lwr_1D_example1.py you should see the following in the Spyder editor:

<p align="center">
  <img src="../../docs/images/first_screen_shot.png" width="1280">
</p>

Proceed to run the first code block, shown in yellow, (**ctrl+enter**) and then the second.
The second code block will plot the 1D regression:

<p align="center">
<img src="../../docs/images/lwr_1D.png" width="480">
</p>

## lwr_1D_example2.py

The second 1D example shows how the hyper-parameters of lwr effect the regression line.

```python
  lwr_opts        = lwr_options()
  lwr_opts.D      = [1]           # variance of the radial basis function
  lwr_opts.y_bias = -1            # the bias the regression returns to when far from datapoints
  lwr_opts.print_param()
```

<p align="center">
<img src="../../docs/images/lwr_1D_example2.png" width="480">
</p>


## lwr_2D_example1.py

<img src="../../docs/images/lwr_2D_example1_train.png" width="400"/> <img src="../../docs/images/lwr_2D_example1_test.png" width="400"/>


## lwr_2D_example2.py

<img src="../../docs/images/lwr_2D_low_var.png" width="400"/> <img src="../../docs/images/lwr_2D_mid.png" width="400"/>
