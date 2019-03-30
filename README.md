# Troubleshooting Basics

## Description

In this module you'll learn about the basic troubleshooting steps that can be taken when something goes wrong on your WordPress site.  The lesson will focus on troubleshooting an existing install of WordPress and will not deal with issues during installation.  This basic troubleshooting will fix a lot of common issues avoiding the need to spend hours researching and waiting for answers on the WordPress Support Forums.

* * *

## Objectives

After completing this lesson, students will be able to list basic troubleshooting steps to resolve many common issues.

* * *

## Prerequisite Skills

*   Basic knowledge of WordPress Dashboard.
*   Comfort with activating and deactivating plugins.
*   Comfort with switching and activating themes.
*   Comfort with manipulating and editing WordPress files via FTP.

* * *

## Assets

*   You need this...

* * *

## Screening Questions

*   Are you familiar with switching and activating themes via the WordPress Dashboard?
*   Are you familiar with activating and deactivating plugins via the WordPress Dashboard?
*   Are you familiar with manipulating WordPress files via FTP?

* * *

## Teacher Notes

*   The ideal student will be able to answer yes to most of the screening questions.
*   A lack of familiarity with FTP and file manipulation does not eliminate the ability to take the course.

* * *

## Hands-on Walkthrough

[This is in progress.]

### Take a deep breath! Walk away.

It is easy to become frustrated when we can't solve a problem immediately. As a result of our frustration, our vision becomes more narrowly focused. We then repeat the same actions over and over or make assumptions about what the problem is and don't look beyond that. We close our mind to other possible causes to the problem or are so overwhelmed by the problem that we don't know where to start to solve it. The first step to solving any problem is to relax. While it may seem like the world is ending, it is not. The site may be temporarily broken or not working as expected, but you are more likely to get it working the way you want if you take a deep breath and a break and approach the problem fresh. When you are feeling more relaxed, you can work through the following exercises to define the problem more clearly and find a solution.

### A well-defined problem is half the solution!

Most computer-related and software-related are not random. With the exception of a hardware failure, all software-related problems follow a very logical and linear progression of cause and effect. Half of the solution to your problem lies in defining the problem. Once you have defined the problem, the solution is close at hand. In defining the problem, we need to be as specific as possible in our description. Instead of saying, "The theme does not work," we may say, "When I updated the theme, my header image disappeared." To begin to solve the problem, first identify WHEN the problem occurs, then see the specific areas below for how to troubleshoot issues with that specific event. Most commonly, problems occur:

*   After installing and activating a new plugin or theme
*   After updating WordPress core, a plugin, or theme
*   After modifying a template file, functions file, or stylesheet

Think about what happened right before the problem occurred. This will help you narrow down the source of the problem.

### Identifying variables

In addition to identifying when the problem occurs, we need to identify other variables in our WordPress installation that may be effecting how our site is functioning. Take time to note the following:

#### A - Hosting

*   Who is your web host?
*   What version of PHP and MySQL are they running on your hosting account?
*   Do these match the recommended software versions on the [WordPress Requirements](https://wordpress.org/about/requirements/) page?

#### B - WordPress

*   What version of WordPress is running?

To find the version of WordPress you are running: 1 - Login to your WordPress site. 2 - Click the Dashboard icon at the top of the Dashboard sidebar. 3 - Take note of the WordPress version under the **At a Glance** panel:

![](https://make.wordpress.org/training/files/2014/10/dashboard-at-a-glance.png)

What version of WordPress are you running? Is it the most current version? If it's not the most current version, you will see an Update button in the **At a Glance** panel:

![](https://make.wordpress.org/training/files/2014/10/dashboard-at-a-glance-update-1.png)

#### C - Plugins

*   What plugins are installed?
*   Are all the plugins current?
*   Are there any plugins that haven't had updates in a while? Find the plugin you are using on WordPress.org (or from the paid plugin developer) and look at the last update date. Do you have the current version? Does it appear the plugin is no longer maintained?

#### D - Themes

*   What theme are you using? (See Troubleshooting Themes)
*   Is the theme the current version?

#### E - Cache

*   Browser
*   Web host
*   Plugin

#### F - Local computer environment

*   Browser and browser version
*   Computer operating system and version
*   Network, router, ISP

### Replicating problem and eliminating variables

*   Repeating the problem
*   Eliminating variables
*   Testing in new install

### Dashboard Troubleshooting

*   Screen Options
*   Revisions

### Step one

Follow along...

### Code Examples

Use shortcodes for each language to wrap code samples. For indentation, use 4 spaces.

**PHP**
```
<?php
    echo 'This line is indented with 4 spaces.';
?>
````

**JavaScript**
```
jQuery( "body" ) .html(
    "This line is indented with 4 spaces."
)
```

**HTML**
```
    This line is indented with 4 spaces.
```

**CSS**
```
{
    /* This line is indented with 4 spaces */ color: #ff0000;
}
```

**Generic with line numbers**
```
    This is some generic code with line numbers
```


### File Names

Wrap file names in the HTML element **code**: `style.css`

* * *

## Exercises

*   Do this...

* * *

## Quiz

### Question?

1.  Answer
2.  Answer
3.  Answer

**Answer:** 3\. Answer

### Question?

1.  Answer
2.  Answer
3.  Answer

**Answer:** 2\. Answer   NOTES: Preventative Maintenance: *Backup *Update Issues: *WSOD *Missing Sidebar *Scheduled Posts, Missed Schedule *Maintenance Mode stuck First Steps: *What did I do last? You can reverse from there *Disable all plugins *Revert to default theme (twenty-xxxxxxx) *re-activate one-by-one or in small groups testing along the way WSOD: *Need to access
