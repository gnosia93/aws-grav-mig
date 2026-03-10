For information about the supported Java versions for applications, see the application pages in the Amazon EMR Release Guide.

Amazon EMR only supports running one runtime version in a cluster, and doesn't support running different nodes or applications on different runtime versions on the same cluster.

* For Amazon EMR 7.x, the default Java Virtual Machine (JVM) is Java 17 for applications that support Java 17, with the exception of Apache Livy. For more information about the supported JDK versions for applications, see the corresponding release page in the Amazon EMR Release Guide.
Starting with Amazon EMR 7.1.0, Flink supports and is set to Java 17 by default. To use a different version Java runtime, override the settings in flink-conf. For more information about configuring Flink to use Java 8 or Java 11, see Configure Flink to run with Java 11.
* For Amazon EMR 5.x and 6.x, the default Java Virtual Machine (JVM) is Java 8.
* For Amazon EMR releases 6.12.0 and higher, some applications also support Java 11 and 17.
* For Amazon EMR releases 6.9.0 and higher, Trino supports Java 17 as default. For more information about Java 17 with Trino, see Trino updates to Java 17 on the Trino blog.
