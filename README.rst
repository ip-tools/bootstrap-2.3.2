###############
Bootstrap 2.3.2
###############


*****
About
*****
Yes, this is the ancient Bootstrap 2.3.2 taken from https://www.npmjs.com/package/bootstrap-2.3.2.

While that 1.0.0 release contains the vanilla version,
versions 2.0.0 and greater add some improvements:

- jQuery 3 compatibility


***************
Troubleshooting
***************
To mitigate the »Couldn't find preset "env" relative to directory« error
after linking this into other projects,
we had to run ``yarn add --dev babel-preset-env`` here, see also
https://github.com/babel/babel-preset-env/issues/186#issuecomment-288833343
