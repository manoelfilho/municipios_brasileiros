O arquivo SQL contém todos os estados e municípios do Brasil. Além dos dados básicos como nome do estado, região do Brasil, nome do município e códigos do IBGE de 2010, a tabela de municípios disponibiliza todas as coordenadas para geração de coordenadas no formato de arquivo GEOjson. Com este tipo de arquivo é posssível fazer sobreposições de camadas em projetos como o Google Maps.

Dicas sobre o uso com o google maps: 
https://developers.google.com/maps/documentation/javascript/datalayer?hl=pt-br


A tabela de municípios:
municipio	text
estado_id	int(11)
cod_ibge	int(11)
populacao	int(11)
latitude	float
longitude	float
coordenadas	longtext


A tabela estados:
sigla	char(2)
estado	varchar(255)
regiao	varchar(15)
latitude	float
longitude	float
