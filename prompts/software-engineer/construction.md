# Construction

## Domain (component) model creation
------
Your Role: You are an experienced software engineer. Before you
start the task as mentioned below, please do the planning and
write your steps in an design/component_model.md file with
checkboxes against each step in the plan. If any step needs my
clarification, please add it to the step to interact with me and get
my confirmation. Do not make critical decisions on your own.
Once you produce the plan, ask for my review and approval. After
my approval, you can go ahead to execute the same plan one step
at a time. Once you finish each step, mark the checkboxes as done
in the plan.
Your Task: Refer to the user stories in the
design/seo_optimization_unit.md file. Design the component
model to implement all the user stories. This model shall contain
all the components, the attributes, the behaviours and how the
components interact to implement the user stories. Do not
generate any codes yet. Write the component model into a
separate md file in the /design folder.
<<<After reviewing and changing the plan>>>>
I approve the plan. Proceed. After completing each step, mark the
checkbox in your plan file

##: Code Generation
------
Your Role: You are an experienced software engineer. Before you
start the task as mentioned below, please do the planning and
write your steps in an md file with checkboxes against each step
in the plan. If any step needs my clarification, please add it to the
step to interact with me and get my confirmation. Do not make
critical decisions on your own. Once you produce the plan, ask for
my review and approval. After my approval, you can go ahead to execute the same plan one step at a time. Once you finish each
step, mark the checkboxes as done in the plan.
Task: Refer to component design in the
search_discovery/nlp_component.md file. Generate a very
simple and intuitive Python implementation for the Natural
Language Processing (NLP) Component that is in the design. For
the processQuery(queryText) method, use amazon bedrock APIs
to extract the entities from the query text. Generate the classes
in respective individual files but keep them in `vocabMapper`
directory.
Refer to the generated codes in vocabMapper directory. I want
the EntityExtractor component to make a call to GenAI. The
current implementation uses the local vocabulary_repository.
Can you analyse and give me a plan on how I can leverage GenAI
for both the Entity Extraction and Intent Extraction.