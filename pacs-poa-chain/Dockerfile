from pacs/parity:1.3.1
add data /data
add keys /keys
WORKDIR /root/parity/target/release
ENTRYPOINT ["./parity","--chain","/data/pacs-parity.json","--keys-path","/keys","--tracing","on","--author","dc6886fd24a32aed03983ded7c8f51f5e86d7ab5","--rpcaddr","0.0.0.0","--jsonrpc-interface","all","--jsonrpc-hosts","all","--unlock","dc6886fd24a32aed03983ded7c8f51f5e86d7ab5","--password","/data/unlock","--no-discovery"]
