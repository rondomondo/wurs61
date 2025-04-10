# Wender Utah Rating Scale (WURS) Assessment Tool

This repo contains a very simple web-based implementation of the [Wender Utah Rating Scale](https://en.wikipedia.org/wiki/Wender_Utah_Rating_Scale), a __self-report__ assessment tool designed to help adults evaluate childhood behaviors associated with [Attention Deficit Hyperactivity Disorder](https://www.psychiatry.org/patients-families/adhd/what-is-adhd).

It is a common diagnostic checklist that is widely understood. ADHD is one of the diagnosis included in the [Diagnostic and Statistical Manual of Mental Disorders (DSM-5-TR)](https://www.psychiatry.org/psychiatrists/practice/dsm)

<br>  

> __Quickstart__
> 
> Here is a hosted version of [this WURS61 checklist webpage](https://rondomondo.github.io/wurs61) that you could save to your computer. Just right click and then "Save As"


## About the Tool

The [Wender Utah Rating Scale](https://en.wikipedia.org/wiki/Wender_Utah_Rating_Scale) was developed to aid in the retrospective diagnosis of childhood ADHD in adults. The assessment consists of 61 questions about childhood behaviors with a subset of 25 questions specifically associated with ADHD symptoms. After completion, questions are scored according to [the rating scale](https://github.com/rondomondo/wurs61/blob/main/random/docs/wenderutah_rating_scale_61questions_full.pdf)

### Key Features herein attempted

- Complete 61-question assessment
- Calculation of both total score (61) and more ADHD-specific subscore
- Immediate visual feedback with score interpretation, top and bottom
- Hopefully works on desktop and mobile devices
- Highlighting of unanswered questions
- Score interpretation guidelines based on the [peer reviewed and oft cited research and source papers](https://github.com/rondomondo/wurs61/tree/main/random/docs)
- Along with the papers I mention in [random/docs](https://github.com/rondomondo/wurs61/tree/main/random/docs) do not that there is a ton of opinions on this topic. Be descerning in your research and please do cast a critical eye over any research you come across, check its source and the quality and quantity of citations from respected peer reviews.
 
## How to Use

1. Answer all 61 questions based on your childhood behaviors and experiences
2. Each question is rated on a 5-point scale from "Not at all" (0) to "Very much" (4)
3. Click "Calculate Scores" button when you've completed all questions
4. Review your score along with the basic interpretation

## Interpretation

The ADHD subscore is calculated from 25 specific questions that were found to be most discriminative for ADHD. A cutoff score of 46 for the ADHD subscore was found to correctly classify:
- 86% of patients with ADHD
- 99% of normal control subjects
- 81% of depressed subjects

**Important Note**: This questionnaire is for information purposes only and cannot replace a formal diagnosis by a qualified healthcare professional. Please, please see a real qualified professional if you feel the need.

## Technical Information

This app is built with:
- HTML5
- CSS3
- JavaScript (vanilla, no dependencies)

The entire application is contained in a single HTML file, making it easy to deploy and use without any server-side components. This will make it easy to copy around or send to anybody.

## Research Background

The Wender Utah Rating Scale was developed by Ward MF, Wender PH, and Reimherr FW, and published in the American Journal of Psychiatry in 1993. The scale has been validated in numerous studies and is widely used in clinical and research settings.

Primary Reference:
- Ward MF, Wender PH, Reimherr FW. The Wender Utah Rating Scale: An aid in the retrospective diagnosis of childhood Attention Deficit Hyperactivity Disorder. Am J Psychiatry. 1993; 150: 885-890.

## Additional Resources
- [A discussion on ADHD Diagnosis](https://www.youtube.com/watch?v=rdmdpMlmU-Q)
- [Discriminant Validity of the Wender Utah Rating Scale for Attention-Deficit/Hyperactivity Disorder in Adults](https://psychiatryonline.org/doi/full/10.1176/jnp.12.2.240)
- [Search for "Wender Utah Rating Scale" on Scholar](https://scholar.google.com/scholar?q=%22Wender+Utah+Rating+Scale%22)
- [Research by M.F. Ward](https://scholar.google.com/scholar?q=author%3A%22Ward+MF%22)
- [Research by P.H. Wender](https://scholar.google.com/scholar?q=author%3A%22Wender+PH%22)
- [Research by F.W. Reimherr](https://scholar.google.com/scholar?q=author%3A%22Reimherr+FW%22)
- [DSM5 ADHD Changes](https://www.ncbi.nlm.nih.gov/books/NBK519704/table/ch3.t21)
- [DSM5 Adult Specific](https://add.org/adhd-dsm-5-criteria/)
- [ADHD Information](https://www.psychiatry.org/patients-families/adhd/what-is-adhd)
- [What is the DSM](https://www.psychiatry.org/psychiatrists/practice/dsm)

## Installation/Deployment

To use:

1. Clone this repository
2. Open the [index.html](https://github.com/rondomondo/wurs61/tree/main/index.html) file in any modern web browser
3. No server or additional dependencies are required

## License

This tool is provided for educational and personal use. The [Wender Utah Rating Scale](https://en.wikipedia.org/wiki/Wender_Utah_Rating_Scale) itself is a published assessment tool and should be used in accordance with professional and ethical guidelines.

## Disclaimer

This application is not intended to diagnose any medical condition and should not be used as a substitute for professional medical advice, diagnosis, or treatment. Always seek the advice of a qualified healthcare provider with any questions you may have regarding a medical condition.