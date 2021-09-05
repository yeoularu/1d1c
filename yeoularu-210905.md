## Destructuring

노마드코더 es6 강의를 들었다.

destructuring은 안의 내용을 밖으로 꺼내서 사용할 수 있도록 하는 개념인데, 사전적으로는 ~의 구조를 파괴[헤체]하다 이런 뜻이다.

```javascript
const {
  element,
  level1: { level2 },
  renaming: renamed,
  ifNotExist = "defaultValue",
} = aObject;

const [firstElm, second, third] = aArray;
const [a, b, c] = aArrayFunction();

let something;
({ something } = updateVar);

function doSomething({ elm1 }) {
  console.log(elm1);
}
```

으악
