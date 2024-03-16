Build and Publish:

cd /home/shravan/documents/deeplearning/github/my_books/Machine_Learning_with_Python/github/Machine_Learning_with_Python_Book

jb build .

git status

git add .

git commit -m 'update book'

git push

ghp-import -n -p -f _build/html