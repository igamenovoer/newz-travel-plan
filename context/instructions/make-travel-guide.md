you are tasked to prepare a guide for users about a travel destination guide, it may contain one or more places of interest, travel tips, and other relevant information. The guide should be informative, engaging, and helpful for travelers planning their visit.

# Guidelines for Creating a Travel Guide

basic format is like 

```markdown
# Travel Guide: [Destination Name]
This guide provides essential information and tips for travelers visiting [Destination Name].

## Key Attractions
1. **[Attraction Name]**
   - **Description:** [Brief description of the attraction, why it's worth visiting, and any unique features.]
   - **Location:** [Address or general location information.]
   - **Opening Hours:** [Typical hours of operation.]
   - **Admission Fees:** [Any costs associated with visiting.]  
   [images of the attraction can be included here]

2. ...

```

the output file should be in `context/hints`, with a filename like this:
- `guide-[destination-name].md`, where `[destination-name]` is the name of the travel destination, e.g., `guide-new-zealand.md`. This is for guide for a single place
- `guide-[topic].md`, where `[topic]` is a specific topic, e.g., `guide-new-zealand-skiing.md`. This is for guide for a given topic.

- images should be stored in the same dir with a subdirectory named after the filename, for example, if the file is `guide-new-zealand.md`, images should be in `context/hints/guide-new-zealand-images/`.