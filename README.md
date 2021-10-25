





main () {
  
  
Map  ingredients = {'tomato': 1, 'onion': 2};
Map  fridge = {'tomato': 1, 'onion': 1};

  int onion_found=0;
  int onion_need=0;
  int tomato_found=0;
  int tomato_need=0;
  
  
  fridge.entries.forEach((e)
  {
    if(e.key=='onion') {
    onion_found=e.value;
    
    } 
    if(e.key=='tomato') {
    tomato_found=e.value;
    
    }
  
   }) ;
  ingredients.entries.forEach((e){
    if(e.key=='onion') {
    onion_need=e.value;
   
    } 
  
  if(e.key=='tomato') {
    tomato_need=e.value;
    
  }
  } ) ;
  
  
  
  if(tomato_need>tomato_found) {print(false) ;}
  else if(onion_need>onion_found) {print(false) ;} 
  else print (true) ;
 
  
  
  
                         } 

                        
