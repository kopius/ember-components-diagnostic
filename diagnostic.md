# Ember Components Diagnostic

Record your responses inside the fenced code blocks below each question.

1.  Give an example of a visual hierarchy that could be modeled with components. Explain why each piece might be it's own component.

    ```md
    A blog might have many posts, with a list view of all the post titles in a
    sidebar and a single post viewable in the main container of the UI. Each
    post could have many comments, viewable below the main post. The post titles
    in the sidebar could be rendered as individual components, since each one
    will need to access data from a distinct post, and the sidebar items might
    need special behavior like linking or collapsing. The post view in the main
    container would also draw data from the post model, but require a different
    component, because the user will want to view and interact differently with
    an individual post when it is rendered in the main container.
    ```

1.  What is the command to generate a new component called '`my-map`'?

    ```sh
    ember generate component my-map
    ```

1.  What files are created and/or edited to produce a component, and what are their responsibilities?

    ```md
    A component consists of two files within a folder matching the component's
    name. These files are `component.js` and `template.hbs`. The file
    `component.js` is responsible for handling actions, i.e. the component's
    behavior. The `template.hbs` file is responsible for how the component is
    rendered in the UI, i.e. the component's appearance.
    ```

1.  Suppose you have a component '`my-contact`', which is loaded from
    '`app/contacts/template.hbs`' when visiting the `/contacts` route. What is
    the syntax (code that is written) to render this component inside that template?

    ```html
    <!-- your response here -->
    ```

1.  Each contact has multiple phone numbers. Suppose you also have '`my-phone`'
    nested under '`my-contact`'. What is the code you would write in
    '`app/components/my-contact/template.hbs`' to load the nested component and
    pass it data?

    ```html
    <!-- your response here -->
    ```
