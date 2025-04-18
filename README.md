### Welcome to my Github 👋

Hello and welcome to my github! 

My name is Daryl and I'm Tech Lead at [ABC Glofox](https://www.glofox.com/) and creator of [Last Folk Standing](https://app.lastfolkstanding.com/)

# 🔭 I’m currently working on:
## ⚽ [Last Folk Standing](https://app.lastfolkstanding.com/)

### What is Last Folk Standing?

It's an online platform that allows you to create & manage Last Man Standing competitions

#### What is a Last Man Standing competition? 

It's a competition where each week you pick a team to win a fixture. If that team wins, you remain in the competition and cannot reuse that team again.

If that team draws or loses, you're out.

The last person remaining wins the prize!

#### Why did I create it?

Last Man Standing competitions are a great way for local sports club to fundraise at the start of the season. 

However the amount of admin required to setup and run these takes a lot of time and effort with all the payoff coming in the first week of it. Once the Last Man Standing starts, there is just a lot of admin work to keep it running and chasing people for selections.

Then when the covid pandemic hit, a lot of the fundraising efforts was very much in person, with a lot of clubs losing the ability to move online quickly, I created an online platform that would handle the running of these competitions and most improtantly, allow for online payments so clubs could continue to fund raise during the pandemic.

#### Built with

- Frontend - Angular
- Backend - AWS API Gateway with lambda & backed with dynamodb
- AWS CDK as IAC (Infrastructure as Code)
- Auth - Auth0.com
- Payment Processing - Stripe integration
- CI/CD - CircleCI

#### How is it built?

It's primarily an event based system, where the main trigger of activity comes from when a round of fixtures is completed.
Due to the bursty nature of last man standing competitions, having a resiliant system with events allows for it to better handle these triggers at a controlled rate without overwhelming the system.

## 🏅 [LeaguR](https://www.leagur.com/)

### What is LeaguR?

Leagur is a simple webapp that will help create and manage your league competitions for you.

Enter the team names you want, select the number of times they play each other and LeaguR generates the fixtures for you.

Enter team results and have the standing auto update for you.

#### Why did I create it?

I created it because I was becoming more and more frustrated with some of the leagues I was playing soccer with that they were extremely slow with updating their league tables and results, some with complete inaccuracies and poorly formatted free-text league tables.

I also wanted to hone some of my learnings into a real world example and was interested in building a working web application and frontend that would have CI/CD built in and built on AWS.

I saw this as a fun side-project that could also help them have a better mechanism to manage and update their leagues. But then it actually became a fun little way of creating leagues for FIFA tournaments we would play ⚽ 🎮

#### Built with

- Frontend - Angular
- Backend - AWS API Gateway with lambda & backed with dynamodb
- SAM template as IAC
- Auth - Auth0.com
- CI/CD - CircleCI

# 📫 How to reach me: 
- [LinkedIn](https://www.linkedin.com/in/petersdaryl/)

# Interests:
- :soccer:  Football
- :video_game:  Video games
- :runner:  Half marathons
- :computer:  Keeping up to date (trying) with the latest technology and methodologies in Software Development
