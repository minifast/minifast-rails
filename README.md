A Rails Application Template for use at Ministry of Velocity

Reference: [Rails Application Templates](https://guides.rubyonrails.org/rails_application_templates.html)

### Locally
```bash
rails new <myproject> --skip-test --skip-jbuilder -d postgresql -c tailwind -m ./template.rb
```

### Remotely
```bash
rails new <myproject> --skip-test --skip-jbuilder -d postgresql -c tailwind -m 'https://raw.githubusercontent.com/jparr/minifast-rails/main/template.rb'
```