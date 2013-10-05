# Identity and Opinion: 

## A Randomized Experiment

<p>Sean J. Taylor (NYU), Lev Muchnik (HUJI), and Sinan Aral (MIT)</p>


# Identity and Opinion:

## A Randomized Experiment

<p>Sean J. Taylor (NYU), Lev Muchnik (HUJI), and Sinan Aral (MIT)</p>
<p><img src="img/stars.png" style="border:none"></p>


# Identity and Opinion:

## A Randomized Experiment
<p><img src="img/stars.png" style="border:none"></p>



# Identity and Content are Tied

## What makes social media <em>social</em>


<img src="img/bieber.png">
<p>Twitter</p><p><small>(18% of online adults, Pew 2013)</small></p>


<img src="img/reddit.png" style="max-width:100%">
<p>Reddit<p><p><small>(6% of online adults, Pew 2013)</small></p>


<img src="img/facebook.png">
<p>Facebook</p><p><small>(665m daily active users, Facebook 2013)</small></p>


<img src="img/pinterest.png" style="width:400px;height:auto;">
<p>Pinterest</p><p><small>(70m users, Semiocast 2013)</small></p>


## Identity Cues

* are pervasive
* provide quality signal
* have a learned meaning/association over time
* affect our evaluation of content?



## How Valuable is an Identity?

<img src="img/reputation-value.jpg">


1. more favorable ratings?
2. higher rate of engagement, response, or sharing?
3. NOT the same as audience size


## Identity and Content are Endogenous

<img src="https://docs.google.com/drawings/d/1hkAo4kkWaMgelBPoRBdvb2qVa7SjeUDrUT7RHtVuXOI/pub?w=888&amp;h=563" style="max-width:85%; background-color: white;">


## Related Work

* measuring user content quality (Agichtein et al. 2008)
* measuring sharer reputation (Yang et al. 2013)
* source effects in evaluation of social media (Messing 2013)
* economic value of online reputation (Resnick et al. 2002)
* causal effect of social cues (Bakshy et al. 2012, Muchnik et al. 2013)



## Field Experiment

<img src="img/pepsi.jpg">


### Social news website (similar to Reddit)

<img src="img/reddit-frontpage-links.png">


## Comments on posted articles

<img src="img/reddit-comments.png">


* ~ 2 years on a social news website
* ~ 3,700 commenters
* ~ 6,700 comment viewers
* ~ 3.5 x 10<sup>5</sup> comments
* ~ 1.7 x 10<sup>7</sup> comment exposures


## Conditions

<div style="column-count:2; -moz-column-count:2;-webkit-column-count:2;-webkit-column-gap: 50%;">
  <div>
    <img src="img/reddit-iden.png" style="height:200px;width:auto;">
    <p><em>identified author</em></p>
    <p><small>95% of viewer-comment exposures</small></p>
  </div>
  <div>
  <img src="img/reddit-anon.png" style="height:200px;width:auto;">
  <p><em>anonymous author</em></p>
  <p><small>5% of viewer-comment exposures</small></p>
  </div>
</div>

<p>Users were informed this was a site-wide experiment.</p><p>Two year study allows us to rule out novelty effects.</p>


## Content Interactions

<img src="img/reddit-comment-annotated.png">

<div>Comment rating is anonymous, ruling out reciprocity/retribution effects</div>


## Measures

* <strong>Turnout rate</strong>: either up-vote or down-vote
* <strong>Up-vote rate</strong>
* <strong>Down-vote rate</strong>
* <strong>Positivity</strong> (<em>opinion change</em>): up-vote given turnout 
* <strong>Reply rate</strong>


## Experiment Design

<img src="https://docs.google.com/drawings/d/11LJQsEhnMqXnmbJlupiPXXMgUOK_cFyf97s-XHydow8/pub?w=885&amp;h=779" style="max-width: 70%; background-color: white;">


## Model

`\( \Pr(Y_{ijk} = 1| D_{jk}) \sim \alpha_{ij} + \delta_{ij} D_{jk}  \)`

* $Y_{ijk}$ &mdash; 1 if the viewer $k$ interacts with $i$'s comment $k$
* $D_{jk}$ &mdash; viewer $j$ sees commenter for comment $k$
* $i$ &mdash; commenter
* $j$ &mdash; viewer
* $k$ &mdash; comment


## ATE of Identity

`ATEI = \( \frac{\Pr(Y_{ijk} = 1 | D_{jk} = 1)}{\Pr(Y_{ijk} = 1 | D_{jk} = 0)} \)`


## Conditional ATE of Identity

`ATEI(x) = \( \frac{\Pr(Y_{ijk} = 1 | D_{jk} = 1, X_{ijk} = x)}{\Pr(Y_{ijk} = 1 | D_{jk} = 0, X_{ijk} = x)} \)`



## Average Treatment Effects

<img src="img/figures/web.ate.effect.png" style="max-width:50%">
<p><small>Bootstrap 95% Confidence Intervals for Relative Risk</small></p>



## Commenter-level Effects

<img src="img/figures/web.commenter.activity.png" style="max-width:50%">
<p><small>Comments are highly skewed toward active users, allowing a within-subject analysis.</small></p>


<img src="img/figures/web.ite.upvote.png" style="max-width:48%">
<img src="img/figures/web.ite.dnvote.png" style="max-width:48%">
<p><small>Active commenters seem to mostly be helped by their identities.</small></p>


<img src="img/figures/web.ite.turnout.png" style="max-width:48%">
<img src="img/figures/web.ite.positivity.png" style="max-width:48%">
<p><small>Dramatic positive opinion change for some active users.</small></p>


<img src="img/figures/web.ite.reply.png" style="max-width:60%">
<p><small>Higher reply rates for some commenters when identity is shown.</small></p>



# Hypotheses

1. new vs. old users
2. articulated relationship
3. accumulating (dis)advantage


## Uncertainty about identity

<img src="https://docs.google.com/drawings/d/1gSeIm9BurDLtKDdQKEx92sbGXVZW3JAX4X15X8wrV4w/pub?w=960&amp;h=720" style="max-width:70%; background-color: white;">


## Articulated Relationship

* friends
* enemies
* no relationship


## You are how you're rated?

Usually seen next to high scores &rarr; helpful identity.

Usually seen next to low scores &rarr; harmful identity.


## New users

<img src="img/figures/signups.png">


## New vs old viewers
<img src="img/figures/web.new.user.effect.png">
<p><small>New viewer subgroup: 4.6x10^5 exposures</small></p>



## New vs old commenters

<img src="img/figures/web.new.author.effect.png">
<p><small>New commenter subgroup: 4.9x10^5 exposures</small></p>



## Articulated Relationship

<img src="img/figures/web.rel.effect.png">



## Influence of Prior Score Cues

<img src="img/figures/web.updn.by.scorestate.png" style="max-width:60%">


## Influence of Prior Score Cues

<img src="img/figures/web.tnps.by.scorestate.png" style="max-width:60%">


## Influence of Prior Score Cues

<img src="img/figures/web.rp.by.scorestate.png" style="max-width:60%">



## Findings

1. rating and reply behavior are altered by identity
2. for active commenters, identity seems to improve ratings
3. new users creating accounts out of spite?
4. tenured users strongly biased against new users
5. strong identity effects for users with articulated relationships
6. associated bad scores hurt ratings, good scores help replies

<p style="margin-top: 40px"><strong>A mechanism for cumulative advantage in ratings?</strong></p>