# Clinical Cohort Simulation Data Dictionary & Biostatistics Protocol (v2.0)

**Study:** Placebo is the Real Therapy — Etymological, Phenomenological & Psychological Analysis  
**Authors:** Şevval Emine Köken (*Faculty of Medicine, Gazi University*), Ömer Hakan Köken  
**Dataset Reference:** `MOD_S3_Clinical_Cohort_Simulation_Data.csv`

---

## 1. Variable Definitions & Clinical Coding Standards

| Variable / Parameter Domain | Data Type | Measurement Unit / Scale | Clinical & Phenomenological Definition |
| :--- | :--- | :--- | :--- |
| **Subject_ID** | Categorical (String) | Alphanumeric Code | Anonymized unique identifier for simulated clinical cohort participants. |
| **Cohort_Arm** | Categorical (Nominal) | Active / Open-Label Placebo / Control | Treatment allocation arm distinguishing pharmacological intervention, open-label placebo, and no-treatment baseline. |
| **Baseline_Symptom_Score** | Continuous (Numeric) | 0 – 100 VAS (Visual Analog Scale) | Pre-intervention subjective symptom severity recorded prior to therapeutic encounter. |
| **Post_Intervention_Score** | Continuous (Numeric) | 0 – 100 VAS (Visual Analog Scale) | Post-intervention symptom severity measuring overall therapeutic response. |
| **Expectancy_Index** | Ordinal / Continuous | 1 – 10 Likert Scale | Quantified patient belief and therapeutic alliance score regarding treatment efficacy. |
| **Neurobiological_Response_Delta** | Continuous (Numeric) | $\Delta$ Score Change | Net clinical improvement attributable to endogenous conditioning and contextual healing mechanisms. |

---

## 2. Biostatistical Evaluation Framework
* **Primary Endpoint Analysis:** Between-group comparison of $\Delta$ symptom reduction using independent two-sample t-tests and Mann-Whitney U tests for non-parametric distributions ($\alpha = 0.05$).
* **Effect Size Estimation:** Standardized mean difference quantified via **Cohen's $d$** to evaluate clinical magnitude beyond statistical significance.
* **Contextual Conditioning Modeling:** Linear regression evaluating the correlation between `Expectancy_Index` and `Neurobiological_Response_Delta`.

## 3. Keywords & Academic Indexing
`Placebo Effect`, `Open-Label Placebo`, `Clinical Cohort Simulation`, `Data Dictionary`, `Medical Psychology`, `Phenomenology of Medicine`, `Therapeutic Alliance`, `Biostatistics`, `Gazi University`, `Open Science`.
