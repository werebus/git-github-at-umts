<!SLIDE >
# Why Source-control? #

* Provides a **history** of your work over time. When did that feature get
  added?  What is the state of the live application? What was version
  3.2 like?
* Allows for **acountablity**. Who should we ask about that new feature?
  Can we prove who authored each line of our production code?
* Facilitates **colaboration**. Multiple authors need a way to merge
  their contributions.

<!SLIDE >
>  As far as I'm concerned, if the code isn't checked into source control,
>  it doesn't exist.
>
> -- <cite>[Jeff Atwood](http://blog.codinghorror.com/check-in-early-check-in-often/), co-founder Stack Exchange</cite>

<!SLIDE >
# Why git? #

* Decentralized: every copy has a full, usable history
* Cheap branches: no additional space you change something
* Fast commits: microseconds, and no network communication

~~~SECTION:notes~~~
The ability to make fast commits and inexpensive branches encourages
developers to work in a granular yet creative manner. Making a branch to
try out a new feature is less than 1 second operation. Frequent
check-ins cost almost nothing and ensure that people looking at the work
will be able to understand what's going on.
~~~ENDSECTION~~~
