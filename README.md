Archetype Java Kata
=========================

Contains basic libraries: junit, hamcrest and mockito.

To install this archetype into your local maven repository, In the root folder of this project, type:

    mvn install

To use it, create a new maven project in your IDE, selecting the archetypes option. If you just installed this archetype, you will need to add it to your IDE providing the following information:

    GroupId: scmallorca
    ArtifactId: kata-quickstart
    Version: 1.0-SNAPSHOT

If you want to create a project from cli with this archetype, you should write the following:

    mvn archetype:generate -DarchetypeGroupId=scmallorca -DarchetypeArtifactId=kata-quickstart -DarchetypeVersion=1.0-SNAPSHOT
