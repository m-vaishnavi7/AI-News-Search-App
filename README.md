# AI Powered News Search App (Level-1)

## Description

The web is home to massive amounts of data, with more being created every day. Organizations can harness this constant stream of information to gain understanding, plan strategies, and find opportunities. Enriched news data can help to make dynamic connections across current events faster.
The AI Powered News Search App is a Node-RED application created on IBM Cloud that acts as a simple user interface that integrates with the IBM Watson Discovery Service and demonstrates the following two use cases using Watson Discovery News:

* **Search**: Query for the most relevant new articles about a specific topic or subject. Because the news collection is pre-enriched with natural language processing, you can query not just on keywords or categories but also on concepts, sentiment, and relations to get richer search responses.

* **Trending topics in the news**: Identify popular topics over the past 24 hours. Topics can be general, or specific to an industry or category.

## Slack Integration

* **Slack Integration**: This app can also be integrated with the slack interface through a bot. Thus, the user can directly query the Watson Discovery News without using the Web application from the Slack app itself.

## Flow

1. The user interacts with the app UI(Built with Node-RED or Cloud or Local) to request relevant news content.
2. The app sends user requests to Watson Discovery News.
3. The Watson Discovery Service is continually crawling the web to update its Discovery News collection.
4. The Watson Discovery Service responds to Slack search requests.

## Sample Output

**The Home page:**

![demo](results/Home_page.png)

<br>

**The trending page:**

![demo](results/trending_topics.png)

<br>

**The query page:**

![demo](results/query_builder.png)

<br>

**Slack integration:**

![slack](results/slack1.png)

<br><br>

![slack](results/slack2.png)



