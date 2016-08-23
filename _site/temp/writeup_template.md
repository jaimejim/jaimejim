# Shepherd Writeup for XXX

## 1. Summary

Who is the document shepherd? Who is the responsible Area Director?

Explain briefly what the intent of the document is (the document's abstract is usually good for this), and why the working group has chosen the requested publication type (BCP, Proposed Standard, Internet Standard, Informational, Experimental, or Historic).

## 2. Review and Consensus

Explain how actively the document was reviewed and discussed, by the working group and external parties, and explain in a general sense how much of the interested community is behind the document. Explain anything notable about the discussion of the document.

(In this section, tell the IESG whether there was review by a small number of interested folks within the working group, a lively long term discussion by large numbers of working group participants, and whether there was quick and broad consensus or several issues for which the consensus was "rough". Cite significant points of difficulty or controversy, and explain how they were resolved. Mention any reviews done by directorates, review teams, expert reviews, reviews from other SDOs, and whether there you think other specific groups should do further review. Consider, for example, reviews from the perspective of security, operational complexity, AAA, DNS, DHCP, XML, or internationalization. You should also describe any specific concerns or issues that the document shepherd has with this document or with the working group process related to it that the responsible Area Director and/or the IESG should be aware of. Note known implementation plans or any current implementations. If there are no plans for implementation, explain why this document is valuable in spite of that.)

## 3. Intellectual Property

Confirm that each author has stated that their direct, personal knowledge of any IPR related to this document has already been disclosed, in conformance with BCPs 78 and 79. Explain briefly the working group discussion about any IPR disclosures regarding this document, and summarize the outcome.

## 4. Other Points

Note any downward references (see RFC 3967) and whether they appear in the DOWNREF Registry (http://trac.tools.ietf.org/group/iesg/trac/wiki/DownrefRegistry), as these need to be announced during Last Call.

Check the IANA Considerations for clarity and against the checklist below. Note any registrations that require expert review, and say what's been done to have them reviewed before last call. Note any new registries that are created by this document and briefly describe the working group's discussion that led to the selection of the allocation procedures and policies (see RFC 5226) that were selected for them. If any new registries require expert review for future allocations, provide any public guidance that the IESG would find useful in selecting the designated experts (private comments may be sent to the Area Director separately).

Explain anything else that the IESG might need to know when reviewing this document. If there is significant discontent with the document or the process, which might result in appeals to the IESG or especially bad feelings in the working group, explain this in a separate email message to the responsible Area Director.

## Checklist

> This section is not meant to be submitted, but is here as a useful checklist of things the document shepherd is expected to have verified before publication is requested from the responsible Area Director. If the answers to any of these is "no", please explain the situation in the body of the writeup.

* Does the shepherd stand behind the document and think the document is ready for publication?
* Is the correct RFC type indicated in the title page header?
* Is the abstract both brief and sufficient, and does it stand alone as a brief summary?
* Is the intent of the document accurately and adequately explained in the introduction?
* Have all required formal reviews (MIB Doctor, Media Type, URI, etc.) been requested and/or completed?
* Has the shepherd performed automated checks -- idnits (see http://www.ietf.org/tools/idnits/ and the Internet-Drafts Checklist), checks of BNF rules, XML code and schemas, MIB definitions, and so on -- and determined that the document passes the tests? (In general, nits should be fixed before the document is sent to the IESG. If there are reasons that some remain (false positives, perhaps, or abnormal things that are necessary for this particular document), explain them.)
* Has each author stated that their direct, personal knowledge of any IPR related to this document has already been disclosed, in conformance with BCPs 78 and 79?
* Have all references within this document been identified as either normative or informative, and does the shepherd agree with how they have been classified?
* Are all normative references made to documents that are ready for advancement and are otherwise in a clear state?
* If publication of this document changes the status of any existing RFCs, are those RFCs listed on the title page header, and are the changes listed in the abstract and discussed (explained, not just mentioned) in the introduction?
* If this is a "bis" document, have all of the errata been considered?

IANA Considerations:
* Are the IANA Considerations clear and complete? Remember that IANA have to understand unambiguously what's being requested, so they can perform the required actions.
* Are all protocol extensions that the document makes associated with the appropriate reservations in IANA registries?
* Are all IANA registries referred to by their exact names (check them in http://www.iana.org/protocols/ to be sure)?
* Have you checked that any registrations made by this document correctly follow the policies and procedures for the appropriate registries?
* For registrations that require expert review (policies of Expert Review or Specification Required), have you or the working group had any early review done, to make sure the requests are ready for last call?
* For any new registries that this document creates, has the working group actively chosen the allocation procedures and policies and discussed the alternatives? Have reasonable registry names been chosen (that will not be confused with those of other registries), and have the initial contents and valid value ranges been clearly specified?