/ 

    - src/
        index.js // main server file
        models/
        config/
        controllers/
        uitls/
        services/
        repository/
        middlewares/
    - tests/ [later]
    - static/
    - temp/

// when deploying we will only required and required are kept inside src folder
// we are going with role based architecture instead of feature based
// In feature based
    // each feature will have seperate models,controllers and so on

cd src/
    // tree

rm -rf file_name

// npx executes a package or a command from a package
// we use 
    // npx squelize init

// using sequelize and sequelize-cli for orm works
// using mysql2 driver to let sequelizer connect to mysql server
// npx sequelize init 
    // creates models,migrations,config,seeders folders
    // moved those into src
// npx sequelize db:create
    // creates a db based on the config set in the config folder