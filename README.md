# 🚀 VendBridge User Adoption & Engagement Analysis  
## Tableau Dashboard for Product Growth, Engagement, and App Performance

Focused on product adoption and user engagement, this analysis tracks installs, sign-ups, active usage, transactions, crashes, uninstalls, and churn to evaluate how well **VendBridge** is performing in the market. The goal was to understand whether early growth is translating into meaningful user activity and retention, while also identifying areas where product performance could be improved.

Built around an interactive **Tableau dashboard**, the analysis highlights key growth trends, engagement patterns, and performance gaps across regions and devices. The findings support smarter decisions around onboarding, retention, app stability, and regional expansion.

🧰 **Tools Used:** Google Sheets, Tableau  

🗂️ **Dataset:** VendBridge Product Analytics Data (3 months)


## 🎯 Project Goal

The goal of this analysis was to monitor how VendBridge has performed since launch by focusing on three key areas:

- user acquisition and adoption
- user engagement and transaction activity
- app performance and retention health

The dashboard was designed to help the product team understand whether growth efforts are working, how users are interacting with the app, and what issues may be limiting long-term success. 


## 🌍 Business Context

VendBridge is a digital marketplace launched to connect buyers and sellers in a seamless and trustworthy online environment. Since the app is still in its early growth stage, the product team needs a clear way to evaluate adoption, engagement, and platform health in order to guide future product and marketing decisions.

With major investments already made in pre-launch and post-launch campaigns, it became important to measure whether the app is gaining traction, converting users effectively, retaining them, and providing a stable enough experience to support continued growth.


## 🧾 About the Dataset

The dataset covers product performance over a three-month period and includes key metrics such as:

- Date
- Total App Installs
- User Sign-Ups
- Daily Active Users
- Number of Transactions
- Uninstalls
- Number of App Crashes
- Average Time Spent per User
- Region
- Device

These fields made it possible to assess VendBridge across the full product funnel — from acquisition to engagement to retention and performance.


## 🛠️ Workflow

### 1. Data Preparation

The process began with extracting the relevant data from Google Sheets and preparing it for dashboard analysis in Tableau. The structure was organized to make metric grouping and KPI creation easier, especially for comparing current-month performance against the previous month.

This helped me create a cleaner analytical flow and ensured the dashboard could support dynamic month-based KPI tracking.


### 2. KPI Structuring

To make the dashboard more useful for decision-making, the analysis was built around **month-over-month comparisons**. Instead of showing only current totals, the dashboard compares current-month values to the previous month so that performance changes can be seen immediately.

The main KPI groups tracked were:

- installs
- sign-ups
- signup rate
- daily active users
- transactions
- average time spent per user
- uninstalls
- churn rate
- app crashes

This made it easier to distinguish between growth, engagement strength, and product health.



### 3. Dashboard Development

Two main dashboard pages were developed:

#### 🪄 Overview Dashboard
This page focuses on **user acquisition and app health**, showing:

- total app installs
- total user sign-ups
- signup rate
- average daily app crashes
- average daily uninstalls
- churn rate
- installs over time

#### 🔥 Engagement Dashboard
This page focuses on **user interaction and usage behavior**, showing:

- average daily active users
- total transactions
- average time spent per user
- transaction volume over time
- transaction volume by device
- transaction volume by region

The dashboard also includes interactive filters for month, region, device, and engagement measure, making it easier to drill into specific performance segments.

## 🖼️ Dashboard Preview

### Overview Dashboard
![VendBridge Overview Dashboard] (./overview.png                                    )

### Engagement Dashboard
![VendBridge Engagement Dashboard](./engagement.png)

## 📈 Key Findings

### 🌱 1. Adoption is growing, but conversion is weakening
VendBridge recorded strong growth in app installs and user sign-ups, which shows that awareness and market reach are improving. However, the signup rate declined compared to the previous month, which means a smaller share of installers are becoming registered users.

This suggests that acquisition campaigns are driving traffic, but the onboarding or signup journey may be creating friction.

### 💬 2. Engagement among active users is improving
Daily active users, transaction volume, and average time spent per user all increased month over month. This indicates that users who stay on the platform are becoming more engaged and are interacting with the app more frequently.

Rather than being a passive user base, the active audience appears to be showing stronger usage behavior.

