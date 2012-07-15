# D4D Boston 2012

## General Session Notes
- Twitter Hashtag: #d4dboston
- Sponsors
    - Redfin
    - Isovera
    - Aquia Dev Cloud
    - OHO Interactive



## Sessions

### Welcome

- #d4dboston
- Seth Cohn, Drupal Association. 
    - d dot o
    - funds comm dev
    - scholorships
    - organize drupal con
    - $30/yr individual
    - association.drupal.org/membership

### Keynote
rm 123, 9:45am - 10:50am

- Angie Byron
- Drupal 8
- Dev began Mar. 10 2011
- Code Freeze Dec 1, 2012
- Initiatives
    - Mobile
        - fix admin UI for small screens, etc..
        - Responsive
        - drupal.org/node/232653
    - Front end performance
    - Blocks and Layouts (SCOTCH)
        - Build pages "outside in"
        - page.tpl.php to go away?
        - everything on page is a block
    - Authoring Experience Improvements
        - Revamp of content creation: node/1510532
    - Spark
        - project/spark
        - inline content editing
        - "edit" module
    - Responsive Layouts
        - Layout editor in prototype
    - HTML5
        - HTML5 doctype
        - mobile device markup
    - Markup Cleanup
        - Makes Zeldman Cry
        - drupal demo on github
        - twig template engine in symphony, noe/1499460
        - NO IE6/7 In Drupal 8
    - webservices initiative
        - serve json, xml, etc
        - 
- Looking for involvment in D8 development
- Download Drupal 99.63%, 0.32% Registered, did something 0.05%
- Be one of that 0.05%
- Helps learn faster and saves time and money
- Helps get business
- Improvements Process
    - Bug report to issue queue
    - dev reviews issue
    - tester reviews patch
    - Reviewe and tested
- /core-mentoring-hours
- /core-windsprints
- #drupal, #drupal-design, #drupal-contribute IRC
- /community-initiatives/drupal-core
- Q&A
    - html5 initiative
        - Local storage
        - Semantics
        - geolocation
        - form elements
    - (Front-end) mobile initiative
        - responsive design
        - admin tools mobile-friendly
        - performance
        - library loader
        - lighten use of jQuery
        - responsive image solution in core. Must be override-able
        - Kevin O'Leary working on responsive D8 admin theme
    - See Webservices Initiative
        - vision to serve up content in formats other than html(json, etc.)
    - "Snowman" initiative?
    - Jeff Atley
        - Ecosite Competition
        - 350 Eco sites
        - drupal@ecositecompetition.org
        - Rules
            - in by end of year
            - build pro-bono
            - size does not matter
            - www.ecositecompetition.org
            - Prize - Dinner with Dries
            - send email to drupal@ecositecompetion.org
                - I'm In, or sorry
                - I have or I need
                - sponsers?
    - 

------------------------------------------------------------------------------
Group Photo, 11:00am - 11:30am
------------------------------------------------------------------------------

### jQuery Demystified
rm 155, 11:30am - 12:20pm

- Patrik Corbett(@pcorbett), Redfin Solutions LLC
- Introduction to jQuery.
- Sat in for intro then skipped out. Nothing else of interest this time 
  period.

------------------------------------------------------------------------------
Lunch, 12:20pm - 1:30pm
------------------------------------------------------------------------------

### Designing and Implementing Beautiful, Flexible Interfaces
rm 141, 1:30pm - 2:20pm

- Ken Woodworth(@kenwoodworth), Aten Design Group(@atendesign)
- http://bokardo.com/principles-of-user-interface-design
- Uses Photoshop to define and art direction
- Style Guide
    - Reference to define the look and feel of different elements of a site.
    - Sets you up for more modular and scalable CSS
    - Create a cohesive visual brand
    - gifffle (dribbble mock)
    - see slides online for gifffle style guide sample
    - Components of style guide:
        - Colors
        - text
        - form
        - misc
