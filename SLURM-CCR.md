# ez

sqstat --clusters=mae

squeue -M mae

sacctmgr show qos compbio

sinfo -M mae

sinfo -M mae -Nel -p compbio

squeue -o %.8i%.12P%.48j%.12u%.8t%.12M%.8m%.8D%.8C%.24R -M mae -p compbio                          (zack legend)

squeue -o "%.32j %.10i %.4t %.12M %.8C %.10m %.12N" -M mae -p compbio -u zmfalls --sort=-t
