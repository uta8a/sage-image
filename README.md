# sage-image
-  is licensed under GPLv3.
- This project uses dockerfile of [sagemath/sage](https://github.com/sagemath/sage/tree/develop/docker)
- 現在変更点は特になく、今後CTFや暗号の勉強用に整備します

```
docker build -t uta8a/sage .
docker run -it -p 8888:8888 --rm uta8a/sage
```