Create and run a container maned `my-web` in localhost on port 8080

<br>

### Solution
First, we make sure we're in our home directory using

```plain
cd ~
```{{exec}}
We can list the current directory using
```plain
pwd
```{{exec}}
Now we create and run the container named my-web in localhost on port 8080
```plain
docker run -it --rm -d -p 8080:80 --name my-web nginx
```{{exec}}