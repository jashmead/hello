Commands are:

git bits:
    -- git add .
    -- git commit -a
    -- git push -- ship to git
    -- git push heroku master -- ship to heroku (must login first)

heroku bits:
    heroku create -- to start (once per directory)
    heroku open -- to open on heroku
    heroku login
    heroku logout

tests:
    -- open up a server with foreman, then turn on browser
    -- turn on browser to heroku location

automated testing?
    -- not at start

monitoring:
    heroku ps
    heroku logs

todos:
    -- automate gits
        -- need better understanding of 'remote' & related
        -- read pro git (238 pages)
    -- automate heroku credentials
        tried:
            heroku keys:add
            -- timed out for both ssh keys
            -- need better understanding of ssh/heroku (and of ssh and heroku)
            -- we did this before!
    -- automate tests
        -- see flask tutorial

