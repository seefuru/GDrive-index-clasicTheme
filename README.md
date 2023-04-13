# GDrive-index-clasicTheme

## Google Drive Directory Index
Combining the power of Cloudflare Workers and Google Drive will allow you to index you files on the browser on Cloudflare Workers.

![](https://i.imgur.com/lNeh3S3.png)

## Deployment  
1.Install `rclone` software locally  
2.Follow [https://rclone.org/drive/]( https://rclone.org/drive/) bind a drive  
3.Execute the command`rclone config file` to find the file `rclone.conf` path  
4.Open `rclone.conf`,find the configuration `root_folder_id` and `refresh_token`  
5.Download index.js in https://github.com/donwa/goindex and fill in root and refresh_token  
6.Deploy the code to [Cloudflare Workers](https://www.cloudflare.com/)
