# XmlToJson
## 1
```
$xmlNode = simplexml_load_file('http://example.com/example.xml');
$arrayData = xmlToArray($xmlNode);
echo json_encode($arrayData);
```
## 2
```
$data =file_get_contents('http://example.com/example.xml');
$arrayData = parse_xml($data);
echo json_encode($arrayData);
```
