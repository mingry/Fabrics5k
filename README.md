# Estimating Cloth Simulation Parameters From Tag Information and Cusick Drape Test

## Abstract

In recent years, the fashion apparel industry has been increasingly employing virtual simulations for the development of new products. The first step in virtual garment simulation involves identifying the optimal simulation parameters that accurately reproduce the drape properties of the actual fabric. Recent techniques advocate for a data-driven approach, estimating parameters from outcomes of a Cusick drape test. Such methods deviate from standard Cusick drape tests, introducing high-cost tools, which reduces practicality. Our research presents a more practical model, utilizing 2D silhouette images from the ISO-standardized Cusick drape test. Notably, while past models have shown limitations in estimating stretching parameters, our novel approach leverages the fabric’s tag information including fabric type and fiber composition. Our proposed model functions as a cascaded system: first, it estimates stretching parameters using tag information, then, in the subsequent step, it considers the estimated stretching parameters alongside the fabric sample’s Cusick drape test results to determine bending parameters. We validated our model against existing methods and applied it in practical scenarios, showing promising outcomes.

## Authors

- Eunjung Ju¹
- Kwang-yun Kim¹
- Gyoo-Chul Kang¹
- Sungjin Yoon¹
- Phil Sik Chang¹
- Eungjune Shim¹
- Myung Geol Choi²

Affiliations:
¹ CLO Virtual Fashion Inc., South Korea
² The Catholic University of Korea, South Korea

## Resources

- [Eurographics Digital Library](https://diglib.eg.org/handle/10.1111/cgf15027)
- [Preprint PDF (31.62MB)](Fabrics5k_eg_CRC.pdf)
- [Video [Youtube]](https://youtu.be/EJ5tjclYSZ8)

## Results

The left image in each pair is a skirt made of actual fabric, and the right image is a skirt simulated with virtual fabric using the simulation parameters estimated by our model.

![Results Comparison](figure_only_skirt.png)

## Bibtex

```bibtex
@article {ju2024fabrics5k,
  journal = {Computer Graphics Forum},
  title = {{ Estimating Cloth Simulation Parameters From Tag Information and Cusick Drape Test}},
  author = {Ju, Eunjung and Kim, Kwang-yun and Kang, Gyoo-Chul and Yoon, Sungjin and Chang, Phil Sik and Shim, Eungjune and Choi, Myung Geol},
  year = {2024},
  publisher = {The Eurographics Association and John Wiley & Sons Ltd.},
  ISSN = {1467-8659},
  DOI = {10.1111/cgf.15029}
}
