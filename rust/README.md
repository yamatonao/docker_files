#hello world

docker build -t rust-env .
docker run -e USER=$USER -itv /Users/yamatonao/Documents/docker/rust/src:/project rust-env