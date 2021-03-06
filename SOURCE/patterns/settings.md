---
layout: page
title: 设置
permalink: settings.html
---

#设置

##设置
应用设置允许用户指出他们对应用行为的偏好。它们授予用户真实的控制感，并且在避免被同样的问题重复地打断方面有用处。  

###访问设置
设置在用户界面中突出程度很低，因为他们并不经常被用户使用。当你的引用使用设置时：在任何情况下，访问“设置”的控件都应简单标识为“设置”。如果当前的页面支持一个左导航栏，把设置放在导航栏除“帮助及反馈”外的所有物件的下方。另外，如果当前页面里有工具栏，把设置放在工具栏的“溢出（overflow）”控件里，并且在除“帮助及反馈”外的所有物件的下方。  

###合理使用设置
当用户访问设置时，不管多么不频繁，他们对这个页面都抱有与其他页面一样的期待。这个页面应该是安排良好和可预测的。需要特别指出的是，它应该避免用过多的选项淹没用户。避免这样的诱惑：通过向“就把它作为一个设置吧”的欲望屈服的方式，来把艰难的产品决定推掉。对于每个你考虑要放入设置里的控制，通过问下列问题来确保它合适：这确实是一个用户偏好吗？信息和动作不是一个用户 偏好。如果不是用户偏好，就不要把它当做一个设置。如果它是应用的静态信息（比如版本号，服务条款，开源证书），将它组织到一个帮助页面里。如果它是一个动作（比如刷新，切换账号），在你的应用的主要流程中为它找一个合适的位置。这个选项经常被用户改变吗？用户每次访问这个控件要多次操作会觉得负担重吗？如果是这样，不要把它作为一个设置。让这个控件更容易使用到，可能通过把它放在工具栏或是溢出（overflow）菜单里面。会有少于20% 的用户改变这个设置的值吗？如果是这样，不要将它作为一个设置。不管是新的还是本来就有的设置，都应该问这些同样的问题。对于已经存在的设置，最后一个问题应该多考虑一些：如果这个设置项被移除了，这会对那些不再能改变这一设置项的少数用户造成危害吗？如果会，或者你不清楚，那么合适的做法是将它作为一个设置项保留。  

###分组的设置
当你有很多设置项时，通过给它们分类来把一个长列表变成几个短一些的列表。  

###7个或少于7个设置项
一点都不要分类。

###8至10个设置项
试着将设置项放在一个或两个节分隔块（section divider）下。如果你有一些“单个设置”（与其他设置项无关的设置项，并且不能归类到在你的章节里），根据下面的方法来处理它们：   
*如果它们中包含一些你最重要的设置项，把它们放在最顶上，但不用节分隔块（section divider）分隔。   
*否则，将它们按重要程度的顺序放在末尾，用一个节分隔块（section divider）分隔。    

###11至15个设置项
建议同上，不过试着用2到4个节分隔块（section divider）分隔。   
同样，寻找“双子选项”：两个设置项互相相关，但与其他设置项无关。试着把它们合并为一个设置项。比如你也许可以把两个相关的复选框设置项重新设计为一个多项选择设置项。  

###16个以上的设置项
如果你有四个以上的设置项相关的情况，把它们分在一个子屏里。把上面说的规则应用到每个子屏里。  

###选择默认项 
用户会期望每个设置项的初始值都符合情理。以下问题可以帮助你做决定：在没有默认选项时，用户自己最有可能选择的选项是哪个？哪个选项最中立或最中庸？哪个选项风险、争议或言过其实的可能性最小？哪个选项用的电量和移动数据最少？哪个选项最尊重用户的注意力，只在最重要的时候打断用户？