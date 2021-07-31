# CityLearnFork

This repository has code for an environment called CityLearn. The main code for this is in citylearn.py. The repo also has a reward_function.py which is modifiable to tune the reward. The program requires a buildings_state_action_space.json as Ann input in order to run. The code is put together in the main.ipynb file, however, for this you simply need to run example_marlisa.ipynb. This repo was meant to be used for a challenge where groups make their own agents, however, CityLearn provided us with an example of their multi-agent model so we are using that.

Simply run the example_marlisa.ipynb file to run Marlisa in the CityLearn environment. Make sure to install all the dependencies: 

* Pandas 0.24.2 or older
* Numpy 1.16.4 or older
* Gym 0.14.0
* Json 2.0.9

In order to run the main files with the sample agent provided you will need:

* PyTorch 1.1.0

example_marlisa.ipynb was given to us inside the examples folder, all that had to be done was to install the dependencies and change the path of example_marlisa.ipynb.

Warning: example_marlisa.ipynb will take about 2 hours to run!