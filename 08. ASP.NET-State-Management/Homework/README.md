# ASP.NET State Management Homework
1. Create an ASP.NET Web Form, which prints the type of the browser and the client IP address requested `.aspx` page.
1. Create a ASP.NET Web Form which appends the input of a text field when a button is clicked in the `Session` object and then prints it in a `<asp:Label>` control. Use `List<string>` to keep all the text lines entered in the page during the session lifetime.
1. Create two pages that exchange user data with cookies. The first page is a login page. The second one redirects to the first one if the expected cookie is missing. The cookie must expire in 1 minute.
1. In ASPX page holding a `TextBox` run a JavaScript code that deletes the ViewState hidden field variable in ASPX page. What happens at postback?
1. Implement a graphical Web counter. It should display as JPEG image the total number of visitors of the requested `.aspx` page since the start of the Web application. Keep the number of visitors in the `Application` object. What happens when the Web server is stopped?
    - Re-implement the previous task to keep the total number of visitors in SQL Server database.
1. Implement the Tic-Tac-Toe game which allows Internet users to play one against another. Multiple game sessions should be supported to run in parallel. The main page (`Default.aspx`) should list all games in the application (games now playing, finished games and games waiting for a second player). The user could start a new game or join existing game which has only one player or view who is the winner of any finished game. When starting new game or joining an existing game, the player should enter his or her name. Players who wait for an oponent to join to their game or to enter a valid move should check repeatedly at 1 second.