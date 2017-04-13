# I want to try `osrm-isochrone`

- it depends on `osrm`, which provides Node.js bindings to OSRM written in C++
- `osrm` fails to install on error to fetch binary node bindings from S3
  - it uses https://www.npmjs.com/package/node-pre-gyp
- https://github.com/Project-OSRM/node-osrm is marked as deprecated
  - saying _Part of osrm-backend since 5.7_
- no information on how npm package works from new home, search brings
  - https://github.com/Project-OSRM/osrm-backend/pull/3768
    - Merges node-osrm into repo
  - https://github.com/Project-OSRM/osrm-backend/issues/3939
    - Document how to build and use [Node.js] bindings
- filled an issue https://github.com/Project-OSRM/osrm-backend/issues/3945
