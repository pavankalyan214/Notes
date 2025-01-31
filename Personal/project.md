![image](https://github.com/user-attachments/assets/ea95664c-a46a-4640-99da-0e00ab141920)

Any Model developed on DataScience on-line or offline will be there in Modelfabric 

![image](https://github.com/user-attachments/assets/e44c0124-28a4-4d82-ac01-377f4615eb35)

![image](https://github.com/user-attachments/assets/b393c3cb-711f-46d5-98c1-1d7bd8e0c149)

![image](https://github.com/user-attachments/assets/5102edbe-15e4-471f-ae51-737691c136bd)

We build Modelfabrice to mimic this Process

![image](https://github.com/user-attachments/assets/2b2fbb45-78cb-4aa6-b787-f7440fb86bbf)

Supervised --> we know the output --> also called blackbox
Unsuperviced --> don’t know the output
Reinforcement --> 
![image](https://github.com/user-attachments/assets/be2f76c0-4088-4ffb-830c-15f1c4ed144e)

![image](https://github.com/user-attachments/assets/ce67cb5b-360a-481a-9991-8d368c1936f8)

Genix can hold Sctucture and Un-Structed data it will reduce the 

![image](https://github.com/user-attachments/assets/ece0aea1-ec60-4e78-8a00-2d6b7f786554)

System Anamoly detection --> it will help for any anomaly 
We will Develop a model and attach it to Anomaly so it can identify any anomaly

Any Marine ship has 3 propulsion system 
1.Starboard side 
2.Center side 
3.Port side 

We got the data where port side Propulsion system is malfunctioned we got 3 months data the data Include 
1.Ashi corp propulsion motor
2.Motor torque
3.Speed
	4. 6winding temp{w1 to w6}
	5. Cooling inlet temp
	6. Cooling outlet temp

These 11 tags

![image](https://github.com/user-attachments/assets/e83a1510-7af2-4a6f-aa57-cf3eade3a35e)



The healthy data available we wil train modle and we will apply port size data to detect the failure cause 

![image](https://github.com/user-attachments/assets/3d86c5a3-158e-465e-88e3-732552679b38)

![image](https://github.com/user-attachments/assets/43e01f3c-ff85-4698-9cd1-d2c07ec4ca53)

![image](https://github.com/user-attachments/assets/50a0c1bd-4920-4034-a74e-f53900991514)


But on port side 23rd march we can see failure 
The motor winding burnt due to high heat 
Her are we are using ModelBased Fault diagnosis to give end use and alert or info before making it shut down 

![image](https://github.com/user-attachments/assets/4e94068a-a9aa-4862-a1cf-8e34267a2b9e)

With healthy data we will find out the winding temp of all 6 winding temps , with fault one we will find out the difference so the fault can be identified the divergence we can give alert.

![image](https://github.com/user-attachments/assets/f55ece6d-4035-49e8-9362-efbebebec095)

![image](https://github.com/user-attachments/assets/638b86e1-c183-46c2-b6e0-ff2f665f8298)

![image](https://github.com/user-attachments/assets/6bf6a19d-f448-482f-895b-763b319a01c1)

![image](https://github.com/user-attachments/assets/8d1ade76-e65e-40d0-8f4f-5fe3e88d8949)

![image](https://github.com/user-attachments/assets/d98e9ae0-081b-4f61-a200-73c1fb004550)

![image](https://github.com/user-attachments/assets/16797eb6-2030-4739-8f1b-86b1f9a8bce4)

![image](https://github.com/user-attachments/assets/7c68bf5e-fe02-416e-93ed-261f8391463b)

![image](https://github.com/user-attachments/assets/4f5d4319-597c-4c0e-92ab-f91623c1c871)

We can find the temperature and power torque

Small increase in power we can see speed also increasing and so as torque which is represented in blue line 

Temp also increaing  the power increase the rate of speed generated also increase 

There is a cooling system to cool or control winding temp

![image](https://github.com/user-attachments/assets/65cf2d59-0f66-4027-8751-6a4837caa90c)

![image](https://github.com/user-attachments/assets/5828bf53-0a84-48a1-b236-53b7905942aa)

![image](https://github.com/user-attachments/assets/48f30f58-a983-48cf-b062-602b34d2a016)

![image](https://github.com/user-attachments/assets/f77b206e-e9d3-4972-8c87-ee04433a4636)

Before resampling 

![image](https://github.com/user-attachments/assets/b20d42ef-ad63-4fa3-b760-389b8bcdb54a)

The data set we have is acent cernecent formate meaning all the tags are sampled uniformly and the fist step is sample uniformly and aggregate them 

Below is the graph which is showing data before and after resampling the data, which will show us how we sampled the data set

![image](https://github.com/user-attachments/assets/17b7f888-df14-4cf5-be72-23292a472b6c)

![image](https://github.com/user-attachments/assets/4cc54fbd-3649-4f49-94ee-64e8284c676d)

![image](https://github.com/user-attachments/assets/eaea7096-60ed-4479-9375-4226eb13e1b4)


Method used is reareast non-zero value  include missing values and alos padding some noise to the system do we don’t have single value we have dynamics to be introduced

![image](https://github.com/user-attachments/assets/43dc9146-9aae-4101-90c8-501500d3c011)

![image](https://github.com/user-attachments/assets/01b104d3-23a5-41eb-a6c4-dae294be365f)

![image](https://github.com/user-attachments/assets/4e1d7f15-2fe1-41d9-957f-0fda8d6b91a7)

![image](https://github.com/user-attachments/assets/1e0c5684-bdbc-4dbb-a40a-0dd580445bfa)

![image](https://github.com/user-attachments/assets/6b661bd0-b126-4f4a-a21c-37ee9de3b17a)

![image](https://github.com/user-attachments/assets/256adb30-02af-4ac2-a39c-ec573e53bde6)

Residual is what is the true value and what is the value I generated since 

![image](https://github.com/user-attachments/assets/894a250b-68c6-447f-a5ae-fd8ff45f91c9)

![image](https://github.com/user-attachments/assets/98704aa0-00ff-4b7d-97f6-62dd28067973)

![image](https://github.com/user-attachments/assets/8f3ef68e-2c40-47f4-a286-4d440af6dd4f)

![image](https://github.com/user-attachments/assets/eb9004fb-9e16-4cef-b137-990ca9aa87ce)

![image](https://github.com/user-attachments/assets/fd8b3a76-c43f-403d-bc0c-6b9e7ccb62d6)

![image](https://github.com/user-attachments/assets/199feb6c-cabc-4b61-b7db-9f0708f811ed)

![image](https://github.com/user-attachments/assets/fc374a85-85d1-4d6e-bdb4-71f2305d7dc1)

![image](https://github.com/user-attachments/assets/2ff9ce53-149e-40b9-b13c-f02f2e1a77ac)


Cummelative sum algorithm 

![image](https://github.com/user-attachments/assets/756d0b8c-9c70-47b9-b24a-b9bd688d4556)

![image](https://github.com/user-attachments/assets/5bfa1e18-d26f-4a76-ab62-9b8b3960c56a)

![image](https://github.com/user-attachments/assets/82cf2e97-cc20-4060-bd93-0324223da7d3)

![image](https://github.com/user-attachments/assets/11d6aaf3-8ed2-48d7-8aec-d8cf829dc9df)


![image](https://github.com/user-attachments/assets/b1614f37-6e75-4097-b5c6-a0d921d572dd)


![image](https://github.com/user-attachments/assets/a5a84b07-a96b-4bfa-beba-79ba0a16971c)


![image](https://github.com/user-attachments/assets/0f402cb6-2638-4acd-9db0-5353b597cc50)



Model based fault detection algorithm 

![image](https://github.com/user-attachments/assets/9d9c7278-0ba3-4954-b417-a4d94ebed024)


![image](https://github.com/user-attachments/assets/4566ee12-6a24-4420-a810-31746e4ef4b2)

![image](https://github.com/user-attachments/assets/2686a3bc-fb2e-46f4-bb28-655a27dfb18a)

![image](https://github.com/user-attachments/assets/c51bf436-a8c5-4fab-bca8-94d12839ee12)

![image](https://github.com/user-attachments/assets/56a028f2-963e-47d6-b6eb-da07141eb1d7)

![image](https://github.com/user-attachments/assets/7bd2fd9a-87a4-46f9-92ee-7fee89c508e5)

![image](https://github.com/user-attachments/assets/36b948f1-749d-4121-b458-e4b58ad80054)

![image](https://github.com/user-attachments/assets/e44a9530-4b28-4d8b-9d7b-2555b073dc33)

![image](https://github.com/user-attachments/assets/9d827250-62df-4dfb-8e2f-b65cb37fe621)

![image](https://github.com/user-attachments/assets/d2a13b99-547c-4f57-8673-e9a4f734bcba)

![image](https://github.com/user-attachments/assets/608c90d4-d717-41b2-81a5-61e851b43efd)

