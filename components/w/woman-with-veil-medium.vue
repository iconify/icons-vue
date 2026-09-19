<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iibEHhb)"><path fill="url(#iRhATUd)" class="qfugmzqtf"/><path fill="url(#iCvPZKd)" class="qfugmzqtf"/><path fill="url(#iDDdakb)" class="qfugmzqtf"/></g><g filter="url(#ittMWNe)"><path fill="url(#iZNna5d)" class="dq75q8bft"/></g><g filter="url(#iIZkgEb)"><path fill="url(#ifIW2cc)" clip-rule="evenodd" class="kxmcwkltc"/><path fill="url(#iHN7Z7x)" clip-rule="evenodd" class="kxmcwkltc"/><path fill="url(#inlchNW)" clip-rule="evenodd" class="kxmcwkltc"/><path fill="url(#i1rUuld)" clip-rule="evenodd" class="kxmcwkltc"/><path fill="url(#iMSzrex)" clip-rule="evenodd" class="kxmcwkltc"/><path fill="url(#iHGtO2d)" clip-rule="evenodd" class="kxmcwkltc"/><path fill="url(#iCiwxXx)" clip-rule="evenodd" class="kxmcwkltc"/><path fill="url(#ik421ye)" clip-rule="evenodd" class="kxmcwkltc"/><path fill="url(#iEzj9zb)" clip-rule="evenodd" class="kxmcwkltc"/><path fill="url(#iR5762n)" clip-rule="evenodd" class="kxmcwkltc"/><path fill="url(#ia1j8od)" clip-rule="evenodd" class="kxmcwkltc"/><path fill="url(#ivIthgd)" clip-rule="evenodd" class="kxmcwkltc"/></g><path fill="url(#iTIwBqe)" class="u5jpvacda"/><path fill="url(#ifGtn7E)" class="u5jpvacda"/><path fill="url(#iAO2btb)" class="u5jpvacda"/><path fill="url(#iJTDZBA)" class="u5jpvacda"/><g filter="url(#iwsiV4b)"><path class="knk8j3xyr"/></g><g filter="url(#ifvRmfl)"><path class="dwa5ppott"/></g><g filter="url(#i9NVjNc)"><path fill="url(#ibzNNgf)" class="tj1at3a2l"/><path fill="url(#iNXjvJd)" class="tj1at3a2l"/><path fill="url(#iLiUiRd)" class="tj1at3a2l"/></g><g filter="url(#iXpFLBc)"><path fill="url(#iYMYNDd)" class="fhzxtua6p"/><path fill="url(#iGGVcnc)" class="fhzxtua6p"/><path fill="url(#iXIEzMd)" class="fhzxtua6p"/></g><g filter="url(#ieZyege)"><path fill="url(#i5jaAiH)" class="hsr3pf4ww"/><path fill="url(#ihnSOpb)" class="hsr3pf4ww"/><path fill="url(#iklVAse)" class="hsr3pf4ww"/><path fill="url(#iZBVQGe)" class="hsr3pf4ww"/><path fill="url(#igW1ABb)" class="hsr3pf4ww"/></g><path fill="url(#i99L1zp)" class="m6ubs3bqo"/><path fill="url(#ir1beic)" class="m6ubs3bqo"/><g filter="url(#iXOj8hd)"><path class="inqzkd-7z"/></g><g filter="url(#ir6fqbK)"><path fill="url(#i3i4UVc)" class="qpy3mfbui"/><path fill="url(#ifSsiqe)" class="qpy3mfbui"/></g><g filter="url(#iqnXQPd)"><path fill="url(#i6g3Gsb)" class="b84xurbwm"/><path fill="url(#iO9MJMe)" class="b84xurbwm"/></g><circle fill="url(#imMMNxc)" class="hy-w2u91k"/><circle fill="url(#ivygAUc)" class="hy-w2u91k"/><circle fill="url(#iAAvyQb)" transform="matrix(-1 0 0 1 22.919 20.41)" class="movji7bnz"/><circle fill="url(#iH86wby)" transform="matrix(-1 0 0 1 22.919 20.41)" class="movji7bnz"/><circle fill="url(#iMg4SFb)" class="iez_ribyj"/><circle fill="url(#izM6NXd)" transform="matrix(-1 0 0 1 21.97 21.468)" class="movji7bnz"/><circle fill="url(#iGbM8pb)" transform="matrix(-1 0 0 1 21.97 21.468)" class="movji7bnz"/><path fill="url(#igbw8Ed)" class="knn4fxbsm"/><g filter="url(#iLYkfbc)"><path class="wcvk_loqv"/><path fill="url(#ilgojKb)" class="qth9jkbhl"/><path fill="url(#iRZ8lcb)" class="qth9jkbhl"/><path fill="url(#iAjYCLK)" class="qth9jkbhl"/><path fill="url(#iejaO7b)" class="qth9jkbhl"/><path fill="url(#i8u60Kc)" class="qth9jkbhl"/></g><path fill="url(#iss2TEd)" class="iqtiw5vmo"/><g filter="url(#iTQGwAb)"><path class="o_-55_dqa"/><path fill="url(#iRjoLDc)" class="mkzqq_74a"/><path fill="url(#i1prXNb)" class="mkzqq_74a"/></g><g filter="url(#i8ekhhd)"><path class="nhx1lw5my"/><path fill="url(#iNabhlb)" class="ib72tsbrb"/><path fill="url(#ilxZkoV)" class="ib72tsbrb"/><path fill="url(#i1ci7sc)" class="ib72tsbrb"/><path fill="url(#iCWVGpM)" class="ib72tsbrb"/><path fill="url(#is9mttb)" class="ib72tsbrb"/></g><g filter="url(#iIY7cxM)"><path fill="url(#iVx6omb)" clip-rule="evenodd" class="pjs-sfuyh"/></g><g filter="url(#iqvdfed)"><path class="zbwtm_a3x"/></g><g filter="url(#iMZkESJ)"><path fill="url(#i2VnJod)" class="emxl68qul"/><path fill="url(#ibMQltn)" class="emxl68qul"/></g><g filter="url(#iWUdvtc)"><path stroke="url(#itrE8mc)" class="qgfdn0els"/></g><g filter="url(#iiuJxHe)"><path stroke="url(#iHkRXXc)" class="dbns8_byb"/></g><g filter="url(#ir5Ojfc)"><path stroke="url(#i1eDidc)" class="obu6d-4mj"/></g><g filter="url(#iEPfjbc)"><path stroke="url(#ixpM4OI)" class="p6khytbgt"/></g><g filter="url(#iK4l8Od)"><path fill="url(#iyajRsp)" class="gbn28d8fq"/></g><path fill="url(#idEoiSb)" class="gbn28d8fq"/><g filter="url(#ia4YZPb)"><path fill="url(#i7c8OuK)" class="ghnhmfcab"/><path fill="url(#iznxtrb)" class="ghnhmfcab"/></g><g filter="url(#iCuT4Sx)"><path class="u1pckdb8y"/><path fill="url(#iZjYKpb)" class="x2y841bdq"/></g><g filter="url(#iPrruGc)"><path class="fayzwvhye"/><path fill="url(#i3JWWAe)" class="vp7ae1_xw"/></g><g filter="url(#ishpnwd)"><path fill="url(#i626DLe)" class="k5ieljw3s"/><path fill="url(#ipzaOIe)" class="k5ieljw3s"/><path fill="url(#iV9IKCe)" class="k5ieljw3s"/><path fill="url(#igwKlYd)" class="k5ieljw3s"/><path fill="url(#ioOsIGd)" class="k5ieljw3s"/><path fill="url(#iV5lRBe)" class="k5ieljw3s"/><path fill="url(#i4RIxJe)" class="k5ieljw3s"/><path fill="url(#i2Nt9Cc)" class="k5ieljw3s"/></g><path fill="url(#isdXSUb)" class="k5ieljw3s"/><g filter="url(#iFPgJIb)"><path class="fto_-78ii"/></g><g filter="url(#iTXCnKb)"><path class="wqftqw10s"/><path fill="url(#iwAf7le)" class="mt79dxbhn"/><path fill="url(#i4cPYue)" class="mt79dxbhn"/><path fill="url(#iMwelne)" class="mt79dxbhn"/><path fill="url(#iAD6Gtc)" class="mt79dxbhn"/></g><g filter="url(#iDxVJqp)"><path stroke="url(#igkfldb)" class="enqe5037q"/></g><path class="wzc4qesat"/><g filter="url(#ik1Ox5c)"><path class="sxw271g7g"/></g><g filter="url(#iOWcp3d)"><path class="t11w35bzd"/></g><g filter="url(#iZi3Wbd)"><path class="v1p9nob5e"/></g><g filter="url(#isMhVye)"><path clip-rule="evenodd" class="monvxeeww"/></g><path class="k7l2qd3fg"/><path fill="url(#i99tAud)" class="a5usbva2v"/><path class="a3tjcx75t"/><g filter="url(#imWwVec)"><path class="ll_a9ebcz"/><path fill="url(#i0qY0Sc)" class="gg1o4rtuc"/></g><g filter="url(#i03ZMyc)"><path fill="url(#icJnqab)" class="qq-3exrjf"/></g><path class="hslc4mdnn"/><path fill="url(#i3A2fDE)" class="gybevs2rv"/><path class="g_7ofss0n"/><g filter="url(#iFDBpFe)"><path fill="url(#iAMBL9d)" class="n_8ruvbgx"/></g><g filter="url(#iZS6ire)"><ellipse transform="rotate(-27.914 13.553 9.892)" class="ibjr3phds"/><ellipse fill="url(#iECormb)" transform="rotate(-27.914 13.553 9.892)" class="h8u9xcqom"/></g><g filter="url(#iREoSDe)"><path class="xh15oqbjw"/></g><g filter="url(#iDQ1EMb)"><path class="iet_7ccmh"/></g><g filter="url(#iiT3Oie)"><path class="e04hi5blf"/><path fill="url(#iUzypYd)" class="ejdlxdbfz"/><path fill="url(#il13l3c)" class="ejdlxdbfz"/></g><g filter="url(#imQj8Ob)"><path class="xke9_jbxx"/><path fill="url(#ielUvae)" class="l076zdbne"/><path fill="url(#iyPJ08c)" class="l076zdbne"/></g><g filter="url(#iGIyRad)"><path stroke="url(#iSWK0Qc)" class="l8kp2p1za"/></g><g filter="url(#iSCdcrd)"><path class="ffa0d27qq"/></g><g filter="url(#ihq2jfc)"><path fill="url(#iIaY28c)" class="l9ayr0bea"/></g><g filter="url(#ix59Uad)"><path fill="url(#iM5YDEe)" clip-rule="evenodd" class="m840w_5cw"/><path fill="url(#iJTjnmb)" clip-rule="evenodd" class="m840w_5cw"/></g><defs><radialGradient id="iCvPZKd" cx="0" cy="0" r="1" gradientTransform="rotate(-126.573 19.833 7.02)scale(14.4752 12.6607)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="sa_c7ns7l"/><stop offset="1" class="xflvpmp1u"/></radialGradient><radialGradient id="iDDdakb" cx="0" cy="0" r="1" gradientTransform="matrix(6.9375 -5.375 4.67303 6.03148 5.7 25.631)" gradientUnits="userSpaceOnUse"><stop class="zhj208b_d"/><stop offset="1" class="y32ab_wii"/></radialGradient><radialGradient id="iHN7Z7x" cx="0" cy="0" r="1" gradientTransform="matrix(-.60337 4.55908 -5.69522 -.75373 15.705 13.085)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="w9gpkna4y"/><stop offset="1" class="xvq3mubqy"/></radialGradient><radialGradient id="inlchNW" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88301 1.94432 -2.5547 -3.78806 12.89 13.353)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="u3fmvdnwh"/><stop offset="1" class="ysga7wb0w"/></radialGradient><radialGradient id="i1rUuld" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.912 8.161)scale(2.15225 1.65263)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="jo-m975mj"/><stop offset="1" class="ecm2ecc2d"/></radialGradient><radialGradient id="iMSzrex" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 3.346 7.646)scale(2.47506 1.74346)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="ksj-40n4x"/><stop offset="1" class="qkj18_koj"/></radialGradient><radialGradient id="iHGtO2d" cx="0" cy="0" r="1" gradientTransform="rotate(62.272 4.153 11.598)scale(2.95399 4.10059)" gradientUnits="userSpaceOnUse"><stop class="bk_mrebvc"/><stop offset="1" class="o57gz703y"/></radialGradient><radialGradient id="iCiwxXx" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 9.966 6.825)scale(2.03849 2.84876)" gradientUnits="userSpaceOnUse"><stop class="g2m4aac5s"/><stop offset="1" class="tulkzacvs"/></radialGradient><radialGradient id="ik421ye" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.11855 -3.84482 23.516 9.733)" gradientUnits="userSpaceOnUse"><stop class="ii82yjbfl"/><stop offset="1" class="tobrp8lrd"/></radialGradient><radialGradient id="iEzj9zb" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.647 7.987)scale(2.90248 3.69733)" gradientUnits="userSpaceOnUse"><stop class="gto3tpbjl"/><stop offset="1" class="k8ni71bqd"/></radialGradient><radialGradient id="iR5762n" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 12.98 -3.769)scale(2.80034 2.21491)" gradientUnits="userSpaceOnUse"><stop class="j6tbtfb5n"/><stop offset="1" class="u7ezkxzae"/></radialGradient><radialGradient id="ia1j8od" cx="0" cy="0" r="1" gradientTransform="matrix(1.50392 .15775 -.2556 2.43678 9.865 9.697)" gradientUnits="userSpaceOnUse"><stop class="r4e237cot"/><stop offset="1" class="ktpt3tb_i"/></radialGradient><radialGradient id="ivIthgd" cx="0" cy="0" r="1" gradientTransform="rotate(-102.748 14.173 -3.915)scale(3.79787 1.37073)" gradientUnits="userSpaceOnUse"><stop class="fyy3crxae"/><stop offset="1" class="x7431zb1g"/></radialGradient><radialGradient id="iTIwBqe" cx="0" cy="0" r="1" gradientTransform="rotate(155.653 10.152 15.733)scale(12.2796 19.1721)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="vc--wpv5i"/><stop offset="1" class="iaefxbcet"/></radialGradient><radialGradient id="iAO2btb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.09375 1.15624 -3.57275 -6.46962 12.762 28.007)" gradientUnits="userSpaceOnUse"><stop offset=".045" class="v9-8bpxan"/><stop offset="1" class="p5ii0k_1a"/></radialGradient><radialGradient id="iJTDZBA" cx="0" cy="0" r="1" gradientTransform="matrix(-3.625 0 0 -3.8125 9.856 24.163)" gradientUnits="userSpaceOnUse"><stop offset=".302" class="tv57cl-9q"/><stop offset="1" class="nof2xyhhe"/></radialGradient><radialGradient id="iNXjvJd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.26562 -1.93554 2.61071 -1.7071 23.356 25.8)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="l9b4opb5t"/><stop offset=".919" class="uaxm8f1hq"/></radialGradient><radialGradient id="iLiUiRd" cx="0" cy="0" r="1" gradientTransform="rotate(155.556 9.638 14.63)scale(1.32158 .2597)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="z3hpt3mcq"/><stop offset="1" class="pzpwlzysi"/></radialGradient><radialGradient id="iGGVcnc" cx="0" cy="0" r="1" gradientTransform="matrix(.42186 -1.97502 3.24628 .6934 21.763 27.303)" gradientUnits="userSpaceOnUse"><stop offset=".705" class="l9b4opb5t"/><stop offset=".989" class="uaxm8f1hq"/></radialGradient><radialGradient id="iXIEzMd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1139 -.45312 .07627 -.1875 23.728 26.866)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="z3hpt3mcq"/><stop offset="1" class="pzpwlzysi"/></radialGradient><radialGradient id="i5jaAiH" cx="0" cy="0" r="1" gradientTransform="matrix(-6.95206 -2.46677 3.46444 -9.76378 21.531 21.584)" gradientUnits="userSpaceOnUse"><stop class="qvobj7b6r"/><stop offset="1" class="zrr9gv88m"/></radialGradient><radialGradient id="ihnSOpb" cx="0" cy="0" r="1" gradientTransform="matrix(.0287 2.22817 -1.66026 .02139 16.73 16.634)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="shkcotbtg"/><stop offset="1" class="x5158qbnu"/></radialGradient><radialGradient id="iklVAse" cx="0" cy="0" r="1" gradientTransform="rotate(166.131 7.032 8.964)scale(4.1718 1.60441)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="gus-gbb9t"/><stop offset="1" class="uubrgfq8x"/></radialGradient><radialGradient id="iZBVQGe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07223 -.6455 .5202 -.8641 22.585 20.807)" gradientUnits="userSpaceOnUse"><stop class="ov1bd0bys"/><stop offset="1" class="a0i9ffblh"/><stop offset="1" class="i829wfr2g"/></radialGradient><radialGradient id="igW1ABb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.8125 -.67275 0 14.336 16.7)" gradientUnits="userSpaceOnUse"><stop class="ysbaxhbyq"/><stop offset="1" class="x15soc1he"/></radialGradient><radialGradient id="i99L1zp" cx="0" cy="0" r="1" gradientTransform="rotate(30.491 -40.734 35.885)scale(7.14423 9.27511)" gradientUnits="userSpaceOnUse"><stop offset=".06" class="a805jtb_d"/><stop offset=".81" class="mpfjlio6c"/></radialGradient><radialGradient id="ifSsiqe" cx="0" cy="0" r="1" gradientTransform="rotate(-56.82 28.171 4.91)scale(2.3126 3.1193)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="l9b4opb5t"/><stop offset=".919" class="uaxm8f1hq"/></radialGradient><radialGradient id="iO9MJMe" cx="0" cy="0" r="1" gradientTransform="matrix(-.42043 -1.9751 3.23141 -.68786 10.244 27.303)" gradientUnits="userSpaceOnUse"><stop offset=".609" class="o9qsnlb6c"/><stop offset=".948" class="pcz4s2bal"/></radialGradient><radialGradient id="imMMNxc" cx="0" cy="0" r="1" gradientTransform="rotate(141.833 1.315 11.8)scale(1.27689)" gradientUnits="userSpaceOnUse"><stop class="b4of-6bao"/><stop offset="1" class="r3y-39nqq"/></radialGradient><radialGradient id="ivygAUc" cx="0" cy="0" r="1" gradientTransform="rotate(90 -5.427 14.595)scale(1.25098)" gradientUnits="userSpaceOnUse"><stop offset=".55" class="d5fabsakk"/><stop offset="1" class="ndghkrcwe"/></radialGradient><radialGradient id="iAAvyQb" cx="0" cy="0" r="1" gradientTransform="matrix(1.17188 .58594 -.45305 .9061 .052 .516)" gradientUnits="userSpaceOnUse"><stop class="n0n4e7bnh"/><stop offset="1" class="jm8e13_st"/></radialGradient><radialGradient id="iH86wby" cx="0" cy="0" r="1" gradientTransform="matrix(.66407 -1.01563 1.1175 .73068 .52 1.063)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="yhk8aqbmk"/><stop offset="1" class="zxvvm-hti"/></radialGradient><radialGradient id="iMg4SFb" cx="0" cy="0" r="1" gradientTransform="rotate(139.138 1.351 12.655)scale(1.3016)" gradientUnits="userSpaceOnUse"><stop class="eatp636hk"/><stop offset="1" class="tgwkdpbql"/></radialGradient><radialGradient id="izM6NXd" cx="0" cy="0" r="1" gradientTransform="matrix(1 1.07031 -1.1661 1.0895 .298 .379)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="zl4k6m5yt"/><stop offset="1" class="j9i7xp3bx"/></radialGradient><radialGradient id="iGbM8pb" cx="0" cy="0" r="1" gradientTransform="matrix(1.07812 -.64844 .589 .9793 .391 .926)" gradientUnits="userSpaceOnUse"><stop offset=".29" class="tqblnl2vv"/><stop offset=".964" class="kv9fthb_h"/></radialGradient><radialGradient id="igbw8Ed" cx="0" cy="0" r="1" gradientTransform="rotate(69.815 -10.366 19.366)scale(2.04763 .82994)" gradientUnits="userSpaceOnUse"><stop class="z87kcgb7t"/><stop offset=".853" class="r_s898b6a"/></radialGradient><radialGradient id="ilgojKb" cx="0" cy="0" r="1" gradientTransform="rotate(67.353 -9.288 20.22)scale(4.0633 .80773)" gradientUnits="userSpaceOnUse"><stop class="i7kjncbis"/><stop offset="1" class="wkalc4bst"/></radialGradient><radialGradient id="iRZ8lcb" cx="0" cy="0" r="1" gradientTransform="matrix(1.97895 1.21874 -.15017 .24384 9.48 23.006)" gradientUnits="userSpaceOnUse"><stop class="ddg3g7pcd"/><stop offset="1" class="ejr-khbri"/></radialGradient><radialGradient id="iAjYCLK" cx="0" cy="0" r="1" gradientTransform="rotate(-118.794 14.173 9.222)scale(2.33566 5.83179)" gradientUnits="userSpaceOnUse"><stop offset=".268" class="isiq9yb3m"/><stop offset="1" class="uq7zq9b9u"/></radialGradient><radialGradient id="iejaO7b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12499 1.3125 -.4864 -.4169 14.278 24.803)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="ehlybtbyr"/><stop offset="1" class="pbh041bmy"/></radialGradient><radialGradient id="i8u60Kc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.64063 -.62499 .30595 -.80313 14.31 24.585)" gradientUnits="userSpaceOnUse"><stop class="u3ly29i0x"/><stop offset="1" class="k1xxa4bqz"/></radialGradient><radialGradient id="iss2TEd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03126 2.5625 -1.3029 -.52434 21.528 21.803)" gradientUnits="userSpaceOnUse"><stop class="rau9skumu"/><stop offset="1" class="obmju7b-z"/></radialGradient><radialGradient id="iRjoLDc" cx="0" cy="0" r="1" gradientTransform="matrix(-.67188 .51562 -.16532 -.21542 23.294 22.71)" gradientUnits="userSpaceOnUse"><stop class="m92tte26k"/><stop offset="1" class="ty1ewib_q"/></radialGradient><radialGradient id="i1prXNb" cx="0" cy="0" r="1" gradientTransform="matrix(.58243 3.00041 -1.02662 .19928 19.588 20.723)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="l33l9dqgq"/><stop offset="1" class="fjji9zbbw"/></radialGradient><radialGradient id="iNabhlb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03124 2.3125 -1.56386 -.69739 16.794 21.288)" gradientUnits="userSpaceOnUse"><stop class="wh23x9bjk"/><stop offset="1" class="wsyd1pyom"/></radialGradient><radialGradient id="ilxZkoV" cx="0" cy="0" r="1" gradientTransform="matrix(-1.96008 .75001 -.74136 -1.93748 19.285 22.975)" gradientUnits="userSpaceOnUse"><stop class="wh23x9bjk"/><stop offset="1" class="wsyd1pyom"/></radialGradient><radialGradient id="iVx6omb" cx="0" cy="0" r="1" gradientTransform="rotate(111.14 1.308 16.634)scale(6.15203 6.32964)" gradientUnits="userSpaceOnUse"><stop class="hr9jc16ta"/><stop offset="1" class="f_r_72dts"/></radialGradient><radialGradient id="i2VnJod" cx="0" cy="0" r="1" gradientTransform="matrix(-.8047 .60938 -.52546 -.69388 16.387 23.85)" gradientUnits="userSpaceOnUse"><stop class="ifzr0vvcb"/><stop offset=".808" class="he14dbbbc"/></radialGradient><radialGradient id="ibMQltn" cx="0" cy="0" r="1" gradientTransform="matrix(.17187 -1.1 1.36133 .2127 15.731 25.237)" gradientUnits="userSpaceOnUse"><stop offset=".039" class="xo240subg"/><stop offset="1" class="ruz641x6w"/></radialGradient><radialGradient id="idEoiSb" cx="0" cy="0" r="1" gradientTransform="matrix(-.6537 -1.20346 1.36368 -.74073 10.928 12.193)" gradientUnits="userSpaceOnUse"><stop class="wlzou1bho"/><stop offset="1" class="muarw1mje"/></radialGradient><radialGradient id="i7c8OuK" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 20.047 11.023)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="xqzyuky4n"/><stop offset="1" class="yiz6fvgdb"/></radialGradient><radialGradient id="iznxtrb" cx="0" cy="0" r="1" gradientTransform="matrix(1.20681 0 0 .5196 20.951 8.878)" gradientUnits="userSpaceOnUse"><stop class="v4cuahbfk"/><stop offset="1" class="ame5l9u0o"/></radialGradient><radialGradient id="iZjYKpb" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 20.398 10.697)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="j_jb06m8v"/><stop offset="1" class="t9v208shd"/></radialGradient><radialGradient id="i3JWWAe" cx="0" cy="0" r="1" gradientTransform="rotate(180 5.703 5.292)scale(1.05596)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="w5re42dqy"/><stop offset="1" class="w4wkyodwa"/></radialGradient><radialGradient id="i626DLe" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 8.33 7.094)scale(7.16175 9.58588)" gradientUnits="userSpaceOnUse"><stop class="ox3481l0h"/><stop offset="1" class="l65mx1yct"/></radialGradient><radialGradient id="ipzaOIe" cx="0" cy="0" r="1" gradientTransform="rotate(156.249 7.843 7.34)scale(2.38203 1.65881)" gradientUnits="userSpaceOnUse"><stop class="vw42v6b3v"/><stop offset="1" class="v5m4qhb2r"/></radialGradient><radialGradient id="iV9IKCe" cx="0" cy="0" r="1" gradientTransform="matrix(1.28915 -3.92836 4.98436 1.6357 13.845 16.555)" gradientUnits="userSpaceOnUse"><stop class="hl813wbpa"/><stop offset="1" class="a21bmlbcx"/></radialGradient><radialGradient id="igwKlYd" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.08631 -8.8578 0 15.745 9.918)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="fa0q4x0wh"/><stop offset=".955" class="vfgk4hb_x"/></radialGradient><radialGradient id="ioOsIGd" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.336 6.755)scale(7.03739 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="qh0bdqbav"/><stop offset="1" class="dt7ct4boy"/></radialGradient><radialGradient id="iV5lRBe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.308 9.629)" gradientUnits="userSpaceOnUse"><stop class="azt-9rbtm"/><stop offset="1" class="ci16jsbol"/></radialGradient><radialGradient id="i4RIxJe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 13.93 9.4)" gradientUnits="userSpaceOnUse"><stop class="zemyxxbjg"/><stop offset="1" class="k1zv-ubmt"/></radialGradient><radialGradient id="i2Nt9Cc" cx="0" cy="0" r="1" gradientTransform="matrix(-.87016 3.22674 -2.58193 -.69627 17.39 7.313)" gradientUnits="userSpaceOnUse"><stop class="aotu-xwil"/><stop offset="1" class="izc7dk1pl"/></radialGradient><radialGradient id="isdXSUb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28528 0 0 -6.44557 21.102 11.116)" gradientUnits="userSpaceOnUse"><stop class="fyxppic9g"/><stop offset="1" class="kq5b787yl"/></radialGradient><radialGradient id="iwAf7le" cx="0" cy="0" r="1" gradientTransform="matrix(-.45554 -2.04401 .62995 -.1404 16.793 11.842)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="ab1vgh_ru"/><stop offset="1" class="f80hfjhpj"/></radialGradient><radialGradient id="iAD6Gtc" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.2179 16.552 12.055)" gradientUnits="userSpaceOnUse"><stop class="hjp773b9j"/><stop offset="1" class="wh0vrhbzi"/></radialGradient><radialGradient id="i99tAud" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.189 9.987)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i0qY0Sc" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 17.96 10.071)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i3A2fDE" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.825 9.987)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iECormb" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.793 -1.56)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iUzypYd" cx="0" cy="0" r="1" gradientTransform="rotate(-65.391 11.302 -4.128)scale(3.03069 1.55043)" gradientUnits="userSpaceOnUse"><stop class="gaydocc3b"/><stop offset="1" class="o5ryhdc_j"/></radialGradient><radialGradient id="il13l3c" cx="0" cy="0" r="1" gradientTransform="matrix(1.14952 -1.97524 1.06043 .61714 12.056 6.886)" gradientUnits="userSpaceOnUse"><stop class="bkfqk3fbn"/><stop offset="1" class="hrqlkdbpd"/></radialGradient><radialGradient id="ielUvae" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 8.123 6.962)scale(4.8729 7.96691)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ukea7pdhy"/><stop offset="1" class="wuqjd3b5z"/></radialGradient><radialGradient id="iyPJ08c" cx="0" cy="0" r="1" gradientTransform="matrix(-.21033 1.3672 -2.94145 -.45252 16.218 3.028)" gradientUnits="userSpaceOnUse"><stop class="y3gk9pbvh"/><stop offset="1" class="j2p90_-bc"/><stop offset="1" class="ru9fl6bjc"/></radialGradient><radialGradient id="iJTjnmb" cx="0" cy="0" r="1" gradientTransform="rotate(118.072 9.667 8.588)scale(.92969 16.1409)" gradientUnits="userSpaceOnUse"><stop offset=".107" class="al0tyek2y"/><stop offset="1" class="nbz8snbyn"/></radialGradient><filter id="iibEHhb" width="21.944" height="26.818" x="4.962" y="3.225" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.952941 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3416"/></filter><filter id="ittMWNe" width="12.631" height="14.916" x="9.484" y="8.485" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.811765 0 0 0 0 0.807843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3416"/><feGaussianBlur result="effect2_foregroundBlur_4002_3416" stdDeviation=".05"/></filter><filter id="iIZkgEb" width="15.268" height="15.768" x="8.498" y="1.306" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.133333 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3416"/></filter><filter id="iwsiV4b" width="5.874" height="5.537" x="6.993" y="23.153" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3416" stdDeviation=".5"/></filter><filter id="ifvRmfl" width="4.979" height="4.054" x="18.51" y="24.756" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3416" stdDeviation=".5"/></filter><filter id="i9NVjNc" width="2.973" height="2.006" x="21.47" y="23.669" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3416"/></filter><filter id="iXpFLBc" width="3.281" height="2" x="20.468" y="25.305" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3416"/></filter><filter id="ieZyege" width="13.965" height="11.381" x="9.149" y="12.614" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.376471 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3416"/></filter><filter id="iXOj8hd" width="10.996" height="6.432" x="11.932" y="21.98" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3416" stdDeviation=".5"/></filter><filter id="ir6fqbK" width="2.973" height="2.006" x="7.658" y="23.669" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3416"/></filter><filter id="iqnXQPd" width="3.266" height="2" x="8.366" y="25.305" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3416"/></filter><filter id="iLYkfbc" width="6.218" height="6.789" x="8.343" y="20.002" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 0.227451 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3416"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".3"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.709804 0 0 0 0 0.141176 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3416" result="effect2_innerShadow_4002_3416"/></filter><filter id="iTQGwAb" width="6.218" height="6.639" x="17.574" y="20.002" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.239216 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3416"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.301961 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3416" result="effect2_innerShadow_4002_3416"/></filter><filter id="i8ekhhd" width="6.702" height="6.417" x="12.683" y="20.734" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.619608 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3416"/></filter><filter id="iIY7cxM" width="6.703" height="6.517" x="12.633" y="20.684" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3416" stdDeviation=".15"/></filter><filter id="iqvdfed" width="3.2" height="3.2" x="14.271" y="22.669" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3416" stdDeviation=".25"/></filter><filter id="iMZkESJ" width="2.35" height="2.35" x="14.893" y="23.037" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.521569 0 0 0 0 0.0823529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3416"/></filter><filter id="iWUdvtc" width="1.458" height="2.505" x="15.848" y="20.587" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3416" stdDeviation=".125"/></filter><filter id="iiuJxHe" width="1.723" height="1.924" x="16.94" y="24.431" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3416" stdDeviation=".125"/></filter><filter id="ir5Ojfc" width="1.368" height="2.217" x="18.104" y="22.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3416" stdDeviation=".125"/></filter><filter id="iEPfjbc" width="3.55" height="1.942" x="15.171" y="17.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3416" stdDeviation=".25"/></filter><filter id="iK4l8Od" width="3.368" height="3.218" x="9.712" y="8.975" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3416"/></filter><filter id="ia4YZPb" width="3.218" height="3.468" x="19.225" y="8.725" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.34902 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3416"/></filter><filter id="iCuT4Sx" width="3.148" height="3.148" x="19.26" y="9.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3416" stdDeviation=".25"/></filter><filter id="iPrruGc" width="2.848" height="2.848" x="9.916" y="9.16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3416" stdDeviation=".175"/></filter><filter id="ishpnwd" width="10.191" height="11.127" x="10.911" y="5.678" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3416"/></filter><filter id="iFPgJIb" width="2.877" height="3.682" x="14.406" y="9.579" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3416" stdDeviation=".25"/></filter><filter id="iTXCnKb" width="2.377" height="3.182" x="14.818" y="9.691" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3416" stdDeviation=".125"/></filter><filter id="iDxVJqp" width="3.702" height="1.526" x="14.156" y="12.932" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3416" stdDeviation=".05"/></filter><filter id="ik1Ox5c" width="3.001" height="1.286" x="16.949" y="9.18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.0705882 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3416"/></filter><filter id="iOWcp3d" width="3.001" height="1.286" x="12.064" y="9.18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3416"/></filter><filter id="iZi3Wbd" width="2.453" height="1.091" x="12.199" y="7.756" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3416"/></filter><filter id="isMhVye" width="2.453" height="1.091" x="17.616" y="7.756" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3416"/></filter><filter id="imWwVec" width=".787" height=".696" x="17.455" y="9.547" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3416" stdDeviation=".05"/></filter><filter id="i03ZMyc" width=".891" height=".913" x="18.295" y="9.622" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3416" stdDeviation=".1"/></filter><filter id="iFDBpFe" width=".986" height="1.04" x="13.852" y="9.559" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3416" stdDeviation=".1"/></filter><filter id="iZS6ire" width=".913" height=".704" x="13.097" y="9.54" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3416" stdDeviation=".05"/></filter><filter id="iREoSDe" width="2.261" height=".978" x="17.646" y="7.878" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3416" stdDeviation=".1"/></filter><filter id="iDQ1EMb" width="2.261" height=".978" x="12.195" y="7.878" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3416" stdDeviation=".1"/></filter><filter id="iiT3Oie" width="4.312" height="4.613" x="9.652" y="3.642" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.286275 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3416"/><feGaussianBlur result="effect2_foregroundBlur_4002_3416" stdDeviation=".2"/></filter><filter id="imQj8Ob" width="8.767" height="5.782" x="12.836" y="2.508" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.317647 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3416"/><feGaussianBlur result="effect2_foregroundBlur_4002_3416" stdDeviation=".125"/></filter><filter id="iGIyRad" width="1.145" height="2.31" x="12.816" y="3.742" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3416" stdDeviation=".1"/></filter><filter id="iSCdcrd" width="6.427" height="3.372" x="15.425" y="4.551" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3416" stdDeviation=".375"/></filter><filter id="ihq2jfc" width="8.285" height="5.027" x="14.004" y="3.042" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3416" stdDeviation=".5"/></filter><filter id="ix59Uad" width="15.448" height="4.54" x="8.283" y="2.475" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.694118 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3416"/></filter><linearGradient id="iRhATUd" x1="26.906" x2="11.7" y1="11.506" y2="21.506" gradientUnits="userSpaceOnUse"><stop class="fzn5p4bte"/><stop offset="1" class="mu5z5titl"/></linearGradient><linearGradient id="iZNna5d" x1="20.7" x2="10.387" y1="17.413" y2="17.413" gradientUnits="userSpaceOnUse"><stop class="ct82q_bbh"/><stop offset="1" class="gi1yleb5l"/></linearGradient><linearGradient id="ifIW2cc" x1="20.7" x2="14.565" y1="3.632" y2="14.393" gradientUnits="userSpaceOnUse"><stop class="ap760fb9g"/><stop offset="1" class="w1etxcbdz"/></linearGradient><linearGradient id="ifGtn7E" x1="14.887" x2="14.887" y1="30.882" y2="29.6" gradientUnits="userSpaceOnUse"><stop class="ujdq-6enc"/><stop offset="1" class="hpzv-ab9a"/></linearGradient><linearGradient id="ibzNNgf" x1="23.649" x2="21.867" y1="25.803" y2="24.393" gradientUnits="userSpaceOnUse"><stop class="t-y5i3b_t"/><stop offset="1" class="rsfcoybzb"/></linearGradient><linearGradient id="iYMYNDd" x1="22.95" x2="21.169" y1="27.387" y2="25.694" gradientUnits="userSpaceOnUse"><stop class="t-y5i3b_t"/><stop offset="1" class="rsfcoybzb"/></linearGradient><linearGradient id="ir1beic" x1="12.653" x2="13.255" y1="29.272" y2="28.928" gradientUnits="userSpaceOnUse"><stop class="jih6tvbze"/><stop offset="1" class="g22d_bc_z"/></linearGradient><linearGradient id="i3i4UVc" x1="7.856" x2="9.361" y1="24.287" y2="26.107" gradientUnits="userSpaceOnUse"><stop class="n1imc2b4i"/><stop offset="1" class="dz0-61bre"/></linearGradient><linearGradient id="i6g3Gsb" x1="9.062" x2="10.843" y1="27.387" y2="25.702" gradientUnits="userSpaceOnUse"><stop class="cnrgi8b1a"/><stop offset="1" class="y8qpet1tz"/></linearGradient><linearGradient id="i1ci7sc" x1="14.919" x2="16.7" y1="27.151" y2="22.882" gradientUnits="userSpaceOnUse"><stop class="i1hqu4kst"/><stop offset="1" class="k_kfijbew"/></linearGradient><linearGradient id="iCWVGpM" x1="13.356" x2="16.981" y1="22.913" y2="23.6" gradientUnits="userSpaceOnUse"><stop offset=".039" class="felc_fb-i"/><stop offset="1" class="wa496n4py"/></linearGradient><linearGradient id="is9mttb" x1="17.231" x2="16.325" y1="26.913" y2="25.163" gradientUnits="userSpaceOnUse"><stop offset=".039" class="felc_fb-i"/><stop offset="1" class="wa496n4py"/></linearGradient><linearGradient id="itrE8mc" x1="16.477" x2="16.477" y1="20.834" y2="22.842" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset=".214" class="e-0jmrbwd"/><stop offset=".739" class="e-0jmrbwd"/><stop offset="1" class="uy9-hlbji"/></linearGradient><linearGradient id="iHkRXXc" x1="17.286" x2="18.153" y1="24.889" y2="26.092" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset="0" class="gn67s1beu"/><stop offset=".739" class="gn67s1beu"/><stop offset="1" class="o38c5rykb"/></linearGradient><linearGradient id="i1eDidc" x1="18.728" x2="18.728" y1="22.421" y2="24.038" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset=".214" class="e-0jmrbwd"/><stop offset=".739" class="e-0jmrbwd"/><stop offset="1" class="uy9-hlbji"/></linearGradient><linearGradient id="ixpM4OI" x1="16.132" x2="20.117" y1="19.033" y2="17.861" gradientUnits="userSpaceOnUse"><stop class="b63i8aczf"/><stop offset="1" class="v85e7pbqp"/></linearGradient><linearGradient id="iyajRsp" x1="9.712" x2="11.569" y1="10.671" y2="10.671" gradientUnits="userSpaceOnUse"><stop class="cg1k0hirj"/><stop offset="1" class="u6m78ac0i"/></linearGradient><linearGradient id="i4cPYue" x1="15.068" x2="16.007" y1="11.916" y2="11.916" gradientUnits="userSpaceOnUse"><stop class="hm31m3bmo"/><stop offset="1" class="vh12xwf7a"/></linearGradient><linearGradient id="iMwelne" x1="16.007" x2="16.007" y1="12.623" y2="11.996" gradientUnits="userSpaceOnUse"><stop class="us3ue9b4r"/><stop offset="1" class="hxr-reb3g"/></linearGradient><linearGradient id="igkfldb" x1="14.943" x2="15.404" y1="14.124" y2="13.412" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="icJnqab" x1="18.967" x2="18.653" y1="10.041" y2="10.234" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iAMBL9d" x1="14.569" x2="14.255" y1="10.041" y2="10.235" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iSWK0Qc" x1="12.898" x2="13.388" y1="3.632" y2="4.897" gradientUnits="userSpaceOnUse"><stop class="olrv_cchi"/><stop offset="1" class="lwhsndh-i"/></linearGradient><linearGradient id="iIaY28c" x1="20.633" x2="13.008" y1="6.913" y2="4.632" gradientUnits="userSpaceOnUse"><stop class="i9gm5zb8o"/><stop offset="1" class="h1uzyzypo"/></linearGradient><linearGradient id="iM5YDEe" x1="20.481" x2="8.544" y1="3.662" y2="7.35" gradientUnits="userSpaceOnUse"><stop class="muovvys4e"/><stop offset="1" class="bvsk-i9dj"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-with-veil-medium" /></template>
<style>
.a0i9ffblh {
  stop-color: var(--svg-color--7c4f3f, #7C4F3F);
  stop-opacity: 0;
}

.a21bmlbcx {
  stop-color: var(--svg-color--945a73, #945A73);
  stop-opacity: 0;
}

.a3tjcx75t {
  fill: var(--svg-color--000, #000);
  d: path("M17.68 10.403a.51.51 0 0 1 .511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.235");
}

.a5usbva2v {
  d: path("M18.19 9.51a.893.893 0 0 1 .86 1.128h-1.723a.896.896 0 0 1 .864-1.128");
}

.a805jtb_d {
  stop-color: var(--svg-color--365c3e, #365C3E);
}

.ab1vgh_ru {
  stop-color: var(--svg-color--cda38b, #CDA38B);
}

.al0tyek2y {
  stop-color: var(--svg-color--f2f1f2, #F2F1F2);
}

.ame5l9u0o {
  stop-color: var(--svg-color--906d53, #906D53);
  stop-opacity: 0;
}

.aotu-xwil {
  stop-color: var(--svg-color--ab8179, #AB8179);
}

.ap760fb9g {
  stop-color: var(--svg-color--6d524e, #6D524E);
}

.azt-9rbtm {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
}

.b4of-6bao {
  stop-color: var(--svg-color--e5d7d2, #E5D7D2);
}

.b63i8aczf {
  stop-color: var(--svg-color--c49987, #C49987);
}

.b84xurbwm {
  d: path("M11.39 25.819c-.678-.6-1.716-.535-2.298.112l-.69.734c-.062.068-.04.22.024.27c.91.563 1.996.493 2.66-.27l.42-.583a.11.11 0 0 0-.009-.15z");
}

.bk_mrebvc {
  stop-color: var(--svg-color--554543, #554543);
}

.bkfqk3fbn {
  stop-color: var(--svg-color--4b2839, #4B2839);
}

.bvsk-i9dj {
  stop-color: var(--svg-color--cdc8ce, #CDC8CE);
}

.cg1k0hirj {
  stop-color: var(--svg-color--8d645f, #8D645F);
}

.ci16jsbol {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnrgi8b1a {
  stop-color: var(--svg-color--58843a, #58843A);
}

.ct82q_bbh {
  stop-color: var(--svg-color--cac2c0, #CAC2C0);
}

.d5fabsakk {
  stop-color: var(--svg-color--d7cfcf, #D7CFCF);
  stop-opacity: 0;
}

.dbns8_byb {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m17.348 24.803l.907 1.18");
}

.ddg3g7pcd {
  stop-color: var(--svg-color--cb5996, #CB5996);
}

.dq75q8bft {
  d: path("M9.984 15.866c0-4.854 2.694-7.28 6.016-7.28s6.016 2.323 6.016 7.28v7.436H9.984z");
}

.dt7ct4boy {
  stop-color: var(--svg-color--9a7267, #9A7267);
}

.dwa5ppott {
  fill: var(--svg-color--aaaeae, #AAAEAE);
  d: path("M19.688 25.985c.78-.46 1.787-.2 2.235.545l.538.851c.048.079.043.218-.074.262c-1 .38-2.053.104-2.561-.77l-.302-.652a.11.11 0 0 1 .037-.145z");
}

.dz0-61bre {
  stop-color: var(--svg-color--487a38, #487A38);
}

.e-0jmrbwd {
  stop-color: var(--svg-color--fff967, #FFF967);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e04hi5blf {
  fill: var(--svg-color--49302e, #49302E);
  d: path("M10.938 4.596c.566-.6 1.636-.6 2.13-.51l.396 1.29c-.253-.04-.295-.002-.485.183c-.137 1.093-1.376 1.756-2.886 2.197c-.149-1.492.109-2.38.845-3.16");
}

.eatp636hk {
  stop-color: var(--svg-color--eee1dd, #EEE1DD);
}

.ecm2ecc2d {
  stop-color: var(--svg-color--27141e, #27141E);
  stop-opacity: 0;
}

.ehlybtbyr {
  stop-color: var(--svg-color--af3465, #AF3465);
}

.ejdlxdbfz {
  d: path("M10.938 4.596c.566-.6 1.636-.6 2.13-.51l.396 1.29c-.253-.04-.295-.002-.485.183c-.137 1.093-1.376 1.756-2.886 2.197c-.149-1.492.109-2.38.845-3.16");
}

.ejr-khbri {
  stop-color: var(--svg-color--cb5996, #CB5996);
  stop-opacity: 0;
}

.emxl68qul {
  d: path("M15.993 25.237a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.enqe5037q {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.007 13.496c-.52 0-1.01-.126-1.422-.345c-.14-.073-.291.089-.203.22a1.932 1.932 0 0 0 3.25 0c.088-.136-.063-.293-.203-.22c-.412.22-.896.345-1.422.345Z");
}

.f_r_72dts {
  stop-color: var(--svg-color--facc4a, #FACC4A);
}

.f80hfjhpj {
  stop-color: var(--svg-color--cda38b, #CDA38B);
  stop-opacity: 0;
}

.fa0q4x0wh {
  stop-color: var(--svg-color--8d5e67, #8D5E67);
  stop-opacity: 0;
}

.fayzwvhye {
  fill: var(--svg-color--7e555a, #7E555A);
  d: path("M11.34 11.659a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.felc_fb-i {
  stop-color: var(--svg-color--ecb12a, #ECB12A);
}

.ffa0d27qq {
  fill: var(--svg-color--664a4a, #664A4A);
  d: path("m18.413 6.404l-1.425.262a.688.688 0 1 1-.125-1.365h2.34c1.385 0 1.843 1.395 1.9 1.872a3.15 3.15 0 0 0-2.69-.77");
}

.fhzxtua6p {
  d: path("M20.61 25.819c.678-.6 1.716-.535 2.297.112l.69.734c.063.068.083.205-.023.27c-.91.563-1.996.493-2.66-.27l-.42-.583a.11.11 0 0 1 .009-.15z");
}

.fjji9zbbw {
  stop-color: var(--svg-color--e16fa7, #E16FA7);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fto_-78ii {
  fill: var(--svg-color--88555f, #88555F);
  d: path("m15.614 10.362l-.683 1.7a.54.54 0 0 0 .52.699h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.493-.376-.613 0");
}

.fyxppic9g {
  stop-color: var(--svg-color--c0967a, #C0967A);
}

.fyy3crxae {
  stop-color: var(--svg-color--3e2125, #3E2125);
}

.fzn5p4bte {
  stop-color: var(--svg-color--e7dedd, #E7DEDD);
}

.g_7ofss0n {
  fill: var(--svg-color--000, #000);
  d: path("M14.334 10.403a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .061-.235");
}

.g22d_bc_z {
  stop-color: var(--svg-color--416b43, #416B43);
  stop-opacity: 0;
}

.g2m4aac5s {
  stop-color: var(--svg-color--6e5350, #6E5350);
}

.gaydocc3b {
  stop-color: var(--svg-color--5c4643, #5C4643);
}

.gbn28d8fq {
  d: path("M11.321 12.193a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.gg1o4rtuc {
  d: path("M18.125 9.699c.064.085-.07.189-.22.302c-.151.113-.263.192-.327.107s.007-.245.159-.358c.15-.113.325-.136.388-.051");
}

.ghnhmfcab {
  d: path("M20.834 12.193a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.gi1yleb5l {
  stop-color: var(--svg-color--aca4a1, #ACA4A1);
}

.gn67s1beu {
  stop-color: var(--svg-color--ffef65, #FFEF65);
}

.gto3tpbjl {
  stop-color: var(--svg-color--564544, #564544);
}

.gus-gbb9t {
  stop-color: var(--svg-color--824c53, #824C53);
}

.gybevs2rv {
  d: path("M13.823 9.51a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.893");
}

.h1uzyzypo {
  stop-color: var(--svg-color--452837, #452837);
  stop-opacity: 0;
}

.h8u9xcqom {
  cx: 13.553px;
  cy: 9.892px;
  rx: 0.39px;
  ry: 0.197px;
}

.he14dbbbc {
  stop-color: var(--svg-color--f38330, #F38330);
}

.hjp773b9j {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
}

.hl813wbpa {
  stop-color: var(--svg-color--945a73, #945A73);
}

.hm31m3bmo {
  stop-color: var(--svg-color--875f54, #875F54);
}

.hpzv-ab9a {
  stop-color: var(--svg-color--d2cfd8, #D2CFD8);
  stop-opacity: 0;
}

.hr9jc16ta {
  stop-color: var(--svg-color--ffe24b, #FFE24B);
}

.hrqlkdbpd {
  stop-color: var(--svg-color--4b2839, #4B2839);
  stop-opacity: 0;
}

.hslc4mdnn {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.616 9.238c-.653 0-1.205.45-1.355 1.06c-.044.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.371-1.128");
}

.hsr3pf4ww {
  d: path("M9.15 20.477a11.2 11.2 0 0 1 4.31-2.048c.28-.06.48-.32.48-.61v-3.145c0-1.13.9-2.04 2.02-2.06c1.16-.02 2.1.95 2.1 2.1v3.105c0 .29.2.54.48.61a11.3 11.3 0 0 1 4.325 2.063a8.44 8.44 0 0 1-6.852 3.503a8.44 8.44 0 0 1-6.864-3.518");
}

.hxr-reb3g {
  stop-color: var(--svg-color--995c76, #995C76);
  stop-opacity: 0;
}

.hy-w2u91k {
  cx: 9.168px;
  cy: 20.511px;
  r: 0.762px;
}

.i1hqu4kst {
  stop-color: var(--svg-color--ca992e, #CA992E);
}

.i7kjncbis {
  stop-color: var(--svg-color--d35897, #D35897);
}

.i829wfr2g {
  stop-color: var(--svg-color--8b604a, #8B604A);
  stop-opacity: 0;
}

.i9gm5zb8o {
  stop-color: var(--svg-color--452837, #452837);
}

.iaefxbcet {
  stop-color: var(--svg-color--c9c5cd, #C9C5CD);
}

.ib72tsbrb {
  d: path("M12.712 23.184c.15-.67.84-1.06 1.5-.85l.62.211a.05.05 0 0 0 .066-.05l-.03-.485c-.06-.67.41-1.266 1.09-1.276c.69-.01 1.18.526 1.18 1.25v.561a.05.05 0 0 0 .066.047l.55-.187c.64-.24 1.31.059 1.49.729c.17.65-.214 1.374-.884 1.494l-.457.1a.05.05 0 0 0-.03.079l.307.422c.44.52.34 1.32-.22 1.71s-1.296.193-1.67-.36l-.31-.413a.05.05 0 0 0-.081.003l-.242.375c-.32.59-1.08.79-1.65.42c-.58-.37-.71-1.16-.29-1.7l.357-.526a.05.05 0 0 0-.032-.078l-.37-.066c-.67-.1-1.11-.75-.96-1.41");
}

.ibjr3phds {
  cx: 13.553px;
  cy: 9.892px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.iet_7ccmh {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.156 8.212c-.323-.079-1.125-.04-1.661.344");
}

.iez_ribyj {
  cx: 10.18px;
  cy: 21.589px;
  r: 0.762px;
}

.ifzr0vvcb {
  stop-color: var(--svg-color--ffad67, #FFAD67);
}

.ii82yjbfl {
  stop-color: var(--svg-color--604947, #604947);
}

.inqzkd-7z {
  fill: var(--svg-color--3f6834, #3F6834);
  d: path("M21.819 23.42c.096.053.144.219.081.348l-.668 1.39c-.181.388-.526.926-.809 1.177c-.687.638-1.466.646-2.21.3a2.4 2.4 0 0 1-.481-.291a.97.97 0 0 1-.407.892c-.466.325-1.079.16-1.39-.3l-.258-.344a.042.042 0 0 0-.068.003l-.201.312a.965.965 0 0 1-1.374.35a.97.97 0 0 1-.241-1.415l.298-.438a.042.042 0 0 0-.027-.065l-.308-.055a.97.97 0 0 1-.799-1.173a.97.97 0 0 1 1.248-.708l.516.176a.042.042 0 0 0 .055-.042l-.025-.403c-.05-.558.514 1.048 1.08 1.04c.574-.009.81-1.664.81-1.062v.467c0 .028.028.049.055.04l.458-.157q.112-.042.223-.058l.036-.084l1.043.854c.063-.13.19-.198.295-.153c.711.328.494-.416.288.729c-.022.122.015.129.098.029c.74-.9 1.97-1.695 2.682-1.36");
}

.iqtiw5vmo {
  d: path("m20.799 26.313l-2.71-1.12l.67-1.62c.41-1 1.1-1.691 1.987-2.11c.466-.19.718.059.798.239c.3.82.081 2.137-.085 3.001z");
}

.isiq9yb3m {
  stop-color: var(--svg-color--c46399, #C46399);
}

.izc7dk1pl {
  stop-color: var(--svg-color--ab8179, #AB8179);
  stop-opacity: 0;
}

.j_jb06m8v {
  stop-color: var(--svg-color--a26d62, #A26D62);
  stop-opacity: 0;
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j6tbtfb5n {
  stop-color: var(--svg-color--5f4846, #5F4846);
}

.j9i7xp3bx {
  stop-color: var(--svg-color--cdc7c8, #CDC7C8);
}

.jih6tvbze {
  stop-color: var(--svg-color--3e5d50, #3E5D50);
}

.jm8e13_st {
  stop-color: var(--svg-color--e1d6d3, #E1D6D3);
}

.jo-m975mj {
  stop-color: var(--svg-color--27141e, #27141E);
}

.k_kfijbew {
  stop-color: var(--svg-color--ca992e, #CA992E);
  stop-opacity: 0;
}

.k1xxa4bqz {
  stop-color: var(--svg-color--af246b, #AF246B);
  stop-opacity: 0;
}

.k1zv-ubmt {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
  stop-opacity: 0;
}

.k5ieljw3s {
  d: path("M10.92 9.322h.012l-.01-.265l-.01-.306c.02-.95.574-1.317.81-1.44q.024-.007.05-.02l.052-.02a2.3 2.3 0 0 0 1.19-1.234l.082-.194a.264.264 0 0 1 .461-.051a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.082.087 1.135 1.332l-.119 3.073c-.123 2.803-2.311 4.685-4.983 4.685s-4.86-1.882-4.983-4.685z");
}

.k7l2qd3fg {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.398 9.238c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.371-1.128");
}

.k8ni71bqd {
  stop-color: var(--svg-color--564544, #564544);
  stop-opacity: 0;
}

.knk8j3xyr {
  fill: var(--svg-color--9b9da0, #9B9DA0);
  d: path("M9.134 24.156c.879-.052 1.658.636 1.72 1.534l.009.116c.31.043.61.174.862.397l.107.113a.11.11 0 0 1 .01.15l-.42.583c-.665.762-1.75.833-2.66.27c-.064-.05-.086-.202-.024-.27l.69-.734a1.6 1.6 0 0 1 .302-.26c-.906-.06-1.574-.75-1.735-1.634c-.013-.049.028-.207.15-.207z");
}

.knn4fxbsm {
  d: path("m11.186 26.313l2.71-1.12l-.67-1.62c-.41-1-1.1-1.691-1.988-2.11c-.465-.19-.717.059-.797.239c-.3.82-.081 2.137.085 3.001z");
}

.kq5b787yl {
  stop-color: var(--svg-color--c0967a, #C0967A);
  stop-opacity: 0;
}

.ksj-40n4x {
  stop-color: var(--svg-color--230c14, #230C14);
}

.ktpt3tb_i {
  stop-color: var(--svg-color--56413d, #56413D);
  stop-opacity: 0;
}

.kv9fthb_h {
  stop-color: var(--svg-color--dfc7b5, #DFC7B5);
}

.kxmcwkltc {
  fill-rule: evenodd;
  d: path("M23.192 11.994c.213-.435.324-.92.324-1.427c0-.467-.096-.906-.269-1.305h.006a3 3 0 0 0-.282-.513l-.002-.004a3.24 3.24 0 0 1-.526-1.77v-.01a3.3 3.3 0 0 0-3.299-3.3a.54.54 0 0 1-.455-.233a3.3 3.3 0 0 0-2.682-1.376a3.3 3.3 0 0 0-2.682 1.376a.56.56 0 0 1-.455.233l-.085.001A3.3 3.3 0 0 0 9.57 6.964v.01a3.24 3.24 0 0 1-.526 1.771l-.002.004a3.3 3.3 0 0 0-.22 3.245a.52.52 0 0 1 0 .455a3.213 3.213 0 0 0 2.894 4.625h8.582a3.213 3.213 0 0 0 3.218-3.218c0-.506-.121-.982-.324-1.407a.52.52 0 0 1 0-.455m-12.26-2.672h-.012l1.198 2.355c.124 2.803 1.217 0 3.889 0s3.836 3.12 3.96.317l1.135-3.197c-.053-1.245-.956-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.189-1.674a.264.264 0 0 0-.461.051l-.082.194a2.3 2.3 0 0 1-1.19 1.235l-.051.02l-.051.02c-.236.123-.79.49-.81 1.44l.01.305z");
}

.l076zdbne {
  d: path("M15.404 2.794c-1.133-.25-2.15.88-2.267 1.299c1.051 3.545 3.712 3.35 6.34 3.058c1.572-.174 1.743.542 1.877.889c0-3.933-3.344-4.671-5.922-5.24z");
}

.l33l9dqgq {
  stop-color: var(--svg-color--e16fa7, #E16FA7);
}

.l65mx1yct {
  stop-color: var(--svg-color--946568, #946568);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l8kp2p1za {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.116 4.042c.023.244.234 1.157.545 1.71");
}

.l9ayr0bea {
  d: path("M21.29 7.07c-.826-2.725-3.536-3.278-6.286-2.938c2.75.215 4.25 1.223 5.125 2.938z");
}

.l9b4opb5t {
  stop-color: var(--svg-color--338e58, #338E58);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll_a9ebcz {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.125 9.699c.064.085-.07.189-.22.302c-.151.113-.263.192-.327.107s.007-.245.159-.358c.15-.113.325-.136.388-.051");
}

.lwhsndh-i {
  stop-color: var(--svg-color--452531, #452531);
}

.m6ubs3bqo {
  d: path("m13.196 29.943l-2.547-3.837l5.25-3.475l5.828 2.91l-2.922 4.402z");
}

.m840w_5cw {
  fill-rule: evenodd;
  d: path("M15.972 4.375c-3.812 0-5.694 1.656-6.334 2.379a.775.775 0 0 1-1.16-1.027c.88-.996 3.165-2.902 7.494-2.902c4.41 0 6.608 1.914 7.54 2.876A.775.775 0 1 1 22.4 6.78c-.735-.758-2.556-2.405-6.428-2.405");
}

.m92tte26k {
  stop-color: var(--svg-color--e170ad, #E170AD);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mkzqq_74a {
  d: path("M23.457 22.772c.076-.155.018-.354-.098-.418c-.854-.404-2.334.552-3.222 1.633c-.099.12-.144.112-.117-.035c.247-1.376.009-3.139-.846-3.532c-.127-.055-.279.027-.355.182l-.754 1.632c-.044.107-.088.204-.132.311c-.111.292-.303.839-.336 1.134c-.152 1.232.46 2.09 1.43 2.538c.894.415 1.83.406 2.656-.36c.34-.303.754-.948.972-1.414z");
}

.monvxeeww {
  fill: var(--svg-color--432a28, #432A28);
  fill-rule: evenodd;
  d: path("m19.738 8.349l-.137.23za.268.268 0 0 1-.275.46l-.005-.003l-.022-.012l-.09-.046a3 3 0 0 0-.343-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 1 1-.093-.528c.513-.09.988 0 1.328.11a3.3 3.3 0 0 1 .558.238l.01.005z");
}

.movji7bnz {
  r: 0.762px;
}

.mpfjlio6c {
  stop-color: var(--svg-color--619951, #619951);
}

.mt79dxbhn {
  d: path("m15.625 10.223l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.376-.646-.376-.765 0");
}

.mu5z5titl {
  stop-color: var(--svg-color--c6bebf, #C6BEBF);
}

.muarw1mje {
  stop-color: var(--svg-color--814e62, #814E62);
  stop-opacity: 0;
}

.muovvys4e {
  stop-color: var(--svg-color--e2dfe3, #E2DFE3);
}

.n_8ruvbgx {
  d: path("M14.638 10.298c0-.288-.235-.48-.298-.539l-.288.28l.177.36z");
}

.n0n4e7bnh {
  stop-color: var(--svg-color--f3f0ef, #F3F0EF);
}

.n1imc2b4i {
  stop-color: var(--svg-color--4f8436, #4F8436);
}

.nbz8snbyn {
  stop-color: var(--svg-color--f2f1f2, #F2F1F2);
  stop-opacity: 0;
}

.ndghkrcwe {
  stop-color: var(--svg-color--c3bbbb, #C3BBBB);
}

.nhx1lw5my {
  fill: var(--svg-color--ffdd2c, #FFDD2C);
  d: path("M12.712 23.184c.15-.67.84-1.06 1.5-.85l.62.211a.05.05 0 0 0 .066-.05l-.03-.485c-.06-.67.41-1.266 1.09-1.276c.69-.01 1.18.526 1.18 1.25v.561a.05.05 0 0 0 .066.047l.55-.187c.64-.24 1.31.059 1.49.729c.17.65-.214 1.374-.884 1.494l-.457.1a.05.05 0 0 0-.03.079l.307.422c.44.52.34 1.32-.22 1.71s-1.296.193-1.67-.36l-.31-.413a.05.05 0 0 0-.081.003l-.242.375c-.32.59-1.08.79-1.65.42c-.58-.37-.71-1.16-.29-1.7l.357-.526a.05.05 0 0 0-.032-.078l-.37-.066c-.67-.1-1.11-.75-.96-1.41");
}

.nof2xyhhe {
  stop-color: var(--svg-color--d1ced0, #D1CED0);
  stop-opacity: 0;
}

.o_-55_dqa {
  fill: var(--svg-color--dc62a7, #DC62A7);
  d: path("M23.457 22.772c.076-.155.018-.354-.098-.418c-.854-.404-2.334.552-3.222 1.633c-.099.12-.144.112-.117-.035c.247-1.376.009-3.139-.846-3.532c-.127-.055-.279.027-.355.182l-.754 1.632c-.044.107-.088.204-.132.311c-.111.292-.303.839-.336 1.134c-.152 1.232.46 2.09 1.43 2.538c.894.415 1.83.406 2.656-.36c.34-.303.754-.948.972-1.414z");
}

.o38c5rykb {
  stop-color: var(--svg-color--ffef65, #FFEF65);
  stop-opacity: 0;
}

.o57gz703y {
  stop-color: var(--svg-color--554543, #554543);
  stop-opacity: 0;
}

.o5ryhdc_j {
  stop-color: var(--svg-color--5c4643, #5C4643);
  stop-opacity: 0;
}

.o9qsnlb6c {
  stop-color: var(--svg-color--1b572f, #1B572F);
  stop-opacity: 0;
}

.obmju7b-z {
  stop-color: var(--svg-color--d0246b, #D0246B);
}

.obu6d-4mj {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M18.434 22.585c.307.135.83.615.461 1.453");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.olrv_cchi {
  stop-color: var(--svg-color--361f1f, #361F1F);
}

.ov1bd0bys {
  stop-color: var(--svg-color--8b604a, #8B604A);
}

.ox3481l0h {
  stop-color: var(--svg-color--c79980, #C79980);
}

.p5ii0k_1a {
  stop-color: var(--svg-color--a3a2a8, #A3A2A8);
  stop-opacity: 0;
}

.p6khytbgt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M15.92 18.857c.395.01 1.357-.063 2.05-.441");
}

.pbh041bmy {
  stop-color: var(--svg-color--af3465, #AF3465);
  stop-opacity: 0;
}

.pcz4s2bal {
  stop-color: var(--svg-color--1b572f, #1B572F);
}

.pjs-sfuyh {
  fill-rule: evenodd;
  d: path("M13.709 24.347a.913.913 0 0 1-.753-1.108a.91.91 0 0 1 1.178-.668l.617.21a.3.3 0 0 0 .396-.302l-.03-.484v-.007q-.019-.216.044-.404a.85.85 0 0 1 .8-.6c.532-.008.927.396.927 1v.561a.3.3 0 0 0 .396.284l.551-.187l.007-.003c.516-.193 1.023.047 1.16.56c.14.531-.183 1.092-.687 1.182l-.466.103a.3.3 0 0 0-.178.47l.312.43l.006.007a.92.92 0 0 1-.172 1.343c-.429.299-1.012.16-1.32-.295l-.316-.423a.3.3 0 0 0-.493.017l-.247.383l-.005.009a.91.91 0 0 1-1.294.33l-.001-.002a.92.92 0 0 1-.227-1.335l.005-.007l.362-.533a.3.3 0 0 0-.196-.464l-.369-.066z");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pzpwlzysi {
  stop-color: var(--svg-color--8bc659, #8BC659);
  stop-opacity: 0;
}

.qfugmzqtf {
  d: path("M5.062 16.444c0-8.813 4.89-13.219 10.922-13.219s10.922 4.219 10.922 13.219v13.5H5.062z");
}

.qgfdn0els {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M16.098 21.038c.324 0 .758.376.758.859v.945");
}

.qh0bdqbav {
  stop-color: var(--svg-color--9a7267, #9A7267);
  stop-opacity: 0;
}

.qkj18_koj {
  stop-color: var(--svg-color--230c14, #230C14);
  stop-opacity: 0;
}

.qpy3mfbui {
  d: path("M10.52 25.306c-.063-.898-.843-1.586-1.721-1.535l-.99.06c-.121 0-.162.157-.149.206c.176.967.961 1.703 2 1.633l.768-.097a.11.11 0 0 0 .102-.118z");
}

.qq-3exrjf {
  d: path("M18.986 10.285a.84.84 0 0 0-.232-.463l-.26.286l.118.228z");
}

.qth9jkbhl {
  d: path("M8.528 22.772c-.076-.155-.018-.354.098-.418c.854-.404 2.333.552 3.222 1.633c.099.12.144.112.117-.035c-.248-1.376-.009-3.139.846-3.532c.126-.055.278.027.355.182l.753 1.632l.133.311c.111.292.303.839.336 1.134c.152 1.232-.46 2.09-1.43 2.538c-.894.415-1.83.406-2.656-.36c-.34-.303-.754-.948-.972-1.414z");
}

.qvobj7b6r {
  stop-color: var(--svg-color--c2977c, #C2977C);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_s898b6a {
  stop-color: var(--svg-color--b81560, #B81560);
}

.r3y-39nqq {
  stop-color: var(--svg-color--cbc7ca, #CBC7CA);
}

.r4e237cot {
  stop-color: var(--svg-color--56413d, #56413D);
}

.rau9skumu {
  stop-color: var(--svg-color--de5390, #DE5390);
}

.rsfcoybzb {
  stop-color: var(--svg-color--64a25a, #64A25A);
}

.ru9fl6bjc {
  stop-color: var(--svg-color--634945, #634945);
  stop-opacity: 0;
}

.ruz641x6w {
  stop-color: var(--svg-color--d76316, #D76316);
  stop-opacity: 0;
}

.sa_c7ns7l {
  stop-color: var(--svg-color--d4d0d4, #D4D0D4);
}

.shkcotbtg {
  stop-color: var(--svg-color--a97b73, #A97B73);
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.sxw271g7g {
  fill: var(--svg-color--2f2c32, #2F2C32);
  d: path("M17.149 10.015c.265-.467.669-.835 1.537-.835c.38 0 .747.105 1.073.368c.269.218.233.496.025.6l-.556.317c-.652-.21-1.373-.24-2.079-.45");
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t-y5i3b_t {
  stop-color: var(--svg-color--8ac463, #8AC463);
}

.t11w35bzd {
  fill: var(--svg-color--27232a, #27232A);
  d: path("M14.865 10.015c-.265-.467-.669-.835-1.537-.835c-.38 0-.747.105-1.073.368c-.269.218-.233.496-.025.6l.556.317c.652-.21 1.373-.24 2.08-.45");
}

.t9v208shd {
  stop-color: var(--svg-color--a26d62, #A26D62);
}

.tgwkdpbql {
  stop-color: var(--svg-color--bab5b4, #BAB5B4);
}

.tj1at3a2l {
  d: path("M21.48 25.306c.063-.898.843-1.586 1.721-1.535l.99.06c.121 0 .162.157.149.206c-.176.967-.961 1.703-2 1.633l-.768-.097a.11.11 0 0 1-.102-.118z");
}

.tobrp8lrd {
  stop-color: var(--svg-color--604947, #604947);
  stop-opacity: 0;
}

.tqblnl2vv {
  stop-color: var(--svg-color--e3dede, #E3DEDE);
  stop-opacity: 0;
}

.tulkzacvs {
  stop-color: var(--svg-color--6e5350, #6E5350);
  stop-opacity: 0;
}

.tv57cl-9q {
  stop-color: var(--svg-color--d1ced0, #D1CED0);
}

.ty1ewib_q {
  stop-color: var(--svg-color--e170ad, #E170AD);
  stop-opacity: 0;
}

.u1pckdb8y {
  fill: var(--svg-color--b38574, #B38574);
  d: path("M20.834 11.659a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.u3fmvdnwh {
  stop-color: var(--svg-color--25131c, #25131C);
}

.u3ly29i0x {
  stop-color: var(--svg-color--af246b, #AF246B);
}

.u5jpvacda {
  d: path("M27 29.944v-1c0-5.2-3.61-9.365-8.46-10.515a.63.63 0 0 1-.48-.61v-3.105c0-1.15-.94-2.12-2.1-2.1c-1.12.02-2.02.93-2.02 2.06v3.145c0 .29-.2.55-.48.61C8.61 19.57 5 23.744 5 28.944v1z");
}

.u6m78ac0i {
  stop-color: var(--svg-color--604138, #604138);
}

.u7ezkxzae {
  stop-color: var(--svg-color--5f4846, #5F4846);
  stop-opacity: 0;
}

.uaxm8f1hq {
  stop-color: var(--svg-color--338e58, #338E58);
}

.ujdq-6enc {
  stop-color: var(--svg-color--d2cfd8, #D2CFD8);
}

.ukea7pdhy {
  stop-color: var(--svg-color--442534, #442534);
  stop-opacity: 0;
}

.uq7zq9b9u {
  stop-color: var(--svg-color--c46399, #C46399);
  stop-opacity: 0;
}

.us3ue9b4r {
  stop-color: var(--svg-color--995c76, #995C76);
}

.uubrgfq8x {
  stop-color: var(--svg-color--8b5c5a, #8B5C5A);
  stop-opacity: 0;
}

.uy9-hlbji {
  stop-color: var(--svg-color--fff967, #FFF967);
  stop-opacity: 0;
}

.v1p9nob5e {
  fill: var(--svg-color--432a28, #432A28);
  d: path("m12.61 8.806l-.005.003a.268.268 0 0 1-.276-.46l.002-.001l.003-.002l.01-.005l.032-.018q.04-.023.116-.06c.098-.046.238-.106.41-.16c.34-.11.815-.2 1.328-.11a.268.268 0 0 1-.093.528a2.3 2.3 0 0 0-1.072.092a3 3 0 0 0-.456.193");
}

.v4cuahbfk {
  stop-color: var(--svg-color--906d53, #906D53);
}

.v5m4qhb2r {
  stop-color: var(--svg-color--c4967a, #C4967A);
  stop-opacity: 0;
}

.v85e7pbqp {
  stop-color: var(--svg-color--c49987, #C49987);
  stop-opacity: 0;
}

.v9-8bpxan {
  stop-color: var(--svg-color--a3a2a8, #A3A2A8);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vfgk4hb_x {
  stop-color: var(--svg-color--764c51, #764C51);
}

.vh12xwf7a {
  stop-color: var(--svg-color--875f54, #875F54);
  stop-opacity: 0;
}

.vp7ae1_xw {
  d: path("M11.34 11.659a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.vw42v6b3v {
  stop-color: var(--svg-color--c4967a, #C4967A);
}

.w1etxcbdz {
  stop-color: var(--svg-color--2c1c24, #2C1C24);
}

.w4wkyodwa {
  stop-color: var(--svg-color--6c4640, #6C4640);
}

.w5re42dqy {
  stop-color: var(--svg-color--6c4640, #6C4640);
  stop-opacity: 0;
}

.w9gpkna4y {
  stop-color: var(--svg-color--261326, #261326);
}

.wa496n4py {
  stop-color: var(--svg-color--ecb12a, #ECB12A);
  stop-opacity: 0;
}

.wcvk_loqv {
  fill: var(--svg-color--c55496, #C55496);
  d: path("M8.528 22.772c-.076-.155-.018-.354.098-.418c.854-.404 2.333.552 3.222 1.633c.099.12.144.112.117-.035c-.248-1.376-.009-3.139.846-3.532c.126-.055.278.027.355.182l.753 1.632l.133.311c.111.292.303.839.336 1.134c.152 1.232-.46 2.09-1.43 2.538c-.894.415-1.83.406-2.656-.36c-.34-.303-.754-.948-.972-1.414z");
}

.wh0vrhbzi {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
  stop-opacity: 0;
}

.wh23x9bjk {
  stop-color: var(--svg-color--fff763, #FFF763);
}

.wkalc4bst {
  stop-color: var(--svg-color--d35897, #D35897);
  stop-opacity: 0;
}

.wlzou1bho {
  stop-color: var(--svg-color--814e62, #814E62);
}

.wqftqw10s {
  fill: var(--svg-color--b38578, #B38578);
  d: path("m15.625 10.223l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.376-.646-.376-.765 0");
}

.wsyd1pyom {
  stop-color: var(--svg-color--fff763, #FFF763);
  stop-opacity: 0;
}

.wuqjd3b5z {
  stop-color: var(--svg-color--442534, #442534);
}

.wzc4qesat {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M16.007 13.496c-.52 0-1.01-.126-1.422-.345c-.14-.073-.291.089-.203.22a1.932 1.932 0 0 0 3.25 0c.088-.136-.063-.293-.203-.22c-.412.22-.896.345-1.422.345");
}

.x15soc1he {
  stop-color: var(--svg-color--966c60, #966C60);
  stop-opacity: 0;
}

.x2y841bdq {
  d: path("M20.834 11.659a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.x5158qbnu {
  stop-color: var(--svg-color--a97b73, #A97B73);
  stop-opacity: 0;
}

.x7431zb1g {
  stop-color: var(--svg-color--3e2125, #3E2125);
  stop-opacity: 0;
}

.xflvpmp1u {
  stop-color: var(--svg-color--d4d0d4, #D4D0D4);
  stop-opacity: 0;
}

.xh15oqbjw {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.947 8.212c.322-.079 1.124-.04 1.66.344");
}

.xke9_jbxx {
  fill: var(--svg-color--553836, #553836);
  d: path("M15.404 2.794c-1.133-.25-2.15.88-2.267 1.299c1.051 3.545 3.712 3.35 6.34 3.058c1.572-.174 1.743.542 1.877.889c0-3.933-3.344-4.671-5.922-5.24z");
}

.xo240subg {
  stop-color: var(--svg-color--d76316, #D76316);
}

.xqzyuky4n {
  stop-color: var(--svg-color--b28279, #B28279);
}

.xvq3mubqy {
  stop-color: var(--svg-color--261326, #261326);
  stop-opacity: 0;
}

.y32ab_wii {
  stop-color: var(--svg-color--bcb7bd, #BCB7BD);
  stop-opacity: 0;
}

.y3gk9pbvh {
  stop-color: var(--svg-color--634945, #634945);
}

.y8qpet1tz {
  stop-color: var(--svg-color--34673c, #34673C);
}

.yhk8aqbmk {
  stop-color: var(--svg-color--e6dcda, #E6DCDA);
  stop-opacity: 0;
}

.yiz6fvgdb {
  stop-color: var(--svg-color--cca58b, #CCA58B);
}

.ysbaxhbyq {
  stop-color: var(--svg-color--966c60, #966C60);
}

.ysga7wb0w {
  stop-color: var(--svg-color--25131c, #25131C);
  stop-opacity: 0;
}

.z3hpt3mcq {
  stop-color: var(--svg-color--8bc659, #8BC659);
}

.z87kcgb7t {
  stop-color: var(--svg-color--c23471, #C23471);
}

.zbwtm_a3x {
  fill: var(--svg-color--dca238, #DCA238);
  d: path("M15.87 25.369a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.zemyxxbjg {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
}

.zhj208b_d {
  stop-color: var(--svg-color--bcb7bd, #BCB7BD);
}

.zl4k6m5yt {
  stop-color: var(--svg-color--f1eceb, #F1ECEB);
}

.zrr9gv88m {
  stop-color: var(--svg-color--9e755f, #9E755F);
}

.zxvvm-hti {
  stop-color: var(--svg-color--d9cabf, #D9CABF);
}

</style>
