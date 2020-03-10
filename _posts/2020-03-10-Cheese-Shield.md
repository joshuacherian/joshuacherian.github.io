---
title: Cheese Shield&#58; A User's Guide to Aerobraking with Dairy
date: 2020-03-10 00:17:41
---

Have you ever wondered what would happen if a spacecraft returning to Earth attempted to replace its heat shield with an equally protective layer of cheese? Have you ever pondered how much cheese would even be necessary for such a task, or what cheese would perform the best under these circumstances? Then you've come to the right place! 

I'm not the first to combine the worlds of cheese and space. SpaceX launched [a wheel of Le Brouere](https://www.space.com/10459-wheel-cheese-launched-space-private-spacecraft.html) back in 2010, and the ISS recently received a shipment of [cheddar and manchego.](https://nypost.com/2020/02/17/iss-astronauts-getting-delivery-of-cheese-skittles/) I do believe I'm the first to, however, to estimate the feasibility of using it as a thermal protection system. Some of my incredibly nerdy friends posed this question in a conversation last month, and I haven't been able to stop thinking about it. So, being the aerospace engineering student/space nerd that I am, I had to find an answer. Surprisingly enough, no one has published any research on the topic. Given what I could find, though, I think I have a reasonably accurate estimate, short of physical field testing.

### Define the Problem

When designing a new system or attempting to solve a problem, it's paramount to define your constraints and requirements. For example, a customer may ask you to design "the best plane ever." But your definition of best may not match theirs. You might think the best plane has the most powerful engine while they think the best plane has the highest fuel efficiency. This is why we need to constrain our problem; if we don't we'll end up on tangents that are completely irrelevant to the issue and wonder why we spent two hours on forum threads discussing mandolin tuning. 

This problem is effectively twofold. First, we need to determine how strong traditional heat shields are. This might be measured in a variety of ways, such as peak temperature, ablation rate, etc. Effectively we're asking, "What makes a good heat shield?" Next, we use that information to determine our optimal cheese characteristics. Therefore, it's important that the metric we decide on in the first part of the problem translates to something we can calculate in the second half.

### Heat Shields
To get my numbers for the ideal heat shield, I decided to go back to the darling of NASA's history: the Apollo program. Everyone who went to the moon returned alive, and that's thanks in no small part to the heat shield on the underside of the Command Module. 

NASA is a government institution, which means that practically everything (barring classified material) is available to the public. This provided the perfect source for my work. Where better to go than to the people who made Apollo? I began researching and eventually stumbled upon [NASA TN D-7564 - "Apollo Experience Report: Thermal Protection Subsystem"](https://ntrs.nasa.gov/search.jsp?R=19740007423). This report is a fascinating look into the development of the heat shield system used on the Apollo missions, including design requirements, assembly, testing procedures, and real-world results.

The report provided me with an ideal metric: heat load. Engineers wanted to know how hot the module would get (because they would be sticking humans inside), so they measured the heating rate during reentry in units of Btu/ft^2-sec. This gave them data points; integrating gives the total heat load in Btu/ft^2. Table III in the Technical Report provides a wealth of reentry information for 8 Apollo missions: Apollo 8 and Apollos 10-16. The highest heat load was experienced by Apollo 16, clocking in at just shy of 28,000 Btu/ft^2. I should note that the true unit of heat is not normalized by surface area, so to get rid of that term, I calculated the surface area of the underside of the Command Module (~130 ft^2). Finally, we can get the amount of heat applied to the Module: 3.64 million Btu. Earlier, I said that we needed a metric that could be easily transferred to the second half of our problem. This is where unit conversions are our friends! In SI units, we have an answer of 3.84 billion joules.

### Say Cheese!
Since cheese will most likely be an ablative heat shield (meaning it will vaporize in the atmosphere due to the intense heat), it would be good to know how much heat it can handle before it vanishes. Here's where chemistry class kicks in. You may remember the enthalpy of vaporization, which is basically a measure of how much heat is required to vaporize a substance. For some odd reason, no one has measured this for cheese of any kind. But not to fear! [An article](https://www.jstage.jst.go.jp/browse/nskkk/-char/en) in Nippon Shokuhin Kagaku Kogaku Kaishi, a Japanese food science journal, calculated the enthalpy of vaporization of milk. The article is entirely in Japanese with the exception of the tables and figures, which are in English. From that, I can at least get a ballpark estimate: 2000 J/g of milk. Using that as a proxy for cheese, we need 1,920,000 grams of cheese. Tack on a safety margin of 20%, and we end up with a final answer of **2,304,000 grams or 5079 pounds of cheese.**

The most important question still remains: which cheese will make the best heat shield? I'm going to make one simplifying assumption here: all cheeses have the same enthalpy of vaporization. While this probably isn't true, there aren't any other numbers I can use for a better comparison. Therefore, the main thing that will separate these cheeses is density. [A 2012 paper](https://onlinelibrary.wiley.com/doi/pdf/10.1111/jfpe.12008) in the Journal of Food Process Engineering has data for several cheese densities; I've selected a few of the more popular varieties below.

| Cheese        | Density(g/m^3) |
|---------------|----------------|
| Cream cheese  | 1.014          |
| Cottage       | 1.04           |
| Gouda curd    | 1.043          |
| Colby         | 1.05           |
| Mozzarella    | 1.062          |
| Monterey Jack | 1.09           |
| Cheddar       | 1.102          |
| **Romano**    | **1.21**       |

To minimize the space taken up by the heat shield, Romano is an ideal solution. This doesn't take into account other important factors. Would Swiss, with its sporadic holes, hold its structure better than crumbly feta? Would an extremely high moisture cheese like Neufchatel fare better or worse than a hard cheddar? And we haven't even gotten started on goat vs. cow milk. But most importantly, which would function as the best dip? The astronauts on board could be on the verge of the greatest queso, provided they bring enough chips.

Of course, we shouldn't forget that we're using the Apollo missions as our benchmark, which provides us with one distinct advantage: we're going to the moon. And since the moon is made entirely of cheese (Swiss, according to a highly informal survey conducted among students at one of the top engineering schools in the country), we could simply go the route of in-situ resource utilization and harvest our own lunar cheese heat shield.

### Conclusion

How does all of this measure up to the original? According to the NASA paper we referenced earlier, the Apollo Block II thermal shielding weighed around 1500 pounds, making our cheesy heat shield over 3 times heavier. So while Neil, Buzz, and Michael didn't get to enjoy a toasty Gruyere after splashing down in the Pacific, perhaps future generations will be able to. After all, space technology just keeps getting cheddar and cheddar. (Sorry, I had to sneak at least one cheesy pun in there!)