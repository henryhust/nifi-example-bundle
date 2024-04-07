## 自定义nifi算子开发模板

- 在IntelliJ上，单击“Create project”，选中“Create from archetype”，单击“ ADD Archetype”，然后输入以下内容

  GroupId: org.apache.nifi
  ArtifactId: nifi-processor-bundle-archetype
  Version:2.0.0-M2

- 输入项目的GroupId、Artifactid、Version

- 项目生成后，即可在processor子模块中进行自定义算子

### 算子开发位置
org.example.processors.MyProcessor

### 算子注册位置
nifi-true-processors/src/main/resources/META-INF.services/org.apache.nifi.processor.Processor
> org.example.processors.MyProcessor