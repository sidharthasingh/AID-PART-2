#!usr/bin/bash
echo "enter start roll_no "
read id1
echo "enter end roll_no   "
read id2
pre_url="https://amizone.net/Amizone//Images//Signatures//"
post_url="_P.png"
post_url2="_S.png"
while [ $id1 -le $id2 ]
	do
		url=$pre_url$id1$post_url
		wget $pre_url$id1$post_url
		#wget $pre_url$id1$post_url2
		id1=$((id1+1));
	done
