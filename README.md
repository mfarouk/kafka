# kafka
kafka experimentation

mvn -X archetype:generate -DarchetypeGroupId=com.digitalreasoning.datajetway -DarchetypeArtifactId=datajetway-archetype -DarchetypeVersion=1.4.0-SNAPSHOT -DgroupId=com.digitalreasoning.gs.djingest -DartifactId=gs-dj-ingest -B

mvn -X archetype:generate \
-DarchetypeCatalog=https://farouk.althlathini:pass@nexus.corp.digitalreasoning.com/nexus/content/repositories/snapshots \
-DarchetypeGroupId=com.digitalreasoning.datajetway \
-DarchetypeArtifactId=datajetway-archetype \
-DarchetypeVersion=1.4.0-SNAPSHOT \
-DgroupId=com.digitalreasoning.gs.djingest \
-DartifactId=gs-dj-ingest \
-Dversion=1.0.0-SNAPSHOT \

mvn -X archetype:generate \
-DarchetypeCatalog=https://farouk.althlathini:password@nexus.corp.digitalreasoning.com/nexus/content/repositories/snapshots/ \
-DarchetypeGroupId=com.digitalreasoning.datajetway \
-DarchetypeArtifactId=datajetway-archetype \
-DarchetypeVersion=1.4.0-SNAPSHOT \
-DgroupId=com.digitalreasoning.datajetway \
-DartifactId=seantest2 \
-Dversion=1.0.0-SNAPSHOT \
-B

mvn archetype:generate -DgroupId=com.tgt.rfid.consumer.rfidqa -DartifactId=rfid-consumer-test -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false

mvn archetype:generate -DgroupId=com.wheels.up.flight.reservation -DartifactId=flightReservation -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false

mvn archetype:generate -DgroupId=com.tgt.eni.ui.eniuiqa -DartifactId=eni-ui-selenium -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false

mvn archetype:generate -DgroupId=com.tgt.selenium.htmlUnit -DartifactId=htmlUnit -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false

mvn archetype:generate -DgroupId=com.tgt.project -DartifactId=myproject-selenium -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false

mvn archetype:generate -DgroupId=com.digitalreasoning.nlptest -DartifactId=nlptest -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false


mvn archetype:generate -DgroupId=com.baml.devopseng.events -DartifactId=events -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false

mvn -X archetype:generate -DarchetypeGroupId=com.digitalreasoning.datajetway -DarchetypeArtifactId=datajetway-archetype -DarchetypeVersion=1.4.0-SNAPSHOT -DgroupId=com.digitalreasoning.watercooler.demo -DartifactId=watercooler-dj-demo -Dversion=0.1 -B

mvn -X archetype:generate -DarchetypeGroupId=com.digitalreasoning.datajetway -DarchetypeArtifactId=datajetway-archetype -DarchetypeVersion=1.4.0-SNAPSHOT -DgroupId=com.digitalreasoning.watercooler.demo -DartifactId=watercooler-dj-demo -Dversion=0.1 -B


mvn archetype:generate -DgroupId=com.digitalreasoning.gs.djwingest -DartifactId=gs-djw-ingest -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false

mvn archetype:generate -DarchetypeGroupId=org.codehaus.gmaven.archetypes -DarchetypeArtifactId=gmaven-archetype-basic -DgroupId=com.digitalreasoning.gs.djwingest -DartifactId=gs-djw-ingest -DinteractiveMode=false

mvn archetype:generate -DgroupId=com.digitalreasoning.gs.djwingest -DartifactId=gs-djw-ingest -DarchetypeGroupId=com.digitalreasoning.groovy -DarchetypeArtifactId=graven-archetype -DarchetypeVersion -DinteractiveMode=false

mvn archetype:generate \  -DarchetypeGroupId=com.digitalreasoning.groovy \  -DarchetypeArtifactId=graven-archetype \  -DarchetypeVersion=1.0-SNAPSHOT \  -DgroupId=com.digitalreasoning.gs.djwingest \  -DartifactId=gs-djw-ingest



