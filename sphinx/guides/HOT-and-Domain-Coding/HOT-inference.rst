.. _HOTinf:

Inference
=========

**Inference:** Deriving a conclusion not otherwise given by using known or logical premises.

Instances of Inference
======================

Inference is the most common type of HOT speech that we code.  These types of speech should be coded as inference.

1.  Causality: Must explictly state the relationship between one event (the cause) and the second event (the effect), where the first event **necessitates** the second event.

* includes most coherent utterances with *because* but **not** children's utterances lacking a clear syntax of cause and effect
  ``try this: get rid of *because* in the utterance. If utterance still has a causal meaning, code as HOT.``

* so can represent a causual relationship
  ``do not code when *so* is used to introduce a topic, this is not causal``
 
 * includes most coherent instances of *how come, why,* and *what for*
 
* includes some instances of *for* as explanation, when glossing to "for the purpose of"
 
  ``do not code when *for* is used to assign one thing to another, such as specific foods for a meal, a person for a social role, or a gift for a party``
 ``try this: turn the utterance into a short dialogue. Use what comes before the *for* as the first line, then pretend a second speaker asks "why?" if the rest of th eutterance makes a coherent and causal resopnse, this is likely HOT-inf.``

* non-temporal *until* can (sometimes) be causal

* non-directional and non-infinitive *to* can (sometimes) be causal
``try this: replace *to* with *in order to*. Does the utterance have the same causal meaning? If yes, then code as HOT.``

2.  *Conditionals:*  Speculation about what could or will happen with predictable cause.

* if/then structure is very important and should be coded
 
 ``if the speaker drops *then,* the utterance can still be HOT-inf.``
 
 ``if the speaker drops the *if/then* structure entirely (e.g. replaces it with a conjunction like *and*, this is not HOT and should not be coded.``

 ``try this: flip the clauses in the utterance. Does the utterance still have a causal meaning? If yes, then the utterance is likely HOT. (e.g. "I'll use this if it's microwave safe" flips to "If it's microwave-safe, then I'll use this" and is still causal).``

* speculation could include keywords like *think* or *doubt*
  
 * this speculation is not HOT if it is probing for a yes/no answer
 * this speculation is not HOT if it is inteneded to halt conversation or direct behavior
 * the speculation can only be coded as inf if there is sufficient evidence in the proximal context
 * if speculation does not have explicitly inferential language, it is necessarily surface, never structure; often a follow-up utterance will contain explicit inf language, but whether that follow-up is surface or structure does not change the speculative utterance to structure.
  
 Surface vs. Structure
 =====================
Inference is the most common HOT speech, so there could be many instances of both surface and structure.

    Code as surface when...
        the cause/effect relationship is cut and dry, easily perceived
        the cause/effect refers to physical sensation (e.g. temperature, hunger, pain)
        the cause/effect relationship is based on knowledge of concurrent or immediate events (e.g. "you broke it because it wasn't broken before)
        there is a "button" relationship explaining what happens but not why (e.g. "when you push the button the clown pops out")
        there is one link or very simple/immediate chain reactions (e.g. "move the block so he can open the door")
        there question is a disembodied why
        
    Code as structure when...
        there is more than one possible relationship between the cause and effect, no clear-cut arrows between events
        the cause and effect are separated in time
        an inference occurs simultaneously with another type of HOT speech
