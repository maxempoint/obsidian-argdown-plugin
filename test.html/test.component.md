<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/npm/@argdown/web-components/dist/argdown-map.css"><script src="https://cdn.jsdelivr.net/npm/@webcomponents/webcomponentsjs/webcomponents-bundle.js" type="module"></script><script type="text/javascript" src="https://cdn.jsdelivr.net/npm/@argdown/web-components/dist/argdown-map.js"></script><figure  role="group" class="argdown-figure"><argdown-map      initial-view="map"><div slot="source" class=""><pre class="language-argdown"><code class="language-argdown"><span class="hljs-meta">===
title: Why the Fed didn&#x27;t Intervene to Prevent the 2008 
    Financial Crisis
subTitle: An Analysis of Alan Greenspan&#x27;s Arguments  
author: 
    - Michael Schefczyk (argument analysis)
    - Gregor Betz (adaptation to Argdown)
date: 19/10/2018
group:
    regroup:  [{
            title: &quot;Subdebate about the existence of bubbles&quot;,
            statements: [&quot;Bubbles impossible&quot;],
            arguments: [&quot;Turnover Argument&quot;, 
            &quot;Speculative Conflagration Argument&quot;]
            },
            {
            title: &quot;Subdebate about the consequences of bubbles&quot;,
            statements: [&quot;Local bubbles harmless&quot;],
            arguments: [&quot;Spatial Fragmentation Argument&quot;, 
            &quot;Diversification Argument&quot;]
        }]
dot: 
    graphVizSettings: 
      &quot;rankdir&quot;: &quot;TB&quot;      
color:
    colorScheme: colorbrewer-set3
    tagColors:
        basic: 4
        concession: 2
===</span>


<span class="hljs-comment">//  This Argdown document has been adapted from:</span>
<span class="hljs-comment">//  Schefczyk, Michael, 2016, &quot;Financial markets: </span>
<span class="hljs-comment">//  Applying argument analysis to the stabilisation </span>
<span class="hljs-comment">//  task&quot;, in: Gertrud Hirsch-Hadorn &amp; Sven Ove </span>
<span class="hljs-comment">//  Hansson (eds): The Argumentative Turn in Policy </span>
<span class="hljs-comment">//  Analysis , Logic, Argumentation &amp; Reasoning 10, </span>
<span class="hljs-comment">//  pp. 265-290. </span>


In the run-up to the financial crisis in 2008, Alan Greenspan 
put forward a variety of arguments for the following claim:

<span class="hljs-statement-title">[Against Preemption]:</span> Policymakers should not implement 
preemptive policies against bubbles. <span class="hljs-tag">#basic</span>

Greenspan argued for this claim by saying that there is no 
need for such preemption because there are no bubbles and 
because potential bubbles would be harmless anyway.

<span class="hljs-statement-title">[Against Preemption]</span>
<span class="hljs-support">  +</span> <span class="hljs-argument-title">&lt;No bubbles, no preemption&gt;:</span> There is no need for 
  preemptive policies against bubbles because there are no 
  bubbles on the housing market in the first place. <span class="hljs-tag">#basic</span> 
<span class="hljs-support">  +</span> <span class="hljs-argument-title">&lt;Harmless bubbles, no preemption&gt;:</span> There is no need for 
  preemptive policies against bubbles because any potential 
  bubbles are, macroecoomically speaking, harmless. <span class="hljs-tag">#basic</span> 

At various occassions, Greenspan put forward sophisticated 
arguments that back one of these basic reasons against 
preemptive policies.

<span class="hljs-section"># Greenspan&#x27;s Arguments in 2002 {isGroup: false}</span>

