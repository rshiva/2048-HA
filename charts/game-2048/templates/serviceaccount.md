# #sample serviceaccount to connect s3
# {{- if .Values.serviceAccount.enabled }}
# apiVersion: v1
# kind: ServiceAccount
# metadata:
#   name: {{ .Values.serviceAccount.name }}
#   namespace: {{ .Values.namespace.name }}
#   annotations:
#     eks.amazonaws.com/role-arn: {{ .Values.serviceAccount.roleArn }}
# {{- end }}
