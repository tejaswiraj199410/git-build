
pipeline{

agent any

stages {

stage ('git-checkout stage'){

steps{

echo "creating build from scm"

}

}
  stage ('build stage'){

steps{

echo "iam running shell command"
sh 'df -h'
}

}

stage ('this is third stage build'){

steps{

echo "this is a third stage build"
}
}
}

}