To start with, Greenspan presented what one might call the 
@<span class="hljs-argument-title">&lt;Turnover Argument&gt;</span> in a testimony before the Joint Economic 
Committee of the US Congress on 17 April 2002:

    &quot;The ongoing strength in the housing market has 
    raised concerns about the possible emergence of 
    a bubble in home prices. However, the analogy 
    often made to the building and bursting of a stock 
    price bubble is imperfect. <span class="hljs-tag">...</span> Unlike in the stock 
    market, sales in the real estate market incur 
    substantial transactions costs and, when most homes 
    are sold, the seller must physically move out. Doing 
    so often entails significant financial and emotional 
    costs and is an obvious impediment to stimulating a 
    bubble through speculative trading in homes. Thus, 
    while stock market turnover is more than 100 percent 
    annually, the turnover of home ownership is less 
    than 10 percent annually--scarcely tinder for specula- 
    tive conflagration.&quot; 

The @<span class="hljs-argument-title">&lt;Turnover Argument&gt;</span> justifies the view that under normal 
circumstances there are no bubbles in the real estate market.

<span class="hljs-argument-title">&lt;Turnover Argument&gt;:</span> Substantial transactions costs render 
bubbles unlikely. 

<span class="hljs-argument-statement-nr">(1)</span> Sales in the real estate market incur substantial 
transaction costs.
<span class="hljs-argument-statement-nr">(2)</span> If transaction costs are substantial, the market turnover 
is low.
<span class="hljs-argument-statement-nr">(3)</span> If market turnover is low, no “speculative conflagration” 
develops.
<span class="hljs-argument-statement-nr">(4)</span> If no “speculative conflagration” develops, prices do not 
rise significantly above their fundamentals.
<span class="hljs-argument-statement-nr">(5)</span> If prices do not rise significantly above their 
fundamentals, bubbles cannot occur.
<span class="hljs-inference">--
Modus ponens
{uses: [1,2,3,4]}
--</span>
<span class="hljs-argument-statement-nr">(6)</span> <span class="hljs-statement-title">[Bubbles impossible]:</span>  Bubbles cannot occur in the real 
estate market.
<span class="hljs-support">    +&gt;</span> <span class="hljs-argument-title">&lt;No bubbles, no preemption&gt;</span>

In the following passage, taken from the same testimony, 
Greenspan addresses a further difference between the stock 
market and the real estate market.

  &quot;A home in Portland, Oregon is not a close substitute 
  for a home in Portland, Maine, and the “national” 
  housing market is better understood as a collection of 
  small local housing markets. Even if a bubble were to 
  develop in a local market, it would not necessarily 
  have implications for the nation as a whole.&quot;

The argument in this passage shall be called the 
@<span class="hljs-argument-title">&lt;Spatial Fragmentation Argument&gt;</span>. 

<span class="hljs-argument-title">&lt;Spatial Fragmentation Argument&gt;:</span> As housing markets are 
local, bubbles will have no substantial effects on the U<span class="hljs-tag">.S.</span> 
economy as a whole.

<span class="hljs-argument-statement-nr">(1)</span> The US housing market is a collection of local markets.
<span class="hljs-argument-statement-nr">(2)</span> <span class="hljs-statement-title">[Local bubbles harmless]:</span> It is unlikely that bubbles in 
local markets have strong detrimental effects on the economy 
of the whole nation.
<span class="hljs-inference">--
Universal instantiation, Modus ponens
{uses: [1,2]}
--</span>
<span class="hljs-argument-statement-nr">(3)</span> It is unlikely that bubbles on the US housing market have 
strong detrimental effects on the economy of the whole nation.
<span class="hljs-support">    +&gt;</span> <span class="hljs-argument-title">&lt;Harmless bubbles, no preemption&gt;</span>

<span class="hljs-section"># Greenspan&#x27;s Arguments in 2005 {isGroup: false}</span>

