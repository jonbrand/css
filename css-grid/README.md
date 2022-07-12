# CSS GRID

## GRID

- Bidimensional
- Divisão de toda a pagina em linha e colunas
- Colocar elementos onde quiser nessa divisão

## GRID OU FLEXBOX

- Grid: Duas dimensões (colunas e linhas)
- Flexbox: Uma dimensão (ou coluna ou linha)
- Verificar quais navegadores ainda não estão aceitando o Grid

## Propriedades

### CONTAINER
- display: grid | Vai definir se e grid;
- grid-template-columns | Define as colunas;
- grid-template-rows | Define as linhas;
- grid-gap | Define os espaçamentos
    - grid-row-gap
    - grid-column-gap
- grid-template-areas | Define áreas entre grids;

### ITEM(s)

- grid-column | onde começa e onde terminal o item na coluna
    - grid-column-start
    - grid-culumn-end
- grid-row | onde começa e onde terminal o item na linha
    - grid-row-start
    - grid-row-end
- grid-area | representação de um item

## GRID: Alinhamento

### Content

justify-content e align-content nos permite alinhar o próprio grid, relativo ao espaço fora do grid.

O uso dessas propriedades são raras, pois só é aplicado caso o grid seja menor que a area definida. (Por exemplo, quando usamos em px o tamanho do grid, poderemos terminar com um grid pequeno, para o tamanho da area do grid)

Podemos usar 7 valores:

start
end
center
stretch
space-between
space-around
space-evenly


### Items
justify-items e align-items vai permitir alinhar os items do nosso grid, em qualquer espaço disponível, na célula que ele habitar.

Podemos usar 4 valores:

start
end
center
stretch

### Self
justify-self e align-self vai nos permitir alinhar o item em si.

Faz a mesma coisa que o justify-items e align-items, porém, aplicado diretamente no item de um grid