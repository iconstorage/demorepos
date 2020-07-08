node {          
        stage "Publish"
        stage "nutanix calm"
        step([$class: 'BlueprintLaunch', appProfileName: 'Default', applicationName: '_${BUILD_ID}', blueprintDescription: 'Description is empty', blueprintName: '02_cicd_mongo', projectName: 'TestApp', runtimeVariables: '''{
    "yourname": "testdb1"
}''', waitForSuccessFulLaunch: true])
}
