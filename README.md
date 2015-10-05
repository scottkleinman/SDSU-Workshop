#Text Analysis Workshops

This is a set of instructions created for the October Workshop on [Building and Strengthening Digital Humanities through a Regional Network](http://www.sd-dh.org/) at San Diego State University, Octber 23-24, 2015. I will be leading two sessions on text analysis. The first session will introduce the text analysis workflow and the Lexos text analysis tool. The second will introduce the topic modelling method, a common DH method of exploring texts. We will focus on applications for research and teaching, and one goal will be to imagine assignments based on text analysis methods that can be deployed in a variety of teaching situations.

Further information abotu the two sessions is provided below, along with advance preparations you can do, such as installing software on your own computer. If you have trouble with the installation features, feel free to e-mail me at scott.kleinman@csun.edu, and I will be happy to diagnose as best as I can remotely in advance of the workshop

I look forward to meeting all of you.

Scott Kleinman
California State University, Northridge

*Last Update:* October 4, 2015

##Friday Workshop
The Friday session will introduce the workflow for computational text analysis using [Lexos](http://lexos.wheatoncollege.edu). Lexos is powerful but easy to learn and highlights many of the intellectual issues digital humanists grapple with in applying computational techniques to the study of humanities data.

###Preparation:
Before the workshop you should download the following to your computer.

* Python and Lexos (optional)
* Sample data from the Lexos Test Suite

####Installing Lexos on Your Computer
You do not have to install Lexos; you can access a hosted version at the link above. However, running Lexos on your own computer provides better performance since there is no internet lag.

Lexos uses the Python programming language, which must also be installed on your computer. Complete instructions for installing both are available at [https://github.com/WheatonCS/Lexos/tree/master/0_InstallGuides](https://github.com/WheatonCS/Lexos/tree/master/0_InstallGuides). Just follow the instructions for your operating system.

#####Some notes about Python:
1. The Lexos team recommends that you install the Anaconda distribution of Python as directed in the Lexos install guide. Anaconda is easy to install and comes with most of the Python packages required by Lexos. As an added bonus, these are also the packages typically used by programmers to do text analysis.

2. If you already have Python installed on your system, make sure it is version 2.7. This will work with Lexos, but you may have to install individual packages. You may prefer to install Ananconda anyway; it will work alongside other Python installations.

If you have installed Lexos on your home computer, it will come with the [Lexos Test Suite](https://github.com/scottkleinman/Lexos-TestSuite). If you have not installed Lexos, you can download the necessary files with the following links: 

* [Experiments.zip](https://github.com/scottkleinman/Lexos-TestSuite/blob/master/Experiments.zip?raw=true)
* [malletfile.zip](https://github.com/scottkleinman/Lexos-TestSuite/blob/master/malletfile.zip?raw=true)

Unzip these zip archives to a folder called `NEH-Workshop` (or a similar name).

##Saturday Workshop
The Saturday session will focus on topic modelling for text exploration. We will briefly look at the GUI Topic Modeling Tool, which you can download at [http://topic-modeling-tool.googlecode.com/files/TopicModelingTool.jar](http://topic-modeling-tool.googlecode.com/files/TopicModelingTool.jar). This tool is a nice introduction to topic modelling because it does not require any installation. We will then experiment topic modelling in Mallet, which  provides more options.

###Preparation:
Before the workshop, you should:

* Download the [GUI Topic Modeling Tool](http://topic-modeling-tool.googlecode.com/files/TopicModelingTool.jar)
* Download and install Mallet

The Programming Historian has a good tutorial with instructions for installing Mallet. Just go to [http://programminghistorian.org/lessons/topic-modeling-and-mallet](http://programminghistorian.org/lessons/topic-modeling-and-mallet) and follow the installation instructions for your system. However, the tutorial's download link for Mallet is somewhat out of date. You can get the most recent version by going to https://github.com/mimno/Mallet/archive/master.zip.

You can run Mallet with some of texts from the Lexos Test Suite, but you may wish to bring your own to the workshop.

