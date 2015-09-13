
Cloud Video Transcoding System
==============================


1. System Interface
-------------------

The system provides three kinds of interface for providing video transcoding service, including Restful API, Command Line Interface, and RPC. In general, the system interfaces can be divided into two categories: task submission and status query. The details of each kind of interfaces are given in the following sections.

###1.1 Restful API Interface

The parameters of HTTP POST method for submitting a new task. The video location is specified with URL. 

<html>
    <title>Markdown</title>
    
     'url': 'http://155.69.52.158/guanyu.mp4',
     'target_resolution': '100x100 200x200',
     'priority': 5

</html>
