# Write-a-program-to-display-all-the-lines-in-a-file-python.txt-along-with-line-record-number.
fh=open("python.txt","r")
count=0
lines=fh.readlines()
for a in lines:
    count=count+1
    print(count,a)
fh.close()
