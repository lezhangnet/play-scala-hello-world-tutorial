MOVED TO https://github.com/playframework/play-samples

NOTE from lezhangnet 20200101

The original base repo (https://github.com/playframework/play-scala-hello-world-tutorial) is archived and moved into "play-samples" (https://github.com/playframework/play-samples/tree/2.8.x/play-scala-hello-world-tutorial), which is a collection of a LOT of projects. So I decided to maintain this repo myself just to keep a short and concise hello world project repo. Let me know if you found any issues.

With minimum changes for Play 2.8.0 (which seems to be working ok), here are potential conflict info:
[warn] There may be incompatibilities among your library dependencies; run 'evicted' to see detailed eviction warnings.
[warn] Found version conflict(s) in library dependencies; some are suspected to be binary incompatible:
[warn] 	* com.google.guava:guava:28.1-jre is selected over 25.1-android
[warn] 	    +- com.typesafe.play:play_2.12:2.8.0 ()               (depends on 28.1-jre)
[warn] 	    +- com.google.inject:guice:4.2.2                      (depends on 25.1-android)
[warn] 	* org.scala-lang.modules:scala-java8-compat_2.12:0.9.0 is selected over 0.8.0
[warn] 	    +- com.typesafe.play:play-streams_2.12:2.8.0 ()       (depends on 0.8.0)
[warn] 	    +- com.typesafe.play:play_2.12:2.8.0 ()               (depends on 0.8.0)
[warn] 	    +- com.typesafe.akka:akka-actor_2.12:2.6.1 ()         (depends on 0.8.0)
[info] Here are other dependency conflicts that were resolved:
[info] 	* com.fasterxml.jackson.core:jackson-databind:2.10.1 is selected over 2.9.6
[info] 	    +- com.fasterxml.jackson.datatype:jackson-datatype-jdk8:2.10.1 (depends on 2.10.1)
[info] 	    +- com.fasterxml.jackson.module:jackson-module-paranamer:2.10.1 (depends on 2.10.1)
[info] 	    +- com.fasterxml.jackson.module:jackson-module-scala_2.12:2.10.1 (depends on 2.10.1)
[info] 	    +- com.typesafe.play:play-json_2.12:2.8.1             (depends on 2.10.1)
[info] 	    +- com.fasterxml.jackson.datatype:jackson-datatype-jsr310:2.10.1 (depends on 2.10.1)
[info] 	    +- com.typesafe.akka:akka-serialization-jackson_2.12:2.6.1 () (depends on 2.10.1)
[info] 	    +- com.typesafe.play:play_2.12:2.8.0 ()               (depends on 2.10.1)
[info] 	    +- com.fasterxml.jackson.module:jackson-module-parameter-names:2.10.1 (depends on 2.10.1)
[info] 	    +- io.jsonwebtoken:jjwt:0.9.1                         (depends on 2.9.6)
[info] 	* org.slf4j:slf4j-api:1.7.29 is selected over 1.7.25
[info] 	    +- org.slf4j:jcl-over-slf4j:1.7.29                    (depends on 1.7.29)
[info] 	    +- com.typesafe.akka:akka-slf4j_2.12:2.6.1 ()         (depends on 1.7.29)
[info] 	    +- com.typesafe.play:play_2.12:2.8.0 ()               (depends on 1.7.29)
[info] 	    +- com.typesafe.akka:akka-actor-typed_2.12:2.6.1 ()   (depends on 1.7.29)
[info] 	    +- org.slf4j:jul-to-slf4j:1.7.29                      (depends on 1.7.29)
[info] 	    +- ch.qos.logback:logback-classic:1.2.3               (depends on 1.7.25)
