job('simpleTrigger') {
  parameters {
    stringParam('Object', 'Undescribed', 'This param describes an object type')
  }
  steps {
    shell('echo $JOB_NAME $BUILD_NUMBER')
    shell('echo $Object')
  }
  publishers {
    downstream('simpleJobWithParameter', 'SUCCESS')
  }
}
