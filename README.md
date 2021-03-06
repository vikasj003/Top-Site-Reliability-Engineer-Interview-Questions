# Top SRE Interview Questions & Answers

> Click :star: if you like the project. Pull Request are highly appreciated.

### Table of Contents

| No. | Questions |
| --- | --------- |
|1  | [Write Efficient data structure for a particular query?](#What-is-WordPress) |
|2  | [Shuffle an array, make sure every element is not on the previous position](#Which-year-was-WordPress-released) |
|3  | [Implement a data structure that supports the operations flipBits(ith bit, # of bits) and getBit(ith bit), billions of possible bits, <= O(n log n) preferably?](#What-are-minimum-requirements-to-run-WordPress) |
|5  | [Print a tree](#What-is-a-plugin-in-WordPress-List-plugin-that-comes-with-WordPress) |
|6  | [How to find if two binary trees have the same structure?](#What-is-the-difference-between-wordpress-com-and-wordpress-org) |
|7  | [Given an array of integers find indices I < j < k such that a[I] < a[j] < a[k].](#Where-is-WordPress-content-stored) |
|8  | [Do you have any recent personal projects?](#What-are-the-differences-between-Posts-and-Pages) |
|9  | [What is graph traversal?](#What-are-the-types-of-hooks-in-WP-and-what-are-their-functions?) |
|10 | [What is a tree?](#What-is-an-action-hook) |
|11 | [Given a collection of ads (data structure given), what is the mean and median of the array?](#What-is-a-filter-hook) |
|12 | [Find the Height of a Binary Search Tree?](#How-do-you-enable-debug-mode-in-WP)
|13 | [Write a program in C, that implements a shell's facilities for (1) initiating a background process, and (2) command line pipes.](#What-is-a-WordPress-taxonomy) |
|14 | [Asked me the difference between a hard and soft link in Linux](#what-is-repository-pattern) |
|15 | [Find all pairs of 3 in an array that add to n.](#Is-WordPres-secure) |
|16 | [What's 2^32](#How-many-default-tables-are-the-WordPress-Can-you-list-them) |
|17 | [Merging intervals](#What-is-default-table-prefix-for-wordpress) |
|18 | [Merge lists/arrays](#how-to-setup-emails) |
|19 | [Implement read() using read4k()](#what-are-queues) |
|20 | [1 round of distributed system and large scale system design](#what-are-jobs)
|21 | [Compress string "aabcaaaaade" to "aabc5xade". Only compress if it shortens the string. 5xa means char a is repeated 5 times.](#what-are-advanced-eloquent-and-query-builder) |
|22 | [Question on 2 lists and their union/ intersection/ remove elements present in L1 which are also present in L2](#which-is-error-management) |
|23 | [Basic list processing](#how-to-create-an-api) |
|24 | [What information is contained in a file inode?](#what-are-events) |
|25 | [HashMap/Hashtable questions?](#what-are-listeners) |
|26 | [Design a "snakes" game](#what-are-payments-and-cashier) |
|27 | [networking, java, and linux/unix](#what-is-test-driven-development) |
|28 | [Linux system call for inode data](#what-is-package-development) |
|29 | [How would you design a real-time sports data collection app] (#at-are-laravel-scout-search-and-algolia) |
|30 | [Made me do a regex of getting just the phone numbers out of a contacts.txt file over Google Docs](#what-is-socialite-auth) |
|31 | [large scale systems design detail](#hat-is-vue-js) |
|32 | [design a phone number search tools](#How-to-connect-Laravel-with-other-SQL-databases) |
|33 | [bit manipulation](#How-to-connect-Laravel-with-non-SQL-databases) |
|34 | [familiarity with Unix/Linux Internals](#what-is-lumen) |
|35 | [familiarity with TCP/IP](#what-is-redis) |
|36 | [which system call returns inode information](#what-is-memcache) |
|37 | [What signal does the "kill" command send by default](#What-is-Horizontal-scaling) |
|38 | [How many IP addresses are usable on a /23 network](#What-is-Vertical-scaling) |
|39 | [Can you describe a connection setup in TCP](#What--Single-Page-Application-in-Laravel) |
|40 | [Filesystems, networking, scripting](#What-are-Microservices-in-Laravel) |
|41 | [Implement a hash table](#what-is-CSRF-and-JWT-token) |
|42 | [What's the default signal used in a kill command?](#what-is-soa) |
|43 | [describe exactly what happens when you type 'telnet google.com 80' at a bash prompt, including shell interpretation, network connections](#what-are-validators) |
|44 | [What happens when I type "ps" into a UNIX prompt?](#what-is-composer) |
|45 | [How does RAID work?](#what-is-symfony) |
|46 | [Something about how a switch works in its internals.](#what-is-route-caching) |
|47 | [How would you design a thumbnail service?](#default-packages) |
|48 | [String manipulation, Trees, Graphs and recursion.](#what-are-named-routes) |
|49 | [Given a data structure of rows (source, ratio, destination), find the value of conversion for a given source to a given destination. Example (EUR, 1.23, GBP)](#what-is-dependency-injection) |
|50 | [How many IP addresses does a network have with a netmask of 21](#what-are-contracts) |
|51 | [Questions about sorting algorithms and their efficiency. Which one is faster, merge sort or bubble sort? As well as the Big O Notation](#what-is-query-log) |
|52 | [Troubleshoot a production incident](#what-are-laravel-traits) |
|53 | [Design the architecture of a system and plan capacity for it](#what-are-Bundles-in-Laravel) |
|54 | [How does fork() work?](#what-are-system-requirements-for-laravel) |
|55 | [Remove chars at first string from second string](#what-are-aggregate-methods-in-query-builder) |
|56 | [Best and worst case of Quicksort](#what-is-singelton-design-pattern) |
|57 | [How would you design hangouts](#what-is-reverse-routing) | 
|58 | [Explain linux virtual memory](#what-are-Popular-composer-packages) |
|59 | [Simple questions such as maximum length of binary tree (n, as it could be unbalanced)](#how-to-get-the-data-from-more-than-3-table-without-using-a-join) |
|60 | [Given a numerym (first letter + length of omitted characters + last letter), how would you return all possible original words? E.G. i18n the numeronym of internationalization](#list-some-artisan-commands) |
|61 | [large systems design?](#what-are-sessions) |
|62 | [theoretical best trans-continental round-trip ping time](#what-are-cookies) |
|63 | [Find the shortest path between two words (like "cat" and "dog), changing only one letter at a time.](#what-is-current-version-of-PHP-MySQL-Laravel-MongoDB-etc) |
|64 | [number of bit in mac address](#Describe-design-architecture-of-an-app) |
|65 | [3 first packet in tcpip connection?](#What-are-SQL-Injections) |
|66 | [what a AAAA record?](#How-to-call-static-methods) |
|67 | [Write the `tail` program, in C, on the whiteboard](#How-to-achieve-multiple-DB-hosts)
|68 | [Write a function to return the most frequently occurring number in a list (the mode).](#what-is-Abstract-class) |
|69 | [Describe Linux from its kernel level?](#what-are-Default-ports-for-MySQL-Email-etc) |

 
1. ###  What is WordPress?

    Its an opensource PHP framework used for CMS, website creation and ecommerce.

   **[⬆ Back to Top](#types-of-routes)**
    
2. ### Which year was WordPress released?

    2003

   **[⬆ Back to Top](#what-is-web-php)**
    
3. ### What are minimum requirements to run WordPress?

    PHP, MYSQL, Apache.
    
   **[⬆ Back to Top](#types-of-routes)**
    
4. ### List some features of WordPress.

    ...
    
5. ### What is a plugin in WordPress? List plugin that comes with WordPress.

    ..

 **[⬆ Back to Top](#what-is-api-php)**

6. ### What is the difference between wordpress.com and wordpress.org

    WordPress.com is cloud hosted WordPress while WordPress.org is the cummunity edition.

   **[⬆ Back to Top](#what-is-api-php)**
   
    
7. ### Where is WordPress content stored?
  wp_posts

   **[⬆ Back to Top](#table-of-contents)**
    
8. ###  What are the differences between Posts and Pages?

 ...

   **[⬆ Back to Top](#table-of-contents)**
    
9. ### What are the types of hooks in WP and what are their functions?
   
   Filters and actions.

   **[⬆ Back to Top](#table-of-contents)**
    
10. ### What is an action hook?

    When we type a URL, a request is sent to the server. The server goes from /public to bootstrap folder from which is goes to the routes file. The route files sends it the right controller/view.


   **[⬆ Back to Top](#table-of-contents)**
    
11. ### What is a filter hook?

    Migrations help us keep SQL tables in code. When we have to setup the DB, we just run the migration.

   **[⬆ Back to Top](#table-of-contents)**
    
12. ###  How do you enable debug mode in WP?

    Service providers are responsible for booting and configuration (binding all resources.)
    
   **[⬆ Back to Top](#table-of-contents)**
    
13. ### What is a WordPress taxonomy?

    Middleware checks for authentication.


   **[⬆ Back to Top](#table-of-contents)**
    
14. ###  Is WordPress secure?

    Object oriented and Model based way of DB query


   **[⬆ Back to Top](#table-of-contents)**
    
15. ### How many default tables are the WordPress, Can you list them?

    The ORM wrapper Laravel uses is called Eloquent. Every table has a model associated with it.
    
   **[⬆ Back to Top](#table-of-contents)**
    
16. ### What is default table prefix for wordpress?

   A database wrapper that makes it easy to access DB.

   **[⬆ Back to Top](#table-of-contents)**
    
17. ### What are Facades?

    Facades are used to hide implementation details and complexities from end user making him/her feel like interacting with a black box.

   **[⬆ Back to Top](#table-of-contents)**
    
18. ### What are disadvantages of WordPress?

    Repository pattern is used to create templates where implementation details are left to be implemented in child classes. It helps with further expansion of code and avoid bottlenecks in class updation.

   **[⬆ Back to Top](#table-of-contents)**
    
19. ### What is the difference between installing and activating a theme?
    
    Passport provides a better way to create API.

   **[⬆ Back to Top](#table-of-contents)**
    
20. ### Which ‘meta box’ is not hidden by default on Post and Page screens?
    Testing every function

   **[⬆ Back to Top](#table-of-contents)**
    
21. ### What is the difference between the two URLs in General Settings? (Hint: WordPress Address AND Site Address).

    Configured using `config/cache.php`. Used for database caching. Popular ways Redis and Memcache.

   **[⬆ Back to Top](#table-of-contents)**
    
22. ### What are Importers in WordPress?

    Writing a test for every unit (function or class) you write.

   **[⬆ Back to Top](#table-of-contents)**
   
23. ### What do you mean by the custom field in WordPress?

    Using PHP's `mail()` function amnd Laravel's `sendmail()` function. You can custoimize it using templates.

  **[⬆ Back to Top](#table-of-contents)**
  
24. ### In WordPress, objects are passed by value or by reference?

    Queue is a line of jobs to be proccessed. You can create multiple queues which is multiple lines of jobs
   **[⬆ Back to Top](#table-of-contents)**
    
25. ### What is the loop in WordPress?

    Job is a task being performed in the background.

   **[⬆ Back to Top](#table-of-contents)**
    
27. ### How to setup Emails?

   Use Laravel's sendmail() function and create a mail template.

   **[⬆ Back to Top](#table-of-contents)**
    
28. ### ) How can you disable comments in WordPress?

    Complex eloquent queries are called advanced eloquent. Query builder is wrapper for database queries.

   **[⬆ Back to Top](#table-of-contents)**
    
29. ### Which JS frameworks do you know?

   Error handling is managing `exception` in a Laravel application.

   **[⬆ Back to Top](#table-of-contents)**
    
30. ### 1 yard of string cost $0.10 . If you have 60 cents how many strings can you buy?

  Use api.php. Link will be x.com/api/slug

   **[⬆ Back to Top](#table-of-contents)**
    
31. ### How to create a WordPress child theme and why should we create a child theme?

   You get notified when an action is triggered.

   **[⬆ Back to Top](#table-of-contents)**
    
32. ### Can we create a child plugin like child theme?

    Which listen to the events.

   **[⬆ Back to Top](#table-of-contents)**
    
33. ### What plugins are you familiar with in WP?

    Payment processing is difficult. Cashier is a package which makes it easy. Its installed using composer.

   **[⬆ Back to Top](#table-of-contents)**
    
34. ### How would you change all the occurrences of “Hello” into “Good Morning” in post/page contents, when viewed before 11AM?

    Test is written first and then the function is written.

   **[⬆ Back to Top](#table-of-contents)**
    
35. ### What is the $wpdb variable in WordPress?

    Larvel uses composer which gets packages. You can develop your own package and submit.

   **[⬆ Back to Top](#table-of-contents)**
    
36. ### How to add a script in WordPress?

   https://laravel.com/docs/5.8/scout

   **[⬆ Back to Top](#table-of-contents)**
    
37. ### How to add a style in WordPress?

    Socialite is Social login for Laravel.
    Auth is Laravel's authentication.

   **[⬆ Back to Top](#table-of-contents)**
    
38. ### How to create a plugin?

    In easy way to do SPA where you can change state.

   **[⬆ Back to Top](#table-of-contents)**
    
39. ### How to create a theme?

    Go to config/database.php

   **[⬆ Back to Top](#table-of-contents)**
    
40. ### What are shortcodes?

   Add the entry to config/database.php

   **[⬆ Back to Top](#table-of-contents)**
    
41. ### What are the requirements of Wordpress?

    Lumen is the lightweight version of Laravel used usually for making microservices.

   **[⬆ Back to Top](#table-of-contents)**
    
42. ### How to turn on debugging in WordPress?
    
    Key-value database making query faster.

   **[⬆ Back to Top](#table-of-contents)**
    
43. ### What are custom fields?

    Key-value database making query faster.

   **[⬆ Back to Top](#table-of-contents)**
    
44. ### What are template tags?

    By adding more servers we scale horizontally.

   **[⬆ Back to Top](#table-of-contents)**
    
45. ###	How to recover from a hack?

    By increasing the size of the same server we scale vertically.

   **[⬆ Back to Top](#table-of-contents)**
    
46. ### Can Deactivated Plugins Slow Down a WP Website?

    There is single URL. The assets are loaded once and only content keeps changing using JSON request. Its not great for SEO but there are workarounds to create virtual URL.

   **[⬆ Back to Top](#table-of-contents)**
    
47. ### What are the types of hooks in WordPress and mention their functions?

    There are many services which are similar sized. Each performs exactly one function and they talk to each other.

   **[⬆ Back to Top](#table-of-contents)**
    
48. ### What is the prefix of WordPress tables by default?
    CSRF and JWT tokens are used to make sure the action is performed by the user. If there is no token, someone can give a link to user to click or hide it behind some action and him do what the hacker wants.
    A JWT token is hidden in the request while CSRF token is not.

   **[⬆ Back to Top](#table-of-contents)**
    
49. ###  What is WordPress loop?

    There are many services which are similar sized. Each performs exactly one function and they talk to each other. 

   **[⬆ Back to Top](#table-of-contents)**
    
50. ### How can you disable the WordPress comment?

    Validations are used to make sure input is of the kind function wanted. Custom validators are custom made valiators.

   **[⬆ Back to Top](#table-of-contents)**
    
51. ### What is white screen of death?
   
    Composer is PHP's package manager.

   **[⬆ Back to Top](#table-of-contents)**
    
52. ### What are the plugins you can use to create a contact form in WordPress?
    Symfony is a framework Laravel is inspired from.

   **[⬆ Back to Top](#table-of-contents)**
    
53. ### Describe WordPress files and directory structure

    Caching of routes to make going to routes faster. Command: `php artisan route:cache`

   **[⬆ Back to Top](#table-of-contents)**
    
54. ### What are Default packages?
    Cashier, Envoy, Passport, Scout, Socialite, Horizon etc

   **[⬆ Back to Top](#table-of-contents)**
    
55. ### How to get a website URL in WordPress?

    You can give route a name using a parameter.

   **[⬆ Back to Top](#table-of-contents)**
    
56. ### How to secure in our WordPress site?

    Laravel injects dependencies as function parameters.
    Read more: https://medium.com/a-young-devoloper/how-laravel-injects-our-dependencies-14e1b1a044e

   **[⬆ Back to Top](#table-of-contents)**
    
57. ### How to change the homepage URL in WordPress?

    https://laravel.com/docs/7.x/contracts

   **[⬆ Back to Top](#table-of-contents)**
    
58. ### How to display custom Post in WordPress?

   You can enable logging queries and Laravel will record the queries which were run.

   **[⬆ Back to Top](#table-of-contents)**
    
59. ### What is wp_footer() in WordPress?

    They solve diamond problem which is when you have to inherit from two classes.

   **[⬆ Back to Top](#table-of-contents)**
    
60. ### How to add custom dynamic sidebars in WordPress?

    Used for grouping stuff like route groups (CRUD in one line.)

   **[⬆ Back to Top](#table-of-contents)**
    
61. ### How to Create a Widget in WordPress?

    PHP version, MySQL, PHP packages mentioned on Laravel.com, apache server

   **[⬆ Back to Top](#table-of-contents)**
    
62.	### What is a permalink in WordPress?

    Max, min, sum etc
   ```
   $price = DB::table('orders')->max('price');
   ```
   
   **[⬆ Back to Top](#table-of-contents)**
    
63.	### How do you create a page template?

    A single object of a class is created throughout the lifecycle.

   **[⬆ Back to Top](#table-of-contents)**
    
64.	### How to make any others pages to front page in WordPress?

   To generate the process of generating the URL which leads to a route. Its used in MVC apps. You can use it using named routes in laravel.
   
   **[⬆ Back to Top](#table-of-contents)**
    
65.	### Why WordPress is the best CMS?

    Guzzle

   **[⬆ Back to Top](#table-of-contents)**
    
66.	### What are the difference between post and page in WordPress?

    Answer: Subquery, union.

   **[⬆ Back to Top](#table-of-contents)**
    
67.	### Explain the usermeta function in WordPress.

    ```
    php artisan list
    php artisan make:migrate
    php artisan make:controller
    php artisan make:model
    php artisan config:clear
    php artisan serve
    ```

   **[⬆ Back to Top](#table-of-contents)**
    
68.	### Explain Avatar in WordPress?

    Session is data related to a specific user.

   **[⬆ Back to Top](#table-of-contents)**
    
69.	### What is Category in WordPress?

    Cookies is generalized data.

   **[⬆ Back to Top](#table-of-contents)**
