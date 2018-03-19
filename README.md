


# Installation guide for pyrouge


## Dependencies

```
cpan install XML::DOM
```

## Clone this repository

```
cd $HOME
git clone https://github.com/laiviet/PyROUGE.git
mv PyROUGE .PyROUGE
```

## Configure pyrouge
```
cd $HOME
mkdir .pyrouge
echo "[pyrouge settings]" > $HOME/.pyrouge/settings.ini
echo "home_dir = $(pwd)/.PyROUGE/" >> $HOME/.pyrouge/settings.ini
```




