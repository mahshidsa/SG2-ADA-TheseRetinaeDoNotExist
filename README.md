# SG2-ADA-TheseRetinaeDoNotExist


1) The file "Discarded_left_samples.csv" contains the list of 42 Messidor-2 samples that we discarded from Messidor-2 data set.

2) Here is a link to the shared folder that contains the generated retina images that we used for unlinkability evaluation. We resized them to 750x750 pixels before using.
Link: https://drive.google.com/drive/folders/1HELUM4FBz85LisCEQFdg_iHRWOnpSGgw?usp=sharing


3) Here is the link to the snapshot for 5,000,000 generated retina. Use the pickle file to generate the retinal images.
Link: https://drive.google.com/file/d/1-tM_XpWLoOOG2i8xNN75v3jPoy5mkMeh/view?usp=sharing

Use the following code to generate images:


!python generate.py --outdir="Your prefered directory" --trunc=0.7 --seeds=1-5000000 \
    --network="directory to the pickle file network-snapshot-000120.pkl"
    
4) Note: --trunc=0.7 will generate 70% of the images which have better quality.
