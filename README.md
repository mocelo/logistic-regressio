# Predicting spam email using logistic-regression
In this project we are clasifying mails typed in by the user as either 'Spam' or 'Not Spam'. Our original dataset was a folder of 5172 text files containing the emails.
Now let us understand why we have separated the words from the mails. This is because, this is a text-classification problem. When a spam classifier looks at a mail, it searches for potential words that it has seen in the previous spam emails. If it finds a majority of those words, then it labels it as 'Spam'. Why did I say majority ? -->

CASE 1 : suppose let's take a word 'Greetings'. Say, it is present in both 'Spam' and 'Not Spam' mails.

CASE 2 : Let's consider a word 'lottery'.Say, it is present in only 'Spam' mails.

CASE 3 : Let's consider a word 'cheap'. Say, it is present only in spam.

If now we get a test email, and it contains all the three words metioned above, there's high probability that it is a 'Spam' mail.

For this project, we will use the logistic regression algorithm
