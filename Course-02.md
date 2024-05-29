# Course 2 : Ask Questions to Make Data-Driven Decisions

This document covers the notes from the Google Data Analytics course - Course 2

## Module 1

### Type of problems encountered by Data Analyst

#### Making predictions 

A company that wants to know the best advertising method to bring in new customers is an example of a problem requiring analysts to make predictions. Analysts with data on location, type of media, and number of new customers acquired as a result of past ads can't guarantee future results, but they can help predict the best placement of advertising to reach the target audience.

#### Categorizing things 

An example of a problem requiring analysts to categorize things is a company's goal to improve customer satisfaction. Analysts might classify customer service calls based on certain keywords or scores. This could help identify top-performing customer service representatives or help correlate certain actions taken with higher customer satisfaction scores.

#### Spotting something unusual 

A company that sells smart watches that help people monitor their health would be interested in designing their software to spot something unusual. Analysts who have analyzed aggregated health data can help product developers determine the right algorithms to spot and set off alarms when certain data doesn't trend normally.

#### Identifying themes 

User experience (UX) designers might rely on analysts to analyze user interaction data. Similar to problems that require analysts to categorize things, usability improvement projects might require analysts to identify themes to help prioritize the right product features for improvement. Themes are most often used to help researchers explore certain aspects of data. In a user study, user beliefs, practices, and needs are examples of themes. 

> [!NOTE]
> difference between categorizing things and identifying themes - categorizing things involves assigning items to categories; identifying themes takes those categories a step further by grouping them into broader themes.

#### Discovering connections 

A third-party logistics company working with another company to get shipments delivered to customers on time is a problem requiring analysts to discover connections. By analyzing the wait times at shipping hubs, analysts can determine the appropriate schedule changes to increase the number of on-time deliveries. 

#### Finding patterns

Minimizing downtime caused by machine failure is an example of a problem requiring analysts to find patterns in data. For example, by analyzing maintenance data, they might discover that most failures happen if regular maintenance is delayed by more than a 15-day window. 

### SMART Questions

- `Leading Questions`: Questions that lead the conversation or guide the conversation in a specific direction.
- SMART Questions: **S**pecific, **M**easurable, **A**ction-oriented, **R**elevant, and **T**ime-bound.
  - **Specific** questions are simple, significant and focused on a single topic or a few closely related ideas.
  - **Measurable** questions are questions that can be quantified and accessed.
  - **Action-oriented** questions are questions that are designed to lead to action.
  - **Relevant** matter, are important and have significance to the problem you're trying to solve.
  - **Time-bound** questions specify the time period of interest.

### Module 1 Glossary 

- `Action-oriented question`: A question whose answers lead to change
- `Cloud`: A place to keep data online, rather than a computer hard drive
- `Data analysis process`: The six phases of ask, prepare, process, analyze, share, and act whose purpose is to gain insights that drive informed decision-making
- `Data life cycle`: The sequence of stages that data experiences, which include plan, capture, manage, analyze, archive, and destroy
- `Leading question`: A question that steers people toward a certain response
- `Measurable question`: A question whose answers can be quantified and assessed
- `Problem types`: The various problems that data analysts encounter, including categorizing things, discovering connections, finding patterns, identifying themes, making predictions, and spotting something unusual
- `Relevant question`: A question that has significance to the problem to be solved
- `SMART methodology`: A tool for determining a question’s effectiveness based on whether it is specific, measurable, action-oriented, relevant, and time-bound 
- `Specific question`: A question that is simple, significant, and focused on a single topic or a few closely related ideas
- `Structured thinking`: The process of recognizing the current problem or situation, organizing available information, revealing gaps and opportunities, and identifying options 
- `Time-bound question`: A question that specifies a time-frame to be studied
- `Unfair question`: A question that makes assumptions or is difficult to answer honestly 

## Module 2

### Data-driven decisions
- Data-driven decision-making means using facts to guide business strategy.
- The phrase “data-driven decisions” means exactly that: Data is used to arrive at a decision.
- This approach is limited by the quantity and quality of readily-available data.
  - If the quality and quantity of the data is sufficient, this approach can far improve decision-making.
  - But if the data is insufficient or biased, this can create problems for decision-makers.
