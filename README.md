# Kaodim-test
this repository is built to solve an interview question from Kaodim

I Chose to scale up a sample ruby app using Code Pipeline through which we can hold entire CI/CD pipeline.

We need to connect the pipeline in various stages. Stage1 will be integration with Codecommit (we can integrate other popular version control tools as well)
then we need to connect to code build where the build happens (basically execution of cloudformation template).
Ideally we execute the changeset but for now I just executed the stack directly.
