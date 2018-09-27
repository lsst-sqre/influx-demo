# influx-demo
Demonstration of the InfluxData stack

1. Clone this repo

```
git clone https://github.com/lsst-sqre/influx-demo.git
```

2. Create a virtualenv

```
cd influx-demo

virtualenv influx-demo -p python3
source influx-demo/bin/activate
pip install -r requirements.txt
```

3. Using the virtualenv in the Jupyter notebook

```
python -m ipykernel install --user --name=influx-demo
jupyter notebook
```

(You should now see your kernel in the Jupyter notebook menu: `Kernel -> Change kernel` and be able so switch to it.)

Open the `influx-demo.ipynb` notebook.
