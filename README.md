# Identdocstore proto
Identification documents storage service thrift protocol.


# Требования к оформлению Thrift IDL файлов

- __Namespace:__ 

	В каждом файле нужно __обязательно__ указывать `namespace` для __JAVA__:
		
		namespace java dev.vality.identdocstore.<name>
			
	Где `<name>` - имя, уникальное для Thrift IDL файлa в Damsel.
	
	
# Java development

Чтобы ипользовать несколько версий дамзели в проекте используте classifier:v${commit.number}

```
<dependency>
    <groupId>dev.vality</groupId>
    <artifactId>identdocstore-proto</artifactId>
    <version>1.5-27d975f</version>
    <classifier>v1</classifier>
</dependency>
```
