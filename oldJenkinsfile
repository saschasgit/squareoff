node{
    openshift.withCluster('ARO_Cluster2'){
        openshift.verbose()
        stage('Build Image'){
            openshift.raw("start-build square-off-git -n atos-squareoff")
        }
    }
}
