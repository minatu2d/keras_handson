Deep learning with keras (Hand-ons)
---

## 1. Install python and virtual enviroment tools
### 1.1 On MAC: Refer https://qiita.com/7110/items/1aa5968022373e99ae28
- Install python
```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew install python3
python3 -V
pip3 install virtualenv
```

- Create virtual enviroment

```
virtualenv --python=/usr/local/bin/python3 --no-site-packages ~/python_env/default_py3
```

### 1.2 On windows: No care

### 1.3 On Linux : DIY

## 2. Install requirement library into "virtual enviroment"
- Activate created `virtual enviroment`
```bash
source ~/python_env/default_py3/bin/activate
```

- Install `numpy`
```bash
pip install numpy
```
- Install `tensorflow` and `keras`
```bash
pip install keras tensorflow
```

- Install `matplotlib`
```bash
pip install matplotlib
```

- Install `Jupyter notebook`
```bash
pip install jupyter
```

## 3. Clone source code
```
git clone https://github.com/minatu2d/keras_handson.git
```

## 4. Run code on `Jupyter notebook`
- Activate created `virtual enviroment` if not yet
```bash
source ~/python_env/default_py3/bin/activate
```

- Change directory to `source code`
```bash
cd keras_handson
```

- Run `Jupyter` under `keras_handson` directory
```
jupyter notebook
```