### 🧨 3. App crashes are rising too quickly
One of the biggest red flags in the dashboard is the sharp increase in average daily app crashes. While adoption and engagement are improving, a rise in crashes creates a serious product risk.

If this trend continues, it could damage user trust, interrupt transactions, and eventually affect retention.

### 🪫 4. Retention health is improving
Despite the rise in crashes, average daily uninstalls declined and churn rate also improved. This suggests that user retention is currently holding up well, even as some product performance issues begin to emerge.

At this stage, VendBridge still appears capable of holding onto users once they are acquired.

### 📲 5. Android is the stronger transaction channel
Transaction activity is higher on Android than on iOS, which shows that Android users are contributing more to marketplace activity. This could be due to a larger Android user base, stronger engagement on Android, or better market fit on that device type.

This makes Android an especially important channel for both optimization and growth.

### 🌐 6. The US is leading all regions
Regional analysis shows that the US has the highest transaction volume by a clear margin, while EMEA, Canada, and APAC sit in a middle tier, and LATAM trails behind.

This suggests that VendBridge currently has its strongest traction in the US and that international growth is still uneven.

### 📉 7. Transaction activity is healthy, but not fully consistent
The transaction trend over time shows several spikes and dips rather than a perfectly stable pattern. This means engagement is strong overall, but user activity may still depend on specific peak days, campaigns, or time-sensitive triggers.

There is an opportunity to make transaction behavior more consistent across the month.

### 🧩 8. Growth is strong, but the funnel is slightly unbalanced
The dashboard shows strong top-line growth in installs and healthy downstream engagement, but the drop in signup rate and increase in crashes suggest that parts of the user journey are not scaling as smoothly as others.

In other words, growth is happening — but not every part of the funnel is growing at the same quality level.


## 💡 Recommendations

### 🛬 1. Improve the install-to-signup journey
Since installs are rising faster than sign-ups, the onboarding flow should be reviewed carefully. Any friction in account creation, first-session setup, or signup prompts could be reducing conversion efficiency.

Improving this stage would help VendBridge convert more of its growing traffic into actual users.

### 🧯 2. Treat app stability as a top priority
The rise in app crashes should be addressed immediately. Crash data should be segmented by device, region, and version to identify where the biggest issues are happening.

Strong acquisition means little if the experience becomes unstable after download.

### 🔁 3. Strengthen the retention strategies that are already working
Uninstalls and churn are moving in a positive direction, which means some aspects of the current user experience are encouraging people to stay.

These retention wins should be preserved and amplified through repeat-use incentives, relevant notifications, and better in-app engagement loops.

### 🤖 4. Prioritize Android optimization
Since Android leads transaction activity, product improvements on Android are likely to have the greatest immediate impact. Performance testing, crash fixes, and feature enhancements should pay special attention to that device segment.

### 🌎 5. Investigate what is working in the US
The US is clearly the strongest performing region, so it would be valuable to study what is driving success there. Marketing strategy, product usage patterns, or user demographics in that region may offer lessons that can be applied elsewhere.

### 🧭 6. Build region-specific expansion strategies
Since growth is uneven across regions, a generic international strategy may not be enough. Different regions may require different acquisition messages, onboarding flows, or engagement tactics.

A more localized strategy could help improve underperformance outside the US.

### 📆 7. Encourage more consistent transaction behavior
To smooth out the visible peaks and dips in transaction volume, VendBridge can explore recurring campaigns, reminders, limited-time incentives, or weekly product engagement triggers.

This would help reduce reliance on isolated spikes and create steadier activity.

### 🔍 8. Monitor the full product funnel together
Installs, sign-ups, engagement, crashes, uninstalls, and churn should not be interpreted in isolation. The strongest product decisions will come from viewing these metrics as one connected funnel.

That will make it easier to spot where growth is accelerating, where it is leaking, and where intervention is needed most.


## 🧠 Final Conclusion

VendBridge is showing encouraging early momentum. User acquisition is growing, engagement levels are improving, and retention signals remain fairly healthy. These are strong signs for a product that is still in its early launch phase.

At the same time, the dashboard reveals two important pressure points: **declining signup efficiency** and **rising app crashes**. If those issues are not addressed, they could slow growth and weaken the user experience over time.

Overall, the analysis shows that VendBridge has strong market potential, but sustaining that growth will depend on improving conversion, stabilizing app performance, and building on the engagement patterns that are already working.