- Photoshop features to understand in order to create style guide:
    -  Layers Panel
    -  Learn keyboard shortcuts: e.g. 
        -  Selecting Layers: option + [ or ]
        -  Move Layers: cm + [ or ]
        -  Copy Merged: cmd + shift + c
    -  Vector and shape layers
    -  Smart Objects
    -  Blend modes
    -  Patterns
        -  "Subtle Patterns" website
    - Use overlay to create gradients
    - SASS Tequniques
        - Use preprocessors() SASS/Less - Leader as far as features,
          community.
        -  * {
                @include box-sizing(border-width);
            }
        - "Symbol Set" - Semantic icons
        - Blen Modes

### Improving the Content Editing Experience in Drupal with Spark
rm 155, 2:30pm - 3:20pm

- by Kevin O'Leary
- New Drupal distribution
- The vision of Spark is the create a Drupal distribution that meets or
  exceeds the content authoring experience found in the bestjopen source
  and proprietary CMSs
- Competition
    - Wordpress
    - CQ5
    - site.com - Salesforce
    - sitecore
    - squarespace - small to mid-size business but very easy to use.
- Who is working on Spark?
    - Dries
    - Angie
    - Gabor Hojtsy
    - Jesse Beach
    - Preston So
    - Kevin O'Leary
- Target Audience
    - Content creators
    - All Acquia distribution leads
    - Any Drupal 7 distribution developer
    - Any site builder
- * Still in very active development at this time
- Features Roadmap
    - Content Creation & Editing (only feature done to date)
    - Page & Content Layouts
    - Dashboards & Workflow
    - Mobile Authoring
    - Media Management
    - Content Staging
    - Localization
- http://drupal.org/project/spark
- http://drupal.org/project/edit
- http://drupal.org/project/ember
- New spark admin theme
- Working with other initiatives
    - WSCCI
    - Scotch
    - HTML5
    - LSD
    - D8 initiative
    - D8 Media
    - D8 multiligual
- How to help
    - Test
    - Take usability test
    - Give feeback
    - help with tickets
- 

------------------------------------------------------------------------------
Break, 3:30pm - 4:00pm
------------------------------------------------------------------------------

### Scalable Stylesheets - Themeing with Modular CSS
rm 155, 4:00pm - 4:50pm

- John Ferris @pixel_whip
- http://atendesigngroup.com/blog/adding-css-classes-blocks-drupal
- http://munich2012.drupal.org/program/sessions/stay-classy-drupal-theming-modular-css
- https://gist.github.com/3113100
- OOCSS, SMACCS
- CSS Architechture
    - Dont repeat yourself
    - Dont mix layout and style
    - Reduce specificity
    - Do not target ids
    - Define naming conventions
- Avoid Drupal CSS (DCSS)
- Progresion of style
    #1 Default tags
    #2 Elements
    #3 Components
    #4 Layout
- CSS Pseudo Logic by exploiting the cascade
    - eg. .resource-list, .resource-item
- Ways to apply CSS
    - Through UI
        - Views
        - Semantic Fields
        - Display Suite
        - Block Class
        - Skinr
        - 
    - Directly to template files
    - With preprocess functions (Preferred)
- <?php print $content_attributes ?> do not put attributes in template
  files
- $var['#attributes']
- Blocks
    - hook_block_view_alter()
    - hook_preprocess_block()
    - hook_process_block()
    - block.tpl.php -> block--{module}.tpl.php
    - function {themename}_preprocess_block(&vars){...}
- Fields - see gist
- Menus
    - Standardize on menu_block module
    - theme_menu_tree(outside)
    - theme_menu_link(inside)
    - 
- adding level depth as class: theme_menu_link
    - http://api.drupal.org/api/drupal/includes%21menu.inc/function/theme_menu_link/7#comment-19004
- 

### Code without thinking
rm 155, 5:00pm - 5:50pm

- David Moore, NPR, @CrookedNumber
- Don't Make Me Think - Steve Krug
- Make coding standard
    - http://drupal.org/coding-standards/
    - http://drupal.org/node/302199 (css)
    - http://drupal.org/node/172169 (js)
