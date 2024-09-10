# best-hotwire
A collection of practical Hotwire recipes and real-world usage examples in Rails applications.

Let's see some documentation to get started with the real-world examples.

## Turbo Streams

Turbo Stream allows you to update parts of a web page in real-time without needing to reload the whole page. It works with Action Cable to send updates from the server to the browser automatically. This makes it perfect for features like group chats, notifications, and other real-time applications. For example, when a new message comes in or a new item is added to a list, the page updates instantly without the user having to refresh.

Real-world examples where you can use Turbo Stream:

- Group chats: Messages appear in real-time as other users send them.
- Live notifications: Notifications for events like friend requests or messages show up immediately.
- Task boards: When someone moves or adds a task, the board updates for all users in real-time.
- Auction sites: Bids update live, showing the current highest bid without refreshing the page.
- Comments on posts: New comments appear instantly as users add them, keeping everyone up to date.

## Turbo Frames

Turbo Frames let you load only parts of a page without reloading the entire page. This is useful when you want to update just one section without refreshing everything else. It helps make your web application feel faster and more responsive with minimal effort.

Here are five real-world examples where you would use Turbo Frames:

- Inline editing: When you click "Edit" on a form, it loads right in the same spot instead of taking you to a new page.
- Modal popups: Load a form or content inside a modal without leaving the current page.
- Tabs or navigation: When clicking between tabs, only the content inside the frame updates, keeping the rest of the page unchanged.
- Pagination: Load more results or navigate through pages without refreshing the entire page, just updating the list section.
- Form submission: Submit a form and only the part of the page with the form updates, showing the success message without a full reload.
