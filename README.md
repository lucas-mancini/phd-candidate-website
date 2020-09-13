# PhD Candidate Website

Personal website for https://juliarubio.com.ar.

SSL certificate generated using [SSL For Free](https://manage.sslforfree.com/). You need to create both certificates for domains: juliarubio.com.ar and www.juliarubio.com.ar.

Update certificate every three months as per the steps here: https://medium.com/@channaly/how-to-host-static-website-with-https-using-amazon-s3-251434490c59.

Import the newly generated certificate into CloudFront's Certificate Manager, and finally, edit the CloudFront distribution to use the new certificate. If you need to just "renew" the certificate, go to AWS Certificates service, click on the certificate that is about to expire, and click "Renew" or "Reimport". 
