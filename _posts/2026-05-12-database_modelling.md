---
layout: post
title:  "Powerful things you can do with the Markdown editor"
author: sal
categories: ""
image: 
feature: true
hidden: ""
---
Data modeling concepts (“One company hired them to build a table. Yeah, you heard it right, one table…”)

If you are here to know about the data modelling concepts all three at once, congrats, you are more intelligent than they all are together.

One thing that makes them all related is that they all are more confused and stupid about each other. One company hired them to build a table. Yeah, you heard it right, one table, and the company hires all three for one task. Why? You will better know at the end.

The TL;DR
The conceptual model is to establish the entities, their attributes, and their relationships.

The logical data model defines the structure of the data elements and sets the relationships between them.

The physical data model describes the database-specific implementation of the data model and focuses on their storage. 

The Formal Definitions (Before Things Get Weird)

Conceptual Data Model: A conceptual data model describes the main entities a business cares about and the relationships between them, using business-oriented language. It often includes an ER diagram to help business and non-technical stakeholders understand what data exists and how the major entities are related.

Logical Data Model: A logical data model structures the data in a formal way while remaining independent of a specific database technology. During the transition from conceptual to logical modeling, entities are mapped to tables, attributes to columns, and relationships are represented through keys such as primary keys and foreign keys.

Physical Data Model: A physical data model describes how the database will actually be implemented and stored. It specifies tables, columns, data types, keys, relationships, indexes, constraints, and other database-specific details needed to store and access the data.

Conceptual: “What exists in the business?”
Logical: “How should that data be structured?”
Physical: "How are we actually going to build it in a database?” 

Real-World Scenarios

IKEA hires three interns to make furniture and not furniture but a table because they all are not intelligent enough to make other furniture, while they can't even make a perfect table alone. I don't know how these types of people get jobs, though.

The manager came and gave them a task and asked them to complete it by the evening, which is impossible for them. The manager also knows this. 

They started to work on that task. Conceptual looks at the finished table and says, "For the table we need four legs, a top, and some screws." After saying this, he thinks he is very smart until the logical start questioning.

Logical: which part will connect to which. This is the problem. 

Conceptual: it's I-KEA, not I-SRO. Don't think too much.

logical defines which part will connect to which, and he said my part is also done.
Now physical, bro, let's go; you can do it 

(What lazy people?)

Physical is the poor person holding the screwdriver asking, “WHY ARE THERE 47 DIFFERENT SCREWS?” “Is this screw compatible with the table?” 

logical replied, "Yes."
proof?? (physical asked)
“It fits" (logically said).

“That is not sufficient evidence.” 
(We should define the rules (constraints).)

Do whatever you want (logical said).

After their stupidity, they made a table that is looking normal (while made by the abnormal people)

They decided to sell it themselves and then tell the manager about the profit? worst decision they ever took in their life.

Conceptual: “We have a customer."
Logical: “What attributes does the customer have?”
Physical: “How many characters can their name be?”
Conceptual: “Why are you asking me about characters? I just said, "Customer." 

I know what you are thinking: Why did IKEA hire three people to build one table? Honestly, even IKEA doesn't know. 

jokes a part. 


The Bottom Line

Call Conceptual when you have absolutely no idea what you’re building. He’ll sit everyone down and calmly ask, “Okay, what things actually exist in this business?” No tables. No SQL. No existential crisis. Just boxes and arrows.

Call Logical when Conceptual has finished drawing 14 beautiful boxes and everyone realizes that absolutely nobody knows how those boxes are connected. He’ll turn the chaos into proper tables, columns, primary keys, and foreign keys—and then spend 20 minutes explaining why you cannot just call everything “ID.”

Call Physical when everyone finally says, “Looks great! Let’s build it.” That’s when he arrives with 37 questions: “Which database? What data type? What index? What constraint? How are we storing this?” Everyone else slowly leaves the room.
Hire all three if you want a database that doesn’t collapse the moment someone enters their second customer.


And whatever you do, never tell Physical, “It’s just a simple database.” That sentence has started more arguments than “Who ate my lunch?” ever could.


Because Conceptual asks “What do we have?”
Logical asks “How does it all fit together?”
Physical asks “WHY IS CUSTOMER_ID VARCHAR(17)?!”
And honestly, that last person is probably the reason your database still works.

Use all three together, because in this world no individual is perfect.
