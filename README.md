# packetbeat-release
A BOSH release for [packetbeat](https://www.elastic.co/products/beats/packetbeat)

Deploy it as an addon to all releases installed with BOSH, by uploading a [runtime-config](/manifests/openstack/runtime-config.yml), forward the data to elasticsearch and get some insight using kibana. You can import [kibana-sample-dashboards](/manifests/openstack/kibana-sample-dashboard.json) as a starting point.
