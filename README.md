# N2 topology fixture

Three services, two internal networks. `frontend` shares `frontend_net` with
`backend`; `backend` also shares `database_net` with `db`. `frontend` has no
path to `db`. Used by A.SPEC 0095 live E2E.
