<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#itbT9ic)"><rect fill="url(#iIk56Pc)" transform="rotate(-45 12.963 13.403)" class="etm0labvf"/></g><g filter="url(#ioJIGVb)"><rect fill="url(#i96BfVc)" transform="scale(-1 1)rotate(-45 -3.014 35.5)" class="ffese-y7m"/></g><rect fill="url(#iIRexfS)" transform="scale(-1 1)rotate(-45 -3.014 35.5)" class="ffese-y7m"/><g filter="url(#iop7mdc)"><path fill="url(#im3tg0d)" class="is89u6ban"/><path fill="url(#iX1BTZW)" class="is89u6ban"/></g><g filter="url(#iVMOROc)"><rect fill="url(#i8mbSfd)" transform="scale(-1 1)rotate(-45 6.585 29.734)" class="z_5s59bdn"/></g><g filter="url(#i6cj6jc)"><path class="er079sbvz"/></g><g filter="url(#i5lUXKd)"><path class="ytl8wkbiv"/></g><g filter="url(#iMAMaFd)"><path class="m8pucsqyt"/></g><g filter="url(#ivmnz1b)"><path class="pv3dgeoha"/></g><g filter="url(#ieDyiqc)"><rect class="r9m8_svvg"/><rect fill="url(#i6PYywe)" class="nl4f7twra"/></g><g filter="url(#i0YdaCz)"><path fill="url(#ioitlCc)" class="oa3f9ve3k"/></g><path fill="url(#i5Ao9Gd)" class="oa3f9ve3k"/><path fill="url(#i8KfH3d)" class="oa3f9ve3k"/><path fill="url(#iEdEbnd)" class="oa3f9ve3k"/><path class="kwrq70t3y"/><path fill="url(#iWUBSSF)" class="yhlqt4zud"/><path fill="url(#ix4g9SG)" class="yhlqt4zud"/><path fill="url(#i83V28c)" class="yhlqt4zud"/><path fill="url(#iJXRjGd)" class="yhlqt4zud"/><path fill="url(#iHjBAxX)" class="yhlqt4zud"/><path class="e593k4bfv"/><path fill="url(#i7QnpSd)" class="xhtzkfsjn"/><path fill="url(#iJU4nte)" class="xhtzkfsjn"/><path fill="url(#iHwKGuc)" class="m0kz_y80u"/><path fill="url(#iG2idHc)" class="m0kz_y80u"/><path fill="url(#i3NKrre)" class="m0kz_y80u"/><path fill="url(#i7mB2nb)" class="m0kz_y80u"/><path fill="url(#iR15onA)" class="bm7w23b9t"/><path fill="url(#iDv7Hjb)" class="bm7w23b9t"/><g filter="url(#il2w90C)"><path class="fdljuobxe"/><path fill="url(#iIEs1Hd)" class="b47wb-b1b"/><path fill="url(#iowaBtV)" class="b47wb-b1b"/></g><path fill="url(#iqaK8tc)" class="b47wb-b1b"/><path fill="url(#iFc3g8a)" class="z45oacyxz"/><path fill="url(#ihvNS4d)" class="z45oacyxz"/><circle fill="url(#iq8HECb)" class="z30kudb-o"/><g filter="url(#i0KWE9c)"><path class="fkflyvb_m"/><path fill="url(#iVm2pab)" class="uu9c01xwt"/><path fill="url(#iwXGa9c)" class="uu9c01xwt"/></g><g filter="url(#iC2ARgP)"><path class="tdcimfbag"/><path fill="url(#iiReXXb)" class="h2pt4jb3o"/><path fill="url(#iggPa7b)" class="h2pt4jb3o"/></g><g filter="url(#ilSc6xb)"><path class="zt9dwabzu"/></g><path fill="url(#iRxWrGd)" class="nr-yk7zrs"/><path fill="url(#iesVFwd)" class="nr-yk7zrs"/><path fill="url(#itiACDd)" class="nr-yk7zrs"/><path fill="url(#i0EOjqc)" class="nr-yk7zrs"/><path fill="url(#iCRra8b)" class="nr-yk7zrs"/><path fill="url(#ibNXoTc)" class="jic9bm_zi"/><g filter="url(#iM4gC0e)"><path stroke="url(#i9tL5Vd)" class="saunobcmg"/></g><g filter="url(#iLoyAVd)"><path stroke="url(#in0SVNc)" class="ikgkim2qs"/></g><g filter="url(#iNxcB0c)"><path stroke="url(#iXQsZLe)" class="zh46g387g"/></g><path fill="url(#iY1r9Me)" class="sie3y1b1c"/><path fill="url(#i3QRAgX)" class="uxuczv7gs"/><g filter="url(#iBnTcFe)"><path fill="url(#ipADvoR)" class="psaan41ml"/></g><path fill="url(#ifMJ0Sb)" class="psaan41ml"/><path fill="url(#imwBg3k)" class="psaan41ml"/><path fill="url(#ijNJiOb)" class="psaan41ml"/><path fill="url(#iHYunKc)" class="psaan41ml"/><path fill="url(#irRl8mz)" class="psaan41ml"/><path fill="url(#it5nT8c)" class="psaan41ml"/><path fill="url(#iZB4TzA)" class="psaan41ml"/><g filter="url(#iWQo5yb)"><path class="o9g1acb4z"/></g><g filter="url(#ikGTKMc)"><path class="o00ub9bxb"/><path fill="url(#itXVb3d)" class="cbof9-bgu"/><path fill="url(#iv0xlsd)" class="cbof9-bgu"/><path fill="url(#iUl0pAu)" class="cbof9-bgu"/><path fill="url(#iJU8Z1d)" class="cbof9-bgu"/><path fill="url(#i1AJYHb)" class="cbof9-bgu"/></g><path fill="url(#iun2Ukc)" class="v0rf09b-u"/><g filter="url(#iAIkB4c)"><path fill="url(#i6R8yjb)" class="h88botbvf"/><path fill="url(#ii3qQNb)" class="h88botbvf"/><path fill="url(#iGVmyKd)" class="h88botbvf"/><path fill="url(#iPfqbbc)" class="h88botbvf"/><path fill="url(#i3ODfnq)" class="h88botbvf"/></g><g filter="url(#iY8HZ3d)"><path class="eb_lzfbwh"/></g><g filter="url(#iNQhoze)"><path class="pu7gpfbtr"/></g><g filter="url(#iOlaPYc)"><path class="e_uyjoq0f"/><path fill="url(#inD7ErP)" class="h_sz7dx-m"/><path fill="url(#iJz2PWd)" class="h_sz7dx-m"/></g><g filter="url(#irLlF3b)"><path class="gaq7fe30j"/><path fill="url(#is5M5Qd)" class="g3opglbhy"/><path fill="url(#iHWJ8sd)" class="g3opglbhy"/><path fill="url(#ilmvaWd)" class="g3opglbhy"/></g><path class="dej2ynjul"/><path fill="url(#ijEilEn)" class="hhdmmdbln"/><path class="ifffzhsgp"/><g filter="url(#iTTXZTb)"><path class="jt7j1ibzr"/><path fill="url(#ipTAuQX)" class="rlebc9g3p"/></g><g filter="url(#isGdgyb)"><path fill="url(#iW8gqvb)" class="u2cv5hb3z"/></g><path class="paqwmgfbp"/><path fill="url(#iuLvJ9d)" class="w4_din79c"/><path class="f0h56obba"/><g filter="url(#iIdWhDd)"><path fill="url(#ikXsKvd)" class="hg82k5vsb"/></g><g filter="url(#iOI6Pab)"><ellipse transform="rotate(-27.914 14.964 7.6)" class="b3bsg4k1o"/><ellipse fill="url(#iNLHNke)" transform="rotate(-27.914 14.964 7.6)" class="ea_bogbnf"/></g><path fill="url(#i2lX03L)" class="p49pqvmwt"/><path fill="url(#iRsmAne)" class="p49pqvmwt"/><path fill="url(#iQDnt0J)" class="p49pqvmwt"/><path fill="url(#ifGox4b)" class="p49pqvmwt"/><path fill="url(#i3ZidRd)" class="eclr80brm"/><path fill="url(#iWo2ZOA)" class="eclr80brm"/><g filter="url(#i7bDd7G)"><path fill="url(#iaQXeRb)" class="ojh7ovyuq"/></g><g filter="url(#icuLmUd)"><path fill="url(#iX2yeNb)" class="nsd5d_b3f"/></g><defs><radialGradient id="iIk56Pc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.87825 -2.80633 3.32449 -2.22505 16.838 21.301)" gradientUnits="userSpaceOnUse"><stop class="vvvf-bx0b"/><stop offset="1" class="rivz2obdn"/></radialGradient><radialGradient id="i96BfVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.75045 -10.1868 0 3.092 .28)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="vm1_cbcaw"/><stop offset="1" class="k356i5yuc"/></radialGradient><radialGradient id="iIRexfS" cx="0" cy="0" r="1" gradientTransform="rotate(-58.508 8.125 5.097)scale(2.87644 1.6899)" gradientUnits="userSpaceOnUse"><stop offset=".419" class="uodqeubaz"/><stop offset="1" class="pha_6_rva"/></radialGradient><radialGradient id="i8mbSfd" cx="0" cy="0" r="1" gradientTransform="matrix(.46404 .88388 -1.60027 .84014 1.815 6.289)" gradientUnits="userSpaceOnUse"><stop class="x6_m96bez"/><stop offset="1" class="s2ceddo5o"/></radialGradient><radialGradient id="ioitlCc" cx="0" cy="0" r="1" gradientTransform="rotate(141.509 11.379 5.864)scale(3.31383 3.4775)" gradientUnits="userSpaceOnUse"><stop class="nw_aknb7y"/><stop offset="1" class="pt-h1ccpi"/></radialGradient><radialGradient id="i5Ao9Gd" cx="0" cy="0" r="1" gradientTransform="matrix(.35156 .89062 -.53122 .2097 23.216 2.575)" gradientUnits="userSpaceOnUse"><stop offset=".22" class="vw5e4lbve"/><stop offset="1" class="v_k-57lgf"/></radialGradient><radialGradient id="i8KfH3d" cx="0" cy="0" r="1" gradientTransform="rotate(78.781 8.915 17.107)scale(1.04377 .3506)" gradientUnits="userSpaceOnUse"><stop class="s_et88bec"/><stop offset="1" class="qlfye6p8o"/></radialGradient><radialGradient id="iEdEbnd" cx="0" cy="0" r="1" gradientTransform="matrix(-.6346 .22 -.12993 -.3748 24.731 3.528)" gradientUnits="userSpaceOnUse"><stop class="s_et88bec"/><stop offset="1" class="qlfye6p8o"/></radialGradient><radialGradient id="iWUBSSF" cx="0" cy="0" r="1" gradientTransform="rotate(-105.819 17.69 2.83)scale(4.87202 1.60555)" gradientUnits="userSpaceOnUse"><stop class="ip469ff8c"/><stop offset="1" class="v0q_-i93u"/></radialGradient><radialGradient id="ix4g9SG" cx="0" cy="0" r="1" gradientTransform="matrix(1.34375 3.125 -1.0965 .4715 17.1 19.904)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="sl-3t4bfx"/><stop offset="1" class="zeih87brn"/></radialGradient><radialGradient id="iJXRjGd" cx="0" cy="0" r="1" gradientTransform="matrix(-.07031 -.73437 .44794 -.04289 16.242 18.481)" gradientUnits="userSpaceOnUse"><stop class="c6dvfyb6s"/><stop offset="1" class="oz3_ipb8v"/></radialGradient><radialGradient id="iHjBAxX" cx="0" cy="0" r="1" gradientTransform="matrix(-.20312 2.82812 -.75946 -.05455 15.241 19.966)" gradientUnits="userSpaceOnUse"><stop class="xo-vurl-f"/><stop offset="1" class="un08nrbhl"/></radialGradient><radialGradient id="i3NKrre" cx="0" cy="0" r="1" gradientTransform="matrix(-.26562 3.09375 -.85026 -.073 15.348 26.277)" gradientUnits="userSpaceOnUse"><stop offset=".085" class="cw-i9xbem"/><stop offset="1" class="t2qxtb2ul"/></radialGradient><radialGradient id="iDv7Hjb" cx="0" cy="0" r="1" gradientTransform="matrix(-.07031 -.19922 1.40814 -.49699 14.503 29.465)" gradientUnits="userSpaceOnUse"><stop class="p5u-_cblu"/><stop offset="1" class="uowu7rarb"/></radialGradient><radialGradient id="iowaBtV" cx="0" cy="0" r="1" gradientTransform="matrix(.46875 1.80469 -.96535 .25074 19.32 20.568)" gradientUnits="userSpaceOnUse"><stop offset=".091" class="wibfg_jba"/><stop offset="1" class="kgna9sqpj"/></radialGradient><radialGradient id="iqaK8tc" cx="0" cy="0" r="1" gradientTransform="matrix(.71094 .34759 -.96823 1.98037 16.606 23.744)" gradientUnits="userSpaceOnUse"><stop offset=".108" class="s3qcrxbjw"/><stop offset="1" class="alg5_vbml"/></radialGradient><radialGradient id="ihvNS4d" cx="0" cy="0" r="1" gradientTransform="matrix(.28516 -.16406 .55035 .95656 16.253 27.216)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="s3hklabia"/><stop offset="1" class="n5igrlbfw"/></radialGradient><radialGradient id="iq8HECb" cx="0" cy="0" r="1" gradientTransform="matrix(.4375 .1914 -.31978 .73092 6.135 15.73)" gradientUnits="userSpaceOnUse"><stop class="aii5rr2eq"/><stop offset="1" class="yv8187b0r"/></radialGradient><radialGradient id="iVm2pab" cx="0" cy="0" r="1" gradientTransform="rotate(-38.729 27.875 -1.303)scale(8.09176 6.39568)" gradientUnits="userSpaceOnUse"><stop offset=".76" class="z1su76bfy"/><stop offset="1" class="ykkax8bmp"/></radialGradient><radialGradient id="iwXGa9c" cx="0" cy="0" r="1" gradientTransform="matrix(-.94747 2.72 -.8954 -.3119 13.593 13.469)" gradientUnits="userSpaceOnUse"><stop class="p8zhg8wps"/><stop offset="1" class="is_m6u3tw"/></radialGradient><radialGradient id="iiReXXb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.16876 .9375 -.156 -.19448 8.314 14.542)" gradientUnits="userSpaceOnUse"><stop class="tdjl0hblu"/><stop offset="1" class="sb1zj3bbu"/></radialGradient><radialGradient id="iggPa7b" cx="0" cy="0" r="1" gradientTransform="matrix(.8047 -.67969 .45175 .53484 7.442 15.269)" gradientUnits="userSpaceOnUse"><stop offset=".45" class="ywqn4-bmn"/><stop offset="1" class="njax42eii"/></radialGradient><radialGradient id="itiACDd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.92712 .2574 -.06658 -.49847 15.23 10.717)" gradientUnits="userSpaceOnUse"><stop class="hq3hkib4c"/><stop offset="1" class="k_rioyb_p"/></radialGradient><radialGradient id="i0EOjqc" cx="0" cy="0" r="1" gradientTransform="rotate(142.326 7.163 8.857)scale(1.55953 .89404)" gradientUnits="userSpaceOnUse"><stop class="ignt4ubkd"/><stop offset="1" class="hts433_5m"/></radialGradient><radialGradient id="iCRra8b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.67188 4.0767 0 18.136 15.553)" gradientUnits="userSpaceOnUse"><stop class="xnxf0re5w"/><stop offset="1" class="utdakeidf"/></radialGradient><radialGradient id="ibNXoTc" cx="0" cy="0" r="1" gradientTransform="rotate(62.33 -1.095 17.766)scale(1.17765 2.48248)" gradientUnits="userSpaceOnUse"><stop class="nov_osbjm"/><stop offset="1" class="b13j0jria"/></radialGradient><radialGradient id="iY1r9Me" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 2.974 17.225)scale(.93463 1.11027)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="xsgkrbcbf"/><stop offset="1" class="ek_f7q3hx"/></radialGradient><radialGradient id="i3QRAgX" cx="0" cy="0" r="1" gradientTransform="matrix(.64068 .20136 -.6212 1.97654 13.4 8.66)" gradientUnits="userSpaceOnUse"><stop class="oaig2cbln"/><stop offset=".746" class="gfuj0ibqm"/></radialGradient><radialGradient id="ipADvoR" cx="0" cy="0" r="1" gradientTransform="matrix(-2.26851 0 0 -4.01298 17.247 8.04)" gradientUnits="userSpaceOnUse"><stop class="yzaj_tb_p"/><stop offset="1" class="ny0rq0bux"/></radialGradient><radialGradient id="imwBg3k" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.73108 -3.9179 0 16.282 6.283)" gradientUnits="userSpaceOnUse"><stop offset=".76" class="www4dfogh"/><stop offset="1" class="c0317ln8x"/></radialGradient><radialGradient id="ijNJiOb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.4983 .61665 0 17.09 7.47)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="h739mqb_c"/><stop offset="1" class="px0sb7ebt"/></radialGradient><radialGradient id="iHYunKc" cx="0" cy="0" r="1" gradientTransform="matrix(.0017 -.47484 .51674 .00186 15.03 7.49)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kxaprmbjh"/><stop offset="1" class="vgn1hf8dm"/></radialGradient><radialGradient id="irRl8mz" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 8.625 4.51)scale(3.69399 9.43628)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="uwe7yhbem"/><stop offset="1" class="snpr2ctwr"/></radialGradient><radialGradient id="it5nT8c" cx="0" cy="0" r="1" gradientTransform="matrix(1.34449 -1.42231 .52067 .49218 13.656 6.163)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="mqqgujbcq"/><stop offset="1" class="fki8vhbsq"/></radialGradient><radialGradient id="iZB4TzA" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 6.883 7.756)scale(1.4619 1.20692)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="lombttb9q"/><stop offset="1" class="bvf2i9bjf"/></radialGradient><radialGradient id="iv0xlsd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .10592 -.3329 0 16.23 8.63)" gradientUnits="userSpaceOnUse"><stop class="t40345qox"/><stop offset="1" class="mrnsdcbqx"/></radialGradient><radialGradient id="iJU8Z1d" cx="0" cy="0" r="1" gradientTransform="rotate(155.369 7.225 5.969)scale(.72614 1.16696)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="o0aif1l1c"/><stop offset="1" class="vni43obah"/></radialGradient><radialGradient id="iun2Ukc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.31275 1.25827 0 16.028 9.575)" gradientUnits="userSpaceOnUse"><stop class="jase_0f7h"/><stop offset="1" class="zn-qjxbde"/></radialGradient><radialGradient id="ii3qQNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.51932 3.84219 0 13.759 6.784)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iGVmyKd" cx="0" cy="0" r="1" gradientTransform="matrix(.04949 -1.09027 1.93173 .08769 18.137 7.353)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="iPfqbbc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.02356 -.6732 .49416 -.75135 17.81 4.63)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="i3ODfnq" cx="0" cy="0" r="1" gradientTransform="matrix(.39276 .64004 -1.48203 .90944 15.636 3.938)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="inD7ErP" cx="0" cy="0" r="1" gradientTransform="matrix(-.95513 0 0 -.35449 16.138 4.919)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="iJz2PWd" cx="0" cy="0" r="1" gradientTransform="matrix(1.39645 -2.21106 2.44963 1.54713 13.672 6.63)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="is5M5Qd" cx="0" cy="0" r="1" gradientTransform="matrix(1.32712 0 0 .51888 17.51 5.256)" gradientUnits="userSpaceOnUse"><stop class="nszf4yi9c"/><stop offset="1" class="a061yvbds"/></radialGradient><radialGradient id="iHWJ8sd" cx="0" cy="0" r="1" gradientTransform="matrix(1.16237 -1.10745 2.02747 2.12801 17.17 6.574)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="ilmvaWd" cx="0" cy="0" r="1" gradientTransform="matrix(1.4095 .16475 -.06898 .59013 16.787 5.933)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="ijEilEn" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35206 -.55998 0 16.975 7.642)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="ipTAuQX" cx="0" cy="0" r="1" gradientTransform="matrix(-.10064 -.12968 .17855 -.13855 16.875 7.679)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iuLvJ9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35207 -.56001 0 15.081 7.642)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iNLHNke" cx="0" cy="0" r="1" gradientTransform="matrix(-.00336 -.2144 .25771 -.00404 14.957 7.737)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iRsmAne" cx="0" cy="0" r="1" gradientTransform="rotate(74.348 3.973 15.713)scale(1.01091 .96449)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="uuzk4vb7h"/><stop offset="1" class="yor2p9b5i"/></radialGradient><radialGradient id="iQDnt0J" cx="0" cy="0" r="1" gradientTransform="matrix(.34184 -.46913 .39322 .28653 18.189 7.885)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="iz6q0pbtm"/><stop offset="1" class="wmov6-bei"/></radialGradient><radialGradient id="ifGox4b" cx="0" cy="0" r="1" gradientTransform="matrix(.25472 -.67278 .89891 .34033 18.238 7.958)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="r8tuldb4n"/><stop offset="1" class="c_6967ufg"/></radialGradient><radialGradient id="iWo2ZOA" cx="0" cy="0" r="1" gradientTransform="matrix(-.7 -.08553 .09181 -.75142 13.895 7.927)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="o8wr4h7sd"/><stop offset="1" class="t0w03e0rr"/></radialGradient><radialGradient id="iaQXeRb" cx="0" cy="0" r="1" gradientTransform="matrix(-.39769 .06826 -.08376 -.48798 13.896 7.927)" gradientUnits="userSpaceOnUse"><stop class="ab9g3hmui"/><stop offset="1" class="bwc1tpbev"/></radialGradient><filter id="itbT9ic" width="7.335" height="7.371" x="13.891" y="10.901" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.075" dy=".08"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.662745 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1156"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.08"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.745098 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1156" result="effect2_innerShadow_4002_1156"/></filter><filter id="ioJIGVb" width="10.517" height="10.517" x="14.14" y="4.72" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1156"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1156" result="effect2_innerShadow_4002_1156"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.788235 0 0 0 0 0.827451 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1156" result="effect3_innerShadow_4002_1156"/></filter><filter id="iop7mdc" width="9.391" height="10.922" x="7.466" y="4.73" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1156"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.545098 0 0 0 0 0.811765 0 0 0 0 0.831373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1156" result="effect2_innerShadow_4002_1156"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.521569 0 0 0 0 0.662745 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1156" result="effect3_innerShadow_4002_1156"/></filter><filter id="iVMOROc" width="7.298" height="7.298" x="10.845" y="10.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.443137 0 0 0 0 0.654902 0 0 0 0 0.905882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1156"/></filter><filter id="i6cj6jc" width="3.908" height="3.642" x="9.545" y="9.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1156"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.941176 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1156" result="effect2_dropShadow_4002_1156"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1156" result="shape"/></filter><filter id="i5lUXKd" width="6.45" height="6.548" x="9.62" y="5.989" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1156"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.941176 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1156" result="effect2_dropShadow_4002_1156"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1156" result="shape"/></filter><filter id="iMAMaFd" width="3.908" height="3.642" x="18.631" y="9.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1156"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.968627 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1156" result="effect2_dropShadow_4002_1156"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1156" result="shape"/></filter><filter id="ivmnz1b" width="6.45" height="6.548" x="16.014" y="5.989" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1156"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.968627 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1156" result="effect2_dropShadow_4002_1156"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1156" result="shape"/></filter><filter id="ieDyiqc" width="1.003" height="4.833" x="22.341" y="4.797" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".35" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.254902 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1156"/></filter><filter id="i0YdaCz" width="4.084" height="3.799" x="20.732" y="2.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.05"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.639216 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1156"/></filter><filter id="il2w90C" width="5.091" height="7.247" x="15.749" y="20.368" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.631373 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1156"/></filter><filter id="i0KWE9c" width="7.578" height="5.434" x="6.015" y="10.552" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.811765 0 0 0 0 0.576471 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1156"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.72549 0 0 0 0 0.470588 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1156" result="effect2_innerShadow_4002_1156"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.67451 0 0 0 0 0.572549 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1156" result="effect3_innerShadow_4002_1156"/></filter><filter id="iC2ARgP" width="1.692" height="1.561" x="6.722" y="14.334" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.54902 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1156"/></filter><filter id="ilSc6xb" width="5.398" height="7.21" x="18.218" y="7.507" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.6"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.517647 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1156"/></filter><filter id="iM4gC0e" width="4.609" height="5.161" x="19.13" y="9.308" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1156" stdDeviation=".25"/></filter><filter id="iLoyAVd" width="1.248" height="2.077" x="21.759" y="8.258" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1156" stdDeviation=".1"/></filter><filter id="iNxcB0c" width=".822" height="1.445" x="22.798" y="8.635" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1156" stdDeviation=".1"/></filter><filter id="iBnTcFe" width="5.435" height="5.555" x="13.831" y="5.362" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.686275 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1156"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.568627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1156" result="effect2_innerShadow_4002_1156"/></filter><filter id="iWQo5yb" width="2.758" height="3.258" x="14.588" y="6.68" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1156" stdDeviation=".5"/></filter><filter id="ikGTKMc" width=".915" height="1.358" x="15.571" y="7.547" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1156" stdDeviation=".025"/></filter><filter id="iAIkB4c" width="5.586" height="3.909" x="13.235" y="3.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1156"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1156" result="effect2_innerShadow_4002_1156"/></filter><filter id="iY8HZ3d" width="1.072" height=".63" x="16.718" y="6.328" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1156"/></filter><filter id="iNQhoze" width="1.072" height=".623" x="14.437" y="6.334" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1156"/></filter><filter id="iOlaPYc" width="3.14" height="2.661" x="13.398" y="4.486" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1156"/><feGaussianBlur result="effect2_foregroundBlur_4002_1156" stdDeviation=".05"/></filter><filter id="irLlF3b" width="2.673" height="2.435" x="16.039" y="4.685" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1156" stdDeviation=".05"/></filter><filter id="iTTXZTb" width=".455" height=".415" x="16.6" y="7.394" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1156" stdDeviation=".05"/></filter><filter id="isGdgyb" width=".613" height=".623" x="16.908" y="7.37" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1156" stdDeviation=".1"/></filter><filter id="iIdWhDd" width=".654" height=".678" x="14.98" y="7.343" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1156" stdDeviation=".1"/></filter><filter id="iOI6Pab" width=".509" height=".419" x="14.709" y="7.391" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1156" stdDeviation=".05"/></filter><filter id="i7bDd7G" width=".86" height="1.315" x="13.248" y="7.269" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1156" stdDeviation=".125"/></filter><filter id="icuLmUd" width="1.411" height="1.826" x="17.7" y="7.016" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1156" stdDeviation=".25"/></filter><linearGradient id="im3tg0d" x1="8.529" x2="12.668" y1="5.843" y2="9.982" gradientUnits="userSpaceOnUse"><stop class="tx327ubjh"/><stop offset="1" class="vxhtc9kgk"/></linearGradient><linearGradient id="iX1BTZW" x1="11.132" x2="10.694" y1="12.966" y2="9.06" gradientUnits="userSpaceOnUse"><stop class="ubeqdvb2g"/><stop offset="1" class="redus_bqs"/></linearGradient><linearGradient id="i6PYywe" x1="22.918" x2="22.549" y1="5.345" y2="6.132" gradientUnits="userSpaceOnUse"><stop offset=".167" class="zqax3vbfg"/><stop offset="1" class="z0_tnl66g"/></linearGradient><linearGradient id="i83V28c" x1="13.263" x2="14.851" y1="19.357" y2="19.357" gradientUnits="userSpaceOnUse"><stop class="x36zqabyv"/><stop offset="1" class="uktlcdafx"/></linearGradient><linearGradient id="i7QnpSd" x1="18.792" x2="16.991" y1="16.247" y2="16.247" gradientUnits="userSpaceOnUse"><stop class="utipi7g6i"/><stop offset="1" class="edfwaihfg"/></linearGradient><linearGradient id="iJU4nte" x1="13.267" x2="15.007" y1="16.431" y2="16.431" gradientUnits="userSpaceOnUse"><stop class="bjaenibkq"/><stop offset="1" class="louyt9b7g"/></linearGradient><linearGradient id="iHwKGuc" x1="15.288" x2="13.817" y1="25.263" y2="25.263" gradientUnits="userSpaceOnUse"><stop offset=".267" class="bs-ywhjno"/><stop offset="1" class="zss1t2k2l"/></linearGradient><linearGradient id="iG2idHc" x1="15.46" x2="14.96" y1="26.669" y2="26.638" gradientUnits="userSpaceOnUse"><stop class="iwsb7zzqk"/><stop offset="1" class="ce0bg7b-n"/></linearGradient><linearGradient id="i7mB2nb" x1="13.261" x2="13.692" y1="25.667" y2="25.667" gradientUnits="userSpaceOnUse"><stop class="tgkl8ebfm"/><stop offset="1" class="wvqlanbxz"/></linearGradient><linearGradient id="iR15onA" x1="15.197" x2="13.71" y1="28.891" y2="28.891" gradientUnits="userSpaceOnUse"><stop class="htqsm-l2e"/><stop offset=".159" class="zd1r_u8ze"/><stop offset=".453" class="x09-01b7i"/><stop offset="1" class="s_f01nb2h"/></linearGradient><linearGradient id="iIEs1Hd" x1="18.825" x2="18.351" y1="24.378" y2="24.091" gradientUnits="userSpaceOnUse"><stop class="gqr8sybry"/><stop offset="1" class="lpb-gbbwk"/></linearGradient><linearGradient id="iFc3g8a" x1="15.749" x2="17.116" y1="25.981" y2="27.044" gradientUnits="userSpaceOnUse"><stop class="ilfb1o36w"/><stop offset="1" class="q6qjg9bpc"/></linearGradient><linearGradient id="iRxWrGd" x1="16.065" x2="16.065" y1="10.717" y2="15.553" gradientUnits="userSpaceOnUse"><stop class="ctgol8ben"/><stop offset="1" class="d2j7ihp4i"/></linearGradient><linearGradient id="iesVFwd" x1="13.303" x2="15.492" y1="14.749" y2="14.749" gradientUnits="userSpaceOnUse"><stop offset=".01" class="k4svfjbzs"/><stop offset="1" class="k0oa_8bou"/></linearGradient><linearGradient id="i9tL5Vd" x1="22.63" x2="20.036" y1="11.605" y2="13.448" gradientUnits="userSpaceOnUse"><stop offset=".453" class="yyuqaqb0l"/><stop offset="1" class="g_3g2umds"/></linearGradient><linearGradient id="in0SVNc" x1="22.059" x2="21.755" y1="8.558" y2="10.249" gradientUnits="userSpaceOnUse"><stop class="a7sb80b8g"/><stop offset="1" class="f7acardkn"/></linearGradient><linearGradient id="iXQsZLe" x1="23.07" x2="22.804" y1="8.935" y2="9.896" gradientUnits="userSpaceOnUse"><stop class="a7sb80b8g"/><stop offset="1" class="f7acardkn"/></linearGradient><linearGradient id="ifMJ0Sb" x1="18.266" x2="16.378" y1="8.771" y2="8.771" gradientUnits="userSpaceOnUse"><stop class="z1p__59we"/><stop offset="1" class="y6b283b4c"/></linearGradient><linearGradient id="itXVb3d" x1="16.65" x2="16.028" y1="8.226" y2="8.347" gradientUnits="userSpaceOnUse"><stop class="af2d-kbww"/><stop offset="1" class="fkbu2fb2z"/></linearGradient><linearGradient id="iUl0pAu" x1="16.028" x2="16.028" y1="8.827" y2="8.625" gradientUnits="userSpaceOnUse"><stop class="y8u9aob3m"/><stop offset="1" class="w22vs7beb"/></linearGradient><linearGradient id="i1AJYHb" x1="16.028" x2="16.028" y1="7.597" y2="7.89" gradientUnits="userSpaceOnUse"><stop class="au2s26bkj"/><stop offset="1" class="e0f0u6bhi"/></linearGradient><linearGradient id="i6R8yjb" x1="19.002" x2="13.963" y1="5.582" y2="5.582" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="iW8gqvb" x1="17.313" x2="17.176" y1="7.665" y2="7.749" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ikXsKvd" x1="15.404" x2="15.268" y1="7.665" y2="7.749" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i2lX03L" x1="18.821" x2="18.297" y1="7.677" y2="8.621" gradientUnits="userSpaceOnUse"><stop class="r7o08-b3s"/><stop offset="1" class="g6f16-bty"/></linearGradient><linearGradient id="i3ZidRd" x1="13.49" x2="14.123" y1="7.983" y2="7.927" gradientUnits="userSpaceOnUse"><stop class="mlsv8jb5y"/><stop offset="1" class="l7gss9bru"/></linearGradient><linearGradient id="iX2yeNb" x1="18.406" x2="18.406" y1="7.516" y2="8.342" gradientUnits="userSpaceOnUse"><stop class="q26gyrbrn"/><stop offset="1" class="ihk5xnqly"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-fairy-light" /></template>
<style>
.a061yvbds {
  stop-color: var(--svg-color--4e494b, #4E494B);
  stop-opacity: 0;
}

.a7sb80b8g {
  stop-color: var(--svg-color--e5b5a5, #E5B5A5);
}

.ab9g3hmui {
  stop-color: var(--svg-color--c18472, #C18472);
}

.af2d-kbww {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
}

.aii5rr2eq {
  stop-color: var(--svg-color--eeb39e, #EEB39E);
}

.alg5_vbml {
  stop-color: var(--svg-color--e49d85, #E49D85);
  stop-opacity: 0;
}

.au2s26bkj {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.b13j0jria {
  stop-color: var(--svg-color--f4baae, #F4BAAE);
}

.b3bsg4k1o {
  cx: 14.964px;
  cy: 7.6px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.169px;
  ry: 0.086px;
}

.b47wb-b1b {
  d: path("m17.672 21.275l-.082-.227l2.331-.48c.02.062.094.292.219.71c.125.42-.01.774-.094.899l-3.269 5.344c-.07.116-.233.128-.311.017c-.297-.42-.547-.974-.686-1.358a.55.55 0 0 1 .023-.42l1.85-4.032a.6.6 0 0 0 .019-.453");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bjaenibkq {
  stop-color: var(--svg-color--839927, #839927);
}

.bm7w23b9t {
  d: path("m13.312 28.098l.006 1.49c0 .169.164.288.322.231c.348-.125.845-.33 1.287-.603a.47.47 0 0 0 .215-.373l.055-.894z");
}

.bs-ywhjno {
  stop-color: var(--svg-color--ffd1bd, #FFD1BD);
}

.bvf2i9bjf {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
  stop-opacity: 0;
}

.bwc1tpbev {
  stop-color: var(--svg-color--ca8b7a, #CA8B7A);
}

.c_6967ufg {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
}

.c0317ln8x {
  stop-color: var(--svg-color--c9747e, #C9747E);
}

.c6dvfyb6s {
  stop-color: var(--svg-color--e94a61, #E94A61);
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.cbof9-bgu {
  d: path("m15.862 7.73l-.23.797c-.047.164.066.328.226.328h.34c.16 0 .274-.166.227-.328l-.23-.798a.171.171 0 0 0-.333 0");
}

.ce0bg7b-n {
  stop-color: var(--svg-color--f5b7a1, #F5B7A1);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.ctgol8ben {
  stop-color: var(--svg-color--ff8328, #FF8328);
}

.cw-i9xbem {
  stop-color: var(--svg-color--ba8d88, #BA8D88);
}

.d2j7ihp4i {
  stop-color: var(--svg-color--ff712e, #FF712E);
}

.dej2ynjul {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.066 7.317c.283 0 .523.195.588.46a.12.12 0 0 1-.116.147h-.968a.1.1 0 0 1-.1-.118a.61.61 0 0 1 .596-.489");
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.e_uyjoq0f {
  fill: var(--svg-color--23181c, #23181C);
  d: path("m16.13 5.603l-.03-.06a.29.29 0 0 0-.267-.181h-.552c-.8 0-1.45.656-1.45 1.466v.12c-.147-.113-.333-.35-.333-.733c0-.465.34-.7.556-.85c.06-.042.112-.078.143-.11l.043-.045c.152-.161.422-.448.894-.573a2 2 0 0 1 .197-.042c.466-.076.807.344.807.817v.185z");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e0f0u6bhi {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
  stop-opacity: 0;
}

.e593k4bfv {
  fill: var(--svg-color--aed62f, #AED62F);
  d: path("M13.267 16.349v-.82h5.525v.82c-2.337.148-4.276.062-5.525 0");
}

.ea_bogbnf {
  cx: 14.964px;
  cy: 7.6px;
  rx: 0.169px;
  ry: 0.086px;
}

.eb_lzfbwh {
  fill: var(--svg-color--202020, #202020);
  d: path("M17.648 6.747a.8.8 0 0 0-.298-.179a1.25 1.25 0 0 0-.527-.025a.12.12 0 1 0 .03.24c.208-.026.336-.013.424.015a.6.6 0 0 1 .213.13a.12.12 0 0 0 .158-.181");
}

.eclr80brm {
  d: path("M13.84 7.233a.698.698 0 0 0 .056 1.389a34 34 0 0 1-.057-1.39");
}

.edfwaihfg {
  stop-color: var(--svg-color--bff332, #BFF332);
  stop-opacity: 0;
}

.ek_f7q3hx {
  stop-color: var(--svg-color--1a161e, #1A161E);
}

.er079sbvz {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.047 9.264a.21.21 0 1 0-.284.31l1.82 1.668l-.84.085a.21.21 0 0 0 .043.418l1.21-.124l.955.875a.21.21 0 1 0 .284-.31z");
}

.etm0labvf {
  width: 4.843px;
  height: 8.191px;
  x: 12.963px;
  y: 13.403px;
  rx: 2.422px;
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f0h56obba {
  fill: var(--svg-color--000, #000);
  d: path("M15.302 7.822a.22.22 0 0 0-.222-.222a.22.22 0 0 0-.197.324h.393a.2.2 0 0 0 .026-.102");
}

.f7acardkn {
  stop-color: var(--svg-color--e5b5a5, #E5B5A5);
  stop-opacity: 0;
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fdljuobxe {
  fill: var(--svg-color--fbc5b5, #FBC5B5);
  d: path("m17.672 21.275l-.082-.227l2.331-.48c.02.062.094.292.219.71c.125.42-.01.774-.094.899l-3.269 5.344c-.07.116-.233.128-.311.017c-.297-.42-.547-.974-.686-1.358a.55.55 0 0 1 .023-.42l1.85-4.032a.6.6 0 0 0 .019-.453");
}

.ffese-y7m {
  width: 6.894px;
  height: 11.735px;
  rx: 3.447px;
}

.fkbu2fb2z {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
  stop-opacity: 0;
}

.fkflyvb_m {
  fill: var(--svg-color--f1bdad, #F1BDAD);
  d: path("M13.28 11.279c.194-.188.29-.23.313-.227v2.59c-.399.557-1.783 1.92-3.508 2.176c-1.615.24-2.64-.206-2.883-.47a4 4 0 0 0-.448.378a.44.44 0 0 1-.556.045a.444.444 0 0 1-.133-.561c.558-1.026 1.462-1.373 2.887-1.33c1.256.038 2.117-.52 2.39-.805c.566-.52 1.744-1.609 1.938-1.796");
}

.fki8vhbsq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g_3g2umds {
  stop-color: var(--svg-color--ffe1c7, #FFE1C7);
  stop-opacity: 0;
}

.g3opglbhy {
  d: path("m18.29 7.02l-.012-.274a.637.637 0 0 0-.61-.618h-.608a1.05 1.05 0 0 1-.921-.547s.312-.902.83-.785c.38.085.785.22 1.095.422c.757.493.625 1.383.226 1.802");
}

.g6f16-bty {
  stop-color: var(--svg-color--f0b8a6, #F0B8A6);
}

.gaq7fe30j {
  fill: var(--svg-color--1f151b, #1F151B);
  d: path("m18.29 7.02l-.012-.274a.637.637 0 0 0-.61-.618h-.608a1.05 1.05 0 0 1-.921-.547s.312-.902.83-.785c.38.085.785.22 1.095.422c.757.493.625 1.383.226 1.802");
}

.gfuj0ibqm {
  stop-color: var(--svg-color--1e191c, #1E191C);
}

.gqr8sybry {
  stop-color: var(--svg-color--e9b9ad, #E9B9AD);
}

.h_sz7dx-m {
  d: path("m16.13 5.603l-.03-.06a.29.29 0 0 0-.267-.181h-.552c-.8 0-1.45.656-1.45 1.466v.12c-.147-.113-.333-.35-.333-.733c0-.465.34-.7.556-.85c.06-.042.112-.078.143-.11l.043-.045c.152-.161.422-.448.894-.573a2 2 0 0 1 .197-.042c.466-.076.807.344.807.817v.185z");
}

.h2pt4jb3o {
  d: path("M7.08 15.003c.177-.133.339-.264.43-.342c.416-.346.637-.217.723-.128c.1.102.145.418-.093.695c-.25.29-.51.464-.735.601c-.165.1-.46.088-.582-.062c-.238-.242-.014-.561.256-.764");
}

.h739mqb_c {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
}

.h88botbvf {
  d: path("M18.135 5.157a1.03 1.03 0 0 1 .504 1.552a.7.7 0 0 0-.117.38v.515a.8.8 0 0 0-.29-.116l.034-.697a.63.63 0 0 0-.598-.622h-.608a1.05 1.05 0 0 1-.96-.626a.29.29 0 0 0-.267-.181h-.552c-.8 0-1.45.656-1.45 1.466l.014.667a.74.74 0 0 0-.313.115v-.521a.7.7 0 0 0-.117-.38a1.04 1.04 0 0 1-.062-1.061c.126-.24.33-.407.563-.489c.249-.088.46-.256.601-.481a1.01 1.01 0 0 1 1.254-.396a.65.65 0 0 0 .518 0a1.01 1.01 0 0 1 1.259.41c.134.22.343.381.587.465");
}

.hg82k5vsb {
  d: path("M15.434 7.777c0-.125-.101-.209-.129-.234l-.125.12l.077.158z");
}

.hhdmmdbln {
  d: path("M16.976 7.435a.387.387 0 0 1 .373.49h-.748a.39.39 0 0 1 .375-.49");
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.hq3hkib4c {
  stop-color: var(--svg-color--e0521f, #E0521F);
}

.htqsm-l2e {
  stop-color: var(--svg-color--664e86, #664E86);
}

.hts433_5m {
  stop-color: var(--svg-color--ff9842, #FF9842);
  stop-opacity: 0;
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.ifffzhsgp {
  fill: var(--svg-color--000, #000);
  d: path("M16.754 7.822a.22.22 0 0 1 .222-.222a.22.22 0 0 1 .197.324h-.392a.2.2 0 0 1-.027-.102");
}

.ignt4ubkd {
  stop-color: var(--svg-color--ff9842, #FF9842);
}

.ihk5xnqly {
  stop-color: var(--svg-color--f6bba0, #F6BBA0);
}

.ikgkim2qs {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M22.06 8.558v.505a1 1 0 0 0 .433.824l.215.147");
}

.ilfb1o36w {
  stop-color: var(--svg-color--352b41, #352B41);
}

.ip469ff8c {
  stop-color: var(--svg-color--ff8045, #FF8045);
}

.is_m6u3tw {
  stop-color: var(--svg-color--c36f72, #C36F72);
  stop-opacity: 0;
}

.is89u6ban {
  d: path("M8.523 10.723a3.454 3.454 0 0 1 .006-4.88a3.454 3.454 0 0 1 4.88-.006l1.19 1.19c.338.337.602.742.775 1.188l1.2 3.086c.154.398.233.822.233 1.249v.56a2.443 2.443 0 0 1-4.17 1.727z");
}

.iwsb7zzqk {
  stop-color: var(--svg-color--f5b7a1, #F5B7A1);
}

.iz6q0pbtm {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
}

.jase_0f7h {
  stop-color: var(--svg-color--88014e, #88014E);
}

.jic9bm_zi {
  d: path("M15.07 10.486v.349a.24.24 0 0 0 .065.157c.135.147.326.443.456.87c.06.195.233.342.437.342a.47.47 0 0 0 .437-.342c.13-.427.322-.723.457-.87a.24.24 0 0 0 .065-.157v-.35z");
}

.jt7j1ibzr {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.948 7.517c.027.037-.03.082-.096.13c-.066.05-.114.084-.142.047s.003-.106.069-.155c.066-.05.141-.06.169-.022");
}

.k_rioyb_p {
  stop-color: var(--svg-color--e0521f, #E0521F);
  stop-opacity: 0;
}

.k0oa_8bou {
  stop-color: var(--svg-color--f36b26, #F36B26);
  stop-opacity: 0;
}

.k356i5yuc {
  stop-color: var(--svg-color--91deff, #91DEFF);
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.k4svfjbzs {
  stop-color: var(--svg-color--d35c1b, #D35C1B);
}

.kgna9sqpj {
  stop-color: var(--svg-color--ffe5ca, #FFE5CA);
  stop-opacity: 0;
}

.kwrq70t3y {
  fill: var(--svg-color--fb652d, #FB652D);
  d: path("M13.263 21.733V16.26l5.529.056c0 .348.063.666.09.765l1.042 3.486l-2.33.484l-.865-2.223c-.132-.336-.285-.64-.504-.64c-.25 0-.356.391-.361.59l-.28 3.011z");
}

.kxaprmbjh {
  stop-color: var(--svg-color--d39991, #D39991);
}

.kydculhfm {
  stop-color: var(--svg-color--272127, #272127);
}

.l1vex1b6a {
  stop-color: var(--svg-color--443d40, #443D40);
}

.l7gss9bru {
  stop-color: var(--svg-color--c9887d, #C9887D);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lombttb9q {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
}

.louyt9b7g {
  stop-color: var(--svg-color--afd730, #AFD730);
  stop-opacity: 0;
}

.lpb-gbbwk {
  stop-color: var(--svg-color--e9b9ad, #E9B9AD);
  stop-opacity: 0;
}

.m0kz_y80u {
  d: path("m13.318 29.589l-.057-7.861l2.32.062l-.438 7.053a.47.47 0 0 1-.216.373a7 7 0 0 1-1.287.603a.242.242 0 0 1-.322-.23");
}

.m8pucsqyt {
  fill: var(--svg-color--fff, #fff);
  d: path("M22.037 9.264a.21.21 0 1 1 .283.31l-1.819 1.668l.84.085a.21.21 0 0 1-.043.418l-1.211-.124l-.954.875a.21.21 0 1 1-.284-.31z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mlsv8jb5y {
  stop-color: var(--svg-color--d19787, #D19787);
}

.mqqgujbcq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
}

.mrnsdcbqx {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
  stop-opacity: 0;
}

.n5igrlbfw {
  stop-color: var(--svg-color--593569, #593569);
  stop-opacity: 0;
}

.njax42eii {
  stop-color: var(--svg-color--f1bdad, #F1BDAD);
}

.nl4f7twra {
  width: 0.703px;
  height: 4.633px;
  x: 22.341px;
  y: 4.997px;
  rx: 0.352px;
}

.nov_osbjm {
  stop-color: var(--svg-color--e19d8a, #E19D8A);
}

.nr-yk7zrs {
  d: path("M16.052 10.718c-.437.015-1.42.083-1.985.163c-.721.101-.764.71-.764.992v3.68h5.525v-3.68c0-.281-.044-.89-.765-.992a25 25 0 0 0-1.985-.163z");
}

.nsd5d_b3f {
  d: path("m18.2 8.342l.048-.826a.415.415 0 0 1-.048.826");
}

.nszf4yi9c {
  stop-color: var(--svg-color--4e494b, #4E494B);
}

.nw_aknb7y {
  stop-color: var(--svg-color--ffc736, #FFC736);
}

.ny0rq0bux {
  stop-color: var(--svg-color--d6a195, #D6A195);
}

.o00ub9bxb {
  fill: var(--svg-color--dea899, #DEA899);
  d: path("m15.862 7.73l-.23.797c-.047.164.066.328.226.328h.34c.16 0 .274-.166.227-.328l-.23-.798a.171.171 0 0 0-.333 0");
}

.o0aif1l1c {
  stop-color: var(--svg-color--d3968c, #D3968C);
  stop-opacity: 0;
}

.o8wr4h7sd {
  stop-color: var(--svg-color--e8af99, #E8AF99);
  stop-opacity: 0;
}

.o9g1acb4z {
  fill: var(--svg-color--d69790, #D69790);
  d: path("m15.854 7.812l-.256.798c-.044.164.061.328.21.328h.317c.15 0 .254-.167.21-.328l-.214-.798c-.046-.177-.219-.177-.267 0");
}

.oa3f9ve3k {
  d: path("M22.5 2.293a.22.22 0 0 1 .4.001l.413.896a.22.22 0 0 0 .175.126l.983.115a.22.22 0 0 1 .128.376l-.734.716a.22.22 0 0 0-.062.2l.185.926a.22.22 0 0 1-.32.237l-.864-.459a.22.22 0 0 0-.206 0l-.87.462a.22.22 0 0 1-.32-.235l.178-.932a.22.22 0 0 0-.062-.198l-.727-.718a.22.22 0 0 1 .13-.375l.98-.115a.22.22 0 0 0 .174-.125z");
}

.oaig2cbln {
  stop-color: var(--svg-color--564943, #564943);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ojh7ovyuq {
  d: path("M13.822 7.52a.415.415 0 0 0 .036.815a34 34 0 0 1-.037-.816");
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.oz3_ipb8v {
  stop-color: var(--svg-color--e94a61, #E94A61);
  stop-opacity: 0;
}

.p49pqvmwt {
  d: path("M18.164 8.621q.044-.692.08-1.384a.698.698 0 0 1-.08 1.384");
}

.p5u-_cblu {
  stop-color: var(--svg-color--603b8b, #603B8B);
}

.p8zhg8wps {
  stop-color: var(--svg-color--c36f72, #C36F72);
}

.paqwmgfbp {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.99 7.317a.606.606 0 0 0-.587.46a.12.12 0 0 0 .116.147h.968a.1.1 0 0 0 .099-.118a.61.61 0 0 0-.595-.489");
}

.pha_6_rva {
  stop-color: var(--svg-color--94d8ff, #94D8FF);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.psaan41ml {
  d: path("M13.935 9.24a1.7 1.7 0 0 0 1.686 1.477h.818a1.7 1.7 0 0 0 1.687-1.478c.05-.817.102-1.631.14-2.448a.63.63 0 0 0-.598-.622h-.608a1.05 1.05 0 0 1-.96-.626a.29.29 0 0 0-.266-.181h-.553c-.8 0-1.45.656-1.45 1.466c0 .807.05 1.602.104 2.411");
}

.pt-h1ccpi {
  stop-color: var(--svg-color--febb35, #FEBB35);
}

.pu7gpfbtr {
  fill: var(--svg-color--202020, #202020);
  d: path("M14.548 6.7a1.2 1.2 0 0 1 .755-.156a.12.12 0 1 1-.03.238a.96.96 0 0 0-.634.145l-.007.005h-.001a.12.12 0 0 1-.148-.19z");
}

.pv3dgeoha {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.68 6.325a.21.21 0 0 1 .418.048l-.159 1.385l1.024-.928a.21.21 0 1 1 .282.311l-5.73 5.192a.21.21 0 0 1-.282-.312l4.234-3.836z");
}

.px0sb7ebt {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
  stop-opacity: 0;
}

.q26gyrbrn {
  stop-color: var(--svg-color--f9bb9e, #F9BB9E);
}

.q6qjg9bpc {
  stop-color: var(--svg-color--64468a, #64468A);
}

.qco-2_b3r {
  stop-color: var(--svg-color--484646, #484646);
}

.qlfye6p8o {
  stop-color: var(--svg-color--ffd545, #FFD545);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r7o08-b3s {
  stop-color: var(--svg-color--ffd6bd, #FFD6BD);
}

.r8tuldb4n {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
  stop-opacity: 0;
}

.r9m8_svvg {
  width: 0.703px;
  height: 4.633px;
  x: 22.341px;
  y: 4.997px;
  fill: var(--svg-color--9a6159, #9A6159);
  rx: 0.352px;
}

.redus_bqs {
  stop-color: var(--svg-color--87c9fb, #87C9FB);
  stop-opacity: 0;
}

.rivz2obdn {
  stop-color: var(--svg-color--91e5ff, #91E5FF);
}

.rlebc9g3p {
  d: path("M16.948 7.517c.027.037-.03.082-.096.13c-.066.05-.114.084-.142.047s.003-.106.069-.155c.066-.05.141-.06.169-.022");
}

.s_et88bec {
  stop-color: var(--svg-color--ffd545, #FFD545);
}

.s_f01nb2h {
  stop-color: var(--svg-color--4b3866, #4B3866);
}

.s2ceddo5o {
  stop-color: var(--svg-color--80caf3, #80CAF3);
}

.s3hklabia {
  stop-color: var(--svg-color--593569, #593569);
}

.s3qcrxbjw {
  stop-color: var(--svg-color--d3947d, #D3947D);
}

.saunobcmg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m19.88 12.667l2.672 1.045a.1.1 0 0 0 .136-.085l.301-3.57");
}

.sb1zj3bbu {
  stop-color: var(--svg-color--fccbb7, #FCCBB7);
  stop-opacity: 0;
}

.sie3y1b1c {
  d: path("M18.138 8.582a.7.7 0 0 0 .392-.134v.404c0 .387-.23.733-.582.876q.112-.236.15-.512z");
}

.sl-3t4bfx {
  stop-color: var(--svg-color--e43423, #E43423);
}

.snpr2ctwr {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.t0w03e0rr {
  stop-color: var(--svg-color--e8af99, #E8AF99);
}

.t2qxtb2ul {
  stop-color: var(--svg-color--e5af9f, #E5AF9F);
  stop-opacity: 0;
}

.t40345qox {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
}

.tdcimfbag {
  fill: var(--svg-color--eab8a0, #EAB8A0);
  d: path("M7.08 15.003c.177-.133.339-.264.43-.342c.416-.346.637-.217.723-.128c.1.102.145.418-.093.695c-.25.29-.51.464-.735.601c-.165.1-.46.088-.582-.062c-.238-.242-.014-.561.256-.764");
}

.tdjl0hblu {
  stop-color: var(--svg-color--fccbb7, #FCCBB7);
}

.tgkl8ebfm {
  stop-color: var(--svg-color--f1b69f, #F1B69F);
}

.tx327ubjh {
  stop-color: var(--svg-color--8eefff, #8EEFFF);
}

.u2cv5hb3z {
  d: path("M17.32 7.771a.37.37 0 0 0-.1-.2l-.112.123l.05.1z");
}

.ubeqdvb2g {
  stop-color: var(--svg-color--87c9fb, #87C9FB);
}

.uktlcdafx {
  stop-color: var(--svg-color--dd4920, #DD4920);
  stop-opacity: 0;
}

.un08nrbhl {
  stop-color: var(--svg-color--ff6737, #FF6737);
  stop-opacity: 0;
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.uodqeubaz {
  stop-color: var(--svg-color--94d8ff, #94D8FF);
}

.uowu7rarb {
  stop-color: var(--svg-color--603b8b, #603B8B);
  stop-opacity: 0;
}

.utdakeidf {
  stop-color: var(--svg-color--ff7e38, #FF7E38);
  stop-opacity: 0;
}

.utipi7g6i {
  stop-color: var(--svg-color--bff332, #BFF332);
}

.uu9c01xwt {
  d: path("M13.28 11.279c.194-.188.29-.23.313-.227v2.59c-.399.557-1.783 1.92-3.508 2.176c-1.615.24-2.64-.206-2.883-.47a4 4 0 0 0-.448.378a.44.44 0 0 1-.556.045a.444.444 0 0 1-.133-.561c.558-1.026 1.462-1.373 2.887-1.33c1.256.038 2.117-.52 2.39-.805c.566-.52 1.744-1.609 1.938-1.796");
}

.uuzk4vb7h {
  stop-color: var(--svg-color--ce978e, #CE978E);
  stop-opacity: 0;
}

.uwe7yhbem {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
  stop-opacity: 0;
}

.uxuczv7gs {
  d: path("M13.919 8.582a.7.7 0 0 1-.393-.134v.404c0 .387.231.733.582.876a1.8 1.8 0 0 1-.15-.512z");
}

.v_k-57lgf {
  stop-color: var(--svg-color--ffdd49, #FFDD49);
  stop-opacity: 0;
}

.v0q_-i93u {
  stop-color: var(--svg-color--ff8045, #FF8045);
  stop-opacity: 0;
}

.v0rf09b-u {
  d: path("M16.028 9.296c-.22 0-.427-.051-.6-.142c-.06-.03-.124.037-.087.09c.146.22.399.368.687.368a.82.82 0 0 0 .687-.367c.038-.057-.026-.121-.085-.091a1.3 1.3 0 0 1-.602.142");
}

.vgn1hf8dm {
  stop-color: var(--svg-color--d39991, #D39991);
  stop-opacity: 0;
}

.vm1_cbcaw {
  stop-color: var(--svg-color--90eeff, #90EEFF);
}

.vni43obah {
  stop-color: var(--svg-color--d3968c, #D3968C);
}

.vvvf-bx0b {
  stop-color: var(--svg-color--93efff, #93EFFF);
}

.vw5e4lbve {
  stop-color: var(--svg-color--ffdd49, #FFDD49);
}

.vxhtc9kgk {
  stop-color: var(--svg-color--8bd2ff, #8BD2FF);
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w22vs7beb {
  stop-color: var(--svg-color--d89793, #D89793);
  stop-opacity: 0;
}

.w4_din79c {
  d: path("M15.08 7.435a.387.387 0 0 0-.373.49h.748a.39.39 0 0 0-.375-.49");
}

.wibfg_jba {
  stop-color: var(--svg-color--ffe5ca, #FFE5CA);
}

.wmov6-bei {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
  stop-opacity: 0;
}

.wvqlanbxz {
  stop-color: var(--svg-color--f1b69f, #F1B69F);
  stop-opacity: 0;
}

.www4dfogh {
  stop-color: var(--svg-color--d69b93, #D69B93);
  stop-opacity: 0;
}

.wyv1gnbxf {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
}

.x09-01b7i {
  stop-color: var(--svg-color--634689, #634689);
}

.x36zqabyv {
  stop-color: var(--svg-color--c45538, #C45538);
}

.x6_m96bez {
  stop-color: var(--svg-color--85d1fb, #85D1FB);
}

.xhtzkfsjn {
  d: path("M13.267 16.349v-.82h5.525v.82c-2.337.148-4.276.062-5.525 0");
}

.xnxf0re5w {
  stop-color: var(--svg-color--ff7e38, #FF7E38);
}

.xo-vurl-f {
  stop-color: var(--svg-color--ff6737, #FF6737);
}

.xsgkrbcbf {
  stop-color: var(--svg-color--313131, #313131);
}

.y6b283b4c {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
  stop-opacity: 0;
}

.y8u9aob3m {
  stop-color: var(--svg-color--d89793, #D89793);
}

.yhlqt4zud {
  d: path("M13.263 21.733V16.26l5.529.056c0 .348.063.666.09.765l1.042 3.486l-2.33.484l-.865-2.223c-.132-.336-.285-.64-.504-.64c-.25 0-.356.391-.361.59l-.28 3.011z");
}

.ykkax8bmp {
  stop-color: var(--svg-color--d3a086, #D3A086);
}

.yor2p9b5i {
  stop-color: var(--svg-color--ce978e, #CE978E);
}

.ytl8wkbiv {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.403 6.325a.21.21 0 0 0-.417.048l.159 1.385l-1.024-.928a.21.21 0 1 0-.282.311l5.73 5.192a.21.21 0 0 0 .282-.312l-4.235-3.836z");
}

.yv8187b0r {
  stop-color: var(--svg-color--c38488, #C38488);
}

.ywqn4-bmn {
  stop-color: var(--svg-color--f1bdad, #F1BDAD);
  stop-opacity: 0;
}

.yyuqaqb0l {
  stop-color: var(--svg-color--ffe1c7, #FFE1C7);
}

.yzaj_tb_p {
  stop-color: var(--svg-color--ffdcc0, #FFDCC0);
}

.z_5s59bdn {
  width: 4.843px;
  height: 8.244px;
  rx: 2.422px;
}

.z0_tnl66g {
  stop-color: var(--svg-color--6c2d29, #6C2D29);
  stop-opacity: 0;
}

.z1p__59we {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
}

.z1su76bfy {
  stop-color: var(--svg-color--d3a086, #D3A086);
  stop-opacity: 0;
}

.z30kudb-o {
  cx: 6.572px;
  cy: 15.685px;
  r: 0.438px;
}

.z45oacyxz {
  d: path("m17.397 26.507l-.62 1.014c-.07.116-.233.128-.311.017c-.297-.42-.547-.974-.686-1.358a.55.55 0 0 1 .023-.42l.466-1.017z");
}

.z6d-f52gr {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
  stop-opacity: 0;
}

.zd1r_u8ze {
  stop-color: var(--svg-color--6a4e8f, #6A4E8F);
}

.zeih87brn {
  stop-color: var(--svg-color--e43423, #E43423);
  stop-opacity: 0;
}

.zh46g387g {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M23.32 8.935v.258a.9.9 0 0 1-.25.617v0");
}

.zn-qjxbde {
  stop-color: var(--svg-color--86004d, #86004D);
}

.zqax3vbfg {
  stop-color: var(--svg-color--6c2d29, #6C2D29);
}

.zss1t2k2l {
  stop-color: var(--svg-color--ebb3a3, #EBB3A3);
}

.zt9dwabzu {
  fill: var(--svg-color--f2b7a1, #F2B7A1);
  d: path("m21.499 12.27l-3.144-1.206l-.137 2.175l3.578 1.368c.185.083.652.2 1.039 0s.516-.72.531-.953l.249-4.56a.433.433 0 0 0-.433-.456h-.007a.137.137 0 0 0-.137.137v.48a.344.344 0 0 1-.687 0V8.51a.404.404 0 0 0-.805-.035c-.013.162-.03.366-.047.6c-.037.494.276.836.438.961z");
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

</style>
