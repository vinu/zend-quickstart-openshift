# Zend Quickstart for OpenShift Express

This is a simple quickstart for [Zend App 1.x][1] on [OpenShift Express][2].

  [1]: http://framework.zend.com/
  [2]: https://openshift.redhat.com/app/express

## Running on OpenShift Express

    rhc-create-app -a zendhello -t php-5.3

    cd zendhello
    git remote add upstream -m master git@github.com:vinu/zend-quickstart-openshift.git
    git pull -s recursive -X theirs upstream master
> Copy the Zend framework to libs/library

	cd libs/library
	git add .
	git commit -a -m 'Zend framework added'
    git push

## License

The quickstart code is licensed under the Apache License, Version 2.0: [http://www.apache.org/licenses/LICENSE-2.0.html][3]

  [3]: http://www.apache.org/licenses/LICENSE-2.0.html


