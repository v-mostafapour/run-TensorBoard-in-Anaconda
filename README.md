# run-TensorBoard-in-Anaconda
get start with tensorboard in anaconda
 
To run tensorboard:
Start anaconda prompt:
Go to the directory of your graph: by typing  >cd “directory_path”
In this example: (C:\ProgramData\Anaconda3) C:\WINDOWS\system32>) 
“> cd C:\Users\siege\Documents\Jupyter notebook\tutorials\Tensorboard”
Then you are at : (C:\ProgramData\Anaconda3) C:\Users\siege\Documents\Jupyter notebook\tutorials\Tensorboard>_
Type following command to run tensorboard:
>tensorboard –logdir=graph_folder_name  –port=6006   then press inter
In my example: >tensorboard --logdir=_example_tensorboard_graph  --port=6006
By press inter it will show the url like: http://DESKTOP-S8PIH6B:6006 
that is tensorboard url for your graph to open in browser 
NOTE!!: 
1.	don’t use Ctrl+c to copy url ; Ctrl+c will stops running here not copy text …. 
2.	Don’t forget to delete old versions of graphs in your logdir 
3.	Don’t forget to delete old checkpoints, to refresh variables and placholders..
4.	SummaryWriter has changed in TensorFlow 1.0. You can use tf.summary.FileWriter

Good tutorial links to summaries by tensorboard:

Code: https://github.com/MorvanZhou/tutorials/blob/master/tensorflowTUT/tf14_tensorboard/full_code.py

Video: 
1.	https://www.youtube.com/watch?v=FtxpjxFi2vk 

another useful video: https://www.youtube.com/watch?v=YGQqh7mmWb4


Here is my anaconda promp:
(C:\ProgramData\Anaconda3) C:\WINDOWS\system32>cd C:\Users\siege\Documents\Jupyter notebook\tutorials\Tensorboard

(C:\ProgramData\Anaconda3) C:\Users\siege\Documents\Jupyter notebook\tutorials\Tensorboard>tensorboard --logdir=_example_tensorboard_graph --port=6006
TensorBoard 1.7.0 at http://DESKTOP-S8PIH6B:6006 (Press CTRL+C to quit)
