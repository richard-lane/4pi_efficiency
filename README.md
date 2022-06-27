efficiency example
====

 * Copy/move the data to this dir
 ```
 scp <USERNAME>@lxplus.cern.ch:/afs/cern.ch/user/b/bwesthen/work/public/For_Richard/Total_DK_as_DK_MC_2017_After_PIC_Calib2_pols_merged_with_PID.root .
 ```

 * Create python virtual env if you need to

 ```
 conda create --name benEnv python=3.10
 ```

 * install requirements
 ```
 pip install -r requirements.txt
 ```

 * run notebook
 ```
 jupyter-notebook efficiency.ipynb
 ```

