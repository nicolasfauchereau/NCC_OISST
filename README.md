In order to run the notebook, you need to install: 

+ curl: 

```
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)" < /dev/null 2> /dev/null
```

then
 
```
brew install curl
```

+ the NetCDF Operators (NCO): 

create a NCO environment: 

```
conda create -n NCO -c conda-forge nco
```

+ the Climate Data Operators (CDO): 

create a CDO environment: 

```
conda create -n CDO -c conda-forge cdo
```

