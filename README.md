# Casting-Image-Data

## Project Detail

One of the ways to manufacture metal products is through a process called casting, in which liquid metal is poured into a mold to harden. Casting products may contain irregularities or defects and thus must be inspected prior shipping to ensure that customer specifications are met. Accurate inspection is important because defective products can cause rejection of the whole production order by the customers, resulting in financial loss for the casting company.

Visual inspection is a non-destructive technique to detect flaws on casting products. It involves an inspector looking at each test piece with the naked eye and then classifying the product as either defective or OK based on his assessment. Due to its reliance on human factors, however, visual inspection is prone to misclassification and can be time-consuming.

This project explores automation of visual inspection with computer vision. A deep learning model called convolutional neural networks (CNN) is created to distinguish images of defective and non-defective castings

following are some of the defects in the casting process.

* blow holes

* pinholes

* burr

* shrinkage defects

* mould material defects

* pouring metal defects

* metallurgical defects*

## Dataset 

Our casting product data comprises top-view 

JPEG images of cast submersible pump impellers

Images were captured with Canon EOS 1300D DSLR camera. Every images are 300×300 pixels in size and already labeled as either def_front (defective castings) or ok_front (non-defective).

The folder train in the input directory contains images that are used for model training/validation.

Images located in the test folder are used to test the trained model's performance.

