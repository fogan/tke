# TKEStack 产品手册

* [产品部署指南](installation)
  * [部署架构](installation/installation-architecture.md)
  * [部署环境要求](installation/installation-requirement.md)
  * [安装步骤](installation/installation-procedures.md)
* [产品快速入门](QuickStart)
  * [快速入门](QuickStart/快速入门.md)
  * [入门示例](QuickStart/examples)
    * [创建简单的 Nginx 服务](QuickStart/examples/%E5%88%9B%E5%BB%BA%E7%AE%80%E5%8D%95nginx%E6%9C%8D%E5%8A%A1.md)
    * [编写 Hello World 程序](QuickStart/examples/%E7%BC%96%E5%86%99%20Hello%20World%E7%A8%8B%E5%BA%8F.md)
    * [如何构建 Docker 镜像](QuickStart/examples/%E5%A6%82%E4%BD%95%E6%9E%84%E5%BB%BAdocker%E9%95%9C%E5%83%8F.md)
* [产品使用指南](products)
  * [平台侧](products/platform)
    * [集群管理](products/platform/cluster.md)
    * [业务管理](products/platform/business.md)
    * [切换控制台](products/platform/controlpannel.md)
    * [拓展组件管理](products/platform/extender.md)
    * [组织资源](products/platform/resource.md)
    * [访问管理](products/platform/access.md)
    * [监控与告警](products/platform/monitor%26alert.md)
    * [运维中心](products/platform/operation.md)
  * [业务侧](products/business-control-pannel)
    * [Kubernetes 对象管理](products/business-control-pannel/application)
      * [Namepsaces](products/business-control-pannel/application/namespace.md)
      * [工作负载](products/business-control-pannel/application/workload)
        * [Deployment 管理](products/business-control-pannel/application/workload/deployment.md)
        * [StatefulSet 管理](products/business-control-pannel/application/workload/stateful-set.md)
        * [DaemonSet 管理](products/business-control-pannel/application/workload/daemon-set.md)
        * [Job 管理](products/business-control-pannel/application/workload/job.md)
        * [CronJob 管理](products/business-control-pannel/application/workload/cron-job.md)
        * [设置工作负载的资源限制](products/business-control-pannel/application/workload/resource-limit.md)
      * [服务](products/business-control-pannel/application/services)
        * [Service 管理](products/business-control-pannel/application/services/service.md)
        * [Ingress 管理](products/business-control-pannel/application/services/ingress.md)
      * [配置](products/business-control-pannel/application/configurations)
        * [ConfigMap 管理](products/business-control-pannel/application/configurations/ConfigMap.md)
        * [Secret 管理](products/business-control-pannel/application/configurations/secret.md)
      * [存储](products/business-control-pannel/application/storage)
        * [PV 和 PVC 管理](products/business-control-pannel/application/storage/persistent-volume-claim.md)
        * [StorageClass 管理](products/business-control-pannel/application/storage/storave-class.md)
      * [事件管理](products/business-control-pannel/application/events.md)
      * [日志管理](products/business-control-pannel/application/log.md)
    * [Helm 应用](products/business-control-pannel/helm/helm.md)
    * [监控与告警](products/business-control-pannel/monitor-alert)
      * [设置告警](products/business-control-pannel/monitor-alert/alert.md)
      * [通知管理](products/business-control-pannel/monitor-alert/notifition.md)
    * [访问凭证](products/business-control-pannel/resource/credentials.md)
* [产品特色功能](features)
  * [Galaxy](features/galaxy.md)
  * [TAPP](features/tapp.md)
  * [GPUManager](features/gpumanager.md)
  * [CronHPA](features/cron-hpa.md)
  * [LBCF](features/lbcf.md)
* [FAQ](FAQ)
  * [部署类](features/galaxy.md)
    * [如何规划部署资源](FAQ/installation.md#如何规划部署资源)
    * [如何使用存储](FAQ/installation.md#如何使用存储)
    * [常见报错解决方案](FAQ/installation.md#常见报错解决方案)
    * [如何重新部署集群](FAQ/installation.md#如何重新部署集群)
  * [功能类](FAQ/features.md)
    * [如何接入 LDAP、OIDC](FAQ/features.md#如何接入LDAP、OIDC)
    * [如何实现自定义监控](FAQ/features.md#如何实现自定义监控)
    * [如何做日志分析](FAQ/features.md#如何做日志分析)
  * [权限类](FAQ/access.md)
    * [业务管理、平台管理的区别](FAQ/access.md#业务管理、平台管理的区别)
    * [如何设置自定义策略](FAQ/access.md#如何设置自定义策略)
  * [事件类](FAQ/events.md)