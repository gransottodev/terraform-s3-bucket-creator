## Terraform AWS Bucket Creator

🚀 Criação automática de infraestrutura através de código utilizando Terraform e AWS Simple Storage Service(S3)


### Como criar seu bucket.

1. Crie uma nova Issue nesse repositório
 
![Captura de tela 2024-04-04 144725](https://github.com/gransottodev/terraform-s3-bucket-creator/assets/101595139/864f8aad-c70a-40e3-90fc-8424d6570327)

3. Escolha um título para seu bucket com letras minúsculas, sem acentuação e dividida por hífen (-) e clique em "Submit new Issue".

![Captura de tela 2024-04-04 145254](https://github.com/gransottodev/terraform-s3-bucket-creator/assets/101595139/558b81d8-552a-42d9-885d-81418662a500)


### Funcionamento
Ao criar uma nova issue um gatilho do github actions é acionado:
</br>

![image](https://github.com/gransottodev/terraform-s3-bucket-creator/assets/101595139/5ebbb1a1-146b-4c72-be55-5df15431868e)

Essa action tem o papel de acessar a aws e executar o terraform  para criação do bucket.

![image](https://github.com/gransottodev/terraform-s3-bucket-creator/assets/101595139/ecf9b747-abd8-472f-8deb-835e017b49bb)


Com o sucesso da action o Bucket S3 é criado.

![image](https://github.com/gransottodev/terraform-s3-bucket-creator/assets/101595139/7d38c941-dfd1-46cc-b7fa-95431789d8a0)

E uma mensagem é retornada para a issue confirmando a criação, tudo isso de forma automática e replicável.


![image](https://github.com/gransottodev/terraform-s3-bucket-creator/assets/101595139/92b8a423-4fec-4cb0-b871-46e9a18a9ed9)



Uma automação como essa pode ser de grande ajuda para times que precisam repetir certas ações cotidianamente, os livrando de confirguações repetitivas dentro
de um ambiente de cloud.
