# Overtime App

## Key requirement: company needs documentation that salaried employees did or did not get overtime each week

## Models
- x Post -> date:date rationale:text
- x User -> Devise
- x AdminUser -> STI
- x AuditLog

## Features:
- x Approval Workflow
- x SMS Sending -> link to approval or overtime input
- x Administrate admin dashboard
- x Block non admin and guest users
- x Email summary to managers for approval
- x Needs to be documented if employee did not log overtime
- x Create audit log for each text message
- x Update the end date when an audit log is confirmed.
- x Update audit log status when an overtime is rejected.
- x Add a home icon for the homepage
- x Update buttons on employee homepage so they show on mobile.
- x Add the full date range in each button.
- x Update button sort order on employee homepage
- x Remove "entries" and "Request overtime" buttons for managers.
- x Fix a bug in admin dashboard. I think this should be more a configuration setting we need to update.
- Implement honeybadger for error reporting *paid
- Implement new relic for keeping the site alive *paid

## TODOS:


- Heroku web address: https://wlp-overtime2.herokuapp.com/