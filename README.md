# Bitnami Moodle
<h3>Langkah A</h3>
mkdir mariadb_data moodle_data moodledata_data<br/>
curl -sSL https://raw.githubusercontent.com/masihgurutkj/bitnamimoodle/main/docker-compose.yml > docker-compose.yml<br/>
docker-compose up -d<br/><br/>
<h3>Langkah B</h3>
git clone https://github.com/masihgurutkj/bitnamimoodle.git <br/>
cd bitnamimoodle<br/>
docker-compose up -d <i>#start container</i><br/>
docker-compose down <i>#stop container</i>
