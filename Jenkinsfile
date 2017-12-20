node('master') {
  
   stage 'Git Checkout'
     git 'https://github.com/nadnoops/spring-petclinic.git'
         echo 'checkout done'

   stage('Maven Build'){
      echo 'Maven Project Compile'
     maven 'clean install'
   }
}
