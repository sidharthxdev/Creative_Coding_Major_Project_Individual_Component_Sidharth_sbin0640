# Creative_Coding_Major_Project_Individual_Component_Sidharth_sbin0640

## Sid's Individual component

---

Sidharth Bindumol Sabu | SID: 530801229 | unikey: sbnin0640 individual component for creative coding major projects

---

*For the tutor: Please not that for my individual component I had to create a new repository as I wasn't able to fork my repository*
*I tried to branch it but it wasn't working the way I expected as for some reason, the changes kept going on to the main group component*

### Concept: Time Interval Based

#### Simple and Automatic Experience:

- Load the page and the animation will begin immediately
- The animation is fully automatic - no user interaction required as it works on a time interval
- Watch as new circles spawn every second from existing circles
- Circles will bounce around the screen continuously
- Each circle displays unique patterns (rings, dots, or combinations)
- The animation adapts to the screen size automatically 
- Resize the = browser window to see the canvas adjust dynamically

#### What to Expect:

- The animation starts with one circle at the center of the screen
- Every second, a new circle appears at the location of a randomly selected existing circle
- Circles move slowly across the screen and bounce off the edges
- Each circle displays one of three randomly assigned pattern types
- Colors are randomly generated for each pattern element
- The animation continues indefinitely, creating an ever-growing ecosystem of moving patterns

#### Individual Approach to Animation
Animation Driver: Time-Based Method
I chose time-based animation in my individual component that would use JavaScript's millis() 
function to track elapsed time and automatically generate new circles at regular intervals. 

#### Why Time-Based Animation:

- Creates a steady, predictable pattern that mirrors natural growth cycles
- Allows for contemplative viewing without requiring user interaction
- Reflects the concept of "Circle of Life" through continuous organic expansion
- Provides a meditative quality where viewers can simply observe the evolution


#### Animation Properties

**What Gets Animated:**

- Circle Generation: New circles are generated automatically every second
- Position: All circles move continuously with individual speed 
- Bouncing Behavior: Circles reverse direction when hitting screen edges
- Pattern Variety: Three distinct visual patterns (rings, dots, combinations)
- Random Colours: Each pattern element generated has random colors
- Size Variation: Circles are generated with random sizes between 10-50 pixels

**Unique Aspects:**

- Generative Growth: Unlike static animations, this creates an ever-expanding population of circles patterns
- New circles inherit the position of existing "parent" circles
- Pattern Diversity: Three distinct visual styles
- Organic Movement: Slow, gentle movement mimics natural floating or drifting

#### Inspiration and References

**Primary Inspiration: Pacita Abad's "Circle of Life"**


**Visual Influence:**

- Pacita Abad's use of concentric circles and radial patterns directly inspired the three pattern types
- Her vibrant, layered color approach influenced the random color generation system
- Her celebration of life cycles resonates with the continuous generation of new circles

**Technical Translation:**
- Concentric Rings: Directly inspired by the artwork's layered circular compositions
- Radial Dots : Reflects the use of dotted patterns and radial arrangements in the artwork
- Cmbination Pattern: Merges both approaches, similar to her complex layered works

**Conceptual Connection:**
- The "Circle of Life" theme is embodied through continuous birth of new circles
- Each circle becomes a potential parent, creating an endless cycle of generation
- The bouncing movement suggests the resilience and persistence of life


#### Technical Exploration

The core animation works around time interval based generation using the millis() function which returns milliseconds since code start
and compares current time with last added time. When difference exceeds the interval of 1000ms which is 1 second, a new circle spawns

Parent circle is randomly selected from existing array. New circle inherits parent's position but gets unique properties. 
Each circle has individual speed values with boundary detection making it bounce off. 

Three pattern types are used randomly and each pattern uses mathematical functions (cos(), sin()) for their position. 
Colors generated randomly for each visual element. Layered drawing creates depth and visual heirarchy. 

#### Key Concpets used

- Object oriented programming
- responsive design
- time based generation


#### Code References

- Started with the Week 9 resposive design lecture concept code and set that as the base framework. Adapted circle animation concepts for pattern-based generation
Modified timing system for automatic generation. Used 3 different types of patterns. 

- Other Techniques included mathematical pattern generation by using trigonometric functions (cos(), sin()) for the placement of circles and the time based animation
fucntion using thhe millis() function\

----

End of readme document







