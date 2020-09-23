# Agent-Based-Simulation-Model
### Agent Based Simulation Model Created for CASA Dissertation 

This model seeks to test the logistical viability of cargo e-bikes as a van replacement in high density urban areas at a micro level through an agent based model built in Python’s Mesa library. In particular, the model simulates a single lane road where both vans and cargo bikes deliver parcels. This is important as there is growing concern about the impact vans have on cities both in terms of traffic and pollution.

![alt text](https://lh3.googleusercontent.com/tN1KVjHovXf5KczYzgt9YdMRf-fUWBGp4uR3cIgkrt21CUSTtMrjyrKohijgNrMF53r0c3Nb9d7Wyw5_ruztQ-ZxIHD-fZiHd1oJbyrr)

### Environment 

The model environment is built according to the road_map.txt. As can be seen in the image below. 1 translates to roads, 3 curbs, 4 delivery destinations, and 5 buildings which are not destinations. The size and proportions of the array also dictates the size and proportions of the model environment. The image below illustrates this. Note that the curb has  different colours to indicate if it is legal or not.

![alt text](https://lh5.googleusercontent.com/YLRbCdD8I0oMAMwFxBTSG8bxmOsg1ASyg4ypWDzNbf7TUxR_vZvnz2z_qFIgTYT-ZJS3A1t0yv8Ht6vyST4NhyUeyb9S4XoFgIWPaS6h)

### To Run the Model

Simply download the python notebook and the road_map.txt (or make your own) file in the same directory and run all the cells. The code is commented so that you know what everything does, but many model parameters are customisable even without having to read the code. Simply change the parameters in the model and click reset to save changes. Then click run.

![](ABMGIF.gif)
