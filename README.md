# 考試題目

1. 分別寫出Js的資料型別

2. 解釋var、const、let的區別

3. 何謂作用域(Scope)

4. 何謂提升(Hoisting)

5. let 跟 const 有 hoisting 嗎

6. 何謂非同步及同步

7. 何謂function

8. 何謂閉包

9. this到底指向哪裏

10. 何謂傳值傳址

11. 何謂淺拷貝及深拷貝

12. 甚麼時機或情況會使用到Promise物件

13. 寫出一個簡單的閉包範例

14. 已知 
for( var i = 0; i < 5; i++ ) {
  setTimeout(function() {
    console.log(i);
  }, 1000);
}
列印出來都是5，修改其寫法讓他可以列印1 2 3 4(有兩種方法都必須寫出來)

15. const hero = {
    _name: 'John Doe',
    getSecretIdentity: function (){
        return this._name;
    }
};

const stoleSecretIdentity = hero.getSecretIdentity;

console.log(stoleSecretIdentity());
console.log(hero.getSecretIdentity());

問stoleSecretIdentity()及hero.getSecretIdentity()各印出甚麼，以及為什麼是這個答案

16. 針對一組字串回傳第一個大寫字母以及它的 index，若沒有大寫就回傳-1，如"i'm your Father go sell matches!!!"，回傳[F, 9]

17. 回傳陣列總和，如[1,2,3,4,5]，回傳15

18. function sayHi() {
console.log(name)
console.log(age)
var name = 'Lydia'
let age = 21
}
sayHi()
會輸出甚麼
A: Lydia 和 undefined
B: Lydia 和 ReferenceError
C: ReferenceError 和 21
D: undefined 和 ReferenceError

19. && || 各是甚麼意思

20. == ===有甚麼不同