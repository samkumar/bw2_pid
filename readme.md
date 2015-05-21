# Bosswave2 Payload Object ID allocations

## Motivation

Part of the problem with a pub/sub overlay network that has multiple vendors
and a wide namespace is that it is not always easy to determine what the actual
payload of a given URI is. This manifest hopes to provide enough structure that
programs and programmers can meaningfully consume services by third parties.

It is present in its own repository so that pull requests can be as trivial
as possible. Fork this repo, claim your own range of PIDs and submit a pull
request. As long as your IDs do not clash with existing ones and as long as
they obey the constraints set by the class they are in, the PR will be accepted.
