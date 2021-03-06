# MEASURING TOXICITY IN PRETRAINED LANGUAGE MODELS

<b>INSTRUCTIONS ON HOW TO RUN THE CODE</b>
<p />
Clone the repostitory:
<p>
<code>git clone https://github.com/shariefyoussef/measuring-toxicity
<p>
  Change to the notebooks direcotry where you will find three notebooks
<p>
For each notebook, please do the following steps:
<ol>
<li> replace all the paths to the places that store corresponding data<br>
  Path to data folder: https://drive.google.com/drive/folders/1gwRPVjreE5iGJNAIGQIJaeVj2FW0HpuX?usp=sharing
<li> a Perspective API key is included in the code but you can also <a href="https://support.perspectiveapi.com/s/docs-get-started">apply for one</a> and <a href="https://support.perspectiveapi.com/s/request-quota-increase">make a request to increase the 25 requests/sec limit<a>
<li> run each block in order from the top of the notebook to the bottom
</ol> 
<p>
  <b>ABOUT THE NOTEBOOKS</b>
<P>
Under the notebooks directory, you will find three notebooks:<br />
<ul>
<li>prompted.ipynb includes code that downloads all the data, generates sentences using prompts with three models: GPT-1, GPT-2 and CTRL, and produces toxicity summaries of those generations.
<li>unprompted_generation.ipynb includes code that generates sentences using respective end-of-sentence token of the same three models.
<li>unprompted_results.ipynb includes code that produces the graph of toxicity with respect to number of experiment trials using those generations.
</ul>
<P/>
<p>
  <b>ORDER OF EXECUTION</b>
<p>
The unprompted_generation.ipynb notebook should be run before unprompted_results.ipynb since unprompted_results.ipynb needs the generations generated by unprompted_generation.ipynb. 
<P>
  <b>RUNTIME ENVIRONMENT</b>
<P>
We recommeded that you run the notebooks on a GPU and not a CPU.

