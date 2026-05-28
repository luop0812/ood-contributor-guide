# Open OnDemand Contributor Guide
## Set up your development environment
We introduce two simple ways to set up your OOD development environment: set up a sandbox and set up an OOD Docker container.  
### Set up a sandbox for app development
If you have an Open OnDemand instance running, the easiest way to set up your development environment is to open a sandbox. 

**Note:** Before you can use the OOD sandbox development environment, it must be enabled by the OOD administrator. This mode allows you to create and test custom web applications directly from your home directory in an isolated space. Contact your OOD adminstrator if your don't see 'My Sandbox Apps (Development)' in step 3. 

1. Enable Development Mode: If you don't see the "Develop" menu in your dashboard, you typically need to create a specific directory in your terminal to signal the system:

```{bash}
mkdir -p ~/ondemand/dev
```

2. Open the Dashboard: Log in to your institution's Open OnDemand portal.

3. Navigate to Sandbox: In the top navigation bar, click the Develop menu and select My Sandbox Apps (Development).

<img src="image.png" width="50%">

4. Launch Your App: From this page, you can see a list of applications currently in your ~/ondemand/dev folder. Click Launch next to an app to start its session in a new tab.

### Set up an OOD Docker container for app development
