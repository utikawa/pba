pba
===

Pattern-Based Archiver é uma nova abordagem para o processo de compressão de arquivos. Ao invés de criar tabelas de sequências identificadas no arquivo sendo comprimido, agregando estas tabelas ao arquivo resultante do processo, as tabelas de sequências serão padrão  e assim não constarão do arquivo final. Desta forma o arquivo resultante poderá ser muito menor que um arquivo utilizando métodos tradicionais pois não irá conter os dados propriamente ditos mas apenas uma "receita" de como se reconstruir o arquivo original.