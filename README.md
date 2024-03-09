Some tests on a inverse problem for an [heat equation](https://github.com/hippylib/hippylib/blob/master/applications/time_dependent/model_heat.py) using the library (hippylib)[https://github.com/hippylib/hippylib].
|Gamma|Delta|Prior Variance|Rel Error|Posterior Variance|Centered|
|-----|-----|--------------|---------|------------------|--------|
|0.1  |0.5  |55            |0.005    |7.8               |Yes     |
|0.1  |0.5  |55            |0.03     |8.6               |No      |
|0.1  |0.05 |654           |0.006    |9.47              |Yes     |
|0.1  |0.05 |654           |0.02     |10.46             |No     |