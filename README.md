# Project PolyBOK

Project PolyBOK (i.e. Polymathic Body of Knowledge) is a [Polymathic Institute](http://polymathic.institute/) initiative to map out interconnected academic concepts that are created with learning in mind. Think Zettelkasten/Second Brain meets Anki meets edX.

The learning application based on this library is still under development. To browse the content of this body of knowledge for now, visit the [PolyBOK](https://library.polymathic.institute/) website.

In order to facilitate reviewing concepts via spaced repetition, every literature note should have its key ideas stylized specifically to enable prompt generation of multiple choice, fill-in-the-blank, and binary questions. This is done in addition to the back-linking of related concepts in other literature notes.

**The goals of enforcing this unique structure are to:**
1. Allow discovery of related concepts so that a learner can learn a new concept that is relatable to their existing network of knowledge, which improves retention significantly.
2. Allow mixing of keywords in neighbouring concepts such that the review prompt require the learner to differentiate between closely related concepts.
3. Research has shown that by requiring generation within review prompts, we help to alleviate passive learning, increasing retention.

In the case that the body text provides poor structure or missing context to highlight as a review prompt, it is encouraged to provide a "summary callout" at the end of the note to include key ideas that have not been captured. 

**This repository is a ObsidianMD vault, and collaboration is welcome!**
- **Important:** Ensure that links are made with "Absolute Path in Vault" and in Markdown style (i.e., Wikilinks disabled). See [quartz documentation](https://quartz.jzhao.xyz/notes/obsidian/) for details.
- Please see "Documentation" for literature note templates, prompt examples, etc.
- Find the best-fit category/sub-category to place a literature note, but do connect with related literature note in any category.
- Look into "LanguageTool" community plug-in for grammar and spelling.
- Look into "Text Generation" community plug-in to help with writing (GPT-3).
- All files under the folder "Personal" are git-ignored, you can use this area for permanent notes, article ideas, or GTD systems in here to take advantage of the shared literature notes.
	- The author personally uses this for blogs and brainstorming.
- Just send me a pull-request when you have created some well-written notes, thanks!

**TO-DOs**
- [x] Create initial set of categories under Literature Notes
- [ ] Create documentation on markup requirements for review prompts.
- [ ] Create literature note template for quick start.
- [x] Add some literature notes for reference.
- [x] CI/CD to deploy PolyBOK on web.
- [ ] Outline project roadmap.
- [ ] Update Polymathic Institute website with landing page.

---
#### Frequently Asked Questions (FAQ)

**Q. What is Zettelkasten?**
Zettelkasten is a method of organizing notes and ideas into an interconnected network of related concepts. It was developed by German historian and sociologist Niklas Luhmann in the 1950s and is based on the idea of creating a personal knowledge base by connecting individual notes together. The notes can be written using paper cards, digital notes, or other media, and can be connected through keywords, tags, or other relationships.

**Q. What is Second Brain by Tiago Forte?**
Second Brain by Tiago Forte is a productivity system that helps organize your ideas, projects, and notes into a unified knowledge base. It uses the Building A Second Brain (BASB) methodology to help you capture, organize, and share your ideas more effectively. It also includes tools for tracking progress on projects and goals, as well as content curation.

**Q. What is a Literature Note? What is a Permanent Note?**
A Literature Note is a note that is made from a source of literature, such as a book, article, or poem. It is used to summarize and analyze the text. A Permanent Note is a note that is kept and stored in an organized way for later reference. It usually contains information that will be relevant for the long term, such as lessons learned or facts about the topic.

