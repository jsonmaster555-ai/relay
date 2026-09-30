# Relay release checklist

- [ ] Build the production macOS app
- [ ] Confirm app name and version
- [ ] Sign the app with the intended Apple Developer ID
- [ ] Notarize the app when distribution signing is configured
- [ ] Package the signed app as `Relay.dmg`
- [ ] Test installation on a clean macOS account or machine
- [ ] Confirm sign-in and Relay Cloud connectivity
- [ ] Confirm event stream, endpoints, retries, replay, and payload inspection
- [ ] Update `CHANGELOG.md`
- [ ] Create a GitHub Release tagged `vX.Y.Z`
- [ ] Attach `Relay.dmg`
- [ ] Add release notes and known issues

Never commit production credentials, signing certificates, private keys, API secrets, or cloud credentials to this repository.
