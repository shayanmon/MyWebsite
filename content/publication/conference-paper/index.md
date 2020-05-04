---
abstract: Bile duct cancer, or cholangiocarcinoma, is a rare and aggressive form of cancer, with approximately 2,500 new diagnoses each year in the United States. Biliary adenocarcinoma comprise of 90% of reported cholangiocarcinoma cases and often presents symptoms in later stages and is therefore associated with poor patient outcomes. Survival rates of cholangiocarcinoma when diagnosed at late stage are 6%, but can be improved to 15% when diagnosed early. Many previous studies have investigated the role of quantitative histomorphometric (QH) features on routinely acquired hematoxylin and eosin (H&E) slides of pancreatobiliary biopsies to help identify malignancies in the lining of the biliary tract. The biopsy procedure carries a high risk of strictures and peritonitis. An alternative to biopsy is a bile duct brushing (BDB), which exclusively contain epithelial cells fixed in cytology slides and have lower complication rates. The goal of this proof of concept study was to evaluate the role of image texture features to differentiate benign clusters and adenocarcinoma on digitized BDB specimens. Textural descriptors are able to characterize local regions of interest within malignant lesions by computing spatial arrangements and statistics of color intensities. Typical features often used in characterizing image texture include Gabor, Law, Haralick, and Co-occurrence of Local Anisotropic Gradient Orientations (CoLlAGe) features. These features are able to capture subtle differences in malignant and benign phenotypes caused by a multitude of phenotypic changes, including nuclear overcrowding, disorientation, and disorderly chromatin distribution. Pixel-wise texture features from each family were computed on whole slide images (WSIs) of BDBs corresponding to 59 unique patients of which 31 were from patients pathologically confirmed as having biliary adenocarcinoma through next generation sequencing, and the remaining 28 were confirmed as benign. Each WSI was magnified at 11X, 5.5X, and 2.25X before features were extracted. A total of 445 clusters were annotated across all slide images, of which 275 were identified as malignant by an expert cytopathologist, and used as the ground truth for our machine learning models. The pixel-wise feature distributions were summarized using mean, median, standard deviation, skewness, and kurtosis. The top five statistical texture features were selected using Wilcoxon ranksum, two-sided t-test, and maximum relevance minimum redundancy tests in 3-fold patient-wise cross validation and used to train three different machine learning classifiers. A linear discriminant classifier was trained with the mean Haralick information measure 2, standard deviation and median of CoLlAGe correlation, and mean of 2D Gabor response with {0,4}Hz frequencies and orientations f2 ; 58 g radian orientations, all selected by the mRMR test. We obtained an AUC of 0:83 ±0:01 using 3-fold cross-validation on 39 patients in the training set and 20 patients in the testing set.
authors:
- admin
- Patrick Leo, Kaustav Bera, Behtash G. Nezami, Claire W. Michael, Aparna Harbhajanka, Anant Madabhushi
date: "2020-March-16"
doi: ""
featured: true
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: true


publication: In *Source Themes Conference*
publication_short: In *STC*
publication_types:
- "1"
publishDate: "2020-March-16"
slides: example
summary: This study attempts to learn the morphological differences between benign and malignant clusters on bile duct brushing cytology slides for the purpose of a diagnostic support tool for cytopathologists.
tags:
- Source Themes
title: Texture features distinguish benign cell clusters from adenocarcinomas on bile duct brushing cytology images
url_pdf: https://www.spiedigitallibrary.org/conference-proceedings-of-spie/11320/113200I/Texture-features-distinguish-benign-cell-clusters-from-adenocarcinomas-on-bile/10.1117/12.2550870.full
---

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).

