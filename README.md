# Image Resizer Lambda

This Lambda will be invoked when a file is uploaded to a particular bucket. It will fetch the file that was added, resize it, and store the output in a different bucket.

## Run Locally

Clone the project

```bash
  git clone https://github.com/OneLightWebDev/image-resizer-lambda.git
```

Install Dependencies

```bash
# Required options if on mac
npm install --arch=x64 --platform=linux --target=16x sharp
```

Update Constants

```bash
npm install --arch=x64 --platform=linux --target=16x sharp
```

Deployment

```bash
npm run package
```

Running the command above will zip your source code and dependencies. The zip can then be uploaded to your Lambda.
