pipeline
{
  agent any
  stages
  {
    stage ('git clone')
    { steps
          { sh ' echo downloading code'}
    }
  
    
    {
      stage ('code compile')
      { steps
            { sh ' echo compiling code'}
      }
    
      
      {
        stage ( 'code build')
        { steps
             { sh 'echo build generated'}
        }
      }
    }
  }
}
