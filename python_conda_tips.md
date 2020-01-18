# Tips for Conda 

Conda cheat sheet 
* https://conda.io/projects/conda/en/latest/user-guide/cheatsheet.html

When we want to install a specific vesion of package,
* conda install <package_name>=<version>=<build_string>

For example, find available pytorch builds using
* conda search -c pytorch pytorch  

Then, install using
* conda install -c pytorch pytorch=1.4.0=py3.7_cuda9.2.148_cudnn7.6.3_0
