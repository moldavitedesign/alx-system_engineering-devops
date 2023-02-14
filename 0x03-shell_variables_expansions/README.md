alias ls="rm *"
echo "hello $USER"
PATH=$PATH:/action
echo $PATH | tr ":" "\n" | wc -l
