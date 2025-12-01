
## Summary (Summarize the bug encountered concisely)
A spelling error found on a blank project creation link.


## Steps to reproduce     
- Navigate to https://gitlab.com/dashboard/projects.
- Click on the New project button.


## What is the current bug behavior?
The first option reads as "Create black project".
     

## What is the expected correct behavior?
Should read as "Create blank project".

     
## Relevant logs and/or screenshots
```<h3 class="gl-text-color-heading gl-text-size-h2">Create black project</h3>```

See also attached Create_black_project.png.
      

## Possible fixes
Change
```<h3 class="gl-text-color-heading gl-text-size-h2">Create black project</h3>```
to
```<h3 class="gl-text-color-heading gl-text-size-h2">Create blank project</h3>```


## Whom do you report/ Assign To/ Tags
/label ~bug ~reproduced ~front-end
/cc @product-owner @test-lead
/assign @front-end-developer


## Priority
Minor