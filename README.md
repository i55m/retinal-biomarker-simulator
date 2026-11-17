[README.md](https://github.com/user-attachments/files/35000237/README.md)
# Retinal & Neurovascular Biomarkers: Interactive Methods Tutorial

An interactive, self-contained tutorial exploring **common-cause causal structures**, **errors-in-variables attenuation**, and **biomarker engineering specifications** in retinal and cerebrovascular imaging research.

## What It Illustrates

1. **Common Causes, Analogy & Reichenbach's Principle:** Why retinal and brain measures correlate in the absence of a direct causal arrow ($R^* \nrightarrow B^*$), anchored in empirical meta-analyses of retinopathy and cerebral white matter hyperintensities (Dumitrascu et al., 2018) and the retina–brain analogy framework (MacCormick et al., 2022).
2. **Error on Both Sides of the Equation & The SNR Spectrum:** How measurement error in the retinal predictor flattens regression slopes (attenuation bias), how brain outcome error inflates variance, and how averaging $k$ repeated measurements within an eye reduces random error variance by $1/k$.
3. **Naive Covariate Adjustment vs. Errors-in-Variables Disattenuation:** Why conditioning on an error-free covariate such as chronological age ($C$) collapses conditional retinal reliability ($\text{ICC}_{R\mid C} < \text{ICC}_R$), flattens the Frisch–Waugh–Lovell residual plot, and transfers biological vascular signal onto Age—alongside how Errors-in-Variables / SEM models recover unbiased slopes with honest confidence intervals.
4. **Designing & Analysing an Ideal Retinal Biomarker:** Balancing biological proximity, spatial/temporal resolution, and within-eye signal averaging against practical clinical constraints (speed, cost, convenience, non-invasiveness), paired with explicit DAG/SEM reasoning.

## Running Locally

No build step or internet connection is required—simply open `index.html` in any modern web browser.

## Key References

- Reichenbach H (1956). *The Direction of Time*. University of California Press.
- Fuller WA (1987). *Measurement Error Models*. Wiley.
- Dumitrascu OM et al. (2018). Retinal microvascular abnormalities as surrogate markers of cerebrovascular ischemic disease: a meta-analysis. *J Stroke Cerebrovasc Dis*, 27(7):1960–1968.
- Cinelli C, Forney A, Pearl J (2022). A crash course in good and bad controls. *Sociological Methods & Research*.
- MacCormick IJC, Zhang B, Hill D, Cordeiro MF, Small DS (2022). A proposed theoretical framework for retinal biomarkers. *Alzheimer's & Dementia: Diagnosis, Assessment & Disease Monitoring*, 14:e12327.
