stop_times.txt is too big for Github and git-lfs doesn't work 
on RHEL7. Concatenate stop_times00.txt, stop_times01.txt and 
stop_times02.txt to stop_times.txt before you use the data: 

`cat stop_times00.txt stop_times01.txt stop_times02.txt >> stop_times.txt`

Please submit patches to the partial files and not to the full 
file. 

