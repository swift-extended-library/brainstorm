# Brainstorm

## Good Questions

- How does a library get added under this umbrella?  
- How do changes get merged in?  
- Who has commit access?  
- Is there a proposal process for these libraries?  
- Do we need a core team that makes decisions for the community about these libraries?

## Scattered Thoughts

- Two approaches
  - single repository with subfolders for different "libraries"
  - one repository per library
- seed repositories/folders that we want to see built. initial thoughts:
  - [data structures](https://forums.swift.org/t/adding-more-data-structures-to-the-standard-library/23651)
  - [sorting](https://forums.swift.org/t/pitch-stdlib-making-sorting-algorithm-selectable/24100)
  - [regular expressions](https://forums.swift.org/t/let-s-chat-first-class-regular-expressions/22411)
  - numeric stuff
    - [sum collections](https://forums.swift.org/t/pitch-method-to-sum-numeric-arrays/24170)
    - [isPowerOf2](https://forums.swift.org/t/adding-ispowerof2-to-binaryinteger/24087)
    - `isEven`/`isOdd`
  - paths
  - CLI arg parsing
  - observables?
  - http?
  - logging strategies for SwiftLog?
- use the forums as a source of ideas for things that have been rejected or deferred from the standard library
- is there a way to make templates for repositories, so that providing a library name will automatically generate the proper folder structure, package manager files, etc?
