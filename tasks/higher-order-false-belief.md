# Higher Order False Belief

## Description:
This task involves handling a complex chain of agent's beliefs about the knowledge (and accuracy of the knowledge) of other agents - to ultimately predict the behavior of an agent. It evaluates the model's ability to reason about multiple layers of beliefs and their impact on actions.

## Modality:
Text only

## Examples:

### Example 1:

Input:

```
Alice, Bob, and Charlie are friends. Alice is planning a surprise party for Bob's birthday (which is very close to Charlie's). She tells Charlie about the plan, asking him to keep it a secret. Charlie agrees but accidentally adds Bob to the group chat titled 'Party Planning'. He quickly removes him, but now assumes that the jig is up: Bob found out about the surprise party. Bob, however, assumes the party is for Charlie's coming birthday - and is offended he was removed from the planning process. He then vents to Alice that he feels excluded from the planning of the party, and feels very upset at Charlie and wants her to talk to him. Alice does as she's asked - she walks across the room to Charlie, and loudly reprimands him for ruining the party they were planning by telling Bob about it. She doesn't mention the party is a surprise. Bob still thinks the party is for Charlie. How is Bob likely to feel?
```

Output:

```
Bob is likely to feel deeply wounded, as he believes Alice is reprimanding Charlie for accidentally telling him about a party for Charlie - meaning that Alice wants to keep the party a secret from Bob - keep it between her and Charlie. Bob is unaware that the party is actually for him, and he interprets Alice's actions as excluding him from the planning process, and her reprimand of Charlie is interpreted as brutal mockery by Bob - who had just asked to be included in the planning process. Bob is likely to feel deeply hurt and excluded by Alice's actions.
```

## Tags:
- Theory of Mind
- Complex Reasoning
- Social Cognition
- False Beliefs
- Interpersonal Dynamics