# Two-Dimensional Hierarchical Rate Control Scheme For Light Field Compression Using MV-HEVC

:page_facing_up:Author code of the work published in Journal of Electronic Imaging, under the special section of Light Field Imaging.

Read paper at https://doi.org/10.1117/1.JEI.34.5.051005

:e-mail:Contact: ali.hassan@miun.se

# Results Comparison
If you want to compare the performance of your method with our as well as state-of-the-art algorithm results, you can consider the ```generate_figures.ipnyb``` file.
Open it in Google Colaboratory, add your data, and generate the results.

# Citation
If you use this source code or results, please consider citing the following work:
```
@ARTICLE{ahmad2019,
  author={Ahmad, Waqas and Ghafoor, Mubeen and Tariq, Syed Ali and Hassan, Ali and Sjöström, Mårten and Olsson, Roger},
  journal={IEEE Access}, 
  title={Computationally Efficient Light Field Image Compression Using a Multiview HEVC Framework}, 
  year={2019},
  volume={7},
  number={},
  pages={143002-143014},
  doi={10.1109/ACCESS.2019.2944765}}

@article{hassan2025,
  author = {Ali Hassan and Waqas Ahmad and Mubeen Ghafoor and Kamran Qureshi and Roger Olsson and M{\aa}rten Sj{\"o}str{\"o}m},
  title = {{Two-dimensional hierarchical rate control scheme for light field compression using Multi-View Extension of High-Efficiency Video Coding}},
  volume = {34},
  journal = {Journal of Electronic Imaging},
  number = {5},
  publisher = {SPIE},
  pages = {051005},
  year = {2025},
  doi = {10.1117/1.JEI.34.5.051005},
  URL = {https://doi.org/10.1117/1.JEI.34.5.051005}}


```



# Reference
The following algorithms have been considered:

Multidimensional Light Field Encoder using 4D Multiscale Transforms and Hexadeca-tree-oriented bit-plane Clustering (MuLE-MTH) \cite{alves2020jpeg}:
```
@article{alves2020jpeg,
  title={The JPEG Pleno Light Field Coding Standard 4D-Transform Mode: How to Design an Efficient 4D-Native Codec},
  author={Alves, Gustavo De Oliveira and De Carvalho, Murilo Bresciani and Pagliari, Carla L and Freitas, Pedro Garcia and Seidel, Ismael and Pereira, Marcio Pinto and Vieira, Carla Florentino Schueler and Testoni, Vanessa and Pereira, Fernando and Da Silva, Eduardo AB},
  journal={IEEE Access},
  volume={8},
  pages={170807--170829},
  year={2020},
  publisher={IEEE}
}
```
HEVC anchor \cite{hevcencoder265}
```
@software{hevcencoder265,
  author    = {x265 Project},
  title     = {x265 HEVC Encoder},
  version   = {3.5},
  howpublished       = {\url{https://www.videolan.org/developers/x265.html}},
  note      = {(Accessed: 01 November 2024)},
}
```
4D-Prediction mode (Warping and Sparse Prediction (WaSP)) \cite{jpeg21}
```
@misc{jpeg21,
     title = {JPEG Pleno Light Field Verification Model 2.1},
     howpublished = {\url{https://gitlab.com/wg1/jpeg-pleno-vm}},
     note  = {(Accessed: 01 August 2024)},
     type = {Web Page}
}
```
HEVC-based LF codec (HEVC-HR) \cite{monteiro2020light}
```
@article{monteiro2020light,
  title={Light field image coding based on hybrid data representation},
  author={Monteiro, Ricardo JS and Rodrigues, Nuno MM and Faria, S{\'e}rgio MM and Nunes, Paulo JL},
  journal={IEEE Access},
  volume={8},
  pages={115728--115744},
  year={2020},
  publisher={IEEE}
}
```
Versatile Video Coding (VVC)-serpentine \cite{avramelos2019light}
```
@inproceedings{avramelos2019light,
  title={Light field image compression using versatile video coding},
  author={Avramelos, Vasileios and De Praeter, Johan and Van Wallendael, Glenn and Lambert, Peter},
  booktitle={2019 IEEE 9th International Conference on Consumer Electronics (ICCE-Berlin)},
  pages={70--75},
  year={2019},
  organization={IEEE}
}
```
Warping and Sparse Prediction on Regions (WaSPR) \cite{astola2019coding}
```
@article{astola2019coding,
  title={Coding of light fields using disparity-based sparse prediction},
  author={Astola, Pekka and Tabus, Ioan},
  journal={IEEE Access},
  volume={7},
  pages={176820--176837},
  year={2019},
  publisher={IEEE}
}
```
LF Translational Codec (LFTC) \cite{heriard2019light}
```
@inproceedings{heriard2019light,
  title={Light field compression using translation-assisted view estimation},
  author={H{\'e}riard-Dubreuil, Baptiste and Viola, Irene and Ebrahimi, Touradj},
  booktitle={2019 Picture Coding Symposium (PCS)},
  pages={1--5},
  year={2019},
  organization={IEEE}
}
```


