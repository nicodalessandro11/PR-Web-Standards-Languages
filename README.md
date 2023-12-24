# PR Instructions

In this assignment, you must create a website that can serve as the foundation for your personal portfolio.

You will develop three pages, both for the desktop version and its mobile counterpart (the mobile or responsive version is not mandatory; it is presented as a bonus or extra credit in the assignment).

The task involves structuring the three pages using HTML and CSS. Screenshots for each page are provided to illustrate the expected outcome.

The goal is to achieve a layout following the best practices in web languages and standards, with semantic markup, well-organized CSS styles for future expansion, and clear navigation elements. Accessibility of the content is also required.

The page must be structured with HTML5, adhering to web standards to ensure maximum quality.

All necessary materials can be found in the file `materials.zip`

Texts for each page, along with font specifications, colours, links, and behaviours, are detailed in the document `FINAL PRACTICE - texts and specifications`. The required images can be found in the `images` folder. The images used are copyrighted and should not be used outside the scope of the assignment.

Design screenshots for the various pages and behaviours, serving as a model, are available in the `screenshots` folder.

## General Considerations

Follow these instructions for building the page:

- The layout should closely adhere to the design presented in the images found in the `screenshots` folder. However, if someone wishes to create a different design, they may do so, provided they consult with the instructor beforehand. In such cases, contact the instructor no later than 10 days before the assignment deadline, presenting the proposed design changes (refer to the "What can I modify?" section, specifying elements that can be changed).
- For page layout, you can use floating techniques, clearing, flexbox, and grid, as covered in the course. At least one section should be created using flexbox, and another using grid.
- Utilize the most semantic elements for each type of content.
- Correctly mark all links, even if they don't have a destination page. Links with no destination should be left as `href="#"`.
- Regarding fonts, Google Fonts have been used. Further instructions can be found in the document containing texts and specifications.
- In the `FINAL PRACTICE - texts and specifications` file, specify the items that should appear in the main navigation menu and footer, along with all text on the website.
- Each page must have its own title (`title`) and meta description, which should be appropriate and descriptive of the page's content.

### The Pages

The website comprises three pages:

- `index.html`
- `multifaceted.html`
- `web-design.html`

### What Can I Modify?

For this assignment, you can modify some graphical elements after consulting with the classroom instructor:

- The logo and favicon: You can include your own.
- Header images.
- The various images on the three pages.
- The colour scheme of the website, provided the new scheme adheres to AA-level accessibility criteria.

You cannot modify:

- The overall structure of the pages or the content.

If you have any questions, please consult.

#### Description (Bonus)

The following tasks are entirely optional. They are presented as an additional exercise of interest for the student and will be positively considered for Honor Roll grades.

In the `screenshots` folder, you'll find a `bonus` folder containing screenshots for the mobile version, which is activated for sizes smaller than `768px`.

To establish different designs based on device width, use the `viewport` tag (HTML5). Modify styles based on screen width using media queries in one of the following two ways:

- If you want a rule to apply from a specific width, use `min-width`.
- If you want a rule to apply up to a certain width, use `max-width`.

Example:

- From (mobile first):

  ```css
  h2 {font-size: 20px; }
  @media screen and (min-width: 550px) {
     h2 {font-size: 40px; }
  }
  ```

- Up to (desktop first):

  ```css
  h2 {font-size: 40px; }
  @media screen and (max-width: 550px) {
     h2 {font-size: 20px; }
  }
  ```

For the new design, you should modify the CSS styles considering the images from the new design. Additionally, the main menu is hidden and transformed into the typical "hamburger menu," which expands when clicked. **For its implementation, do not use JavaScript, only CSS**.

### Other Considerations

In addition to everything mentioned, consider the following:

- Both HTML and CSS should be as "clean" as possible.
- All HTML and CSS files should be free of validation errors.

**It is essential to prepare the necessary documentation so that anyone wishing to continue with the project understands the procedure to follow and aspects such as styles and classes to apply.**

This documentation, at a minimum, should include an explanation of the HTML elements and CSS declarations used to achieve the proposed structure, **explaining both common blocks for all sections and the specific structures of each section (It's not about copying and pasting the code; it's about explaining the code used)**.

This report will be delivered in a document with any of the following extensions: .doc, .odt, .pdf. In addition to submitting the solution, **it must be hosted in the personal space** to be publicly accessible on the Internet (IMPORTANT: the link to the `index` of the website must also be included in the project document).

The student may propose an alternative solution, but it must be communicated in advance (at least ten days before the submission deadline) to the instructor.

#### About the use of code generation tools

Do not use Dreamweaver or any other code generation tool for this assignment. If you do, you will be responsible for any incorrect markup created by the tools used. It is essential to review the code created by the tool and improve it according to the explanations provided in the course.

#### Intellectual Property and Plagiarism

Often, when creating a multimedia work, it is unavoidable to use resources created by third parties. It is understandable to do so within the scope of an assignment, as long as it is clearly documented and does not constitute plagiarism in practice.

Therefore, when submitting an assignment that uses external resources, a document detailing all of them, specifying the name of each resource, its author, where it was obtained, and its legal status (whether the work is protected by copyright or falls under another usage license such as Creative Commons, GNU license, GPL, etc.) must be presented. You must ensure that the chosen licence does not specifically prohibit its use within the context of the assignment. In case the corresponding information is not found, it should be assumed that the work is protected by copyright.

Additionally, original files must be attached when digital works are used, along with their source code if applicable.

#### Plagiarism

Unless specified differently in the assignment, all assignments must be done individually. In case of detecting plagiarized activities, all of them will be graded with a D.

#### Format and Submission Deadline

All assignment files (including the text document explaining the HTML and CSS entities used), the folder with images, and the CSS folder will be submitted in a compressed ZIP or RAR file.

Furthermore, the entire website must be uploaded to the UOC FTP server. The URL to access the website must be indicated on the first page of the document that explains the HTML and CSS used.

The submission deadline is January 12th at 23:59 hours.

#### Evaluation Criteria

- Validation, explanation of HTML and CSS entities used, structure, publication of the practice on the FTP server: 15%
- Accessibility: 8%
- General layout: 8%
- Navigation menu: 5%
- Header: 3%
- Footer: 14%
- `index.html`: 20%
- Header of `multifaceted.html` and `web-design.html`: 2%
- `multifaceted.html`: 15%
- `web-design.html`: 10%

##### Bonus

- +10% for the mobile version. The total score for the assignment will never exceed 100%.

The completion of the optional part ("bonus") will be taken into account when awarding the honor roll grade.

---
