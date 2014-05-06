!SLIDE center

![EmberConf](http://cdn.confreaks.com/system/events/logos/162/emberconf-logo-small-original.png?1396842548)
# Recap


!SLIDE
brought to you by

## [showoff](https://github.com/puppetlabs/showoff)

(presentation software ... for developers)


!SLIDE
## Ember Inspector now works in Firefox.

[https://addons.mozilla.org/en-US/firefox/addon/ember-inspector/](https://addons.mozilla.org/en-US/firefox/addon/ember-inspector/)


!SLIDE

## Ember Data 1.0 coming soon.


!SLIDE large

> If we all realize we are climbing the same mountain ...
> we can abstract ... do away with unnecessary variations ...
#### ... find a common solution.


!SLIDE

## Ember CLI

[http://iamstef.net/ember-cli/](http://iamstef.net/ember-cli/)


!SLIDE

    npm install -g ember


!SLIDE small

    ember new my-new-app
    cd my-new-app
    ember server


!SLIDE

# [http://localhost:4200](http://localhost:4200)


!SLIDE small

    git init
    git add .
    git commit
    git add remote origin git@github.com:jehoshua02/my-new-app.git
    git push -u origin master


!SLIDE

# LET'S GET TO WORK!


!SLIDE small

# Contributor

    git clone git@github.com:jehoshua02/my-new-app.git
    cd my-new-app && npm install && bower install
    ember server


!SLIDE smaller

    $ ember server
    Livereload server on port 31929
    Serving on http://0.0.0.0:4200
    Path or pattern "ember-shim.js" did not match any files Error: Path or pattern "ember-shim.js" did not match any files
        at Object.multiGlob (/Users/employee/tmp/my-new-app/node_modules/broccoli-es6-concatenator/node_modules/broccoli-kitchen-sink-helpers/index.js:216:13)
        at /Users/employee/tmp/my-new-app/node_modules/broccoli-es6-concatenator/index.js:61:33
        at invokeCallback (/usr/local/lib/node_modules/ember-cli/node_modules/rsvp/dist/commonjs/rsvp/promise.js:228:21)
        at publish (/usr/local/lib/node_modules/ember-cli/node_modules/rsvp/dist/commonjs/rsvp/promise.js:176:9)
        at publishFulfillment (/usr/local/lib/node_modules/ember-cli/node_modules/rsvp/dist/commonjs/rsvp/promise.js:312:5)
        at flush (/usr/local/lib/node_modules/ember-cli/node_modules/rsvp/dist/commonjs/rsvp/asap.js:41:9)
        at process._tickCallback (node.js:415:13)
    Error: Path or pattern "ember-shim.js" did not match any files
    Path or pattern "ember-shim.js" did not match any files Error: Path or pattern "ember-shim.js" did not match any files
        at Object.multiGlob (/Users/employee/tmp/my-new-app/node_modules/broccoli-es6-concatenator/node_modules/broccoli-kitchen-sink-helpers/index.js:216:13)
        at /Users/employee/tmp/my-new-app/node_modules/broccoli-es6-concatenator/index.js:61:33
        at invokeCallback (/usr/local/lib/node_modules/ember-cli/node_modules/rsvp/dist/commonjs/rsvp/promise.js:228:21)
        at publish (/usr/local/lib/node_modules/ember-cli/node_modules/rsvp/dist/commonjs/rsvp/promise.js:176:9)
        at publishFulfillment (/usr/local/lib/node_modules/ember-cli/node_modules/rsvp/dist/commonjs/rsvp/promise.js:312:5)
        at flush (/usr/local/lib/node_modules/ember-cli/node_modules/rsvp/dist/commonjs/rsvp/asap.js:41:9)
        at process._tickCallback (node.js:415:13)
    Error: Path or pattern "ember-shim.js" did not match any files


!SLIDE

# Uh-oh!


!SLIDE

# "Gimme a sec ..."


!SLIDE small

    git add -f vendor/ember-shim.js
    git add -f vendor/_loader.js
    git add -f vendor/qunit-shim.js
    git commit
    git push


!SLIDE

# "Ok, pull now"


!SLIDE small

    git pull
    ember server


!SLIDE small

# [http://localhost:4200](http://localhost:4200)


!SLIDE

# SUCCESS!


!SLIDE bullets

# Broccoli
[https://www.npmjs.org/package/broccoli](https://www.npmjs.org/package/broccoli)


!SLIDE

# HTMLBars
[http://talks.erikbryn.com/htmlbars/#/10](http://talks.erikbryn.com/htmlbars/#/10)

(Coming soon?)


!SLIDE

# Ember Testing
[http://emberjs.com/guides/testing/](http://emberjs.com/guides/testing/)


!SLIDE

# WATCH EM' ALL
[http://confreaks.com/events/emberconf2014](http://confreaks.com/events/emberconf2014)


!SLIDE

# Tom Dale on Ember and Javascript Frameworks
[http://www.infoq.com/interviews/tom-dale-ember](http://www.infoq.com/interviews/tom-dale-ember)


!SLIDE smbullets small

# Links

+ Ember Inspector for Firefox: [https://addons.mozilla.org/en-US/firefox/addon/ember-inspector/](https://addons.mozilla.org/en-US/firefox/addon/ember-inspector/)
+ Ember Data: [https://github.com/emberjs/data](https://github.com/emberjs/data)
+ Ember CLI: [http://iamstef.net/ember-cli/](http://iamstef.net/ember-cli/)
+ Broccoli: [https://www.npmjs.org/package/broccoli](https://www.npmjs.org/package/broccoli)
+ HTMLBars: [https://github.com/tildeio/htmlbars](https://github.com/tildeio/htmlbars)
+ Ember Testing Guide: [http://emberjs.com/guides/testing/](http://emberjs.com/guides/testing/)
+ EmberConf 2014 Talks: [http://confreaks.com/events/emberconf2014](http://confreaks.com/events/emberconf2014)
+ Tom Dale Interview: [http://www.infoq.com/interviews/tom-dale-ember](http://www.infoq.com/interviews/tom-dale-ember)

![Tomster](http://www.gravatar.com/avatar/0cf15665a9146ba852bf042b0652780a?s=200)
