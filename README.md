# Proyecto-Aaron
La función de este README es ser una carpeta de archivos necesarios para proyecto de aaron
```text
Proyecto-Aaron/
├── entorno_docking/
│   ├── 1_archivos_originales/
|   |   ├── canon/
|   |   |   ├── RpoS.pdb
|   |   |   └── RssB.pdb
|   |   └── new/
|   |       └── SWAP_completo.pdb
│   └── 2_archivos_nuevos/
|       ├── complejo_final_rpos_swap.pdb
|       ├── complejo_rpos_rssb.pdb
|       ├── complejo_rpos_swap.pdb
|       └── proyecto_completo.cxs
├── figuras articulo/
│   ├── figuras principales/
│   │   ├── Biofilm # adentro se encuntra el .png de cada figura
|   |   ├── Cinetica # 
|   |   ├── Dockin Molecular #
|   |   ...
|   |   └── UMAP #
│   └── figuras suplementarias/
|       ├── crecimiento/ #
|       ├── gel/ #
|       ├── rin/ #
|       ├── sanger/ #
|       └── vectores/ #
├── scripts python/
|   ├── bioanalaiser.ipynb # código para generar imagenes de gráficas
|   ├── Biofilm_cuant.ipynb #
|   ...
|   └── time_course.ipynb #
├── README.md
├── secuencias/
|   ├── E.coli (control)/
|   |   ├── genes/
|   |   |   ├── rpoS/
|   |   |   |   └── rpoS_ECOLI.fasta
|   |   |   └── rssB/
|   |   |       └── rssB_ECOLI.fasta
|   |   ├── proteinas/
|   |   |   ├── RpoS/
|   |   |   |   └── RpoS_ECOLI.fasta
|   |   |   └── RssB/
|   |   |       └── RssB_ECOLI.fasta
|   |   └── proteinas_pdb/
|   |       └── ... # Son iguales que los .pdb de entorno docking
|   ├── P.commutabilis (objetivo)/
|   |   ├── genes/
|   |   |   ├── rpoS/
|   |   |   |   └── rpoS_PCOM.fasta
|   |   |   └── swap1/
|   |   |       └── swap1.fasta
|   |   └── proteinas/
|   |       ├── RpoS/
|   |       |   └── RpoS_PCOMM.fasta
|   |       └── SWAP1/
|   |          └── SWAP1_PCOMM.fasta
|   └── primers/
|       ├── primers_gibson/
|       |   └── primers_gibson.txt
|       ├── primers_mutagenesis/
|       |   └── primers_mutagenesis.txt
|       └── primers_simple/
|           └── primers_simple.txt
└── descripción_proyecto_aaron.txt # lo usé al principio pero está muy desactualizado

```

## Guía de Navegación del Proyecto ( o_o )

Para ayudarle, aquí tienes dónde encontrar cada cosa:

### ( * _ * ) Resultados Visuales
Si busca las imágenes finales para el artículo, dirígete a **`figuras articulo/`**.
* En **`figuras principales/`** están los gráficos clave (Biofilm, Cinética, Docking, UMAP).
* En **`figuras suplementarias/`** encontrarás los datos de soporte (geles, curvas, etc.).

### ( >_< ) Código y Análisis
Todo el procesamiento de datos está en **`scripts python/`**.
* Contiene los *Jupyter Notebooks* (`.ipynb`) para generar las gráficas y analizar cuantificaciones (como `bioanalaiser.ipynb`).

### ( O.O ) Estructuras y Docking
Los inputs y resultados del modelado molecular está en **`entorno_docking/`**.
* **Input:** Los PDB originales (RpoS, RssB) en `1_archivos_originales/`.
* **Output:** Los modelos predichos de los complejos y sesiones `.cxs` en `2_archivos_nuevos/`.

### ( ~_~ ) Secuencias y Primers
Las secuencias tanto de nucleótidos como aminoácidos está en **`secuencias/`**.
* Separado por organismo: **`E.coli (control)/`** y **`P.commutabilis (objetivo)/`**.
* Si buscas los oligos para clonación o mutagénesis, revisa la carpeta `primers/`.

---
> **Nota ( u_u )**: El archivo `descripción_proyecto_aaron.txt` es un remanente antiguo. Ignórelo, este README contiene la info real.
