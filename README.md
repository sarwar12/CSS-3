# CSS-3


### CSS SYNTAX: 
		Selector Property Value
		     h1{        color:       red;   }

### Multiple CSS:
		Internal+ External+ Inline CSS

### Property & Values:
#### Background Property::
		Background-color: red/ #000;
		Background-image: url(drk.jpg);
		Background-repeat: repeat; (this repeated full background)
				 no-repeat;(this is not repeated)
				 repeat-x;( this is repeat horizontally/ left-right)
				 repeat-y;(this is repeat vertically/ top-bottom)	
		Background-position: top center; (two value used by image positioning )
				    left center; 
				    left bottom; 
				    center top; 
				    center center; 
				    right top; 
		Background-attachment: scroll; ( do you mouse scroll with image scrolling )
				           fixed; (do you mouse scroll with dont scroll image)
		Background-size: 500px 500px; (height width)
			                cover; (cover by full image)
	ShortHand Property:::
		Background: color |image|repeat|attachment|position;
		Background: red url(imie.jpg) no-repeat fixed cover;
		
#### Border Property::
		Border-style: solid/ double/ groove/ dotted/ dashed/ inset/ outset/ ridge/ hidden; (All side)
		Border-width: 3px;
		color:teal; (border color)

		Border-top-style: solid;
		Border-bottom-style: solid;
		Border-left-style: solid;
		Border-right-style: solid;

		Border-top-width: 10px;
		Border-bottom-width: 10px;
		Border-right-width: 10px;
		Border-left-width: 10px;
	ShortHand Property:::
		Border:color| style |width;
		Border:red solid 5px;
		
 #### Outline Property:: 
		Outline-style: none|hidden|dotted|dashed|solid|double|groove|ridge|inset|outset|initial|inherit;
		Outline-color: red/#000/ RGB;
		Out-width: 20px;
	ShortHand Property:::
		Outline: outline-color | outline-style | outline-width
		Outline: gray solid 20px;


### Selector's:
	1) Element Selector / Type Selector :
 	    ( EX:  p{} )      p { color:red; }

	2) Id Selector :
   	    ( EX: #idname {} )      #para { color:red; }

	3) Class Selector :
     	    ( EX:  classname{} )       .para { color:red; }

	4) Universal Selector :
   	    ( EX:*{} )        * { color:red; }
	
	5) Descendent Selector :
   	    ( EX:menu ul li{} )       menu ul li { color:red; }

	6) Group selector :
 	    ( EX:a,p,b{}  )	  a,p,b { color:red; }

	7) Attribute Selector :
    	    ( EX: input[type=text]{} )     input[type=text] { color:red; }
### Comments:
	        /* content */    or     /* */

***

## G SARWAR
### Web Instructor
