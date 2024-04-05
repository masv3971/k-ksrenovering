# Schema

```mermaid
    gantt
        title Project Schedule
        dateFormat YYYY-MM-DD
        axisFormat %m/%d

        section Förberedelser
        Planera m. grävare : 2024-04-25, 1d
        Planera m. grus-farbror : 2024-04-25, 1d
        Planera m. betongare : 2024-04-25, 1d
        Planera m. container till rivning : 2024-04-25, 1d
        Planera m. hyra av maskvibbra : 2024-04-25, 1d
        Planera m. VVS : 2024-04-25, 1d
        Offerera material : 2024-04-25, 1d
        Beställa material : 2024-04-26, 10d

        section EL-central

        section Vardagsrum
        Panel : p, 2024-04-05, 5d
        Tak : t, after p, 2d
        Gips : g, after t, 2d
        Koppla in EL : el, after g, 1d

        section Spelrum
        Panel : p, 2024-04-15, 5d
        Tak : t, after p, 2d
        Gips : g, after t, 2d
        Koppla in EL : el, after g, 2d
        Bygga skjutdörr : door, after el, 2d

        section Växthus

        section Provisoriskt kök
        Flytta upp spis / kyl / micro : f, 2024-05-01, 1d
        Bygga hyllor : h, after f, 1d


        section Rivning av köket
        Container på plats : 2024-06-01, 1d
        Riva : 2024-06-01, 9d
        Container tillbaka : 2024-06-10, 1d
        Gräva ur grunden : 2024-06-10, 7d
        
        section Vatten
        Provisoriskt vatten/EL : 2024-06-17, 2d
        Gräva : 2024-06-19, 3d
        Anlägga vattenrör + isolera : 2024-06-21, 3d
        Ansluta vattenrör : 2024-06-24, 1d
        Anlägga EL/Fiber rör : 2024-06-25, 2d
        Ansluta EL : 2024-06-27, 1d
        Riva Provisoriskt vatten/EL :
        övertäckning : 2024-06-27, 1d

        section Gjuta platta
        Dra rör : 2024-07-01, 1d
        Grusa och vibrera : 2024-07-02, 3d
        Isolera : 2024-07-05, 3d
        Dra golvvärme : 2024-07-08, 2d
        Armera : 2024-07-10, 2d
        Gjuta : 2024-07-12, 1d


        section Utflykter
        Stockholm : 2024-04-19, 2d
        E & V besök : 2024-04-26, 3d
        GBG E : 2024-05-04, 1d
        Subkultfestivalen : 2024-06-28, 3d



```