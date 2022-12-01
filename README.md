# JourneeGridap2022

WELCOME to Journée Gridap.jl!

🚨 **BEFORE STARTING THE SESSION: Please make sure you have gone through the points below** 👇

## Session checklist

```
github.com/gridap/JourneeGridap2022
```

If you have not completed an item, click on it for further instructions.

* [I have a Julia installation](#installing-julia) on my laptop
* [I have a ParaView installation](#installing-paraview) on my laptop
* [I have run the `LoadGridap` notebook](#running-the-notebooks-locally)
* [I have pulled the latest version](#pulling-the-latest-version-of-the-course-material) of this project

## About the tutorial

This event is hosted by Groupe Calcul and INRIA Saclay. The two speakers are Gridap's founder [Francesc Verdugo](https://github.com/fverdugo) and Gridap's contributor [Eric Neiva](https://github.com/ericneiva).

The session will consist of several **hands-on tutorials and exercises on Jupyter notebooks** to discover and learn about the basic and advanced features of [Gridap](https://github.com/gridap/Gridap.jl).

⚠️ In order to follow the session activities on your laptop, **you'll need a local installation of Julia and ParaView**.

**Alternatively, if you have access to [mathrice's JupyterCloud](https://jupytercloud.math.cnrs.fr/sites/)**, you only need to install ParaView and run the `LoadGridap` notebook on your JupyterLab notebook server.

## Getting help

Contact Eric Neiva (eric.neiva@college-de-france.fr) if you need help setting up your laptop for the session.

## Installing Julia

Instructions to download and install the current stable release of Julia for the platform of your choice are available [on this download table](https://julialang.org/downloads/#current_stable_release).

Please, make sure you follow the platform specific instructions by clicking on the **`[help]`** link next to every platform name in the left column of the download table.

## Installing ParaView

Download ParaView for your platform of choice [here](https://www.paraview.org/download/).

Linux installation is very straighforward, you just need to download, uncompress and (optionally) add the binary folder to your `PATH` environment variable.

## Running the notebooks locally

Clone the repository
```
$ git clone https://github.com/gridap/JourneeGridap2022.git
```

Move into the folder and open a Julia REPL setting the current folder as the project environment. 
```
$ cd JourneeGridap2022
$ julia --project=.
               _
   _       _ _(_)_     |  Documentation: https://docs.julialang.org
  (_)     | (_) (_)    |
   _ _   _| |_  __ _   |  Type "?" for help, "]?" for Pkg help.
  | | | | | | |/ _` |  |
  | | |_| | | | (_| |  |  Version 1.8.3 (2022-11-14)
 _/ |\__'_|_|_|\__'_|  |  Official https://julialang.org/ release
|__/                   |

julia> 

```

Instantiate the environment. This will automatically download all required packages.
```
# Type ] to enter in pkg mode
(JourneeGridap2022) pkg> instantiate
```

Open the notebooks
```
julia> using IJulia
julia> notebook(dir=pwd())
```
This will open a browser window. 

Navigate to the `notebooks` folder, open the tutorial `LoadGridap` and run it.

If there are no problems with `LoadGridap`, open any other tutorial. Enjoy!

## Pulling the latest version of the course material

If you have cloned the repository a while ago, you can update to the newest version with these steps.

Go to the JourneeGridap2022 repo folder and git pull
```
$ git pull
```
Open Julia REPL
```
$ julia --project

```
and instantiate the environment again
```
# Type ] to enter in pkg mode
(JourneeGridap2022) pkg> instantiate
```

Done!

