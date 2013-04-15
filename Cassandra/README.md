Project work at University of Southern California.

Collaborators: 
Pallav Rustogi   - rustogi@usc.edu
David Righettini - drighett@usc.edu

Guide:
Shahram Ghandeharizadeh  - shahram@pollux.usc.edu

Aim: To benchmark Cassandra using BGBenchmark tool ( http://www.bgbenchmark.org/ )

Getting Started with BG:
1) Download BG from http://www.bgbenchmark.org/BG/downloads.html
2) Unzip the files
3) Run Ant
4) Import Project in Eclipse
5) Fix build path issues if any (Delete the jar with wrong paths and add the correct jar files)
6) Create following folder structure:
        BG\db
            |Cassandra
                |lib
                |src
7) Download libthrift.jar from http://www.java2s.com/Code/Jar/l/Downloadlibthriftjar.htm
8) Place this jar in BG\db\Cassandra\lib
9) Mark BG\db\Cassandra\src as the source folder
10)Download CassandraDbClient.java dnd CassandraDBClientConstants.java from Git and add to Cassandra\src folder

