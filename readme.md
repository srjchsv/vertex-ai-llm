### Using Vertex AI LLM in jupyter notebook

To run this notebook you got to have:

- on the GCP

  - created project
  - created service account
  - set a role for the service account: 'Vertex AI Service Agent" for example
  - create new key with credentials in .json format

- create a .env file in root directory of this repo with GOOGLE_APPLICATION_CREDENTIALS variable that will hold path to service account .json credentials.
