# Traj_based_MLP

It's a trial to make a trajectory based classifier following the article https://pubs.acs.org/doi/10.1021/acs.jpclett.1c01494
The MLP notebook is adopted from: https://github.com/zzhang624/ML-SARS-CoV-2

Here a couple of notebooks (Distance Feature folder) extract the inter-residue distances (for couples within certain cutoff) from trajectories and create the feature matrix.

MLP.ipynb use that feature mat. to train a MLP and act as a predictor for blind dataset.
 
