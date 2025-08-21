# demo_repo
demo_repo
# we are creating samall terraform code

Main.tf
provider "aws" {
region = " "
}
main.tf
   resource"aws_instance" "firstcode" {
      ami             = ""
      instance_type   = ""
      count           = 3
      tags = {
          Name = element${var.name,count_index}
          }
    }
variable.tf
   variable "name" {
   }
  terraform.tfvar
  name = [ "thiru", "arvind", "sunitha" ]
  
     
          
      
