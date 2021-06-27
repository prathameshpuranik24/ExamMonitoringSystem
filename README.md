# Exam Monitoring System

WITHackathon-21(Software Edition)

ORGANISED BY,
COMPUTER SCIENCE AND ENGINEERING DEPARTMENT
IN ASSOCIATION WITH COMPUTER SOCIETY OF INDIA.

Problem Statement:-

2. Exam Monitoring System.

Develop a Desktop application for an Online Examination Monitoring system (OEMS), which will be used to monitor an examination conducted in an online mode. OEMS will register running processes on the clients. Whenever an exam starts, the monitoring system logs the processes that will run on the computer with all popup messages. Log will also contain Login time, Logout time, idle time more than prescribed time etc. OEMS will stop automatically when the exam stops and generate reports including an examination score, individual student log and other analysis parameters concerned with an exam. The system shall send 3 alerts in case of malpractice and will automatically end the exam if such malpractice is continued. Log shall also capture all the pop-ups.Develop a system to discourage a student from cheating and check the content of the computer clipboard (copy/paste-function).


Docker file link:-
https://hub.docker.com/r/proctoredexam/exam/tags?page=1&ordering=last_updated

Command to pull our docker file:-
docker pull proctoredexam/exam:v2

Command to run our docker file:-
docker run -t -p 5000:5000 -v /etc/localtime:/etc/localtime e360d3415ea9
