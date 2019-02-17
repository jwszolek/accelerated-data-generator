# accelerated-data-generator
Ultra-fast data generator. It gives you an ability to generate almost 1M of rows in around second. The sample output file has 3 (comma separated) columns. 
 

## Install 


``` 
git clone https://github.com/jwszolek/accelerated-data-generator.git
cd ./accelerated-data-generator
bash speed-generator.sh
```

## Options

``` 
USAGE: speed-generator.sh [numer-of-records] [output-filename]


Options:
  numer-of-records            number of generated records in the text file
  output-filename             output filename
```                        

## Usage

Run: `bash speed-generator.sh 1000 output.csv`

Sample output:
```
$ head -100 output.csv                                                                                                              
acbb6247,59,27531
f735dbda,39,25846
fd2d04a1,af,76981
264a8fe5,c3,104653
98ce4646,10,149364
a58da449,be,38840
f8deb907,7e,76892
ad17301a,ad,201386
1baea434,fe,81919
2597450e,c2,181524
f9ae4360,88,172076
d0e2c101,8f,247282
54424247,c0,155392
32bd6748,99,235523
c8f4ecc6,db,468039
5e88ecbb,96,480350
d0e49014,48,354127
```

