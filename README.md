#  Brewing Insights: Coffee Customer and Offer Performance Analysis

## Project overview 

🌐 The data is scourced from Maven Analytics: https://mavenanalytics.io/challenges/maven-rewards-challenge/404c6060-60eb-400f-9bce-c3b9f97e9d5a

📊 The dataset consists of three CSV files: **Customers**, **Offers**, and **Events**.


## Questions 

This report is structured into three pages: the first page focuses on Events & Offer Performance, the second page explores Customer Behavior, and the third page analyzes Transactions.

### Page 1: Events & Offer Performance


![image](https://github.com/user-attachments/assets/77787683-a2af-4153-a370-efda72192595)


This page explores the performance of different offer types and their impact on customer engagement, focusing on the view and completion rates across two segments (Age & Income). The key questions answered are:

**1. Which offer type has the most views?**

There are 3 offer types: Bogo, Discount, and Informational.

Goal: To find the offer type that has the highest view rates.

Answer: **BOGO offers have the highest view rate at 81.3%**, meaning that 81.3% of BOGO offers received were viewed. However, **in terms of total views, BOGO accounts for 37.3% of all views.**

- Informational offers have a view rate of 70.4% and contribute to 31.61% of total views.
- Discount offers have a view rate of 69.2% and account for 31.69% of total views.

**This indicates that while BOGO offers are more likely to be viewed once received, the overall engagement across different offer types is relatively balanced, with Discount and Informational offers collectively making up over 63% of total views.**


**2. Do views translate into completions?**

Goal: To analyze offers that were completed, comparing the completion rates between BOGO and Discount offers. Additionally, this analysis explores **whether the offer with the higher completion rate** also has **the highest view rate**. 

Answer: 

- Completion Rate Comparison:

The completion rate for **Discount offers (64.5%) is higher than for BOGO offers (57%)**.

- Correlation Between View and Completion Rates:
  
There seems to be an **inverse relationship between view and completion rates.** **BOGO** offers get **more views but have a lower completion rate**, while **Discount offers have fewer views** but **a higher completion rate**. This indicates that views and completions are not strongly correlated in this case.

This highlights an interesting disconnect. While **BOGO offers are good at capturing attention**, **Discount offers appear to be more effective at motivating customers to follow through and complete the offer**. It could suggest that the perceived value of the Discount offer is more compelling, despite having fewer views.

***
##### Interaction Insight: Comparison of View and Completion Rates.

BOGO offers excel in attracting attention and views but Discount offers are more successful in driving completions. 
***


**3. How does VIEW rate vary by segements (Income & Age)?**

Goal: To explore how these two different segments respond to offers in terms of viewing rates.

Answer: 

 •	**By Income:**
 
- **Upper-Middle and Middle income levels** tend to have the highest view rates (77.7% and 79.9%), while High income ranks last with 62.2%.

•	**By Age:**

- **Middle-aged customers (Mid Career and Late Career)** have the highest view rates (78.0% and 75.5%).



***
##### Interaction Insight:  How does VIEW rate vary by segements (Income & Age)?

The alignment between higher view rates in **middle-income and middle-aged segments** suggests that life stage might drive greater interest and responsiveness to offers.

While middle-income customers have the highest view rates, higher-income customers show less engagement (62.2%), indicating that greater purchasing power does not necessarily translate to higher interest in offers. This suggests that life stage rather than income may be a stronger factor influencing customer engagement patterns.
***


**4. How does COMPLETION rate vary by segements (Income & Age)?**

Goal: To analyze the completion rates and understand the segment's engagement.

•	**By Income:**

- Completion rates increase with income level, peaking at 77.6% for high-income customers. This suggests that higher-income customers are more likely to follow through on offers, possibly due to greater purchasing power.

•	**By Age:**

- The age group with the highest completion rates is Retirement Age (64.8%), followed closely by Late Career (64.7%). This may reflect that retirement-age customers have more free time and established consumption habits, which could drive higher completion rates. Additionally, their higher completion rates may reflect increased brand loyalty or a greater focus on value, even if they are not necessarily high-income.

***

##### Interaction Insight:  How does COMPLETION rate vary by segements (Income & Age)?

The **highest completion** rates are seen in **high-income customers** (77.6%), indicating that greater purchasing power may increase the likelihood of following through on offers once engaged. **This suggests that while higher-income customers may show lower initial interest (in terms of viewing), they are more decisive when they do engage.**

In terms of age, the highest completion rates are observed among retirement-age customers (64.8%), followed closely by late-career customers (64.7%). This may reflect greater brand loyalty, established habits, or a preference for value among older customers.

***


***

##### Overall Segment Insight (View vs. Completion):

**Middle-income and middle-aged** customers have the **highest view rates**, suggesting that life stage and financial stability drive initial engagement with offers.

**High-income and retirement-age** customers, however, **have the highest completion rates**, suggesting that while they may engage less frequently, they are more likely to convert when they do engage.

**This indicates that life stage influences initial interest (viewing), but financial power and loyalty are stronger drivers of conversion (completion).**
***






### Page 2: Customer Behavior


![image](https://github.com/user-attachments/assets/af0e916f-62de-4d27-a13e-b58649080b56)

This page focuses on customer behavior, analyzing patterns such as how customers interact with offers, the completion times, and which channels drive higher completion rates. The questions answered include:

**1. How is the distribution of completion times different across Age and Income level segements?** 

Goal: To analyze how completion times vary across Age and Income level segements. 

Answer:

•	**By Age:**

- The median completion times increase slightly with age, suggesting that **older individuals tend to take longer to complete offers.**
- The **IQR is wider during the Early Career**, indicating **greater variability** in completion times for people in this group. This suggests that younger adults in the early stages of their careers might have more unpredictable behavior when engaging with offers — possibly due to varying levels of financial stability, decision-making confidence, or external distractions.
- The range of completion times (whiskers) remains relatively consistent across age groups, but the variability narrows slightly in the Late Career and Retirement Age groups.

•	**By Income:**

- The median completion times are fairly consistent across income groups, except for the high-income group, which has a noticeably lower median (around 237 hours vs. 320 hours for others).
- This suggests that **higher-income individuals tend to complete tasks faster compared to other groups.**
- The interquartile range (IQR) and whiskers are similar across all income levels, indicating that the overall variability in completion times is consistent regardless of income.

**2. Do customers complete offers without viewing them? - By Age group & Income level.**

Goal: To determine if it is possible to complete an order without having seen the offer first. If customers **complete offers without viewing them**, it suggests they were influenced by factors other than direct engagement, **such as prior experience, brand awareness, or social influence.**

**3. Which offer types are completed without being viewed?**

Goal: To provide a high-level view of how BOGO and Discount offer types perform in terms of completion, even when not viewed.

**4. Which channel drives the highest completion rate? By Age group & Income level.**

Goal: To analyze which channels are most effective in driving completions across different age and income groups.

**5. How does completion rate vary with difficulty? - Sized by Reward**

Goal: To investigate how the difficulty of an offer, when sized by the reward, affects its completion rate.

**6. How does YoY growth in new customers vary by segment?**

Goal: To analyze the year-over-year (YoY) growth of new customers and its variation across different customer segments.


### Page 3: Transactions


![image](https://github.com/user-attachments/assets/efb5b192-1af0-421f-b574-99aa85a267bb)



The final page focuses on analyzing transactions across different years, segments, and channels. However, the dataset has limitations related to the lack of transaction data for specific offer types, such as BOGO and Discount. Despite this, the following questions were addressed:

**1. Transactions Trending across the years**

Goal: To analyze the trends in transactions over the years, Quarters, Months, Week number.


**2. Does Sending More Offers Drive Higher Transactions?**

Goal: To investigate the relationship between the number of offers sent and the resulting transaction volume.

**3. Which segment drives the Transactions?**

Goal: To analyzing which customer segment are driving the highest number of transactions.


## Tools Used 

Python, Power BI


## Data Credibility

**1. Reliable:**  The dataset shows **signs of inaccuracies** and **incompleteness**, with potential bias issues that cannot be fully assessed.

The **age** distribution of customers ranges from **18 to 118**. Notably, **all rows with an age of 118 have null values in the 'gender' and 'income' columns**. Additionally, there are 253 rows corresponding to customers aged 90-101, with 17 of them between 100-101. Unlike the 118-year-old entries, **the 90-101 age group has no missing values in other columns**, suggesting they may not be typos. However, **it is worth noting that customers over 100 purchasing coffee might be unrealistic and could indicate potential data quality concerns.** I removed only the rows where the age was 118.

The dataset **lacks transaction amount data for BOGO (Buy One Get One) and Discount offer types**, which limits the ability to assess the financial success of these offers. As a result:

- **Inability to Measure Offer Success Based on Revenue:** The lack of transaction data means we cannot evaluate the success of these offers in terms of revenue generation. Only offer engagement metrics are available.

- **Limited Insights into Channel Performance:** Since transactional data is missing, we cannot fully assess which channels are most successful in driving revenue.

- **Focus on Engagement Rather than Financial Impact:** Any performance analysis must focus on engagement metrics such as offer views, completions, and redemption rates, rather than financial success.

**2. Original:** The data was downloaded from Maven Analytics but was originally sourced from Kaggle, via Udacity.

**3. Comprehensive:** Contains all essential information needed to answer key questions.

**4. Current:** Not up to date — there is no information regarding the date of data collection. However, this dataset contains fictional data, which was intended to represent data collected in the 30 days prior to the start of the analysis.

**5. Cited:** The data is not cited, but it is in the public domain.


## Data Cleaning 


### Table: Customers 

This table serves as a Dimension table. 

Number of Rows: 17.000

Number of Columns: 5

**Missing values** were found in the 'Gender' and 'Income' columns, corresponding to entries where the 'Age' is 118.

**Cleaning:**

- **Became Member on:** This column is populated with dates but is stored as an **integer** in the format of YYYY-MM-DD. I transformed it before converting it to a  YYYY-MM-DD **date** format. 

```ruby
#date(
    Number.IntegerDivide([became_member_on], 10000), // Extract year
    Number.IntegerDivide(Number.Mod([became_member_on], 10000), 100), // Extract month
    Number.Mod([became_member_on], 100) // Extract day
)
```


-**Age:**  2.175 rows with an age of 118 were removed. Filtering out these rows also eliminated all null entries in the 'Gender' and 'Income' columns. 

![image](https://github.com/user-attachments/assets/1fb84450-eb25-4396-81b4-7aecfbe7a250)


![image](https://github.com/user-attachments/assets/f8dcb289-e119-4ef5-850b-8a663c4b3bce)


### Table: Offers

This table serves as a Dimension table. **It needed no cleaning.**

Number of Rows: 10

Number of Columns: 6

No missing values or inconsistencies. 

**Duplicates:**  The 'offer_type' column contains duplicate values, which is expected since multiple offers can belong to the same type. However, each offer has a unique 'offer_id'.

**Channels Column:** The values in the 'channels' column are stored as lists, as some offers are available across multiple platforms.

To improve the analysis of offer performance across different marketing channels, I created **a new Channels table**. The original channels column in the offers_dim table stored multiple channels as a list (e.g., ['email', 'mobile', 'social']), which made it difficult to analyze individual channel performance.

To resolve this, I unpivoted the channels column, splitting the list into separate rows, creating a clean table with two columns: offer_id and Channel. I then established a relationship between the new Channels table and the offers_dim table using offer_id.


### Table: Events_fact

This table serves as the fact table because it contains transactional data (not for BOGO & Discount). Each row represents an event, such as an offer being received, viewed, or completed.

Number of Rows: 306534

Number of Columns: 5

No missing values or inconsistencies.

**Cleaning:**

- **Event column:** To optimize performance and ensure consistency, the event column was transformed into a separate dimension table (event_type). This reduces storage space, improves query efficiency, and replaces repetitive text with an integer key for better performance. As a result, the 'event' column was replaced with event_id.


![image](https://github.com/user-attachments/assets/9f4e2bc5-6ffb-4bf1-b378-05c8f64d6d75)


![image](https://github.com/user-attachments/assets/350c14a2-d35d-4880-9e3d-13472de63219)


- **Value:** Contains  inconsistent data formats in the form of nested JSON-like data, e.g., {'offer id': '9b98b8c7a33c4b65b9aebfe6a799e6d9'}, {'amount': 0.05}, {'amount': 0.30000000000000004}. Further investigation revealed that this column **is context-dependent**, meaning its contents vary based on the event type.


1. Offer-related events (offer received, offer viewed, offer completed) → Contained an offer ID.
2. Transactions (transaction) → Contained only the transaction amount.
3. Completed offers (offer completed) → Included both an offer ID and a reward amount.

![image](https://github.com/user-attachments/assets/651c36e0-4008-4d09-a241-3ddf858bb9fb)

![image](https://github.com/user-attachments/assets/e6c2d8b5-ebb4-4375-9989-dae6fa2202c2)

![image](https://github.com/user-attachments/assets/242b8d10-0b8a-4367-a802-2c8a78b89772)



In addition:

There is a small inconsistency in the **key naming**:

1. "offer completed" has ['offer_id'] with underscore

![image](https://github.com/user-attachments/assets/677a381b-c9cf-419c-89b5-0ab3b415e130)


2. "offer received" and "offer viewed" have ['offer id'] with space

![image](https://github.com/user-attachments/assets/d7a51b95-5045-422a-8448-a669aa7c6b05)


![image](https://github.com/user-attachments/assets/dccaa300-f9c1-4ab1-950a-d822242bc70b)


4. "transaction" contains only ['amount']

![image](https://github.com/user-attachments/assets/36cdf935-0ad3-417e-b131-025e3fa487d2)

**And all together from Python (pandas)**

![image](https://github.com/user-attachments/assets/5be8957c-d3f9-4dc0-989b-a640cb8d9545)



I used Python to parse and extract structured data from the 'value' column. Using ast.literal_eval(), I converted string representations of dictionaries into actual dictionaries and extracted the relevant fields. The extracted values were then assigned to three new columns: 'transaction_amount', 'offer_id', and 'reward'. Python was chosen for its efficiency in handling complex data structures and automating the transformation process.


![image](https://github.com/user-attachments/assets/802b20c5-e56e-4d74-b76b-b40b993ef2f7)


After extracting the new columns, NULL values appear in certain rows because the corresponding event category does not require those values. For example, if the event is "received order," the reward column will be NULL since rewards are only applicable to "completed orders." Similarly, transaction amounts will be NULL when related to offer_id and reward. 

![image](https://github.com/user-attachments/assets/6eaef01d-ad9c-4f24-a024-a2141c9c9a88)

![image](https://github.com/user-attachments/assets/083a046c-f7b9-46d5-9f06-ce5a614521b8)


**Nulls & Blanks**

**1. Transaction_amount:** Nulls were replaced with 0, as NULL transaction_amount **means no transaction happened**, so replacing it with 0 is fine.

**2. Reward:** A NULL reward **doesn't mean the customer received 0 rewards** —it simply indicates that the row isn't eligible for rewards, such as in "offer received" or "offer viewed" events. To avoid confusion, I left it as NULL, even though it's not the best practice. However, given the context, this approach makes the most sense here.


**3. Offer_id**: Blanks were replaced with 'No offer' as this clearly indicates that the event (like a transaction) is not linked to an offer.


**Mismatched Customers in events_fact and customers_dim:** Initially, both the events_fact and customers_dim tables had 17,000 unique customers. However, after removing customers aged 118 from customers_dim, this left behind rows in the events_fact table, causing a mismatch. These customers, with age 118, are not valid and cannot be considered reliable. 

To address this, I first created a calculated column to mark valid customers, and then applied a page-level filter in Power BI to remove blanks caused by the mismatch, ensuring accurate data representation.


```ruby
Valid Customer (no 118 Age) = 
IF(
    events_fact[customer_id] IN DISTINCT(customers_dim[customer_id]), 
    "Valid", 
    "Inavlid Age"
)
```


### Table: Dates 

To improve performance and enable efficient time-based analysis, a separate Dates Table was created. This allows for better date hierarchies, optimized relationships, and enhanced filtering across the dataset.

```ruby
let
    // Get the minimum and maximum date from customers_dim
    MinDate = List.Min(customers_dim[Date]),
    MaxDate = List.Max(customers_dim[Date]),

    // Generate a list of dates from MinDate to MaxDate
    DateList = List.Dates(MinDate, Number.From(MaxDate - MinDate) + 1, #duration(1,0,0,0)),

    // Convert list to a table
    DateTable = Table.FromList(DateList, Splitter.SplitByNothing(), {"Date"}),

    // Change type to Date
    ChangedType = Table.TransformColumnTypes(DateTable, {{"Date", type date}}),

    // Add necessary columns
    AddYear = Table.AddColumn(ChangedType, "Year", each Date.Year([Date]), Int64.Type),
    AddMonth = Table.AddColumn(AddYear, "Month", each Date.Month([Date]), Int64.Type),
    AddMonthName = Table.AddColumn(AddMonth, "Month Name", each Date.ToText([Date], "MMM"), type text),
    AddWeek = Table.AddColumn(AddMonthName, "Week Number", each Date.WeekOfYear([Date]), Int64.Type),
    AddDayName = Table.AddColumn(AddWeek, "Day Name", each Date.ToText([Date], "ddd"), type text),
    AddQuarter = Table.AddColumn(AddDayName, "Quarter", each "Q" & Number.ToText(Date.QuarterOfYear([Date])), type text),
    #"Filtered Rows" = Table.SelectRows(AddQuarter, each true)
in
    #"Filtered Rows"
```

## Modeling 

![image](https://github.com/user-attachments/assets/065aca55-86e1-4ad1-a250-79c7c74f9a3d)



The column 'time' in the Fact table represents the number of hours elapsed since the start of the 30-day period, essentially acting as a timestamp for each event. 


## Data Analysis 

I grouped customers based on age and income to analyze patterns more effectively. The age groups were defined within the range 18 to 101, while the income groups were categorized between $30,000 and $120,000. This segmentation allows for better insights into customer behavior, offer engagement, and spending habits across different demographics.

Age Groups:
- 18-25 (Young Adults)
- 26-35 (Early Career)
- 36-50 (Mid-Career)
- 51-65 (Late Career)
- 66+ (Retirement Age)

Income Groups:
- 30K-50K (Low Income)
- 50K-75K (Middle Income)
- 75K-100K (Upper Middle Income)
- 100K-120K (High Income)




