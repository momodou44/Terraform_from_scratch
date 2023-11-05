# Terraform_from_scratch

Avant l’avènement de l’IaC, la gestion de l’infrastructure était généralement un processus manuel et chronophage. Les administrateurs système et les équipes opérationnelles devaient :

1. Configurer manuellement les serveurs : les serveurs et autres composants d'infrastructure étaient souvent installés et configurés manuellement, ce qui pouvait entraîner des incohérences et des erreurs.

2. Absence de contrôle de version : les configurations d'infrastructure n'étaient généralement pas contrôlées par version, ce qui rendait difficile le suivi des modifications ou le retour aux états précédents.

3. Documentation lourde : les organisations s'appuient fortement sur la documentation pour enregistrer les étapes et les configurations requises pour les différentes configurations d'infrastructure. Cette documentation pourrait devenir rapidement obsolète.

4. Automatisation limitée : l'automatisation se limitait aux scripts de base, manquant souvent de la robustesse et de la flexibilité offertes par les outils IaC modernes.

5. Provisionnement lent : le provisionnement de nouvelles ressources ou environnements était un processus long qui impliquait plusieurs étapes manuelles, entraînant des retards dans la livraison du projet.

6. IaC relève ces défis en proposant une approche systématique, automatisée et basée sur le code de la gestion de l'infrastructure. Les outils IaC populaires incluent Terraform, AWS CloudFormation, les modèles Azure Resource Manager et autres.

7. Ces outils permettent aux organisations de définir, déployer et gérer leur infrastructure de manière efficace et cohérente, facilitant ainsi leur adaptation aux besoins dynamiques des applications et services modernes.

###Pourquoi Terraform ?
Il existe plusieurs raisons pour lesquelles Terraform est utilisé par rapport aux autres outils IaC, mais voici les principales raisons.

- Prise en charge multi-cloud : Terraform est connu pour sa prise en charge multi-cloud. Il vous permet de définir une infrastructure indépendante du cloud, ce qui signifie que vous pouvez utiliser le même code de configuration pour provisionner des ressources sur différents fournisseurs de cloud (AWS, Azure, Google Cloud, etc.) et même une infrastructure sur site. Cette flexibilité peut être bénéfique si votre organisation utilise plusieurs fournisseurs de cloud ou envisage de migrer entre eux.

- Grand écosystème : Terraform dispose d'un vaste écosystème de fournisseurs et de modules apportés à la fois par HashiCorp (la société derrière Terraform) et par la communauté. Cela signifie que vous pouvez trouver des modules et des configurations prédéfinis pour une large gamme de services et de composants d'infrastructure, ce qui vous permet d'économiser du temps et des efforts dans l'écriture de configurations personnalisées.

- Syntaxe déclarative : Terraform utilise une syntaxe déclarative, vous permettant de spécifier l'état final souhaité de votre infrastructure. Cela facilite la compréhension et la maintenance de votre code par rapport aux langages de script impératifs.

- Gestion de l'état : Terraform maintient un fichier d'état qui suit l'état actuel de votre infrastructure. Ce fichier d'état aide Terraform à comprendre les différences entre les états souhaités et réels de votre infrastructure, lui permettant ainsi de prendre des décisions éclairées lorsque vous appliquez des modifications.

- Planifier et appliquer : le workflow « planifier » et « appliquer » de Terraform vous permet de prévisualiser les modifications avant de les appliquer. Cela permet d'éviter des modifications inattendues de votre infrastructure et offre la possibilité d'examiner et d'approuver les modifications avant leur mise en œuvre.

- Support communautaire : Terraform dispose d'une communauté d'utilisateurs vaste et active, ce qui signifie que vous pouvez trouver des réponses aux questions courantes, des conseils de dépannage et une multitude de documentation et de didacticiels en ligne.

- Intégration avec d'autres outils : Terraform peut être intégré à d'autres outils DevOps et d'automatisation, tels que Docker, Kubernetes, Ansible et Jenkins, vous permettant de créer des pipelines d'automatisation complets.

- Langage HCL : Terraform utilise le langage de configuration HashiCorp (HCL), spécialement conçu pour définir l'infrastructure. Il est lisible par l'homme et expressif, ce qui facilite le travail des développeurs et des opérateurs.
