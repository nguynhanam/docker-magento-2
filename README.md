Docker for magento 2 with all necessary extendsion
- Add your project folder in /src/
- Change nginx file in /nginx/nginx.conf:
 + server.name: with your alias
 + set $MAGE_ROOT /src/magento2; => /src/{Your project}
- Change docker-compose.yml:
 + All volumns line have /src/magento with /src/{Your project}
 + Your database info (database name, database root password)
