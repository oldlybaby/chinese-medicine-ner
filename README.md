# chinese-medicine-ner
it's a competiton in Aliyun.

https://tianchi.aliyun.com/competition/entrance/531824/introduction?spm=5176.12281949.1003.3.493e2448h7vzO7 

## model list

- bert
- bert+crf
- bert+lstm+crf  (still working on...)

## requirement

python>=3.7

pytorch=1.6

transformers=3.3.1

## input format

each example contains a .txt and an .ann file, which is required to change to a BIO file . 

## run the code

I'm still organizing the code and adding note to make it easier to use, please wait for a few days :)

## result

 

|  model   | accuracy | precison | recall   | f1       |
| :------: | -------- | -------- | -------- | -------- |
|   bert   | 0.782047 | 0.729291 | 0.952726 | 0.826168 |
| bert+crf | 0.911917 | 0.880348 | 0.939154 | 0.908221 |