In a testimony before the Joint Committee on 9 June 2005, 
Greenspan retreated from the @<span class="hljs-argument-title">&lt;Turnover Argument&gt;</span>, which had 
proved untenable in the light of new developments.

  &quot;In recent years, the pace of turnover of 
  existing homes has quickened. It appears that 
  a substantial part of the acceleration in turnover 
  reflects the purchase of second homes— either 
  for investment or vacation purposes. Trans-
  actions in second homes, of course, are not 
  restrained by the same forces that restrict the 
  purchases or sales of primary residences -- an 
  individual can sell without having to move. This 
  suggests that speculative activity may have had 
  a greater role in generating the recent price 
  increases than it has customarily had in the 
  past.&quot;

Surging home turnover and a steep climb in home prices 
contradict premises (1) and (2) of the @<span class="hljs-argument-title">&lt;Turnover Argument&gt;</span> 
of June 2002. Greenspan now argues for exactly the opposite 
conclusion:

<span class="hljs-argument-title">&lt;Speculative Conflagration Argument&gt;:</span> As the transaction 
costs of the sale of second homes are low enough to allow 
for high turnover and speculative activity, bubbles can 
develop. <span class="hljs-tag">#concession</span> 

<span class="hljs-argument-statement-nr">(1)</span> Sales of second homes do not incur substantial 
transaction costs. 
<span class="hljs-argument-statement-nr">(2)</span> If transaction costs are not substantial, the market 
turnover can be high.
<span class="hljs-argument-statement-nr">(3)</span> If market turnover can be high, “speculative 
conflagration” can develop.
<span class="hljs-argument-statement-nr">(4)</span> If speculative conflagration can develop, prices can rise 
significantly above their fundamentals.
<span class="hljs-argument-statement-nr">(5)</span> If prices can rise significantly above their fundamentals,
bubbles can occur.
<span class="hljs-inference">--
Universal instantiation of 2-5 to the housing market, Modus ponens 
--</span>
<span class="hljs-argument-statement-nr">(6)</span> Bubbles can occur in the real estate market.
<span class="hljs-contradiction">    &gt;&lt;</span> <span class="hljs-statement-title">[Bubbles impossible]</span>

However, Greenspan stood fast to the 
@<span class="hljs-argument-title">&lt;Spatial Fragmentation Argument&gt;</span> of 2002. In one passage of 
the 2005 testimony, he added considerations which were meant 
to endorse premise (2) of that argument in view of possible 
objections.

  &quot;Although we certainly cannot rule out home 
  price declines, especially in some local markets, 
  these declines, were they to occur, likely 
  would not have substantial macroeconomic 
  implications. Nationwide banking and widespread 
  securitization of mortgages make it less likely 
  that financial intermediation would be impaired 
  than was the case in prior episodes of regional 
  house price corrections.&quot;

Greenspan hence argues:

<span class="hljs-argument-title">&lt;Diversification Argument&gt;:</span> Nationwide banking and widespread 
securitization of mortgages make it unlikely that financial 
intermediation would be impaired in case house prizes were 
corrected.

<span class="hljs-argument-statement-nr">(1)</span> Nationwide banking and widespread securitization 
diversify the risk of mortgage lenders (in the case of home 
price declines in some local markets).
<span class="hljs-argument-statement-nr">(2)</span> The diversification of risk makes the impairment of 
financial intermediation (in the case of home price declines 
in some local markets) unlikely.
<span class="hljs-inference">--
Transitivity of subjunction/causality
--</span>
<span class="hljs-argument-statement-nr">(3)</span> Nationwide banking and widespread securitization make the 
impairment of financial intermediation (in the case of home 
price declines in some local markets) unlikely.
<span class="hljs-argument-statement-nr">(4)</span> If the impairment of financial intermediation (in the 
case of home price declines in some local markets) is 
unlikely, then it is unlikely that bubbles in local markets 
have strong detrimental effects on the economy of the whole 
nation.
<span class="hljs-argument-statement-nr">(5)</span> Banking is nationwide and securitization is widespread.
<span class="hljs-inference">--
Modus ponens (twice)
--</span>
<span class="hljs-argument-statement-nr">(6)</span> <span class="hljs-statement-title">[Local bubbles harmless]</span>
</code></pre></div><div slot="map">
<!-- Generated by graphviz version 2.47.0 (20210316.0004)
 -->
