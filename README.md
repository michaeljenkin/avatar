# avatar_face_detection
This encapsulates the avatar lower level face detection and recognition process

Nodes:
  rebuild_database is a node that can be used to rebuild the database. It looks for a directory 'faces'. This 
  directory should have a set of directories, each of which consists of a collection of images of the same person. There is 
  also a info.json, which is a json file with a colleciton of keys that match the directory name. When a face is recognized
  this data will also be sent along to the user.
  
  face_finder.py finds the faces based on the current operational database
