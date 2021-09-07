# MinIO

Run in linux

docker run \
-p 9000:9000 \
-p 9001:9001 \
--name minio1 \
-v /mnt/data:/data \
-e "MINIO_ROOT_USER=AKIAIOSFODNN7EXAMPLE" \
-e "MINIO_ROOT_PASSWORD=wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY" \
quay.io/minio/minio server /data --console-address ":9001"


Run in mac
brew install minio/stable/minio
minio server <path where you want bucket to be created>


Start application on any por other than 9090.
