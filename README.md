# COVID-19-Modelling

## Objective :  <br/>

To access the impact of lockdown on the number of active cases in the state of Karnataka. <br/>

## Abstract: <br/>

>- Have you ever wondered why did goverment impose lockdowns during the pandamic ?   <br/>
>- How can it imapct the number of active cases ?  <br/>
>- When the goverment should lift the lockdown off ?   <br/>
>- What is the impact of imposing a particular lockdown strategy ?  <br/>
(for example each Tuesday goverment officials will update the lockdown restriction based on the 
average number of active number last week)  <br/>
>- How does vaccination can impact the number of cases ? <br/>

## Note:

>- Here beta refers to the contact ratio. <br/>
>- day=0 corresponds to March 16th.(starting date for simulation) <br/>
>- The hence each date get a corresponding number.*For example day=42 corresponds to April 26th.* <br/>

## Assumptions:

1. The population is time-invariant. <br/>
2. This analysis is done with respct to the State of Karnataka.  <br/>

## Results obtained:

### How the number of cases will evolve till Dec 31st under the followng lockdown strategy <br/>

  under : The government continue to use the strategy which was used from March 16 th to April 26  <br/>
  
  ![Cases_with_beta_C1](https://user-images.githubusercontent.com/113635391/197468571-9aceca0b-f937-41a1-b485-f050319f3c8a.png)

 
  under : The government deployed (2/3) rd restriction with respect to the restriction which was used from March 16 th to April 26 <br />
  
  ![Cases_with_beta_C2](https://user-images.githubusercontent.com/113635391/197468610-83d26bb6-4c85-435f-bce0-5922f35ab1e9.png)

  under : The government deployed (1/2) rd restriction with respect to the restriction which was used from March 16 th to April 26 <br />
  
  ![Cases_with_beta_C3](https://user-images.githubusercontent.com/113635391/197468649-a87fab2e-0a3e-4775-bdfc-79a3037da8a7.png)

  
  under : The government deployed (1/3) rd restriction with respect to the restriction which was used from March 16 th to April 26 <br />
  
  
  ![Cases_with_beta_C4](https://user-images.githubusercontent.com/113635391/197468753-42e2a215-4792-4e47-97e4-038969a6710a.png)

  

### How the fraction of Susceptable people evolve till Dec 31st under the followng lockdown strategy <br/>

  under : The government continue to use the strategy which was used from March 16 th to April 26  <br/>
  
  ![Sus_with_beta_C1](https://user-images.githubusercontent.com/113635391/197468802-cd49f067-94d3-4c76-9c01-954b22d858d7.png)

 
  under : The government deployed (2/3) rd restriction with respect to the restriction which was used from March 16 th to April 26 <br />
  
  ![Sus_with_beta_C2](https://user-images.githubusercontent.com/113635391/197468850-11921142-ea0e-4a4b-b09a-605afeb2d836.png)

  
  
  under : The government deployed (1/2) rd restriction with respect to the restriction which was used from March 16 th to April 26 <br />
  ![Sus_with_beta_C3](https://user-images.githubusercontent.com/113635391/197468870-f67789f3-7c30-45fb-a832-75be94e7c8a9.png)

  
  
  under : The government deployed (1/3) rd restriction with respect to the restriction which was used from March 16 th to April 26 <br />
  
  ![Sus_with_beta_C4](https://user-images.githubusercontent.com/113635391/197468899-391efc77-0b27-43c6-9337-b0f446e89e96.png)

  

### How it is with respct to the original number of active cases till 19th Sept 2021 under the followng lockdown strategy  ? <br />
  (Data was only available till this date)
  
  under : The government continue to use the strategy which was used from March 16 th to April 26  <br/>
  
 ![Comparison_with_beta_C1](https://user-images.githubusercontent.com/113635391/197468948-d3019fb9-6286-4183-8b1d-1030d74afc0a.png)

  under : The government deployed (2/3) rd restriction with respect to the restriction which was used from March 16 th to April 26 <br />
  
  ![Comparison_with_beta_C2](https://user-images.githubusercontent.com/113635391/197469029-bd16ffa9-a994-4119-b657-683068547d87.png)

  
  under : The government deployed (1/2) rd restriction with respect to the restriction which was used from March 16 th to April 26 <br />
  
  ![Comparison_with_beta_C3](https://user-images.githubusercontent.com/113635391/197469048-e8d5aaa8-465e-4ed5-93a4-6b5ab5e46f03.png)

  
  under : The government deployed (1/3) rd restriction with respect to the restriction which was used from March 16 th to April 26 <br />
  ![Comparison_with_beta_C4](https://user-images.githubusercontent.com/113635391/197469096-c9e9b17a-4da5-4191-bd21-95b64bd740cb.png)

  
  
  

### What if the government had deployed the given feedback lockdown strategy ? <br/>
 (based on the number of active cases in the preceesding week) <br/>
 
<img width="433" alt="Screenshot 2022-10-24 at 12 59 11 PM" src="https://user-images.githubusercontent.com/113635391/197471196-daff626b-7470-4a30-a678-f463698ca8f4.png">

 
 4.1.  How the number of cases will evolve till Dec 31st <br/>
 
 ![Cases_with_closed_loop](https://user-images.githubusercontent.com/113635391/197469307-d7ba0d0d-df30-407e-b167-afbc6ea90956.png)

 
 
 4.2.  How the fraction of Susceptable people evolve till Dec 31st <br/>
 ![Sus_with_closed](https://user-images.githubusercontent.com/113635391/197469328-378ca2ff-e1e9-4483-a435-e2ac7a1416d4.png)

 
 
 
 