- Potential dangers of relying entirely on data-driven decision-making can include - 
  - over reliance on historical data
  - tendency to ignore qualitative insights
  - potential biases in data collection and analysis

**Example of a data-driven decision**
A/B testing is a simple example of collecting data for data-driven decision-making. For example, a website that sells widgets has an idea for a new website layout they think will result in more people buying widgets. For two weeks, half of their website visitors are directed to the old site; the other half are directed to the new site. After those two weeks, the analyst gathers the data about their website visitors and the number of widgets sold for analysis. This helps the analyst understand which website layout resulted in more widget sales. If the new website performed better in producing widget sales, then the company can confidently make the decision to use the new layout!

### Data-inspired decisions
- Data-inspired decisions include the same considerations as data-driven decisions while adding another layer of complexity.
- They create space for people using data to consider a broader range of ideas: drawing on comparisons to related concepts, giving weight to feelings and experiences, and considering other qualities that may be more difficult to measure.
- Data-inspired decision-making can avoid some of the pitfalls that data-driven decisions might be prone to. 

**Example of a data-inspired decision**
A customer support center gathers customer satisfaction data (often known as a “CSAT” score). They use a simple 1–10 score along with a qualitative description in which the customer describes their experience. The customer support center manager wants to improve customer experience, so they set a goal to improve the CSAT score. They start by analyzing the CSAT scores and reading each of the descriptions from the customers. Additionally, they interview the people working in the customer support center. From there, the manager formulates a strategy and decides what needs to improve the most in order to raise customer satisfaction scores. While the manager certainly relies on the CSAT data in the decision-making process, input of support center representatives and other qualitative information informs the approach as well.

### Qualitative and Quantitative data

![alt text](./images/course-2-module-2.png)

- `Quantitative data` is all about the specific and objective measures of numerical facts.
  - This can often be the what, how many, and how often about a problem.
  - In other words, things you can measure, like how many commuters take the train to work every week.
- `Qualitative data` describes subjective or explanatory measures of qualities and characteristics or things that can't be measured with numerical data.
  - Qualitative data is great for helping us answer why questions.
  - For example, why people might like a certain celebrity or snack food more than others.
  - With quantitative data, we can see numbers visualized as charts or graphs.
  - Qualitative data can then give us a more high-level understanding of why the numbers are the way they are. This is important because it helps us add context to a problem.

### Sharing data - Reports and Dashboards

#### Reports

- A report is a static collection of data given to stakeholders periodically.
- **Pros**
  - Reports are great for giving snapshots of high level historical data for an organization.
  - They can be designed and sent out periodically, often on a weekly or monthly basis, as organized and easy to reference information.
  - They're quick to design and easy to use as long as you continually maintain them.
  - Finally, because reports use static data or data that doesn't change once it's been recorded, they reflect data that's already been cleaned and sorted.
- **Cons**
  - Reports need regular maintenance and aren't very visually appealing.
  - Reports don't show live, evolving data.

#### Dashboards

- A dashboard monitors live, incoming data.
- **Pros**
  - Dashboards are great for a lot of reasons, they give your team more access to information being recorded, you can interact through data by playing with filters, and because they're dynamic, they have long-term value.
  - If stakeholders need to continually access information, a dashboard can be more efficient than having to pull reports over and over, which is a big time saver for you.
  - They're just nice to look at.
  - Easy access for stakeholders
  - Ability to monitor live data
  - Low maintenance
- **Cons**
  - They take a lot of time to design and can actually be less efficient than reports, if they're not used very often.
  - If the base table breaks at any point, they need a lot of maintenance to get back up and running again.
  - Dashboards can sometimes overwhelm people with information too.

##### Dashboard benefits
The following table summarizes the benefits of using a dashboard for both data analysts and their stakeholders.

