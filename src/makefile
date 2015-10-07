build-dir=../build
theme=green-icon

all: ${theme}

green-icon:
	mkdir ${build-dir};rsync -avC --progress --exclude ${mathjax}.zip lab/* lib/* themes/${theme}/* ${build-dir}
clean:
	rm -rf ${build-dir}
