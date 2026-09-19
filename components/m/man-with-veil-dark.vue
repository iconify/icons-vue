<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i1NRwre)"><path fill="url(#i8J3eXk)" class="w0lgbgbhh"/><path fill="url(#izYK5Hc)" class="w0lgbgbhh"/><path fill="url(#i3rodPc)" class="w0lgbgbhh"/></g><g filter="url(#ikLLxOc)"><path fill="url(#iRujXJe)" class="h-5x17bxj"/></g><path fill="url(#iJf1iUb)" class="shep8_bdh"/><path fill="url(#i2qypic)" class="shep8_bdh"/><path fill="url(#i8qGVjb)" class="shep8_bdh"/><path fill="url(#i3dimgb)" class="shep8_bdh"/><g filter="url(#iqoJTCd)"><path class="lux6k2ifl"/></g><g filter="url(#ij6S8lb)"><path class="o7b0b7x3a"/></g><g filter="url(#inLBtfb)"><path fill="url(#io4gIPe)" class="ix_9o_9wu"/><path fill="url(#iqMD7gd)" class="ix_9o_9wu"/><path fill="url(#isjlhEd)" class="ix_9o_9wu"/></g><g filter="url(#iVLDuze)"><path fill="url(#i5TF0qb)" class="hzq3o_buh"/><path fill="url(#iNWzONb)" class="hzq3o_buh"/><path fill="url(#iA1fBab)" class="hzq3o_buh"/></g><g filter="url(#iq0TIBb)"><path fill="url(#iIEcKAK)" class="dw40nqbxs"/><path fill="url(#ia50H6B)" class="dw40nqbxs"/><path fill="url(#iCWD9Hz)" class="dw40nqbxs"/><path fill="url(#ik6Kw6b)" class="dw40nqbxs"/></g><path fill="url(#ifau3jC)" class="o2j9ljphc"/><path fill="url(#iZ9f8ke)" class="o2j9ljphc"/><g filter="url(#inC87My)"><path class="dz5hgfbwb"/></g><g filter="url(#ilKNRxc)"><path fill="url(#isd35Ge)" class="k13ak_bzi"/><path fill="url(#iiLdS3c)" class="k13ak_bzi"/></g><g filter="url(#iusVGOs)"><path fill="url(#iFLhSvc)" class="ylqxkab7o"/><path fill="url(#iplo2Cc)" class="ylqxkab7o"/></g><circle fill="url(#ioJN0Qd)" class="j-elh2uvv"/><circle fill="url(#ijowZ1b)" class="j-elh2uvv"/><circle fill="url(#iAAvyQb)" transform="matrix(-1 0 0 1 22.919 20.426)" class="movji7bnz"/><circle fill="url(#iH86wby)" transform="matrix(-1 0 0 1 22.919 20.426)" class="movji7bnz"/><circle fill="url(#ifbe9cT)" class="brgj7qtnd"/><circle fill="url(#izM6NXd)" transform="matrix(-1 0 0 1 21.97 21.485)" class="movji7bnz"/><circle fill="url(#iGbM8pb)" transform="matrix(-1 0 0 1 21.97 21.485)" class="movji7bnz"/><path fill="url(#i2LQlsd)" class="ccrydivzf"/><g filter="url(#iJauvme)"><path class="hej-omb_k"/><path fill="url(#icPrSEd)" class="ntrmoswfw"/><path fill="url(#iNUb3Pc)" class="ntrmoswfw"/><path fill="url(#iRJHFee)" class="ntrmoswfw"/><path fill="url(#iptGC2c)" class="ntrmoswfw"/><path fill="url(#isTDdze)" class="ntrmoswfw"/></g><path fill="url(#ibyJhIe)" class="kcwstyspx"/><g filter="url(#ioZ3q3e)"><path class="tpcvtjbvk"/><path fill="url(#iYuu2Rd)" class="o110mgbff"/><path fill="url(#iglME4c)" class="o110mgbff"/></g><g filter="url(#ijhNAhc)"><path class="fo-imacds"/><path fill="url(#i84ZkMb)" class="f5jafwbws"/><path fill="url(#iBTolRe)" class="f5jafwbws"/><path fill="url(#iqD660c)" class="f5jafwbws"/><path fill="url(#iVpU4dr)" class="f5jafwbws"/><path fill="url(#iTMsRuF)" class="f5jafwbws"/></g><g filter="url(#iR3VtOd)"><path fill="url(#in15rgd)" clip-rule="evenodd" class="yjp69hbuv"/></g><g filter="url(#inHW3cc)"><path class="i4i_2ibui"/></g><g filter="url(#iFuvIqe)"><path fill="url(#iJ6OHFc)" class="rk5yg3y4a"/><path fill="url(#iBvwMLu)" class="rk5yg3y4a"/></g><g filter="url(#isnpTFe)"><path stroke="url(#ihsvHFe)" class="jtc6ijb6j"/></g><g filter="url(#iIsqmvd)"><path stroke="url(#izL61sC)" class="hbyh_lbnn"/></g><g filter="url(#i6sZdPb)"><path stroke="url(#iMFCApc)" class="wn7tf0b0a"/></g><g filter="url(#iJLWzBe)"><path stroke="url(#iP0FelY)" class="s9dopkbsv"/></g><g filter="url(#inX48Pc)"><circle fill="url(#ipmkRxe)" class="h2cywub0g"/></g><g filter="url(#iNnUKMb)"><circle fill="url(#iSgqXmb)" class="jekksk-xe"/></g><g filter="url(#iHzOQbd)"><circle fill="url(#iGN34Jt)" class="ji48w9x8q"/><circle fill="url(#iCU00ib)" class="ji48w9x8q"/></g><g filter="url(#iSD0a8c)"><circle class="w_teojfnp"/><circle fill="url(#i62k2eb)" class="whnrrccuq"/><circle fill="url(#ivXXGke)" class="whnrrccuq"/></g><g filter="url(#iS2flMp)"><path fill="url(#is09IBb)" class="r-_oyqohi"/><path fill="url(#iZqloBe)" class="r-_oyqohi"/><path fill="url(#iHzbGqb)" class="r-_oyqohi"/><path fill="url(#iC0sCSb)" class="r-_oyqohi"/><path fill="url(#iIK5Mkk)" class="r-_oyqohi"/><path fill="url(#icqe6Cc)" class="r-_oyqohi"/></g><g filter="url(#izu38Xr)"><path fill="url(#ieT7XOd)" class="tzg34ubeh"/></g><g filter="url(#iFXgqvc)"><path class="k_7yd74ov"/><path fill="url(#io32jGe)" class="oxi6re-fl"/><path fill="url(#iNI1BOc)" class="oxi6re-fl"/><path fill="url(#iy1HQOy)" class="oxi6re-fl"/><path fill="url(#iN9AxsU)" class="oxi6re-fl"/></g><g filter="url(#iqZRi8b)"><path class="pa5huib1d"/></g><g filter="url(#iU4buZv)"><path class="wiyv84b_o"/><path fill="url(#iBCxU1d)" class="z50uotcgt"/><path fill="url(#isA4ZFb)" class="z50uotcgt"/><path fill="url(#iVueKmr)" class="z50uotcgt"/><path fill="url(#i4GOOrY)" class="z50uotcgt"/></g><path fill="url(#in5aDFc)" class="z50uotcgt"/><path stroke="url(#iykTENe)" class="gml7mjs1e"/><g filter="url(#iIhGeXb)"><path class="fo6e4ubtr"/></g><g filter="url(#i5XLmmb)"><path class="fkaavsban"/></g><path class="e0cbbw76x"/><path fill="url(#iydKNab)" class="r4ioajtto"/><path class="vnikxkbns"/><g filter="url(#inquW6d)"><path class="g7bpppbcy"/><path fill="url(#i59n3gc)" class="ntv62zbtk"/></g><g filter="url(#igPda4Z)"><path fill="url(#ioLJgQc)" class="jbx-p_bln"/></g><path class="wcd5sbdsf"/><path fill="url(#ihpajVh)" class="iz2ikoybq"/><path class="r-pc6bbbp"/><g filter="url(#iuWgoye)"><path fill="url(#i4Et8id)" class="om0ekg77s"/></g><g filter="url(#iydjRIe)"><ellipse transform="rotate(-27.914 13.632 9.87)" class="own01tonm"/><ellipse fill="url(#iaawuxe)" transform="rotate(-27.914 13.632 9.87)" class="fxzibxmbn"/></g><g filter="url(#iz2ojke)"><path stroke="url(#ix6c84c)" class="cpsq5ig7p"/></g><g filter="url(#iFuSJXd)"><path stroke="url(#i5fXldc)" class="i3tc6-bqo"/></g><g filter="url(#ig8ezud)"><path stroke="url(#icURold)" class="zp-7rc6tp"/></g><g filter="url(#iA4SKCb)"><path fill="url(#iaEU97Y)" clip-rule="evenodd" class="d72oepody"/><path fill="url(#ilvKHwb)" clip-rule="evenodd" class="d72oepody"/></g><defs><radialGradient id="izYK5Hc" cx="0" cy="0" r="1" gradientTransform="rotate(-126.573 19.837 7.029)scale(14.4752 12.6607)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="sa_c7ns7l"/><stop offset="1" class="xflvpmp1u"/></radialGradient><radialGradient id="i3rodPc" cx="0" cy="0" r="1" gradientTransform="matrix(6.9375 -5.375 4.67303 6.03148 5.7 25.648)" gradientUnits="userSpaceOnUse"><stop class="zhj208b_d"/><stop offset="1" class="y32ab_wii"/></radialGradient><radialGradient id="iJf1iUb" cx="0" cy="0" r="1" gradientTransform="rotate(155.653 10.15 15.742)scale(12.2796 19.1721)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="vc--wpv5i"/><stop offset="1" class="iaefxbcet"/></radialGradient><radialGradient id="i8qGVjb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.09375 1.15624 -3.57275 -6.46962 12.762 28.024)" gradientUnits="userSpaceOnUse"><stop offset=".045" class="v9-8bpxan"/><stop offset="1" class="p5ii0k_1a"/></radialGradient><radialGradient id="i3dimgb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.625 0 0 -3.8125 9.856 24.18)" gradientUnits="userSpaceOnUse"><stop offset=".302" class="tv57cl-9q"/><stop offset="1" class="nof2xyhhe"/></radialGradient><radialGradient id="iqMD7gd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.26562 -1.93554 2.61071 -1.7071 23.356 25.819)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="l9b4opb5t"/><stop offset=".919" class="uaxm8f1hq"/></radialGradient><radialGradient id="isjlhEd" cx="0" cy="0" r="1" gradientTransform="rotate(155.556 9.636 14.638)scale(1.32158 .2597)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="z3hpt3mcq"/><stop offset="1" class="pzpwlzysi"/></radialGradient><radialGradient id="iNWzONb" cx="0" cy="0" r="1" gradientTransform="matrix(.42186 -1.97502 3.24628 .6934 21.762 27.322)" gradientUnits="userSpaceOnUse"><stop offset=".705" class="l9b4opb5t"/><stop offset=".989" class="uaxm8f1hq"/></radialGradient><radialGradient id="iA1fBab" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1139 -.45312 .07627 -.1875 23.728 26.884)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="z3hpt3mcq"/><stop offset="1" class="pzpwlzysi"/></radialGradient><radialGradient id="iIEcKAK" cx="0" cy="0" r="1" gradientTransform="matrix(-7.77323 -2.8082 3.94394 -10.91704 21.531 21.602)" gradientUnits="userSpaceOnUse"><stop class="pq2t7lb5q"/><stop offset=".981" class="e7f-98b7z"/></radialGradient><radialGradient id="ia50H6B" cx="0" cy="0" r="1" gradientTransform="matrix(.0287 2.22817 -1.66026 .02139 16.728 16.65)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="uct9hwfmk"/><stop offset="1" class="dsb0iwt3f"/></radialGradient><radialGradient id="iCWD9Hz" cx="0" cy="0" r="1" gradientTransform="rotate(167.545 7.09 9.238)scale(4.44166 1.16057)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="p1f9bl61w"/><stop offset="1" class="x3lhf8m8j"/></radialGradient><radialGradient id="ik6Kw6b" cx="0" cy="0" r="1" gradientTransform="rotate(-143.653 14.525 6.708)scale(.91393 .73652)" gradientUnits="userSpaceOnUse"><stop class="nwmok1m8m"/><stop offset="1" class="debc6xrbn"/></radialGradient><radialGradient id="ifau3jC" cx="0" cy="0" r="1" gradientTransform="rotate(30.491 -40.766 35.893)scale(7.14423 9.27511)" gradientUnits="userSpaceOnUse"><stop offset=".06" class="a805jtb_d"/><stop offset=".81" class="mpfjlio6c"/></radialGradient><radialGradient id="iiLdS3c" cx="0" cy="0" r="1" gradientTransform="rotate(-56.82 28.188 4.92)scale(2.3126 3.1193)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="l9b4opb5t"/><stop offset=".919" class="uaxm8f1hq"/></radialGradient><radialGradient id="iplo2Cc" cx="0" cy="0" r="1" gradientTransform="matrix(-.42043 -1.9751 3.23141 -.68786 10.244 27.32)" gradientUnits="userSpaceOnUse"><stop offset=".609" class="o9qsnlb6c"/><stop offset=".948" class="pcz4s2bal"/></radialGradient><radialGradient id="ioJN0Qd" cx="0" cy="0" r="1" gradientTransform="rotate(141.833 1.312 11.808)scale(1.27689)" gradientUnits="userSpaceOnUse"><stop class="b4of-6bao"/><stop offset="1" class="r3y-39nqq"/></radialGradient><radialGradient id="ijowZ1b" cx="0" cy="0" r="1" gradientTransform="rotate(90 -5.436 14.603)scale(1.25098)" gradientUnits="userSpaceOnUse"><stop offset=".55" class="d5fabsakk"/><stop offset="1" class="ndghkrcwe"/></radialGradient><radialGradient id="iAAvyQb" cx="0" cy="0" r="1" gradientTransform="matrix(1.17188 .58594 -.45305 .9061 .052 .516)" gradientUnits="userSpaceOnUse"><stop class="n0n4e7bnh"/><stop offset="1" class="jm8e13_st"/></radialGradient><radialGradient id="iH86wby" cx="0" cy="0" r="1" gradientTransform="matrix(.66407 -1.01563 1.1175 .73068 .52 1.063)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="yhk8aqbmk"/><stop offset="1" class="zxvvm-hti"/></radialGradient><radialGradient id="ifbe9cT" cx="0" cy="0" r="1" gradientTransform="rotate(139.138 1.348 12.664)scale(1.3016)" gradientUnits="userSpaceOnUse"><stop class="eatp636hk"/><stop offset="1" class="tgwkdpbql"/></radialGradient><radialGradient id="izM6NXd" cx="0" cy="0" r="1" gradientTransform="matrix(1 1.07031 -1.1661 1.0895 .298 .379)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="zl4k6m5yt"/><stop offset="1" class="j9i7xp3bx"/></radialGradient><radialGradient id="iGbM8pb" cx="0" cy="0" r="1" gradientTransform="matrix(1.07812 -.64844 .589 .9793 .391 .926)" gradientUnits="userSpaceOnUse"><stop offset=".29" class="tqblnl2vv"/><stop offset=".964" class="kv9fthb_h"/></radialGradient><radialGradient id="i2LQlsd" cx="0" cy="0" r="1" gradientTransform="rotate(69.815 -10.378 19.374)scale(2.04763 .82994)" gradientUnits="userSpaceOnUse"><stop class="z87kcgb7t"/><stop offset=".853" class="r_s898b6a"/></radialGradient><radialGradient id="icPrSEd" cx="0" cy="0" r="1" gradientTransform="rotate(67.353 -9.3 20.229)scale(4.0633 .80773)" gradientUnits="userSpaceOnUse"><stop class="i7kjncbis"/><stop offset="1" class="wkalc4bst"/></radialGradient><radialGradient id="iNUb3Pc" cx="0" cy="0" r="1" gradientTransform="matrix(1.97895 1.21874 -.15017 .24384 9.481 23.023)" gradientUnits="userSpaceOnUse"><stop class="ddg3g7pcd"/><stop offset="1" class="ejr-khbri"/></radialGradient><radialGradient id="iRJHFee" cx="0" cy="0" r="1" gradientTransform="rotate(-118.794 14.178 9.23)scale(2.33566 5.83179)" gradientUnits="userSpaceOnUse"><stop offset=".268" class="isiq9yb3m"/><stop offset="1" class="uq7zq9b9u"/></radialGradient><radialGradient id="iptGC2c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12499 1.3125 -.4864 -.4169 14.278 24.821)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="ehlybtbyr"/><stop offset="1" class="pbh041bmy"/></radialGradient><radialGradient id="isTDdze" cx="0" cy="0" r="1" gradientTransform="matrix(-1.64063 -.62499 .30595 -.80313 14.309 24.601)" gradientUnits="userSpaceOnUse"><stop class="u3ly29i0x"/><stop offset="1" class="k1xxa4bqz"/></radialGradient><radialGradient id="ibyJhIe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03126 2.5625 -1.3029 -.52434 21.528 21.82)" gradientUnits="userSpaceOnUse"><stop class="rau9skumu"/><stop offset="1" class="obmju7b-z"/></radialGradient><radialGradient id="iYuu2Rd" cx="0" cy="0" r="1" gradientTransform="matrix(-.67188 .51562 -.16532 -.21542 23.294 22.727)" gradientUnits="userSpaceOnUse"><stop class="m92tte26k"/><stop offset="1" class="ty1ewib_q"/></radialGradient><radialGradient id="iglME4c" cx="0" cy="0" r="1" gradientTransform="matrix(.58243 3.00041 -1.02662 .19928 19.588 20.74)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="l33l9dqgq"/><stop offset="1" class="fjji9zbbw"/></radialGradient><radialGradient id="i84ZkMb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03124 2.3125 -1.56386 -.69739 16.794 21.305)" gradientUnits="userSpaceOnUse"><stop class="wh23x9bjk"/><stop offset="1" class="wsyd1pyom"/></radialGradient><radialGradient id="iBTolRe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.96008 .75001 -.74136 -1.93748 19.285 22.992)" gradientUnits="userSpaceOnUse"><stop class="wh23x9bjk"/><stop offset="1" class="wsyd1pyom"/></radialGradient><radialGradient id="in15rgd" cx="0" cy="0" r="1" gradientTransform="rotate(111.14 1.302 16.642)scale(6.15203 6.32964)" gradientUnits="userSpaceOnUse"><stop class="hr9jc16ta"/><stop offset="1" class="f_r_72dts"/></radialGradient><radialGradient id="iJ6OHFc" cx="0" cy="0" r="1" gradientTransform="matrix(-.8047 .60938 -.52546 -.69388 16.387 23.867)" gradientUnits="userSpaceOnUse"><stop class="ifzr0vvcb"/><stop offset=".808" class="he14dbbbc"/></radialGradient><radialGradient id="iBvwMLu" cx="0" cy="0" r="1" gradientTransform="matrix(.17187 -1.1 1.36133 .2127 15.731 25.255)" gradientUnits="userSpaceOnUse"><stop offset=".039" class="xo240subg"/><stop offset="1" class="ruz641x6w"/></radialGradient><radialGradient id="ipmkRxe" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 9.666 10.648)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="x3sd7rf5r"/><stop offset="1" class="dsm4f-bda"/></radialGradient><radialGradient id="iCU00ib" cx="0" cy="0" r="1" gradientTransform="matrix(.82748 -.60254 .68772 .94447 21.232 10.383)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ytssyfa7a"/><stop offset="1" class="fnfe_1psv"/></radialGradient><radialGradient id="i62k2eb" cx="0" cy="0" r="1" gradientTransform="matrix(.82204 -1.51196 .88496 .48114 20.818 11.47)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="lvos55blo"/><stop offset=".916" class="bvmj8ubsx"/></radialGradient><radialGradient id="ivXXGke" cx="0" cy="0" r="1" gradientTransform="matrix(.25953 .2569 -.33118 .33457 20.86 10.648)" gradientUnits="userSpaceOnUse"><stop class="iqm2531qk"/><stop offset="1" class="n3g96cceg"/></radialGradient><radialGradient id="iHzbGqb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.11187 -9.65399 0 15.788 10.45)" gradientUnits="userSpaceOnUse"><stop offset=".561" class="g0r5sc7jj"/><stop offset="1" class="i5c5eto6f"/></radialGradient><radialGradient id="iC0sCSb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.61023 0 18.438 9.376)" gradientUnits="userSpaceOnUse"><stop class="kb28pwbin"/><stop offset="1" class="uck_nmbag"/></radialGradient><radialGradient id="iIK5Mkk" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39218 1.7313 0 13.876 9.342)" gradientUnits="userSpaceOnUse"><stop class="j7sc31byj"/><stop offset="1" class="e9zt2gbxt"/></radialGradient><radialGradient id="icqe6Cc" cx="0" cy="0" r="1" gradientTransform="rotate(-166.409 11.183 7.194)scale(2.92567 1.71902)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="ph-yb3bws"/><stop offset="1" class="az2la2bjr"/></radialGradient><radialGradient id="io32jGe" cx="0" cy="0" r="1" gradientTransform="matrix(.79857 -2.95942 1.09745 .29614 20.439 6.538)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="iNI1BOc" cx="0" cy="0" r="1" gradientTransform="matrix(3.82845 .35231 -.18944 2.05853 18.795 4.777)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="iy1HQOy" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68076 -2.60303 0 16.09 2.04)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="iN9AxsU" cx="0" cy="0" r="1" gradientTransform="matrix(3.07685 -2.2548 3.53253 4.82042 9.635 8.864)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="i4GOOrY" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19709 -.6332 0 16.417 12.256)" gradientUnits="userSpaceOnUse"><stop class="ldpzz4bsg"/><stop offset="1" class="xtaxaigve"/></radialGradient><radialGradient id="iydKNab" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8119 -1.29142 0 18.27 9.966)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i59n3gc" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 18.042 10.05)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ihpajVh" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81194 -1.29148 0 13.903 9.966)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iaawuxe" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.822 -1.61)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ilvKHwb" cx="0" cy="0" r="1" gradientTransform="rotate(118.072 9.661 8.597)scale(.92969 16.1409)" gradientUnits="userSpaceOnUse"><stop offset=".107" class="al0tyek2y"/><stop offset="1" class="nbz8snbyn"/></radialGradient><filter id="i1NRwre" width="21.944" height="26.818" x="4.962" y="3.242" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.952941 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3411"/></filter><filter id="ikLLxOc" width="12.631" height="14.916" x="9.484" y="8.503" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.811765 0 0 0 0 0.807843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3411"/><feGaussianBlur result="effect2_foregroundBlur_4002_3411" stdDeviation=".05"/></filter><filter id="iqoJTCd" width="5.874" height="5.537" x="6.993" y="23.17" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3411" stdDeviation=".5"/></filter><filter id="ij6S8lb" width="4.98" height="4.054" x="18.51" y="24.773" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3411" stdDeviation=".5"/></filter><filter id="inLBtfb" width="2.973" height="2.006" x="21.47" y="23.687" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3411"/></filter><filter id="iVLDuze" width="3.281" height="2" x="20.468" y="25.323" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3411"/></filter><filter id="iq0TIBb" width="13.965" height="11.381" x="9.149" y="12.631" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.192157 0 0 0 0 0.192157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3411"/></filter><filter id="inC87My" width="10.996" height="6.432" x="11.932" y="21.998" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3411" stdDeviation=".5"/></filter><filter id="ilKNRxc" width="2.973" height="2.006" x="7.658" y="23.687" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3411"/></filter><filter id="iusVGOs" width="3.266" height="2" x="8.366" y="25.323" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3411"/></filter><filter id="iJauvme" width="6.218" height="6.789" x="8.343" y="20.019" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 0.227451 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3411"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".3"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.709804 0 0 0 0 0.141176 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3411" result="effect2_innerShadow_4002_3411"/></filter><filter id="ioZ3q3e" width="6.218" height="6.639" x="17.574" y="20.019" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.239216 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3411"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.301961 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3411" result="effect2_innerShadow_4002_3411"/></filter><filter id="ijhNAhc" width="6.702" height="6.417" x="12.683" y="20.751" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.619608 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3411"/></filter><filter id="iR3VtOd" width="6.703" height="6.517" x="12.633" y="20.701" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3411" stdDeviation=".15"/></filter><filter id="inHW3cc" width="3.2" height="3.2" x="14.271" y="22.686" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3411" stdDeviation=".25"/></filter><filter id="iFuvIqe" width="2.35" height="2.35" x="14.893" y="23.055" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.521569 0 0 0 0 0.0823529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3411"/></filter><filter id="isnpTFe" width="1.458" height="2.505" x="15.848" y="20.605" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3411" stdDeviation=".125"/></filter><filter id="iIsqmvd" width="1.724" height="1.924" x="16.94" y="24.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3411" stdDeviation=".125"/></filter><filter id="i6sZdPb" width="1.368" height="2.217" x="18.104" y="22.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3411" stdDeviation=".125"/></filter><filter id="iJLWzBe" width="3.55" height="1.942" x="15.171" y="17.683" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3411" stdDeviation=".25"/></filter><filter id="inX48Pc" width="3.542" height="3.342" x="9.666" y="8.977" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.270588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3411"/></filter><filter id="iNnUKMb" width="2.992" height="2.992" x="9.841" y="9.152" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3411" stdDeviation=".25"/></filter><filter id="iHzOQbd" width="3.592" height="3.592" x="19.188" y="8.727" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.141176 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3411"/></filter><filter id="iSD0a8c" width="2.992" height="2.992" x="19.364" y="9.152" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3411" stdDeviation=".25"/></filter><filter id="iS2flMp" width="10.383" height="12.189" x="10.927" y="5.019" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.0509804 0 0 0 0 0.0509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3411"/></filter><filter id="izu38Xr" width="6.25" height="5.07" x="15.26" y="4.019" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3411" stdDeviation=".5"/></filter><filter id="iFXgqvc" width="12.614" height="8.551" x="9.783" y="1.539" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3411"/></filter><filter id="iqZRi8b" width="3.262" height="4.184" x="14.22" y="9.493" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3411" stdDeviation=".375"/></filter><filter id="iU4buZv" width="2.379" height="3.184" x="14.9" y="9.83" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3411" stdDeviation=".125"/></filter><filter id="iIhGeXb" width="2.982" height="1.874" x="17.273" y="6.996" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3411"/></filter><filter id="i5XLmmb" width="2.982" height="1.874" x="12.12" y="6.996" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3411"/></filter><filter id="inquW6d" width=".787" height=".697" x="17.536" y="9.526" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3411" stdDeviation=".05"/></filter><filter id="igPda4Z" width=".892" height=".914" x="18.377" y="9.601" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3411" stdDeviation=".1"/></filter><filter id="iuWgoye" width=".987" height="1.041" x="13.931" y="9.537" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3411" stdDeviation=".1"/></filter><filter id="iydjRIe" width=".914" height=".705" x="13.175" y="9.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3411" stdDeviation=".05"/></filter><filter id="iz2ojke" width="2.701" height="1.282" x="17.327" y="7.323" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3411" stdDeviation=".15"/></filter><filter id="iFuSJXd" width="2.779" height="1.339" x="12.102" y="7.386" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3411" stdDeviation=".15"/></filter><filter id="ig8ezud" width="1.008" height="2.271" x="10.919" y="5.457" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3411" stdDeviation=".125"/></filter><filter id="iA4SKCb" width="15.448" height="4.54" x="8.283" y="2.493" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.694118 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3411"/></filter><linearGradient id="i8J3eXk" x1="26.906" x2="11.7" y1="11.523" y2="21.523" gradientUnits="userSpaceOnUse"><stop class="fzn5p4bte"/><stop offset="1" class="mu5z5titl"/></linearGradient><linearGradient id="iRujXJe" x1="20.7" x2="10.387" y1="17.43" y2="17.43" gradientUnits="userSpaceOnUse"><stop class="ct82q_bbh"/><stop offset="1" class="gi1yleb5l"/></linearGradient><linearGradient id="i2qypic" x1="14.887" x2="14.887" y1="30.899" y2="29.617" gradientUnits="userSpaceOnUse"><stop class="ujdq-6enc"/><stop offset="1" class="hpzv-ab9a"/></linearGradient><linearGradient id="io4gIPe" x1="23.649" x2="21.867" y1="25.822" y2="24.411" gradientUnits="userSpaceOnUse"><stop class="t-y5i3b_t"/><stop offset="1" class="rsfcoybzb"/></linearGradient><linearGradient id="i5TF0qb" x1="22.95" x2="21.169" y1="27.406" y2="25.712" gradientUnits="userSpaceOnUse"><stop class="t-y5i3b_t"/><stop offset="1" class="rsfcoybzb"/></linearGradient><linearGradient id="iZ9f8ke" x1="12.653" x2="13.255" y1="29.289" y2="28.945" gradientUnits="userSpaceOnUse"><stop class="jih6tvbze"/><stop offset="1" class="g22d_bc_z"/></linearGradient><linearGradient id="isd35Ge" x1="7.856" x2="9.361" y1="24.305" y2="26.125" gradientUnits="userSpaceOnUse"><stop class="n1imc2b4i"/><stop offset="1" class="dz0-61bre"/></linearGradient><linearGradient id="iFLhSvc" x1="9.062" x2="10.843" y1="27.405" y2="25.72" gradientUnits="userSpaceOnUse"><stop class="cnrgi8b1a"/><stop offset="1" class="y8qpet1tz"/></linearGradient><linearGradient id="iqD660c" x1="14.919" x2="16.7" y1="27.168" y2="22.899" gradientUnits="userSpaceOnUse"><stop class="i1hqu4kst"/><stop offset="1" class="k_kfijbew"/></linearGradient><linearGradient id="iVpU4dr" x1="13.356" x2="16.981" y1="22.93" y2="23.617" gradientUnits="userSpaceOnUse"><stop offset=".039" class="felc_fb-i"/><stop offset="1" class="wa496n4py"/></linearGradient><linearGradient id="iTMsRuF" x1="17.231" x2="16.325" y1="26.93" y2="25.18" gradientUnits="userSpaceOnUse"><stop offset=".039" class="felc_fb-i"/><stop offset="1" class="wa496n4py"/></linearGradient><linearGradient id="ihsvHFe" x1="16.477" x2="16.477" y1="20.852" y2="22.859" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset=".214" class="e-0jmrbwd"/><stop offset=".739" class="e-0jmrbwd"/><stop offset="1" class="uy9-hlbji"/></linearGradient><linearGradient id="izL61sC" x1="17.286" x2="18.153" y1="24.906" y2="26.109" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset="0" class="gn67s1beu"/><stop offset=".739" class="gn67s1beu"/><stop offset="1" class="o38c5rykb"/></linearGradient><linearGradient id="iMFCApc" x1="18.728" x2="18.728" y1="22.438" y2="24.055" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset=".214" class="e-0jmrbwd"/><stop offset=".739" class="e-0jmrbwd"/><stop offset="1" class="uy9-hlbji"/></linearGradient><linearGradient id="iP0FelY" x1="16.132" x2="20.117" y1="19.05" y2="17.878" gradientUnits="userSpaceOnUse"><stop class="m7an_cnhm"/><stop offset="1" class="b-1v_fhcy"/></linearGradient><linearGradient id="iSgqXmb" x1="11.337" x2="10.696" y1="10.927" y2="10.927" gradientUnits="userSpaceOnUse"><stop class="fbs6uccsw"/><stop offset="1" class="np-b1wbds"/></linearGradient><linearGradient id="iGN34Jt" x1="21.947" x2="21.127" y1="9.555" y2="12.094" gradientUnits="userSpaceOnUse"><stop class="o1rzobcjq"/><stop offset="1" class="acjykw8xe"/></linearGradient><linearGradient id="is09IBb" x1="20.129" x2="12.485" y1="11.038" y2="12.177" gradientUnits="userSpaceOnUse"><stop class="cdm_o50ho"/><stop offset="1" class="ahguepbtf"/></linearGradient><linearGradient id="iZqloBe" x1="10.689" x2="12.956" y1="13.737" y2="13.595" gradientUnits="userSpaceOnUse"><stop offset=".283" class="j-n0q842a"/><stop offset="1" class="o-j_7gbpq"/></linearGradient><linearGradient id="ieT7XOd" x1="17.049" x2="25.674" y1="7.657" y2="4.689" gradientUnits="userSpaceOnUse"><stop class="cgqcq-bjq"/><stop offset="1" class="o1syipbau"/></linearGradient><linearGradient id="iBCxU1d" x1="15.225" x2="16.164" y1="11.698" y2="11.698" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="isA4ZFb" x1="17.029" x2="16.002" y1="12.021" y2="12.006" gradientUnits="userSpaceOnUse"><stop class="yww6tz8di"/><stop offset="1" class="n-4z7qb5o"/></linearGradient><linearGradient id="iVueKmr" x1="16.284" x2="16.284" y1="12.764" y2="12.19" gradientUnits="userSpaceOnUse"><stop class="xtiplndwl"/><stop offset="1" class="h8-lntwqp"/></linearGradient><linearGradient id="in5aDFc" x1="16.215" x2="16.215" y1="12.806" y2="12.638" gradientUnits="userSpaceOnUse"><stop class="zoxadnjxe"/><stop offset="1" class="gnvm67mtb"/></linearGradient><linearGradient id="iykTENe" x1="15.052" x2="15.487" y1="14.38" y2="13.692" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="ioLJgQc" x1="19.049" x2="18.735" y1="10.02" y2="10.213" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i4Et8id" x1="14.648" x2="14.334" y1="10.02" y2="10.213" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ix6c84c" x1="19.065" x2="18.644" y1="7.878" y2="7.019" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="i5fXldc" x1="13.755" x2="12.565" y1="7.75" y2="7.251" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="icURold" x1="11.423" x2="11.423" y1="5.733" y2="7.892" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient><linearGradient id="iaEU97Y" x1="20.481" x2="8.544" y1="3.68" y2="7.368" gradientUnits="userSpaceOnUse"><stop class="muovvys4e"/><stop offset="1" class="bvsk-i9dj"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-with-veil-dark" /></template>
<style>
.a805jtb_d {
  stop-color: var(--svg-color--365c3e, #365C3E);
}

.acjykw8xe {
  stop-color: var(--svg-color--452a31, #452A31);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.al0tyek2y {
  stop-color: var(--svg-color--f2f1f2, #F2F1F2);
}

.az2la2bjr {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
  stop-opacity: 0;
}

.b-1v_fhcy {
  stop-color: var(--svg-color--655554, #655554);
  stop-opacity: 0;
}

.b4of-6bao {
  stop-color: var(--svg-color--e5d7d2, #E5D7D2);
}

.brgj7qtnd {
  cx: 10.18px;
  cy: 21.606px;
  r: 0.762px;
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bvmj8ubsx {
  stop-color: var(--svg-color--31191a, #31191A);
}

.bvsk-i9dj {
  stop-color: var(--svg-color--cdc8ce, #CDC8CE);
}

.ccrydivzf {
  d: path("m11.186 26.33l2.71-1.12l-.67-1.62c-.41-1-1.1-1.691-1.988-2.11c-.465-.19-.717.06-.797.24c-.3.82-.081 2.136.085 3z");
}

.cdm_o50ho {
  stop-color: var(--svg-color--533531, #533531);
}

.cgqcq-bjq {
  stop-color: var(--svg-color--675454, #675454);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnrgi8b1a {
  stop-color: var(--svg-color--58843a, #58843A);
}

.cpsq5ig7p {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.752 7.781c.43-.075 1.27-.053 1.85.399");
}

.ct82q_bbh {
  stop-color: var(--svg-color--cac2c0, #CAC2C0);
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.d5fabsakk {
  stop-color: var(--svg-color--d7cfcf, #D7CFCF);
  stop-opacity: 0;
}

.d72oepody {
  fill-rule: evenodd;
  d: path("M15.972 4.393c-3.812 0-5.694 1.656-6.334 2.379a.775.775 0 0 1-1.16-1.027c.88-.996 3.165-2.902 7.494-2.902c4.41 0 6.608 1.915 7.54 2.876A.775.775 0 1 1 22.4 6.798c-.735-.757-2.556-2.405-6.428-2.405");
}

.ddg3g7pcd {
  stop-color: var(--svg-color--cb5996, #CB5996);
}

.debc6xrbn {
  stop-color: var(--svg-color--392726, #392726);
  stop-opacity: 0;
}

.dsb0iwt3f {
  stop-color: var(--svg-color--503c3d, #503C3D);
  stop-opacity: 0;
}

.dsm4f-bda {
  stop-color: var(--svg-color--332423, #332423);
}

.dw40nqbxs {
  d: path("M9.15 20.494a11.2 11.2 0 0 1 4.31-2.048c.28-.06.48-.32.48-.61v-3.145c0-1.13.9-2.04 2.02-2.06c1.16-.02 2.1.95 2.1 2.1v3.105c0 .29.2.54.48.61a11.3 11.3 0 0 1 4.325 2.063a8.44 8.44 0 0 1-6.852 3.503a8.44 8.44 0 0 1-6.864-3.518");
}

.dz0-61bre {
  stop-color: var(--svg-color--487a38, #487A38);
}

.dz5hgfbwb {
  fill: var(--svg-color--3f6834, #3F6834);
  d: path("M21.819 23.438c.096.053.144.219.081.348l-.668 1.39c-.181.388-.526.926-.809 1.177c-.687.638-1.466.646-2.21.3a2.4 2.4 0 0 1-.481-.291a.97.97 0 0 1-.407.892c-.466.325-1.079.16-1.39-.3l-.258-.344a.042.042 0 0 0-.068.003l-.201.312a.966.966 0 0 1-1.374.35a.97.97 0 0 1-.241-1.415l.298-.438a.042.042 0 0 0-.027-.064l-.308-.056a.97.97 0 0 1-.799-1.173a.97.97 0 0 1 1.248-.708l.516.176a.042.042 0 0 0 .055-.042l-.025-.403c-.05-.558.514 1.048 1.08 1.04c.574-.009.81-1.664.81-1.062v.467c0 .028.028.048.055.04l.458-.157q.112-.041.223-.057l.036-.085l1.043.854c.063-.13.19-.198.295-.152c.711.327.494-.417.288.728c-.022.122.015.129.098.029c.74-.9 1.97-1.695 2.682-1.36");
}

.e-0jmrbwd {
  stop-color: var(--svg-color--fff967, #FFF967);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e0cbbw76x {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.48 9.216c.653 0 1.205.45 1.355 1.06a.274.274 0 0 1-.267.34h-2.233a.23.23 0 0 1-.227-.272a1.4 1.4 0 0 1 1.372-1.128");
}

.e7f-98b7z {
  stop-color: var(--svg-color--402825, #402825);
}

.e9zt2gbxt {
  stop-color: var(--svg-color--351d26, #351D26);
  stop-opacity: 0;
}

.eatp636hk {
  stop-color: var(--svg-color--eee1dd, #EEE1DD);
}

.ehlybtbyr {
  stop-color: var(--svg-color--af3465, #AF3465);
}

.ejr-khbri {
  stop-color: var(--svg-color--cb5996, #CB5996);
  stop-opacity: 0;
}

.f_r_72dts {
  stop-color: var(--svg-color--facc4a, #FACC4A);
}

.f5jafwbws {
  d: path("M12.712 23.201c.15-.67.84-1.06 1.5-.85l.62.211a.05.05 0 0 0 .066-.05l-.03-.484c-.06-.67.41-1.267 1.09-1.277c.69-.01 1.18.527 1.18 1.25v.561a.05.05 0 0 0 .066.048l.55-.188c.64-.24 1.31.06 1.49.73c.17.65-.214 1.373-.884 1.493l-.457.1a.05.05 0 0 0-.03.079l.307.422c.44.52.34 1.32-.22 1.71s-1.296.193-1.67-.36l-.31-.413a.05.05 0 0 0-.081.003l-.242.375c-.32.59-1.08.79-1.65.42c-.58-.37-.71-1.16-.29-1.7l.357-.526a.05.05 0 0 0-.032-.078l-.37-.066c-.67-.1-1.11-.75-.96-1.41");
}

.fbs6uccsw {
  stop-color: var(--svg-color--281920, #281920);
}

.felc_fb-i {
  stop-color: var(--svg-color--ecb12a, #ECB12A);
}

.fjji9zbbw {
  stop-color: var(--svg-color--e16fa7, #E16FA7);
  stop-opacity: 0;
}

.fkaavsban {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m12.313 7.926l.001-.001l.002-.002l.004-.003l.012-.01a2 2 0 0 1 .155-.108c.1-.062.242-.14.42-.21a2.83 2.83 0 0 1 1.495-.159a.534.534 0 0 1-.167 1.056a1.77 1.77 0 0 0-.935.096a1.5 1.5 0 0 0-.308.166a.534.534 0 0 1-.68-.825");
}

.fnfe_1psv {
  stop-color: var(--svg-color--40272a, #40272A);
  stop-opacity: 0;
}

.fo-imacds {
  fill: var(--svg-color--ffdd2c, #FFDD2C);
  d: path("M12.712 23.201c.15-.67.84-1.06 1.5-.85l.62.211a.05.05 0 0 0 .066-.05l-.03-.484c-.06-.67.41-1.267 1.09-1.277c.69-.01 1.18.527 1.18 1.25v.561a.05.05 0 0 0 .066.048l.55-.188c.64-.24 1.31.06 1.49.73c.17.65-.214 1.373-.884 1.493l-.457.1a.05.05 0 0 0-.03.079l.307.422c.44.52.34 1.32-.22 1.71s-1.296.193-1.67-.36l-.31-.413a.05.05 0 0 0-.081.003l-.242.375c-.32.59-1.08.79-1.65.42c-.58-.37-.71-1.16-.29-1.7l.357-.526a.05.05 0 0 0-.032-.078l-.37-.066c-.67-.1-1.11-.75-.96-1.41");
}

.fo6e4ubtr {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m19.813 7.926l-.002-.001l-.002-.002l-.004-.003l-.012-.01l-.036-.027a2.6 2.6 0 0 0-.54-.291a2.84 2.84 0 0 0-1.493-.159a.534.534 0 0 0 .166 1.056c.399-.063.717.01.935.096a1.5 1.5 0 0 1 .309.166a.534.534 0 0 0 .679-.825");
}

.ft5dv1b6b {
  fill: none;
}

.fxzibxmbn {
  cx: 13.632px;
  cy: 9.87px;
  rx: 0.39px;
  ry: 0.197px;
}

.fzn5p4bte {
  stop-color: var(--svg-color--e7dedd, #E7DEDD);
}

.g0r5sc7jj {
  stop-color: var(--svg-color--3d2138, #3D2138);
  stop-opacity: 0;
}

.g22d_bc_z {
  stop-color: var(--svg-color--416b43, #416B43);
  stop-opacity: 0;
}

.g7bpppbcy {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.207 9.677c.063.085-.07.19-.22.302c-.152.113-.264.193-.328.108c-.063-.085.008-.246.159-.36c.151-.112.325-.135.389-.05");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gi1yleb5l {
  stop-color: var(--svg-color--aca4a1, #ACA4A1);
}

.gml7mjs1e {
  fill: var(--svg-color--2a0219, #2A0219);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.726 13.408c.394.205.863.323 1.364.323c.505 0 .97-.118 1.363-.323a.2.2 0 0 1 .242.04a.19.19 0 0 1 .02.241m-2.989-.281l2.948.254m-2.948-.254a.2.2 0 0 0-.242.042a.19.19 0 0 0-.02.24m.262-.282l-.22.254m3.21.027l-.042-.027m.042.027l-.042-.027m.042.027a1.95 1.95 0 0 1-1.626.87a1.95 1.95 0 0 1-1.626-.87m3.21-.027c-.335.507-.92.846-1.584.846c-.666 0-1.25-.339-1.585-.846m-.041.027v.001l.041-.028m-.041.027l.041-.027");
}

.gn67s1beu {
  stop-color: var(--svg-color--ffef65, #FFEF65);
}

.gnvm67mtb {
  stop-color: var(--svg-color--31171f, #31171F);
  stop-opacity: 0;
}

.h-5x17bxj {
  d: path("M9.984 15.883c0-4.854 2.694-7.28 6.016-7.28s6.016 2.323 6.016 7.28v7.436H9.984z");
}

.h2cywub0g {
  cx: 11.337px;
  cy: 10.648px;
  r: 1.671px;
}

.h8-lntwqp {
  stop-color: var(--svg-color--3f222f, #3F222F);
  stop-opacity: 0;
}

.hbyh_lbnn {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m17.348 24.82l.907 1.18");
}

.he14dbbbc {
  stop-color: var(--svg-color--f38330, #F38330);
}

.hej-omb_k {
  fill: var(--svg-color--c55496, #C55496);
  d: path("M8.528 22.789c-.076-.155-.018-.354.098-.418c.854-.404 2.333.552 3.222 1.633c.099.12.144.112.117-.035c-.248-1.376-.009-3.139.846-3.532c.126-.055.278.027.355.182l.753 1.632l.133.311c.111.292.303.839.336 1.134c.152 1.232-.46 2.09-1.43 2.538c-.894.415-1.83.406-2.656-.36c-.34-.303-.754-.948-.972-1.414z");
}

.hpzv-ab9a {
  stop-color: var(--svg-color--d2cfd8, #D2CFD8);
  stop-opacity: 0;
}

.hr9jc16ta {
  stop-color: var(--svg-color--ffe24b, #FFE24B);
}

.hzq3o_buh {
  d: path("M20.61 25.837c.678-.6 1.716-.535 2.297.112l.69.734c.063.068.083.205-.023.271c-.91.563-1.996.492-2.66-.27l-.42-.584a.11.11 0 0 1 .009-.15z");
}

.i1hqu4kst {
  stop-color: var(--svg-color--ca992e, #CA992E);
}

.i3tc6-bqo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.527 8.3c.328-.29 1.043-.594 1.93-.453");
}

.i4i_2ibui {
  fill: var(--svg-color--dca238, #DCA238);
  d: path("M15.87 25.387a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.i5c5eto6f {
  stop-color: var(--svg-color--3d2138, #3D2138);
}

.i7kjncbis {
  stop-color: var(--svg-color--d35897, #D35897);
}

.iaefxbcet {
  stop-color: var(--svg-color--c9c5cd, #C9C5CD);
}

.ifzr0vvcb {
  stop-color: var(--svg-color--ffad67, #FFAD67);
}

.iqm2531qk {
  stop-color: var(--svg-color--352123, #352123);
}

.isiq9yb3m {
  stop-color: var(--svg-color--c46399, #C46399);
}

.ix_9o_9wu {
  d: path("M21.48 25.324c.063-.898.843-1.586 1.721-1.535l.99.06c.121 0 .162.157.149.206c-.176.967-.961 1.703-2 1.633l-.768-.097a.11.11 0 0 1-.102-.118z");
}

.iz2ikoybq {
  d: path("M13.901 9.488a.893.893 0 0 0-.86 1.129h1.725a1 1 0 0 0 .033-.236a.9.9 0 0 0-.898-.893");
}

.j-elh2uvv {
  cx: 9.168px;
  cy: 20.528px;
  r: 0.762px;
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j7sc31byj {
  stop-color: var(--svg-color--351d26, #351D26);
}

.j9i7xp3bx {
  stop-color: var(--svg-color--cdc7c8, #CDC7C8);
}

.jbx-p_bln {
  d: path("M19.068 10.264a.84.84 0 0 0-.231-.463l-.26.285l.117.229z");
}

.jekksk-xe {
  cx: 11.337px;
  cy: 10.648px;
  r: 0.996px;
}

.ji48w9x8q {
  cx: 20.859px;
  cy: 10.648px;
  r: 1.671px;
}

.jih6tvbze {
  stop-color: var(--svg-color--3e5d50, #3E5D50);
}

.jm8e13_st {
  stop-color: var(--svg-color--e1d6d3, #E1D6D3);
}

.jtc6ijb6j {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M16.098 21.055c.324 0 .758.376.758.86v.944");
}

.k_7yd74ov {
  fill: var(--svg-color--21181b, #21181B);
  d: path("m20.913 4.165l.43.213c.751.374 1.18 1.228 1.02 2.135l-.59 3.043c-.054.315-.261.526-.573.534h-.018s.053-.907.107-1.441c.043-.434-.032-.566-.43-.961c-.214-.214-.376-.534-.376-.854V5.98c0-.267-.214-.48-.429-.534c-.644-.16-1.986-.427-3.92-.427c-1.932 0-3.274.267-3.919.427a.52.52 0 0 0-.43.534v.854c0 .32-.107.64-.375.854l-.161.16c-.215.16-.322.48-.322.747c.053.588.107 1.442.107 1.442l-.05-.002a.634.634 0 0 1-.594-.532L9.8 6.46c-.108-.854.321-1.708 1.073-2.082l.43-.213a8 8 0 0 0 .805-.588l.966-1.014c.59-.534 1.45-.694 2.202-.32c.537.16 1.127.16 1.664 0c.805-.267 1.718-.054 2.362.534l.806.8c.215.267.483.427.805.588");
}

.k_kfijbew {
  stop-color: var(--svg-color--ca992e, #CA992E);
  stop-opacity: 0;
}

.k13ak_bzi {
  d: path("M10.52 25.324c-.063-.898-.843-1.586-1.721-1.535l-.99.06c-.121 0-.162.157-.149.206c.176.967.961 1.703 2 1.633l.768-.097a.11.11 0 0 0 .102-.118z");
}

.k1xxa4bqz {
  stop-color: var(--svg-color--af246b, #AF246B);
  stop-opacity: 0;
}

.kb28pwbin {
  stop-color: var(--svg-color--412628, #412628);
}

.kcwstyspx {
  d: path("m20.799 26.33l-2.71-1.12l.67-1.62c.41-1 1.1-1.691 1.987-2.11c.466-.19.718.06.798.24c.3.82.081 2.136-.085 3z");
}

.kv9fthb_h {
  stop-color: var(--svg-color--dfc7b5, #DFC7B5);
}

.l33l9dqgq {
  stop-color: var(--svg-color--e16fa7, #E16FA7);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l9b4opb5t {
  stop-color: var(--svg-color--338e58, #338E58);
  stop-opacity: 0;
}

.ldpzz4bsg {
  stop-color: var(--svg-color--624e4d, #624E4D);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lux6k2ifl {
  fill: var(--svg-color--9b9da0, #9B9DA0);
  d: path("M9.134 24.173c.879-.052 1.658.636 1.72 1.534l.009.116c.31.043.61.174.862.397l.107.114a.11.11 0 0 1 .01.15l-.42.582c-.665.762-1.75.833-2.66.27c-.064-.05-.086-.202-.024-.27l.69-.734q.136-.152.302-.26c-.906-.06-1.574-.75-1.735-1.634c-.013-.049.028-.207.15-.207z");
}

.lvos55blo {
  stop-color: var(--svg-color--31191a, #31191A);
  stop-opacity: 0;
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m7an_cnhm {
  stop-color: var(--svg-color--655554, #655554);
}

.m92tte26k {
  stop-color: var(--svg-color--e170ad, #E170AD);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.movji7bnz {
  r: 0.762px;
}

.mpfjlio6c {
  stop-color: var(--svg-color--619951, #619951);
}

.mu5z5titl {
  stop-color: var(--svg-color--c6bebf, #C6BEBF);
}

.muovvys4e {
  stop-color: var(--svg-color--e2dfe3, #E2DFE3);
}

.n-4z7qb5o {
  stop-color: var(--svg-color--624d4b, #624D4B);
  stop-opacity: 0;
}

.n0n4e7bnh {
  stop-color: var(--svg-color--f3f0ef, #F3F0EF);
}

.n1imc2b4i {
  stop-color: var(--svg-color--4f8436, #4F8436);
}

.n3g96cceg {
  stop-color: var(--svg-color--352123, #352123);
  stop-opacity: 0;
}

.nbz8snbyn {
  stop-color: var(--svg-color--f2f1f2, #F2F1F2);
  stop-opacity: 0;
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.ndghkrcwe {
  stop-color: var(--svg-color--c3bbbb, #C3BBBB);
}

.nof2xyhhe {
  stop-color: var(--svg-color--d1ced0, #D1CED0);
  stop-opacity: 0;
}

.np-b1wbds {
  stop-color: var(--svg-color--27161d, #27161D);
}

.ntrmoswfw {
  d: path("M8.528 22.789c-.076-.155-.018-.354.098-.418c.854-.404 2.333.552 3.222 1.633c.099.12.144.112.117-.035c-.248-1.376-.009-3.139.846-3.532c.126-.055.278.027.355.182l.753 1.632l.133.311c.111.292.303.839.336 1.134c.152 1.232-.46 2.09-1.43 2.538c-.894.415-1.83.406-2.656-.36c-.34-.303-.754-.948-.972-1.414z");
}

.ntv62zbtk {
  d: path("M18.207 9.677c.063.085-.07.19-.22.302c-.152.113-.264.193-.328.108c-.063-.085.008-.246.159-.36c.151-.112.325-.135.389-.05");
}

.nwmok1m8m {
  stop-color: var(--svg-color--392726, #392726);
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o110mgbff {
  d: path("M23.457 22.789c.076-.155.018-.354-.098-.418c-.854-.404-2.334.552-3.222 1.633c-.099.12-.144.112-.117-.035c.247-1.376.009-3.139-.846-3.532c-.127-.055-.279.027-.355.182l-.754 1.632c-.044.107-.088.204-.132.311c-.111.292-.303.839-.336 1.134c-.152 1.232.46 2.09 1.43 2.538c.894.415 1.83.406 2.656-.36c.34-.303.754-.948.972-1.414z");
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o1syipbau {
  stop-color: var(--svg-color--685654, #685654);
  stop-opacity: 0;
}

.o2j9ljphc {
  d: path("m13.196 29.96l-2.547-3.836l5.25-3.476l5.828 2.91l-2.922 4.403z");
}

.o38c5rykb {
  stop-color: var(--svg-color--ffef65, #FFEF65);
  stop-opacity: 0;
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.o7b0b7x3a {
  fill: var(--svg-color--aaaeae, #AAAEAE);
  d: path("M19.688 26.002c.78-.46 1.787-.2 2.235.545l.538.852c.048.078.043.217-.074.261c-1 .38-2.053.105-2.561-.77l-.302-.652a.11.11 0 0 1 .037-.145z");
}

.o9qsnlb6c {
  stop-color: var(--svg-color--1b572f, #1B572F);
  stop-opacity: 0;
}

.obmju7b-z {
  stop-color: var(--svg-color--d0246b, #D0246B);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.om0ekg77s {
  d: path("M14.717 10.277c0-.29-.235-.482-.298-.54l-.289.28l.178.361z");
}

.own01tonm {
  cx: 13.632px;
  cy: 9.87px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.oxi6re-fl {
  d: path("m20.913 4.165l.43.213c.751.374 1.18 1.228 1.02 2.135l-.59 3.043c-.054.315-.261.526-.573.534h-.018s.053-.907.107-1.441c.043-.434-.032-.566-.43-.961c-.214-.214-.376-.534-.376-.854V5.98c0-.267-.214-.48-.429-.534c-.644-.16-1.986-.427-3.92-.427c-1.932 0-3.274.267-3.919.427a.52.52 0 0 0-.43.534v.854c0 .32-.107.64-.375.854l-.161.16c-.215.16-.322.48-.322.747c.053.588.107 1.442.107 1.442l-.05-.002a.634.634 0 0 1-.594-.532L9.8 6.46c-.108-.854.321-1.708 1.073-2.082l.43-.213a8 8 0 0 0 .805-.588l.966-1.014c.59-.534 1.45-.694 2.202-.32c.537.16 1.127.16 1.664 0c.805-.267 1.718-.054 2.362.534l.806.8c.215.267.483.427.805.588");
}

.p1f9bl61w {
  stop-color: var(--svg-color--2f1921, #2F1921);
}

.p5ii0k_1a {
  stop-color: var(--svg-color--a3a2a8, #A3A2A8);
  stop-opacity: 0;
}

.pa5huib1d {
  fill: var(--svg-color--332024, #332024);
  d: path("m15.814 10.526l-.821 1.701c-.102.35.142.7.489.7h.737c.346 0 .59-.355.489-.7l-.499-1.701c-.107-.377-.283-.377-.395 0");
}

.pbh041bmy {
  stop-color: var(--svg-color--af3465, #AF3465);
  stop-opacity: 0;
}

.pcz4s2bal {
  stop-color: var(--svg-color--1b572f, #1B572F);
}

.ph-yb3bws {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pq2t7lb5q {
  stop-color: var(--svg-color--543a37, #543A37);
}

.pzpwlzysi {
  stop-color: var(--svg-color--8bc659, #8BC659);
  stop-opacity: 0;
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_s898b6a {
  stop-color: var(--svg-color--b81560, #B81560);
}

.r-_oyqohi {
  d: path("m10.985 10.035l.049.002s-.054-.854-.107-1.442c0-.267.107-.587.322-.747l.16-.16c.27-.214.377-.534.377-.854v-.855a.52.52 0 0 1 .43-.533c.644-.16 1.986-.427 3.919-.427c1.932 0 3.275.266 3.919.427c.215.053.43.267.43.533v.855c0 .32.16.64.375.854c.503.352.472.546.43.96a46 46 0 0 0-.108 1.442h.019l-.267 3.962c-.16 1.771-1.553 3.006-3.213 3.006h-3.213c-1.714 0-3.053-1.235-3.214-3.006z");
}

.r-pc6bbbp {
  fill: var(--svg-color--000, #000);
  d: path("M14.413 10.382a.51.51 0 0 0-.512-.512a.51.51 0 0 0-.454.747h.905a.5.5 0 0 0 .06-.235");
}

.r3y-39nqq {
  stop-color: var(--svg-color--cbc7ca, #CBC7CA);
}

.r4ioajtto {
  d: path("M18.273 9.488a.893.893 0 0 1 .86 1.129h-1.725a.897.897 0 0 1 .865-1.129");
}

.rau9skumu {
  stop-color: var(--svg-color--de5390, #DE5390);
}

.rk5yg3y4a {
  d: path("M15.993 25.255a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.rsfcoybzb {
  stop-color: var(--svg-color--64a25a, #64A25A);
}

.ruz641x6w {
  stop-color: var(--svg-color--d76316, #D76316);
  stop-opacity: 0;
}

.s9dopkbsv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M15.92 18.874c.395.01 1.357-.063 2.05-.441");
}

.sa_c7ns7l {
  stop-color: var(--svg-color--d4d0d4, #D4D0D4);
}

.shep8_bdh {
  d: path("M27 29.961v-1c0-5.2-3.61-9.365-8.46-10.515a.63.63 0 0 1-.48-.61v-3.105c0-1.15-.94-2.12-2.1-2.1c-1.12.02-2.02.93-2.02 2.06v3.145c0 .29-.2.55-.48.61C8.61 19.586 5 23.761 5 28.961v1z");
}

.t-y5i3b_t {
  stop-color: var(--svg-color--8ac463, #8AC463);
}

.tgwkdpbql {
  stop-color: var(--svg-color--bab5b4, #BAB5B4);
}

.tpcvtjbvk {
  fill: var(--svg-color--dc62a7, #DC62A7);
  d: path("M23.457 22.789c.076-.155.018-.354-.098-.418c-.854-.404-2.334.552-3.222 1.633c-.099.12-.144.112-.117-.035c.247-1.376.009-3.139-.846-3.532c-.127-.055-.279.027-.355.182l-.754 1.632c-.044.107-.088.204-.132.311c-.111.292-.303.839-.336 1.134c-.152 1.232.46 2.09 1.43 2.538c.894.415 1.83.406 2.656-.36c.34-.303.754-.948.972-1.414z");
}

.tqblnl2vv {
  stop-color: var(--svg-color--e3dede, #E3DEDE);
  stop-opacity: 0;
}

.tv57cl-9q {
  stop-color: var(--svg-color--d1ced0, #D1CED0);
}

.ty1ewib_q {
  stop-color: var(--svg-color--e170ad, #E170AD);
  stop-opacity: 0;
}

.tzg34ubeh {
  d: path("m20.057 5.019l-3.08 1.027a1.048 1.048 0 0 0 .47 2.033l3.063-.41z");
}

.u3ly29i0x {
  stop-color: var(--svg-color--af246b, #AF246B);
}

.uaxm8f1hq {
  stop-color: var(--svg-color--338e58, #338E58);
}

.uck_nmbag {
  stop-color: var(--svg-color--412628, #412628);
  stop-opacity: 0;
}

.uct9hwfmk {
  stop-color: var(--svg-color--503c3d, #503C3D);
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.ujdq-6enc {
  stop-color: var(--svg-color--d2cfd8, #D2CFD8);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.uq7zq9b9u {
  stop-color: var(--svg-color--c46399, #C46399);
  stop-opacity: 0;
}

.uy9-hlbji {
  stop-color: var(--svg-color--fff967, #FFF967);
  stop-opacity: 0;
}

.v9-8bpxan {
  stop-color: var(--svg-color--a3a2a8, #A3A2A8);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vnikxkbns {
  fill: var(--svg-color--000, #000);
  d: path("M17.761 10.382a.51.51 0 0 1 .512-.512a.51.51 0 0 1 .454.747h-.905a.46.46 0 0 1-.06-.235");
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.w_teojfnp {
  cx: 20.86px;
  cy: 10.648px;
  r: 0.996px;
  fill: var(--svg-color--463133, #463133);
}

.w0lgbgbhh {
  d: path("M5.062 16.46c0-8.812 4.89-13.218 10.922-13.218s10.922 4.219 10.922 13.219v13.5H5.062z");
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.wa496n4py {
  stop-color: var(--svg-color--ecb12a, #ECB12A);
  stop-opacity: 0;
}

.wcd5sbdsf {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.694 9.216c-.653 0-1.205.45-1.356 1.06a.274.274 0 0 0 .268.34h2.233a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.372-1.128");
}

.wh23x9bjk {
  stop-color: var(--svg-color--fff763, #FFF763);
}

.whnrrccuq {
  cx: 20.86px;
  cy: 10.648px;
  r: 0.996px;
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wiyv84b_o {
  fill: var(--svg-color--4b3034, #4B3034);
  d: path("m15.707 10.363l-.532 1.7a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .521-.7l-.532-1.7c-.114-.377-.646-.377-.765 0");
}

.wkalc4bst {
  stop-color: var(--svg-color--d35897, #D35897);
  stop-opacity: 0;
}

.wn7tf0b0a {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M18.434 22.602c.307.135.83.615.461 1.453");
}

.wsyd1pyom {
  stop-color: var(--svg-color--fff763, #FFF763);
  stop-opacity: 0;
}

.x3lhf8m8j {
  stop-color: var(--svg-color--2f1921, #2F1921);
  stop-opacity: 0;
}

.x3sd7rf5r {
  stop-color: var(--svg-color--362324, #362324);
}

.xflvpmp1u {
  stop-color: var(--svg-color--d4d0d4, #D4D0D4);
  stop-opacity: 0;
}

.xo240subg {
  stop-color: var(--svg-color--d76316, #D76316);
}

.xtaxaigve {
  stop-color: var(--svg-color--624e4d, #624E4D);
  stop-opacity: 0;
}

.xtiplndwl {
  stop-color: var(--svg-color--3f222f, #3F222F);
}

.y32ab_wii {
  stop-color: var(--svg-color--bcb7bd, #BCB7BD);
  stop-opacity: 0;
}

.y8qpet1tz {
  stop-color: var(--svg-color--34673c, #34673C);
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.yhk8aqbmk {
  stop-color: var(--svg-color--e6dcda, #E6DCDA);
  stop-opacity: 0;
}

.yjp69hbuv {
  fill-rule: evenodd;
  d: path("M13.709 24.364a.913.913 0 0 1-.753-1.108a.91.91 0 0 1 1.178-.667l.617.21a.3.3 0 0 0 .396-.303l-.03-.484v-.007q-.019-.216.044-.404a.85.85 0 0 1 .8-.6c.532-.008.927.396.927 1v.561a.3.3 0 0 0 .396.284l.551-.187l.007-.003c.516-.193 1.023.047 1.16.56c.14.531-.183 1.092-.687 1.182l-.466.103a.3.3 0 0 0-.178.47l.312.43l.006.007a.92.92 0 0 1-.172 1.343c-.429.299-1.012.16-1.32-.295l-.316-.423a.3.3 0 0 0-.493.017l-.247.384l-.005.008a.91.91 0 0 1-1.294.33l-.001-.002a.92.92 0 0 1-.227-1.335l.005-.007l.362-.533a.3.3 0 0 0-.196-.464l-.369-.066z");
}

.ylqxkab7o {
  d: path("M11.39 25.837c-.678-.6-1.716-.535-2.298.112l-.69.734c-.062.068-.04.22.024.27c.91.563 1.996.493 2.66-.27l.42-.583a.11.11 0 0 0-.009-.15z");
}

.ytssyfa7a {
  stop-color: var(--svg-color--40272a, #40272A);
}

.yww6tz8di {
  stop-color: var(--svg-color--624d4b, #624D4B);
}

.z3hpt3mcq {
  stop-color: var(--svg-color--8bc659, #8BC659);
}

.z50uotcgt {
  d: path("m15.707 10.363l-.532 1.7a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .521-.7l-.532-1.7c-.114-.377-.646-.377-.765 0");
}

.z87kcgb7t {
  stop-color: var(--svg-color--c23471, #C23471);
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zhj208b_d {
  stop-color: var(--svg-color--bcb7bd, #BCB7BD);
}

.zl4k6m5yt {
  stop-color: var(--svg-color--f1eceb, #F1ECEB);
}

.zoxadnjxe {
  stop-color: var(--svg-color--31171f, #31171F);
}

.zp-7rc6tp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.552 5.832v.898c-.007.15-.07.482-.258.623");
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

.zxvvm-hti {
  stop-color: var(--svg-color--d9cabf, #D9CABF);
}

</style>
