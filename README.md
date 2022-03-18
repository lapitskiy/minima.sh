# minima.sh
group 9001

useradd: group '9001' does not exist

https://unix.stackexchange.com/questions/695876/useradd-group-9001-does-not-exist/695880#695880

wget -O minima_setup.sh https://github.com/lapitskiy/minima.sh/blob/0fef185261a358b6f6b7d5bff0565bbc851f5465/minima_setup.sh && 
chmod +x minima_setup.sh && sudo ./minima_setup.sh -r 9002 -p 9001
