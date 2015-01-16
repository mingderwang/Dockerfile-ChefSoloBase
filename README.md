## Usage

Replace authorized_keys to your public key.

    $ cp ~/.ssh/authorized_keys ./authorized_keys
    $ docker build -t marcie001/chefbase .
    $ docker run -d marcie001/chefbase

`knife solo bootstrap foo` to run chef-solo
