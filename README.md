# InterconnectionDemo

2018/12/6, upload all files for demo:

1. WS.xml

用于演示互联互通的文档和服务实现

2. WSCodeGlobalExport.gof

所有用于互联互通的术语表，需要导入到Global

3. HL7V3MessageSchemas.zip

用于互联互通的Hl7 V3 template, 需要测试某个服务，需要把相关的请求，回复消息的V3 template导入Ensemble, 否则无法使用相应的virtual Document

4. WS_XSLT_Files.zip

用于互联互通文档和服务的xslt文件，需要解压到install-dir\CSP\xslt\目录

5. WS-Service-SoapIn-soapui-project.xml

用于SoupUI测试互联互通服务

6. CDR.xml

Ensemble存储数据的数据模型示例。因为删除了包里面的很多类，因此编译时会有很多问题，使用者可以修改后使用其中最基本的类存储数据，CDR.Patient。 此类包只做示意。

7. HIP.xml

在某医院做demo从外部系统向CDR同步数据的production. 只做示意。它展示的是集成平台设计的理念，并不必须用于互联互通测试。
