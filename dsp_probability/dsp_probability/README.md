# dsp-probability packages


DSP probability contains methods to calculate the distributions of:

	- Gausian distribution
	- Binomial distribution


# Files

	Gaussiandistribution.py
	Binomialdistribution.py



# Instalation

pip install dsp-probability


# Example

from dsp_probability import Gaussian, Binomial

Gaussian(10,7)
Binomial(.4,25)

sample_n = Gaussian()
sample_n.read_data_file("numbers.txt")
sample_n.stdev
sample_n.mean
sample_n.pdf(100)
sample_n.plot_histogram_pdf()