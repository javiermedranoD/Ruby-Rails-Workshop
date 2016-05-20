# Ruby &amp; Rails Workshop Requeriments (Ruby on Rails Installation Tutorial)

## Requisitos para asistir al taller:



### Instalar Git (si no se tiene ya):

```bash
$ \curl -sSL https://get-git.rvm.io | sudo bash
```

 
 =====================================================================
 

### Instalar un gestor de versiones de Ruby (elegir solo uno):



#### rbenv:

 * Instalar rbenv:
 ```bash
 $ git clone https://github.com/sstephenson/rbenv.git ~/.rbenv
 ```

 * Añadir rbenv al $PATH:

 - Mac:
 ```bash
 $ echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bash_profile
 ```

 - Linux:
 ```bash
 $ echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bashrc
 ```

 - Zsh:
 ```bash
 $ echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.zshrc
 ```

 * Añadir rbenv al autocompletado:

 - Mac:
 ```bash
 $ echo 'eval "$(rbenv init -)"' >> ~/.bash_profile
 ```

 - Linux:
 ```bash
 $ echo 'eval "$(rbenv init -)"' >> ~/.bashrc
 ```

 - Zsh:
 ```bash
 $ echo 'eval "$(rbenv init -)"' >> ~/.zshrc
 ```

 * Cerrar el terminal para reiniciar la shell y probar que se ha instalado correctamente:
 ```bash
 $ type rbenv
 ```

 * Instalar ruby-build:
 ```bash
 $ git clone https://github.com/sstephenson/ruby-build.git ~/.rbenv/plugins/ruby-build
 ```
 
 =====================================================================
 
##### NOTA: Si se usa Mac o Linux, se puede instalar todo a través de Homebrew:

 * Instalar Homebrew (si no se tiene ya):

 - Mac:
```bash
$ ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

 - Linux:
```bash
$ ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Linuxbrew/install/master/install)"
```

 * Actualizar Homebrew:
```bash
$ brew update
```

 * Instalar rbenv:
```bash
$ brew install rbenv ruby-build
```

 * Añadir rbenv al autocompletado:

 - Mac:
 ```bash
 $ echo 'eval "$(rbenv init -)"' >> ~/.bash_profile
 ```

 - Linux:
 ```bash
 $ echo 'eval "$(rbenv init -)"' >> ~/.bashrc
 ```

 - Zsh:
 ```bash
 $ echo 'eval "$(rbenv init -)"' >> ~/.zshrc
 ```
 
 =====================================================================
 
 * Ver versiones de Ruby:
 ```bash
 $ rbenv install -l
 ```

 * Instalar una versión de Ruby:
 ```bash
 $ rbenv install 2.3.1
 ```

 * Usar una versión de Ruby por defecto:
 ```bash
 $ rbenv global 2.3.1
 ```

 * Recargar configuración de la shell:
 ```bash
 $ rbenv rehash
 ```

 * Probar versión de Ruby:
 ```bash
 $ ruby -v
 ```

 * Probar que se está usando rbenv:
 ```bash
 $ which ruby
 ```

 
 =====================================================================
 

#### RVM:

 * Instalar RVM:
 ```bash
 $ \curl -sSL https://get.rvm.io | bash -s stable --rails
 ```

 * Recargar configuración de la shell:
 ```bash
 $ source ~/.rvm/scripts/rvm
 ```

 * Probar que se ha instalado correctamente:
 ```bash
 $ type rvm | head -n 1
 ```

 * Ver versiones de Ruby:
 ```bash
 $ rvm list known
 ```

 * Instalar una versión de Ruby:
 ```bash
 $ rvm install 2.3.1
 ```

 * Usar una versión de Ruby por defecto:
 ```bash
 $ rvm use 2.3.1 --default
 ```

 * Probar versión de Ruby:
 ```bash
 $ ruby -v
 ```

 * Probar que se está usando RVM:
 ```bash
 $ which ruby
 ```

 
 =====================================================================
 

#### Si te parece muy complicado, puedes probar [RailsInstaller](http://railsinstaller.org)

 
 =====================================================================
 

### Instalar [PostgreSQL](http://www.postgresql.org/download/) (si no se tiene ya).

 
 =====================================================================
 

### Crearse una cuenta en [Heroku](https://id.heroku.com/signup) (si no se tiene ya).


### Instalar [Heroku Toolbelt](https://toolbelt.heroku.com) (si no se tiene ya).
##### En Mac se puede instalar con:
```bash
$ brew install heroku-toolbelt
```

 
 =====================================================================
 

### Instalar las gemas que se van a usar:

```bash
$ gem install bundler

$ gem install json

$ gem install pg

$ gem install unicorn

$ gem install sinatra

$ gem install therubyracer

$ gem install rails

$ gem install devise

$ gem install twitter-bootstrap-rails
```


