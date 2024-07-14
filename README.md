- 👋 Hi, I’m @koko004

<!---
koko004/koko004 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

# Install Python2.7

Add to /etc/apt/sources.list
`deb http://archive.debian.org/debian/ stretch contrib main non-free`
Then
`apt-get update && apt-get install python2.7 python2.7-dev -y`
Then when all installed remove `deb http://archive.debian.org/debian/ stretch contrib main non-free` from /etc/apt/sources.list

# Install PIP2

`python get-pip.py
curl https://bootstrap.pypa.io/pip/2.7/get-pip.py -o get-pip.py && python get-pip.py`
