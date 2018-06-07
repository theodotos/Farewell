# Farewell Github

Github is a [walled garden](https://en.wikipedia.org/wiki/Closed_platform). It is florid and fragrant but a walled garden nevertheless. We have been lured by its charms and forgot all about what lies inside its walls.

Now a new Giant dwells insides the walls. And I don't want to be here anymore. I a not the only one that feels this way.

People have been looking for alternatives ever since the announcement. I don't want to go to Gitlab.org, Bitbucket or the ill-fated Sourceforge. I prefer setting up my own code hosting platform. There are some self-hosted alternatives:

* [Gitlab CE](https://gitlab.com/gitlab-org/gitlab-ce)
* [Gogs](https://gogs.io/)
* [Gitea](https://gitea.io)

I have migrated all my repos to my self-hosted Gitea instance:

https://git.theo-andreou.org

I have prepared an Ansible Playbook to make it easy for all those that wish to leave and host their own Gitea instance:

https://git.theo-andreou.org/Personal/ansible-deploy-gitea

The problem with the self-hosted solutions though is that it makes collaboration harder. People will have to create accounts on every platform they want to contribute to or ask for help. Using OpenID will make this a bit easier but still not convenient enough. So some people have started an effort to build a protocol that would provide cross-instance collaboration between the self-hosted and also the commercial solutions. They named it **gitpub** and if you interested in participating you can find the details here:

https://github.com/git-federation/gitpub

Farewell!
