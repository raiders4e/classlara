
                                            |        |      o
                                            |        |      
                                            |        |      |
                                            |--------|      |
                                            |        |      |
                                            |        |      |
                                            |        |      |

#Laravel + GIT

Hey class. This will be the working repository for our Laravel webapp. This will be an exercise (maybe set of exercises)
where 
we will be getting familiar with both Laravel and GIT. In doing so, we'll also be exposed to GitHub. 
We'll start out with some pretty simple stuff, but hopefully as the term goes on, we can get into some 
more advanced topics and exercises. I think you'll quickly find that these are two incredibly 
powerful tools when it comes to the work we do. In the beginning, the focus of this will be more on 
GIT. As we get familiar with that however, the focus will shift a little bit more towards Laravel and 
object oriented programming in general. Let's __git__ to work! (__Git__ it? (XD okay... I'm done))

***

##Exercise Outlook
####1. GIT Introduction and Laravel Installation
   * Setup GIT and GitHub
   * Object Oriented Programming (OOP) and Model View Controller (MVC) Explanation
   * Laravel Installation and Talk
   * Laravel Routes and Views
   * Clone, commit, push, branch, etc. with GIT
   
####2. Laravel and Model View Controller (MVC) Frameworks (work in progress)

***

##Exercises

####Exercise 1
   1. GIT and GitHub Setup
       * Make sure GIT is setup and ready to go in Cloud 9 server.
       * Verify GitHub account.
   2. OOP and MVC Discussion
       * Go over concepts of OOP including the separation of concerns, classes, etc.
       * Dive into what makes up an MVC and how it relates to OOP. Take a look at the MVC components 
       (models, views, controllers) and the purpose of each.
   3. Install Laravel
       * Clone stock [Laravel repository](https://github.com/laravel/laravel.git) to Cloud 9 server.
       * Run necessary terminal commands as described by me in class.
       * Clone Laravel repository (the very repository you're reading this in) to your Cloud9 server.
       * Follow the same steps you completed in the stock Laravel installation (the terminal commands).
   4. Create Routes and Views
       * Note: The following steps will be completed in the Laravel installation that you cloned from this repository.
       * Take tour through the various parts of Laravel - namely the app, resources, public, and Http directories.
       * Create a new GIT branch for yourself and make sure you use the checkout command to select it.
       * Open and view _routes.php_ file that resides in the _app_ directory. Go into how routes work in relation to an MVC framework like Laravel.
       * Create route.
          * This route that should should include an enclosure that returns a view that you create.
          * The view you return should reside in the _resources/views_ directory. This view will obviously be written 
            in HTML but if you're up for the task, you could write some of it in Laravel's proprietary Blade syntax. 
            The content of your view should be at least somewhat pertinent to the name of the route I assign to you 
            (I'll explain shortly). For example, if I assign you a route named "Welcome," then I would like to see 
            the content of your view relate to that somehow. For the example I just gave, the content could be something 
            as simple as an h1 tag containing the phrase "Welcome to this view!" The content is really not too important 
            as I'm more focused on the proper creation and placement of the view.
          * Route assignments:
             * Anthony: Contact
             * Chris: Help
             * Troy Johnson: Welcome
             * Michael: Blog
             * Troy Fisher (if present): About
             * Matt: Login
             * Rory (if present): Register
             * Bob (if you want to follow along): Home
   5. Commit Changes and Issue Pull Request
       * In the terminal, stage and commit your changes with GIT. Make sure your commit message is descriptive.
       * Push changes to your branch.
       * Issue a pull request to me for your branch so that it can be merged with the master branch.
         