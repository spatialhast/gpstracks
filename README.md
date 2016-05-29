# gpstracks



topojson -o bike.json --id-property name bike.geojson

bounds: 23.996192 45.361617 36.672639 50.203004 (spherical)
pre-quantization: 1.41m (0.0000127°) 0.538m (0.00000484°)
topology: 10013 arcs, 38885 points
post-quantization: 141m (0.00127°) 53.8m (0.000484°)
prune: retained 10013 / 10013 arcs (100%)

topojson -o bike.json --id-property name --q0 1e6 bike.geojson

bounds: 23.996192 45.361617 36.672639 50.203004 (spherical)
pre-quantization: 1.41m (0.0000127°) 0.538m (0.00000484°)
topology: 12026 arcs, 302606 points
post-quantization: 141m (0.00127°) 53.8m (0.000484°)
prune: retained 12026 / 12026 arcs (100%)



topojson -o bike.json --id-property name --no-quantization --simplify-proportion 0.3 bike.geojson