- Don't be too anal
- It's about consistency and predictability
- Reduces arguments
- see Drupal coding standards
- Guiding Principle #1
    WWCD - What Would Core Do?
- Close HTML Tags?
- Guiding Principle #2
    - TATNG - Think About The Next Guy/Gal(person)
    - Google: crell code smells
- Don't set an implicit argument to the default value
- If using "magic number" in multiple places it probably should be a constant
- current_path()
    - _GET['q']
        - going away in Drupal 8
        - more readable
- use "bumper" comment eg: } // end for loop
- "Coder Tough Love": http://drupal.org/project/coder_tough_love
    - dependence on http://drupal.org/project/coder
- When to Watchdog
    - Look at the function name
    - If something is bark-worthy, log it
    - Don't log the fact that the dog didn't bark
- Commented out Code - should not be in production code




==============================================================================
Day 2
==============================================================================

## Keynote - Designing for Content Management Systems
- Jared Ponchot, @jponch, Creative Director, Lullabot
- drupalize.me

- Think Creatively
    - #aside Dr. Zonkett
    - CMS-es create ways of imposing order
    - What Drew to Drupal
        -  Thinks Contextually
    -  How CMS(like drupal) Thinks
        -  Contexts
        -  User Types
        -  Content Types
-  
- Critique
- Create Systems
- Content Types & Fields
    - How break down into "discreet chunks"?
    - Digestible Chunks
- Goals - Set organizational and creative goals early
    - Why should this site exist?
    - Think about content types - At least most important first
- User Types
    - Who is using site
    - What are they using it for 
    - Anon or Auth
    - What can they access or not access? create or not create? Edit or not edit?
- #aside: article "Baby got Backend" - Jeff Eaton
- Think like content creator early and often
- Contexts - "The original 'Responsive web design'" - jp
    - provide conditions and reactions
    - if this then that
- RECAP
    - Contexts
    - User Types
    - Content Types "Meat and Potatoes"
- Why should we think this way? (content first)
    - need to know out tool
    - simplifies the complexity
    - We can't design for each PIECE of content on a dynamic site!
- #aside: "Future-Ready Content" - ALA - Sara Wachter-Boettcher
- "An Escalator could never break"
- Where to Begin?
    - Start with most important content first, or context.
        - Make relationship chart for content: whiteboard, mindmap, atc
    - * observation - uses plain drupal to wireframe content and context
- Don't forget Hierarchy
    - Assign numbers(1,2,3...) to define hierarchy of content items
    - Don't ever let client tell you that everything is a one(1)
        - lingscars.com
- Gestalt & Other FUNdamentals (Gestal Laws)
    - Position
        - "Have yet to find a website that folds" - jp
    - Proportion
        - Larger item is more noticable
        - #aside - "petchow" (rat poison)
    - Proximity
        - very powerful
    - Symmetry
    - unity - simple as adding an arrow between two objects
    - Pause - Awkward silence in our designs
    - etc..
- "Blur Trick" - Blur deign to see what eye is drawn to
- "To Achieve great things two things are needed: A plan and not enought time"
    - Leonard Bernstien
- QA
    - How content first?
        - Structure first Content always
        - At least start with content types if no content is yet available
        - Break up into chuncks(eg. fields)
    - Wireframes in drupal - Slide in presentation is actually fireworks
        - Wireframes should be as plain vanilla as possible
    - wysiwyg editors should be very limited to help prevent destruction of design
    - Think of content as if it could be used as a a service(xml,json,etc)
    - User first
    - 


## Case Study: Transforming a Designer's Vision into a Drupal Site
rm 141, 11:30am - 12:20pm
- Natalie Keller - Charles River Web
    - http://www.linkedin.com/pub/natalie-keller/6/b54/555
- Case Study: Michael J. Skok responsive website
    - http://www.mjskok.com/
- Design by tom O'Keefe
- Usually does not use base theme
- Chose Adaptive theme by Jeff Burns
- Used adaptive for front-end and admin area
- Adaptive theme 
    - allows to choose layout in UI
    - Can set max width and specific media query
    - Adaptive theme generates
