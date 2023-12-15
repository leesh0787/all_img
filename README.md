# all_img

# 개발자모드 -> 네트워크 -> img -> 복사
![image](https://github.com/leesh0787/all_img/assets/131154479/356e1e90-4ad0-42b9-a47f-fcccb483498d)

# console창에 변수를 만든다

# var har = 위에 복사한 내용을 붙여넣는다 (그 값은 객체이다)

var har = {복사한내용}

# 객체가 har이라는 변수에 할당되었고 그 아래에
  ```
var imageUrls = [];
har.log.entries.forEach(function (entry) {
  if (entry.response.content.mimeType.indexOf("image/") !== 0) return;
  imageUrls.push(entry.request.url);
});
console.log(imageUrls.join('\n'));
  ```
을 console에 붙여넣으면 전체 이미지 주소가 일괄적으로 나타난다.

짜잔 🤗 
![image](https://github.com/leesh0787/all_img/assets/131154479/dd7969d8-c883-4ebf-8c9e-d922f7a50234)

