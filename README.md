# CP_inferno
Computational pathology inference.

This project deals with applying inference models to virtual slides. It contains
classes and methods for sampling the virtual slide images, apply the models
(i.e. predict classes, produce masks, etc) and aggregate the results. The models
are supposed to have been trained/fitted elsewhere and, to the extent it is possible,
to have been exported in a portable format (e.g. ONNX).
