# AWS-Map-ReduceHadoop

# Map - Reduce
1. Get, install, try Hadoop.
(downloads: http://www.apache.org/dyn/closer.cgi/hadoop/common/,
more at: http://hadoop.apache.org/)
Or, use a prebuilt image or, use the AWS service
But, you will need to use Hadoop on a cloud service provider (AWS)
2. Interesting data sets have at least 100 thousand tuples up to a few million tuples.
At these web-sites there are schema/meta-data describing the data.
3. Using earthquakes as an example, we would like to know: are magnitude 1 or 2
(or others) increasing, week-by-week? Day-by-day? Is there a relationship between
magnitude and depth? Location and magnitude? Week-by-week?
We want to take large amounts of data and categorize into groups (ranges),
for example magnitude groups (1-2, 2-3, 3-4,…) or latitude groups (20-25, 25-30, …)
using Hadoop.
4. Try with different numbers of mappers and reducers. (1 mapper, 1 reducer (1,1),
then: (2,1), (2,2), (10,1), (10,2)
Run with 1, 2, and 3 instances.
5. “Instrument” (time) running.
