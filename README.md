luna-sysmgr-ipc (PIpc)
======================

**DEPRECATED — this library is no longer used by LuneOS.**

PIpc implemented the shared-memory/socket IPC between the retired
LunaSysMgr UI and WebAppMgr. As of 2026 no component in the LuneOS
stack includes a PIpc header or links this library; the remaining
`DEPENDS`/`pkg_check_modules` references in luna-sysmgr-common,
luna-appmanager and luna-displaymanager were build plumbing only and
have been removed on their cleanup branches.

Once the meta-webos-ports recipes drop `luna-sysmgr-ipc` from
`DEPENDS`, the recipe and this repository can be archived.
