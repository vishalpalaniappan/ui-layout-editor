# ui-layout-editor
This tool allows users to create layouts visually and export a LDF file that can be imported into the ui-layout-manager in custom applications.

As part of creating the layout by splitting the UI into rows and columns using dividers, the user will also be able to specify custom properties for each container. This includes properties like minimum width, tabs, color scheme, container id, component names etc. 

This editor will use the ui-layout-manager to generate the layout for this application, so it will be implemented after the minimum required features are added to the ui-layout-manager (layout, resizeable containers, component injection, layout caching etc).

This isn't necessary to use the layout manager, so it is lower in priority but I do intend to implement it as part of the full layout manager toolkit in the background.
