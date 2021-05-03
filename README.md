# CUDA-streams
A stream in CUDA is a sequence of operations that execute on the device in the order in which they are issued by the host code. While operations within a stream are guaranteed to execute in the prescribed order, operations in different streams can be interleaved and, when possible, they can even run concurrently.

For more info : https://developer.nvidia.com/blog/how-overlap-data-transfers-cuda-cc/
