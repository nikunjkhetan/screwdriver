## ME 359 Black and Decker Screwdriver Breakdown

### Project Overview

  The purpose of this project was to learn more about machine components and how they are produced and put together. By taking apart a relatively cheap, mass produced screwdriver and then analyzing it, it makes it possible to learn more about the engineering design process by looking at it in reverse. By being able to spot instances where DFMA tactics are implemented, observing how each component of the screwdriver fits into subassemblies and then into the final assembly, and observing the overall shape and size, it’s made clear that the seemingly simple design of the screwdriver had a lot of thought put into it. The portion of the project dedicated to analyzing the gearbox allows for a greater understanding on how gear ratios work, and some real-world applications of gear trains. It is another way to see all of the thought that must go into a design.

### Gearbox Analysis

  After taking apart the screwdriver, the individual parts of the gear train were analyzed, starting with the number of teeth (N). For the ring, planets, and the sun, N is found by simply counting the number of teeth. For the planetary carrier, however, N is found by using Equation 1.



Once the number of teeth for each component is calculated, the gear ratio for each stage can be determined by Equation 2 and then the total gear ratio for an epicyclic gear train can be found by using Equation 3.



The gear ratio is proportional to the ratio between the input and output torque, as well as the input and output angular velocity (RPM), as can be seen in Equation 4. The values in table 3 reflect the calculations done using Equation 4.



One of the most important values needed when working with gears is the pitch diameter. This diameter is somewhere in between the outside diameter and the center and is crucial to making sure that the gears fit together without friction. In order to calculate the pitch diameter for an epicyclic gear train, the value of the center to center distances between the two gears is needed. Equation 6 can be used if the two components have the same number of teeth and Equation 7 can be used if they do not. The calculated values for the pitch diameters are listed below in Table 4.


### Graphical Representation of Product Structure

![Image](ProductStructure.png)

This image displays all of the different components and subassemblies that go into the creation of the LI2000 Black & Decker screwdriver.

### Discussion Questions
1.	Three instances where Black & Decker incorporated Design for Manufacturing and Assembly (DFMA):

•	Injection molding: When looking at the product closely, it is easy to tell that parts of the structure of the screwdriver were created through injection molding. The orange plastic covers, in particular, have small round circles that are a result of the molds pushing together and not lining up exactly.

•	Uniform fasteners: Three out of the five screws used to assemble the screwdriver are identical—a tactic used by manufacturers to make it simpler to put the product together. The other two screws are most likely different because they need to serve a specific function that couldn’t be obtained using the other screw.

•	Premade gears: premade gears make the most sense to use since it is extremely difficult to make from scratch. Using standardized gears is also more reliable and cost effective.

2.	How the Power/Manual option works:

The drill can switch from power to manual mode and vice versa by rotating the tip of the drill until it clicks into place. Perhaps the rotation of the tip causes the gear train to lock so that it can no longer rotate, so then the bit will be able to act like a normal screwdriver.


You can use the [editor on GitHub](https://github.com/nikunjkhetan/screwdriver/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/nikunjkhetan/screwdriver/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
