#Compile pug
cd pug
pug -w ./ -o ./../ -P

#Compile SASS
sass assets/scss/styles.scss assets/css/style.css