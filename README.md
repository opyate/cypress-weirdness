Running with

```
docker-compose up --exit-code-from cypress
```

Outputs:

```
WARNING: using --exit-code-from implies --abort-on-container-exit
Creating e2e_cypress_1 ... done
Attaching to e2e_cypress_1
cypress_1  | npm ERR! code 1
cypress_1  | npm ERR! path /e2e/node_modules/cypress
cypress_1  | npm ERR! command failed
cypress_1  | npm ERR! command sh -c node index.js --exec install
cypress_1  | npm ERR! [STARTED] Task without title.
cypress_1  | npm ERR! [SUCCESS] Task without title.
cypress_1  | npm ERR! [STARTED] Task without title.
cypress_1  | npm ERR! The Cypress App could not be unzipped.
cypress_1  | npm ERR! 
cypress_1  | npm ERR! Search for an existing issue or open a GitHub issue at
cypress_1  | npm ERR! 
cypress_1  | npm ERR! https://github.com/cypress-io/cypress/issues
cypress_1  | npm ERR! 
cypress_1  | npm ERR! ----------
cypress_1  | npm ERR! 
cypress_1  | npm ERR! Error: EACCES: permission denied, mkdir '/root/.cache/Cypress/9.4.1'
cypress_1  | npm ERR! 
cypress_1  | npm ERR! ----------
cypress_1  | npm ERR! 
cypress_1  | npm ERR! Platform: linux-x64 (Debian - 10.11)
cypress_1  | npm ERR! Cypress Version: 9.4.1
cypress_1  | npm ERR! [FAILED] The Cypress App could not be unzipped.
cypress_1  | npm ERR! [FAILED] 
cypress_1  | npm ERR! [FAILED] Search for an existing issue or open a GitHub issue at
cypress_1  | npm ERR! [FAILED] 
cypress_1  | npm ERR! [FAILED] https://github.com/cypress-io/cypress/issues
cypress_1  | npm ERR! [FAILED] 
cypress_1  | npm ERR! [FAILED] ----------
cypress_1  | npm ERR! [FAILED] 
cypress_1  | npm ERR! [FAILED] Error: EACCES: permission denied, mkdir '/root/.cache/Cypress/9.4.1'
cypress_1  | npm ERR! [FAILED] 
cypress_1  | npm ERR! [FAILED] ----------
cypress_1  | npm ERR! [FAILED] 
cypress_1  | npm ERR! [FAILED] Platform: linux-x64 (Debian - 10.11)
cypress_1  | npm ERR! [FAILED] Cypress Version: 9.4.1
cypress_1  | 
cypress_1  | npm ERR! A complete log of this run can be found in:
cypress_1  | npm ERR!     /root/.npm/_logs/2022-02-04T23_31_53_957Z-debug.log
e2e_cypress_1 exited with code 1
Aborting on container exit...
```

Not sure where `9.4.1` comes from, as it's not referenced anywhere.
What can I do to make this work regardless?

