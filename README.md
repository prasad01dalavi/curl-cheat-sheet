# Curl Cheat Sheet

### Curl Basic Commands

```
curl -h                                               # list of arguments/flags
curl <GET request api endpoint>                       # Shows the response of GET request 
curl -i <GET request api endpoint>                    # includes headers information in GET response
curl -o filename.ext <GET request api endpoint> -i    # write the output(along with header) into the file instead of stdour
curl -O <download path>                               # download file using curl with remote file name

# POST json data (-X is the request type)
curl -H "Content-Type: application/json" -X POST -d '{"curl": "rocks"}' <API endpoint>
```
