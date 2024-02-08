## About

To facilitate research on the sleep symptomatology occurring during opioid withdrawal, the Sleep Neurobiology Laboratory at SRI International releases the C57BL/6J mouse morphine withdrawal (CMMW) dataset. This dataset contains EEG and EMG recordings conducted in male and female C57BL/6J mice. The data were collected during an experiment whose aim was to assess the impacts of opioid withdrawal on sleep and wakefulness in rodents. The data include the EEG and EMG signals collected during this study. Each individual in the cohort of adult male (N = 7; age: 10.4 ± 0.5 weeks) and female (N = 7; age: 9.9 ± 0.3 weeks) C57BL/6J mice received two treatments in a counterbalanced manner; 16 days elapsed between the final treatment in the first arm of the study and the 1st treatment in the second study arm:  

<u>Treatment 1:</u>  Bidaily SC injections of escalating doses of morphine sulfate (Day 1: 5 mg/kg, Day 2: 10 mg/kg, Day 3: 20 mg/kg, Day 4: 40 mg/kg and Day 5: 80 mg/kg) over 5 days followed by 7 days without injections.

<u>Treatment 2:</u> Bidaily SC injections of saline over 5 days followed by 7 days without injections.

## Methods

## Data overview

[/EDF](:files_path:/EDF)
EDF files exported by [NeuroscoreTM CNS Software](https://www.datasci.com/products/software/neuroscore) which include 1 EEG channel, 1 EMG channel, body temperature (Tsc), signal strength, and gross motor activity (LMA). EEG and EMG data were recorded at a sampling rate of 500 Hz, signal strength and Tsc at 10Hz, and Activity at 1 Hz with [Ponemah software (version 5.20; DSI)](https://www.datasci.com/products/software/ponemah).  The DSI F20-EET wireless transmitters only permit EEG power analysis in the 0.5-60 Hz range.

[/FFT](:files_path:/FFT)
CSV files exported by [Somnivore (version 1.1.7.0; Somnivore, Ltd. Pty.)](https://somnivore.ai/products/). These files contain an epoched (10-second epochs) representation of the data including (1) sleep stage (manually scored) and (2) power spectral density data as determined by fast Fourier transform across 985 bins between 0 and 60.059 Hz.


## Access and usage restrictions

The CMMW dataset is only available for non-commercial use.

## Citation and acknowledgement

When using this dataset, users must cite the following:

>[Zhang GQ, Cui L, Mueller R, Tao S, Kim M, Rueschman M, Mariani S, Mobley D, Redline S. The National Sleep Research Resource: towards a sleep data commons. J Am Med Inform Assoc. 2018 Oct 1;25(10):1351-1358. doi: 10.1093/jamia/ocy064. PMID: 29860441; PMCID: PMC6188513.](https://pubmed.ncbi.nlm.nih.gov/29860441/)

>[Tisdale RK, Sun Y, Park S, Ma SC, Haire M, Allocca G, Bruchas MR, Morairty SR, Kilduff TS. Biological sex influences sleep phenotype in mice experiencing spontaneous opioid withdrawal. J Sleep Res. 2023 Sep 20:e14037. doi: 10.1111/jsr.14037. Epub ahead of print. PMID: 37731248.](https://pubmed.ncbi.nlm.nih.gov/37731248/)

Users must include the following text in any Acknowledgements:

> The recordings deposited here were supported by NIH R01 HL150836 to Thomas S. Kilduff and Michael R. Bruchas. The National Sleep Research Resource was supported by the U.S. National Institutes of Health, National Heart Lung and Blood Institute (R24 HL114473, 75N92019R002).

## Changelog

*February 2024*

- Make CMMW dataset available for data requests

## References

- CMMW GitHub Documentation: https://github.com/nsrr/cmmw-documentation

## Questions?

Please reach out to us at support@sleepdata.org or in the [Forum](https://sleepdata.org/forum) if you have questions.
