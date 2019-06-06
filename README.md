# xunhuan
1.操场上100多⼈人排队，三⼈人⼀一组多1⼈人，四⼈人⼀一组多2⼈人，五⼈人⼀一组多3⼈人，共 



        for(let num=100;num<200;num++){
        if(num%3==1&&num%4==2&&num%5==3){
            document.write(num)
        }
    }
    
    
    
      2.甲、乙、丙、丁四人共加工零件370个，如果把甲做的个数加10个，乙做的个数减20
    for(let i=0;i<370;i++){
        if(i+(i+10+20)+(i+10)/2+(i+10)*2==370)
            document.write(i)
    }
    
    
    
    4.两个自然数X，Y相除，商3余10，被除数、除数、商、余数的和是163，求被除数、除
    for(let y=0;y<=163;y++){
        x=(3*y+10)
            if(x+y+3+10==163)
                document.write(y,x)
            
    }
    
    
    5..某数学竞赛中，参赛人数大约在380~450人之间。比赛结果，全体考生的总平均分为
           for(let x=0;x<=450;x++){
              for (let y=0;y<=450;y++){
                  if((x+y)*76==(x*75)+(y*80.1) && (x+y>=380) && (x+y<=450)){
                       document.write(x,y)
                   }
               }
             }




        6. 个四位数，恰好等于去掉它的首位数字之后所剩的三位数的3倍，这个四位数是多
        for(let num=1000;num<9999;num++){
            a=num%1000;
              if(a==num/3)
            document.write(num)
        }



        7.有一个两位数，如果在它的前面添一个3，可得到一个三位数；把3添在它的后面，也可
        for(let a=10;a<=99;a++){
            if((3*100+a)+468==(a*10+3))
            document.write(a)
        }
        
        
        
        
                8.⼀一个六位⾃自然数，将其末位上数字7移⾄至⾸首位，其余数字依次向右移动⼀一
        for(let x=10000;x<=799999;x++){
            if(4*x==7*100000+parseInt(x/10))
            document.write(x)
        }
        
        
        
        
        
                9..要在[ ]、[ ]7、[ ]48这三个数中的每个[ ]内各填上1~9中的⼀一个数字，使中间 
        let a,b,c
        for(a=1;a<=9;a++){
            for(b=1;b<=9;b++){
                for(c=1;c<=9;c++){
                    if(b*10+7==(a+c*100+48)/2){
                        console.log(a,b*10+7,c*100+48)

                    }
                }
            }
        }
        
        
        
        
        
        
                12.输出四位⾃自然数中各位数字之和为6并且各位数字互不不相同的数，并统计个 
        var	a,b,c,d, num=0;
        for(a=1;a<6;a++){
            for(b=1;b<6;b++){
                if(b==a){
                    continue;
                }
                for(c=1;c<6;c++){
                    if(c==b||c==a){
                        continue;
                    }
                    for(d=1;d<6;d++){
                        if(d==a||d==b||d==c){
                            continue;
                        }
                            console.log(a*1000+b*100+c*10+d);
                            num++;
                        
                    }
                }
                
            }
        }
        
        
        
        
                13.由数字1、2、3、4、5、6六个数字共可组成多少个没有重复数字的四位 
         var	a,b,c,d,e,f, num=0;
        for(a=1;a<10;a++){
            for(b=1;b<10;b++){
                if(b==a){
                    continue;
                }
                for(c=1;c<10;c++){
                    if(c==b||c==a){
                        continue;
                    }
                        for(d=1;d<10;d++){
                            if(d==a||d==b||d==c);{
                                continue;
                            }
                        }
                        console.log(a*1000+b*100+c*10+d);
                        num++;
                        
                    }
                }
                
            }
            
            
            
                    14.将100元纸币兑换成10元、5元和1元纸币共20张，输出各种兑换法，并统 
        var	ten,five,one;
        for(ten=1;ten<10;ten++){
            for(five=1;five<20;five++){
                for(one=1;one<100;one++){
                    if(ten+five+one==20&&ten*10+five*5+one*1==100)
                    console.log(ten+","+five+","+one)
                }
            }
        }
