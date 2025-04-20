LRC/SRT/TXT conversion

pip install swapsub

python
import swapsub
sub = swapsub.load("demo.lrc")  
swapsub.convert(sub,"/home/demosrt.srt")
