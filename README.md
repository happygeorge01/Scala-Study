Scala-Study
===========
Details in Scala study

Install Scala and using REPL(Centos)
============================
1. download Scala from www.scala-lang.org/download
2. tar -zxvf scala-$version.tar; ln -s scala-$version scala // make soft link for following settings
3. Set system environment
  a. vim /etc/profile
  b. Insert following settings
    export SCALA_HOME=/usr/local/share/scala
    PATH=$PATH:$SCALA_HOME
  c. source /etc/profile
4. execute command scala in CLI
  
