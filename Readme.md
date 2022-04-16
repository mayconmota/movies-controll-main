# Instruções de uso

- Instalar componentes do backend e frontend (npm i)
- Backend na porta 5000
- Frontend na porta 3000

# Comandos utilizados para o banco de dados

CREATE TABLE movies(
    id INT PRIMARY KEY AUTO_INCREMENT,
    type INT NOT NULL,
    name VARCHAR(30) NOT NULL,
    total_ep INT,
    atual_ep INT,
    last_view DATE DEFAULT CURRENT_TIMESTAMP
)