# fastAI_boneage
Repo of my attempt to replicate the bone age competition - http://rsnachallenges.cloudapp.net/competitions/4#learn_the_details

#Set up the FastAI conda env based on the YAML 
conda env create -f environment.yml

# Steps
1. Noticed there are two directories in the validation dataset - so tried to find out what was the difference

```
diff -qr dir1 dir2
ls > filenames.txt
```

