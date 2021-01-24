# Your review

1. It would be great if you could :
* Clarify what systematic review approach you employed in section 2.4.1. If you didn't perform a formal systematic review then I would use another term. 
  * _This is indeed removed_
* Consider if - in terms of language, jargon and complexity - the review is accessible to makers and hobbyists as is your stated aim in the abstract.
  * _In the end, I have refocused indeed, as those interested in this information may be more focused than only makers, say at least people with hardware/electronics interest. I have tried reframing this in the article._
* Consider creating tables from sections that are long lists of components and references or manufacturers and references, to make the text flow better for the reader.
  * _Working on this, to improve the reading flow_


2. I have also reviewed the previous reviewer comments keeping in mind my understanding of how the article has been adjusted in response. 
* One of your reviewers suggested: "Without figures for many subsections, the discussion is difficult to follow and remains unclear.
  * _I have simplified the sections.. unsure however how figures would help_ 
* Many sub-sections need additional details to especially understand their associated functionality in ultrasound scanning.
  * _Unclear as they do relate at a fundamental level to ultrasound, as we're only focusing on ultrasound._ 
* Also, the pros and cons of the available technologies must be added for each subsection along with a brief discussion to better evaluate the feasibility of incorporating them for the open-source ultrasound hardware.
  * _We have tried to complete as much a possible for this. However, since they are no options, just parts of a "block diagram", they have no intrisic pro or cons, they just have to be there for ultrasound imaging. But we may have understood the question in a wrong way_.

3. I cannot see that you have substantially addressed these points in each of the subsections. For example, the list of signal processing options at the end has no recommendations or discussion on which is most feasible/appropriate in the open-source/maker context. Could you explain why you were not able to address these comments?
  * _Covering these as per previous points_



# Reviewer 1 findings

* The paper claims is: “The aim of this paper is to identify relevant literature to consider when designing a simple open-source single-channel ultrasound device”. However, the paper mixes high-end, very complex multi-channel systems with simpler single-channel board; medical and NTD applications. Authors must clearly specify the class of the target boards and concentrate the attention on those.
  * _Clarified in the paper. Even if the review focuses on single channels, one can consider multichannels designs as fundamental, physical behaviors are the same, and existing research may be "hacked" or at least recycled/reused for single channel designs._
* The paper would like to describe a too wide range of aspects: among others: electronics, processing, probe motorization, coupling materials, etc.  And all these in 10 pages. Often only few linens are devoted to some subject, and no discussion is presented.
  * _The scope is in a sense very wide indeed. The purpose is really a high level overview and introduction to design to the reader to understand the key considerations for a design - but not a in-depth comment of every point, which is an exercice left to the reader as they can read to the cited papers_ 
* The paper was submitted not completed yet. Figure 2 is even not commented, Sec 3.4. includes just “[Hager, 2019, Hager and Benini, 2019] TO DO: also cite SUPRA @william ;)”. In Sec 3.2 this reviewer reads: “TO DO: add a figure showing the shift from RF to IF ….”.  Uploaded material includes a figure not shown in the paper. The writing of a paper requires much more care by the  authors.
  * _Agreed, hopefully taken care of in the new version_
* Sec 1.2 includes Amode and Bmode only. Much more modes are present in echographs.
  * _Agreed. However, these are the two main modes (clarified in the paper), and other modes may not be possible with single element the way we see in modern echographs, and as such were not reviewed (though mentioned as per below comment)._
* Sec 1.2 this review reads: “Other modes, such as M-Mode and C-Mode, combine or extend the aforementioned modes” These modes employed Doppler, and are not a “simple” extension.
  * _I respectfully disagree (though I agree it is not a simple extension): other modalities present information to the radiologist in a way at it augments/extends their understanding of the patient_
* Last paragraph of sec 2.1. “Equipment suppliers…” contains several errors in the references.
  * _Hope this is clarified_
* It is not clear if Fig.1 behaves to single-element or multi-channel systems.
  * _Clarified in the figure_
* Acronyms must be defined
  * _Thanks again for this - normally processed_


# Reviewer 2 findings
 
* Corrections: Page 9 of the manuscript need corrections, some of them are the 
* (a) missing body of sub-section 3.4, 
  * _Thanks, it was adjusted_
* (b) repeated sentences in section 3.3, 
  * _Thanks, it was adjusted as well_
* (c) please remove the visible "TO DO" list from the manuscript particularly noticeable on page 3.
  * _Processed, as the comment above_
* Suggestions: Without figures for many subsections, the discussion is difficult to follow and remains unclear. 
  * _We have tried to simplify the structure, having an introduction, hardware considerations and software opportunities linked to the hardware design choices_
* Many sub-sections need additional details to especially understand their associated functionality in ultrasound scanning. 
  * _I hope this was clarified. It is not the purpose however of the document to review their functionnality (though we try and cover use cases), rather to mention they exist, and may be thought about when one desings an ultrasound system._
* Also, the pros and cons of the available technologies must be added for each subsection along with a brief discussion to better evaluate the feasibility of incorporating them for the open-source ultrasound hardware.
  * _As of today, the architecture itself is well known - improvement lying in improvement of electronics or processing. As such, there are really no absolute pros and cons: utilising a FPGA ("hard to master" component) could be a pro for a FPGA hobbyist, but it would cause more trouble to a microcontroler oriented user. Similarly, choices of elements or chips would depend on the final context and specifications of the reader/user._ 


