# portafolio-python-Cinematic

In this work, using integral field spectroscopy data, we will calculate the rotation curves of a galaxy and compare them with the theoretical ones. This will allow us to observe the effect that dark matter has on the galaxy's rotation, serving as evidence of its existence. Before that, we will analyze how the redshift varies across the galaxy by integrating over different intervals around the H-alpha line, and we will visualize this variation with a GIF.

## Data

The data used in this work can be downloaded in this link: https://www.dropbox.com/scl/fo/x1kr9w0p5y498wiqehezr/AEIKpK4Np4YC_AkTTwGTViY?rlkey=tomexhbfnkmdv2eg03qu5p5wr&st=ririfw6a&dl=0

## You need to have (Requirements)

- Python 3.10

- NumPy

- Matplotlib 

- Astropy 

- Photutils

- Natsort 

- Jupyter Notebook

- Imageio

Install using:

```bash
pip install -r requirements.txt
```

## Structure
```
├── Cinematic_IFU130425.ipynb # Notebook 
├── requirements.txt # Requirements
└── README.md
```

## What you need to do

- Create an environment:
```
python3 -m venv envAstro
```
- Activate it:
source envAstro/bin/activate

- Install requirements inside environment
  
- Download the data

- Execute cells on jupyter lab

## Results

In this work, we successfully identified the HII regions based on redshift using different integration intervals, thus observing the effect of rotation and visualizing it with a GIF. For the rotation curves, which were the primary objective, we identified the wavelengths of the H-alpha and NII lines in different spectra from points distributed along the galaxy's major axis, using Gaussian fitting. These lines allow us to calculate the redshift at those points, and consequently, the rotational velocity.

Although the redshift results appeared to be correct, the plot of the experimental rotation curve does not match reality. This may be due to errors in performing the Gaussian fits, as the rotational velocities are highly sensitive to the redshift values.

## Author

Miguel Ángel Susillo Ridao

Linkedin: www.linkedin.com/in/miguelangelsurid
