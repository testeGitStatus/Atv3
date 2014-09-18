Atv3
====

Teste
Using worker: worker-linux-9-1.bb.travis-ci.org:travis-linux-2
git.1
0.48s$ git clone --depth=50 --branch=master git://github.com/Prof-Calebe/Source-Code-Inspection.git Prof-Calebe/Source-Code-Inspection
Cloning into 'Prof-Calebe/Source-Code-Inspection'...
remote: Counting objects: 84, done.
remote: Compressing objects: 100% (54/54), done.
remote: Total 84 (delta 24), reused 64 (delta 16)
Receiving objects: 100% (84/84), 33.32 KiB | 0 bytes/s, done.
Resolving deltas: 100% (24/24), done.
Checking connectivity... done.
$ cd Prof-Calebe/Source-Code-Inspection
git.4
$ git checkout -qf 80891ecd1c57948cb1f4db9ed1f1b16772af98b2
couchdb stop/waiting
$ java -version
java version "1.7.0_60"
Java(TM) SE Runtime Environment (build 1.7.0_60-b19)
Java HotSpot(TM) 64-Bit Server VM (build 24.60-b09, mixed mode)
$ javac -version
javac 1.7.0_60
before_script
0.01s$ chmod +x ./build.sh
6.13s$ ./build.sh
CLASSPATH::/home/travis/build/Prof-Calebe/Source-Code-Inspection/lib/org-netbeans-modules-java-j2seproject-copylibstask.jar:
 
Compiling these projects:
 
----- Source Code Inspection -----
Buildfile: /home/travis/build/Prof-Calebe/Source-Code-Inspection/Source Code Inspection/build.xml
-pre-init:
-init-private:
-init-user:
-init-project:
-init-macrodef-property:
-do-init:
-post-init:
-init-check:
-init-ap-cmdline-properties:
-init-macrodef-javac-with-processors:
-init-macrodef-javac-without-processors:
-init-macrodef-javac:
-init-macrodef-test-impl:
-init-macrodef-junit-init:
-init-macrodef-junit-single:
-init-macrodef-junit-batch:
-init-macrodef-junit:
-init-macrodef-junit-impl:
-init-macrodef-testng:
-init-macrodef-testng-impl:
-init-macrodef-test:
-init-macrodef-junit-debug:
-init-macrodef-junit-debug-batch:
-init-macrodef-junit-debug-impl:
-init-macrodef-test-debug-junit:
-init-macrodef-testng-debug:
-init-macrodef-testng-debug-impl:
-init-macrodef-test-debug-testng:
-init-macrodef-test-debug:
-init-debug-args:
-init-macrodef-nbjpda:
-init-macrodef-debug:
-init-macrodef-java:
-init-presetdef-jar:
-init-ap-cmdline-supported:
-init-ap-cmdline:
init:
-deps-jar-init:
deps-jar:
    [mkdir] Created dir: /home/travis/build/Prof-Calebe/Source-Code-Inspection/Source Code Inspection/build
-warn-already-built-jar:
[propertyfile] Updating property file: /home/travis/build/Prof-Calebe/Source-Code-Inspection/Source Code Inspection/build/built-jar.properties
-check-automatic-build:
-clean-after-automatic-build:
-verify-automatic-build:
-pre-pre-compile:
    [mkdir] Created dir: /home/travis/build/Prof-Calebe/Source-Code-Inspection/Source Code Inspection/build/classes
-pre-compile:
-copy-persistence-xml:
-compile-depend:
-do-compile:
    [mkdir] Created dir: /home/travis/build/Prof-Calebe/Source-Code-Inspection/Source Code Inspection/build/empty
    [mkdir] Created dir: /home/travis/build/Prof-Calebe/Source-Code-Inspection/Source Code Inspection/build/generated-sources/ap-source-output
    [javac] Compiling 5 source files to /home/travis/build/Prof-Calebe/Source-Code-Inspection/Source Code Inspection/build/classes
-post-compile:
compile:
-pre-pre-compile-test:
-pre-compile-test:
-compile-test-depend:
-do-compile-test:
-post-compile-test:
compile-test:
-pre-test-run:
-do-test-run:
test-report:
-post-test-run:
-test-browse:
test:
-pre-jar:
-pre-pre-jar:
    [mkdir] Created dir: /home/travis/build/Prof-Calebe/Source-Code-Inspection/Source Code Inspection/dist
-do-jar-with-manifest:
-do-jar-without-manifest:
-do-jar-with-mainclass:
-do-jar-with-libraries-create-manifest:
-do-jar-with-libraries-copy-manifest:
     [copy] Copying 1 file to /home/travis/build/Prof-Calebe/Source-Code-Inspection/Source Code Inspection/build
-do-jar-with-libraries-set-main:
-do-jar-with-libraries-set-splashscreen:
-init-macrodef-copylibs:
-do-jar-with-libraries-pack:
 [copylibs] Nothing to copy.
 [copylibs] Building jar: /home/travis/build/Prof-Calebe/Source-Code-Inspection/Source Code Inspection/dist/Source_Code_Inspection.jar
     [echo] To run this application from the command line without Ant, try:
     [echo] java -jar "/home/travis/build/Prof-Calebe/Source-Code-Inspection/Source Code Inspection/dist/Source_Code_Inspection.jar"
-do-jar-with-libraries-delete-manifest:
-do-jar-with-libraries:
-post-jar:
jar:
-javadoc-build:
    [mkdir] Created dir: /home/travis/build/Prof-Calebe/Source-Code-Inspection/Source Code Inspection/dist/javadoc
  [javadoc] Warning: Leaving out empty argument '-windowtitle'
  [javadoc] Generating Javadoc
  [javadoc] Javadoc execution
  [javadoc] Loading source file /home/travis/build/Prof-Calebe/Source-Code-Inspection/Source Code Inspection/src/br/calebe/ticketmachine/core/PapelMoeda.java...
  [javadoc] Loading source file /home/travis/build/Prof-Calebe/Source-Code-Inspection/Source Code Inspection/src/br/calebe/ticketmachine/core/TicketMachine.java...
  [javadoc] Loading source file /home/travis/build/Prof-Calebe/Source-Code-Inspection/Source Code Inspection/src/br/calebe/ticketmachine/core/Troco.java...
  [javadoc] Loading source file /home/travis/build/Prof-Calebe/Source-Code-Inspection/Source Code Inspection/src/br/calebe/ticketmachine/exception/PapelMoedaInvalidaException.java...
  [javadoc] Loading source file /home/travis/build/Prof-Calebe/Source-Code-Inspection/Source Code Inspection/src/br/calebe/ticketmachine/exception/SaldoInsuficienteException.java...
  [javadoc] Constructing Javadoc information...
  [javadoc] Standard Doclet version 1.7.0_60
  [javadoc] Building tree for all the packages and classes...
  [javadoc] Building index for all the packages and classes...
  [javadoc] Building index for all classes...
-javadoc-browse:
javadoc:
default:
BUILD SUCCESSFUL
Total time: 5 seconds
 
The command "./build.sh" exited with 0.
Done. Your build exited with 0.
