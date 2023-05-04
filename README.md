Download Link: https://assignmentchef.com/product/solved-csci-585-homework-1-sbook
<br>
<strong><em>Please create an ER Diagram for a simple social network based on the following description and write a report to justify your design. </em></strong>

Sbook is a social network. Each user has one unique profile including: name, gender, profile picture, date of birth and a cover picture. A user can be either a regular user or a privileged user and all regular users can upgrade to privileged users through a one-time payment. For security reasons, payments are processed by a third party and the database only stores the payment confirmation ID.

A regular user can post a status with text content and multiple pictures. All pictures are grouped into albums. Each picture belongs to only one album and each album is owned by a single user. Pictures are stored on a remote server, and the database only needs to store the addresses of pictures. A picture may contain persons and users can be tagged by other users in the picture. Each tag can refer to only one user in the picture. A picture can have multiple tags when there are many users in it, while a tag can belong to only one picture.

Besides statuses that a regular user can post, a privileged user can post an advanced status with text content, multiple pictures and a video (for example, a privileged user might choose to post their advertisement). Videos are also stored on a remote server and the database only needs to store addresses of the videos. Unlike pictures, videos are not grouped and cannot be tagged.

For each status a user posts, including advanced status, any user can comment on it with text content and one picture. Videos are not allowed in the comments. One comment is created by one user and it can only refer to one status. Only statuses can be commented (comments, pictures, albums or any other elements cannot be commented).

Users have friendships, which are bi-directional.

To simplify, we assume one picture or one video will only appear in one posted status or in one comment. Albums cannot appear in a posted status or comment.

<em>Feel free to make additional assumptions if they are not stated in the description (for example, attributes of entities). You also should be able to analyze the trade-offs of your design decisions. </em>




<em>Total number of points for this homework is 6. The submission </em><strong>MUST</strong><em> be a pdf file named <strong>[Student First Name]_[Student Last Name]_HW1.pdf</strong> (</em><em>wrong file name will not be graded</em><em>) that includes: </em>

<em>The ER Diagram for Sbook (3 points). This could be a generated figure from any ER tool (we recommend Visio 2016 and an online tool https://www.lucidchart.com). Hand-drawn diagrams will be penalized by -1 point. For Viterbi students, Visio can be downloaded from https://viterbiit.usc.edu/microsoft-imagine-downloads/ </em>

<em>A report where you describe and justify your design choices (3 points). Some suggestions are: </em>

<em>Why the relationship between A and B is 1:1, 1:N or M:N? </em>

<em>Is there any optional/multi-valued attributes in your design? If yes, why? </em>

<em>What are the attributes of the defined entities that you may have, and why do/don’t you include that in the ERD? </em>

<em>Could some design choices be different, and what are the trade-offs between your designs with others? </em>

If you have any general questions about the homework, please post your questions on HW1 discussion on USC DEN course forum. Before asking, please check to see whether similar questions were asked and answered. Thank you!

<em>Students can submit the assignment to USC DEN. Just go to the course MY TOOLS </em>

<em>Assignments Homework 1. The deadline is firm, only submissions that make it to the system will be graded<strong>. </strong>It is irrelevant if you submit your work at 11:59 PM according to your clock, the system will stop accepting submissions at 11:59 PM according to the clock on DEN (Dropbox) server.<strong>  You will not be able to submit your homework after the deadline. </strong>Also please expect the heavy network traffic around the deadline and network delay won’t be treated as a valid reason for late submission. The system accepts multiple submissions and only the most recent submission will be graded. Therefore, we advise you to make the initial submission at least a day before the deadline, and overwrite it with a better version or more complete submission after you have it. Make up data and have fun with this! </em>