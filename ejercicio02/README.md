1. Ejecute docker pull nicopaez/pingapp:3.0.0
2. Entre a dockerhub pizajuan y cree un repo (test-repo)
3. docker tag nicopaez/pingapp:3.0.0 pizajuan/test-repo:1.0.0
4. docker push pizajuan/test-repo:1.0.0
5. docker pull pizajuan/test-repo:1.0.0