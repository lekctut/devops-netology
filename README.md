Прогнорированы будут папки и файлы находящиеся в папке terraform:
скрытая папка .terraform,
все заканчичающие(формат) файлы .tfstate
все файлы содержащие .tfstate.
файл crash.log
файлы который начинается на crash. и заканчивающийся на .log
файлы формата .tfvars и .tfvars.json
Файлы override.tf и override.tf.json
все файлы заканчивающиеся на _override.tf и _override.tf.json
файлы .terraform.tfstate.lock.info .terraformrc terraform.rc