| Benefits | For data analysts | For stakeholders |
| --- | --- | --- |
| Centralization | Share a single source of data with all stakeholders | Work with a comprehensive view of data, initiatives, objectives, projects, processes, and more |
| Visualization | Show and update live, incoming data in real time* | Spot changing trends and patterns more quickly |
| Insightfulness | Pull relevant information from different datasets | Understand the story behind the numbers to keep track of goals and make data-driven decisions |
| Customization | Create custom views dedicated to a specific person, project, or presentation of the data  Drill down to more specific areas of specialized interest or concern |

##### Create a dashboard
Here’s a process you can follow to create a dashboard, whether in Tableau or another visualization tool:

1. Identify the stakeholders who need to see the data and how they will use it
2. Design the dashboard (what should be displayed)
  1. Use a clear header to label the information.
  2. Add short text descriptions to each visualization.
  3. Show the most important information at the top.
3. Create mockups if desired
4. Select the visualizations

##### Types of dashboards

The three most common categories are:

###### Strategic

- Focuses on long term goals and strategies at the highest level of metrics
- They typically contain information that is useful for enterprise-wide decision-making.

###### Operational

- short-term performance tracking and intermediate goals.
- contain information on a time scale of days, weeks, or months.
- they can provide performance insight almost in real-time. 
- This allows businesses to track and maintain their immediate operational processes in light of their strategic goals.

###### Analytical

- consists of the datasets and the mathematics used in these sets
- contain a vast amount of data used by data analysts.
- contain the details involved in the usage, analysis, and predictions made by data scientists.


### Data v/a Metrics

- `Data` is a collection of facts.
- `Metrics` are a single, quantifiable type of data that can be used for measurement.
  - Metrics can also be combined into formulas that you can plug your numerical data into.
  - Data contains a lot of raw details about the problem we're exploring.
  - But the right metrics provide the answers we're looking for.

> [!NOTE]
> The metric goal is a measurable goal set by a company and evaluated using metrics.

### Big and Small Data

- `Small data` can be really small.
  - These kinds of data tend to be made up of datasets concerned with specific metrics over a short, well defined period of time.
  - Small data can be useful for making day-to-day decisions, like deciding to drink more water.
    - But it doesn't have a huge impact on bigger frameworks like business operations. 
- `Big data` has larger, less specific datasets covering a longer period of time.
  - They usually have to be broken down to be analyzed.
  - Big data is useful for looking at large-scale questions and problems, and they help companies make big decisions.

> [!NOTE]
> 4 V words for big data while considering the benefits and challenges of data - 
> | V           | Description                             |
> | ----        | ----                                    |
> | `Volume`    | he amount of data                       |
> | `Variety`   | The different kinds of data             |
> | `Velocity`  | How fast the data can be processed      |
> | `Veracity`  | The quality and reliability of the data |

### Module 2 Glossary

- `Algorithm`: A process or set of rules followed for a specific task
- `Big data`: Large, complex datasets typically involving long periods of time, which enable data analysts to address far-reaching business problems
- `Dashboard`: A tool that monitors live, incoming data
- `Data-inspired decision-making`: The process of exploring different data sources to find out what they have in common
- `Metric`: A single, quantifiable type of data that is used for measurement
- `Metric goal`: A measurable goal set by a company and evaluated using metrics
- `Pivot chart`: A chart created from the fields in a pivot table
- `Pivot table`: A data summarization tool used to sort, reorganize, group, count, total, or average data
- `Problem types`: The various problems that data analysts encounter, including categorizing things, discovering connections, finding patterns, identifying themes, making predictions, and spotting something unusual
- `Qualitative data`: A subjective and explanatory measure of a quality or characteristic
- `Quantitative data`: A specific and objective measure, such as a number, quantity, or range
- `Report`: A static collection of data periodically given to stakeholders
- `Return on investment (ROI)`: A formula that uses the metrics of investment and profit to evaluate the success of an investment
- `Revenue`: The total amount of income generated by the sale of goods or services
- `Small data`: Small, specific data points typically involving a short period of time, which are useful for making day-to-day decisions

