---
layout: post title:
"Going Shopping"
date:   2016-04-27 17:54:57 -0400
categories: scala
---


# Intro

In this post I am going to talk about 'going shopping' for a software solution
to a 'well worn problem'.

Firstly, I will define what I mean by 'going shopping' and 'well worn
problem'. Then I will lay out some well worn problems I have personally come
across.
Next, I will walk through a concrete example of looking for an aws S3 library
for Scala. Finally, I will recap on what I learned from the whole process.


# Definition

I define a 'well worn problem' as: ``` A problem that has been solved time and
time again, often using many different technologies.```

Following on from that 'going shopping' is: ```An exploration to see if the 
problem at hand has been solved before, maybe even a number of different
ways.```

Often there are a number of off the shelve solutions readily available for the
problem but not one that stands as objectively superior out for the current language or framework.

I find that I often end up anchoring to the solution I know.  While this often
works out, I can't help but feel that I am sometimes missing out on a solution that is: easier,
more robust, more maintainable or all of the above.

# Examples of well worn problems

1. Logging requests and responses for an HTTP service.  2. Formatting your code
in a consistent manner.  3. Versioning your code releases.


I have run into the examples above multiple times in my short career for
numerous language-technology pairings. I think programers often take for
granted the problems that they have already already solved. This makes sense as 
we are able to solve a problem much more quickly the second time. However, when we
step back a little further we could observe that most of the day to day
problems of web developement have been encountered before. So, even if you have
not solved a problem personally you can often leverage the experiences of
others to expedite the time to develop a solution. Shopping can help with this as we 
will see next.

# S3 and Scala

## The Potential Solutions

I recently had to write some code in Scala that talked to Amazon's S3 service. Without any
existing code to pattern from I needed to go shopping to figure out what library to use.  A
quick google showed a number of promissing options.

* [AWScala](https://github.com/seratch/AWScala)
* [Aws-Wrap](https://dwhjames.github.io/aws-wrap/doc/s3.html)
* [Aws Scala](https://bitbucket.org/atlassian/aws-scala/overview)

So now that I have a problem and some potential solutions how do I choose which is
the best fit.

## Criteria for comparison

Things to consider when going shopping:

* Quality
** Test quality and coverage
** Stars/Likes 
** Actively maintained? Last commit, is it assigned to person, has it been
replaced by newer and shinyer thing
** Are there stable releases?
** Number of bug fixes 
* Likelihood of future developemt
** Active users 
** Active commiters 
** Commit volume and age
** Gitter channel/ IRC Channel
** Number of feature requests/ pull requests 
* Ease of integraion with your stack
* Feature set
** Special features: Async support Libraries, integration with your framework, etc 

## The Comparison

{% highlight scala %} {% endhighlight %}

# Conclusion

It might be overkill to do this for every shopping oppertunity.

# Further Reading