<!-- Title: Argument Map Pages: 1 -->
<svg width="720pt" height="582pt"
 viewBox="0.00 0.00 720.00 581.57" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(0.99 0.99) rotate(0) translate(4 580.8)">
<title>Argument Map</title>
<g id="clust1" class="cluster">
<title>cluster_1</title>
<polygon fill="#dadada" stroke="#dadada" points="282,-222 282,-442.4 708,-442.4 708,-222 282,-222"/>
<text text-anchor="start" x="382.95" y="-427.6" font-family="arial" font-size="12.00" fill="#000000">Subdebate about the existence of bubbles</text>
</g>
<g id="clust2" class="cluster">
<title>cluster_2</title>
<polygon fill="#dadada" stroke="#dadada" points="8,-216 8,-568.8 274,-568.8 274,-216 8,-216"/>
<text text-anchor="start" x="15.6" y="-554" font-family="arial" font-size="12.00" fill="#000000">Subdebate about the consequences of bubbles</text>
</g>
<!-- n1 -->
<g id="node1" class="node">
<title>n1</title>
<path fill="white" stroke="#8dd3c7" stroke-width="2" d="M474,-282C474,-282 302,-282 302,-282 296,-282 290,-276 290,-270 290,-270 290,-242 290,-242 290,-236 296,-230 302,-230 302,-230 474,-230 474,-230 480,-230 486,-236 486,-242 486,-242 486,-270 486,-270 486,-276 480,-282 474,-282"/>
<text text-anchor="start" x="344.94" y="-268" font-family="arial" font-weight="bold" font-size="10.00" fill="#000000">Bubbles impossible</text>
<text text-anchor="start" x="301.58" y="-251" font-family="arial" font-size="10.00" fill="#000000">Bubbles cannot occur in the real estate</text>
<text text-anchor="start" x="369.94" y="-239" font-family="arial" font-size="10.00" fill="#000000"> market.</text>
</g>
<!-- n3 -->
<g id="node8" class="node">
<title>n3</title>
<path fill="#80b1d3" stroke="black" d="M472,-182C472,-182 300,-182 300,-182 294,-182 288,-176 288,-170 288,-170 288,-118 288,-118 288,-112 294,-106 300,-106 300,-106 472,-106 472,-106 478,-106 484,-112 484,-118 484,-118 484,-170 484,-170 484,-176 478,-182 472,-182"/>
<text text-anchor="start" x="325.98" y="-168" font-family="arial" font-weight="bold" font-size="10.00" fill="#000000">No bubbles, no preemption</text>
<text text-anchor="start" x="315.15" y="-151" font-family="arial" font-size="10.00" fill="#000000">There is no need for preemptive</text>
<text text-anchor="start" x="298.47" y="-139" font-family="arial" font-size="10.00" fill="#000000"> policies against bubbles because there</text>
<text text-anchor="start" x="300.69" y="-127" font-family="arial" font-size="10.00" fill="#000000"> are no bubbles on the housing market</text>
<text text-anchor="start" x="330.99" y="-115" font-family="arial" font-size="10.00" fill="#000000"> in the first place. #basic </text>
</g>
<!-- n1&#45;&gt;n3 -->
<g id="edge3" class="edge">
<title>n1&#45;&gt;n3</title>
<path fill="none" stroke="#00ff00" d="M387.54,-229.76C387.34,-218.65 387.09,-205.22 386.86,-192.36"/>
<polygon fill="#00ff00" stroke="#00ff00" points="390.36,-192.16 386.68,-182.22 383.36,-192.29 390.36,-192.16"/>
</g>
<!-- n5 -->
<g id="node2" class="node">
<title>n5</title>
<path fill="#8dd3c7" stroke="black" d="M688,-394C688,-394 516,-394 516,-394 510,-394 504,-388 504,-382 504,-382 504,-354 504,-354 504,-348 510,-342 516,-342 516,-342 688,-342 688,-342 694,-342 700,-348 700,-354 700,-354 700,-382 700,-382 700,-388 694,-394 688,-394"/>
<text text-anchor="start" x="558.94" y="-380" font-family="arial" font-weight="bold" font-size="10.00" fill="#000000">Turnover Argument</text>
<text text-anchor="start" x="520.03" y="-363" font-family="arial" font-size="10.00" fill="#000000">Substantial transactions costs render</text>
<text text-anchor="start" x="562.27" y="-351" font-family="arial" font-size="10.00" fill="#000000"> bubbles unlikely. </text>
</g>
<!-- n5&#45;&gt;n1 -->
<g id="edge6" class="edge">
<title>n5&#45;&gt;n1</title>
<path fill="none" stroke="#00ff00" d="M553.17,-341.9C521.37,-325.56 479.73,-304.15 446.21,-286.92"/>
<polygon fill="#00ff00" stroke="#00ff00" points="447.48,-283.64 436.99,-282.18 444.28,-289.87 447.48,-283.64"/>
</g>
<!-- n7 -->
<g id="node3" class="node">
<title>n7</title>
<path fill="#bebada" stroke="black" d="M474,-412C474,-412 302,-412 302,-412 296,-412 290,-406 290,-400 290,-400 290,-336 290,-336 290,-330 296,-324 302,-324 302,-324 474,-324 474,-324 480,-324 486,-330 486,-336 486,-336 486,-400 486,-400 486,-406 480,-412 474,-412"/>
<text text-anchor="start" x="307.98" y="-398" font-family="arial" font-weight="bold" font-size="10.00" fill="#000000">Speculative Conflagration Argument</text>
<text text-anchor="start" x="304.92" y="-381" font-family="arial" font-size="10.00" fill="#000000">As the transaction costs of the sale of</text>
<text text-anchor="start" x="300.2" y="-369" font-family="arial" font-size="10.00" fill="#000000"> second homes are low enough to allow</text>
<text text-anchor="start" x="314.09" y="-357" font-family="arial" font-size="10.00" fill="#000000"> for high turnover and speculative</text>
<text text-anchor="start" x="321.31" y="-345" font-family="arial" font-size="10.00" fill="#000000"> activity, bubbles can develop.</text>
<text text-anchor="start" x="357.43" y="-333" font-family="arial" font-size="10.00" fill="#000000"> #concession </text>
</g>
<!-- n7&#45;&gt;n1 -->
<g id="edge5" class="edge">
<title>n7&#45;&gt;n1</title>
<path fill="none" stroke="#ff0000" d="M388,-323.84C388,-313.39 388,-302.34 388,-292.29"/>
<polygon fill="#ff0000" stroke="#ff0000" points="391.5,-292.26 388,-282.26 384.5,-292.26 391.5,-292.26"/>
</g>
<!-- n2 -->
<g id="node4" class="node">
<title>n2</title>
<path fill="white" stroke="#8dd3c7" stroke-width="2" d="M253,-406C253,-406 81,-406 81,-406 75,-406 69,-400 69,-394 69,-394 69,-342 69,-342 69,-336 75,-330 81,-330 81,-330 253,-330 253,-330 259,-330 265,-336 265,-342 265,-342 265,-394 265,-394 265,-400 259,-406 253,-406"/>
<text text-anchor="start" x="114.49" y="-392" font-family="arial" font-weight="bold" font-size="10.00" fill="#000000">Local bubbles harmless</text>
<text text-anchor="start" x="95.6" y="-375" font-family="arial" font-size="10.00" fill="#000000">It is unlikely that bubbles in local</text>
<text text-anchor="start" x="94.21" y="-363" font-family="arial" font-size="10.00" fill="#000000"> markets have strong detrimental</text>
<text text-anchor="start" x="85.58" y="-351" font-family="arial" font-size="10.00" fill="#000000"> effects on the economy of the whole</text>
<text text-anchor="start" x="150.6" y="-339" font-family="arial" font-size="10.00" fill="#000000"> nation.</text>
</g>
<!-- n6 -->
<g id="node5" class="node">
<title>n6</title>
<path fill="#8dd3c7" stroke="black" d="M253,-288C253,-288 81,-288 81,-288 75,-288 69,-282 69,-276 69,-276 69,-236 69,-236 69,-230 75,-224 81,-224 81,-224 253,-224 253,-224 259,-224 265,-230 265,-236 265,-236 265,-276 265,-276 265,-282 259,-288 253,-288"/>
<text text-anchor="start" x="95.04" y="-274" font-family="arial" font-weight="bold" font-size="10.00" fill="#000000">Spatial Fragmentation Argument</text>
<text text-anchor="start" x="82.54" y="-257" font-family="arial" font-size="10.00" fill="#000000">As housing markets are local, bubbles</text>
<text text-anchor="start" x="91.15" y="-245" font-family="arial" font-size="10.00" fill="#000000"> will have no substantial effects on</text>
<text text-anchor="start" x="99.2" y="-233" font-family="arial" font-size="10.00" fill="#000000"> the U.S. economy as a whole.</text>
</g>
<!-- n2&#45;&gt;n6 -->
<g id="edge8" class="edge">
<title>n2&#45;&gt;n6</title>
<path fill="none" stroke="#00ff00" d="M167,-329.76C167,-319.66 167,-308.67 167,-298.36"/>
<polygon fill="#00ff00" stroke="#00ff00" points="170.5,-298.34 167,-288.34 163.5,-298.34 170.5,-298.34"/>
</g>
<!-- n4 -->
<g id="node9" class="node">
<title>n4</title>
<path fill="#80b1d3" stroke="black" d="M256,-188C256,-188 84,-188 84,-188 78,-188 72,-182 72,-176 72,-176 72,-112 72,-112 72,-106 78,-100 84,-100 84,-100 256,-100 256,-100 262,-100 268,-106 268,-112 268,-112 268,-176 268,-176 268,-182 262,-188 256,-188"/>
<text text-anchor="start" x="95.26" y="-174" font-family="arial" font-weight="bold" font-size="10.00" fill="#000000">Harmless bubbles, no preemption</text>
<text text-anchor="start" x="99.15" y="-157" font-family="arial" font-size="10.00" fill="#000000">There is no need for preemptive</text>
<text text-anchor="start" x="85.81" y="-145" font-family="arial" font-size="10.00" fill="#000000"> policies against bubbles because any</text>
<text text-anchor="start" x="120.82" y="-133" font-family="arial" font-size="10.00" fill="#000000"> potential bubbles are,</text>
<text text-anchor="start" x="82.77" y="-121" font-family="arial" font-size="10.00" fill="#000000"> macroecoomically speaking, harmless.</text>
<text text-anchor="start" x="152.77" y="-109" font-family="arial" font-size="10.00" fill="#000000"> #basic </text>
</g>
<!-- n6&#45;&gt;n4 -->
<g id="edge4" class="edge">
<title>n6&#45;&gt;n4</title>
<path fill="none" stroke="#00ff00" d="M167.85,-223.77C168.07,-215.83 168.31,-207.07 168.54,-198.36"/>
<polygon fill="#00ff00" stroke="#00ff00" points="172.05,-198.31 168.82,-188.21 165.05,-198.11 172.05,-198.31"/>
</g>
<!-- n8 -->
<g id="node6" class="node">
<title>n8</title>
<path fill="#8dd3c7" stroke="black" d="M253.5,-538.4C253.5,-538.4 80.5,-538.4 80.5,-538.4 74.5,-538.4 68.5,-532.4 68.5,-526.4 68.5,-526.4 68.5,-462.4 68.5,-462.4 68.5,-456.4 74.5,-450.4 80.5,-450.4 80.5,-450.4 253.5,-450.4 253.5,-450.4 259.5,-450.4 265.5,-456.4 265.5,-462.4 265.5,-462.4 265.5,-526.4 265.5,-526.4 265.5,-532.4 259.5,-538.4 253.5,-538.4"/>
<text text-anchor="start" x="113.33" y="-524.4" font-family="arial" font-weight="bold" font-size="10.00" fill="#000000">Diversification Argument</text>
<text text-anchor="start" x="87.2" y="-507.4" font-family="arial" font-size="10.00" fill="#000000">Nationwide banking and widespread</text>
<text text-anchor="start" x="88.88" y="-495.4" font-family="arial" font-size="10.00" fill="#000000"> securitization of mortgages make it</text>
<text text-anchor="start" x="87.21" y="-483.4" font-family="arial" font-size="10.00" fill="#000000"> unlikely that financial intermediation</text>
<text text-anchor="start" x="78.59" y="-471.4" font-family="arial" font-size="10.00" fill="#000000"> would be impaired in case house prizes</text>
<text text-anchor="start" x="131.66" y="-459.4" font-family="arial" font-size="10.00" fill="#000000"> were corrected.</text>
</g>
<!-- n8&#45;&gt;n2 -->
<g id="edge7" class="edge">
<title>n8&#45;&gt;n2</title>
<path fill="none" stroke="#00ff00" d="M167,-450.24C167,-439.28 167,-427.45 167,-416.29"/>
<polygon fill="#00ff00" stroke="#00ff00" points="170.5,-416.28 167,-406.28 163.5,-416.28 170.5,-416.28"/>
</g>
<!-- n0 -->
<g id="node7" class="node">
<title>n0</title>
<path fill="white" stroke="#80b1d3" stroke-width="2" d="M364,-64C364,-64 192,-64 192,-64 186,-64 180,-58 180,-52 180,-52 180,-12 180,-12 180,-6 186,0 192,0 192,0 364,0 364,0 370,0 376,-6 376,-12 376,-12 376,-52 376,-52 376,-58 370,-64 364,-64"/>
<text text-anchor="start" x="234.38" y="-50" font-family="arial" font-weight="bold" font-size="10.00" fill="#000000">Against Preemption</text>
<text text-anchor="start" x="199.38" y="-33" font-family="arial" font-size="10.00" fill="#000000">Policymakers should not implement</text>
<text text-anchor="start" x="196.04" y="-21" font-family="arial" font-size="10.00" fill="#000000"> preemptive policies against bubbles.</text>
<text text-anchor="start" x="262.16" y="-9" font-family="arial" font-size="10.00" fill="#000000"> #basic</text>
</g>
<!-- n3&#45;&gt;n0 -->
<g id="edge1" class="edge">
<title>n3&#45;&gt;n0</title>
<path fill="none" stroke="#00ff00" d="M349.44,-105.76C338.59,-94.72 326.7,-82.6 315.78,-71.48"/>
<polygon fill="#00ff00" stroke="#00ff00" points="318.27,-69.02 308.77,-64.34 313.28,-73.93 318.27,-69.02"/>
</g>
<!-- n4&#45;&gt;n0 -->
<g id="edge2" class="edge">
<title>n4&#45;&gt;n0</title>
<path fill="none" stroke="#00ff00" d="M212.37,-99.84C221.61,-90.44 231.32,-80.55 240.35,-71.35"/>
<polygon fill="#00ff00" stroke="#00ff00" points="242.92,-73.72 247.43,-64.14 237.93,-68.82 242.92,-73.72"/>
</g>
</g>
</svg>
</div></argdown-map><figcaption>Why the Fed didn't Intervene to Prevent the 2008 Financial Crisis — An Analysis of Alan Greenspan's Arguments</figcaption></figure>