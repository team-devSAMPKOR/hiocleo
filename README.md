#HI0 CLEO 2016
TODO : HI0 CLEO 2016 STRUCTURE<br><br>
<p>
intro<br>
    <br>
    main 1 ~ main 21<br>
    <br>
        총알 1발증가     giveOneAmmo      120 122<br>        
        무한 총알ON/OFF	 muhanAmmo        8 187<br>
                         muhanAmmoON<br>
                         muhanAmmoOFF<br>
        <br>
        무기삭제	     deleteWeapon     120 123<br>
        <br>
        체력증가 5	     healthUp         122 187<br>
        체력감소 5  	 healthDown       122 189<br>
        아머증가 5	     armourUp         123 187<br>
        아머감소 5 	     armourDown       123 189<br>
        <br>
        몸체타격무효화	 bodyMujuk        2 70<br>
                         bodyMujuk_LOOP<br>
                         bodyMujuk_LOOP_CLOSE<br>
        <br> 
        차내구증가 50    carHealthUp      120 187<br>
        차내구감소 50	 carHealthDown    120 189<br>
        차외형수리       carPartsRepair   120 121 <br>
        <br>
        차뒤집힘방지 	 antiCarTurn(재귀) 90 88<br>
        <br>
        무한니트로	     clickNitro      car in LMB<br>
                         clickNitro_Shoot<br>
                         clickNitro_Shoot_CLOSE<br>
        <br>
        파워피트무적	 powerPit        car in RMB<br>
                         clickNitro_LOOP<br>
                         clickNitro_LOOP_CLOSE<br>
                         <br>
        드리프트제어	 driftControl(재귀) car in 16<br>
         <br>
        맵핵ON/OFF	     mapHack         8 221<br>
                	     mapHackON<br>
                	     mapHackOFF<br>
        <br>
        애님스왓ON/OFF   showAnimSwat    186 222<br>
                         showAnimSwatON<br>
                         showAnimSwatOFF<br>
                         <br>
        빠른달리기       fastRun         81 87 69<br>
        <br>
        나이트고글       nightGoggle     221 220 (delete)<br>
        적외선고글       thermalGoggle   219 220 (delete)<br>
        <br>
        자살             setDead         46  220<br>
        <br>
        비행기선회앵글   airplaneAngle   32<br>
                         airplaneAngle_SETUP<br>
                         <br>
        무반동ON/OFF     mubanWeapon     8 187<br>
                         mubanWeaponON<br>
                         mubanWeaponOFF<br>
                         mubanWeaponONService<br>
                         mubanWeaponOFFService<br>
                         mubanWeaponServiceImpl
</p>
