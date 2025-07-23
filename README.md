# Домашнее задание к занятию 2 «Работа с Playbook»

1. Подготовьте свой inventory-файл prod.yml.

ссылка на [prod.yml](https://github.com/vladmgb/hw-playbook/blob/main/playbook/inventory/prod.yml)

2. Допишите playbook: нужно сделать ещё один play, который устанавливает и настраивает vector.

ссылка на [templates](https://github.com/vladmgb/hw-playbook/tree/main/playbook/templates)

ссылка на [site.yml](https://github.com/vladmgb/hw-playbook/blob/main/playbook/site.yml)
   

5. Запустите ansible-lint site.yml и исправьте ошибки, если они есть.

Ошибок нет:

<img width="1233" height="475" alt="image" src="https://github.com/user-attachments/assets/af536487-aeb5-4623-bcec-50cadfafad03" />

6. Попробуйте запустить playbook на этом окружении с флагом --check.

<img width="1132" height="664" alt="image" src="https://github.com/user-attachments/assets/5d130096-f995-4d6d-abb9-ab055d8cf1e5" />
<img width="1139" height="67" alt="image" src="https://github.com/user-attachments/assets/d41ef55a-b8a5-448d-a305-70bc721aae18" />

7. Запустите playbook на prod.yml окружении с флагом --diff. Убедитесь, что изменения на системе произведены.

<img width="1137" height="675" alt="image" src="https://github.com/user-attachments/assets/1ea6bca2-edff-4f6a-a46a-175e14e71500" />
<img width="1134" height="76" alt="image" src="https://github.com/user-attachments/assets/68b8c291-3787-4e98-8d39-3a3d96acb886" />


8. Повторно запустите playbook с флагом --diff и убедитесь, что playbook идемпотентен.

<img width="1135" height="657" alt="image" src="https://github.com/user-attachments/assets/ba4b36d5-b872-4777-b679-80214697d103" />
<img width="1138" height="77" alt="image" src="https://github.com/user-attachments/assets/a59c9e56-1583-44ae-884a-19943cb85cd9" />


9. Подготовьте README.md-файл по своему playbook.

    ссылка на [README.md](https://github.com/vladmgb/hw-playbook/blob/main/playbook/README.md)

10. Готовый playbook выложите в свой репозиторий

    ссылка на [playbook](https://github.com/vladmgb/hw-playbook/tree/main/playbook)
