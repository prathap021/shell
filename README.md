# shell
echo "how many pages"
read x;
for (( c=1; c<=x; c++ ))
do 
  tiff2pdf -j -o $c.PDF  $c.tif
  

done
