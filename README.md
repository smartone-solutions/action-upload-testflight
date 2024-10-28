# GitHub Action to upload to Apple's TestFlight service

## Usage:

```yaml
- name: Upload to Testflight
  uses: smartone-solutions/action-upload-testflight@v1.0.0
  with: 
    app-path: 'path/to/application.ipa' 
    issuer-id: ${{ secrets.APPSTORE_ISSUER_ID }}
    api-key-id: ${{ secrets.APPSTORE_API_KEY_ID }}
    api-private-key: ${{ secrets.APPSTORE_API_PRIVATE_KEY }}
```

## Additional Arguments

See [action.yml](action.yml) for more details.
