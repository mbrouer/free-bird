## [2.6.6](https://github.com/ds-onyx-shark/terraform-modules/compare/v2.6.5...v2.6.6) (2023-11-08)


### Bug Fixes

* **coreos-snippets:** add danskespil issuing ca trust ([9a476a3](https://github.com/ds-onyx-shark/terraform-modules/commit/9a476a3f1233c78a7d7f0331a1d93ab2f61d549c))

## [2.6.5](https://github.com/ds-onyx-shark/terraform-modules/compare/v2.6.4...v2.6.5) (2023-11-08)


### Bug Fixes

* **vault/credential-sources/datadog:** output data path fixed and tested ([bf8545f](https://github.com/ds-onyx-shark/terraform-modules/commit/bf8545ff2e0a71fb35e99b04a692721443294a12))

## [2.6.4](https://github.com/ds-onyx-shark/terraform-modules/compare/v2.6.3...v2.6.4) (2023-11-08)


### Bug Fixes

* **vault/credential-sources/datadog:** output data path fixed ([505f239](https://github.com/ds-onyx-shark/terraform-modules/commit/505f23936a4b752a0c72cea3392d2bbabd11be2a))

## [2.6.3](https://github.com/ds-onyx-shark/terraform-modules/compare/v2.6.2...v2.6.3) (2023-11-08)


### Chores

* **aws/eks/network:** bump vpc module to v5.1.2 ([1890265](https://github.com/ds-onyx-shark/terraform-modules/commit/1890265bdb22781cdf0bf330ec6451cec179ba7b))

## [2.6.2](https://github.com/ds-onyx-shark/terraform-modules/compare/v2.6.1...v2.6.2) (2023-11-08)


### Bug Fixes

* **aws/rds:** use HCP vault ([157332d](https://github.com/ds-onyx-shark/terraform-modules/commit/157332d1dff517c082a36871b2e7d30eda7d24b0))
* **vault/credentials-sources/datadog:** DD credentials from HCP vault ([77c9b40](https://github.com/ds-onyx-shark/terraform-modules/commit/77c9b401aa49fa931af342c9f7b094bbd48fb374))

## [2.6.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v2.6.0...v2.6.1) (2023-11-08)


### Chores

* **k8s/helm-modules/cilium:** add prometheus monitors ([291217e](https://github.com/ds-onyx-shark/terraform-modules/commit/291217ee1005ebc223409b07b942a96bebdd4579))
* **k8s/helm-modules/datadog:** enable prometheus scrape and network monitoring ([4be9932](https://github.com/ds-onyx-shark/terraform-modules/commit/4be9932423a00533a2beb699b32be4d9d47293d7))

## [2.6.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v2.5.3...v2.6.0) (2023-11-06)


### Features

* **k8s/helm-modules/argo-cd:** add ds-itu-frontend-service pat ([15f4060](https://github.com/ds-onyx-shark/terraform-modules/commit/15f4060fe982526a26b78a8a5fe974fdd98f1c61))

## [2.5.3](https://github.com/ds-onyx-shark/terraform-modules/compare/v2.5.2...v2.5.3) (2023-11-03)


### Bug Fixes

* **vault/credential-sources:** did not work correctly ([f425f68](https://github.com/ds-onyx-shark/terraform-modules/commit/f425f683a1e2552e366c91c8e422f0767dbf71e5))

## [2.5.2](https://github.com/ds-onyx-shark/terraform-modules/compare/v2.5.1...v2.5.2) (2023-11-03)


### Bug Fixes

* **vault/credential-sources:** use hcp vault ([f94b408](https://github.com/ds-onyx-shark/terraform-modules/commit/f94b40807f0af3f3cec0848b2835c0544d677630))

## [2.5.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v2.5.0...v2.5.1) (2023-11-02)


### Bug Fixes

* **vault/data/ip-list:** update to hcp vault ([1e6893c](https://github.com/ds-onyx-shark/terraform-modules/commit/1e6893c2401e0f901f97312d3b1567549bec8e51))

## [2.5.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v2.4.0...v2.5.0) (2023-10-31)


### Features

* **k8s/helm-modules/vault:** add adjustable injector replicas ([8d085a4](https://github.com/ds-onyx-shark/terraform-modules/commit/8d085a49b928b80cf4a433c39abb9a2003fe1908))

## [2.4.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v2.3.0...v2.4.0) (2023-10-31)


### Features

* **k8s/helm-modules/spring-config-server:** add module ([8de340a](https://github.com/ds-onyx-shark/terraform-modules/commit/8de340af0e0b7a1f95f7067dfcf816dceb7afcf3))

## [2.3.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v2.2.1...v2.3.0) (2023-10-23)


### Features

* **aws/eks/cluster:** add and modify supporting variables ([60edac1](https://github.com/ds-onyx-shark/terraform-modules/commit/60edac15050ae768530418661f28e8c5e4e7138f))
* **aws/eks/cluster:** bump all addons ([a39ad15](https://github.com/ds-onyx-shark/terraform-modules/commit/a39ad153e5d1c922b276e28c53063d195d3e3549))
* **aws/eks/cluster:** bump eks module to v19 ([0afd473](https://github.com/ds-onyx-shark/terraform-modules/commit/0afd47391a7131b39187be4263ef60853263ec1b))
* **aws/eks/cluster:** create vault namespace ([c7b89cf](https://github.com/ds-onyx-shark/terraform-modules/commit/c7b89cf4628436d0e71277d906a2fecba71515a1))


### Bug Fixes

* **aws/eks/cluster:** kubernetes and helm provider authentication ([e43ddd2](https://github.com/ds-onyx-shark/terraform-modules/commit/e43ddd247a514f9a2e047e5958641a37dc3af5c4))
* **aws/eks/cluster:** nlb security groups ([d99c1e9](https://github.com/ds-onyx-shark/terraform-modules/commit/d99c1e9ca7494ad72b1e0a69d17c9f9b1d080983))

## [2.2.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v2.2.0...v2.2.1) (2023-10-20)


### Chores

* **k8s/helm-modules/argo-cd:** Add custom ds logo ([95fccbe](https://github.com/ds-onyx-shark/terraform-modules/commit/95fccbe5a27f0715b29661b789d18676c29b80f3))

## [2.2.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v2.1.3...v2.2.0) (2023-10-20)


### Features

* **k8s/helm-modules/waf:** use new traefik crds ([d229c82](https://github.com/ds-onyx-shark/terraform-modules/commit/d229c82ed862990106b4721592884fa95f664e9b))

## [2.1.3](https://github.com/ds-onyx-shark/terraform-modules/compare/v2.1.2...v2.1.3) (2023-10-20)


### Chores

* **k8s/helm-modules/vault:** increase default and max token ttl to 1h ([4cde0f2](https://github.com/ds-onyx-shark/terraform-modules/commit/4cde0f245c4b1ce503230612e52731dd044a1c6a))

## [2.1.2](https://github.com/ds-onyx-shark/terraform-modules/compare/v2.1.1...v2.1.2) (2023-10-20)


### Chores

* **k8s/helm-modules/vault:** bump chart version ([0d24a2c](https://github.com/ds-onyx-shark/terraform-modules/commit/0d24a2c7707bfc4970d04755d932a42a3504cfc5))

## [2.1.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v2.1.0...v2.1.1) (2023-10-20)


### Bug Fixes

* **aws/route53:** reduce assume role ttl to 1 hour as per aws limits ([a554053](https://github.com/ds-onyx-shark/terraform-modules/commit/a554053ab1deb8428721acbcf9aa1fd68196d9db))

## [2.1.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v2.0.0...v2.1.0) (2023-10-19)


### Features

* **k8s/helm-modules/cert-manager:** bump chart to 1.13.1 ([1669183](https://github.com/ds-onyx-shark/terraform-modules/commit/1669183484d472ea6ec74bf8fc824cd63beacde5))
* **k8s/helm-modules/coredns:** bump chart to 1.27.1 ([3f6f4ea](https://github.com/ds-onyx-shark/terraform-modules/commit/3f6f4ea395e675ddc9921c794eed03bfae7f89be))
* **k8s/helm-modules/datadog-operator:** bump chart to 1.2.1 ([5d704a4](https://github.com/ds-onyx-shark/terraform-modules/commit/5d704a48f28d7ad843df19eb706ebf81217e92ab))
* **k8s/helm-modules/datadog:** bump chart to 3.40.2 ([9f84e23](https://github.com/ds-onyx-shark/terraform-modules/commit/9f84e23e3af9295c731ce6fdb38d50e44930dd3a))
* **k8s/helm-modules/external-dns:** bump chart to 1.13.1 ([3145100](https://github.com/ds-onyx-shark/terraform-modules/commit/314510005a45c0d4ddb0fc19b844735716a0d94c))

## [2.0.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.116.0...v2.0.0) (2023-10-19)


### ⚠ BREAKING CHANGES

* **k8s/helm-modules/traefik:** CRDs have changed names. Upgrade instructions can be found at https://github.com/traefik/traefik-helm-chart#upgrading-crds

### Features

* **k8s/helm-modules/argo-cd:** upgrade to new traefik crds ([27f2a36](https://github.com/ds-onyx-shark/terraform-modules/commit/27f2a36ae0d65467936aacf2bf86911edef2eb9e))
* **k8s/helm-modules/pinniped:** upgrade to new traefik crds ([5faf32d](https://github.com/ds-onyx-shark/terraform-modules/commit/5faf32d1972c153acdc412b5240c9b73d32e35a4))
* **k8s/helm-modules/traefik:** bump traefik to 24.0.0 ([d68b384](https://github.com/ds-onyx-shark/terraform-modules/commit/d68b3848b8bb0eb93b893df7a708a966b82ffe47))

## [1.116.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.115.0...v1.116.0) (2023-10-19)


### Features

* **k8s/helm-modules/cilium:** upgrade to 1.14.2 ([871dbbc](https://github.com/ds-onyx-shark/terraform-modules/commit/871dbbc34e6a3a12e949aef58f1152c3f5dadb7e))

## [1.115.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.114.0...v1.115.0) (2023-10-19)


### Features

* **k8s/helm-modules/efs-csi-driver:** bump to 2.5.0 ([18266e7](https://github.com/ds-onyx-shark/terraform-modules/commit/18266e7edafe2be038d33782fba28823d3b6a4de))

## [1.114.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.113.0...v1.114.0) (2023-10-19)


### Features

* **k8s/helm-modules/velero:** upgrade velero to hcp vault ([b9a77a4](https://github.com/ds-onyx-shark/terraform-modules/commit/b9a77a445b22f1651cfd1b1c7346661402223500))

## [1.113.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.112.0...v1.113.0) (2023-10-18)


### Features

* **k8s/helm-modules:** upgrade cluster-autoscaler and ebs-csi-driver to hcp vault ([ab7be54](https://github.com/ds-onyx-shark/terraform-modules/commit/ab7be54280a5c04aa3b755838deed8ffb0193b43))

## [1.112.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.111.2...v1.112.0) (2023-10-17)


### Features

* **k8s/helm-modules:** upgrade datadog and datadog-operator to use hcp vault ([5745087](https://github.com/ds-onyx-shark/terraform-modules/commit/5745087d370f93d3d289d8524c90ad9497c33ae5))

## [1.111.2](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.111.1...v1.111.2) (2023-10-12)


### Bug Fixes

* **aws/rds:** move maintenance window to avoid clashing with backups ([6cf9e5d](https://github.com/ds-onyx-shark/terraform-modules/commit/6cf9e5ddede3b1b776f8eea6063b3ac5b8f4cfb3))

## [1.111.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.111.0...v1.111.1) (2023-10-11)


### Bug Fixes

* **vault/drone-approle:** add parameter for plugin_roles + change default policy ([365ba9e](https://github.com/ds-onyx-shark/terraform-modules/commit/365ba9eb51b9a858873b38f87771e75c417fe6c5))

## [1.111.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.110.4...v1.111.0) (2023-10-09)


### Features

* **k8s/helm-modules:** upgrade cert-manager external-dns argo-cd pinniped to use new HCP vault infrastructure ([0f2b219](https://github.com/ds-onyx-shark/terraform-modules/commit/0f2b219c3a5ab1090779147857d17d5945baf8a6))

## [1.110.4](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.110.3...v1.110.4) (2023-10-05)


### Bug Fixes

* **datadog/monitor/modules/rds:** use correct values for alert descriptions ([b7df77c](https://github.com/ds-onyx-shark/terraform-modules/commit/b7df77c5dc042a04cf3e7784966e07b46ae29512))

## [1.110.3](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.110.2...v1.110.3) (2023-10-04)


### Bug Fixes

* **vault/tenant/root-namespace:** add id output ([10eb2f3](https://github.com/ds-onyx-shark/terraform-modules/commit/10eb2f3b53fef7939edf5077cfc9449343a949b7))

## [1.110.2](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.110.1...v1.110.2) (2023-10-03)


### Bug Fixes

* **vault/tenant/namespace:** add id output ([69dd46e](https://github.com/ds-onyx-shark/terraform-modules/commit/69dd46ef9f34ebb0144dd31c7f136eec3fdea62a))

## [1.110.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.110.0...v1.110.1) (2023-09-28)


### Bug Fixes

* **aws/rds:** add moved block and removed password from replicas ([8316947](https://github.com/ds-onyx-shark/terraform-modules/commit/831694742f6be64a70eea68831c6aecc8b2ffe0a))

## [1.110.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.109.0...v1.110.0) (2023-09-28)


### Features

* **aws/rds:** bump rds module to v6.1.1 ([4b99c59](https://github.com/ds-onyx-shark/terraform-modules/commit/4b99c5988dc3713492cdb959bae791e63c4c6118))

## [1.109.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.108.3...v1.109.0) (2023-09-27)


### Features

* **aws/tgw-attachment:** add appliance mode support switch ([4954141](https://github.com/ds-onyx-shark/terraform-modules/commit/4954141431badd77d7eb23390dc7df069e6e2399))

## [1.108.3](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.108.2...v1.108.3) (2023-09-21)


### Bug Fixes

* **vault/drone-approle:** fix token_num_uses should not be set ([f2f2d15](https://github.com/ds-onyx-shark/terraform-modules/commit/f2f2d15bc39f6ffe01229099d2d4836271470539))

## [1.108.2](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.108.1...v1.108.2) (2023-09-20)


### Bug Fixes

* **vsphere/linux-swarm/generic/...:** fix some issues in legacy module ([297af52](https://github.com/ds-onyx-shark/terraform-modules/commit/297af5217d951b0be3ef37aedf998458e8ea5843))

## [1.108.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.108.0...v1.108.1) (2023-09-19)


### Bug Fixes

* **vault/drone-approle:** fix rules in default repo policy ([fce70e4](https://github.com/ds-onyx-shark/terraform-modules/commit/fce70e4f5fc05ffba9b65c42b9d30172a8d993e7))

## [1.108.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.107.0...v1.108.0) (2023-09-18)


### Features

* **aws/rds:** add support for prefix-lists ([1d019b8](https://github.com/ds-onyx-shark/terraform-modules/commit/1d019b87bff94d732d06b589415b3770ad4b3ce1))

## [1.107.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.106.3...v1.107.0) (2023-09-18)


### Features

* **aws/rds:** added auto_minor_version_upgrade switch ([416462a](https://github.com/ds-onyx-shark/terraform-modules/commit/416462a6ddf0cbcd050365fe671508cc76345ab8))

## [1.106.3](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.106.2...v1.106.3) (2023-09-13)


### Bug Fixes

* **aws/route53:** refactor to support hcp vault ([3658937](https://github.com/ds-onyx-shark/terraform-modules/commit/3658937c3d2d9a64ce6dac06493d114af12914d0))

## [1.106.2](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.106.1...v1.106.2) (2023-09-13)


### Bug Fixes

* **vault/tenant/root-namespace:** add missing callback url in oidc role ([82e81bc](https://github.com/ds-onyx-shark/terraform-modules/commit/82e81bcb57832cca19f5dcb452e26a3ffcb6762c))

## [1.106.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.106.0...v1.106.1) (2023-09-13)


### Bug Fixes

* **vault/tenant/root-namespace:** Add extra localhost callback urls to support multiple vault providers in TF ([f80415d](https://github.com/ds-onyx-shark/terraform-modules/commit/f80415dfefc3766ea816d05833d4ffb8705cc621))

## [1.106.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.105.5...v1.106.0) (2023-09-12)


### Features

* **vault/drone-approle:** Added module for creating approles for Drone repositories and plugins ([779587b](https://github.com/ds-onyx-shark/terraform-modules/commit/779587b45bbeecbae942754668874c7ac993203e))

## [1.105.5](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.105.4...v1.105.5) (2023-09-11)


### Bug Fixes

* **vault/aws-backend:** refactor module to support HCP vault ([41d9839](https://github.com/ds-onyx-shark/terraform-modules/commit/41d9839a45a5f1fac6bd24a588d526a5676247da))

## [1.105.4](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.105.3...v1.105.4) (2023-09-08)


### Bug Fixes

* **vault/aws-backend:** add support for hcp vault ([5d1c513](https://github.com/ds-onyx-shark/terraform-modules/commit/5d1c513d9220ae320e3390909cb280619af68194))

## [1.105.3](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.105.2...v1.105.3) (2023-09-08)


### Chores

* **aws/eks/cluster:** add argo-cd and bump all modules ([c6d6cb9](https://github.com/ds-onyx-shark/terraform-modules/commit/c6d6cb91361c7a26b6110135559964f32d621a3f))

## [1.105.2](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.105.1...v1.105.2) (2023-09-08)


### Bug Fixes

* **vault/tenant/root-namespace:** remove path_full output ([f210664](https://github.com/ds-onyx-shark/terraform-modules/commit/f21066484f38cc2a9b36f9ad3a36905fb7863981))

## [1.105.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.105.0...v1.105.1) (2023-09-08)


### Bug Fixes

* **vault/tenant/root-namespace:** add missing path_full output ([3edc46f](https://github.com/ds-onyx-shark/terraform-modules/commit/3edc46fa2af84bc0945cb5724a8bbd0794e8e12e))

## [1.105.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.104.0...v1.105.0) (2023-09-08)


### Features

* add vault hcp tenant modules ([8e81ed4](https://github.com/ds-onyx-shark/terraform-modules/commit/8e81ed4ccf75c7fa6ee52f925ae90ffb83f13a3f))

## [1.104.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.103.0...v1.104.0) (2023-09-05)


### Features

* **aws/linux-swarm/generic:** use dsservice.lokal records instead of dsservice.eu ([5275fe9](https://github.com/ds-onyx-shark/terraform-modules/commit/5275fe935bd7b774e67ada7d967ef1844363e8be))

## [1.103.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.102.0...v1.103.0) (2023-09-05)


### Features

* **aws/linux-swarm/generic:** bump coreos to 38 ([206e515](https://github.com/ds-onyx-shark/terraform-modules/commit/206e51546f2dbec3d2879fdb4152de21e060dc18))

## [1.102.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.101.0...v1.102.0) (2023-09-05)


### Features

* **coreos-snippets/storage/nfs/var-mnt-swarm-shared:** add noresvport option to shared swarm mount ([7d9cb50](https://github.com/ds-onyx-shark/terraform-modules/commit/7d9cb50e40ac0354158406a2702abbfdc3a784b4))

## [1.101.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.100.2...v1.101.0) (2023-08-04)


### Features

* **vault/drone-repo-approle-backend-role:** Add module for creating repo approles for Drone ([dbe248d](https://github.com/ds-onyx-shark/terraform-modules/commit/dbe248d8afdb7c0df1d20a7ca15f80cc125c43d8))

## [1.100.2](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.100.1...v1.100.2) (2023-06-29)


### Chores

* **vsphere/k8s/rke/cluster:** enable datadog operator module ([9ccd7d2](https://github.com/ds-onyx-shark/terraform-modules/commit/9ccd7d269a5557d1ce2bbbf44818910342e8cf61))

## [1.100.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.100.0...v1.100.1) (2023-06-29)


### Bug Fixes

* **k8s/helm-modules/argo-cd:** use correct github auth ([221a70c](https://github.com/ds-onyx-shark/terraform-modules/commit/221a70c77870d3abebacd61f14d3e47519eab74e))

## [1.100.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.99.2...v1.100.0) (2023-06-29)


### Features

* **k8s/helm-modules/datadog-operator:** Add datadog-operator module ([660928f](https://github.com/ds-onyx-shark/terraform-modules/commit/660928f600bf9080ca45a2a4e78063fd6760cb71))

## [1.99.2](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.99.1...v1.99.2) (2023-06-26)


### Bug Fixes

* **datadog/monitor/modules/drone-server:** Add SSL check monitor ([206b623](https://github.com/ds-onyx-shark/terraform-modules/commit/206b623c3f4b9c9def837dc46e76e0b924d9cf2b))

## [1.99.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.99.0...v1.99.1) (2023-06-22)


### Bug Fixes

* **aws/drone:** ignore ami changes in server and runners ([3f880d6](https://github.com/ds-onyx-shark/terraform-modules/commit/3f880d66cc35421d2440da641b8e217f9c77b0a7))


### Chores

* **aws/drone/runners:** use environment_type in naming ([3a2a2ea](https://github.com/ds-onyx-shark/terraform-modules/commit/3a2a2ea8ca1cfefc120dabab66555ea60c3bbde6))

## [1.99.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.98.1...v1.99.0) (2023-05-30)


### Features

* **datadog/monitor/modules/drone-server:** Add drone-server datadog module ([3e3337c](https://github.com/ds-onyx-shark/terraform-modules/commit/3e3337cc377d54f5a606fea90ca4c0f4e2390e51))

## [1.98.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.98.0...v1.98.1) (2023-05-26)


### Bug Fixes

* **aws/drone/runners:** add environment_type variable ([02fea6b](https://github.com/ds-onyx-shark/terraform-modules/commit/02fea6ba14117a89acbf751ce466d89808439098))

## [1.98.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.97.0...v1.98.0) (2023-05-26)


### Features

* **datadog/monitor/modules/drone-runner:** Add new monitor module for Drone runners ([f5408a9](https://github.com/ds-onyx-shark/terraform-modules/commit/f5408a9ca5b5ad61bb63b71041aaa935c7d33b63))

## [1.97.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.96.0...v1.97.0) (2023-05-24)


### Features

* Allow overriding thin_provisioned for template disks ([8f2f194](https://github.com/ds-onyx-shark/terraform-modules/commit/8f2f19416c388d1e9d9c0694600daae934ab376c))

## [1.96.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.95.1...v1.96.0) (2023-05-24)


### Features

* add drone runner datadog module ([4d3da30](https://github.com/ds-onyx-shark/terraform-modules/commit/4d3da30742c719b3fff285c1319c6beb13d0f390))

## [1.95.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.95.0...v1.95.1) (2023-05-04)


### Bug Fixes

* **vsphere/k8s/coreos-vm:** upgrade to coreos 38 ([09a9128](https://github.com/ds-onyx-shark/terraform-modules/commit/09a9128612c3b1c572b3a8632d8183c9bdc491e8))

## [1.95.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.94.2...v1.95.0) (2023-05-04)


### Features

* Add Drone server ip allowlist ([4b87152](https://github.com/ds-onyx-shark/terraform-modules/commit/4b87152c2ada91aec45f65f252ad2e1e86692467))

## [1.94.2](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.94.1...v1.94.2) (2023-05-02)


### Bug Fixes

* **k8s/helm-modules/velero:** remove private acl ([5e3158d](https://github.com/ds-onyx-shark/terraform-modules/commit/5e3158d94dfa518f4bced8c23dc4aaaab5155587))

## [1.94.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.94.0...v1.94.1) (2023-05-02)


### Chores

* add .releaserc ([1350616](https://github.com/ds-onyx-shark/terraform-modules/commit/1350616d94f7b1d9039de6be7c4d5613e8df883b))

## [1.94.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.93.0...v1.94.0) (2023-05-02)


### Features

* **aws/rds:** add support for multiple vault secret mountpoints ([d1b69d8](https://github.com/ds-onyx-shark/terraform-modules/commit/d1b69d807e083f711558fb0a5952697429003f35))
* **aws/rds:** add vault secret metadata tag terraform-config ([978f930](https://github.com/ds-onyx-shark/terraform-modules/commit/978f9300f47e1af4b0bfaa2e9b16a35ae11298ee))


### Bug Fixes

* **vault/auth-backend/k8s:** tune lease TTL to avoid Vault lease sprawl ([8e34e94](https://github.com/ds-onyx-shark/terraform-modules/commit/8e34e944a6a6e9c62e06b1a7577afc72c08442d4))
* **vsphere/k8s/rke/cluster:** Pull system images with dockerhub credentials ([ad1a22f](https://github.com/ds-onyx-shark/terraform-modules/commit/ad1a22f0e40e2b47a9af5fdccc11a68531f5050c))
* **vsphere/k8s/rke/nodes:** remove vmware fix ([df3a7da](https://github.com/ds-onyx-shark/terraform-modules/commit/df3a7da900fb0cad67fc760ceb821e1279435e8f))


### Refactor

* use drone template ([46042fb](https://github.com/ds-onyx-shark/terraform-modules/commit/46042fbb97890ad2a87fdb2fd7d30964381ed609))

## [1.93.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.92.1...v1.93.0) (2023-04-11)


### Features

* **vault/tenant/namespace:** Add vault enterprise tenant module ([e6fcd7f](https://github.com/ds-onyx-shark/terraform-modules/commits/e6fcd7ffd14496ea35ea10b0dd518e8679d1cdc5))

## [1.92.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.92.0...v1.92.1) (2023-04-03)


### Bug Fixes

* **aws/rds:** use https instead of git in source ([0630589](https://github.com/ds-onyx-shark/terraform-modules/commits/063058937c1f7440309033aefbb01a6179396c42))

## [1.92.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.91.1...v1.92.0) (2023-03-31)


### Features

* **aws/drone/server:** add module ([2abec2d](https://github.com/ds-onyx-shark/terraform-modules/commits/2abec2d200243102881749786ebec5929a7a3365))

## [1.91.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.91.0...v1.91.1) (2023-03-31)


### Bug Fixes

* **aws/rds:** change rds_storage_iops and rds_storage_throughput defaults to null ([758eeed](https://github.com/ds-onyx-shark/terraform-modules/commits/758eeed4908834d70276bb429353f09dca81d32b))
* **aws/rds:** change vault secret name to name_prefix ([32f9e53](https://github.com/ds-onyx-shark/terraform-modules/commits/32f9e5359b8f74a00f0f0336336d4adf296f07c9))

## [1.91.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.90.2...v1.91.0) (2023-03-30)


### Features

* **datadog/monitor/modules/rds:** add rds connection count monitor ([f929ea4](https://github.com/ds-onyx-shark/terraform-modules/commits/f929ea4de65d8ecd6c5f6b1248766059bd7a4c28))

## [1.90.2](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.90.1...v1.90.2) (2023-03-28)


### Bug Fixes

* **aws/rds:** remove backup retention variable ([3af8eac](https://github.com/ds-onyx-shark/terraform-modules/commits/3af8eaca07e65e80839c814e13ede5688fa2d011))

## [1.90.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.90.0...v1.90.1) (2023-03-27)


### Chores

* **aws/rds:** readme formatting ([30e4f10](https://github.com/ds-onyx-shark/terraform-modules/commits/30e4f10bd722d9e23f717be57fab3ccd433831ff))

## [1.90.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.89.0...v1.90.0) (2023-03-27)


### Features

* **datadog/monitor/modules/rds:** add rds monitor collection ([18058d6](https://github.com/ds-onyx-shark/terraform-modules/commits/18058d6c43217857f5ffbf070905f2fd08a19e65))
* **datadog/monitor:** add module ([e269bd0](https://github.com/ds-onyx-shark/terraform-modules/commits/e269bd068db3b1ecc212aac40ffb0a0e39c9bf25))


### Chores

* **aws/rds:** cleanup ([cb264a7](https://github.com/ds-onyx-shark/terraform-modules/commits/cb264a75a3d2f6b8fa0778c853c9a492c1990bf5))

## [1.89.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.88.0...v1.89.0) (2023-03-27)


### Features

* **aws/rds:** add rds_backup_tags variable ([05158ae](https://github.com/ds-onyx-shark/terraform-modules/commits/05158ae2ba98672d4be47d2e036003f2df6c04e4))

## [1.88.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.87.1...v1.88.0) (2023-03-24)


### Features

* **aws/rds:** add allow_major_version_upgrade variable ([968a0ba](https://github.com/ds-onyx-shark/terraform-modules/commits/968a0ba8bf855ab9b138c785be46090f3fbf00e2))
* **aws/rds:** add snapshot_identifier variable ([9874bbd](https://github.com/ds-onyx-shark/terraform-modules/commits/9874bbd4eb680636dd3878266b857470e5ea6c9d))
* **aws/rds:** add storage_encrypted variable ([6095626](https://github.com/ds-onyx-shark/terraform-modules/commits/60956266e66c6c6597d108e546dca624d676bffa))

## [1.87.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.87.0...v1.87.1) (2023-03-17)


### Chores

* **vsphere/k8s/rke/cluster:** Upgrade RKE provider to 1.4.0 and set default Kubernetes version to v1.24.9-rancher1-1 ([258f470](https://github.com/ds-onyx-shark/terraform-modules/commits/258f4703cfed8589c57d036b30e27574fe5aa0fb))

## [1.87.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.86.1...v1.87.0) (2023-03-17)


### Features

* **k8s/helm-modules/pinniped:** Add pinniped token rotation ([c7c5973](https://github.com/ds-onyx-shark/terraform-modules/commits/c7c59737de208de00f561c851efd163902b8cce0))

## [1.86.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.86.0...v1.86.1) (2023-03-17)


### Bug Fixes

* **vsphere/k8s/rke/cluster:** upgrade modules ([b5b229d](https://github.com/ds-onyx-shark/terraform-modules/commits/b5b229d887b0061ac0af25eae2b46689e24f7bea))

## [1.86.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.85.0...v1.86.0) (2023-03-15)


### Features

* **aws/rds:** add performance insights switch ([5d4ff9d](https://github.com/ds-onyx-shark/terraform-modules/commits/5d4ff9d2341b12b4a74c00750998f29019cda379))

## [1.85.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.84.1...v1.85.0) (2023-03-15)


### Features

* **k8s/helm-modules/argo-cd:** add module ([0352be3](https://github.com/ds-onyx-shark/terraform-modules/commits/0352be3a1e8fb0e4285447f14b8a5f23f4a6420b))

## [1.84.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.84.0...v1.84.1) (2023-02-27)


### Chores

* **aws/rds:** reuse options group in read replicas ([0baf400](https://github.com/ds-onyx-shark/terraform-modules/commits/0baf400ada9228661df60275e32d59405ad26efd))

## [1.84.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.83.2...v1.84.0) (2023-02-27)


### Features

* **aws/rds:** add old ca-identifier to replicas while using newer for primary dbs ([bf45170](https://github.com/ds-onyx-shark/terraform-modules/commits/bf451702151ca4d01d27dbf03e715220e1c09e99))

## [1.83.2](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.83.1...v1.83.2) (2023-02-21)


### Chores

* **aws/rds:** reuse parameter group in read replicas ([bc6ad19](https://github.com/ds-onyx-shark/terraform-modules/commits/bc6ad197ca7b65dd6032a35cae9e106e41dea5ba))

## [1.83.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.83.0...v1.83.1) (2023-02-17)


### Bug Fixes

* **aws/rds:** revert to older ca certificate ([e5c99cd](https://github.com/ds-onyx-shark/terraform-modules/commits/e5c99cdb62564679923f956733599e99a3fcec53))

## [1.83.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.82.0...v1.83.0) (2023-02-10)


### Features

* **aws/rds:** add port and endpoint address to vault secret and output ([922f499](https://github.com/ds-onyx-shark/terraform-modules/commits/922f49957baadb38f48ebef0020f93e86eba41f2))
* **aws/rds:** add storage iops, throughput and autoscaling ([e16c653](https://github.com/ds-onyx-shark/terraform-modules/commits/e16c653b0f915c35ed5560c345838179d9d2722c))

## [1.82.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.81.0...v1.82.0) (2023-02-07)


### Features

* **aws/rds:** add environment_type variable ([3c3fb1f](https://github.com/ds-onyx-shark/terraform-modules/commits/3c3fb1fbd29fb583c8cfb149905858009933d1af))

## [1.81.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.80.3...v1.81.0) (2023-02-01)


### Features

* **aws/rds:** add module ([7aa67d4](https://github.com/ds-onyx-shark/terraform-modules/commits/7aa67d418dfa754df9bbf759332619e0ad20ac5c))

## [1.80.3](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.80.2...v1.80.3) (2023-02-01)


### Bug Fixes

* **vsphere/linux-swarm:** add dc id output ([835c385](https://github.com/ds-onyx-shark/terraform-modules/commits/835c385d3b7057c2b07412261c06020b3f55663c))

## [1.80.2](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.80.1...v1.80.2) (2023-01-19)


### Bug Fixes

* **vsphere/linux/on-datastore/with-one-persistent-disk:** update pacman provider ([be766d9](https://github.com/ds-onyx-shark/terraform-modules/commits/be766d95a1065930dcc42dbb90e4fd5b5ba4d4b5))

## [1.80.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.80.0...v1.80.1) (2023-01-17)


### Chores

* **aws/drone/network:** remove tgw files and variables ([5f2645c](https://github.com/ds-onyx-shark/terraform-modules/commits/5f2645ca8c37bd4f6795b4b3c8f32485a8be62d0))

## [1.80.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.79.0...v1.80.0) (2023-01-06)


### Features

* add aws datadog-forwarder module ([3e20eae](https://github.com/ds-onyx-shark/terraform-modules/commits/3e20eaeb24feb5a289fd7f679f330fa1c75e3261))

## [1.79.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.78.1...v1.79.0) (2023-01-02)


### Features

* **aws/tgw-attachment:** add module ([779e4d8](https://github.com/ds-onyx-shark/terraform-modules/commits/779e4d835139b722d585de54e9f02035a68999f5))

## [1.78.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.78.0...v1.78.1) (2022-12-21)


### Bug Fixes

* **aws/drone/runners:** replace _ with - in dns record ([60ee4e1](https://github.com/ds-onyx-shark/terraform-modules/commits/60ee4e133377c3fbf2885eb7c567b12e51b0c4d3))

## [1.78.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.77.1...v1.78.0) (2022-12-21)


### Features

* **aws/drone:** add drone runner modules ([a3f6820](https://github.com/ds-onyx-shark/terraform-modules/commits/a3f682052b308a97cce1e365813b4be58f39c36a))


### Chores

* **k8s/helm-modules/datadog:** terraform fmt ([cab3cec](https://github.com/ds-onyx-shark/terraform-modules/commits/cab3cecadf2d81766460105d1bcdc9c6c0331247))

## [1.77.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.77.0...v1.77.1) (2022-12-19)


### Chores

* **vsphere/settings:** Update ubuntu 22.04 template ([39df33d](https://github.com/ds-onyx-shark/terraform-modules/commits/39df33d1e7fa50c5ccd1e1a02780da693182ef10))

## [1.77.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.76.1...v1.77.0) (2022-12-13)


### Features

* **vault/credential-sources/datadog:** Added generic credentials for datadog ([6f9bd4a](https://github.com/ds-onyx-shark/terraform-modules/commits/6f9bd4a38249a230625cc240266c1aafb91987c7))

## [1.76.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.76.0...v1.76.1) (2022-11-25)


### Bug Fixes

* **vsphere/k8s/rke/cluster:** Bump addon version ([6891c62](https://github.com/ds-onyx-shark/terraform-modules/commits/6891c62fbfc9d606bd2b213061394a1c09342499))

## [1.76.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.75.2...v1.76.0) (2022-11-25)


### Features

* **k8s/helm-modules/nfs-subdir-external-provisioner:** Add NFS privisioner addon ([85723c6](https://github.com/ds-onyx-shark/terraform-modules/commits/85723c691e30f7a498d85eda6dd6044607490d1e))

## [1.75.2](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.75.1...v1.75.2) (2022-11-24)


### Bug Fixes

* **vsphere/k8s/rke/cluster:** bump datadog module version ([a68475b](https://github.com/ds-onyx-shark/terraform-modules/commits/a68475bc6f334f411878a8a87454ab4b0270f030))

## [1.75.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.75.0...v1.75.1) (2022-11-24)


### Bug Fixes

* **k8s/helm-modules/datadog:** bump chart version + add helm check integration ([71da606](https://github.com/ds-onyx-shark/terraform-modules/commits/71da6069a9f11383d0ad5d5d8f75e295226cb32d))

## [1.75.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.74.0...v1.75.0) (2022-11-22)


### Features

* **aws/eks/cluster:** add custom oidc thumbprint variable ([a584b1c](https://github.com/ds-onyx-shark/terraform-modules/commits/a584b1ce5f10411ff7f29e092911935cf8ac3bde))
* **aws/eks/cluster:** add eks addon bootstrappers ([a776dad](https://github.com/ds-onyx-shark/terraform-modules/commits/a776dadb22321277d6f41b876d417b2cf1e77fbf))
* **aws/eks/cluster:** add ssm core role to default node group variables ([2f138a0](https://github.com/ds-onyx-shark/terraform-modules/commits/2f138a045d7fbeeca61013159b5767197362a428))


### Bug Fixes

* **aws/eks/cluster:** reconfigure waiter dependencies ([b623abc](https://github.com/ds-onyx-shark/terraform-modules/commits/b623abcad40ff6bae8e7bac834162ff06d3ede84))


### Chores

* **aws/eks/cluster:** bump default eks version ([b8a17cf](https://github.com/ds-onyx-shark/terraform-modules/commits/b8a17cff3461be5fdbd51f2efc36724da6c1c6ef))
* **aws/eks/cluster:** cleanup local modules coredns, efs-csi-driver, velero, wazuh, kubernetes-dashboard ([af813f1](https://github.com/ds-onyx-shark/terraform-modules/commits/af813f1485f16e4866d923d90c489ba699e61d3f))
* **aws/eks/cluster:** remove aws-auth management ([3d55e2f](https://github.com/ds-onyx-shark/terraform-modules/commits/3d55e2f49229c8e7c0ff07619d5de5fb4f88ee09))
* **aws/eks/cluster:** remove self managed node group options ([dcd2335](https://github.com/ds-onyx-shark/terraform-modules/commits/dcd23355f61255eb468217664e6c0dac82791233))
* **aws/eks/cluster:** remove unused variables and moved comments to descriptions ([4f89f10](https://github.com/ds-onyx-shark/terraform-modules/commits/4f89f1070bd7bd25022768b8ffbf9c2337d08fc7))
* **aws/eks/cluster:** switch coredns and efs-csi-driver to shared modules ([596c5dd](https://github.com/ds-onyx-shark/terraform-modules/commits/596c5dded96ad372534fdd6071f4c1dd537980ce))

## [1.74.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.73.2...v1.74.0) (2022-11-18)


### Features

* **k8s/helm-modules/coredns:** add module ([7ceff7b](https://github.com/ds-onyx-shark/terraform-modules/commits/7ceff7b91f3a6f52e628eb681d87a1e10fde2fa7))
* **k8s/helm-modules/efs-csi-driver:** add module ([95e912b](https://github.com/ds-onyx-shark/terraform-modules/commits/95e912b9907f00925be29353755038cf14a312f6))

## [1.73.2](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.73.1...v1.73.2) (2022-11-18)


### Bug Fixes

* **vsphere/k8s/rke/cluster:** Fix wrong resource name ([5d808e0](https://github.com/ds-onyx-shark/terraform-modules/commits/5d808e0f5e88f27172c778f2274f6d1b5bb77833))

## [1.73.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.73.0...v1.73.1) (2022-11-18)


### Chores

* **vsphere/k8s/rke/cluster:** Upgrade RKE provider and kubernetes versions ([727d4f0](https://github.com/ds-onyx-shark/terraform-modules/commits/727d4f0fc50454a4ef6d853279c4de8a8f356bc8))

## [1.73.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.72.1...v1.73.0) (2022-11-17)


### Features

* **k8s/helm-modules/cilium:** switch to kube-proxy replacement ([3b18522](https://github.com/ds-onyx-shark/terraform-modules/commits/3b1852230a360bd76ae1ff9e70a01dacd950cb28))

## [1.72.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.72.0...v1.72.1) (2022-11-17)


### Bug Fixes

* **vsphere/k8s/coreos-vm:** bump version ([421a5d7](https://github.com/ds-onyx-shark/terraform-modules/commits/421a5d799a9d5285e706ff2f170ec3706b454b3b))
* **vsphere/k8s/nodes:** bump version ([2b4b1ff](https://github.com/ds-onyx-shark/terraform-modules/commits/2b4b1ff989cee84f7ff3155f31cf916f9d4f55ec))

## [1.72.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.71.0...v1.72.0) (2022-11-16)


### Features

* Add vsphere cluster modules ([475aed6](https://github.com/ds-onyx-shark/terraform-modules/commits/475aed68efbd67c46ad4fc984c7eac5f6a9f23a9))

## [1.71.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.70.1...v1.71.0) (2022-11-09)


### Features

* **vsphere/vm:** switch to public pacman provider ([91d1518](https://github.com/ds-onyx-shark/terraform-modules/commits/91d1518393dd5113853539e4a84c3ae115ccebc2))

## [1.70.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.70.0...v1.70.1) (2022-10-25)


### Bug Fixes

* **vsphere/vm:** change dns provider from hashicorp/dns to danskespil/dns ([a823945](https://github.com/ds-onyx-shark/terraform-modules/commits/a8239457cec75c211a8951efaec1f17519d10173))

## [1.70.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.69.1...v1.70.0) (2022-10-25)


### Features

* **vsphere/settings:** Added ubuntu 22.04 image ([2ea0b50](https://github.com/ds-onyx-shark/terraform-modules/commits/2ea0b50cc9cd99a5f5d8b7456dda3e4cbb400e6a))

## [1.69.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.69.0...v1.69.1) (2022-10-19)


### Bug Fixes

* **aws/eks/cluster:** add correct type to cluster-autoscaler enabler variable ([229e5f3](https://github.com/ds-onyx-shark/terraform-modules/commits/229e5f3228297346b63cd6b08a11dc37a25bc4bf))

## [1.69.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.68.0...v1.69.0) (2022-10-19)


### Features

* **aws/eks/cluster:** add cluster-autoscaler addon ([78c6413](https://github.com/ds-onyx-shark/terraform-modules/commits/78c6413d0376dfb74e1bda1a355f1b2d81971cd5))
* **aws/eks/cluster:** bump cilium to v1.68.0 ([f861ece](https://github.com/ds-onyx-shark/terraform-modules/commits/f861ece7dcb2c9806036f6a7fd9fee6e9319d104))

## [1.68.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.67.0...v1.68.0) (2022-10-19)


### Features

* **k8s/helm-modules/cilium:** bump to v1.12.2 ([ddc6332](https://github.com/ds-onyx-shark/terraform-modules/commits/ddc63323135760ca0c0d4042fad5ec9b803caf32))

## [1.67.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.66.0...v1.67.0) (2022-10-19)


### Features

* **k8s/helm-modules/cluster-autoscaler:** add module ([446325a](https://github.com/ds-onyx-shark/terraform-modules/commits/446325ae03471f3816418763b9d8174b3e102a10))

## [1.66.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.65.1...v1.66.0) (2022-10-19)


### Features

* **datadog/aws-integration:** add module ([97e1106](https://github.com/ds-onyx-shark/terraform-modules/commits/97e110602445a105940a137a6f68346c2f2fbd2e))

## [1.65.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.65.0...v1.65.1) (2022-10-17)


### Refactor

* **aws/eks/cluster:** update and refactor kubecost addon ([21806d5](https://github.com/ds-onyx-shark/terraform-modules/commits/21806d508acedbe8066a53f844730a7b8dfb8367))


### Chores

* **aws/eks/cluster:** remove unused parameters from efs-csi-driver ([a3c50a5](https://github.com/ds-onyx-shark/terraform-modules/commits/a3c50a5b436eba9a7946f7ac2dbfb769e034e852))

## [1.65.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.64.1...v1.65.0) (2022-10-17)


### Features

* **aws/eks/cluster:** bump multiple addon versions and cleanup dependencies ([d1ec70b](https://github.com/ds-onyx-shark/terraform-modules/commits/d1ec70bc8ffc5f7dde80788d99679b1673d9b530))

## [1.64.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.64.0...v1.64.1) (2022-10-11)


### Bug Fixes

* **k8s/helm-modules/waf:** fix datadog logging ([e259581](https://github.com/ds-onyx-shark/terraform-modules/commits/e259581005a11207f9e4ae6ace639eb5428de125))
* **k8s/helm-modules/waf:** fix ipv6 issues on vmware ([55b68c7](https://github.com/ds-onyx-shark/terraform-modules/commits/55b68c7809108d8d99e5b4f19bdee6a0156e60f2))

## [1.64.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.63.1...v1.64.0) (2022-10-11)


### Features

* **k8s/helm-modules/pinniped:** switch to forked dns provider ([7d60853](https://github.com/ds-onyx-shark/terraform-modules/commits/7d60853bdb40ea8ee3fb221976e8da06b23442ce))
* **k8s/helm-modules/traefik:** switch dashboard to internal endpoints ([e892ccc](https://github.com/ds-onyx-shark/terraform-modules/commits/e892ccc88d6587bffb99c8d26687de54b1d11e93))

## [1.63.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.63.0...v1.63.1) (2022-10-07)


### Bug Fixes

* **k8s/helm-modules/secret-store-csi-driver:** Add variable kubelet_root_dir. Required when using CoreOS + RKE. ([d5c47b9](https://github.com/ds-onyx-shark/terraform-modules/commits/d5c47b961359b6feee6cf42feb1c310e96661789))

## [1.63.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.62.0...v1.63.0) (2022-10-07)


### Features

* **k8s/helm-modules/waf:** add module ([fcd17f2](https://github.com/ds-onyx-shark/terraform-modules/commits/fcd17f24e12ab81d88575e2147402152e3e033a2))

## [1.62.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.61.0...v1.62.0) (2022-09-28)


### Features

* **aws/eks/cluster:** add efs-csi-driver addon ([b6b4eec](https://github.com/ds-onyx-shark/terraform-modules/commits/b6b4eec79c2c417ada5935ac9ec2226aef70143f))

## [1.61.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.60.1...v1.61.0) (2022-09-28)


### Features

* **k8s/helm-modules/ebs-csi-driver:** add module ([d427ee3](https://github.com/ds-onyx-shark/terraform-modules/commits/d427ee3f223b5af62dd6aa63079ca41651bbc18f))

## [1.60.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.60.0...v1.60.1) (2022-09-20)


### Bug Fixes

* **cloudamqp/rmq:** remove cloudamqp provider version constraint ([c44862f](https://github.com/ds-onyx-shark/terraform-modules/commits/c44862fc41d8e85e7695fc1b4db20c97ea5d2144))

## [1.60.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.59.0...v1.60.0) (2022-09-13)


### Features

* **aws/eks/cluster:** bump kubernetes provider version ([da867ae](https://github.com/ds-onyx-shark/terraform-modules/commits/da867ae59a624fadabf53f58ed933cbadef1e4a7))

## [1.59.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.58.0...v1.59.0) (2022-09-13)


### Features

* **aws/eks/cluster:** bump eks module version ([782d0f3](https://github.com/ds-onyx-shark/terraform-modules/commits/782d0f3ac8a55cd8890870d74f6a8c1170bce839))
* **aws/eks/cluster:** bump vault module version ([f1c1842](https://github.com/ds-onyx-shark/terraform-modules/commits/f1c184237f891cbfe8e4b53d9754cab611d524a1))
* **aws/eks/cluster:** bump velero module version ([3cd736b](https://github.com/ds-onyx-shark/terraform-modules/commits/3cd736bc360849094d78964a79ec411a19ce8c84))

## [1.58.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.57.0...v1.58.0) (2022-09-13)


### Features

* **k8s/helm-modules/velero:** bump s3 bucket module version ([bbae4e9](https://github.com/ds-onyx-shark/terraform-modules/commits/bbae4e91d4e2cd86dabc0cc1964ecd23d0a35968))

## [1.57.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.56.0...v1.57.0) (2022-09-13)


### Features

* **k8s/helm-modules/vault:** add custom sa token for external vault auth ([e56e088](https://github.com/ds-onyx-shark/terraform-modules/commits/e56e0888b398e40079a816fd17ed5706c2422ed5))

## [1.56.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.55.0...v1.56.0) (2022-09-09)


### Features

* **aws/eks/cluster:** add pinniped support ([c0dbc9e](https://github.com/ds-onyx-shark/terraform-modules/commits/c0dbc9eccb20918831a1761395a843afcf395474))
* **aws/eks/cluster:** bump traefik version and fix dependencies ([042453a](https://github.com/ds-onyx-shark/terraform-modules/commits/042453ab0e355b83f706eecd4cb2fb9825fc5f8e))

## [1.55.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.54.6...v1.55.0) (2022-09-08)


### Features

* **k8s/helm-modules/pinniped:** add pinniped module ([ac327f1](https://github.com/ds-onyx-shark/terraform-modules/commits/ac327f1e6bd818ee302e374a1046fa1099a13885))

## [1.54.6](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.54.5...v1.54.6) (2022-08-29)


### Bug Fixes

* **k8s/helm/charts/traefik:** move TLSStore resource to post-deploy chart ([65522ca](https://github.com/ds-onyx-shark/terraform-modules/commits/65522ca5970cf0bd66491db8121023aaba2b656c))

## [1.54.5](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.54.4...v1.54.5) (2022-08-22)


### Bug Fixes

* **cloudamqp/rmq:** Add terraform tag ([8074792](https://github.com/ds-onyx-shark/terraform-modules/commits/80747923dbabf2b3be1ae95bad0bfc61ec3875ac))

## [1.54.4](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.54.3...v1.54.4) (2022-08-19)


### Bug Fixes

* **cloudamqp/rmq:** Cleaned up + added DD integration and custom domain support ([1f1e257](https://github.com/ds-onyx-shark/terraform-modules/commits/1f1e257eee6b30faed895be6846d16a9bd3edd62))

## [1.54.3](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.54.2...v1.54.3) (2022-08-18)


### Bug Fixes

* **vault/data/ip-list:** change outputs ([3ddcd83](https://github.com/ds-onyx-shark/terraform-modules/commits/3ddcd8306869d30f37e74c915ca87e1864dbf68d))

## [1.54.2](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.54.1...v1.54.2) (2022-08-18)


### Bug Fixes

* **aws/mq:** Add preserve_client_ip to lb target group ([77498e8](https://github.com/ds-onyx-shark/terraform-modules/commits/77498e89e3f135ba0d0ae981fc2f1de43c8b9120))

## [1.54.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.54.0...v1.54.1) (2022-08-17)


### Bug Fixes

* **datadog-monitor:** remove deprecated option ([ff382ea](https://github.com/ds-onyx-shark/terraform-modules/commits/ff382ea4ced5e4608e04afd1d219c273df946b16))

## [1.54.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.53.1...v1.54.0) (2022-08-17)


### Features

* **cloudamqp/rmq:** Add cloudamqp module for creating RabbitMQ instances ([9c3a8e2](https://github.com/ds-onyx-shark/terraform-modules/commits/9c3a8e2efe75bffc04d3684f50bb3754bbe196d1))

## [1.53.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.53.0...v1.53.1) (2022-08-15)


### Bug Fixes

* **vault/data/ip-list:** rename outputs ([2f3ef9b](https://github.com/ds-onyx-shark/terraform-modules/commits/2f3ef9b2f64a0c3d556adf0b669daecd5b5e3d9d))

## [1.53.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.52.0...v1.53.0) (2022-08-12)


### Features

* **aws/eks/cluster:** bump traefik, vault and secret-store-csi-driver addons ([7b03871](https://github.com/ds-onyx-shark/terraform-modules/commits/7b038712c0c7f0ffeb5c7027618c7c6af262f4d4))

## [1.52.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.51.1...v1.52.0) (2022-08-12)


### Features

* **k8s/helm-modules/secret-store-csi-driver:** enable secret sync and rotation ([fc84268](https://github.com/ds-onyx-shark/terraform-modules/commits/fc84268a242b698c1b847b6c8f944830b1302601))
* **k8s/helm-modules/traefik:** add certificates to traefik using secret csi driver ([b0f5734](https://github.com/ds-onyx-shark/terraform-modules/commits/b0f5734ed9275a6232728abb14986a34e1ca149d))
* **k8s/helm-modules/traefik:** add pre-deploy sub chart and tlsstore and tlsoptions ([fc1adce](https://github.com/ds-onyx-shark/terraform-modules/commits/fc1adce6deb30b4210a53c8217c6021a0b26d06e))


### Bug Fixes

* **k8s/helm-modules/vault:** start csi driver daemonset pods on all nodes ([963c8b9](https://github.com/ds-onyx-shark/terraform-modules/commits/963c8b93d59cb2c22de23a65908e5835dc1291b6))


### Refactor

* **k8s/helm-modules/traefik:** rename custom-resources chart post-deploy ([8a83388](https://github.com/ds-onyx-shark/terraform-modules/commits/8a8338891e61ae7a128110bce2ed00e9dd462b4b))

## [1.51.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.51.0...v1.51.1) (2022-08-11)


### Bug Fixes

* **k8s/helm-modules/cert-manager:** allow dns01 challenge on custom nameservers ([2ff8c47](https://github.com/ds-onyx-shark/terraform-modules/commits/2ff8c4789a17f2213cffc431b6bc3823b3a7a326))

## [1.51.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.50.0...v1.51.0) (2022-08-02)


### Features

* **aws/eks/cluster:** add private_dns_zone_name variable to be ready for pinniped ([e5a12dc](https://github.com/ds-onyx-shark/terraform-modules/commits/e5a12dcca9523ac8cc93a57552f0e299144c36e0))

## [1.50.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.49.0...v1.50.0) (2022-07-20)


### Features

* **aws/eks/cluster:** add support for internal nlb and more traefik entrypoints ([8ad78b1](https://github.com/ds-onyx-shark/terraform-modules/commits/8ad78b1094f2c9e3f7c52f0a573eae2ae5f9593a))

## [1.49.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.48.0...v1.49.0) (2022-07-19)


### Features

* **aws/eks/cluster:** add support for internal nlb ([e31986b](https://github.com/ds-onyx-shark/terraform-modules/commits/e31986b6f6f8599469c18953a7d0fc97397f9ab5))

## [1.48.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.47.2...v1.48.0) (2022-07-19)


### Features

* **aws/eks/network:** add internal load balancer ([5552d86](https://github.com/ds-onyx-shark/terraform-modules/commits/5552d86d65de01976d7750d8b23e219a05c2cc27))

## [1.47.2](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.47.1...v1.47.2) (2022-07-15)


### Bug Fixes

* **vsphere/k8s/rke/nodes:** refactor ([7a328e6](https://github.com/ds-onyx-shark/terraform-modules/commits/7a328e62a0a1899c90841006317dca9565e9721a))

## [1.47.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.47.0...v1.47.1) (2022-07-15)


### Bug Fixes

* **vsphere/k8s/coreos-vm:** refactor ([4c774e7](https://github.com/ds-onyx-shark/terraform-modules/commits/4c774e70903e73b5dce8feb4acb8bdeed57bb275))
* **vsphere/k8s/rke/nodes:** refactor ([777b05e](https://github.com/ds-onyx-shark/terraform-modules/commits/777b05ea1b3cb43054ceedb4b3920de28ad81159))

## [1.47.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.46.0...v1.47.0) (2022-07-14)


### Features

* **aws/eks/cluster:** add datadog addon ([50d9161](https://github.com/ds-onyx-shark/terraform-modules/commits/50d91617c784ebed69cc84b8e9705f8c8dedc491))

## [1.46.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.45.0...v1.46.0) (2022-07-14)


### Features

* **k8s/helm-modules/datadog:** add tolerations to deploy daemonset to all nodes ([292e471](https://github.com/ds-onyx-shark/terraform-modules/commits/292e471365c8f2de852e07d93da6abdae9c39224))


### Chores

* **k8s/helm-modules/datadog:** remove unused aws-node cleanup resource ([a87f71c](https://github.com/ds-onyx-shark/terraform-modules/commits/a87f71c748853f7a4986c41b40abe917fa5ce7e7))

## [1.45.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.44.1...v1.45.0) (2022-07-14)


### Features

* **aws/eks/cluster:** bump cert-manager addon ([ccc613c](https://github.com/ds-onyx-shark/terraform-modules/commits/ccc613cf0df78923e21ae8efecf17f31880d137e))

## [1.44.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.44.0...v1.44.1) (2022-07-14)


### Refactor

* **k8s/helm-modules/cert-manager:** move clusterissuers to local helm chart ([91b3994](https://github.com/ds-onyx-shark/terraform-modules/commits/91b3994b3b1c46464bb2c2676255aec9b5b4808f))

## [1.44.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.43.0...v1.44.0) (2022-07-14)


### Features

* **aws/eks/cluster:** bump traefik addon ([207bfb4](https://github.com/ds-onyx-shark/terraform-modules/commits/207bfb429031c89033ef48becb61a5cf7e4d620e))

## [1.43.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.42.2...v1.43.0) (2022-07-14)


### Features

* **k8s/helm-modules/traefik:** bump traefik chart to v10.24.0 and traefik to 2.8 ([481fc88](https://github.com/ds-onyx-shark/terraform-modules/commits/481fc88cc17acb31d7b6d86d970b378dc618b8c3))
* **k8s/helm-modules/traefik:** remove deprecated traefik pilot ([72ed960](https://github.com/ds-onyx-shark/terraform-modules/commits/72ed9603098286e1cd218081b5e82d1dbe06c979))

## [1.42.2](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.42.1...v1.42.2) (2022-07-13)


### Refactor

* **k8s/helm-modules/traefik:** rename dashboard related variables ([0cf582a](https://github.com/ds-onyx-shark/terraform-modules/commits/0cf582a188d39bc8f4a150b6e1e2b3a9a4de2a56))

## [1.42.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.42.0...v1.42.1) (2022-07-13)


### Bug Fixes

* **.releaserc:** fix conventional commits config ([f0a86ca](https://github.com/ds-onyx-shark/terraform-modules/commits/f0a86ca2aa2940bdfd2b66eac0eb25de4fc599f6))

## [1.42.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.41.3...v1.42.0) (2022-07-13)


### Features

* **.releaserc:** add conventional commits ([8d9d96b](https://github.com/ds-onyx-shark/terraform-modules/commit/8d9d96b2bf8a1c3f45d52b720dc444403173e3d9))

## [1.41.3](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.41.2...v1.41.3) (2022-07-13)

## [1.41.2](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.41.1...v1.41.2) (2022-07-13)

## [1.41.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.41.0...v1.41.1) (2022-07-13)

# [1.41.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.40.0...v1.41.0) (2022-07-13)


### Features

* **k8s/helm-modules/secret-store-csi-driver:** add secret-store-csi-driver addon ([af7c44e](https://github.com/ds-onyx-shark/terraform-modules/commits/af7c44ec07cfe7da42a66af108269a2b7481cac7))

# [1.40.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.39.0...v1.40.0) (2022-07-13)


### Features

* **aws/eks/cluster:** bump external-dns addon ([a11bf1a](https://github.com/ds-onyx-shark/terraform-modules/commits/a11bf1abd77584998182b8bdfef5f1c934a10b7f))
* **aws/eks/cluster:** bump traefik addon ([8c9747d](https://github.com/ds-onyx-shark/terraform-modules/commits/8c9747ddf121316c8bd52cdb660833154cde6a6b))

# [1.39.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.38.2...v1.39.0) (2022-07-13)


### Features

* **k8s/helm-modules/external-dns:** bump chart version and remove todo comment ([2d66249](https://github.com/ds-onyx-shark/terraform-modules/commits/2d66249eafb3ba8e0bd32c598eebac7a310325aa))

## [1.38.2](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.38.1...v1.38.2) (2022-07-12)


### Bug Fixes

* **vsphere/k8s/rke/nodes:** fix variable type ([617e514](https://github.com/ds-onyx-shark/terraform-modules/commits/617e514899328e30824cfd620465545a2cae4056))

## [1.38.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.38.0...v1.38.1) (2022-07-12)


### Bug Fixes

* **k8s/helm-modules/traefik:** remove unused variables ([e316ac1](https://github.com/ds-onyx-shark/terraform-modules/commits/e316ac15554e774663be2d6d5e9f74efb0173379))

# [1.38.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.37.2...v1.38.0) (2022-07-12)


### Features

* **k8s/helm-modules/traefik:** add entrypoint map as a variable ([899c4c9](https://github.com/ds-onyx-shark/terraform-modules/commits/899c4c926cdd660d709a98180fd42915ac8744af))

## [1.37.2](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.37.1...v1.37.2) (2022-07-12)


### Bug Fixes

* **vsphere/k8s/rke/nodes:** fix variable type ([875a553](https://github.com/ds-onyx-shark/terraform-modules/commits/875a553205ebe09ae812e8dd20715375e8410135))

## [1.37.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.37.0...v1.37.1) (2022-07-12)


### Bug Fixes

* **vsphere/k8s/rke/nodes:** fix default variable ([4d7747e](https://github.com/ds-onyx-shark/terraform-modules/commits/4d7747e96351b39e377787deae6c822c89d26710))

# [1.37.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.36.0...v1.37.0) (2022-07-12)


### Features

* **vsphere/k8s/rke/nodes:** Add module for creating RKE nodes ([66a8a6c](https://github.com/ds-onyx-shark/terraform-modules/commits/66a8a6cb11c62d4c7af4882a995a2272b25efbba))

# [1.36.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.35.0...v1.36.0) (2022-07-08)


### Features

* **aws/eks/cluster:** bump vault module ([4979731](https://github.com/ds-onyx-shark/terraform-modules/commits/4979731bc398f7f73ab5bf4a6d32a1915f718d6c))

# [1.35.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.34.0...v1.35.0) (2022-07-08)


### Features

* **k8s/helm-modules/vault:** bump auth_backend module ([4c5c7a7](https://github.com/ds-onyx-shark/terraform-modules/commits/4c5c7a73f90ab5b74056ef6bdae1b4d47c88f88e))

# [1.34.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.33.0...v1.34.0) (2022-07-08)


### Features

* **vault/auth-backend/k8s:** enable iss validation ([08be245](https://github.com/ds-onyx-shark/terraform-modules/commits/08be2456a51370068c65c372fa669aafb81cd43f))

# [1.33.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.32.0...v1.33.0) (2022-07-07)


### Features

* **aws/eks/cluster:** bump traefik addon to v1.32.0 ([6c30f8d](https://github.com/ds-onyx-shark/terraform-modules/commits/6c30f8d3b0144146d1b454ebffc1641dae0fc334))

# [1.32.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.31.1...v1.32.0) (2022-07-07)


### Features

* **k8s/helm-modules/traefik:** enable cross namespace resource sharing ([8e84d52](https://github.com/ds-onyx-shark/terraform-modules/commits/8e84d5210a18a81e583751d494ff31768f6099b0))

## [1.31.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.31.0...v1.31.1) (2022-07-06)


### Bug Fixes

* **aws/mq:** wrong domain name ([6fb5e04](https://github.com/ds-onyx-shark/terraform-modules/commits/6fb5e04a9bc499cdc7db6309beeac7b64ef955bc))

# [1.31.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.30.1...v1.31.0) (2022-07-06)


### Features

* **vault/data/ip-list:** Added ip-list module to access generic safe ip lists ([61992a2](https://github.com/ds-onyx-shark/terraform-modules/commits/61992a2ef6159a1d45a245bd24f3f5d49f6395f8))

## [1.30.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.30.0...v1.30.1) (2022-07-06)


### Bug Fixes

* **aws/mq:** rename variables and replace remote state with data source ([cf31b9e](https://github.com/ds-onyx-shark/terraform-modules/commits/cf31b9e54f4311fd207c8d23f31ef8a646b17a97))

# [1.30.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.29.1...v1.30.0) (2022-07-06)


### Features

* **aws/route53:** add route53:ListTagsForResource permissions ([da4c82f](https://github.com/ds-onyx-shark/terraform-modules/commits/da4c82f84879a032cf88b2de235418b18a4d46f8))

## [1.29.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.29.0...v1.29.1) (2022-07-04)


### Bug Fixes

* **aws/route53:** Fix dumb mistake in vault policy naming. ([4c50898](https://github.com/ds-onyx-shark/terraform-modules/commits/4c50898b3c492a937fb947854e2d3ea87ee00136))

# [1.29.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.28.0...v1.29.0) (2022-06-29)


### Features

* **aws/mq:** Added module for creating Amazon MQ resources tailored for DS infrastructure ([a46eb4a](https://github.com/ds-onyx-shark/terraform-modules/commits/a46eb4a35f59b4f2ffcdab43ec630aacc44d59fd))

# [1.28.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.27.2...v1.28.0) (2022-06-28)


### Features

* **aws/acm:** Added module for ACM certificate management ([deb939e](https://github.com/ds-onyx-shark/terraform-modules/commits/deb939ef61dad05e4a575dfb2196c49cf5a9665e))

## [1.27.2](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.27.1...v1.27.2) (2022-06-27)


### Bug Fixes

* **aws/route53:** Add missing policy to vault manage-route53 policy ([fd79afe](https://github.com/ds-onyx-shark/terraform-modules/commits/fd79afeba7a3b740044cfab5865dc2d0cda7d6c6))

## [1.27.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.27.0...v1.27.1) (2022-06-27)


### Bug Fixes

* **aws/route53:** Add missing vault aws secret backend outputs ([bd88792](https://github.com/ds-onyx-shark/terraform-modules/commits/bd887922adfbc82d59dc6e7a176ef31b897ae08d))

# [1.27.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.26.1...v1.27.0) (2022-06-24)


### Features

* **aws/eks/cluster:** bump addon versions and add new dependencies ([6c740b7](https://github.com/ds-onyx-shark/terraform-modules/commits/6c740b79858a338738412f4a64f1dfbb3263e91b))

## [1.26.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.26.0...v1.26.1) (2022-06-24)


### Bug Fixes

* **k8s/helm-modules/traefik:** add dependencies for custom resources ([8b8b14f](https://github.com/ds-onyx-shark/terraform-modules/commits/8b8b14fafe74851c09e8b4b24012f147e4472778))

# [1.26.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.25.0...v1.26.0) (2022-06-23)


### Features

* **k8s/helm-modules/velero:** add velero module ([7bce932](https://github.com/ds-onyx-shark/terraform-modules/commits/7bce932fe6fa742baeadc692ee63c4920d85c8b5))

# [1.25.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.24.0...v1.25.0) (2022-06-22)


### Bug Fixes

* **aws/eks/cluster:** fix traefik dependencies ([41929b9](https://github.com/ds-onyx-shark/terraform-modules/commits/41929b9c027c95c6b3d7da820fbcf40ab7a29c5a))


### Features

* **aws/eks/cluster:** switch to remote traefik module ([69dc124](https://github.com/ds-onyx-shark/terraform-modules/commits/69dc1241ba904f5c6cd111beab29a6ef16e442bb))

# [1.24.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.23.0...v1.24.0) (2022-06-22)


### Features

* **k8s/helm-modules/traefik:** move custom resources to local helm chart ([a0e6be3](https://github.com/ds-onyx-shark/terraform-modules/commits/a0e6be3e8fb9b392e3c454ef074bfa60e93caadf))

# [1.23.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.22.0...v1.23.0) (2022-06-22)


### Features

* **aws/eks/network:** add cross zone load balancing ([e7ef7b8](https://github.com/ds-onyx-shark/terraform-modules/commits/e7ef7b8fa210a13aaec5c67d4bed0ef50f16dfc3))

# [1.22.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.21.1...v1.22.0) (2022-06-03)


### Features

* **vsphere/k8s/coreos-vm:** Added k8s/rke optimized coreos vm module ([5892ea2](https://github.com/ds-onyx-shark/terraform-modules/commits/5892ea2e4637cffb07659499f790d35f4ad4f7bc))

## [1.21.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.21.0...v1.21.1) (2022-06-03)


### Bug Fixes

* **vsphere/vm:** Export dns a record + fix default variable ([fdd32b3](https://github.com/ds-onyx-shark/terraform-modules/commits/fdd32b34dee2b6cfcb5cf083bdf557f1002e3353))

# [1.21.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.20.0...v1.21.0) (2022-06-02)


### Features

* **vsphere/vm:** Add new generic VM module ([ad3e57a](https://github.com/ds-onyx-shark/terraform-modules/commits/ad3e57a1a3e5b3725ea46eb56bddb2f096b33f30))

# [1.20.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.19.3...v1.20.0) (2022-06-02)


### Features

* **vsphere/diskv2:** Add new disk module ([39504e4](https://github.com/ds-onyx-shark/terraform-modules/commits/39504e4da496ec3d5682d3e175706e941104d34a))

## [1.19.3](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.19.2...v1.19.3) (2022-06-01)


### Bug Fixes

* **aws/eks/cluster:** group coredns zones with the same dns server ([e46e1dd](https://github.com/ds-onyx-shark/terraform-modules/commits/e46e1ddeed4feb7cc297a567b6bcfcb197b558ef))
* **aws/eks/cluster:** move addon cluster issuers to shared variable ([e9b385b](https://github.com/ds-onyx-shark/terraform-modules/commits/e9b385b69267c963f789f155905ecc9acdadae6f))
* **aws/eks/cluster:** update traefik module to v1.19.1 ([812df6e](https://github.com/ds-onyx-shark/terraform-modules/commits/812df6ec449f1b73ad98dc975c8df4a4011a7452))

## [1.19.2](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.19.1...v1.19.2) (2022-05-31)


### Bug Fixes

* **vault/credential-sources/dns/dsservice.lokal:** Add zone to outputs ([fe46cf4](https://github.com/ds-onyx-shark/terraform-modules/commits/fe46cf41bab575fa0cf1b37da5ce13c8b899ea1c))

## [1.19.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.19.0...v1.19.1) (2022-05-31)


### Bug Fixes

* **k8s/helm-modules/traefik:** remove forced http to https redirect ([4781ccf](https://github.com/ds-onyx-shark/terraform-modules/commits/4781ccf1b761cb3dcbbbfc12d3a4a95bb2a11469))

# [1.19.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.18.2...v1.19.0) (2022-05-18)


### Features

* **k8s/helm-modules/datadog:** Added Datadog addon ([acf248e](https://github.com/ds-onyx-shark/terraform-modules/commits/acf248e74f91cf6ead5c21606050ae3f2a90afc2))

## [1.18.2](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.18.1...v1.18.2) (2022-05-17)


### Bug Fixes

* **coreos-snippets/os/k8s-docker.yaml:** use json-file log driver instead of journald. ([80ef809](https://github.com/ds-onyx-shark/terraform-modules/commits/80ef809d86891410454fa05ad4717672daa2b502))

## [1.18.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.18.0...v1.18.1) (2022-05-17)


### Bug Fixes

* **k8s/helm-modules/cilium:** Replace hostPort.enabled with kubeProxyReplacement=probe as the former had no effect. ([ef1cf84](https://github.com/ds-onyx-shark/terraform-modules/commits/ef1cf843939668a66429edc7cb11cd37c184534d))

# [1.18.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.17.0...v1.18.0) (2022-05-12)


### Features

* **aws/eks/cluster:** bump aws provider and velero module versions ([5e14a4d](https://github.com/ds-onyx-shark/terraform-modules/commits/5e14a4d2df72db49d833c1a43a40379dd73444ab))

# [1.17.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.16.0...v1.17.0) (2022-05-12)


### Bug Fixes

* **aws/eks/cluster:** use ingress variable in node group target group selector ([d7176ff](https://github.com/ds-onyx-shark/terraform-modules/commits/d7176ffcaec07936287a18a7c4d3fe8c579a1c4a))


### Features

* **aws/eks/cluster:** bump eks module version to v18.19.0 ([028f2cf](https://github.com/ds-onyx-shark/terraform-modules/commits/028f2cfbbd9123c14be911e5a299d3defaa56a50))
* **aws/eks/cluster:** move from local to shared traefik module ([301cfca](https://github.com/ds-onyx-shark/terraform-modules/commits/301cfca75e0ad30876a9aaf5d34cede6fcbcdccb))

# [1.16.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.15.0...v1.16.0) (2022-05-12)


### Features

* **k8s/helm-modules/traefik:** add traefik module ([8f1391a](https://github.com/ds-onyx-shark/terraform-modules/commits/8f1391a1568e7825b7a9ab5d9664fb3f37628765))

# [1.15.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.14.0...v1.15.0) (2022-05-11)


### Features

* **aws/eks/network:** add pre-provisioned eips to the nlb ([e65911d](https://github.com/ds-onyx-shark/terraform-modules/commits/e65911d8ac38d442db798ccb27014c15082443ad))

# [1.14.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.13.0...v1.14.0) (2022-05-11)


### Features

* **k8s/helm-modules/vault:** add vault module ([2b1db70](https://github.com/ds-onyx-shark/terraform-modules/commits/2b1db70399881d592d2e1065c62f123c5619c20c))

# [1.13.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.12.0...v1.13.0) (2022-05-11)


### Features

* **k8s/helm-modules/external-dns:** add external-dns module ([d658b76](https://github.com/ds-onyx-shark/terraform-modules/commits/d658b761656cf587aa08cadb9dbd6d50e7d900e3))

# [1.12.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.11.3...v1.12.0) (2022-05-11)


### Features

* **k8s/helm-modules/cert-manager:** add cert-manager module ([a318aae](https://github.com/ds-onyx-shark/terraform-modules/commits/a318aaec5a4d7a8f34f334d85de2bded7205da6c))

## [1.11.3](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.11.2...v1.11.3) (2022-05-11)


### Bug Fixes

* **aws/eks/cluster:** clean and fix route53 zones and records ([656df74](https://github.com/ds-onyx-shark/terraform-modules/commits/656df747506e139319839630a61e02dcdd9f6ffc))

## [1.11.2](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.11.1...v1.11.2) (2022-05-11)


### Bug Fixes

* **aws/route53:** fix vault and iam role ttl ([c58f1a2](https://github.com/ds-onyx-shark/terraform-modules/commits/c58f1a285aa3a0b35f8ea9bd292d77387f79e740))

## [1.11.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.11.0...v1.11.1) (2022-05-11)


### Bug Fixes

* **aws/linux-swarm/generic:** add itu ssh certs ([070619d](https://github.com/ds-onyx-shark/terraform-modules/commits/070619d3b8cee134dbcb6cfd660ac16bd6ba60af))

# [1.11.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.10.1...v1.11.0) (2022-05-11)


### Features

* **aws/route53:** rework route53 module to support vault ([5dc7567](https://github.com/ds-onyx-shark/terraform-modules/commits/5dc7567c9906e714a2602f22b10ad88ebf4ae16c))

## [1.10.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.10.0...v1.10.1) (2022-05-10)


### Bug Fixes

* **k8s/helm-modules/cilium:** enable hostport service support ([ff6b2ba](https://github.com/ds-onyx-shark/terraform-modules/commits/ff6b2ba6ae9214bedd3728cff1ea0876fee633c3))

# [1.10.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.9.0...v1.10.0) (2022-05-10)


### Features

* **aws/eks/cluster:** switch external-dns and cert-manager to vault injector ([f34884b](https://github.com/ds-onyx-shark/terraform-modules/commits/f34884bf751d4729efd892a50585e6f7c0321ed1))

# [1.9.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.8.0...v1.9.0) (2022-05-05)


### Features

* **k8s/helm-modules:** add cilium module ([6700e7f](https://github.com/ds-onyx-shark/terraform-modules/commits/6700e7f5d4a4733816486e4aab820cb6d3897e26))

# [1.8.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.7.0...v1.8.0) (2022-05-05)


### Features

* **k8s/helm-modules/cilium:** add default to egress_masquerade_interfaces ([fb620d8](https://github.com/ds-onyx-shark/terraform-modules/commits/fb620d8f7bf454d7c11df5af1e94b2a9c4f3f505))

# [1.7.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.6.2...v1.7.0) (2022-04-12)


### Features

* **aws/eks/cluster:** add secret-store-csi-driver addon ([9f75307](https://github.com/ds-onyx-shark/terraform-modules/commits/9f753070d3c1765442a754a32843cf9f9cc4bdab))
* **aws/eks/cluster:** add vault addon ([68180d9](https://github.com/ds-onyx-shark/terraform-modules/commits/68180d923edf6210d7e0d601fb5e36873fe11dde))

## [1.6.2](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.6.1...v1.6.2) (2022-04-08)


### Bug Fixes

* **vault/auth-backend/k8s:** add default value to optional variable ([969bbb9](https://github.com/ds-onyx-shark/terraform-modules/commits/969bbb917f173d74199c71342d764a2f9cd3ea41))

## [1.6.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.6.0...v1.6.1) (2022-04-05)


### Bug Fixes

* **rke:** pacman conditional ([36705ab](https://github.com/ds-onyx-shark/terraform-modules/commits/36705ab13267834d182f95293789ca4d43a908e3))

# [1.6.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.5.2...v1.6.0) (2022-04-04)


### Features

* **vault/auth-backend/k8s:** Added new module for per cluster k8s auth backends ([642d906](https://github.com/ds-onyx-shark/terraform-modules/commits/642d906087166c384424771c2350c4d90c30abc3))

## [1.5.2](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.5.1...v1.5.2) (2022-03-25)


### Bug Fixes

* **aws/eks/cluster:** fix ingress connections ([488129f](https://github.com/ds-onyx-shark/terraform-modules/commits/488129f63eb7d859c2d00b273cd2d0bb9df8d107))

## [1.5.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.5.0...v1.5.1) (2022-03-18)


### Bug Fixes

* **aws/route53:** fix output ([b750905](https://github.com/ds-onyx-shark/terraform-modules/commits/b750905bce8d541f77e84209a88dca53aa18dcf3))

# [1.5.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.4.0...v1.5.0) (2022-03-18)


### Features

* **aws/route53:** add route53 module ([ef3b332](https://github.com/ds-onyx-shark/terraform-modules/commits/ef3b332c1c1f7a0bf3f4814a69d10a25cb0c7da1))

# [1.4.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.3.0...v1.4.0) (2022-03-17)


### Features

* **vault/vault/credential-sources/dns/dsservice.lokal:** Added new credential source module for new dsservice.lokal zone ([ffc4af6](https://github.com/ds-onyx-shark/terraform-modules/commits/ffc4af6e176e4a863368ffdb10bd55bd4be40c6c))

# [1.3.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.2.0...v1.3.0) (2022-03-15)


### Features

* **vault/module:** Added default vault backend ([3ad4383](https://github.com/ds-onyx-shark/terraform-modules/commits/3ad438379dba2db9ebb5470735e73f6f46639dbb))

# [1.2.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.1.1...v1.2.0) (2022-03-07)


### Features

* **aws/eks:** add eks module ([9495380](https://github.com/ds-onyx-shark/terraform-modules/commits/9495380a327b0468c944476711be1d618262aab8))

## [1.1.1](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.1.0...v1.1.1) (2022-03-02)


### Bug Fixes

* **aws/terraform-s3-remote-state:** fix tagging ([64da4ea](https://github.com/ds-onyx-shark/terraform-modules/commits/64da4eae95f75bdb8bf1bbca3f6c5bb91764fd1f))
* **aws/terraform-s3-remote-state:** remove conflicting ACL and fix excryption algorithm ([16c198f](https://github.com/ds-onyx-shark/terraform-modules/commits/16c198f1090ab0316750418572ce6df0f5ed4573))

# [1.1.0](https://github.com/ds-onyx-shark/terraform-modules/compare/v1.0.0...v1.1.0) (2022-03-02)


### Features

* **aws/terraform-s3-remote-state:** add terraform-s3-remote-state module ([065a1b1](https://github.com/ds-onyx-shark/terraform-modules/commits/065a1b1c6115a982d76eaaedf369efeaf0a6fbb3))

# 1.0.0 (2022-02-16)


### Features

* **everything:** terraform fmt recursive ([b79fccf](https://github.com/ds-onyx-shark/terraform-modules/commits/b79fccf7c523d9a0d753291a8a894c5dd26dd5d6))