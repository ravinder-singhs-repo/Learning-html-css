# h1 is a block level element : border accross it will take full width of the entire page
block level elements start from new line always
even if we decrese their widht this is true , 
block level elements take complete width that is available on the page 

inline elements always take width that is required or covered by content on the page (a tag is an example)
if we give width or height to them that is of no use -> they wont change 

we can give margin to block level elements 
we can give only margin left and right to inline elements

dont give top bottom padding to inline elements 
by displau property we can change inline to block and vice versa

after converting from inline to inline-block we can give width to the elements and also give margin to them 
-> no issues in giving padding also 

box-sizing:border box property when given widht does not changes even after giving padding , changing border size

default stylings given by browser can be changed by using * and resetting the values

pseudo classes used with link and buttons 
-> link , visited , hover , active
->link is default state 
-> active is state when we click and dont release

-> input related pseudo class 
:focus , :required

->ouline:none to remove outline from input 

-> pseudo elements like ::before and ::after are used to insert content before or after content which is already there on the page 
-> inserted content has by default display:inline , we can change that to display:flex
-> cant use before and after for img tag , br , input tag

% percentage values are given to elements as compared to their parent elements 

rem unit 
-> we can give values to css properties by using rem unit . 2rem mean 2 * (default font size given to html root element.)
we can also set font size of html root element by doing
html{
    font-size:10px;
}
or
:root{
    font-size:10px;
}

we can use rem unit to give values to properties like border , margin , font size , padding etc

changes in default font size of html element will result in changes in any property er give values in rem unit 


em unit 
explained in 74th file 
for padding and margin we should use em , bcz em units change with font size and this can help in responsiveness of the website

for border we can use pixel units

viewport units -> vw - view port width 
vh -> viewport height 



