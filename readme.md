# **Commands**

**Setup Symfony:**

 - `composer create-project symfony/website-skeleton my-project`
 - `php bin/console server:run`

**Other Symfony commands:**

 - `php bin/console doctrine:schema:update --force - update database scheme`

**FOSUserBundle:**

 - `composer require friendsofsymfony/user-bundle "~2.0"`
 - 

**MakerBundle:**

 - `composer require symfony/maker-bundle --dev`
 - `php bin/console list make`

	 `make:command` -            Creates a new console command class
	 `make:controller` -        Creates a new controller class
	 `make:entity` -           Creates a new Doctrine entity class

	 `make:validator` -         Creates a new validator and constraint class
	 `make:voter` -             Creates a new security voter class

