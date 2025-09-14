## ✅ Основні команди Docker

### 🔹 Контейнери

-   **Переглянути всі контейнери (запущені та зупинені):**
    
    `docker ps -a` 
    
-   **Запустити контейнер:**
    
    `docker start <container_name_or_id>` 
    
-   **Зупинити контейнер:**
    
    `docker stop <container_name_or_id>` 
    
-   **Видалити зупинений контейнер:**
    
    `docker rm <container_name_or_id>` 
    
-   **Видалити всі зупинені контейнери:**
    
    `docker container prune` 
    
-   **Видалити всі контейнери (запущені та зупинені):**
    
    `docker rm $(docker ps -a -q)` 
    

### 🔹 Образи

-   **Переглянути всі образи:**
    
    `docker images` 
    
-   **Видалити образ:**
    
    `docker rmi <image_name_or_id>` 
    
-   **Видалити всі непотрібні образи:**
    
    `docker image prune` 
    

### 🔹 Томі (Volumes)

-   **Переглянути всі томи:**
    
    `docker volume ls` 
    
-   **Видалити том:**
    
    `docker volume rm <volume_name>` 
    
-   **Видалити всі непотрібні томи:**
    
    `docker volume prune` 
    

### 🔹 Мережі

-   **Переглянути всі мережі:**
    
    `docker network ls` 
    
-   **Видалити мережу:**
    
    `docker network rm <network_name>` 
    

### 🔹 Docker Compose

-   **Запустити контейнери в фоновому режимі:**
    
    `docker-compose up -d` 
    
-   **Зупинити та видалити контейнери:**
    
    `docker-compose down` 
    
-   **Переглянути логи контейнерів:**
    
    `docker-compose logs` 
    
-   **Перевірити статус контейнерів:**
    
    `docker-compose ps`
