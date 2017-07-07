# Data Visualization using Tableau - UC Davis
## Essential Design Principles 
### 2.1 Cognitive Load
Amount of mental effort required to interpret the information. Goal of DV - minimize the cognitive load and communicate the message effectively. These are of  three types
1. Intrinsic - amount of brainpower required to understand an idea eg. (2+2 while presenting)
2. Extraneous - relates to how the information is presented. requires extra effort to spot the issues and create a mental image.
3. Germane - how we mentally organize and contextualize information for later reference.

### 2.2 Clutter
* Information to add and discard in DV.

### 2.3 Gestalt Principles
* Proximity - when elements are placed closed enough to be perceived as a group
* Similarity - Naturally connect things that look alike and are grouped. 
* Enclosure - using color or boundaries to highlight or contrast information
* Closure - the completeness of visualization
* Continuity - mind's ability to fill in gaps provided necessary information is present.
* Connection - things that are connected with a line are related.

### 2.4 Pre-attentive attributes
They are a way to get the brain to immediately focus on certain aspects of Viz. Three types of memory
* Iconic - if we want get something into reader's brain without having them to think about it, we need to tap the iconic memory. The sense memory of visual images after the images are gone and before the brain kicks in.
* Short-term - here we deal with the cognitive load. ability to hold info in active memory.
* Long-term: Visualizations that hit iconic and short-term memories. 

Pre attentive attributes to change to focus the user's attention.
* Size
* Color 
* Orientation
* Shape
* Line Composition (width, length)
* Enclosure
* Intensity
* Position
Two general categories to describe data
* Quantitative - bar, line
* Categories - shape

![Visual Attributes for measurer](https://github.com/sumitkant/Data-Visualization-using-Tableau/blob/master/Visual%20Attributes%20for%20measures.PNG)

### 2.5 Aesthetics
1. Color
2. Alignment
3. Leveraging white space

### 2.6 Ascombe's Quartet
summary statistics are not enough to understand the data. your need to visualize it.

### 2.7 Identifying Outliers
* Strip Plot - 1 dimensional circle graph for a variable to examine extra-ordinary values in the data.
* Histogram - Histogram along with bins can show distribution of extraordinary values and their frequency.
* Control Chart - To know how well are we doing based on standard deviations

## MODULE 4
### 4.1 Design for Understanding
Strengths and weakness of different visual encoding elements•
* Color
  * helps pattern stand out (categories)
  * not helpful for showing precision
  * qualitative sense: lighter showing less activity and vice versa
* Line
  * length for qualitative diff
  * thickness for qualitative - relative strength between entities
  
### 4.2 Know your Audience(s)
* What are the needs and goals of your audience? How will the viz meet those needs?
* Audience's familiarity with subject matter. Level of prior knowledge?
* Level of detail and information density that fits TA?
* User control do users have interacting with the viz?
* Use personas to identify your audience aniticipate needs

### 4.3 Design for Purpose
For purely explanatory purposes, interactivity may not be needed, nor any prior knowledge expected. If the purpose is exploratory, you need to provide users with more direct control and interactivity for their analytic process and workflow.
A general framework to think about determining visual context is shown below.

![Design for Purpose](https://github.com/sumitkant/Data-Visualization-using-Tableau/blob/master/DFP.PNG)

#### Progressive Disclosure
Showing data based on context, urgency and criticality.

![Data Relationships](https://github.com/sumitkant/Data-Visualization-using-Tableau/blob/master/data%20relationships.PNG)

### 4.5 Static vs Interactive Viz.
* Ben Shneiderman rules for data visualization - Overview first, zoom and filter and then details on demand.
* Colin Ware's Viz Framework 
 1. Direct Manipulation of Graphical objects
 2. Exploration and navigation
 3. Problem solving and question generation - primary purposes of DV
 
### 4.6 Multiple Connected Views
Coordinated views of DV - contain a mix of different but related visualizations. For Example, bar charts, scatter plots and maps etc.
Pivots are used to view data from different perspectives inclusing some summary statistics.

### 4.7 Language labelling and Scales
Survivor ship bias - During World War II fighters were being shot down at an alarming rate. So they studied the survived fighters to understand where the protection must be added. They increased the armour where there found holes in the aircraft. However the resolution had a drawback since they were looking that survived and not at the planes for whom the damage was catastrophic

Key descriptors in a visualization can either clarify or make picture more confusing instead of just describing what's happenining in the picture.

### 4.8 Visual Lies and Cognitive Bias
Beliefs can distort interpretation. Hence, knowledge of audience is important to select what and how the visualization is portrayed to them
