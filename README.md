# maven-repo
maven-repo

# 本地安装

mvn deploy -DaltDeploymentRepository=doctorwho-maven-repo::default::file:/Users/xx/git/maven-repo/repositories/releases

mvn deploy -DaltDeploymentRepository=doctorwho-maven-repo::default::file:/Users/xx/git/maven-repo/repositories/releases


# pom使用

    <repositories>
        <repository>
            <id>doctorwho-maven-repo</id>
            <url>https://raw.githubusercontent.com/sdcuike/maven-repo/master/repository/releases</url>
        </repository>
        <repository>
            <id>doctorwho-maven-repo</id>
            <url>https://raw.githubusercontent.com/sdcuike/maven-repo/master/repository/snapshots</url>
        </repository>
    </repositories>
 