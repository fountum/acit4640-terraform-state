# terraform-s3-backend-lab

1. When is the state file created?
- After run `terraform apply`
3. When is the lock file present?
- After run `terraform plan`
4. Is the lock file always in the bucket after it is created?
- No, its only created when you are modifying the state (terraform plan, terraform apply, terraform destroy, etc.).
5. Take a screenshot that shows the state file only.
  <img width="1343" height="407" alt="image" src="https://github.com/user-attachments/assets/15a6c93b-5a76-4751-b503-34e5eae6162d" />
6. Take a screenshot that shows the lock file and the state file.
 <img width="1361" height="494" alt="image" src="https://github.com/user-attachments/assets/5ab8e6b0-5489-4b22-92c8-00462bc52852" />



