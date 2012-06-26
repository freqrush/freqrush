freqrush
========

My sandbox repository to try out things.

Edited on laptop now :-)

I have map in my ~/ named Gittest.

[peter@armada Gittest]$ git clone https://github.com/freqrush/freqrush
Cloning into 'freqrush'...
remote: Counting objects: 51, done.
remote: Compressing objects: 100% (48/48), done.
remote: Total 51 (delta 3), reused 0 (delta 0)
Unpacking objects: 100% (51/51), done.
[peter@armada Gittest]$ 

This created a map freqrush/ and a map freqrush/.git/
in the current working directory.

Then I cd into freqrush/ and edit README.md, this file you're reading 
here.

To tell git that this file should be updated, I can do
[peter@armada freqrush]$ git add README.md
and
[peter@armada freqrush]$ git commit

or replace the above commands with 
[peter@armada freqrush]$ git commit -a

(I hope it's right)

 
[peter@armada freqrush]$ git add README.md 
[peter@armada freqrush]$ git commit -m 'more editing of the 
README.md 
file'
[master af4202f] more editing of the README.md file
 1 file changed, 27 insertions(+)
[peter@armada freqrush]$ git push origin master
Counting objects: 5, done.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 692 bytes, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/freqrush/freqrush
   a51cbb6..af4202f  master -> master
[peter@armada freqrush]$ 

