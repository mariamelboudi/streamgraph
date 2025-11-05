# EMOJI VISUALIZER

The sweet spot where data visualization connects with graphic design.

As I was exploring graphs, I came across my latest fixation: the streamgraph. This variation of the stacked area chart is a personal favorite. Admittedly, bar charts get to the point, and best practice requires to communicate information in the fastest way possible. But as someone who has a background in photography, I have a soft spot for graphs that require a little more attention.

I would even argue that in the current attention economy, learning how to pull the reader in by offering a slight degree of complexity is probably the most efficient strategy to stand out amidst the online noise, whilst also creating space to intentionally connect with a topic rather than offering only a superficial overview.

This streamgraph was built with Plotly and required a heavy dose of workaround. Recent emojis appeared either as fallbacks (black and white sketches) or tofu (▯) on my computer (2014, ahem...), which lead me to not being able to fully use ax.legend(). I learnt how to manually create my own legends and labels, which resulted in more freedom regarding placement and layout. I personally enjoy the final result as it allows for anybody to make it their own, without being held back by OS configurations.

This graph shows the rolling average of the top 5 emojis my partner and I used in our Whatsapp conversations between September 2024 and September 2025.

Designing incurred adding a taper and a fade window for a smooth fade in/fade out. You can also decide if you want to view the information monthly, weekly or daily, as well as the time frame of the rolling average.

Feel free to download the Juypter Notebook and make it your own.
Stay tuned for the Altair version 🐍

________________________

Draw a customizable streamgraph based on emoji counts. Visualize emoji-use and overall sentiment with a beautiful PLOTLY stream graph.

Use 001_EXTRACT_EMOJIS and 002_SCRIPT to prepare and process your data.

For privacy reasons I did not include the original chat, only the .CSV that I extracted. Feel free to play around with the data !
