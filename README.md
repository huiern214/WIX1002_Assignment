## WIX1002 FOP Assignment
(a)  Number of jobs created/ended within a given time range.  
 
(b)  Number of jobs by partitions, i.e. EPYC, Opteron and GPU.  
 
(c)  Number of jobs causing error and the corresponding user. The error is indicated as “[2022-06-01T15:12:23.290] error: This association…”  
 
(d)  Average execution time of the jobs submitted to UMHPC.  
 
(e)  Other statistical data that you can extract.  
- Average runtime submitted (usec: xxx from the lines that contain _slurm_rpc_submit_batch_job)
- Total no. of error (Job & Other Error)
- NodeList
- Number of requests to kill jobs (_slurm_rpc_kill_job: REQUEST_KILL_JOB)