Hi Freddie!

You've displayed a high level of understanding and have more than satisfied the requirements for a VG grade. Your use of 'advanced' html/css concepts such as variables, grid and flex is outstanding.

I've made a few comments about some things below that I think you'll apprciate. I'd like you to fix these things for your own knowlege, but I have absolute confidence you know what you are doing (and the main issue is likely my fault) so there is no need to resubmit.

Very well done!

*************************************

CRITERIA FOR GRADING

*************************************

GODKÄNT:
-------------------------------------

3 separate pages: ✅

A header with a page title on every page: ✅
  FYI: No one knows Google's exact search algorithim but the general advice is that each h1s and its content should be unique.

A navigational menu every page with links to the other pages: ✅

Contact form:
    Email: ✅
    Message: ✅
    Required: ✅
    Mail to: ✅ ❌
      Re-reading the assignment specs and this might be my fault - my email client is launching correctly base don the mailto action but none of the info entered is showing. I'm expecting to see the email & message I entered appear in the email body, but I see that I didn't directly state that was what is required. I'd like you to add them for your own knowlege about how to add info to forms, but it won't affect the grading as it is

RWD:
    Desktop: ✅
      On the home page the nav container is larger than on the other pages, and only on the home page are the header and nav the same height despite having the same fr value. This is caused by:
        a) the calculation of the fr units. The main content on the home page is larger than on the other pages, and fr units are proportional: 0.5fr of 1000px is smaller than 0.5fr of 1500px and b) the h1 has top & bottom margin which forces its parent to expand. Fr units specify the initial or minimum size of a container, and the containers will try to expand if their content forces them to. In other words only on the home page is the header 0.5fr, every where else it is being forced to expand while the nav is always rendered at 0.5fr.
    Mobile: ✅

External CSS: ✅

-------------------------------------

VÄLGODKÄNT:
-------------------------------------

Current page indication in the menu: ✅ ❌
  Check "current-menu-item" on the mobile menu for the different pages! 

Responsive Image: ✅
  Very well done

RWD:
  Media Query: ✅
  Flex/Grid: ✅
    Excellent understanding

Separate CSS: ✅
  Semantic: ✅

Semantic Element naming: ✅

Code Style:
  HTML: ✅
  CSS: ✅
  test.html should be deleted!