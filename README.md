## Start openvpn client with .ovpn

Run openvpn client

	docker run --restart=always -d --net=host --privileged -v $(pwd)/my.ovpn:/my.ovpn wernerb/openvpn-client --config my.ovpn
