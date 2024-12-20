# Progrid Geo Monitoring System (Sapura)

This first phase of Progrid's application development is designed for Sapura Towers; 616 towers across Malaysia and 11 monitoring teams. In-development is a basic Firebase authentication system for said teams to track their visits to each tower over a 7-month period.

__Modules__:
    - Firebase User Authentication
    - Firebase Database for Credentials Storage (User Types)
    - Firebase Storage (Photo Uploads)

Database/Storage Flow:
__User Information: Authentication data for the monitoring teams.
__Tower Data: Information on each tower, its status, and the teams visiting.
__Media: Two pictures per sign-in and sign-out event to Firebase Storage.

__Requires__:
    - Flutter 3.24.x(stable) or higher
    - Dart 3.5.4 or higher
    - The Connected Firebase Account
    - Compatible Mobile Device or Emulator for Testing


** If you'd like to contribute to the project, please fork this repository, create a branch, and submit a pull request.
** todo: create license