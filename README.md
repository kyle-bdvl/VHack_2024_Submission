Project introduction
-------------------------------------------------------
Project name: thriftBook
Version 1.0
Project created as hackathon submission for VHack 2024. Created by Tan Xin Sheng, Wun Lim Zhe, Kyle John Boudville and Karthik A/L Karunanithy.
Submitted via GitHub on 24th March 2024.

Purpose
-------------------------------------------------------
This app is a financial tracker that serves to complement preexisting initiatives such as the DMP. The princpal aim is to assist users in satisfying their debt management plans and other financial goals by directly managing their day-to-day expenditure and income sources, shaping them via product recommendations and other initiatives to fit the demands of their financial targets.

Currently the app only works with debt management plans provided by AKPK's DMP. The app works by tracking the user's income and expenditure activities relative to their DMP programme requirements via user updates. The app then uses this information along with user spending habits to recommend budget-friendly products and services suitable for the user. Products that are budget friendly will be given a high rating and recommended directly by the app. Meanwhile, products that are expensive will be given a lower rating so that users do not risk exceeding their budget and financial goals. 

At the same time, the app will recommend other initiatives, such as selling off their unused items or getting a side job to further empower users in building financial resillience and contribute towards their financial goals, such as debt repayment. IF the user decides to pursue these initiatives, the app will also take them into account and update its product recommmendations accordingly.

 
-------------------------------------------------------



Technologies used
-------------------------------------------------------



List of features
-------------------------------------------------------
The project's features are divided into a few sections:

1. Start up
This section covers the components that the user will interact with before they can access the app.
    i.	Start up
        This is the page that is first displayed when the project is run. Users can choose to either log in via their Apple account, Google account or a thriftBook account. New users can also create their own account.

        If the user chooses to log in via Apple or Google accounts, they will be redirected to the home page once their respective accounts are verified. If they choose to log in with a thriftBook account, they will be redirected to the log in page. If they choose to create a new account, they will be redirected to the Sign-Up page.

    ii.	Log in
        This page is for users who wish to log in via thriftBook account to enter their username and password. Once verification is successful, they will be redirected to the home page associated with their account.

    iii. Sign Up
        This page is for new users to sign up with the app and create their own account. Users will be asked to enter their email, desired username and password.

    iv. DMP submission
        This page is for new users to upload their debt management plans into the app. This is necessary so that the app may recommend products and services based on their budget constraints as stated within their DMP.
        
        Once the user has uploaded their DMP information, they will be sent to the homepage. Users who do not have a DMP plan may also skip this step and upload their DMP later.

2. Home page
This section covers all components related to managing the user's personal finance.
    i.	 Home-main
        This is the main page of this section. Upon successful log in or account creation, the user will be redirected to this page. 
        
        This page shows the user their budget details in terms of amount spent and budget requirements so that they may plan their spending. Users can also use this page to report recent transactions or update the details regarding their debt management plans here. Finally, users may also view their transaction history for both income and expenditures.

    ii.	Transaction reporting page 
        This is the page where the user can report their financial transaction. Users enter the recepient's name, transaction type, category and amount and a short description describing the purpose and nature of the transaction. 
        Users then submit them and the transaction is recorded by the app.

    iii. My DMP
        This is the page where users are allowed to manage and update their DMP. The contents of this page are similar to the DMP submission page in the Start up section.

3. Search
    This section covers all components responsible for providing the product and job recommendation features.
    i. Search-main
        This is the main page of the section. This page allows users to directly access the product recommendations within the app. Thus, it also serves as a junction for the various product categories classified. 

        In this page, users can set their location information to localize app recommendations. A general search bar is also provided to enable direct searching for products, services or jobs. Below the search bar are buttons that lead to different product categories, such as food and groceries. Users can tap on the button associated with each category to navigate to their respective category pages. Finally, general product recommendations fill the remainder of the page.
    
    ii. Food and grocery pages
        These pages are demo pages to showcase the User Interface associated with each of the category pages mentioned in 3. i. They include a search bar for searching products within their categories (food and groceries) and an explanation of the product recommendation system. Below it is the search by demand function, where the app recommends product combinations according to budget size, number of products and entered keywords. Finally, general product recommendations fill the remainder of the page.

    iii. My purchase list
        This page covers the products that the user intends to purchase. The total cost of the products and the available budget are shown to help users make a sound judgement before they proceed with their purchase.

    iv. Transaction confirmation page
        If the user decides to proceed with purchasing the items within the purchase list (3. iii), this page is displayed. It informs users that the app acknowledges the purchase made and will use it to recalculate product recommendations.

4. Community 
    This section covers the components responsible for connecting users to the community.
    i. Community-main
        This is the main page of the section. In this page, users can manage their advertisements on the platform as well as the sale of their unwanted items as second-hand products. Their advertisements serve as the products that may be recommended to other users. Meanwhile, the items they put up as second-hand products will be visible to other users who are browsing for second-hand deals.

        Users can also access forums started by other users and participate in active discussion. A personal message system is also implemented for private conversations between different users.

    ii. Advertisements and Second-Hand wares
        These pages allow users to manage their advertisements and second-hand wares respectively. They are accessible by tapping on the "Manage my advertisements" and "Manage my second-hand wares" buttons in the Community-main page. In each page, items can be sorted according to categories and directly interacted with.

5. Profile
    This section covers all components that assist the user in managing their account.
    i. Profile-main
        This page enables users to directly manage their profile on the app. Users can edit their profile, see their saved posts, manage blocked users, synchronize e-wallets and modify app settings. They can also log out of their account in this page. Logging out brings them to the start up page.

    ii. Edit profile
        This page enables users to edit their profile.

    iii. Saved posts
        This page enables users to see their saved posts.

    iv. Blocked contacts
        This page enables users to see other users that they have blocked
    
    v. Sync e-wallet
        This page provides a feature where the user can synchronize the app with an e-wallet account. This enables the app to directly recognize transactions made using the registered e-wallets without user input. 

        
