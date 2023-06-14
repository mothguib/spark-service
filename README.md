# Spark-service

cp ./spark-master.service /etc/systemd/system/
cp ./run-start-master.sh /usr/local/bin
systemctl daemon-reload
sudo systemctl start spark.service
sudo systemctl enable spark.service
