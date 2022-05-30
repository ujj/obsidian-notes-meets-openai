### Installation

pip install openai

pip install transformers

pip install pandas


### Run

Run the notes_prep.py first with your OpenAI API key and path to your notes folder (or subfolder). 

Depending on your note files this will take a bit. Since the OpenAI API have rate limits, I've severely slowed down the execution with sleeps. 

Feel free to change it as per your choice. 

Make sure you update the output filename.

Once your *embeddings.csv file is ready, you need to run the notes_search.py file with a text value and see what other notes your text connects to.

### Apologies in advance

I was clearly too lazy to make this more useful via command line inputs.

I take it you will do some cool things starting with this. 

Good luck!

Detailed blog post at https://infermuse.com/obsidian-notes-meet-openai/
