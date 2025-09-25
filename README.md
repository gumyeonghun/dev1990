# dev1990

void main() {

int a = 84;

print ('필수문제 1번');

if(a<=100 && a>=90){
print('이 학생의 점수는 $a점 이며 등급은 A등급 입니다');
}else if(a<=89 && a>=80){
print('이 학생의 점수는 $a점 이며 등급은 B등급 입니다');
}else{
print('이 학생의 점수는 $a점 이며 등급은 C등급 입니다');
};


}

void main() {

List<String> cart = ["티셔츠", "바지", "모자", "티셔츠", "바지"];

Map<String,int> goodsPrice = {
"티셔츠" : 10000,
"바지" : 8000,
"모자" : 4000
};

     var goodsList = [];

for(var i = 0; i < cart.length; i++ ){

    var cartGoods = cart[i];
    var cartGoodsPrice = goodsPrice[cartGoods];
    
    print(cartGoodsPrice);
    

    
    goodsList.add(cartGoodsPrice);

};

print(goodsList);

var totalPrice = goodsList.reduce((sum,element) => sum +element);

    print(totalPrice);

if(totalPrice>20000){
int salePrice = totalPrice*0.9;

    print(salePrice);
    
    print("최종 결제 금액은 $salePrice원 입니다");

}


}

