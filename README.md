# Critical Scale Invariance in a Healthy Human Heart Rate
> Group project for Laboratory of Computational Physics - Module A Course, AA 2022/23

### Description of the project
In this project you will analyse from a physics perspective time series of human heart rate. You will demonstrate the robust scale-invariance in the probability density function (PDF) of detrended healthy human heart rate increments. Moreover, you will show that such increments are not Gaussian distributed, but they display fat tails. This scale-independent and fractal structure supports the view that a healthy human heart rate is controlled to converge continually to a critical state.

### Original reference
[Critical Scale Invariance in a Healthy Human Heart Rate, Kiyono, Oct 2004](https://journals.aps.org/prl/pdf/10.1103/PhysRevLett.93.178103)

### Assignment steps
1. Build the cumulative time series $B(i)$ from the detrended and normalised heart beat time series $b(i)$
2. Do a polynomial fit of $B(i)$
3. Calculate the increments (fluctuation) from the polynomial fit
4. Build the increments PDF and fit it with Gaussian and non Gaussian distributions.
5. Test the scale invariance of the PDFs by collapse plot

### Data sources
1. [Fantasia](https://physionet.org/content/fantasia/1.0.0/)
2. [Normal Sinus Rhythm Database](https://www.physionet.org/content/nsrdb/1.0.0/)
3. [Congestive Heart Failure Database](https://physionet.org/content/chfdb/1.0.0/)

### Members of Group 2
* [Tommaso Bertola](https://github.com/tommaso-bertola)
* [Giacomo Di Prima](https://github.com/GiacomoDiPrima)
* [Giuseppe Viterbo](https://github.com/vepe99)
* [Marco Zenari](https://github.com/MarcoZenari)

![](https://contrib.rocks/image?repo=threeblueonebrowneyes/Critical-Scale-Invariance-Heart-Rate)


