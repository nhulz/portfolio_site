# Middleman Template: ZURB Foundation #

middleman-zurb-foundation is a minimal [Middleman](http://middlemanapp.com/) project template with the [SASS](http://sass-lang.com/) version of the [ZURB Foundation](http://foundation.zurb.com/) Framework.

## Installation ##

Make sure to have:

1. ruby
1. git
1. middleman ($ `gem install middleman`)
1. bower ($ `npm install -g bower`)


Clone into ~/.middleman (you'll have to create this directory if it's not already there). You can then use it with the `--template` flag on `middleman init`.

1. $ `git clone git://github.com/axyz/middleman-zurb-foundation.git ~/.middleman/zurb-foundation`

Then create a new project using zurb-foundation template.

1. $ `middleman init my_new_project --template=zurb-foundation`
1. $ `cd my_new_project`
1. $ `bower install`
1. $ `bundle exec middleman`

Now you can start hacking on `source` directory and watch live changes on [localhost:4567](http://localhost:4567).

For more help follow [Middleman's project template instructions](http://middlemanapp.com/getting-started/welcome/) or feel free to hit me up on [Twitter](http://twitter.com/axyz).

## ZURB Foundation License ##

Copyright (c) 2011 ZURB, http://www.zurb.com/

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.








    <!-- Navigation -->
    <nav class="navbar navbar-inverse navbar-fixed-top" role="navigation">
       <!--  <div class="container"> -->
            <!-- Brand and toggle get grouped for better mobile display -->
            <div class="navbar-header">
                <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1">
                    <span class="sr-only">Toggle navigation</span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                </button>
                <a class="navbar-brand" href="#">Nathan Hulsey</a>
            </div>
            <!-- Collect the nav links, forms, and other content for toggling -->
            <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
                <ul class="nav navbar-nav">
                    <li>
                        <a href="#">About</a>
                    </li>
                    <li>
                        <a href="#">Services</a>
                    </li>
                    <li>
                        <a href="#">Contact</a>
                    </li>
                </ul>
            </div>
            <!-- /.navbar-collapse -->
        <!-- </div> -->
        <!-- /.container -->
    </nav>