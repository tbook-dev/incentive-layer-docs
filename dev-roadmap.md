# TON WISE Score and TBook Incentive Passport Tech Spec

## 1 Introduction

### 1.1 Purpose

This documentation is to provide details of the requirements, architecture and implementations for the TON WISE Score and Tbook Incentive Passport.&#x20;

### 1.2 TON WISE(Wealth, identity, social, engagement) Score

TON WISE(Wealth, identity, social, engagement) Score is an index to measure a user’s impact on The Open Network web3 projects. It can:

1. Help TON community participants digitalize their impact. Improve community participation.&#x20;
2. Help new projects onboard TON, and provide Leaderboard for them to efficiently find the top community users to help them build their business.
3. Be viewed on Incentive Passport&#x20;

## 2 Demands description

### 2.1 Incentive Passport Telegram Mini App

1. Register for a TBook Incentive Passport account by connecting their TON wallet, in the Incentive Passport TMA.&#x20;
2. Enable users to view their WISE Scores and index metrics in telegram

### 2.2 Multi-Chain Attestation Integration

1. Attest users' activities on multiple blockchains and web2 platforms, and update their WISE Scores. This enables users to translate their impact into a singular index.&#x20;
2. Generate TON WISE Score with TON address.&#x20;

### 2.3 Build TON WISE Score Leaderboard

1. Users need to be able to earn TON WISE Score points based on their on-chain activities attestations. With TON WISE Score Users will be able to measure and demonstrate their impact on TON.
2. Leaderboard should be able to show the rank of high impact users. The rank could provide  Each user needs to have a public profile showing their TON Builder Score and key stats.&#x20;
3. When web3 projects onboard TON, they can find the profiles of high impact crowd on the Leaderboard, and use rewards(airdrops, tokens, NFTs etc.) to attract their participation in promotion campaigns.&#x20;

## 3 Product Implementation

### 3.1 product architecture

#### 1 Incentive passport

1. Provides functionalities for identity verification. A user can create an incentive passport by connecting with TON wallet.&#x20;
2. &#x20;Users can attest their activities and profiles from multiple blockchains and web2 services(X, Meta etc.) through Incentive Passport.&#x20;
3. &#x20;Users should get access to their incentive passport in the TBook TMA. They can manage and view their TON WISE Scores on the TBook Incentive Passport TMA.

#### **2 TON WISE Score Engine**

1. TON WISE Score is an indicator of: activeness, holdings and coinage, engagement, multi-chain wealth and social impact.&#x20;
2. Handles the calculation of users’ TON Builder Scores and user ranking.&#x20;
3. TON WISE Score Engine will update the TOP users on the Leaderboard periodically. The update will be in the manner of a priority queue.

#### **3 Leaderboard**

1. The user interface that provides the ranking of users' TON WISE Score. Leaderboard provides a UI with the high ranking individuals.&#x20;
2. Users can open TON WISE Score Leaderboard in his own incentive passport TMA.

### 3.2 User Interface Design

#### 1 Incentive Passport TMA Portal

<div align="left">

<figure><img src=".gitbook/assets/TON Connect.png" alt="" width="188"><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/Tbook Incentive Passport-TON.png" alt="" width="188"><figcaption></figcaption></figure>

</div>

#### **2 TON WISE Score with Interactive leaderboard**

<div align="left">

<figure><img src=".gitbook/assets/Telegram Mini App.png" alt="" width="188"><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/Telegram Mini App2.png" alt="" width="188"><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/Telegram Mini App-leaderboard.png" alt="" width="188"><figcaption></figcaption></figure>

</div>

#### 3 Campaign Participation TMA page

<div align="left">

<figure><img src=".gitbook/assets/Telegram Mini App-cam1.png" alt="" width="188"><figcaption></figcaption></figure>

 

<figure><img src=".gitbook/assets/Telegram Mini App-re.png" alt="" width="188"><figcaption></figcaption></figure>

</div>

### 3.3 Technical Design

#### 1 Incentive Passport TMA integration

1. Tbook TMA integrates main the functionalities of incentive psasport.
2. Incentive passport TMA will support major incentive assets of Tbook.
3. Incentive passport TMA will be able to track important incentive footprints of users.

#### 2 TON WISE Score Engine

1. Aggregate and update users' TON WISE Scores.&#x20;
2. Rank users based on TON WISE Scores. This happens on each user attestation.
3. TON WISE Score Leaderboard as the presentation layer of TON Builder Score ranks.

#### 3 Attestation

1. Tbook attestation for attesting user activities on TON. &#x20;
2. Tbook's multi-chain attestation system securely aggregates and validates user data from multiple blockchains using cross-chain protocols and standardized data formats.
3. Tbook's social media attestation system securely verifies and records user activities across various platforms(X, etc.).

## 4 Milestones

### Phase 1: **Incentive Passport TMA**&#x20;

Integrate TONConnect wallet on Incentive Passport, enable users to create and use Incentive Passport with one click through TONConnect wallet. 

Build TBook Incentive Passport TMA, allowing users to use Incentive Passport on telegram to participate and claim rewards.

### Phase 2: **TBook TON WISE Score Engine**&#x20;

Build TBook attestation scheme, allow users to attest their social and multi-chain activities on Incentive Passport. 

Build TON WISE Score engine. The engine handles the fundamental logic of users' WISE Score index data aggregation, as well as the ranking of users. 

A catalog of incentive activities released by different projects. The catalog can be displayed based on different categories and trends. 

The admin panel for projects to set up their incentive campaigns.

## 5 Conclusion

The TON WISE Score will be a critical piece of infrastructure to accelerate the growth of the web3 projects built on TON and those who want to onboard TON. The key value of TON Builder Score would be:

1. Creating a standard for user activity and reputation measurement on TON. Enabling users to digitalize their impact.
2. Helping projects to airdrop to a user crowd that has the highest potential of boosting their growth efficiently.
3. Advocate competition among community participants, improve overall performance of web3 projects.&#x20;
4. Enable users to monetize their impact on TON.&#x20;

In the initial phase of Tbook, we need to work with the top applications on TON network as the cold start phase. Thus we need help from TON to connect us with these applications.&#x20;

With the integration of TON WISE Score in Tbook Incentive Passport, we will be able to help projects built on TON to gain their advantages on the market quickly. We will also be able to bring more high quality community builders and web3 projects into the TON ecosystem.
