<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ippHexe)" class="naelpkfgy"/><path fill="url(#ilppoMc)" class="eq3rppbvk"/><path fill="url(#iubETLe)" class="eq3rppbvk"/><path fill="url(#i2jEDob)" class="kgzt1l6gu"/><path fill="url(#idMUmwe)" class="kgzt1l6gu"/><path fill="url(#iQAWpQG)" class="kgzt1l6gu"/><path fill="url(#i5yOIxd)" class="kgzt1l6gu"/><path fill="url(#ip9DT7P)" class="d2ee_ob-s"/><path fill="url(#iuP5CMc)" class="d2ee_ob-s"/><path fill="url(#iQEaU5b)" class="d2ee_ob-s"/><path fill="url(#iV63qab)" class="d2ee_ob-s"/><g filter="url(#ipJNxpe)"><path fill="url(#iav9pvc)" class="zmxfx2rxd"/></g><g filter="url(#iFCa9ob)"><path fill="url(#iiV9cCd)" class="mi7wrlbpd"/></g><g filter="url(#iotbBpb)"><path fill="url(#iFYUGnb)" class="d-qqn8bjq"/></g><path fill="url(#ibnSXkV)" class="v18r02bgo"/><path fill="url(#iXIz2Xd)" class="v18r02bgo"/><path fill="url(#iPkR49b)" class="v18r02bgo"/><path fill="url(#ivftDrd)" class="v18r02bgo"/><path fill="url(#iH0vHOc)" class="v18r02bgo"/><path fill="url(#iecDELe)" class="v7p6bhbpd"/><path fill="url(#iVANVBb)" class="v7p6bhbpd"/><path fill="url(#iyUmNeb)" class="v7p6bhbpd"/><path fill="url(#ilDstmM)" class="v7p6bhbpd"/><path fill="url(#iQjJF6b)" class="mi7wrlbpd"/><path fill="url(#iXJNlbd)" class="l0p3fkz8i"/><path fill="url(#iCAqrOd)" class="l0p3fkz8i"/><path fill="url(#ippHexe)" class="naelpkfgy"/><path fill="url(#i5ew00c)" class="q5imiaboc"/><path fill="url(#iUxKmyb)" class="q5imiaboc"/><path fill="url(#iz0HsLr)" class="g6r91acok"/><path fill="url(#iHlsAjd)" class="g6r91acok"/><path fill="url(#ipbXshc)" class="z-bhsabjt"/><path fill="url(#iM5du6b)" class="z-bhsabjt"/><path fill="url(#i5pfcHe)" class="z-bhsabjt"/><g filter="url(#i1jsUYb)"><rect class="u_ji_6ffx"/><rect fill="url(#iI1jvXd)" class="yej4ptjro"/><rect fill="url(#ii9FaKb)" class="yej4ptjro"/><rect fill="url(#iVQgtub)" class="yej4ptjro"/></g><path fill="url(#i5nqlae)" class="rfapv98pn"/><path fill="url(#iU4Thtb)" class="rfapv98pn"/><path fill="url(#idbHWHd)" class="rfapv98pn"/><path fill="url(#iOmncPa)" class="rfapv98pn"/><path fill="url(#ia2eTMb)" class="pn-cqgbxa"/><path fill="url(#ieXiiyd)" class="a34585b1k"/><g filter="url(#ieLxbCG)"><path fill="url(#iWhPz9c)" class="h85toedyq"/><path fill="url(#iggO4Tc)" class="h85toedyq"/><path fill="url(#iI6sdog)" class="h85toedyq"/><path fill="url(#irf2ZHe)" class="h85toedyq"/><path fill="url(#iDCzmXd)" class="h85toedyq"/></g><path fill="url(#i85gdqd)" class="h85toedyq"/><g filter="url(#iILExHb)"><path stroke="url(#ic2tCub)" class="b9klw6huu"/></g><g filter="url(#iUZ4RSg)"><path stroke="url(#iFDPBad)" class="oqn_fmbzg"/></g><g filter="url(#iYhLeie)"><path stroke="url(#imPibib)" class="lqgzdkb4h"/></g><g filter="url(#iHeQTvc)"><circle fill="url(#ix4nslb)" class="x8misgbrk"/></g><g filter="url(#iBXvlmc)"><circle fill="url(#iQMvwPd)" class="pyvs2kbks"/></g><g filter="url(#ipbOOfe)"><circle fill="url(#ipKRVze)" class="tk5yh1ftj"/><circle fill="url(#indtqvc)" class="tk5yh1ftj"/></g><g filter="url(#iVZfsLe)"><circle class="rdx_v9b6g"/><circle fill="url(#i5plmMb)" class="h39fwsbnd"/><circle fill="url(#iGZnqSF)" class="h39fwsbnd"/></g><g filter="url(#imofyOc)"><path fill="url(#iIhkeqd)" class="lnvrxfnpr"/><path fill="url(#iKefjBd)" class="lnvrxfnpr"/><path fill="url(#i61hL7E)" class="lnvrxfnpr"/><path fill="url(#iUEvJ0c)" class="lnvrxfnpr"/><path fill="url(#iEEkrPd)" class="lnvrxfnpr"/></g><g filter="url(#iYDXnGc)"><path class="hqef41bvv"/><path fill="url(#ilxng8d)" class="gj8czvbng"/><path fill="url(#iD0yitb)" class="gj8czvbng"/><path fill="url(#izaknie)" class="gj8czvbng"/><path fill="url(#i0jS7ib)" class="gj8czvbng"/><path fill="url(#ieimK7d)" class="gj8czvbng"/></g><path fill="url(#iwZEs6b)" class="gj8czvbng"/><path fill="url(#ikBbzHc)" class="gj8czvbng"/><g filter="url(#i8rMOwe)"><path class="h0jfjqbja"/></g><g filter="url(#iPCMUNd)"><path class="qt_1xcw6v"/><path fill="url(#iL5rmbb)" class="cslhaac0k"/><path fill="url(#iQSRWsb)" class="cslhaac0k"/><path fill="url(#iQH480d)" class="cslhaac0k"/></g><path fill="url(#iMqGjbe)" class="cslhaac0k"/><path stroke="url(#iGu8D7b)" class="tlocd3bga"/><g filter="url(#i2lq4qS)"><path class="i34cip54a"/></g><g filter="url(#i5swbdg)"><path class="tt8yicc8a"/></g><path class="qva3gns5h"/><path fill="url(#i2Ks36b)" class="y7y-mpblw"/><path class="rln_z2biv"/><g filter="url(#isGCDOb)"><path class="wgmj14bxw"/><path fill="url(#ifiiXJc)" class="d9qqfsbai"/></g><g filter="url(#i9blokm)"><path fill="url(#iLgHOed)" class="t-zbzrn_k"/></g><path class="w9o22ybew"/><path fill="url(#iVvFsGe)" class="nj59msbyw"/><path class="etvlp-wjo"/><g filter="url(#inPGPdb)"><path fill="url(#iFCqzXb)" class="i9k1h-beb"/></g><g filter="url(#iBMR9Ad)"><ellipse transform="rotate(-27.914 12.982 9.843)" class="e-tlnhtpv"/><ellipse fill="url(#iWk7HWc)" transform="rotate(-27.914 12.982 9.843)" class="kbgl8s13x"/></g><g filter="url(#ic9Wnxe)"><path stroke="url(#i9LEi0d)" class="wlz_l_byo"/></g><g filter="url(#iHJsntb)"><path stroke="url(#iby0ZYd)" class="fu4hkwrpp"/></g><path fill="url(#i7v3Uen)" class="yjltf6srs"/><g filter="url(#iwfJYwo)"><path clip-rule="evenodd" class="w0-t33e1f"/></g><defs><radialGradient id="ilppoMc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.8125 -3.29991 0 15.446 18.309)" gradientUnits="userSpaceOnUse"><stop class="h-vnc5n6a"/><stop offset="1" class="buwur_dqz"/></radialGradient><radialGradient id="iubETLe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.65625 6.93357 0 15.446 30.309)" gradientUnits="userSpaceOnUse"><stop class="iufxq5boh"/><stop offset="1" class="w4j6xtngg"/></radialGradient><radialGradient id="i2jEDob" cx="0" cy="0" r="1" gradientTransform="rotate(161.686 4.493 14.557)scale(4.67425 7.57955)" gradientUnits="userSpaceOnUse"><stop class="d-w3_abhe"/><stop offset="1" class="bqs6izbmd"/></radialGradient><radialGradient id="i5yOIxd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.375 -2.57376 0 9.302 17.402)" gradientUnits="userSpaceOnUse"><stop class="x3hlfcbwc"/><stop offset="1" class="sfpaimhix"/></radialGradient><radialGradient id="ip9DT7P" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.15073 2.71782 0 21.206 30.277)" gradientUnits="userSpaceOnUse"><stop class="rfuz_acet"/><stop offset="1" class="q-fl22tnr"/></radialGradient><radialGradient id="iuP5CMc" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.15625 -3.9375 0 22.77 18.527)" gradientUnits="userSpaceOnUse"><stop class="n8vj2kb3y"/><stop offset="1" class="irjqokbks"/></radialGradient><radialGradient id="iiV9cCd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.7279 1.31251 -2.69681 -7.65971 14.999 21.902)" gradientUnits="userSpaceOnUse"><stop class="iezv8nbum"/><stop offset="1" class="ry-6rkb7q"/></radialGradient><radialGradient id="ibnSXkV" cx="0" cy="0" r="1" gradientTransform="matrix(-3.74796 3.71877 -3.74799 -3.7774 22.49 17.684)" gradientUnits="userSpaceOnUse"><stop class="y5gxirbqq"/><stop offset="1" class="t0qf5rbqk"/></radialGradient><radialGradient id="iXIz2Xd" cx="0" cy="0" r="1" gradientTransform="rotate(-64.11 29.301 -.258)scale(8.30198 11.1931)" gradientUnits="userSpaceOnUse"><stop class="mvrro-b_u"/><stop offset=".93" class="ocku6nzyd"/></radialGradient><radialGradient id="iPkR49b" cx="0" cy="0" r="1" gradientTransform="rotate(111.826 5.24 14.376)scale(3.56729 6.41649)" gradientUnits="userSpaceOnUse"><stop offset=".073" class="ycu0bme2d"/><stop offset="1" class="zt127j5os"/></radialGradient><radialGradient id="iecDELe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.95848 0 0 -8.5991 8.226 26.105)" gradientUnits="userSpaceOnUse"><stop class="xoi7hsb-w"/><stop offset="1" class="hkq9astav"/></radialGradient><radialGradient id="iyUmNeb" cx="0" cy="0" r="1" gradientTransform="matrix(-7.51743 0 0 -10.8202 10.005 28.96)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="c1dciy28n"/><stop offset="1" class="vxd8ts5kx"/></radialGradient><radialGradient id="iQjJF6b" cx="0" cy="0" r="1" gradientTransform="rotate(114.365 1.785 11.82)scale(4.20765 8.70789)" gradientUnits="userSpaceOnUse"><stop class="zqbntluns"/><stop offset="1" class="v6bhjtbbk"/></radialGradient><radialGradient id="iXJNlbd" cx="0" cy="0" r="1" gradientTransform="matrix(.41584 12.10916 -8.52544 .29277 24.177 17.871)" gradientUnits="userSpaceOnUse"><stop class="v6ge5bcpf"/><stop offset="1" class="z78o0obou"/></radialGradient><radialGradient id="i5ew00c" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.41281 -3.18655 0 15.426 16.56)" gradientUnits="userSpaceOnUse"><stop class="pplj5kbhg"/><stop offset=".632" class="m50akfb7d"/></radialGradient><radialGradient id="iUxKmyb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.25 -.875 0 13.766 15.921)" gradientUnits="userSpaceOnUse"><stop class="rdp66lkxf"/><stop offset="1" class="hvoveibaa"/></radialGradient><radialGradient id="iz0HsLr" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03943 1.39355 -1.36898 -2.00347 27.808 23.613)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="a05f1abog"/><stop offset="1" class="u70m8cc1d"/></radialGradient><radialGradient id="iHlsAjd" cx="0" cy="0" r="1" gradientTransform="matrix(.80395 -.6129 .46984 .6163 27.206 23.458)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="hcxzg0b5c"/><stop offset="1" class="eqicngbxg"/></radialGradient><radialGradient id="i5pfcHe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.54688 -.39416 0 25.571 19.371)" gradientUnits="userSpaceOnUse"><stop class="hkh0bccgk"/><stop offset="1" class="sfa02aclf"/></radialGradient><radialGradient id="iI1jvXd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.91833 0 0 -.20741 25.177 19.059)" gradientUnits="userSpaceOnUse"><stop offset=".496" class="afeb8bsjy"/><stop offset="1" class="rced3uh7f"/></radialGradient><radialGradient id="ii9FaKb" cx="0" cy="0" r="1" gradientTransform="matrix(-.28516 .14844 -.12607 -.24218 27.006 18.912)" gradientUnits="userSpaceOnUse"><stop class="p4k8mjbje"/><stop offset="1" class="e1oaafz6u"/></radialGradient><radialGradient id="iVQgtub" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .13281 -.08816 -.11928 23.407 19.27)" gradientUnits="userSpaceOnUse"><stop class="bj_z41bxg"/><stop offset="1" class="boi6rx35q"/></radialGradient><radialGradient id="iOmncPa" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.34375 -.51563 0 26.227 21.215)" gradientUnits="userSpaceOnUse"><stop class="tsloro5fn"/><stop offset="1" class="p9rinuedy"/></radialGradient><radialGradient id="iggO4Tc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.574 25.285)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iI6sdog" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.574 26.58)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="irf2ZHe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.574 27.83)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iDCzmXd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.574 29.181)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="i85gdqd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.72856 5.10992 -3.29343 -1.7586 28.024 24.87)" gradientUnits="userSpaceOnUse"><stop class="hsdt12m1i"/><stop offset="1" class="v1bt46wqv"/></radialGradient><radialGradient id="ix4nslb" cx="0" cy="0" r="1" gradientTransform="matrix(1.75471 0 0 3.07076 9.02 10.62)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="aik_z9b6i"/><stop offset="1" class="k1mq2zvhc"/></radialGradient><radialGradient id="indtqvc" cx="0" cy="0" r="1" gradientTransform="matrix(.82663 -.60192 .68701 .9435 20.574 10.355)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="g7lt91bhf"/><stop offset="1" class="ze1cb0iau"/></radialGradient><radialGradient id="i5plmMb" cx="0" cy="0" r="1" gradientTransform="matrix(.8212 -1.5104 .88405 .48065 20.16 11.441)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ezktjkbgg"/><stop offset="1" class="j3anadbkm"/></radialGradient><radialGradient id="iGZnqSF" cx="0" cy="0" r="1" gradientTransform="matrix(.25926 .25663 -.33084 .33423 20.202 10.62)" gradientUnits="userSpaceOnUse"><stop class="i4pfhbczn"/><stop offset="1" class="xjk10obil"/></radialGradient><radialGradient id="iKefjBd" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.0847 -9.63492 0 15.908 7.279)" gradientUnits="userSpaceOnUse"><stop offset=".658" class="uqbj0nblw"/><stop offset="1" class="jlu5wk-ta"/></radialGradient><radialGradient id="iUEvJ0c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30697 1.60857 0 17.783 9.349)" gradientUnits="userSpaceOnUse"><stop class="op2kwubyv"/><stop offset="1" class="wvivicznw"/></radialGradient><radialGradient id="iEEkrPd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39075 1.72952 0 13.225 9.315)" gradientUnits="userSpaceOnUse"><stop class="y7nn5tbfc"/><stop offset="1" class="uylyaxbnq"/></radialGradient><radialGradient id="ilxng8d" cx="0" cy="0" r="1" gradientTransform="rotate(127.807 8.852 6.139)scale(5.6057 9.53299)" gradientUnits="userSpaceOnUse"><stop class="qyobb4hvj"/><stop offset="1" class="szm1jtb2t"/></radialGradient><radialGradient id="izaknie" cx="0" cy="0" r="1" gradientTransform="matrix(-.06682 -1.86131 .91413 -.03282 11.246 7.165)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="u7v6tactn"/><stop offset="1" class="hpjuubccm"/></radialGradient><radialGradient id="i0jS7ib" cx="0" cy="0" r="1" gradientTransform="matrix(.85907 -1.96631 1.60368 .70064 19.664 8.883)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ls62f1bvq"/><stop offset="1" class="gx0o3oiqw"/></radialGradient><radialGradient id="ieimK7d" cx="0" cy="0" r="1" gradientTransform="matrix(.9927 1.23176 -1.08755 .87648 14.662 2.02)" gradientUnits="userSpaceOnUse"><stop class="kxzxrmw_u"/><stop offset="1" class="vs8934bpj"/></radialGradient><radialGradient id="iwZEs6b" cx="0" cy="0" r="1" gradientTransform="matrix(.18136 .78313 -1.28748 .29815 16.132 2.02)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="dohbdcxhl"/><stop offset="1" class="bb6ud4ewj"/></radialGradient><radialGradient id="ikBbzHc" cx="0" cy="0" r="1" gradientTransform="matrix(.72544 .89725 -2.0104 1.62544 11.092 3.748)" gradientUnits="userSpaceOnUse"><stop class="w-a4mnbis"/><stop offset="1" class="ab4_rnbjl"/></radialGradient><radialGradient id="i2Ks36b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90308 -1.06858 0 17.616 10.272)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ifiiXJc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.148 .753)scale(.37817 .52064)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iVvFsGe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90312 -1.06863 0 13.253 10.272)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iWk7HWc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.483 -1.304)scale(.49399 .59379)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="ippHexe" x1="8.23" x2="22.659" y1="15.289" y2="15.289" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="idMUmwe" x1="11.239" x2="11.239" y1="30.402" y2="29.09" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iQAWpQG" x1="15.177" x2="14.208" y1="29.09" y2="29.09" gradientUnits="userSpaceOnUse"><stop offset=".129" class="hu0w8ibzb"/><stop offset="1" class="q4mowll4q"/></linearGradient><linearGradient id="iQEaU5b" x1="19.74" x2="19.74" y1="30.402" y2="29.09" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iV63qab" x1="15.802" x2="16.505" y1="27.965" y2="27.965" gradientUnits="userSpaceOnUse"><stop class="o77zymbyt"/><stop offset="1" class="i4kgizoks"/></linearGradient><linearGradient id="iav9pvc" x1="10.677" x2="12.896" y1="17.934" y2="24.621" gradientUnits="userSpaceOnUse"><stop class="v4-zmrbyl"/><stop offset="1" class="r-0tl8b_g"/></linearGradient><linearGradient id="iFYUGnb" x1="20.45" x2="18.099" y1="18.963" y2="23.664" gradientUnits="userSpaceOnUse"><stop class="z4xhuybyb"/><stop offset="1" class="lkjzf4omc"/></linearGradient><linearGradient id="ivftDrd" x1="18.958" x2="17.552" y1="24.09" y2="22.59" gradientUnits="userSpaceOnUse"><stop class="dhui3nlqd"/><stop offset="1" class="ifg4wbcuq"/><stop offset="1" class="kzdc46tfj"/></linearGradient><linearGradient id="iH0vHOc" x1="17.146" x2="17.974" y1="18.871" y2="19.215" gradientUnits="userSpaceOnUse"><stop offset=".081" class="foy77stiz"/><stop offset="1" class="i3p8g97ol"/></linearGradient><linearGradient id="iVANVBb" x1="6.567" x2="6.567" y1="30.345" y2="29.211" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="ilDstmM" x1="8.38" x2="7.935" y1="29.379" y2="29.376" gradientUnits="userSpaceOnUse"><stop offset=".175" class="w01lnqx9a"/><stop offset="1" class="xx10debny"/></linearGradient><linearGradient id="iCAqrOd" x1="22.753" x2="23.162" y1="27.652" y2="27.637" gradientUnits="userSpaceOnUse"><stop class="ckzhu0bvt"/><stop offset="1" class="dtqi4cbss"/></linearGradient><linearGradient id="ipbXshc" x1="23.825" x2="26.529" y1="20.84" y2="20.84" gradientUnits="userSpaceOnUse"><stop offset=".253" class="cpykpvzxv"/><stop offset=".773" class="ahix7mbin"/></linearGradient><linearGradient id="iM5du6b" x1="26.529" x2="26.18" y1="20.824" y2="20.824" gradientUnits="userSpaceOnUse"><stop class="g1a66we9o"/><stop offset="1" class="c3eiz-bza"/></linearGradient><linearGradient id="i5nqlae" x1="26.529" x2="25.177" y1="23.152" y2="23.152" gradientUnits="userSpaceOnUse"><stop offset=".477" class="ubsir5m6c"/><stop offset="1" class="v0fk_zbwr"/></linearGradient><linearGradient id="iU4Thtb" x1="26.529" x2="26.129" y1="23.301" y2="23.301" gradientUnits="userSpaceOnUse"><stop class="bywelvb6j"/><stop offset="1" class="s44sum5km"/></linearGradient><linearGradient id="idbHWHd" x1="23.696" x2="24.227" y1="23.301" y2="23.301" gradientUnits="userSpaceOnUse"><stop class="jr9zsmblm"/><stop offset="1" class="r1tra0r1f"/></linearGradient><linearGradient id="ia2eTMb" x1="24.782" x2="23.892" y1="21.793" y2="21.793" gradientUnits="userSpaceOnUse"><stop class="d7d_80btw"/><stop offset="1" class="x3pdtmzbl"/></linearGradient><linearGradient id="ieXiiyd" x1="24.782" x2="23.892" y1="23.574" y2="23.574" gradientUnits="userSpaceOnUse"><stop class="d7d_80btw"/><stop offset="1" class="x3pdtmzbl"/></linearGradient><linearGradient id="iWhPz9c" x1="27.165" x2="23.137" y1="28.043" y2="28.043" gradientUnits="userSpaceOnUse"><stop offset=".146" class="hqh-1rbea"/><stop offset=".861" class="id19t5fes"/></linearGradient><linearGradient id="ic2tCub" x1="23.754" x2="25.463" y1="26.061" y2="26.061" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="iFDPBad" x1="23.676" x2="25.385" y1="27.365" y2="27.365" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="imPibib" x1="23.754" x2="25.463" y1="28.67" y2="28.67" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="iQMvwPd" x1="10.69" x2="10.049" y1="10.899" y2="10.899" gradientUnits="userSpaceOnUse"><stop class="s236rjbsc"/><stop offset="1" class="o6sle6pni"/></linearGradient><linearGradient id="ipKRVze" x1="21.288" x2="20.47" y1="9.529" y2="12.065" gradientUnits="userSpaceOnUse"><stop class="kwz3apblc"/><stop offset="1" class="gx0xrfbie"/></linearGradient><linearGradient id="iIhkeqd" x1="19.473" x2="11.836" y1="11.01" y2="12.148" gradientUnits="userSpaceOnUse"><stop class="b941pszbd"/><stop offset="1" class="jtnk9gb3a"/></linearGradient><linearGradient id="i61hL7E" x1="10.042" x2="12.354" y1="13.705" y2="13.404" gradientUnits="userSpaceOnUse"><stop class="ls27mhbfe"/><stop offset="1" class="ys1ri2qqc"/></linearGradient><linearGradient id="iD0yitb" x1="10.576" x2="13.478" y1="10.353" y2="5.199" gradientUnits="userSpaceOnUse"><stop class="ts8ii3fly"/><stop offset="1" class="zlpmx2b9v"/></linearGradient><linearGradient id="iL5rmbb" x1="14.573" x2="15.511" y1="11.669" y2="11.669" gradientUnits="userSpaceOnUse"><stop class="gs643vbjw"/><stop offset="1" class="v4v-qb7kx"/></linearGradient><linearGradient id="iQSRWsb" x1="16.375" x2="15.35" y1="11.991" y2="11.977" gradientUnits="userSpaceOnUse"><stop class="sbp9bz1ap"/><stop offset="1" class="xrkexibub"/></linearGradient><linearGradient id="iQH480d" x1="15.632" x2="15.632" y1="12.734" y2="12.161" gradientUnits="userSpaceOnUse"><stop class="rxh459f4v"/><stop offset="1" class="lemuo5beu"/></linearGradient><linearGradient id="iMqGjbe" x1="15.563" x2="15.563" y1="12.775" y2="12.608" gradientUnits="userSpaceOnUse"><stop class="e14d05bbo"/><stop offset="1" class="jt8p4rb1c"/></linearGradient><linearGradient id="iGu8D7b" x1="14.4" x2="14.835" y1="14.348" y2="13.661" gradientUnits="userSpaceOnUse"><stop class="pn2_jabhi"/><stop offset=".663" class="z9945l-5h"/></linearGradient><linearGradient id="iLgHOed" x1="18.394" x2="18.08" y1="9.992" y2="10.185" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iFCqzXb" x1="13.997" x2="13.683" y1="9.992" y2="10.185" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i9LEi0d" x1="18.409" x2="17.989" y1="7.853" y2="6.994" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><linearGradient id="iby0ZYd" x1="13.105" x2="11.916" y1="7.725" y2="7.226" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><linearGradient id="i7v3Uen" x1="10.588" x2="22.177" y1="9.593" y2="9.593" gradientUnits="userSpaceOnUse"><stop class="aetlj_buy"/><stop offset=".115" class="yl8r25bpm"/><stop offset=".257" class="yl8r25bpm"/><stop offset=".917" class="pusr6ob-i"/></linearGradient><filter id="ipJNxpe" width="7.023" height="11.703" x="8.591" y="15.707" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2177" stdDeviation=".375"/></filter><filter id="iFCa9ob" width="5.673" height="10.453" x="9.476" y="15.599" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.721569 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2177"/></filter><filter id="iotbBpb" width="6.388" height="10.529" x="15.499" y="16.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2177" stdDeviation=".375"/></filter><filter id="i1jsUYb" width="4.008" height=".781" x="23.173" y="18.668" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.796078 0 0 0 0 0.94902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2177"/></filter><filter id="ieLxbCG" width="4.468" height="5.556" x="23.137" y="24.424" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.443137 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2177"/></filter><filter id="iILExHb" width="2.097" height=".3" x="23.604" y="25.832" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2177" stdDeviation=".05"/></filter><filter id="iUZ4RSg" width="2.097" height=".3" x="23.526" y="27.137" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2177" stdDeviation=".05"/></filter><filter id="iYhLeie" width="2.097" height=".3" x="23.604" y="28.442" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2177" stdDeviation=".05"/></filter><filter id="iHeQTvc" width="3.539" height="3.339" x="9.02" y="8.951" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.643137 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2177"/></filter><filter id="iBXvlmc" width="2.99" height="2.99" x="9.195" y="9.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2177" stdDeviation=".25"/></filter><filter id="ipbOOfe" width="3.589" height="3.589" x="18.533" y="8.701" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.529412 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2177"/></filter><filter id="iVZfsLe" width="2.99" height="2.99" x="18.707" y="9.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2177" stdDeviation=".25"/></filter><filter id="imofyOc" width="10.373" height="12.177" x="10.28" y="4.996" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.501961 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2177"/></filter><filter id="iYDXnGc" width="12.601" height="8.543" x="9.137" y="1.52" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.690196 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2177"/></filter><filter id="i8rMOwe" width="3.26" height="4.181" x="13.568" y="9.466" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2177" stdDeviation=".375"/></filter><filter id="iPCMUNd" width="2.377" height="3.181" x="14.249" y="9.803" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2177" stdDeviation=".125"/></filter><filter id="i2lq4qS" width="2.979" height="1.873" x="16.619" y="6.971" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2177"/></filter><filter id="i5swbdg" width="2.98" height="1.873" x="11.472" y="6.971" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2177"/></filter><filter id="isGCDOb" width=".787" height=".696" x="16.882" y="9.499" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2177" stdDeviation=".05"/></filter><filter id="i9blokm" width=".891" height=".913" x="17.721" y="9.574" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2177" stdDeviation=".1"/></filter><filter id="inPGPdb" width=".986" height="1.04" x="13.28" y="9.51" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2177" stdDeviation=".1"/></filter><filter id="iBMR9Ad" width=".913" height=".704" x="12.525" y="9.49" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2177" stdDeviation=".05"/></filter><filter id="ic9Wnxe" width="3.099" height="1.681" x="16.473" y="7.098" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2177" stdDeviation=".25"/></filter><filter id="iHJsntb" width="3.177" height="1.738" x="11.254" y="7.161" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2177" stdDeviation=".25"/></filter><filter id="iwfJYwo" width="11.479" height="6.324" x="9.611" y="5.83" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.537255 0 0 0 0 0.670588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2177"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.760784 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2177" result="effect2_innerShadow_4002_2177"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-scientist-medium-light" /></template>
<style>
.a05f1abog {
  stop-color: var(--svg-color--deaf8e, #DEAF8E);
}

.a34585b1k {
  d: path("M23.825 23.809v-.469h.805a.234.234 0 1 1 0 .469z");
}

.ab4_rnbjl {
  stop-color: var(--svg-color--dcc291, #DCC291);
  stop-opacity: 0;
}

.aetlj_buy {
  stop-color: var(--svg-color--9cc4ac, #9CC4AC);
}

.afeb8bsjy {
  stop-color: var(--svg-color--b8e0ff, #B8E0FF);
}

.ahix7mbin {
  stop-color: var(--svg-color--bff0ff, #BFF0FF);
}

.aik_z9b6i {
  stop-color: var(--svg-color--c28775, #C28775);
}

.b941pszbd {
  stop-color: var(--svg-color--fac39e, #FAC39E);
}

.b9klw6huu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.754 25.983h1.797");
}

.bb6ud4ewj {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
  stop-opacity: 0;
}

.bj_z41bxg {
  stop-color: var(--svg-color--caedff, #CAEDFF);
}

.boi6rx35q {
  stop-color: var(--svg-color--caedff, #CAEDFF);
  stop-opacity: 0;
}

.bqs6izbmd {
  stop-color: var(--svg-color--cdc1db, #CDC1DB);
}

.buwur_dqz {
  stop-color: var(--svg-color--2f649d, #2F649D);
}

.bywelvb6j {
  stop-color: var(--svg-color--c0f07e, #C0F07E);
}

.c1dciy28n {
  stop-color: var(--svg-color--c4c1c3, #C4C1C3);
  stop-opacity: 0;
}

.c3eiz-bza {
  stop-color: var(--svg-color--aedcff, #AEDCFF);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.ckzhu0bvt {
  stop-color: var(--svg-color--b59fc2, #B59FC2);
}

.cpykpvzxv {
  stop-color: var(--svg-color--a3d3ff, #A3D3FF);
}

.cslhaac0k {
  d: path("m15.055 10.335l-.531 1.7a.54.54 0 0 0 .52.699h.786a.54.54 0 0 0 .52-.7l-.53-1.699c-.114-.377-.646-.377-.765 0");
}

.d-qqn8bjq {
  d: path("m21.02 18.134l.115 1.534a.53.53 0 0 1-.437.563l-.424.075a.133.133 0 0 0-.076.22l.554.611a.44.44 0 0 1-.012.607L16.552 26a.177.177 0 0 1-.303-.124v-2.991c0-.25.053-.497.155-.725l2.306-5.136c.822.264 1.599.64 2.31 1.111");
}

.d-w3_abhe {
  stop-color: var(--svg-color--e3d3fa, #E3D3FA);
}

.d2ee_ob-s {
  d: path("M19.865 16.273a10.5 10.5 0 0 1 2.878 1.917v.014l.01-.014c1.29 1.21 2.3 2.76 2.86 4.53l.03.08c.52 1.66.79 3.38.79 5.11v2.07H15.98v-6.519z");
}

.d7d_80btw {
  stop-color: var(--svg-color--0e7268, #0E7268);
}

.d9qqfsbai {
  d: path("M17.552 9.65c.064.085-.069.189-.22.302s-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.05");
}

.dhui3nlqd {
  stop-color: var(--svg-color--d6baf6, #D6BAF6);
}

.dohbdcxhl {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
}

.dtqi4cbss {
  stop-color: var(--svg-color--b59fc2, #B59FC2);
  stop-opacity: 0;
}

.e-tlnhtpv {
  cx: 12.982px;
  cy: 9.843px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.e14d05bbo {
  stop-color: var(--svg-color--c27b77, #C27B77);
}

.e1oaafz6u {
  stop-color: var(--svg-color--d3faff, #D3FAFF);
  stop-opacity: 0;
}

.eq3rppbvk {
  d: path("M15.466 15.34c-2.75 0-5.32 1.06-7.23 2.85v.014l-.01-.014c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07h21.79l.01-2.03c.01-1.76-.25-3.51-.77-5.18c-.57-1.81-1.59-3.38-2.91-4.61a10.62 10.62 0 0 0-7.2-2.82");
}

.eqicngbxg {
  stop-color: var(--svg-color--e6bea1, #E6BEA1);
  stop-opacity: 0;
}

.etvlp-wjo {
  fill: var(--svg-color--000, #000);
  d: path("M13.762 10.353a.51.51 0 0 0-.51-.51a.51.51 0 0 0-.455.746h.904a.5.5 0 0 0 .061-.236");
}

.ezktjkbgg {
  stop-color: var(--svg-color--d79a76, #D79A76);
  stop-opacity: 0;
}

.foy77stiz {
  stop-color: var(--svg-color--9f98a7, #9F98A7);
}

.ft5dv1b6b {
  fill: none;
}

.fu4hkwrpp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.879 8.274c.327-.289 1.041-.593 1.927-.452");
}

.g1a66we9o {
  stop-color: var(--svg-color--aedcff, #AEDCFF);
}

.g6r91acok {
  d: path("M26.434 22.95c.56 0 1.02.46 1.02 1.02v2.34h-2.04v-2.34c.01-.56.46-1.02 1.02-1.02");
}

.g7lt91bhf {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gj8czvbng {
  d: path("m20.256 4.143l.429.213c.75.374 1.18 1.227 1.019 2.133l-.59 3.04c-.053.314-.26.525-.572.533h-.018s.053-.906.107-1.44c.044-.432-.032-.565-.43-.96c-.214-.213-.375-.533-.375-.853v-.853c0-.267-.214-.48-.429-.533c-.643-.16-1.984-.427-3.915-.427c-1.93 0-3.272.267-3.915.427a.52.52 0 0 0-.43.533v.853c0 .32-.107.64-.375.854l-.16.16c-.215.16-.322.48-.322.746c.053.587.107 1.44.107 1.44l-.05-.002a.63.63 0 0 1-.594-.531l-.59-3.04c-.107-.853.322-1.706 1.073-2.08l.429-.213a8 8 0 0 0 .805-.587l.965-1.013c.59-.533 1.448-.693 2.199-.32a2.94 2.94 0 0 0 1.663 0c.804-.267 1.716-.053 2.36.533l.804.8c.215.267.483.427.805.587");
}

.gs643vbjw {
  stop-color: var(--svg-color--cb9173, #CB9173);
}

.gx0o3oiqw {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
  stop-opacity: 0;
}

.gx0xrfbie {
  stop-color: var(--svg-color--dca189, #DCA189);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h-vnc5n6a {
  stop-color: var(--svg-color--3a6fb4, #3A6FB4);
}

.h0jfjqbja {
  fill: var(--svg-color--c68378, #C68378);
  d: path("m15.162 10.498l-.82 1.7c-.102.35.142.699.488.699h.737c.345 0 .59-.355.488-.7l-.498-1.699c-.107-.376-.283-.376-.395 0");
}

.h39fwsbnd {
  cx: 20.202px;
  cy: 10.62px;
  r: 0.995px;
}

.h85toedyq {
  d: path("M23.137 25.306c0-.401.325-.732.726-.732h2.391a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.591a.731.731 0 0 1-.32-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.406-.657");
}

.hcxzg0b5c {
  stop-color: var(--svg-color--e6bea1, #E6BEA1);
}

.hkh0bccgk {
  stop-color: var(--svg-color--bcebff, #BCEBFF);
}

.hkq9astav {
  stop-color: var(--svg-color--d6cbe2, #D6CBE2);
}

.hpjuubccm {
  stop-color: var(--svg-color--eec19c, #EEC19C);
  stop-opacity: 0;
}

.hqef41bvv {
  fill: var(--svg-color--ebcc94, #EBCC94);
  d: path("m20.256 4.143l.429.213c.75.374 1.18 1.227 1.019 2.133l-.59 3.04c-.053.314-.26.525-.572.533h-.018s.053-.906.107-1.44c.044-.432-.032-.565-.43-.96c-.214-.213-.375-.533-.375-.853v-.853c0-.267-.214-.48-.429-.533c-.643-.16-1.984-.427-3.915-.427c-1.93 0-3.272.267-3.915.427a.52.52 0 0 0-.43.533v.853c0 .32-.107.64-.375.854l-.16.16c-.215.16-.322.48-.322.746c.053.587.107 1.44.107 1.44l-.05-.002a.63.63 0 0 1-.594-.531l-.59-3.04c-.107-.853.322-1.706 1.073-2.08l.429-.213a8 8 0 0 0 .805-.587l.965-1.013c.59-.533 1.448-.693 2.199-.32a2.94 2.94 0 0 0 1.663 0c.804-.267 1.716-.053 2.36.533l.804.8c.215.267.483.427.805.587");
}

.hqh-1rbea {
  stop-color: var(--svg-color--f3c29f, #F3C29F);
}

.hsdt12m1i {
  stop-color: var(--svg-color--feca9f, #FECA9F);
}

.hu0w8ibzb {
  stop-color: var(--svg-color--b5a2c9, #B5A2C9);
}

.hvoveibaa {
  stop-color: var(--svg-color--cf8b7d, #CF8B7D);
  stop-opacity: 0;
}

.i34cip54a {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("m19.156 7.9l-.003-.002l-.004-.004l-.012-.01a1.4 1.4 0 0 0-.155-.107c-.1-.062-.241-.14-.42-.21a2.83 2.83 0 0 0-1.492-.159a.534.534 0 0 0 .166 1.054c.398-.062.716.01.934.097a1.5 1.5 0 0 1 .308.165a.534.534 0 0 0 .678-.824");
}

.i3p8g97ol {
  stop-color: var(--svg-color--e2d6f0, #E2D6F0);
  stop-opacity: 0;
}

.i4kgizoks {
  stop-color: var(--svg-color--d1bee7, #D1BEE7);
  stop-opacity: 0;
}

.i4pfhbczn {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
}

.i9k1h-beb {
  d: path("M14.066 10.249c0-.289-.234-.48-.298-.539l-.288.279l.178.361z");
}

.id19t5fes {
  stop-color: var(--svg-color--c68b80, #C68B80);
}

.iezv8nbum {
  stop-color: var(--svg-color--fcefff, #FCEFFF);
}

.ifg4wbcuq {
  stop-color: var(--svg-color--e2d2ee, #E2D2EE);
  stop-opacity: 0;
}

.irjqokbks {
  stop-color: var(--svg-color--d7ccea, #D7CCEA);
  stop-opacity: 0;
}

.iufxq5boh {
  stop-color: var(--svg-color--3971d9, #3971D9);
}

.j3anadbkm {
  stop-color: var(--svg-color--d79a76, #D79A76);
}

.jlu5wk-ta {
  stop-color: var(--svg-color--b8718d, #B8718D);
}

.jr9zsmblm {
  stop-color: var(--svg-color--a4c098, #A4C098);
}

.jt8p4rb1c {
  stop-color: var(--svg-color--c27b77, #C27B77);
  stop-opacity: 0;
}

.jtnk9gb3a {
  stop-color: var(--svg-color--c9917c, #C9917C);
}

.k1mq2zvhc {
  stop-color: var(--svg-color--ba7867, #BA7867);
}

.kbgl8s13x {
  cx: 12.982px;
  cy: 9.843px;
  rx: 0.389px;
  ry: 0.197px;
}

.kgzt1l6gu {
  d: path("M11.114 16.273a10.5 10.5 0 0 0-2.878 1.917v.014l-.01-.014c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07h10.453v-6.519z");
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kwz3apblc {
  stop-color: var(--svg-color--f5c8a5, #F5C8A5);
}

.kxzxrmw_u {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
}

.kzdc46tfj {
  stop-color: var(--svg-color--e7cfff, #E7CFFF);
  stop-opacity: 0;
}

.l0p3fkz8i {
  d: path("M22.753 29.98V18.19c1.29 1.21 2.3 2.76 2.86 4.53l.03.08c.52 1.66.79 3.38.79 5.11v2.07z");
}

.ldqge0b0v {
  stop-color: var(--svg-color--c08666, #C08666);
  stop-opacity: 0;
}

.lemuo5beu {
  stop-color: var(--svg-color--c98583, #C98583);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkjzf4omc {
  stop-color: var(--svg-color--c5b2dd, #C5B2DD);
}

.lnvrxfnpr {
  d: path("m10.338 10.008l.049.001s-.054-.853-.107-1.44c0-.266.107-.586.321-.746l.161-.16c.268-.214.376-.534.376-.854v-.853c0-.267.16-.48.429-.533c.643-.16 1.984-.427 3.915-.427s3.272.267 3.916.427c.214.053.429.266.429.533v.853c0 .32.16.64.375.854c.502.351.47.545.43.96c-.055.533-.108 1.44-.108 1.44h.018l-.266 3.957c-.16 1.77-1.552 3.003-3.21 3.003h-3.21c-1.712 0-3.05-1.233-3.21-3.003z");
}

.lqgzdkb4h {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.754 28.592h1.797");
}

.ls27mhbfe {
  stop-color: var(--svg-color--d99e84, #D99E84);
}

.ls62f1bvq {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
}

.m50akfb7d {
  stop-color: var(--svg-color--cf8f8d, #CF8F8D);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mi7wrlbpd {
  d: path("m9.608 17.105l-.13 1.733a.6.6 0 0 0 .493.636l.48.084a.15.15 0 0 1 .085.249l-.626.69a.5.5 0 0 0 .014.687l4.732 4.808a.2.2 0 0 0 .343-.14v-3.38a2 2 0 0 0-.176-.82l-2.605-5.803a10.5 10.5 0 0 0-2.61 1.256");
}

.mvrro-b_u {
  stop-color: var(--svg-color--d8bbf3, #D8BBF3);
}

.n8vj2kb3y {
  stop-color: var(--svg-color--f6f4ff, #F6F4FF);
}

.naelpkfgy {
  d: path("M15.466 15.29h-.04c.1 0 .19 0 .3.01c-.09-.01-.18-.01-.26-.01");
}

.nj59msbyw {
  d: path("M13.251 9.461a.892.892 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.236a.9.9 0 0 0-.896-.892");
}

.o6sle6pni {
  stop-color: var(--svg-color--b87862, #B87862);
}

.o77zymbyt {
  stop-color: var(--svg-color--a588b8, #A588B8);
}

.ocku6nzyd {
  stop-color: var(--svg-color--d8bbf3, #D8BBF3);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.op2kwubyv {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
}

.oqn_fmbzg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.676 27.287h1.797");
}

.p4k8mjbje {
  stop-color: var(--svg-color--d3faff, #D3FAFF);
}

.p9rinuedy {
  stop-color: var(--svg-color--e6ff81, #E6FF81);
  stop-opacity: 0;
}

.pclg_efwa {
  stop-color: var(--svg-color--c7aae2, #C7AAE2);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pn-cqgbxa {
  d: path("M23.825 22.028v-.47h.805a.234.234 0 1 1 0 .47z");
}

.pn2_jabhi {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
}

.pplj5kbhg {
  stop-color: var(--svg-color--be7682, #BE7682);
}

.pqf0u3bgb {
  stop-color: var(--svg-color--a57146, #A57146);
}

.pusr6ob-i {
  stop-color: var(--svg-color--97c1a5, #97C1A5);
  stop-opacity: 0.75;
}

.pyvs2kbks {
  cx: 10.69px;
  cy: 10.62px;
  r: 0.995px;
}

.q-fl22tnr {
  stop-color: var(--svg-color--cfbce6, #CFBCE6);
}

.q4mowll4q {
  stop-color: var(--svg-color--e2d2f8, #E2D2F8);
  stop-opacity: 0;
}

.q5imiaboc {
  d: path("M15.426 18.61a2.11 2.11 0 0 1-2.11-2.11v-1.39h4.22v1.39c0 1.17-.95 2.11-2.11 2.11");
}

.qt_1xcw6v {
  fill: var(--svg-color--e4ac8f, #E4AC8F);
  d: path("m15.055 10.335l-.531 1.7a.54.54 0 0 0 .52.699h.786a.54.54 0 0 0 .52-.7l-.53-1.699c-.114-.377-.646-.377-.765 0");
}

.qva3gns5h {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.825 9.19c.653 0 1.204.45 1.354 1.058a.274.274 0 0 1-.267.34h-2.23a.23.23 0 0 1-.228-.271c.126-.64.69-1.127 1.37-1.127");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qyobb4hvj {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
}

.r-0tl8b_g {
  stop-color: var(--svg-color--bfa7d3, #BFA7D3);
}

.r1tra0r1f {
  stop-color: var(--svg-color--a4c098, #A4C098);
  stop-opacity: 0;
}

.rced3uh7f {
  stop-color: var(--svg-color--b8e0ff, #B8E0FF);
  stop-opacity: 0;
}

.rdp66lkxf {
  stop-color: var(--svg-color--cf8b7d, #CF8B7D);
}

.rdx_v9b6g {
  cx: 20.202px;
  cy: 10.62px;
  r: 0.995px;
  fill: var(--svg-color--d79e81, #D79E81);
}

.rfapv98pn {
  d: path("M26.529 21.215v4.172h-2.704v-4.172z");
}

.rfuz_acet {
  stop-color: var(--svg-color--c3a5dc, #C3A5DC);
}

.rln_z2biv {
  fill: var(--svg-color--000, #000);
  d: path("M17.107 10.354c0-.284.227-.511.51-.511a.51.51 0 0 1 .455.746h-.904a.46.46 0 0 1-.061-.235");
}

.rxh459f4v {
  stop-color: var(--svg-color--c98583, #C98583);
}

.ry-6rkb7q {
  stop-color: var(--svg-color--e6d7e3, #E6D7E3);
}

.s236rjbsc {
  stop-color: var(--svg-color--af6f5d, #AF6F5D);
}

.s44sum5km {
  stop-color: var(--svg-color--c0f07e, #C0F07E);
  stop-opacity: 0;
}

.sbp9bz1ap {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
}

.sbugs4b_s {
  stop-color: var(--svg-color--f2c49e, #F2C49E);
  stop-opacity: 0;
}

.sfa02aclf {
  stop-color: var(--svg-color--bcebff, #BCEBFF);
  stop-opacity: 0;
}

.sfpaimhix {
  stop-color: var(--svg-color--bdbabb, #BDBABB);
  stop-opacity: 0;
}

.szm1jtb2t {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
  stop-opacity: 0;
}

.t-zbzrn_k {
  d: path("M18.413 10.236a.84.84 0 0 0-.232-.462l-.26.285l.118.228z");
}

.t0qf5rbqk {
  stop-color: var(--svg-color--e6d2de, #E6D2DE);
}

.tk5yh1ftj {
  cx: 20.202px;
  cy: 10.62px;
  r: 1.669px;
}

.tlocd3bga {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.075 13.377a2.96 2.96 0 0 0 1.362.323c.505 0 .969-.118 1.362-.323a.2.2 0 0 1 .242.04c.057.06.078.155.02.241m-2.986-.28l2.945.252m-2.945-.253a.2.2 0 0 0-.242.042a.19.19 0 0 0-.02.24m.262-.282l-.22.253m3.207.028l-.042-.028m.042.028l-.042-.028m.042.028a1.94 1.94 0 0 1-1.625.868c-.682 0-1.28-.347-1.624-.868m3.207-.028a1.9 1.9 0 0 1-1.583.846a1.9 1.9 0 0 1-1.583-.846m-.041.028l.041-.028m-.041.028l.041-.028");
}

.ts8ii3fly {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
}

.tsloro5fn {
  stop-color: var(--svg-color--e6ff81, #E6FF81);
}

.tt8yicc8a {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("m11.664 7.9l.002-.002l.005-.004l.012-.01a1.4 1.4 0 0 1 .155-.107c.1-.062.24-.14.42-.21a2.83 2.83 0 0 1 1.492-.159a.534.534 0 0 1-.167 1.054a1.77 1.77 0 0 0-.933.097a1.5 1.5 0 0 0-.308.165a.534.534 0 0 1-.68-.823");
}

.u_ji_6ffx {
  width: 4.008px;
  height: 0.781px;
  x: 23.173px;
  y: 18.668px;
  fill: var(--svg-color--addaff, #ADDAFF);
  rx: 0.391px;
}

.u70m8cc1d {
  stop-color: var(--svg-color--b27959, #B27959);
}

.u7v6tactn {
  stop-color: var(--svg-color--eec19c, #EEC19C);
}

.ubsir5m6c {
  stop-color: var(--svg-color--ccff86, #CCFF86);
}

.uqbj0nblw {
  stop-color: var(--svg-color--c6858b, #C6858B);
  stop-opacity: 0;
}

.uxfooubcv {
  stop-color: var(--svg-color--ae7759, #AE7759);
}

.uylyaxbnq {
  stop-color: var(--svg-color--c2837a, #C2837A);
  stop-opacity: 0;
}

.v0fk_zbwr {
  stop-color: var(--svg-color--83b651, #83B651);
}

.v18r02bgo {
  d: path("m21.37 17.105l.132 1.733a.6.6 0 0 1-.494.636l-.48.084a.15.15 0 0 0-.085.249l.626.69a.5.5 0 0 1-.014.687l-4.732 4.808a.2.2 0 0 1-.343-.14v-3.38a2 2 0 0 1 .175-.82l2.606-5.803c.929.298 1.807.723 2.61 1.256");
}

.v1bt46wqv {
  stop-color: var(--svg-color--feca9f, #FECA9F);
  stop-opacity: 0;
}

.v4-zmrbyl {
  stop-color: var(--svg-color--b0a6b5, #B0A6B5);
}

.v4v-qb7kx {
  stop-color: var(--svg-color--cb9173, #CB9173);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v6bhjtbbk {
  stop-color: var(--svg-color--a8a1ad, #A8A1AD);
  stop-opacity: 0;
}

.v6ge5bcpf {
  stop-color: var(--svg-color--faf8fe, #FAF8FE);
}

.v7p6bhbpd {
  d: path("M8.226 29.98V18.19c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07z");
}

.vs8934bpj {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
  stop-opacity: 0;
}

.vxd8ts5kx {
  stop-color: var(--svg-color--c4c1c3, #C4C1C3);
}

.w-a4mnbis {
  stop-color: var(--svg-color--dcc291, #DCC291);
}

.w0-t33e1f {
  fill: var(--svg-color--ada3b0, #ADA3B0);
  fill-rule: evenodd;
  d: path("M9.761 9.035c.012-1.676 1.389-3.005 3.047-3.005h5.275a3.01 3.01 0 0 1 3.007 3.04c-.022 1.568-1.339 2.918-2.907 2.973h-.002a3.06 3.06 0 0 1-2.63-1.341c-.045-.066-.09-.076-.112-.076s-.067.01-.112.075a3.08 3.08 0 0 1-2.549 1.352a3.02 3.02 0 0 1-3.017-3.016zm.6.003a2.42 2.42 0 0 0 2.417 2.415c.841 0 1.62-.435 2.05-1.085l.002-.003a.74.74 0 0 1 .609-.34a.74.74 0 0 1 .609.34v.002a2.46 2.46 0 0 0 2.114 1.077c1.248-.045 2.31-1.134 2.328-2.382a2.41 2.41 0 0 0-2.407-2.432h-5.275c-1.336 0-2.437 1.07-2.447 2.408");
}

.w01lnqx9a {
  stop-color: var(--svg-color--bfa6da, #BFA6DA);
}

.w4j6xtngg {
  stop-color: var(--svg-color--3971d9, #3971D9);
  stop-opacity: 0;
}

.w9o22ybew {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.044 9.19c-.653 0-1.204.45-1.354 1.058a.273.273 0 0 0 .268.34h2.23a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.37-1.127");
}

.wgmj14bxw {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.552 9.65c.064.085-.069.189-.22.302s-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.05");
}

.wlz_l_byo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.098 7.756c.43-.075 1.268-.054 1.849.398");
}

.wvivicznw {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
  stop-opacity: 0;
}

.x3hlfcbwc {
  stop-color: var(--svg-color--bdbabb, #BDBABB);
}

.x3pdtmzbl {
  stop-color: var(--svg-color--29615d, #29615D);
}

.x8misgbrk {
  cx: 10.69px;
  cy: 10.62px;
  r: 1.669px;
}

.xjk10obil {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
  stop-opacity: 0;
}

.xogpiobqs {
  stop-color: var(--svg-color--a57146, #A57146);
  stop-opacity: 0;
}

.xoi7hsb-w {
  stop-color: var(--svg-color--ddcef1, #DDCEF1);
}

.xrkexibub {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
  stop-opacity: 0;
}

.xx10debny {
  stop-color: var(--svg-color--c0a9d9, #C0A9D9);
  stop-opacity: 0;
}

.y5gxirbqq {
  stop-color: var(--svg-color--fffbff, #FFFBFF);
}

.y7nn5tbfc {
  stop-color: var(--svg-color--c2837a, #C2837A);
}

.y7y-mpblw {
  d: path("M17.618 9.461a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.127");
}

.ycu0bme2d {
  stop-color: var(--svg-color--c2bfc3, #C2BFC3);
}

.yej4ptjro {
  width: 4.008px;
  height: 0.781px;
  x: 23.173px;
  y: 18.668px;
  rx: 0.391px;
}

.yhi4l7bah {
  stop-color: var(--svg-color--f8c8ad, #F8C8AD);
}

.yjltf6srs {
  d: path("M18.083 6.33h-5.275c-1.497 0-2.737 1.2-2.746 2.707a2.72 2.72 0 0 0 2.716 2.716c.942 0 1.814-.486 2.3-1.22c.189-.277.533-.277.721 0a2.76 2.76 0 0 0 2.373 1.21c1.408-.05 2.598-1.269 2.618-2.677a2.71 2.71 0 0 0-2.707-2.736");
  opacity: var(--svg-opacity--0-6, 0.6);
}

.yl8r25bpm {
  stop-color: var(--svg-color--77a78a, #77A78A);
}

.ys1ri2qqc {
  stop-color: var(--svg-color--d99e84, #D99E84);
  stop-opacity: 0;
}

.z-bhsabjt {
  d: path("M23.825 19.449h2.703v5.938h-2.703z");
}

.z4xhuybyb {
  stop-color: var(--svg-color--c8c2cc, #C8C2CC);
}

.z78o0obou {
  stop-color: var(--svg-color--c6a5e0, #C6A5E0);
}

.z9945l-5h {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
  stop-opacity: 0;
}

.ze1cb0iau {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
  stop-opacity: 0;
}

.zlpmx2b9v {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
  stop-opacity: 0;
}

.zmxfx2rxd {
  d: path("m9.474 17.713l-.131 1.733a.6.6 0 0 0 .494.636l.48.085a.15.15 0 0 1 .084.248l-.626.691a.5.5 0 0 0 .015.687l4.732 4.807a.2.2 0 0 0 .343-.14v-3.38a2 2 0 0 0-.176-.82l-2.605-5.803c-.93.299-1.807.723-2.61 1.256");
}

.zpmhxsbxd {
  stop-color: var(--svg-color--c7aae2, #C7AAE2);
  stop-opacity: 0;
}

.zqbntluns {
  stop-color: var(--svg-color--746e77, #746E77);
}

.zt127j5os {
  stop-color: var(--svg-color--ddd8e2, #DDD8E2);
  stop-opacity: 0;
}

</style>
