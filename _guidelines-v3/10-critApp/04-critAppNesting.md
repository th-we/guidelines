---
sectionid: critAppNesting
title: "Nesting Apparati"
---



In some situations, musical sources will agree at one level while differing at a lower
level.
For these cases, [app](/v3/elements/app.html){:.link_odd_elementSpec} elements may be nested to any level necessary. In
the following example, there are three sources, two of which agree on the addition
of a
measure, but differ in the content of the added measure:

{% include plainExample.html example="./v3/examples/critApp/critApp-sample206.xml" valid="false" %}


When nesting [app](/v3/elements/app.html){:.link_odd_elementSpec} elements, it is important that the value(s) in the
child [rdg](/v3/elements/rdg.html){:.link_odd_elementSpec} element's **@source** attribute must be a strict subset
of the ancestor [rdg](/v3/elements/rdg.html){:.link_odd_elementSpec} element's **@source** value.


