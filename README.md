# pn-wrangle

![Screenshot of commands](https://github.com/pruthvi-naskanti/pn-wrangle/blob/main/bdassign.JPG?raw=true)

- Here, I have found occurance of words TITANIA and THESEUS using 'awk' command.
- 'awk' is a programming language which we can combine with shell script and can be used for processing text-based data.

## Commands used:
- command to get wordcount of word TITANIA and print it to Output.txt file

awk '{print gsub("TITANIA",$0)}' Input.txt | awk 'BEGIN{sum=0}{sum=sum+$1}END{print sum}' > Output.txt

- command to get wordcount of word THESEUS

awk '{print gsub("THESEUS",$0)}' Input.txt | awk 'BEGIN{sum=0}{sum=sum+$1}END{print sum}' >> Output.txtand print it to Output.txt file
