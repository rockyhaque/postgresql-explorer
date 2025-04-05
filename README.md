# Bookstore Database Assignment

This project demonstrates the setup and management of a PostgreSQL database for a bookstore. The assignment involves creating and manipulating tables, inserting sample data, and performing SQL queries.

## 🚀 Objective

The assignment focuses on the following tasks:

- Creating tables (`books`, `customers`, `orders`).
- Inserting sample data into the tables.
- Performing SQL queries (CRUD operations, JOINs, aggregation, etc.).

## Bonus Section

1.  What is PostgreSQL? <br>
    `Ans:` PostgreSQL হলো একটি ওপেন-সোর্স রিলেশনাল ডেটাবেস ম্যানেজমেন্ট সিস্টেম (RDBMS)।

2.  What is the purpose of a database schema in PostgreSQL? <br>
    `Ans:` Schema ডাটাবেস অবজেক্ট যেমন টেবিলগুলিকে লজিক্যাল গ্রুপে সংগঠিত করতে দেয় যাতে সেগুলিকে আরও পরিচালনাযোগ্য করা যায় । Schema একাধিক ব্যবহারকারীকে একে অপরের সাথে হস্তক্ষেপ না করে একটি database ব্যবহার করতে সক্ষম করে।

3.  Explain the Primary Key and Foreign Key concepts in PostgreSQL. <br>
    `Ans:` Primary Key একটি টেবিলের ইউনিক আইডেন্টিফায়ার, আর Foreign Key অন্য টেবিলের সাথে সম্পর্ক তৈরি করে।

4.  What is the difference between the VARCHAR and CHAR data types? <br>
    `Ans:` CHAR এর একটি নির্দিষ্ট আকার আছে, কিন্তু VARCHAR এর একটি পরিবর্তনশীল আকার আছে । CHAR ডেটা টাইপ নির্দিষ্ট দৈর্ঘ্যের ডেটা সঞ্চয় করে, যেখানে VARCHAR ডেটা টাইপ পরিবর্তনশীল ফর্ম্যাটের ডেটা সঞ্চয় করে। VARCHAR ডেটা টাইপের মানগুলিতে স্পেস দেওয়া হয় না; CHAR মানগুলিতে নির্দিষ্ট দৈর্ঘ্যের স্পেস দেওয়া হয়।

5.  Explain the purpose of the WHERE clause in a SELECT statement. <br>
    `Ans:` WHERE ক্লজটি রেকর্ড ফিল্টার করতে ব্যবহৃত হয়। এটি শুধুমাত্র সেই রেকর্ডগুলি বের করতে ব্যবহৃত হয় যা একটি নির্দিষ্ট শর্ত পূরণ করে।

6.  What are the LIMIT and OFFSET clauses used for? <br>
    `Ans:` LIMIT ডেটার সংখ্যা সীমাবদ্ধ করে, আর OFFSET কতটি রেকর্ড স্কিপ করবে তা নির্ধারণ করে।

7.  How can you modify data using UPDATE statements? <br>
    `Ans:` UPDATE স্টেটমেন্ট PostgreSQL-এ বিদ্যমান টেবিলের ডেটা পরিবর্তনের জন্য ব্যবহৃত হয়। এটি সাধারণত SET ক্লজ এবং WHERE ক্লজ সহ ব্যবহার করা হয়, যেখানে SET ক্লজ দ্বারা কোন কোন কলামের মান পরিবর্তন করতে হবে তা নির্ধারণ করা হয়, এবং WHERE ক্লজ দ্বারা নির্দিষ্ট করে দেওয়া হয় কোন কোন রেকর্ডে পরিবর্তন আসবে।

8.  What is the significance of the JOIN operation, and how does it work in PostgreSQL? <br>
    `Ans:` JOIN অপারেশন PostgreSQL-এ অনেক গুরুত্বপূর্ণ কারণ এটি একাধিক টেবিলের মধ্যে সম্পর্ক স্থাপন করে ।

9.  Explain the GROUP BY clause and its role in aggregation operations. <br>
    `Ans:` JOIN মূলত দুটি বা তার অধিক টেবিলের সাধারণ একটি বা একাধিক কলাম (যেমন - প্রাইমারি কি ও ফরেন কি) এর উপর ভিত্তি করে কাজ করে। একে টেবিলগুলোর মধ্যে "relationship" তৈরি করার উপায় বলা যায়।

10. How can you calculate aggregate functions like COUNT(), SUM(), and AVG() in PostgreSQL? <br>
    `Ans:` PostgreSQL-এ অ্যাগ্রিগেট ফাংশনগুলো (যেমন COUNT(), SUM(), AVG()) ব্যবহার করে টেবিলের ডেটা থেকে বিভিন্ন পরিসংখ্যানমূলক মান বের করা যায়। এই ফাংশনগুলো একটি কলামের উপর গাণিতিক হিসাব চালিয়ে ফলাফল প্রদান করে।
