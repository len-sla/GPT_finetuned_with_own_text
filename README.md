## Project Name
> <p>Finetune a GPT-2 Text-Generating Model with prepared text.<br>
In this particual case text is concatenation of books <br>
from the field of Management, Leadership and good practices in Business.<br>
355M model was used for tuning:<br>
Effects are really good.

![### comparing local and online translator result ](gpt00.JPG)

### General info
There are three released sizes of GPT-2:

* 124M (default): the "small" model, 500MB on disk.
* 355M: the "medium" model, 1.5GB on disk.
* 774M: the "large" model, cannot currently be finetuned with Colaboratory but can be used to generate text from the pretrained model (see later in Notebook)
*  1558M: the "extra large", true model. Will not work if a K80 GPU is attached to the notebook. (like 774M, it cannot be finetuned).
   Larger models have more knowledge, but take longer to finetune and longer to generate text. You can specify which base model to use by changing model_name.

 Other examples with diffrent  prefixes which  are sometimes interesting, crude or surprising:

 <p>-->  You don't need to look behind <br>you to see solutions to problems; you can see them in the mirror.<br>
That helps you recognize the solutions you already have in your mind and moves you to action.</p>
																																																						
<p> --> You don't need to look behind <br> you as you make your way up the ladder to know you are needed. <br>
You can recognize yourself in the crowd.<br>
You can tell when others are glancing at you, or judging you. You can be vulnerable.<br>
And if you’re trying to be strong, you are.</p>

<p> -->  Flexibility is the worst possible approach to leadership.<br> When you are the boss, you should be able to assign people and projects to whomever you want,<br>
when you want, for as long as you want. But you can’t  expect other people to do all the work for you.<br>
Of course, you can bring in people to assist, but that is a small step and not a big enough one. Start slowly and build your trust.</p>




### Technologies
* Python, 
* GPT-2 


### Setup
easiest is to install/update libraries accordnig to install secion in notebook


### Status
Project is: _in progress_ 



### Other information
Notebook is divided on universal fuctions whicht  could be easlily used elsewhere.




### Contact
Created by: _len.sla_

