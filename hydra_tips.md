# Download data 
wget URL 

# Start an interactive session in Hydra 
You start an interactive session with the command
qrsh

If you plan to use more than one thread, or will need more memory than the per slot limit, you can request more than one slot with

qrsh -pe mthread N
