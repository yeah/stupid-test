Planio
======

Planio &hearts; GitHub! This service hook notifies Planio to fetch new commits from your repository at GitHub whenever you push to it.

Install Notes
-------------

1. Create a free or paid Planio account at http://plan.io
2. Logged in to your Planio account, navigate to **Administration** -> **Settings** -> **Repositories** and make sure that the **Enable WS for repository management** checkbox is active and that you have an **API key** set up
3. Create a project, then navigate to **Settings** -> **Repositories**
4. Click on **New repository**
5. Select **Git**, choose an **Identifier**, enter the (preferably public, read-only, git://) URL of your GitHub repository in the **Mirror from external URL** field, then click **Create**
6. Back in your project, head over to the **Repository** tab, find and select the repository you just created in the sidebar
7. Should you not see the blue instructions screen, click on **Help** on the upper right
8. Fill in the information from the **Set up web hook** section in the above form here on GitHub and click **Update settings**
9. Optional: if this GitHub repository is private, click on **Deploy Keys** here on the right and add the SSH public key from the **Set up a public key (deploy key)** section in Planio
10. A short while after your next commit, the repository will show up on Planio. If you have nothing to commit, you can also come back here and hit the **Test Hook** button.


testing 