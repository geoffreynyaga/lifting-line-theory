# Prandtl Lifting Line Theory

This script file generates the Lifting Line Theory curve and also return the 3D CL (coefficient of lift) for the wing

The complete step-by-step explanation/docs can be found here
(https://geoffreynyaga.com/python-code-lifting-line-theory/)

## Setup

- clone the project

```bash
git clone https://github.com/geoffreynyaga/lifting-line-theory.git
```

- cd into the project

```bash
cd lifting-line-theory
```

- create a virtual environment (for Mac/Linux users. Fow windows users create the virtualenv and manually cd into venv/Scripts folder and run activate.bat)

```bash
virtualenv venv && source venv/bin/activate
```

- install dependancies

```bash
pip install -r requirements.txt
```

- Replace the following values with your appropriate values

```python
S: float = 24.39  # wing area m^2
AR: float = 7.8  # Aspect ratio
taper: float = 0.45  # Taper ratio
alpha_twist: float = -2.0  # Twist angle (deg)
i_w: float = 1.0  # wing setting angle (deg)
a_2d: float = 6.8754  # lift curve slope (1/rad)
alpha_0: float = -4.2  # zero-lift angle of attack (deg)
```

- run the file in Terminal

## Results

![Screenshot 1](https://geoffreynyaga.com/wp-content/uploads/2017/08/lifting-line-theory-elliptical-distribution-python-code.png)

and you also get the resulting CL

```bash
0.4049012444698557 CL_wing
```
