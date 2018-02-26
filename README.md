# maven-archetypes
Repository for Payara Maven archetypes

## payara-micro-maven-archetype

Generate Payara Micro application using maven archetype : 

    mvn -DarchetypeGroupId=fish.payara.maven.archetypes 
        -DarchetypeArtifactId=payara-micro-maven-archetype 
        -DarchetypeVersion=1.0 
        -DarchetypeRepository=http://repo.maven.apache.org/maven2 
        -DgroupId=fish.payara 
        -DartifactId=payara-sample 
        -Dversion=1.0-SNAPSHOT 
        -Dpackage=fish.payara.sample 
        -DjavaeeVersion=8.0 
        -DpayaraMicroVersion=5.181-SNAPSHOT
        -Darchetype.interactive=false
        --batch-mode archetype:generate
    
