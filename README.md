# Kali-Linux-Issues-and-Errors

## Error 1
### E: Failed to fetch http://http.kali.org/kali/dists/kali-rolling/main/Contents-amd64  File has unexpected size (41449010 != 41441266). Mirror sync in progress? [IP: XXX.XX.XXX.XXX 80]
### E: Some index files failed to download. They have been ignored, or old ones used instead.

#### Solution:
`proxychains sudo apt-get update`
