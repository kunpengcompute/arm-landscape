---
layout: project
permalink: /:title/
category: bigdata

meta:
  keywords: "Apache, Hadoop"

project:
  title: "Apache Hadoop"
  type: "Java"
  ci_url: "https://ci-hadoop.apache.org/view/Hadoop/job/hadoop-qbt-linux-ARM-trunk/"
  url: "ApacheHadoop"
  logo: "/assets/images/bigdata/hadoop/logo.png"
  overview-logo: "/assets/images/bigdata/hadoop/logo-large.png"
  overview: "The Apache™ Hadoop® project develops open-source software for reliable, scalable, distributed computing. The Apache Hadoop software library is a framework that allows for the distributed processing of large data sets across clusters of computers using simple programming models. It is designed to scale up from single servers to thousands of machines, each offering local computation and storage. Rather than rely on hardware to deliver high-availability, the library itself is designed to detect and handle failures at the application layer, so delivering a highly-available service on top of a cluster of computers, each of which may be prone to failures."

supported_releases:
  - release:
    version: "3.3.0"
    url: "https://www.apache.org/dyn/closer.cgi/hadoop/common/hadoop-3.3.0/hadoop-3.3.0-aarch64.tar.gz"
  - release:
    version: "3.3.1"
    url: "https://www.apache.org/dyn/closer.cgi/hadoop/common/hadoop-3.3.1/hadoop-3.3.1-aarch64.tar.gz"

work_items:
  - work:
    title: "[HADOOP-16614] Missing leveldbjni package of aarch64 platform"
    url: "https://issues.apache.org/jira/browse/HADOOP-16614"
    status: "DONE"
  - work:
    title: "[YARN-10042] Upgrade grpc-xxx depdencies to 1.26.0"
    url: "https://issues.apache.org/jira/browse/YARN-10042"
    status: "DONE"
  - work:
    title: "[YARN-9898] Dependency netty-all-4.1.27.Final doesn't support ARM platform"
    url: "https://issues.apache.org/jira/browse/YARN-9898"
    status: "DONE"

events:
    - event:
      title: "Linaro Connect 21: Boosting Application Performance on Arm Data Centers"
      type: "Online Session"
      url: "https://connect.linaro.org/resources/lvc20/lvc20-303"
      language: "English"
    - event:
      title: "Linaro Connect 20: State of Big Data and Data Science on Arm"
      type: "Online Session"
      url: "https://connect.linaro.org/resources/lvc20/lvc20-303"
      language: "English"


---
<p>Apache Hadoop</p>
