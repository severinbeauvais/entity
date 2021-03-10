# RFC for Create UI architecture to support new filing types

- Start Date: (2021-03-10)
- Target Major Version: None
- Epic Ticket #: https://github.com/bcgov/entity/issues/6705
- RFC Ticket #: https://github.com/bcgov/entity/issues/6733
- Implementation PR(s): Will be created and groomed under Epic

# Summary

The Create UI web app is currently implemented to allow a user to create a Benefit Company (BEN) Incorporation
Application (IA) filing.

This web app will be updated to support many other types of incorporation and continuation filings.

The purpose of this RFC is to propose/communicate and allow discussion on architectural changes to the subjectweb app
to support these other filings. The goals are to:
- speed up the addition of new types of filings
- promote maximum reuse of existing architecture, components and other code
- minimize future large refactors
- apply best practices learned in the development of other BCROS web apps

For consideration:
- unit testing parameterization?
- increased use of common and shared components

# Prototype

_TBD_

# Motivation

_TBD_

# Main Options Considered

_TBD_

# Still To Do

_TBD_

# References

- https://github.com/bcgov/bcrs-business-create-ui
- https://github.com/bcgov/bcrs-shared-components


# Thanks

This template is heavily based on the Vue, Golang, React, and other RFC templates. Thanks to those groups for allowing
us to stand on their shoulders.
