# Documentation for Zoom App Place

This README is to document Zoom App Place requirements.

# Technology Stack

## Main Frameworks

| Stack         | Description                            |
| ------------- | -------------------------------------- |
| Ruby on Rails | Web Framework                          |
| ReactJS       | Frontend                               |
| Bootstrap     | Frontend                               |
| Postgres      | Database                               |
| Redis         | Background jobs, chats and actioncable |
| Sidekiq       | Background job processing              |
| Sinatra       | Sidekiq admin dashboard                |

## External Services

| Stack      | Description                                                        |
| ---------- | ------------------------------------------------------------------ |
| Salesforce | API to interact with Salesforce data, mainly for automations       |
| Contentful | API to interact with Contentful data, mainly for blogs             |
| Stripe     | Payment                                                            |
| Bitly      | API for creating short links                                       |
| Circle     | Single Sign On with community platform                             |
| Canny      | User feedback, changelogs                                          |
| AWS        | CDN, assets                                                        |
| Sendgrid   | Transactional Emails                                               |
| Uploadcare | Image processing, image storage                                    |
| Twilio     | SMS System                                                         |
| Slack      | API for notifications, some workflows to communicate with our app. |
| Zoom       | Video conference meeting, scheduling                               |

## Monitoring and CI

| Stack                                      | Description                            |
| ------------------------------------------ | -------------------------------------- |
| Skylight                                   | Rails performance monitoring           |
| Honeybadger                                | Exception, uptime, check-in monitoring |
| Papertrail                                 | System logs                            |
| Heroku Pipeline, Heroku CI, Github Actions | Continues integration                  |
