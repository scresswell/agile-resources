Getting started with Kanban






Lean Software Development and Kanban have their history in manufacturing and the work done by one company, in particular, Toyota Motor Corporation. In its effort to economically mass-produce affordable motor vehicles for people after the Second World War, Toyota made profound changes to the way it organised its production line.

Toyota realized early on that there was a significant waste in manufacturing, which added to the overall cost. They implemented two notable changes to typical mass production lines, which had a profound effect on reducing costs and significantly increasing quality.

1. Reduce all waste which didn't add value to the customer

2. Focus on single-piece flow through the production line using a pull system

Reducing waste
Waste was identified at multiple levels, for example, overproduction of a particular part was seen as waste for two reasons. Firstly, space was needed to stockpile the part until it could be used. This cost money not only for storing it but also took up floor space that could be used for production. Secondly, sometimes problems in the manufactured parts weren't found until they were combined with other parts and put to use further down the production line. If a problem were discovered that required the entire batch to be re- machined or re-manufactured, this would add significant time and money.

Single-piece flow
In a production line environment, there are multiple workstations each of which takes the work of preceding stations and combines it or enhances it before passing it on to the next workstation. In this way, each station adds value and passes it further down the production line until the product being built is complete.

In a traditional product line environment, the work was pushed from one station to the next. Sometimes the work was sent in batches. For example, the machine that built widget A, with some amount of retooling, also built widget B. Rather than lose time due to retooling, if you built batches of say 100 at a time, the machine operation was more efficient.

This can create unevenness in the production line, which can lead to fluctuations in the flow; sometimes a station further down the line could be waiting for the previous station to complete a batch of Widget As and retool because it needs two Widget Bs.

To solve these problems, Toyota perfected a system called Kanban. A Japanese word meaning signboard, Kanban is used in lean manufacturing to signal when a piece of work needs to be done. The profound change that Toyota's employee Taiichi Ohno implemented in this signaling system was to reverse the flow of information on the production line. This means that stations further down the production line would send Kanban signals to the stations behind them that they needed certain parts made.

The following figure shows how a Lean Production Line works:





A Lean Production Line waits until there are orders for its product because the communication channel is reversed. The order being placed is a signal to the end of the production line that it needs to deliver more finished products. It does this by sending requests to the stations preceding it in the production line so that they can make and assemble the necessary parts for it to deliver a finished product.

The reversed flow creates a pull rather than push approach to manufacture and changes the dynamic of the system to focus on the whole system's end-to-end flow. In layman's terms, this means that each station on the production line is concerned with carrying out the request it receives as promptly as possible to ensure the next station ahead of it is also able to do so.

Each station only carries out the work when it is requested; this is the Just in Time (JIT) of lean manufacturing. In any time between servicing requests, the workers at the station can clean their station and prepare themselves for any potentially busy periods ahead. They can also use this time to see if there is anything they can do to improve their process.

It is the responsibility of the entire production line to smooth out any unevenness in the flow. Workers should not try to compensate by deliberately operating their station even though they have no work requests, as this leads to unnecessary overproduction and stockpiling of inventory.



Introduction to the mechanics of Lean/Kanban
Here are the basic characteristics and features of Lean/Kanban:

Planning style: Lean/Adaptive

Delivery Style: Flow/Incremental

Iteration length: Doesn't have time-boxed iterations

Principles: Eliminate waste, amplify learning, decide as late as possible, deliver as fast as possible, empower the team, build integrity in, see the whole

Roles: Not prescribed, existing roles

Team size: Not prescribed

Artefacts: Kanban (message board)

Events: Andon (stop the line), Gemba (go and see), Improvement Kata

Special features: Kaizen (Continuous Improvement), makes work visible, limits work in progress, works with your existing process, makes policies explicit, evolves empirically

Lacks: A clear process framework of its own; instead it asks that we make our existing process visible and use the principles of Lean to continuously improve it using small incremental changes



There are no explicit roles defined by Kanban; assuming you have everyone necessary to do the job you've been asked to do, this is sufficient.

Start with your existing process. Map the workflow on a wall, making it visible so that everyone sees it. Use this sudden wealth of information on how your system works to makes changes and bit by bit evolve it into something that works better.



Getting started with Kanban
There are four steps to implementing Kanban within your team:

Step 1 – Make the team's work visible
This involves creating a board that reflects the current process the team uses to deliver software. The work that the team currently has in progress and the stage it's at also needs to be shown. The easiest way to do this is to write down each work item on an index card and place it in the appropriate area of the board.

