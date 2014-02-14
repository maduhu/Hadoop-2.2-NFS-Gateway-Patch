This version is applying the patch manually that is found in this ticket https://issues.apache.org/jira/browse/HDFS-5804 to HDP 2 version 2.2.0.2.0.6.0-101.  Does not include the tests that were updated in the patch.

This patch is a fix for using the NFS HDFS gateway on a kerberized cluster.  Instructions for starting the service were followed from http://docs.hortonworks.com/HDPDocuments/HDP2/HDP-2.0.9.0/bk_user-guide/content/user-guide-hdfs-nfs.html.  An additional configuration was done to add a proxy group to the user starting the nfs service, in our case the HDFS user.
