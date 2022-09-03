# S3D Tutorial Project

This is a tutorial project from
[S3D](https://www.linkedin.com/groups/14117472/) group.

The S3D group was created with the goal of at teaching software development to
inidvidals with Dyslexia, Dyscalcula, ADHD, and/or other differences in
thinking styles.

All work in this project is described as tasks. The tasks are intentionally
short and simple.  Participannts are encuraged to follow along by performing
the task but also engage in learning on their own.

The tasks build on each other such that if you complete the entire tutorial you
will have a basic understanding of software development.  This is challenging
work and as such I encurage you to take your time on each task. Please follow
the hyperlinks in this document and read about the technologies in detail.  You
can revist tasks and reach out to members of the S3D group for help related to
the tasks and discussions about the associated technologies.

## Task 1 - Create an AWS Account

To follow this tutorial, you need access to Amazon Web Services _(AWS)_.

Use the following link to establish an account on AWS.
- https://aws.amazon.com/free

This project uses only a tiny fraction of the power of AWS but exposure to the
platform will help you as you learn about software developmment. We encurage
you to explore features of AWS and eventually other similar services on your
own time.

## Task 2 - Clone this Git repository

Sign into the AWS Web Console and open a
[CloudShell](https://aws.amazon.com/cloudshell/) session.  The CloudShell
provides us with a [Bash](https://en.wikipedia.org/wiki/Bash_(Unix_shell))
environment we can type in commands to interact with our AWS environment.

Enter the following commands exactly as the are show shown to clone this
repository.

```bash
git clone https://github.com/farnsworth2008/s3d.git
```

Look over the command you entered. This might be the first time you have
entered a command on a Bash terminal but even if you have worked with Bash in
the past take the time to reflect on what we have just done. Read slowly and
carfully through the line and consider what each part does.

The top level command we are executing is `git`.  We are sending `clone` and
the URL of a project as parameters.  The git command performs the work of
obtaining the project and creating a directory called s3d in your cloudshell.

In this task, you have started to learn Bash shell.  The Bash shell is a very
powerful way to interact with a computer.  As someone with dyslexia, the author
of this tutorial has strangely found that he enjoys and does well with command
line tools and computer languages. The syntax of computers can at times be very
painful and exacting but computing environments allow us to work through the
syntax and grow our understanding of the rules of languges.  There are many
languages in computers and each of them have different rules but there are also
common themes.  We won't do a great deal of Bash in this course but the task
was needed to establish our enviornment. A Bash command line environment may
seem primitive but it remains an important skill for working with computers.
Outside this course you are encuraged to use all sorts of tutorials which may
involve point-n-click graphical environments but I strongly encurage you to
commit yourself to learning Bash, Go, AWS, and other technologies from a
console and language based perspective rather then from a menu click and drag
and drop approach.  I want you to become someone who creates powerful software
and as such learning the basics is critical.

Take some time to read about Bash and GIT with the following links.

- [Bash](https://www.gnu.org/software/bash/manual/bash.html#Introduction)
- [Git](https://git-scm.com/book/en/v2)

