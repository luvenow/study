# Header 1 (including line)
## Header 2 (including line)
### Header 3 (not including line)
#### Header 4 (not including line)
##### Header 5 (not including line)
###### Header 6 (not including line)


## List

- Dot list 
-- Dash list 
-- Dash list 2
	> Description 1
	

 ## Table
|                |ASCII                          |HTML                         |
|----------------|-------------------------------|-----------------------------|
|Single backticks|`'Isn't this fun?'`            |'Isn't this fun?'            |
|Quotes          |`"Isn't this fun?"`            |"Isn't this fun?"  		   |
|Dashes          |`-- is en-dash, --- is em-dash`|-- is en-dash, --- is em-dash|


## Link

[google](https://google.com)
[naver](https://naver.com)

## Font
**Bold letter**
*Italic letter*

## Graph

- Diagram
```mermaid
sequenceDiagram
A ->> B: Normal/Arrow
B ->> A: Normal/Arrow
B -->>C: Dash/Arrow
C --x B: Dash/Arrow(x)
B -x C: Real/Arrow(x)
A -> C: Normalr/No Arrow
A --> B: Dash/No Arrow
Note left of A: You can write <br/>**whatever**<br/> you would like to
```

- Chart

```mermaid
graph LR
A[Square Rect] -- Link text --> B((Circle))
A --> C(Round Rect)
B --> D{Rhombus}
C --> D
```
