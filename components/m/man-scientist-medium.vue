<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ivWcDIe)" class="sghpbcc-q"/><path fill="url(#iyYnmte)" class="ox0t0tbyw"/><path fill="url(#iUDSZ5b)" class="ox0t0tbyw"/><path fill="url(#iNLTPlc)" class="lzxh7zbhd"/><path fill="url(#i8s27wu)" class="lzxh7zbhd"/><path fill="url(#iEjhPFO)" class="lzxh7zbhd"/><path fill="url(#iIr2zNb)" class="lzxh7zbhd"/><path fill="url(#i6IymKc)" class="vzhel1b-t"/><path fill="url(#icbfzYc)" class="vzhel1b-t"/><path fill="url(#iD7xuyW)" class="vzhel1b-t"/><path fill="url(#iokG4Xd)" class="vzhel1b-t"/><g filter="url(#iiiVBQd)"><path fill="url(#iPm6Z8c)" class="hjxoqcl0v"/></g><g filter="url(#iDqElxe)"><path fill="url(#iBCBk6c)" class="nw8wqqnto"/></g><g filter="url(#ifpr9Fb)"><path fill="url(#ic5ISlz)" class="ue9z25r5u"/></g><path fill="url(#iXMjlYd)" class="j1xrp0vsi"/><path fill="url(#iuMA8qd)" class="j1xrp0vsi"/><path fill="url(#i3Tf6Wx)" class="j1xrp0vsi"/><path fill="url(#i3bFchc)" class="j1xrp0vsi"/><path fill="url(#iTzbEqb)" class="j1xrp0vsi"/><path fill="url(#iziRMXb)" class="mx_0g-cbx"/><path fill="url(#iWWrm2c)" class="mx_0g-cbx"/><path fill="url(#iYC5CUv)" class="mx_0g-cbx"/><path fill="url(#iOYmIxc)" class="mx_0g-cbx"/><path fill="url(#iV5Qwac)" class="nw8wqqnto"/><path fill="url(#iEtcdkc)" class="lceri-vrq"/><path fill="url(#i5KOZnc)" class="lceri-vrq"/><path fill="url(#ivWcDIe)" class="sghpbcc-q"/><g filter="url(#iYKAWUP)"><path fill="url(#iHM3Djd)" class="ftb0dac9p"/><path fill="url(#i04Aaeb)" class="ftb0dac9p"/></g><path fill="url(#iJo4ysd)" class="gip5y3buk"/><path fill="url(#id6Igne)" class="gip5y3buk"/><path fill="url(#ixATofe)" class="a0q7e-rbb"/><path fill="url(#iIN33ps)" class="a0q7e-rbb"/><path fill="url(#iMD4Akd)" class="a0q7e-rbb"/><g filter="url(#iELVDQe)"><rect class="rxsc4xb2z"/><rect fill="url(#in80oDb)" class="q3ap7obeh"/><rect fill="url(#iEsINHM)" class="q3ap7obeh"/><rect fill="url(#imH7Vqd)" class="q3ap7obeh"/></g><path fill="url(#itN89Zb)" class="min4o96wl"/><path fill="url(#iWn83Lb)" class="min4o96wl"/><path fill="url(#i6aufrd)" class="min4o96wl"/><path fill="url(#i4MNM9d)" class="min4o96wl"/><path fill="url(#idoLaid)" class="fn5mc_bpm"/><path fill="url(#iwOSsec)" class="cjh4xuujf"/><g filter="url(#iKp19vc)"><path fill="url(#itP5hod)" class="hjy6wxw2l"/><path fill="url(#iM86qWb)" class="hjy6wxw2l"/><path fill="url(#ihjk7db)" class="hjy6wxw2l"/><path fill="url(#i3LWoQy)" class="hjy6wxw2l"/><path fill="url(#iho2Lqe)" class="hjy6wxw2l"/></g><g filter="url(#ilT10vZ)"><path stroke="url(#ijrhy7c)" class="ql-d_bcrc"/></g><g filter="url(#ih1zZcb)"><path stroke="url(#i3R3PTB)" class="dkh21gill"/></g><g filter="url(#iltvOec)"><path stroke="url(#iW8GzSd)" class="c7dra70nl"/></g><g filter="url(#iyyj2we)"><circle fill="url(#iEYPpnc)" class="eqh0cfbvm"/></g><circle fill="url(#ieyxwDb)" class="eqh0cfbvm"/><g filter="url(#iK62vjc)"><circle fill="url(#iFokuJb)" class="fr_b02bjn"/></g><g filter="url(#iOWPyOb)"><circle fill="url(#i8GrSDb)" class="hcjan-b1f"/><circle fill="url(#ilrzlze)" class="hcjan-b1f"/></g><g filter="url(#izqBrze)"><circle class="p-34tp0cy"/><circle fill="url(#i8sEWNL)" class="r0yuiobng"/><circle fill="url(#in9zxXN)" class="r0yuiobng"/></g><g filter="url(#iOz4Nuc)"><path fill="url(#iruh9gc)" class="pcruds7ya"/><path fill="url(#iIcoakc)" class="pcruds7ya"/><path fill="url(#ii5ajxb)" class="pcruds7ya"/></g><path fill="url(#iV9A2kd)" class="qj9uaub0h"/><path fill="url(#iGTdOhd)" class="qj9uaub0h"/><path fill="url(#i5o5xee)" class="qj9uaub0h"/><g filter="url(#iWXEBAd)"><path fill="url(#iaXGgNe)" class="irlflqb9d"/></g><g filter="url(#iGwyMLb)"><path class="d7awfrbet"/><path fill="url(#ikiQjci)" class="v3ogti5pm"/><path fill="url(#i6hNYWd)" class="v3ogti5pm"/><path fill="url(#iQCEMLy)" class="v3ogti5pm"/><path fill="url(#incZaDe)" class="v3ogti5pm"/></g><g filter="url(#ik5uVye)"><path class="lhjpienem"/></g><g filter="url(#idb5Sib)"><path class="l6o16cbfx"/><path fill="url(#i34LOTR)" class="x90jv--ax"/><path fill="url(#iDriT4b)" class="x90jv--ax"/><path fill="url(#i3HqjXf)" class="x90jv--ax"/><path fill="url(#iGoCpFW)" class="x90jv--ax"/></g><path fill="url(#iTiAbhc)" class="x90jv--ax"/><path stroke="url(#iFSUIhe)" class="sblsowqxq"/><g filter="url(#iQ7IGob)"><path class="lf5nh8bzv"/><path fill="url(#iPDoOKe)" class="n1g7hfaoi"/></g><g filter="url(#irNQBod)"><path class="u5_p34bfc"/><path fill="url(#i19HwwA)" class="kco6a3z9b"/></g><path class="g7s-7qqtm"/><path fill="url(#ilZ7QOd)" class="hnaq7acku"/><path class="a80z27bdo"/><g filter="url(#iWkX2Yd)"><path class="me2uelb3s"/><path fill="url(#iKMU0Fg)" class="vvrrezecs"/></g><g filter="url(#iDDaorz)"><path fill="url(#ikt4fNb)" class="pqww-jb6v"/></g><path class="bo5gh3lkf"/><path fill="url(#iC6hv5d)" class="cm8-zbciu"/><path class="l7y0xcbsw"/><g filter="url(#isqPmCe)"><path fill="url(#iH5uCKe)" class="wzm8egb0t"/></g><g filter="url(#iRPO9jc)"><ellipse transform="rotate(-27.914 12.982 9.835)" class="vegm4sbyn"/><ellipse fill="url(#idQPvGt)" transform="rotate(-27.914 12.982 9.835)" class="hokylobnm"/></g><g filter="url(#i1jaYDd)"><path stroke="url(#imUYDBb)" class="hugh_lb9y"/></g><g filter="url(#iFPFnBe)"><path stroke="url(#ixRbs3c)" class="fm128-6yn"/></g><g filter="url(#iQ26Oye)"><path stroke="url(#iVNKzNc)" class="orjg_kbri"/></g><path fill="url(#ip0WrSb)" class="dlpdj9bfs"/><g filter="url(#iyWTXne)"><path clip-rule="evenodd" class="d32l4nd3w"/></g><defs><radialGradient id="iyYnmte" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.8125 -3.29991 0 15.446 18.316)" gradientUnits="userSpaceOnUse"><stop class="h-vnc5n6a"/><stop offset="1" class="buwur_dqz"/></radialGradient><radialGradient id="iUDSZ5b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.65625 6.93357 0 15.446 30.316)" gradientUnits="userSpaceOnUse"><stop class="iufxq5boh"/><stop offset="1" class="w4j6xtngg"/></radialGradient><radialGradient id="iNLTPlc" cx="0" cy="0" r="1" gradientTransform="rotate(161.686 4.493 14.56)scale(4.67425 7.57955)" gradientUnits="userSpaceOnUse"><stop class="d-w3_abhe"/><stop offset="1" class="bqs6izbmd"/></radialGradient><radialGradient id="iIr2zNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.375 -2.57376 0 9.302 17.41)" gradientUnits="userSpaceOnUse"><stop class="x3hlfcbwc"/><stop offset="1" class="sfpaimhix"/></radialGradient><radialGradient id="i6IymKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.15073 2.71782 0 21.206 30.285)" gradientUnits="userSpaceOnUse"><stop class="rfuz_acet"/><stop offset="1" class="q-fl22tnr"/></radialGradient><radialGradient id="icbfzYc" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.15625 -3.9375 0 22.77 18.535)" gradientUnits="userSpaceOnUse"><stop class="n8vj2kb3y"/><stop offset="1" class="irjqokbks"/></radialGradient><radialGradient id="iBCBk6c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.7279 1.31251 -2.69681 -7.65971 14.999 21.91)" gradientUnits="userSpaceOnUse"><stop class="iezv8nbum"/><stop offset="1" class="ry-6rkb7q"/></radialGradient><radialGradient id="iXMjlYd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.74796 3.71877 -3.74799 -3.7774 22.49 17.691)" gradientUnits="userSpaceOnUse"><stop class="y5gxirbqq"/><stop offset="1" class="t0qf5rbqk"/></radialGradient><radialGradient id="iuMA8qd" cx="0" cy="0" r="1" gradientTransform="rotate(-64.11 29.307 -.255)scale(8.30198 11.1931)" gradientUnits="userSpaceOnUse"><stop class="mvrro-b_u"/><stop offset=".93" class="ocku6nzyd"/></radialGradient><radialGradient id="i3Tf6Wx" cx="0" cy="0" r="1" gradientTransform="rotate(111.826 5.238 14.38)scale(3.56729 6.41649)" gradientUnits="userSpaceOnUse"><stop offset=".073" class="ycu0bme2d"/><stop offset="1" class="zt127j5os"/></radialGradient><radialGradient id="iziRMXb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.95848 0 0 -8.5991 8.226 26.113)" gradientUnits="userSpaceOnUse"><stop class="xoi7hsb-w"/><stop offset="1" class="hkq9astav"/></radialGradient><radialGradient id="iYC5CUv" cx="0" cy="0" r="1" gradientTransform="matrix(-7.51743 0 0 -10.8202 10.005 28.968)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="c1dciy28n"/><stop offset="1" class="vxd8ts5kx"/></radialGradient><radialGradient id="iV5Qwac" cx="0" cy="0" r="1" gradientTransform="rotate(114.365 1.783 11.823)scale(4.20765 8.70789)" gradientUnits="userSpaceOnUse"><stop class="zqbntluns"/><stop offset="1" class="v6bhjtbbk"/></radialGradient><radialGradient id="iEtcdkc" cx="0" cy="0" r="1" gradientTransform="matrix(.41584 12.10916 -8.52544 .29277 24.177 17.879)" gradientUnits="userSpaceOnUse"><stop class="v6ge5bcpf"/><stop offset="1" class="z78o0obou"/></radialGradient><radialGradient id="iHM3Djd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.41281 -3.18655 0 15.426 16.567)" gradientUnits="userSpaceOnUse"><stop class="ph_moylrd"/><stop offset=".632" class="gknvw6bil"/></radialGradient><radialGradient id="i04Aaeb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.25 -.875 0 13.766 15.929)" gradientUnits="userSpaceOnUse"><stop class="pgp6pr__x"/><stop offset="1" class="lehkj4qja"/></radialGradient><radialGradient id="iJo4ysd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03943 1.39355 -1.36898 -2.00347 27.808 23.62)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="v0ox3l-0u"/><stop offset="1" class="x78tqlban"/></radialGradient><radialGradient id="id6Igne" cx="0" cy="0" r="1" gradientTransform="matrix(.80395 -.6129 .46984 .6163 27.206 23.466)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="ruv4dbc7o"/><stop offset="1" class="meeoi68df"/></radialGradient><radialGradient id="iMD4Akd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.54688 -.39416 0 25.571 19.379)" gradientUnits="userSpaceOnUse"><stop class="hkh0bccgk"/><stop offset="1" class="sfa02aclf"/></radialGradient><radialGradient id="in80oDb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.91833 0 0 -.20741 25.177 19.066)" gradientUnits="userSpaceOnUse"><stop offset=".496" class="afeb8bsjy"/><stop offset="1" class="rced3uh7f"/></radialGradient><radialGradient id="iEsINHM" cx="0" cy="0" r="1" gradientTransform="matrix(-.28516 .14844 -.12607 -.24218 27.005 18.918)" gradientUnits="userSpaceOnUse"><stop class="p4k8mjbje"/><stop offset="1" class="e1oaafz6u"/></radialGradient><radialGradient id="imH7Vqd" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .13281 -.08816 -.11928 23.407 19.277)" gradientUnits="userSpaceOnUse"><stop class="bj_z41bxg"/><stop offset="1" class="boi6rx35q"/></radialGradient><radialGradient id="i4MNM9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.34375 -.51563 0 26.227 21.223)" gradientUnits="userSpaceOnUse"><stop class="tsloro5fn"/><stop offset="1" class="p9rinuedy"/></radialGradient><radialGradient id="iM86qWb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.574 25.293)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="ihjk7db" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.574 26.587)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="i3LWoQy" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.574 27.837)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iho2Lqe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.574 29.189)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iEYPpnc" cx="0" cy="0" r="1" gradientTransform="matrix(1.75472 0 0 3.07077 9.02 10.612)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="n91c-gs8j"/><stop offset="1" class="qo7u-3bcf"/></radialGradient><radialGradient id="ieyxwDb" cx="0" cy="0" r="1" gradientTransform="rotate(-124.98 8.543 3.357)scale(1.6566)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="ev4-2pfvs"/><stop offset="1" class="w_j-6pbpp"/></radialGradient><radialGradient id="ilrzlze" cx="0" cy="0" r="1" gradientTransform="matrix(.82663 -.60192 .68701 .9435 20.574 10.348)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="cu-ecjbbc"/><stop offset="1" class="a1ftncccj"/></radialGradient><radialGradient id="i8sEWNL" cx="0" cy="0" r="1" gradientTransform="matrix(.8212 -1.5104 .88405 .48065 20.16 11.433)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="d66ufbbtl"/><stop offset=".916" class="f7hwkw-sq"/></radialGradient><radialGradient id="in9zxXN" cx="0" cy="0" r="1" gradientTransform="rotate(44.707 -2.802 29.87)scale(.3648 .47028)" gradientUnits="userSpaceOnUse"><stop class="suj-pjbhk"/><stop offset="1" class="dg9o8ubcl"/></radialGradient><radialGradient id="iIcoakc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30697 1.60858 0 17.783 9.341)" gradientUnits="userSpaceOnUse"><stop class="e6v6vrbif"/><stop offset="1" class="qmnjff_ag"/></radialGradient><radialGradient id="ii5ajxb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37399 1.70868 0 13.225 9.475)" gradientUnits="userSpaceOnUse"><stop class="c02-eqbxv"/><stop offset="1" class="mmmkqcbgq"/></radialGradient><radialGradient id="i5o5xee" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.32774 -10.3217 0 15.309 9.079)" gradientUnits="userSpaceOnUse"><stop offset=".608" class="n6gltqb_f"/><stop offset="1" class="fe9mitb1b"/></radialGradient><radialGradient id="ikiQjci" cx="0" cy="0" r="1" gradientTransform="rotate(-74.899 14.138 -9.66)scale(3.06211 1.13553)" gradientUnits="userSpaceOnUse"><stop class="ki2rd4v4k"/><stop offset="1" class="tp9jx5j2y"/></radialGradient><radialGradient id="i6hNYWd" cx="0" cy="0" r="1" gradientTransform="rotate(5.258 -42.62 199.903)scale(3.84067 2.0651)" gradientUnits="userSpaceOnUse"><stop offset=".392" class="je_aabb8l"/><stop offset="1" class="ivhsfvmdg"/></radialGradient><radialGradient id="iQCEMLy" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.67903 -2.60035 0 15.437 2.012)" gradientUnits="userSpaceOnUse"><stop class="n7o-m0b5s"/><stop offset="1" class="xp-9f0bqu"/></radialGradient><radialGradient id="incZaDe" cx="0" cy="0" r="1" gradientTransform="matrix(3.07368 -2.25248 3.5289 4.81545 8.989 8.83)" gradientUnits="userSpaceOnUse"><stop class="ux7-g74jy"/><stop offset="1" class="dd8hfetks"/></radialGradient><radialGradient id="iGoCpFW" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19688 -.63254 0 15.764 12.219)" gradientUnits="userSpaceOnUse"><stop class="mifq-tdon"/><stop offset="1" class="n-ko-_w7d"/></radialGradient><radialGradient id="iPDoOKe" cx="0" cy="0" r="1" gradientTransform="matrix(.10418 -.60322 1.78457 .30822 17.88 8.528)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="i19HwwA" cx="0" cy="0" r="1" gradientTransform="rotate(-80.2 11.43 -3.296)scale(.61215 1.81109)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="ilZ7QOd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81106 -1.29009 0 17.616 9.93)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iKMU0Fg" cx="0" cy="0" r="1" gradientTransform="matrix(-.23184 -.29876 .41132 -.3192 17.388 10.014)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iC6hv5d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8111 -1.29015 0 13.253 9.93)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="idQPvGt" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.48 -1.308)scale(.49399 .59379)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="ivWcDIe" x1="8.23" x2="22.659" y1="15.296" y2="15.296" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="i8s27wu" x1="11.239" x2="11.239" y1="30.41" y2="29.098" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iEjhPFO" x1="15.177" x2="14.208" y1="29.098" y2="29.098" gradientUnits="userSpaceOnUse"><stop offset=".129" class="hu0w8ibzb"/><stop offset="1" class="q4mowll4q"/></linearGradient><linearGradient id="iD7xuyW" x1="19.74" x2="19.74" y1="30.41" y2="29.098" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iokG4Xd" x1="15.802" x2="16.505" y1="27.973" y2="27.973" gradientUnits="userSpaceOnUse"><stop class="o77zymbyt"/><stop offset="1" class="i4kgizoks"/></linearGradient><linearGradient id="iPm6Z8c" x1="10.677" x2="12.896" y1="17.941" y2="24.629" gradientUnits="userSpaceOnUse"><stop class="v4-zmrbyl"/><stop offset="1" class="r-0tl8b_g"/></linearGradient><linearGradient id="ic5ISlz" x1="20.45" x2="18.099" y1="18.97" y2="23.671" gradientUnits="userSpaceOnUse"><stop class="z4xhuybyb"/><stop offset="1" class="lkjzf4omc"/></linearGradient><linearGradient id="i3bFchc" x1="18.958" x2="17.552" y1="24.098" y2="22.598" gradientUnits="userSpaceOnUse"><stop class="dhui3nlqd"/><stop offset="1" class="ifg4wbcuq"/><stop offset="1" class="kzdc46tfj"/></linearGradient><linearGradient id="iTzbEqb" x1="17.146" x2="17.974" y1="18.879" y2="19.223" gradientUnits="userSpaceOnUse"><stop offset=".081" class="foy77stiz"/><stop offset="1" class="i3p8g97ol"/></linearGradient><linearGradient id="iWWrm2c" x1="6.567" x2="6.567" y1="30.353" y2="29.219" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iOYmIxc" x1="8.38" x2="7.935" y1="29.387" y2="29.384" gradientUnits="userSpaceOnUse"><stop offset=".175" class="w01lnqx9a"/><stop offset="1" class="xx10debny"/></linearGradient><linearGradient id="i5KOZnc" x1="22.753" x2="23.162" y1="27.66" y2="27.644" gradientUnits="userSpaceOnUse"><stop class="ckzhu0bvt"/><stop offset="1" class="dtqi4cbss"/></linearGradient><linearGradient id="ixATofe" x1="23.825" x2="26.529" y1="20.848" y2="20.848" gradientUnits="userSpaceOnUse"><stop offset=".253" class="cpykpvzxv"/><stop offset=".773" class="ahix7mbin"/></linearGradient><linearGradient id="iIN33ps" x1="26.529" x2="26.18" y1="20.832" y2="20.832" gradientUnits="userSpaceOnUse"><stop class="g1a66we9o"/><stop offset="1" class="c3eiz-bza"/></linearGradient><linearGradient id="itN89Zb" x1="26.529" x2="25.177" y1="23.16" y2="23.16" gradientUnits="userSpaceOnUse"><stop offset=".477" class="ubsir5m6c"/><stop offset="1" class="v0fk_zbwr"/></linearGradient><linearGradient id="iWn83Lb" x1="26.529" x2="26.129" y1="23.308" y2="23.308" gradientUnits="userSpaceOnUse"><stop class="bywelvb6j"/><stop offset="1" class="s44sum5km"/></linearGradient><linearGradient id="i6aufrd" x1="23.696" x2="24.227" y1="23.308" y2="23.308" gradientUnits="userSpaceOnUse"><stop class="jr9zsmblm"/><stop offset="1" class="r1tra0r1f"/></linearGradient><linearGradient id="idoLaid" x1="24.782" x2="23.892" y1="21.801" y2="21.801" gradientUnits="userSpaceOnUse"><stop class="d7d_80btw"/><stop offset="1" class="x3pdtmzbl"/></linearGradient><linearGradient id="iwOSsec" x1="24.782" x2="23.892" y1="23.582" y2="23.582" gradientUnits="userSpaceOnUse"><stop class="d7d_80btw"/><stop offset="1" class="x3pdtmzbl"/></linearGradient><linearGradient id="itP5hod" x1="27.165" x2="23.137" y1="28.05" y2="28.05" gradientUnits="userSpaceOnUse"><stop offset=".146" class="fd7w0ysog"/><stop offset=".861" class="wtwh9i50b"/></linearGradient><linearGradient id="ijrhy7c" x1="23.754" x2="25.463" y1="26.068" y2="26.068" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="i3R3PTB" x1="23.676" x2="25.385" y1="27.373" y2="27.373" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="iW8GzSd" x1="23.754" x2="25.463" y1="28.678" y2="28.678" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="iFokuJb" x1="10.69" x2="10.049" y1="10.891" y2="10.891" gradientUnits="userSpaceOnUse"><stop class="vo9agqbnp"/><stop offset="1" class="fwwugibmc"/></linearGradient><linearGradient id="i8GrSDb" x1="21.288" x2="20.47" y1="9.521" y2="12.057" gradientUnits="userSpaceOnUse"><stop class="ix2ytv1nc"/><stop offset="1" class="sla6kib8v"/></linearGradient><linearGradient id="iruh9gc" x1="19.473" x2="11.836" y1="11.002" y2="12.14" gradientUnits="userSpaceOnUse"><stop class="f43nfdclv"/><stop offset="1" class="ixdockwro"/></linearGradient><linearGradient id="iV9A2kd" x1="10.042" x2="11.923" y1="13.698" y2="13.631" gradientUnits="userSpaceOnUse"><stop class="xaj4s_mqh"/><stop offset="1" class="nzdq87b8k"/></linearGradient><linearGradient id="iGTdOhd" x1="20.358" x2="19.245" y1="12.856" y2="12.759" gradientUnits="userSpaceOnUse"><stop class="mxfqo-b2y"/><stop offset="1" class="z8_150olp"/></linearGradient><linearGradient id="iaXGgNe" x1="14.905" x2="23.049" y1="8.017" y2="5.102" gradientUnits="userSpaceOnUse"><stop class="m26ledckw"/><stop offset="1" class="yudgedput"/></linearGradient><linearGradient id="i34LOTR" x1="14.573" x2="15.511" y1="11.661" y2="11.661" gradientUnits="userSpaceOnUse"><stop class="brzpz-p3w"/><stop offset="1" class="qxphtrj0e"/></linearGradient><linearGradient id="iDriT4b" x1="16.375" x2="15.35" y1="11.983" y2="11.969" gradientUnits="userSpaceOnUse"><stop class="hcuo1obkg"/><stop offset="1" class="soj01hbui"/></linearGradient><linearGradient id="i3HqjXf" x1="15.632" x2="15.632" y1="12.726" y2="12.153" gradientUnits="userSpaceOnUse"><stop class="xk94moblk"/><stop offset="1" class="v1vf9kb3x"/></linearGradient><linearGradient id="iTiAbhc" x1="15.563" x2="15.563" y1="12.768" y2="12.6" gradientUnits="userSpaceOnUse"><stop class="kpt7nxbeg"/><stop offset="1" class="c70lx944e"/></linearGradient><linearGradient id="iFSUIhe" x1="14.4" x2="14.835" y1="14.341" y2="13.653" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="ikt4fNb" x1="18.393" x2="18.08" y1="9.984" y2="10.177" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iH5uCKe" x1="13.997" x2="13.683" y1="9.984" y2="10.178" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="imUYDBb" x1="18.409" x2="17.989" y1="7.845" y2="6.986" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="ixRbs3c" x1="13.105" x2="11.916" y1="7.717" y2="7.218" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="iVNKzNc" x1="10.775" x2="10.775" y1="5.703" y2="7.86" gradientUnits="userSpaceOnUse"><stop offset=".228" class="zw2ljvb-t"/><stop offset="1" class="ohs50t_5m"/></linearGradient><linearGradient id="ip0WrSb" x1="10.917" x2="22.177" y1="9.6" y2="9.6" gradientUnits="userSpaceOnUse"><stop class="pxdyn0bka"/><stop offset=".099" class="fy-71g_sr"/><stop offset=".374" class="fy-71g_sr"/><stop offset="1" class="t5bid5bsq"/></linearGradient><filter id="iiiVBQd" width="7.023" height="11.703" x="8.591" y="15.715" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2174" stdDeviation=".375"/></filter><filter id="iDqElxe" width="5.673" height="10.453" x="9.476" y="15.606" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.721569 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2174"/></filter><filter id="ifpr9Fb" width="6.388" height="10.529" x="15.499" y="16.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2174" stdDeviation=".375"/></filter><filter id="iYKAWUP" width="4.32" height="3.6" x="13.316" y="15.118" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.235294 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2174"/></filter><filter id="iELVDQe" width="4.008" height=".781" x="23.173" y="18.676" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.796078 0 0 0 0 0.94902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2174"/></filter><filter id="iKp19vc" width="4.468" height="5.556" x="23.137" y="24.432" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.313726 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2174"/></filter><filter id="ilT10vZ" width="2.097" height=".3" x="23.604" y="25.84" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2174" stdDeviation=".05"/></filter><filter id="ih1zZcb" width="2.097" height=".3" x="23.526" y="27.145" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2174" stdDeviation=".05"/></filter><filter id="iltvOec" width="2.097" height=".3" x="23.604" y="28.449" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2174" stdDeviation=".05"/></filter><filter id="iyyj2we" width="3.539" height="3.339" x="9.02" y="8.943" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.470588 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2174"/></filter><filter id="iK62vjc" width="2.99" height="2.99" x="9.195" y="9.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2174" stdDeviation=".25"/></filter><filter id="iOWPyOb" width="3.589" height="3.589" x="18.533" y="8.693" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.368627 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2174"/></filter><filter id="izqBrze" width="2.99" height="2.99" x="18.707" y="9.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2174" stdDeviation=".25"/></filter><filter id="iOz4Nuc" width="10.373" height="12.127" x="10.28" y="4.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.2 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2174"/></filter><filter id="iWXEBAd" width="8.246" height="7.066" x="13.607" y="2.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2174" stdDeviation="1"/></filter><filter id="iGwyMLb" width="12.601" height="8.543" x="9.137" y="1.512" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.109804 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2174"/></filter><filter id="ik5uVye" width="3.26" height="4.181" x="13.568" y="9.458" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2174" stdDeviation=".375"/></filter><filter id="idb5Sib" width="2.377" height="3.181" x="14.249" y="9.795" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2174" stdDeviation=".125"/></filter><filter id="iQ7IGob" width="2.979" height="1.873" x="16.619" y="6.964" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2174"/></filter><filter id="irNQBod" width="2.98" height="1.873" x="11.472" y="6.964" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2174"/></filter><filter id="iWkX2Yd" width=".787" height=".696" x="16.882" y="9.491" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2174" stdDeviation=".05"/></filter><filter id="iDDaorz" width=".891" height=".913" x="17.721" y="9.566" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2174" stdDeviation=".1"/></filter><filter id="isqPmCe" width=".986" height="1.04" x="13.28" y="9.502" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2174" stdDeviation=".1"/></filter><filter id="iRPO9jc" width=".913" height=".704" x="12.525" y="9.483" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2174" stdDeviation=".05"/></filter><filter id="i1jaYDd" width="3.099" height="1.681" x="16.473" y="7.09" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2174" stdDeviation=".25"/></filter><filter id="iFPFnBe" width="3.177" height="1.738" x="11.254" y="7.153" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2174" stdDeviation=".25"/></filter><filter id="iQ26Oye" width="1.008" height="2.269" x="10.271" y="5.426" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2174" stdDeviation=".125"/></filter><filter id="iyWTXne" width="11.479" height="6.324" x="9.611" y="5.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.537255 0 0 0 0 0.670588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2174"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.760784 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2174" result="effect2_innerShadow_4002_2174"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-scientist-medium" /></template>
<style>
.a0q7e-rbb {
  d: path("M23.825 19.457h2.703v5.938h-2.703z");
}

.a1ftncccj {
  stop-color: var(--svg-color--8f6459, #8F6459);
  stop-opacity: 0;
}

.a80z27bdo {
  fill: var(--svg-color--000, #000);
  d: path("M17.107 10.346c0-.284.227-.511.51-.511a.51.51 0 0 1 .455.746h-.904a.46.46 0 0 1-.061-.235");
}

.afeb8bsjy {
  stop-color: var(--svg-color--b8e0ff, #B8E0FF);
}

.ahix7mbin {
  stop-color: var(--svg-color--bff0ff, #BFF0FF);
}

.bac636b7w {
  stop-color: var(--svg-color--5b4545, #5B4545);
}

.bj_z41bxg {
  stop-color: var(--svg-color--caedff, #CAEDFF);
}

.bo5gh3lkf {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.044 9.182c-.653 0-1.204.45-1.354 1.058a.273.273 0 0 0 .268.34h2.23a.23.23 0 0 0 .227-.27a1.4 1.4 0 0 0-1.37-1.128");
}

.boi6rx35q {
  stop-color: var(--svg-color--caedff, #CAEDFF);
  stop-opacity: 0;
}

.bqs6izbmd {
  stop-color: var(--svg-color--cdc1db, #CDC1DB);
}

.brzpz-p3w {
  stop-color: var(--svg-color--8b6455, #8B6455);
}

.buwur_dqz {
  stop-color: var(--svg-color--2f649d, #2F649D);
}

.bywelvb6j {
  stop-color: var(--svg-color--c0f07e, #C0F07E);
}

.c02-eqbxv {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
}

.c1dciy28n {
  stop-color: var(--svg-color--c4c1c3, #C4C1C3);
  stop-opacity: 0;
}

.c3eiz-bza {
  stop-color: var(--svg-color--aedcff, #AEDCFF);
  stop-opacity: 0;
}

.c70lx944e {
  stop-color: var(--svg-color--8e5263, #8E5263);
  stop-opacity: 0;
}

.c7dra70nl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.754 28.6h1.797");
}

.cjh4xuujf {
  d: path("M23.825 23.816v-.468h.805a.234.234 0 0 1 0 .468z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.ckzhu0bvt {
  stop-color: var(--svg-color--b59fc2, #B59FC2);
}

.cm8-zbciu {
  d: path("M13.251 9.453a.892.892 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.893");
}

.cpykpvzxv {
  stop-color: var(--svg-color--a3d3ff, #A3D3FF);
}

.cu-ecjbbc {
  stop-color: var(--svg-color--8f6459, #8F6459);
}

.d-w3_abhe {
  stop-color: var(--svg-color--e3d3fa, #E3D3FA);
}

.d1vocvbes {
  stop-color: var(--svg-color--c99e80, #C99E80);
  stop-opacity: 0;
}

.d32l4nd3w {
  fill: var(--svg-color--ada3b0, #ADA3B0);
  fill-rule: evenodd;
  d: path("M9.761 9.042c.012-1.676 1.389-3.005 3.047-3.005h5.275a3.01 3.01 0 0 1 3.007 3.04v.001c-.022 1.567-1.339 2.918-2.907 2.973h-.002a3.06 3.06 0 0 1-2.63-1.342c-.045-.065-.09-.076-.112-.076s-.067.01-.112.076a3.08 3.08 0 0 1-2.549 1.352a3.02 3.02 0 0 1-3.017-3.017zm.6.003a2.42 2.42 0 0 0 2.417 2.416c.841 0 1.62-.435 2.05-1.085l.002-.003a.74.74 0 0 1 .609-.34c.243 0 .465.128.609.34v.001a2.46 2.46 0 0 0 2.114 1.077c1.248-.044 2.31-1.133 2.328-2.381a2.41 2.41 0 0 0-2.407-2.433h-5.275c-1.336 0-2.437 1.07-2.447 2.408");
}

.d66ufbbtl {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
  stop-opacity: 0;
}

.d7awfrbet {
  fill: var(--svg-color--4f3332, #4F3332);
  d: path("m20.256 4.135l.429.213c.75.374 1.18 1.227 1.019 2.134l-.59 3.04c-.053.313-.26.525-.572.533h-.018s.053-.907.107-1.44c.043-.433-.032-.565-.43-.96c-.214-.213-.375-.533-.375-.853v-.854c0-.266-.214-.48-.429-.533c-.643-.16-1.984-.427-3.915-.427c-1.93 0-3.272.267-3.915.427a.52.52 0 0 0-.43.533v.854c0 .32-.107.64-.375.853l-.16.16c-.215.16-.323.48-.323.746c.054.587.108 1.44.108 1.44l-.05-.001a.63.63 0 0 1-.594-.532l-.59-3.04c-.107-.853.322-1.706 1.073-2.08l.429-.213a8 8 0 0 0 .804-.586l.966-1.014c.59-.533 1.448-.693 2.199-.32a2.94 2.94 0 0 0 1.662 0c.805-.266 1.717-.053 2.36.534l.805.8c.215.266.483.426.805.586");
}

.d7d_80btw {
  stop-color: var(--svg-color--0e7268, #0E7268);
}

.dd8hfetks {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
  stop-opacity: 0;
}

.dg9o8ubcl {
  stop-color: var(--svg-color--895f52, #895F52);
  stop-opacity: 0;
}

.dhui3nlqd {
  stop-color: var(--svg-color--d6baf6, #D6BAF6);
}

.dkh21gill {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.676 27.295h1.797");
}

.dlpdj9bfs {
  d: path("M18.083 6.337h-5.275c-1.497 0-2.737 1.2-2.746 2.707a2.72 2.72 0 0 0 2.716 2.717c.942 0 1.814-.486 2.3-1.22c.189-.277.533-.277.721 0a2.76 2.76 0 0 0 2.373 1.21c1.408-.05 2.598-1.27 2.618-2.677a2.71 2.71 0 0 0-2.707-2.737");
  opacity: var(--svg-opacity--0-6, 0.6);
}

.dtqi4cbss {
  stop-color: var(--svg-color--b59fc2, #B59FC2);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e1oaafz6u {
  stop-color: var(--svg-color--d3faff, #D3FAFF);
  stop-opacity: 0;
}

.e6v6vrbif {
  stop-color: var(--svg-color--ab7773, #AB7773);
}

.eqh0cfbvm {
  cx: 10.69px;
  cy: 10.612px;
  r: 1.669px;
}

.eqzjb1bwj {
  stop-color: var(--svg-color--5b4545, #5B4545);
  stop-opacity: 0;
}

.ev4-2pfvs {
  stop-color: var(--svg-color--834e63, #834E63);
}

.f43nfdclv {
  stop-color: var(--svg-color--c69980, #C69980);
}

.f7hwkw-sq {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
}

.fd7w0ysog {
  stop-color: var(--svg-color--c89a81, #C89A81);
}

.fe9mitb1b {
  stop-color: var(--svg-color--9a5786, #9A5786);
}

.fm128-6yn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.879 8.266c.327-.289 1.04-.593 1.927-.452");
}

.fn5mc_bpm {
  d: path("M23.825 22.035v-.469h.805a.234.234 0 1 1 0 .469z");
}

.foy77stiz {
  stop-color: var(--svg-color--9f98a7, #9F98A7);
}

.fr_b02bjn {
  cx: 10.69px;
  cy: 10.612px;
  r: 0.995px;
}

.fr4wpbo2m {
  stop-color: var(--svg-color--422235, #422235);
}

.ft5dv1b6b {
  fill: none;
}

.ftb0dac9p {
  d: path("M15.426 18.618a2.11 2.11 0 0 1-2.11-2.11v-1.39h4.22v1.39c0 1.17-.95 2.11-2.11 2.11");
}

.fwwugibmc {
  stop-color: var(--svg-color--6e464d, #6E464D);
}

.fy-71g_sr {
  stop-color: var(--svg-color--50a193, #50A193);
}

.g1a66we9o {
  stop-color: var(--svg-color--aedcff, #AEDCFF);
}

.g7s-7qqtm {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.825 9.182c.653 0 1.204.45 1.354 1.058a.274.274 0 0 1-.267.34h-2.23a.23.23 0 0 1-.228-.27a1.4 1.4 0 0 1 1.37-1.128");
}

.gip5y3buk {
  d: path("M26.434 22.958c.56 0 1.02.46 1.02 1.02v2.34h-2.04v-2.34c.01-.56.46-1.02 1.02-1.02");
}

.gknvw6bil {
  stop-color: var(--svg-color--a5776e, #A5776E);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h-vnc5n6a {
  stop-color: var(--svg-color--3a6fb4, #3A6FB4);
}

.hcjan-b1f {
  cx: 20.202px;
  cy: 10.612px;
  r: 1.669px;
}

.hcuo1obkg {
  stop-color: var(--svg-color--cda186, #CDA186);
}

.hjxoqcl0v {
  d: path("m9.474 17.72l-.131 1.733a.6.6 0 0 0 .494.637l.48.084a.15.15 0 0 1 .084.249l-.626.69a.5.5 0 0 0 .015.687l4.732 4.808a.2.2 0 0 0 .343-.14v-3.38c0-.283-.06-.562-.176-.82l-2.605-5.803c-.93.298-1.807.722-2.61 1.256");
}

.hjy6wxw2l {
  d: path("M23.137 25.314a.73.73 0 0 1 .726-.732h2.391a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.591a.731.731 0 0 1-.32-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.406-.657");
}

.hkh0bccgk {
  stop-color: var(--svg-color--bcebff, #BCEBFF);
}

.hkq9astav {
  stop-color: var(--svg-color--d6cbe2, #D6CBE2);
}

.hnaq7acku {
  d: path("M17.618 9.453a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.127");
}

.hokylobnm {
  cx: 12.982px;
  cy: 9.835px;
  rx: 0.389px;
  ry: 0.197px;
}

.hu0w8ibzb {
  stop-color: var(--svg-color--b5a2c9, #B5A2C9);
}

.hugh_lb9y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.098 7.748c.43-.075 1.268-.054 1.849.398");
}

.i3p8g97ol {
  stop-color: var(--svg-color--e2d6f0, #E2D6F0);
  stop-opacity: 0;
}

.i4kgizoks {
  stop-color: var(--svg-color--d1bee7, #D1BEE7);
  stop-opacity: 0;
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

.irlflqb9d {
  d: path("m19.4 4.988l-3.077 1.026a1.047 1.047 0 0 0 .47 2.031l3.06-.41z");
}

.iufxq5boh {
  stop-color: var(--svg-color--3971d9, #3971D9);
}

.ivhsfvmdg {
  stop-color: var(--svg-color--644949, #644949);
  stop-opacity: 0;
}

.ix2ytv1nc {
  stop-color: var(--svg-color--cca68c, #CCA68C);
}

.ixdockwro {
  stop-color: var(--svg-color--916762, #916762);
}

.j1xrp0vsi {
  d: path("m21.37 17.112l.132 1.733a.6.6 0 0 1-.494.636l-.48.085a.15.15 0 0 0-.085.248l.626.691a.5.5 0 0 1-.014.687L16.323 26a.2.2 0 0 1-.343-.14v-3.381a2 2 0 0 1 .175-.82l2.606-5.803c.929.299 1.807.723 2.61 1.256");
}

.je_aabb8l {
  stop-color: var(--svg-color--644949, #644949);
}

.jr9zsmblm {
  stop-color: var(--svg-color--a4c098, #A4C098);
}

.kco6a3z9b {
  d: path("m11.664 7.893l.001-.002l.002-.001l.005-.004l.012-.01a1.4 1.4 0 0 1 .155-.107c.1-.062.24-.14.42-.21A2.83 2.83 0 0 1 13.75 7.4a.534.534 0 0 1-.167 1.055a1.77 1.77 0 0 0-.933.096a1.5 1.5 0 0 0-.309.165a.534.534 0 0 1-.678-.823");
}

.ki2rd4v4k {
  stop-color: var(--svg-color--554042, #554042);
}

.kpt7nxbeg {
  stop-color: var(--svg-color--8e5263, #8E5263);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kzdc46tfj {
  stop-color: var(--svg-color--e7cfff, #E7CFFF);
  stop-opacity: 0;
}

.l6o16cbfx {
  fill: var(--svg-color--b7877d, #B7877D);
  d: path("m15.055 10.327l-.531 1.7a.54.54 0 0 0 .52.699h.786a.54.54 0 0 0 .52-.7l-.53-1.699c-.114-.376-.646-.376-.765 0");
}

.l731pf7zh {
  stop-color: var(--svg-color--835646, #835646);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l7y0xcbsw {
  fill: var(--svg-color--000, #000);
  d: path("M13.762 10.346a.51.51 0 0 0-.51-.511a.51.51 0 0 0-.455.746h.904a.5.5 0 0 0 .061-.235");
}

.lceri-vrq {
  d: path("M22.753 29.988v-11.79c1.29 1.21 2.3 2.76 2.86 4.53l.03.08c.52 1.66.79 3.38.79 5.11v2.07z");
}

.lehkj4qja {
  stop-color: var(--svg-color--925f61, #925F61);
  stop-opacity: 0;
}

.lf5nh8bzv {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("m19.156 7.892l-.003-.002l-.004-.004l-.012-.01a1.4 1.4 0 0 0-.155-.107c-.1-.062-.241-.14-.42-.21A2.83 2.83 0 0 0 17.07 7.4a.534.534 0 0 0 .166 1.055c.398-.063.716.01.934.096a1.5 1.5 0 0 1 .308.165a.534.534 0 0 0 .678-.824");
}

.lhjpienem {
  fill: var(--svg-color--87565c, #87565C);
  d: path("m15.162 10.49l-.82 1.7c-.102.35.142.699.488.699h.737c.345 0 .59-.355.488-.7l-.498-1.699c-.107-.376-.283-.376-.395 0");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkjzf4omc {
  stop-color: var(--svg-color--c5b2dd, #C5B2DD);
}

.lzxh7zbhd {
  d: path("M11.114 16.28a10.5 10.5 0 0 0-2.878 1.918v.014l-.01-.014c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07h10.453v-6.52z");
}

.m26ledckw {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.me2uelb3s {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.552 9.642c.064.085-.069.189-.22.302s-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.051");
}

.meeoi68df {
  stop-color: var(--svg-color--cba68e, #CBA68E);
  stop-opacity: 0;
}

.mifq-tdon {
  stop-color: var(--svg-color--c39787, #C39787);
}

.min4o96wl {
  d: path("M26.529 21.223v4.171h-2.704v-4.171z");
}

.mmmkqcbgq {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
  stop-opacity: 0;
}

.mvrro-b_u {
  stop-color: var(--svg-color--d8bbf3, #D8BBF3);
}

.mx_0g-cbx {
  d: path("M8.226 29.988v-11.79c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07z");
}

.mxfqo-b2y {
  stop-color: var(--svg-color--c1987f, #C1987F);
}

.n-ko-_w7d {
  stop-color: var(--svg-color--c39787, #C39787);
  stop-opacity: 0;
}

.n1g7hfaoi {
  d: path("m19.156 7.892l-.003-.002l-.004-.004l-.012-.01a1.4 1.4 0 0 0-.155-.107c-.1-.062-.241-.14-.42-.21A2.83 2.83 0 0 0 17.07 7.4a.534.534 0 0 0 .166 1.055c.398-.063.716.01.934.096a1.5 1.5 0 0 1 .308.165a.534.534 0 0 0 .678-.824");
}

.n6gltqb_f {
  stop-color: var(--svg-color--9d6278, #9D6278);
  stop-opacity: 0;
}

.n7o-m0b5s {
  stop-color: var(--svg-color--624c49, #624C49);
}

.n8vj2kb3y {
  stop-color: var(--svg-color--f6f4ff, #F6F4FF);
}

.n91c-gs8j {
  stop-color: var(--svg-color--865d5f, #865D5F);
}

.njj87ojhb {
  stop-color: var(--svg-color--c2998b, #C2998B);
}

.nw8wqqnto {
  d: path("m9.608 17.112l-.13 1.733a.6.6 0 0 0 .493.636l.48.085a.15.15 0 0 1 .085.248l-.626.691a.5.5 0 0 0 .014.687L14.656 26a.2.2 0 0 0 .343-.14v-3.381a2 2 0 0 0-.176-.82l-2.605-5.803c-.93.299-1.807.723-2.61 1.256");
}

.nzdq87b8k {
  stop-color: var(--svg-color--9b7569, #9B7569);
  stop-opacity: 0;
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

.ohs50t_5m {
  stop-color: var(--svg-color--4a3236, #4A3236);
  stop-opacity: 0;
}

.orjg_kbri {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.905 5.801V6.7c-.008.148-.07.48-.258.622");
}

.ox0t0tbyw {
  d: path("M15.466 15.348c-2.75 0-5.32 1.06-7.23 2.85v.014l-.01-.014c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07h21.79l.01-2.03c.01-1.76-.25-3.51-.77-5.18c-.57-1.81-1.59-3.38-2.91-4.61a10.62 10.62 0 0 0-7.2-2.82");
}

.p-34tp0cy {
  cx: 20.202px;
  cy: 10.612px;
  r: 0.995px;
  fill: var(--svg-color--a57c70, #A57C70);
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

.pcruds7ya {
  d: path("m10.338 10l.049.001s-.054-.853-.107-1.44c0-.266.107-.586.321-.746l.161-.16c.268-.213.376-.533.376-.853v-.854c0-.266.16-.48.429-.533c.643-.16 1.984-.427 3.915-.427s3.272.267 3.916.427c.214.053.429.267.429.533v.854c0 .32.16.64.375.853c.502.352.47.545.43.96c-.055.533-.108 1.44-.108 1.44h.018l-.266 3.958c-.16 1.769-1.552 3.002-3.21 3.002h-3.21c-1.712 0-3.05-1.233-3.21-3.002z");
}

.pgp6pr__x {
  stop-color: var(--svg-color--925f61, #925F61);
}

.ph_moylrd {
  stop-color: var(--svg-color--945771, #945771);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pqww-jb6v {
  d: path("M18.413 10.228a.84.84 0 0 0-.232-.463l-.26.286l.118.228z");
}

.pxdyn0bka {
  stop-color: var(--svg-color--87bfb5, #87BFB5);
}

.q-fl22tnr {
  stop-color: var(--svg-color--cfbce6, #CFBCE6);
}

.q3ap7obeh {
  width: 4.008px;
  height: 0.781px;
  x: 23.173px;
  y: 18.676px;
  rx: 0.391px;
}

.q4mowll4q {
  stop-color: var(--svg-color--e2d2f8, #E2D2F8);
  stop-opacity: 0;
}

.qj9uaub0h {
  d: path("M10.28 8.561c0-.266.107-.586.321-.746l.161-.16c.268-.213.376-.533.376-.853v-.854c0-.266.16-.48.429-.533c.643-.16 1.984-.427 3.915-.427s3.272.267 3.916.427c.214.053.429.267.429.533v.854c0 .32.16.64.375.853c.502.352.47.545.43.96c-.055.533-.108 1.44-.108 1.44h.018l-.266 3.958c-.16 1.769-1.552 3.002-3.21 3.002h-3.21c-1.712 0-3.05-1.233-3.21-3.002c-.14-1.817-.2-3.638-.367-5.452");
}

.ql-d_bcrc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.754 25.99h1.797");
}

.qmnjff_ag {
  stop-color: var(--svg-color--ab7773, #AB7773);
  stop-opacity: 0;
}

.qo7u-3bcf {
  stop-color: var(--svg-color--76594a, #76594A);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxphtrj0e {
  stop-color: var(--svg-color--8b6455, #8B6455);
  stop-opacity: 0;
}

.r-0tl8b_g {
  stop-color: var(--svg-color--bfa7d3, #BFA7D3);
}

.r0yuiobng {
  cx: 20.202px;
  cy: 10.612px;
  r: 0.995px;
}

.r1tra0r1f {
  stop-color: var(--svg-color--a4c098, #A4C098);
  stop-opacity: 0;
}

.rced3uh7f {
  stop-color: var(--svg-color--b8e0ff, #B8E0FF);
  stop-opacity: 0;
}

.rfuz_acet {
  stop-color: var(--svg-color--c3a5dc, #C3A5DC);
}

.ruv4dbc7o {
  stop-color: var(--svg-color--cba68e, #CBA68E);
}

.rxsc4xb2z {
  width: 4.008px;
  height: 0.781px;
  x: 23.173px;
  y: 18.676px;
  fill: var(--svg-color--addaff, #ADDAFF);
  rx: 0.391px;
}

.ry-6rkb7q {
  stop-color: var(--svg-color--e6d7e3, #E6D7E3);
}

.s44sum5km {
  stop-color: var(--svg-color--c0f07e, #C0F07E);
  stop-opacity: 0;
}

.sblsowqxq {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.075 13.37v-.001a.2.2 0 0 0-.242.042a.19.19 0 0 0-.02.24c.344.52.942.867 1.624.867s1.28-.347 1.625-.868a.19.19 0 0 0-.021-.241a.2.2 0 0 0-.242-.04a2.94 2.94 0 0 1-1.362.323c-.5 0-.968-.118-1.362-.323Z");
}

.sfa02aclf {
  stop-color: var(--svg-color--bcebff, #BCEBFF);
  stop-opacity: 0;
}

.sfpaimhix {
  stop-color: var(--svg-color--bdbabb, #BDBABB);
  stop-opacity: 0;
}

.sghpbcc-q {
  d: path("M15.466 15.298h-.04c.1 0 .19 0 .3.01c-.09-.01-.18-.01-.26-.01");
}

.sla6kib8v {
  stop-color: var(--svg-color--ae7f75, #AE7F75);
}

.soj01hbui {
  stop-color: var(--svg-color--cda186, #CDA186);
  stop-opacity: 0;
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.suj-pjbhk {
  stop-color: var(--svg-color--895f52, #895F52);
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t0qf5rbqk {
  stop-color: var(--svg-color--e6d2de, #E6D2DE);
}

.t5bid5bsq {
  stop-color: var(--svg-color--a9ff93, #A9FF93);
  stop-opacity: 0.5;
}

.tp9jx5j2y {
  stop-color: var(--svg-color--554042, #554042);
  stop-opacity: 0;
}

.tsloro5fn {
  stop-color: var(--svg-color--e6ff81, #E6FF81);
}

.u5_p34bfc {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("m11.664 7.893l.001-.002l.002-.001l.005-.004l.012-.01a1.4 1.4 0 0 1 .155-.107c.1-.062.24-.14.42-.21A2.83 2.83 0 0 1 13.75 7.4a.534.534 0 0 1-.167 1.055a1.77 1.77 0 0 0-.933.096a1.5 1.5 0 0 0-.309.165a.534.534 0 0 1-.678-.823");
}

.ubsir5m6c {
  stop-color: var(--svg-color--ccff86, #CCFF86);
}

.ucdgelbmi {
  stop-color: var(--svg-color--835646, #835646);
  stop-opacity: 0;
}

.ue9z25r5u {
  d: path("m21.02 18.142l.115 1.534a.53.53 0 0 1-.437.562l-.424.075a.133.133 0 0 0-.076.22l.554.612a.44.44 0 0 1-.012.607l-4.188 4.255a.177.177 0 0 1-.303-.125v-2.99c0-.25.053-.498.155-.726l2.306-5.135a9.4 9.4 0 0 1 2.31 1.11");
}

.ux7-g74jy {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
}

.v0fk_zbwr {
  stop-color: var(--svg-color--83b651, #83B651);
}

.v0ox3l-0u {
  stop-color: var(--svg-color--a27f66, #A27F66);
}

.v1vf9kb3x {
  stop-color: var(--svg-color--9c6073, #9C6073);
  stop-opacity: 0;
}

.v3ogti5pm {
  d: path("m20.256 4.135l.429.213c.75.374 1.18 1.227 1.019 2.134l-.59 3.04c-.053.313-.26.525-.572.533h-.018s.053-.907.107-1.44c.043-.433-.032-.565-.43-.96c-.214-.213-.375-.533-.375-.853v-.854c0-.266-.214-.48-.429-.533c-.643-.16-1.984-.427-3.915-.427c-1.93 0-3.272.267-3.915.427a.52.52 0 0 0-.43.533v.854c0 .32-.107.64-.375.853l-.16.16c-.215.16-.323.48-.323.746c.054.587.108 1.44.108 1.44l-.05-.001a.63.63 0 0 1-.594-.532l-.59-3.04c-.107-.853.322-1.706 1.073-2.08l.429-.213a8 8 0 0 0 .804-.586l.966-1.014c.59-.533 1.448-.693 2.199-.32a2.94 2.94 0 0 0 1.662 0c.805-.266 1.717-.053 2.36.534l.805.8c.215.266.483.426.805.586");
}

.v4-zmrbyl {
  stop-color: var(--svg-color--b0a6b5, #B0A6B5);
}

.v6bhjtbbk {
  stop-color: var(--svg-color--a8a1ad, #A8A1AD);
  stop-opacity: 0;
}

.v6ge5bcpf {
  stop-color: var(--svg-color--faf8fe, #FAF8FE);
}

.vegm4sbyn {
  cx: 12.982px;
  cy: 9.835px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.vo9agqbnp {
  stop-color: var(--svg-color--694448, #694448);
}

.vvrrezecs {
  d: path("M17.552 9.642c.064.085-.069.189-.22.302s-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.051");
}

.vxd8ts5kx {
  stop-color: var(--svg-color--c4c1c3, #C4C1C3);
}

.vzhel1b-t {
  d: path("M19.865 16.28a10.5 10.5 0 0 1 2.878 1.918v.014l.01-.014c1.29 1.21 2.3 2.76 2.86 4.53l.03.08c.52 1.66.79 3.38.79 5.11v2.07H15.98v-6.52z");
}

.w_j-6pbpp {
  stop-color: var(--svg-color--834e63, #834E63);
  stop-opacity: 0;
}

.w01lnqx9a {
  stop-color: var(--svg-color--bfa6da, #BFA6DA);
}

.w4j6xtngg {
  stop-color: var(--svg-color--3971d9, #3971D9);
  stop-opacity: 0;
}

.wtwh9i50b {
  stop-color: var(--svg-color--94616d, #94616D);
}

.wzm8egb0t {
  d: path("M14.066 10.24c0-.287-.234-.48-.298-.538l-.288.28l.177.36z");
}

.x3hlfcbwc {
  stop-color: var(--svg-color--bdbabb, #BDBABB);
}

.x3pdtmzbl {
  stop-color: var(--svg-color--29615d, #29615D);
}

.x78tqlban {
  stop-color: var(--svg-color--6f4745, #6F4745);
}

.x90jv--ax {
  d: path("m15.055 10.327l-.531 1.7a.54.54 0 0 0 .52.699h.786a.54.54 0 0 0 .52-.7l-.53-1.699c-.114-.376-.646-.376-.765 0");
}

.xaj4s_mqh {
  stop-color: var(--svg-color--9b7569, #9B7569);
}

.xk94moblk {
  stop-color: var(--svg-color--9c6073, #9C6073);
}

.xo-sv8bhm {
  stop-color: var(--svg-color--422235, #422235);
  stop-opacity: 0;
}

.xoi7hsb-w {
  stop-color: var(--svg-color--ddcef1, #DDCEF1);
}

.xp-9f0bqu {
  stop-color: var(--svg-color--624c49, #624C49);
  stop-opacity: 0;
}

.xx10debny {
  stop-color: var(--svg-color--c0a9d9, #C0A9D9);
  stop-opacity: 0;
}

.y5gxirbqq {
  stop-color: var(--svg-color--fffbff, #FFFBFF);
}

.ycu0bme2d {
  stop-color: var(--svg-color--c2bfc3, #C2BFC3);
}

.yudgedput {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
  stop-opacity: 0;
}

.z4xhuybyb {
  stop-color: var(--svg-color--c8c2cc, #C8C2CC);
}

.z78o0obou {
  stop-color: var(--svg-color--c6a5e0, #C6A5E0);
}

.z8_150olp {
  stop-color: var(--svg-color--c1987f, #C1987F);
  stop-opacity: 0;
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

.zw2ljvb-t {
  stop-color: var(--svg-color--4a3236, #4A3236);
}

</style>
