function convert(num) {
 var tx=["I","IV","V","IX","X","XL","L","XC","C","CD","D","CM","M"],
     arr=[1,4,5,9,10,40,50,90,100,400,500,900,1000], ans=[];  
 for(i=arr.length; i>=0; i--){
   while(num>=arr[i]){
     ans.push(tx[i]);
     num-=arr[i];
   }
 }
  return ans.join("");
}

convert(2016);
