# Simpsons Analysis
[Data Source](https://www.kaggle.com/datasets/jonbown/simpsons-episodes-2016?resource=download)

# Potential Questions
Some questions I've considered with preliminary knowledge of Simpsons episodes and early observation of colums / variables.

- Anything interesting about 100th ep?
- Who killed Mr. Burns episode (Televised as big event for viewer interaction/prize (?))
- Pre vs Post-Movie patterns
- Holiday specials patterns? (Treehouse of Horror (Halloween), Christmas, etc.)
    - Usually parodies cultural trends i.e. Marvel movies (if Avengers released, will following special have higher view / ratings?)
    - External research required
- Difference b/w descriptions (Homer-centric episode vs Bart, etc.)
- Patterns in ratings / view count
- Certain other cultural shifts 
  - e.g. rise of streaming how affected cable viewership
- Director vs Writers etc
- Controvery of Apu voice actor, death of Ms. Krabappel, etc.


# References / Resources
- [grid.arrange()](https://stackoverflow.com/questions/10706753/how-do-i-arrange-a-variable-list-of-plots-using-grid-arrange)
- [RMD Output](https://stackoverflow.com/questions/37755037/how-to-add-code-folding-to-output-chunks-in-rmarkdown-html-documents)
- [plotly](https://plotly.com/ggplot2/text-and-annotations/)
- [plotly vs plot_ly](https://jtr13.github.io/spring19/community_contribution_group17.html) (Feb 17)
- [plot_ly pie chart](https://plotly.com/r/pie-charts/)

# Future To Dos
- Change seasonal graphs to plotlys to better inspect values
- Change grid arrange (i.e. 4 per window as opposed to 12)


Feb 16
- Minor typos and mild refactoring
- Seasonal gridarrange graphs with special highlighting, legends updated
- [Jitter graph](https://cmdlinetips.com/2018/04/how-to-make-boxplot-in-r-with-ggplot2/)
- TO-DO/WIP:
  - Adjust seasonal graphs to more readible, and change to rating
  - Parse through writers and conduct EDA
    - Find RegEx / stringr functions to use

Feb 17
- Finished regex for writers, attempting to plot
- Minor graphs