# spaces

- The entire code across all of the social network platform is free and open-source
- Users owns the platform
  - They can fork the code, modify and develop it in whatever way they want
  - There is no single database holding all of users' data
  - Users choose themselves which data to expose
- There could be a convention (a standard) for sharing the data, e.g.:
  - Users work on data locally with open-source tools and share it on the web, having full control and transparency over it
  - Users pull the data from multiple users' data endpoints, exposed to the web
    - with all/any application / data /security best practices implemented throughough the entire chain
      - starting with application / data sharing layer (?)
      - continuing preferably with 0-depdendency tools across the toolchain (?)
      - up to to the open-source fully transparent and data-privacy proof custom hardware (?)

The idea is to **restore trust for the users of the web**, by ensuring they have and own full control over the tech they use to communicate, throughout all of its layers. It should be unobtrusive, easy to use (most preferably - with BCI-interfaces (brain-computer) interfaces and devices) and optional - meaning that users should have freedom to decide: 

- what their data is
- what shape it has
- how their data is exposed and shared to the web
  - across the entirety of their apps and tech-stack
- where from to pull the data for the network they communicate with / follow

and have efficient tools for it.

---

- Different repos (monorepo?) for different parts of application
  - Each part with its own manual semantic versioning & changelog gen
  - The social-network frontend app
    - Easy addition of data endpoints from users'
      - How do users explore data endpoints of other users?
      - How do users (easily) add those to follow / etc. ?
  - The social-network data sharing app

---

0 trust policy by default for everything throughout the entire stack, unless:

- it is fully open-source
- easily reproducible
- verifiable with constant predictable results
- transparent
- trustworthy
