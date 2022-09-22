# Interface-to-determine-Brewster-angle-for-different-cases
Assume a y-polarized uniform plane wave ( Ei, Hi) is incident at an angle of incidence theta(i) from medium 1 (&epsilon;r1, &mu;r1) on medium 2 (&epsilon;r2, &mu;r2) at x=0. Plot the instantaneous expressions of total fields E1(= Ei+ Er), H1(= Hi+ Hr), E2(=Et ),H2 (=Ht ) of the wave in media 1 and 2, respectively. Consider both parallel and perpendicular polarizations separately. Determine the Brewster angle for different cases. The parameter values will be provided from user-end. 

## Brief Information
- Taken a y-polarized uniform plane wave (Ei, Hi) is incident at an angle of incidence &theta;i from medium 1 (&epsilon;r1, &mu;r1) on medium 2 (&epsilon;r2, &mu;r2) at x=0.
- Considered both cases of Perpendicular Polarization and Parallel Polarization. 
- Made an app for plotting the instantaneous expressions of total fields E1 (=Ei + Er), H1 (= H1 + Hr), E2 (=Et), H2 (= Ht) of the wave in media 1 and 2, respectively.
- In the app, we can provide parameters values Ei0, &omega;, &theta;i, &epsilon;r1, &mu;r1, &epsilon;r2, &mu;r2 from user end. It contains buttons for plotting E1(Ei + Er), H1(Hi + Hr), E2(Er) and H2(Hr) for both the cases.
- It also has a feature to calculate Brewster Angle which is a angle at which incident EM wave has zero reflection coefficient for both Perpendicular and Parallel Polarization.

## Description
### CASE-1: Perpendicular Polarisation

![image](https://user-images.githubusercontent.com/67547281/191763938-22a6c0b0-84fa-4f24-98b7-6634b04b8e61.png)

In case of perpendicular polarization, the electric field is perpendicular to the plane of incidence and the magnetic field is parallel to the plane of incidence.
- For the above case, since the incident electric field, Ei is

>![image](https://user-images.githubusercontent.com/67547281/191764210-abbdd2d2-6cd6-4a8e-aa10-919998c01710.png)

- And the reflected electric field, Er is

>![image](https://user-images.githubusercontent.com/67547281/191765342-bc516556-2a63-40bd-ae22-49e855236794.png)

- Then the total electric field in medium 1, E1 will be Ei+Er

>![image](https://user-images.githubusercontent.com/67547281/191765484-e2ff7e1f-def0-4177-b9e8-810f0cb08bd4.png)

- Similarly. since the incident magnetic field, Hi is

>![image](https://user-images.githubusercontent.com/67547281/191765712-cbd605ed-8782-40ef-a5fd-a7c09a47941e.png)

- And the reflected magnetic field, Hr is

>![image](https://user-images.githubusercontent.com/67547281/191765813-64425016-48d0-4b52-acbb-ecce41b34f63.png)

- Then the total magnetic field in medium 1, H1 will be Hi+Hr

>![image](https://user-images.githubusercontent.com/67547281/191765951-652bf54a-b366-4ad5-9a3c-0f0fc65e5fc6.png)

**Plotting E1 and H1 in GUI**

![image](https://user-images.githubusercontent.com/67547281/191766497-060b6830-8ae2-47a1-bdf4-1ed8559c20ad.png)


![image](https://user-images.githubusercontent.com/67547281/191766746-0b0e70f3-3b8b-438a-92fe-199802caed1e.png)

![image](https://user-images.githubusercontent.com/67547281/191766888-5771bd86-b636-4754-84dc-fa907f32479e.png)


- Now, in medium 2 the transmitted electric field, Et is
>![image](https://user-images.githubusercontent.com/67547281/191767178-d95649ba-0f87-4967-97d8-5125ca0182c1.png)
- Then the total electric field in medium 2, E2 will be (E2=Et)
>![image](https://user-images.githubusercontent.com/67547281/191767315-8d3b5aac-f850-4a5f-97ad-853889715e41.png)
- Similarly, the transmitted magnetic field, Ht is
>![image](https://user-images.githubusercontent.com/67547281/191767437-bcf97261-087a-4848-8475-e67c9ea9ab00.png)
- Then the total magnetic field in medium 2, H2 will be (H2=Ht)
>![image](https://user-images.githubusercontent.com/67547281/191767535-b0a0c57f-b90b-4c58-ae6c-9c9f272c1ccb.png)

**Plotting E2 and H2 in GUI**

![image](https://user-images.githubusercontent.com/67547281/191770496-3cfaa52a-d0bd-4f07-ba80-b59cc3a16ffb.png)






