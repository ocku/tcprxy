TCPRXY
        A quick tcp port forwarding util.

USAGE
        -l {listen_addr}  -- the address to listen on.
        -f {forward_addr} -- the address to forward to.
EXAMPLES
        tcprxy -l :3000 -f app.local:8080
        tcprxy -l 10.0.1.10:3000 -f [::1]:80
        tcprxy -l localhost:3000 -f google.com:http

WHY
        It's fun to reinvent the wheel. Also, I get to write a nice 80 column 
        plaintext README for it.