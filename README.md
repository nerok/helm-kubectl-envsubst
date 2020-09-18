# helm-kubectl-envsubst
This docker image adds the gettext library which includes the envsubst command.
The envsubst command is a tool allowing templating using environment variables. `envsubst < file.ext.tmpl > file.ext`, where any environment variables on either `${variable}` or `$variable` format will be substituted.

For details about the gettext library, see https://www.gnu.org/software/gettext/.