For example, a Kanban board for a team with a simple workflow would look something like this:











Step 2 – Make the work policies of the team explicit
Teams often handle this by placing entry and exit criteria for each column to make them transparent. This will look something like the following:









The policies form what is commonly known as the Definition of Done (DoD). The DoD is a checklist that the team applies to each work item. It is a way for the team to ensure they've completed the work item to a satisfactory standard and therefore ensure they are the baking quality of their product.

Step 3 – Improve flow
With Kanban, as with the other Agile approaches, we want to add value as soon as we can, by delivering useful software as fast as possible. The reason for this is two-fold:

Most people don’t know what they need until they see it. It's hard to imagine how the software will look and behave until it's built. Everyone has a different version of it in their head. Once you have something working, you can start to get feedback from your customer. This is when the real work begins.

The domain we’re operating in is rapidly evolving. In business terms, 6 to 12 months is too long to wait for something. The way the business works and the rules that govern it could have easily changed within such a timeframe.



For work to start to flow across the board, we have to do two things:

The first step is to reduce the size of each work item so that it is as small as possible. Taiichi Ohno called this reducing the waste of unevenness (Muri). For us in the software industry, unevenness is reduced by managing and reducing probable variability, which we can also manage by keeping the work item as small as possible. This doesn't mean that we're eliminating all variability, just reducing the amount.

The second step is to switch to small batches. This can either be done as Scrum or XP does, using Sprints or Iterations. Alternatively, the more granular way is to start to manage Work In Progress (WIP) limits so that the team can focus their effort on the items currently being worked on and avoid the loss of time caused by context switching when multitasking. Assuming the items have been prioritized by value, this allows them to focus on completing the high-value items first.



Rather than thinking and working in iterations, the focus in Kanban is on optimizing the flow of work items through the system. To optimize flow two shifts in thinking have to happen. Firstly, we need to think of the system as a whole, the end-to-end process from idea to delivery of the implementation of that idea.

Secondly, instead of pushing the work through the system, we have to think of the system as pulling the work through it. When the system has the capacity, it pulls the next piece of work into it to be worked on.



This requires careful control; the aim is to avoid large batches of work that move as one block as this only encourages optimization at the local level.

Instead, we carefully manage WIP and prevent overcapacity by limiting the number of items being worked on at any given moment:



The following shows a Kanban board where our team has mapped out every step of the process:






Visualizing your work in this way will soon help you identify when there is too much work in progress.

To identify where you might have flow issues in your process, you can map your entire process out so that the entire process is explicit. This is similar to a technique known as Value Stream Mapping, but where a Value Stream Map is a snapshot in time, modeling your Kanban board precisely to your Value Stream allows you to observe and iron out any problems in flow in real time.



For example, the team using the Kanban board in the following figure have identified that they have too much work to test and this is causing a logjam:





Blocks like this can have quite subtle effects. One observed result of allowing work to accumulate is to put all of the work items in the column into a single batch. We can then create a single software deployment and carry out testing on all the items at once. We think this will create efficiency in our testing, which it may do at a local level. However, with five work items in that column, the reality is that each work item will delay the others as we wait for testing to complete. If we find any problems with one or two them, the whole batch will be delayed and the overall flow will be significantly reduced.



To tackle this, determine if this is a one-off or whether a pattern is emerging. Either way it is important to take pressure off the people who are currently testing, by swarming on the work as a team. Once the workload is back to normal, the team can prevent this from happening again by placing a WIP limit on the test column. The following figure shows a Kanban board with WIP limits set:







Step 4 – Kaizen or continuous improvement
Once the team is up and running with the preceding three steps, the next thing for them to implement is Kaizen.

Kaizen is a Japanese word meaning continuous improvement. It is similar in concept to Scrum and XP's retrospective event. Our team is encouraged to take time to reflect on their work regularly, and where possible identify improvements to the way they carry it out.

An improvement event can be triggered in the following circumstances:

A priority problem occurs which our team have to fix immediately. The team should go about fixing the immediate problem and then carry out a root cause analysis of the issue to see what they can do prevent this kind of problem occuring again.

When we have slack in our schedule, our team should take time to see what it can improve in it’s process. This involves looking at improving the way we work and includes our tooling. In particularly we should focus on automating as much of our mundane/repetitive tasks as possible.


One key aspect of this is taking time to keep things in order, and includes tidying our board as well as our work area. Something often during this “housekeeping”
