---
title : "Tạo EC2 Security Group"
date :  "`r Sys.Date()`" 
weight : 2
chapter : false
pre : " <b> 2.2. </b> "
---


#### Tạo EC2 security group bằng  giao diện AWS console:  
1. Truy cập giao diện [EC2 console](https://us-east-1.console.aws.amazon.com/ec2/home?region=us-east-1#Home:).
2. Chọn **Security Groups**.
3. Chọn **Create Security Group**.

    ![Create EC2 SG](/images/preparation/2/1.png)

4. Tại mục **VPC**, chọn VPC bạn muốn tạo security group.
5. Tại mục **Security group name**, nhập tên cho security group.
6. Tại mục **Description**, nhập mô tả cho security group.

    ![Create EC2 SG](/images/preparation/2/2.png)

7. Cấu hình Inbound Rule

    ![Create EC2 SG](/images/preparation/2/3.png)

8. Cấu hình Outbound Rule

    ![Create EC2 SG](/images/preparation/2/4.png)

9. Click **Create**.

    ![Create EC2 SG](/images/preparation/2/5.png)

***Bạn đã tạo thành công security group cho EC2 instance.***