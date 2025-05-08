## Desafio 4

É necessário recuperar as informações dos vetores normais dos vértices no arquivo .OBJ (vn). Teremos então mais um atributo para os vértices da geometria, que devem ser configurados no Vertex Array Object (VAO), no código da aplicação e acrescentados a layout do vértice no vertex shader.

É necessário recuperar os coeficientes de iluminação ambiente, difusa e especular do arquivo de materiais (.mtl), que serão enviados pela aplicação para o fragment shader, onde calcularemos sua contribuição para a cor do pixel.

Para o cálculo das parcelas ambiente, difusa e especular do modelo de Phong, você pode consultar o material de apoio, que apresenta um passo-a-passo de como implementar no fragment shader usando a linguagem GLSL.

![Alt Text](https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExNDFtZnNobzczbm5sdGJsZnZ0M3dpZHFheHZpZW9qdmZybG85cmN2ayZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/k9uWUCpBSRhasDjwcD/giphy.gif)