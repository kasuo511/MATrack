# MATrack

raw results:

[[LaSOT]](https://drive.google.com/file/d/14qsubE5fWh3WBjmvCXpGYVkS84d67xZE/view?usp=sharing)

[[VOT2018]](https://drive.google.com/file/d/1Sz0VKEY9qYPSQCvCRZO5MXo2a1tK0CPk/view?usp=sharing)

[[VOT2019]](https://drive.google.com/file/d/1S_FGwTlzueANeHiCrMCcc34Qsv1jXV7s/view?usp=sharing)

## Install the environment with Anaconda

We assume your root path is `/home/ltp/Workspace/MATrack`
Your anaconda path is `/home/ltp/Workspace/anaconda3`

```
cd /home/ltp/Workspace/MATrack/lib/tutorial
bash install.sh /home/ltp/Workspace/anaconda3 MATrack
cd $MATrack
conda activate MATrack
python setup.py develop
```
## Test MATrack

download the test datasetson the official website and put them in this form:

   ```
   ${MATRACK_ROOT}
    -- dataset
    -- VOT2019.json
    -- LaSOT.json
        -- VOT2019
            |-- agility
            |-- ants1
            |-- ball2
            ...
        -- LaSOT
            |-- airplane-1
            |-- airplane-9
            |-- airplane-13
            ...
        ...

   ```
