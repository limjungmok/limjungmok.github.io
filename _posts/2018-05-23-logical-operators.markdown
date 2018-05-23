---
layout: post
title:  "Logical Operators"
date:   2018-05-23 10:42:32 +0900
categories: js
---
<style>
    .paragraph {
        font-size: 14px;
        font-weight: 400;
        white-space: pre-line;
    }

    .emp {
        display: inline-block;
        padding: 0 4px;
        color: #fff;
        font-size: 12px;
        font-weight: 300;
        line-height: 18px;
        border-radius: 2px;
        letter-spacing: 2px;
        background-color: #2472f2;
    }
</style>

<p class="paragraph">논리 연산자는 주로 불리언(논리적) 값과 함께 사용됩니다.  
이때, 논리 연산자는 불리언 값을 반환합니다.  
<strong>&&</strong> 와 <strong>||</strong> 연산자는 실제로는 <strong>피연산자 중에 하나의 값을 반환</strong>하기 때문에, 
두 연산자가 Boolean 값이 아닌 <strong>값</strong>과 함께 사용되면 Boolean 값이 아닌 값을 반환할 것입니다
</p>

#### 1. && (AND)

<p class="paragraph"><strong class="emp">Expr1 && Expr2  </strong>
Expr1 이 false (또는 false로 취급 되는 값일 경우) -> Expr1 을 반환, Expr2 조건은 호출되지 않습니다.
(비교할 앞의 값이 false 이기 때문에, 뒤의 값은 확인 할 필요가 없습니다.)

Expr1 이 true (또는 true로 취급 되는 값일 경우) -> Expr2 값에 의존하여 Expr2 값이 반환됩니다.
(비교할 앞의 값이 true 이기 때문에, 뒤의 값만 확인하면 됩니다.)

Expr1, Expr2가 모두 true (또는 true로 취급 되는 값일 경우) -> true 조건을 성립하며, Expr2 값이 반환됩니다.
</p>


#### 2. || (OR)

<p class="paragraph"><strong class="emp">Expr1 || Expr2  </strong>
Expr1 이 true (또는 true로 취급 되는 값일 경우) -> Expr1 을 반환, Expr2 조건은 호출되지 않습니다.
(비교할 앞의 값이 true 이기 때문에, 뒤의값은 확인 할 필요가 없습니다.)

Expr1 이 false (또는 false로 취급 되는 값일 경우) -> Expr2 값에 의존하여 Expr2 값이 반환됩니다.
(비교할 앞의 값이 false 이기 때문에, 뒤의 값만 확인하면 됩니다.)

Expr1, Expr2 모두 false (또는 false로 취급 되는 값일 경우) -> false 조건을 성립하며, Expr2 값이 반환됩니다.
</p>

#### 3. ! (NOT)

<p class="paragraph"><strong class="emp">!Expr</strong> 
Expr 이 true (또는 true로 취급 되는 값일 경우) -> false 반환
Expr 이 false (또는 false로 취급 되는 값일 경우) -> true 반환
</p>

#### 4. Sample Code

<p data-height="950" data-theme-id="0" data-slug-hash="vjMrVP" data-default-tab="js" data-user="jeongmok" data-embed-version="2" data-pen-title="Vanilla sample Code" class="codepen">See the Pen <a href="https://codepen.io/jeongmok/pen/vjMrVP/">Vanilla sample Code</a> by JeongMok IM (<a href="https://codepen.io/jeongmok">@jeongmok</a>) on <a href="https://codepen.io">CodePen</a>.</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script> <br>

### Reference  

<a href="https://developer.mozilla.org/ko/docs/Web/JavaScript/Guide/Obsolete_Pages/Core_JavaScript_1.5_Guide/Operators/Logical_Operators" target="_blank">https://developer.mozilla.org/ko/docs/Web/JavaScript/Guide/Obsolete_Pages/Core_JavaScript_1.5_Guide/Operators/Logical_Operators</a>
