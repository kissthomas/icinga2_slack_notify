# icinga2_slack_notify

Icinga2 notifier plugin for Slack, compatible with icinga2 director.
Based on https://github.com/nisabek/icinga2-slack-notifications

Just drop it to your icinga2 configuration and include it.
(You may need to do a kickstart if you use director)

You only need to add host.vars.slack_notifications and 
service.vars.slack_notifications to your templates, and 
then set it to true where needed.

To start using it you only need to change vars.slack_notifications_webhook_url 
and vars.slack_notifications_icinga2_base_url in 
slack-notifications-user-configuration.conf
