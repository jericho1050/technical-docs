**User Stories:**

1. You can see a `main` element with a corresponding `id="main-doc"`, which contains the page's main content (technical documentation)
1. Within the `#main-doc` element, you can see several `section` elements, each with a class of `main-section`. There should be a minimum of five
1. The first element within each `.main-section` should be a `header` element, which contains text that describes the topic of that section.
1. Each `section` element with the class of `main-section` should also have an `id` that corresponds with the text of each `header` contained within it. Any spaces should be replaced with underscores (e.g. The section that contains the header "JavaScript and Java" should have a corresponding `id="JavaScript_and_Java"`)
1. The `.main-section` elements should contain at least ten `p` elements total (not each)
1. The `.main-section` elements should contain at least five `code` elements total (not each)
1. The `.main-section` elements should contain at least five `li` items total (not each)
1. You can see a `nav` element with a corresponding `id="navbar"`
1. The navbar element should contain one `header` element which contains text that describes the topic of the technical documentation
1. Additionally, the navbar should contain link (`a`) elements with the class of `nav-link`. There should be one for every element with the class `main-section`
1. The `header` element in the `#navbar` must come before any link (`a`) elements in the navbar
1. Each element with the class of `nav-link` should contain text that corresponds to the `header` text within each `section` (e.g. if you have a "Hello world" section/header, your navbar should have an element which contains the text "Hello world")
1. When you click on a navbar element, the page should navigate to the corresponding section of the `#main-doc` element (e.g. If you click on a `.nav-link` element that contains the text "Hello world", the page navigates to a `section` element with that id, and contains the corresponding header)
1. On regular sized devices (laptops, desktops), the element with `id="navbar"` should be shown on the left side of the screen and should always be visible to the user
1. Your technical documentation should use at least one media query


This is in compliance with the certification project for FreeCodeCamp's Responsive Web Design
