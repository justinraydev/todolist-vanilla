# Vanilla JavaScript Test

## Goal

Extend functionality of existing ToDo List application with ability to categorize tasks.

### Description

As a user I would like to categorize tasks when creating them. Since every user have their own preferences, categories should be dynamically created.

### Acceptance criteria

1. Next to `What needs to be done?` field should be text input field `Category`
2. When blur event is happening on `What needs to be done?` task should not be created
3. Task creation should happen only when both input fields are fulfilled
4. In the list of existing tasks categories should be shown as labels
5. Every task can belong to one category only
6. When task is being created and input text in `Category` field matches already existing category it should be reused.
7. Deleting the last task within category should delete category also.

### Evaluation criteria

1. Code should be maintainable and testable
2. Application arhitecture should not be affected in a bad way
3. Task is a work in progress, valuable feedback will earn you additional points