- Resource Grid page
    - Blocks set in three columns
        - stack for small screen
- Spoon.net for cross desktop testing
    - Spoon.net lets you run your applications from any desktop with no installs
    - 
- Steps to create responsive background photo
    - Make photo content type
    - Make scaled, small screen, image style
    - PHP randomly selects image and writes out to javascript the path
      to the image
    - JS detects content(page container)-width to determine whether to use small or large 
      background photo. Small screen defined at 481px
    - http://css-tricks.com/perfect-fill-page-background-image/
        - Works for IE9 and up
        - uses conditional comments to attach img element in body for
          less than IE9
- Transparency
    - Site title(logo)
        - png image with text as transparent background.
    - Content area
        - Uses opaque png for opaque backgrounds
        - Audience input: use rgba for newer browsers
    - Menus -  dropdown
        - Taxonomy menu
            - Configure parent item(resource in this case)
            - Choose menu path type(default Taxonomy name/tid)
            - resource_menu_taxonomy_menu_path()
            - resource_menu_path_terms()
                - gets vocab name
                - builds path
    - View - for resources gallery
        - url: resources/% (% is placeholder for argument)
        - Contextual filter - term id
## BOF - SASS
rm 155, 12:30 - 2:00
### Installation:
    - gem install compass
        - for windows users
            - install ruby first: http://rubyinstaller.org/
        - mac users
        - all
            - gem install compass
            - do above at command line
        - GUI Apps for Mac:
            - code-kit
            - compass.app
### Sample Themes
    - zen 5
    - Basic
    - aether - Drupal base theme
### New project
    - compass create
    - Do this within project new project directory
### Compass Sprite Maps
    - Merges many images together into one then creates styles with
      background positions set
    - @include "images/sprite_imgs/*.png"
    - Compass will handle svg images as well
        - background-size: contain; /* secret sauce for scalable bg images */
### Resources
- compass-style.org
- Compass - photoshop-like mixin library
    - "blend modes"
    - https://github.com/heygrady/scss-blend-modes
- symbolset for symbols
    - http://symbolset.com/
- http://thecodingdesigner.com/journal/breakpoint-1
- http://thesassway.com/intermediate/responsive-web-design-in-sass-using-media-queries-in-sass-32
- Open-aid dist profile - by Ken Woodworth
- NYC Sass -  Meetup streams on meetup.org
- Watch for SASS confs in spring
- styletil.es
- look for html/css style style project
- alienresident https://github.com/alienresident
    - Watch for html/css style-tile project on github

## Panel Discussion: How Devs and Designers can Make Drupal Better, Together
rm 155, 2:00pm - 2:50pm
### Panel
    - Ben Melancon - https://twitter.com/mlncn
    - Dave Myburgh - https://www.acquia.com/about-us/team/dave-myburgh
    - Scott Lozier - https://twitter.com/reallyroger
    - Stephane Corlosquet - https://twitter.com/scorlosquet

    - Dharmesh Mistry(Moderator)

### Discussion Notes
- No designers on panel?
- Aten group
    - iterative process
    - small chunks at a time
    - designers and developers involved all the way in the process
- Aquia
    - Agile
- Content
    - not introduced early enough in the process
    - can change through the project and cause development problems
- Design for Drupal - 
    - Designers community
- Post on design group
- http://groups.drupal.org/drupal-design
- Seems like developers are trying to bring designers down to their level
  We need to bring outselves up(or down) to a designer's level to get great
  designers more involved.


## Misc
- Voip Drupal dot org
    - Assign phone extensions to drupal users
    - http://voipdrupal.org/user voiptest/voiptest
    - http://drupal.org/project/voipdrupal/
    - audio blog
- Seth Cohn -  NH Legislator, Cantebury
   HB418 - NH Open Source Legislation
        - http://www.nhliberty.org/bills/view/2012/HB418
        - "This bill requires state agencies to consider open source software
          when acquiring software ..."

- gfxCardStatus - codykrieger - allows to view which gpu is in use

- drush site-install --db-url=sqlite://sites/spark-demo/files/.ht.sqlite



