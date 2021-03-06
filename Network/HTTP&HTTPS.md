## 질문 LIST & 간단 답변

#### 💡 HTTP와 HTTPS를 설명해주세요
- HTTP는 인터넷 통신을 할 때 사용하는 TCP/IP 기반의 프로토콜입니다.
- HTTPS는 기존 HTTP 프로토콜에서 보인계층(SSL, TLS)을 더하여 보안이 강화된 프로토콜입니다.

#### 💡 HTTP의 단점과 HTTPS를 사용하는 설명해주세요



#### 💡그렇다면 HTTPS의 단점은 없나요?
- HTTPS 프로토콜은 SSL을 사용하기 때문에 처리가 늦어진다는 단점이 있습니다.
- 서버와 클라이언트가 데이터를 주고받을 때, 양쪽 **모두 암복호화 처리**가 필요하기 때문에 통신 처리에 시간이 걸리고 하드웨어나 네트워크 리소스를 더 많이 소비하게 됩니다.
- (HTTPS는 HTTP에 비해 약 2~100배 느리다고 한다)

#### 💡HTTP 1.1과 HTTP 2.0의 차이점은 무엇인가요?

#### 💡HTTP는 왜 비연결성인가요?

#### 💡모든 웹 페이지에서 HTTPS를 사용하지 않는 이유를 설명해주세요
- 평문통신인 HTTP보다 훨씬 처리속도가 느리고, 리소스를 더 많이 소비하기 때문입니다.
- 또한, HTTPS를 사용하기 위해서는 인증기관(CA)을 통해 증명서를 구입해야 하는데 이 가격이 부담되는 서비스들은 HTTPS 대신 HTTP을 사용하기도 합니다.

#### 💡비대칭키 또는 공개키 암호화 방식은 무엇인가요?
- [https://wayhome25.github.io/cs/2018/03/11/ssl-https/](https://wayhome25.github.io/cs/2018/03/11/ssl-https/)

#### 💡HTTP 메소드의 종류에 대해 설명해주세요

#### 💡HTTP Request 방식 중 GET과 POST의 차이를 설명해주세요

#### 💡HTTP Request 방식 중 PUT과 PATCH의 차이를 설명해주세요

#### 💡조회하기 위한 용도로 POST가 아닌 GET을 사용하는 이유는 무엇인가요?

#### 💡현대 웹에서 비연결성을 해결하는 방법에 대해 설명해주세요

---

## 추가 질문

#### 💡 SSL와 TLS은 무엇인가요?
- SSL (Secure Socket Layer)
- TLS (Transport Layer Security)

#### 💡 SSL에서 사용되는 암호화방식에 대해 간단히 설명해주세요
