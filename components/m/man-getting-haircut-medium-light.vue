<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ikQo4hb)" class="vsd5z4bzn"/><path fill="url(#iTJaJmb)" class="vsd5z4bzn"/><path fill="url(#iEzDb0x)" class="vsd5z4bzn"/><path fill="url(#iEVCODs)" class="vsd5z4bzn"/><path fill="url(#igdhcyc)" class="vsd5z4bzn"/><path fill="url(#i0G4Fnc)" class="duamz0b8m"/><path fill="url(#iHwC75H)" class="duamz0b8m"/><path class="eic4j5j0i"/><path fill="url(#iTeqUld)" class="b6k1axmhp"/><path fill="url(#imeqhId)" class="b6k1axmhp"/><path class="xtr1tybzs"/><path fill="url(#ie68eYd)" class="sdwn2xbgr"/><path fill="url(#iRGdTsd)" class="sdwn2xbgr"/><g filter="url(#iypzuqd)"><circle fill="url(#ioTcMpc)" class="t-xw98brg"/></g><g filter="url(#iCtMPDP)"><circle fill="url(#isCRgJb)" class="j_0_l0dzh"/></g><g filter="url(#ih8qj9d)"><circle fill="url(#i8aCzeE)" class="qi89ecakj"/><circle fill="url(#i69l3nc)" class="qi89ecakj"/></g><g filter="url(#iZrabjb)"><circle class="m5h_2yb7z"/><circle fill="url(#iX3OZ0b)" class="ropjnrb-t"/><circle fill="url(#iNao9Ab)" class="ropjnrb-t"/></g><g filter="url(#imDOddB)"><path fill="url(#i5tzCeb)" class="td5sfhbse"/><path fill="url(#i8xKV7I)" class="td5sfhbse"/><path fill="url(#iOFUUce)" class="td5sfhbse"/><path fill="url(#iovplDe)" class="td5sfhbse"/><path fill="url(#i03Lk6c)" class="td5sfhbse"/></g><g filter="url(#iAWe43W)"><path class="wodlq0j2b"/><path fill="url(#ixJVFFd)" class="kfb9k_bug"/><path fill="url(#isZxE6u)" class="kfb9k_bug"/><path fill="url(#iEfYfve)" class="kfb9k_bug"/><path fill="url(#iJ1IBRb)" class="kfb9k_bug"/><path fill="url(#iWsGUwc)" class="kfb9k_bug"/></g><path fill="url(#icUTUuC)" class="kfb9k_bug"/><path fill="url(#iRZ1Fse)" class="kfb9k_bug"/><g filter="url(#isd55Vc)"><path class="o79a7bclz"/></g><g filter="url(#i9xzZKc)"><path class="u207l-w-d"/><path fill="url(#ihwHGob)" class="tq594abms"/><path fill="url(#i2ejT7m)" class="tq594abms"/><path fill="url(#inb0Tmd)" class="tq594abms"/></g><path stroke="url(#iXPnJ5d)" class="pv5af87fu"/><g filter="url(#i23oxJc)"><path class="csh7z6x1o"/></g><g filter="url(#iWbPPWb)"><path class="itf2z1bmi"/></g><path class="mzd4cyb6c"/><path fill="url(#ixwwTjX)" class="xuv1spb_l"/><path class="w288a_boz"/><g filter="url(#iMz5s5H)"><path class="d85-ehcsj"/><path fill="url(#iTyb5ee)" class="n8442jnle"/></g><g filter="url(#i2llelb)"><path fill="url(#iDhxooe)" class="pj18qir8q"/></g><path class="baiadf44i"/><path fill="url(#iQlviYn)" class="xx8xnnb2g"/><path class="omozuebmd"/><g filter="url(#inLAxfc)"><path fill="url(#iIPG9wd)" class="e564nzbob"/></g><g filter="url(#iqPRsEe)"><ellipse transform="rotate(-27.914 12.179 12.057)" class="wmbqnx98e"/><ellipse fill="url(#i2bjZte)" transform="rotate(-27.914 12.179 12.057)" class="leh3g6bge"/></g><g filter="url(#i951pMd)"><path stroke="url(#ifLFKcD)" class="yqrihcbbb"/></g><g filter="url(#iqoaCPd)"><path stroke="url(#iXGQFed)" class="lnwtx-bmv"/></g><path fill="url(#i8iTnId)" class="son215bua"/><path fill="url(#iOcgpve)" class="son215bua"/><path fill="url(#i0zRyEb)" class="son215bua"/><path fill="url(#itKwPXc)" class="wbyyasbet"/><path fill="url(#ip9aQEE)" class="wbyyasbet"/><path fill="url(#iYsUQ1d)" class="c3rrqob2u"/><path fill="url(#icDUhjd)" class="c3rrqob2u"/><g filter="url(#iadDXub)"><circle fill="url(#i7CSKfb)" class="vfpxgxdvv"/><circle fill="url(#iJD7wEd)" class="vfpxgxdvv"/><circle fill="url(#i7GrLud)" class="vfpxgxdvv"/></g><g filter="url(#iDvxwTK)"><path fill="url(#iowoHsl)" clip-rule="evenodd" class="yp7sw01gc"/></g><path fill="url(#i2Fc8ae)" clip-rule="evenodd" class="yp7sw01gc"/><g filter="url(#ilC8bEe)"><path fill="url(#iHggw2b)" clip-rule="evenodd" class="f6wekcb9r"/></g><g filter="url(#iCIQLlI)"><circle stroke="url(#iMvf4od)" class="gt0_0ib7q"/></g><g filter="url(#iKyI8Ib)"><circle stroke="url(#i3eMlAc)" class="npxh6t9ui"/></g><g filter="url(#ie4vQjb)"><circle stroke="url(#ikatBke)" class="ij6z4d42z"/></g><g filter="url(#iTXNoGd)"><circle stroke="url(#iEkAtWc)" class="qryqg8hpq"/></g><defs><radialGradient id="ikQo4hb" cx="0" cy="0" r="1" gradientTransform="rotate(154.071 8.352 13.733)scale(15.0662 17.3462)" gradientUnits="userSpaceOnUse"><stop class="tet72waca"/><stop offset="1" class="bmx48tuma"/></radialGradient><radialGradient id="iTJaJmb" cx="0" cy="0" r="1" gradientTransform="rotate(-115.528 17.132 10.41)scale(12.9022 18.5657)" gradientUnits="userSpaceOnUse"><stop offset=".879" class="rxprtfb0z"/><stop offset="1" class="m-fo0lvbc"/></radialGradient><radialGradient id="iEzDb0x" cx="0" cy="0" r="1" gradientTransform="rotate(166.984 5.965 10.047)scale(6.38273 2.1839)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="zdar40bkv"/><stop offset="1" class="cybfe7yaw"/></radialGradient><radialGradient id="iEVCODs" cx="0" cy="0" r="1" gradientTransform="matrix(-2.6713 0 0 -14.1675 21.546 29.02)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="puczgzv3j"/><stop offset="1" class="mq0bii3nt"/></radialGradient><radialGradient id="igdhcyc" cx="0" cy="0" r="1" gradientTransform="matrix(1.24045 0 0 9.50024 7.166 29.02)" gradientUnits="userSpaceOnUse"><stop class="wke-8-xfb"/><stop offset="1" class="h-56b9bpz"/></radialGradient><radialGradient id="i0G4Fnc" cx="0" cy="0" r="1" gradientTransform="matrix(3.25185 0 0 9.13279 21.577 28.242)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="kin3dabop"/><stop offset="1" class="jlkbatyzp"/></radialGradient><radialGradient id="iHwC75H" cx="0" cy="0" r="1" gradientTransform="matrix(.87006 0 0 11.9715 21.577 29.02)" gradientUnits="userSpaceOnUse"><stop class="hos3q5hgu"/><stop offset="1" class="txm2ysbkn"/></radialGradient><radialGradient id="iTeqUld" cx="0" cy="0" r="1" gradientTransform="matrix(-3.70862 0 0 -8.85437 7.31 29.02)" gradientUnits="userSpaceOnUse"><stop offset=".614" class="vp_-q7ldm"/><stop offset=".956" class="k-z4zg2os"/></radialGradient><radialGradient id="imeqhId" cx="0" cy="0" r="1" gradientTransform="matrix(-.8463 0 0 -10.457 7.31 29.02)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="oxun88gow"/><stop offset="1" class="zi0iv1bfj"/></radialGradient><radialGradient id="ie68eYd" cx="0" cy="0" r="1" gradientTransform="matrix(.5625 1.75 -3.03541 .97567 13.7 18.656)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="klq83xb8g"/><stop offset="1" class="pzhgobu-w"/></radialGradient><radialGradient id="iRGdTsd" cx="0" cy="0" r="1" gradientTransform="rotate(139.583 4.538 13.14)scale(2.48229 1.07513)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="j3zs1gb2z"/><stop offset="1" class="sxf8lwb7u"/></radialGradient><radialGradient id="ioTcMpc" cx="0" cy="0" r="1" gradientTransform="matrix(1.75471 0 0 3.07076 8.217 12.835)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="aik_z9b6i"/><stop offset="1" class="k1mq2zvhc"/></radialGradient><radialGradient id="i69l3nc" cx="0" cy="0" r="1" gradientTransform="matrix(.82663 -.60192 .68701 .9435 19.77 12.57)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="g7lt91bhf"/><stop offset="1" class="ze1cb0iau"/></radialGradient><radialGradient id="iX3OZ0b" cx="0" cy="0" r="1" gradientTransform="matrix(.8212 -1.5104 .88405 .48065 19.358 13.656)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ezktjkbgg"/><stop offset="1" class="j3anadbkm"/></radialGradient><radialGradient id="iNao9Ab" cx="0" cy="0" r="1" gradientTransform="matrix(.25926 .25663 -.33084 .33423 19.399 12.835)" gradientUnits="userSpaceOnUse"><stop class="i4pfhbczn"/><stop offset="1" class="xjk10obil"/></radialGradient><radialGradient id="i8xKV7I" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.6693 -10.1935 0 15.105 9.493)" gradientUnits="userSpaceOnUse"><stop offset=".618" class="vpd4dcexx"/><stop offset="1" class="upbi0xbpg"/></radialGradient><radialGradient id="iovplDe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30697 1.60857 0 16.98 11.564)" gradientUnits="userSpaceOnUse"><stop class="op2kwubyv"/><stop offset="1" class="wvivicznw"/></radialGradient><radialGradient id="i03Lk6c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39075 1.72952 0 12.422 11.53)" gradientUnits="userSpaceOnUse"><stop class="y7nn5tbfc"/><stop offset="1" class="uylyaxbnq"/></radialGradient><radialGradient id="ixJVFFd" cx="0" cy="0" r="1" gradientTransform="rotate(127.807 7.909 7.05)scale(5.6057 9.53299)" gradientUnits="userSpaceOnUse"><stop class="qyobb4hvj"/><stop offset="1" class="szm1jtb2t"/></radialGradient><radialGradient id="iEfYfve" cx="0" cy="0" r="1" gradientTransform="matrix(-.06682 -1.86131 .91413 -.03282 10.441 9.38)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="u7v6tactn"/><stop offset="1" class="hpjuubccm"/></radialGradient><radialGradient id="iJ1IBRb" cx="0" cy="0" r="1" gradientTransform="matrix(.85907 -1.96631 1.60368 .70064 18.86 11.098)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ls62f1bvq"/><stop offset="1" class="gx0o3oiqw"/></radialGradient><radialGradient id="iWsGUwc" cx="0" cy="0" r="1" gradientTransform="matrix(.9927 1.23176 -1.08755 .87648 13.86 4.235)" gradientUnits="userSpaceOnUse"><stop class="kxzxrmw_u"/><stop offset="1" class="vs8934bpj"/></radialGradient><radialGradient id="icUTUuC" cx="0" cy="0" r="1" gradientTransform="matrix(.18136 .78313 -1.28748 .29815 15.329 4.234)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="dohbdcxhl"/><stop offset="1" class="bb6ud4ewj"/></radialGradient><radialGradient id="iRZ1Fse" cx="0" cy="0" r="1" gradientTransform="matrix(.72544 .89725 -2.0104 1.62544 10.29 5.962)" gradientUnits="userSpaceOnUse"><stop class="w-a4mnbis"/><stop offset="1" class="ab4_rnbjl"/></radialGradient><radialGradient id="ixwwTjX" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90308 -1.06858 0 16.813 12.486)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iTyb5ee" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.289 2.057)scale(.37817 .52064)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iQlviYn" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90312 -1.06863 0 12.45 12.486)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i2bjZte" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.172 .199)scale(.49399 .59379)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i8iTnId" cx="0" cy="0" r="1" gradientTransform="rotate(152.76 11.053 5.058)scale(5.16675 4.07534)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="urv0wcclq"/><stop offset="1" class="sgrzynbwj"/></radialGradient><radialGradient id="iOcgpve" cx="0" cy="0" r="1" gradientTransform="rotate(-117.731 13.073 -2.957)scale(1.58366 3.14201)" gradientUnits="userSpaceOnUse"><stop offset=".295" class="dit-rib8x"/><stop offset="1" class="w9pwl7bon"/></radialGradient><radialGradient id="i0zRyEb" cx="0" cy="0" r="1" gradientTransform="matrix(-.01562 .32031 -.28346 -.01383 23.196 4.29)" gradientUnits="userSpaceOnUse"><stop class="mnikv3jnk"/><stop offset="1" class="ydiskrbte"/></radialGradient><radialGradient id="i7CSKfb" cx="0" cy="0" r="1" gradientTransform="rotate(141.18 10.8 7.498)scale(.43619)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="cz-qsgbfy"/><stop offset="1" class="j80tr6o9y"/></radialGradient><radialGradient id="iJD7wEd" cx="0" cy="0" r="1" gradientTransform="matrix(.19922 -.48438 1.17186 .48198 23.594 7.011)" gradientUnits="userSpaceOnUse"><stop offset=".147" class="m8bo-jb-t"/><stop offset="1" class="wy7e69bbh"/></radialGradient><radialGradient id="i7GrLud" cx="0" cy="0" r="1" gradientTransform="matrix(.4375 .04684 -.05916 .55254 23.37 6.574)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="zk512ndyg"/><stop offset="1" class="hy0z0nf6k"/></radialGradient><radialGradient id="iowoHsl" cx="0" cy="0" r="1" gradientTransform="matrix(2.20247 -1.61719 2.56784 3.49718 21.397 9.76)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="cnux6p8xn"/><stop offset="1" class="jaxt-o31p"/></radialGradient><radialGradient id="iHggw2b" cx="0" cy="0" r="1" gradientTransform="matrix(2.53124 -1.40627 1.98705 3.57664 24.543 7.937)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="cnux6p8xn"/><stop offset="1" class="jaxt-o31p"/></radialGradient><filter id="iypzuqd" width="3.539" height="3.339" x="8.217" y="11.166" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.643137 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_35"/></filter><filter id="iCtMPDP" width="2.99" height="2.99" x="8.392" y="11.34" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_35" stdDeviation=".25"/></filter><filter id="ih8qj9d" width="3.589" height="3.589" x="17.73" y="10.916" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.529412 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_35"/></filter><filter id="iZrabjb" width="2.99" height="2.99" x="17.904" y="11.34" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_35" stdDeviation=".25"/></filter><filter id="imDOddB" width="10.373" height="12.177" x="9.477" y="7.211" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.501961 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_35"/></filter><filter id="iAWe43W" width="12.601" height="8.543" x="8.334" y="3.734" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.690196 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_35"/></filter><filter id="isd55Vc" width="3.26" height="4.181" x="12.765" y="11.68" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_35" stdDeviation=".375"/></filter><filter id="i9xzZKc" width="2.077" height="2.881" x="13.596" y="12.167" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_35" stdDeviation=".05"/></filter><filter id="i23oxJc" width="2.979" height="1.873" x="15.816" y="9.186" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_35"/></filter><filter id="iWbPPWb" width="2.98" height="1.873" x="10.669" y="9.186" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_35"/></filter><filter id="iMz5s5H" width=".787" height=".696" x="16.079" y="11.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_35" stdDeviation=".05"/></filter><filter id="i2llelb" width=".891" height=".913" x="16.919" y="11.788" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_35" stdDeviation=".1"/></filter><filter id="inLAxfc" width=".986" height="1.04" x="12.477" y="11.725" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_35" stdDeviation=".1"/></filter><filter id="iqPRsEe" width=".913" height=".704" x="11.722" y="11.705" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_35" stdDeviation=".05"/></filter><filter id="i951pMd" width="3.099" height="1.681" x="15.669" y="9.312" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_35" stdDeviation=".25"/></filter><filter id="iqoaCPd" width="3.177" height="1.738" x="10.45" y="9.376" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_35" stdDeviation=".25"/></filter><filter id="iadDXub" width=".726" height=".726" x="23.426" y="6.251" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.52549 0 0 0 0 0.388235 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_35"/></filter><filter id="iDvxwTK" width="3.834" height="4.387" x="20.968" y="7.053" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.45098 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_35"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.282353 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_35" result="effect2_innerShadow_4002_35"/></filter><filter id="ilC8bEe" width="4.283" height="3.734" x="24.166" y="5.576" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.203922 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_35"/></filter><filter id="iCIQLlI" width="3.843" height="3.843" x="24.637" y="5.546" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_35" stdDeviation=".1"/></filter><filter id="iKyI8Ib" width="2.734" height="2.734" x="25.191" y="6.101" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_35" stdDeviation=".1"/></filter><filter id="ie4vQjb" width="2.734" height="2.734" x="21.543" y="8.114" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_35" stdDeviation=".1"/></filter><filter id="iTXNoGd" width="3.805" height="3.805" x="21.008" y="7.579" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_35" stdDeviation=".1"/></filter><linearGradient id="isCRgJb" x1="9.886" x2="9.246" y1="13.114" y2="13.114" gradientUnits="userSpaceOnUse"><stop class="s236rjbsc"/><stop offset="1" class="o6sle6pni"/></linearGradient><linearGradient id="i8aCzeE" x1="20.485" x2="19.666" y1="11.743" y2="14.28" gradientUnits="userSpaceOnUse"><stop class="kwz3apblc"/><stop offset="1" class="gx0xrfbie"/></linearGradient><linearGradient id="i5tzCeb" x1="18.67" x2="11.034" y1="13.224" y2="14.362" gradientUnits="userSpaceOnUse"><stop class="b941pszbd"/><stop offset="1" class="jtnk9gb3a"/></linearGradient><linearGradient id="iOFUUce" x1="9.239" x2="11.551" y1="15.92" y2="15.618" gradientUnits="userSpaceOnUse"><stop class="ls27mhbfe"/><stop offset="1" class="ys1ri2qqc"/></linearGradient><linearGradient id="isZxE6u" x1="9.774" x2="12.675" y1="12.568" y2="7.413" gradientUnits="userSpaceOnUse"><stop class="ts8ii3fly"/><stop offset="1" class="zlpmx2b9v"/></linearGradient><linearGradient id="ihwHGob" x1="13.77" x2="14.708" y1="13.884" y2="13.884" gradientUnits="userSpaceOnUse"><stop class="gs643vbjw"/><stop offset="1" class="v4v-qb7kx"/></linearGradient><linearGradient id="i2ejT7m" x1="15.572" x2="14.547" y1="14.206" y2="14.191" gradientUnits="userSpaceOnUse"><stop class="sbp9bz1ap"/><stop offset="1" class="xrkexibub"/></linearGradient><linearGradient id="inb0Tmd" x1="14.829" x2="14.829" y1="14.948" y2="14.375" gradientUnits="userSpaceOnUse"><stop class="rxh459f4v"/><stop offset="1" class="lemuo5beu"/></linearGradient><linearGradient id="iXPnJ5d" x1="13.597" x2="14.032" y1="16.563" y2="15.876" gradientUnits="userSpaceOnUse"><stop class="pn2_jabhi"/><stop offset=".663" class="z9945l-5h"/></linearGradient><linearGradient id="iDhxooe" x1="17.591" x2="17.277" y1="12.207" y2="12.4" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iIPG9wd" x1="13.194" x2="12.88" y1="12.207" y2="12.4" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ifLFKcD" x1="17.606" x2="17.186" y1="10.067" y2="9.209" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><linearGradient id="iXGQFed" x1="12.302" x2="11.113" y1="9.94" y2="9.441" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><linearGradient id="itKwPXc" x1="24.949" x2="23.758" y1="4.713" y2="4.369" gradientUnits="userSpaceOnUse"><stop class="p9lsnsm5t"/><stop offset="1" class="lapvr59ed"/></linearGradient><linearGradient id="ip9aQEE" x1="23.801" x2="23.875" y1="6.207" y2="5.917" gradientUnits="userSpaceOnUse"><stop offset=".16" class="zl0fwhbas"/><stop offset="1" class="lxc0fmbqt"/></linearGradient><linearGradient id="iYsUQ1d" x1="22.887" x2="23.152" y1="7.062" y2="5.765" gradientUnits="userSpaceOnUse"><stop class="p9lsnsm5t"/><stop offset="1" class="lapvr59ed"/></linearGradient><linearGradient id="icDUhjd" x1="24.298" x2="24.1" y1="7.144" y2="7.088" gradientUnits="userSpaceOnUse"><stop class="jd-vaq0no"/><stop offset="1" class="gof7ehbkx"/></linearGradient><linearGradient id="i2Fc8ae" x1="23.637" x2="23.578" y1="7.234" y2="7.46" gradientUnits="userSpaceOnUse"><stop offset=".209" class="ni_6htbzm"/><stop offset="1" class="ajm38_jxm"/></linearGradient><linearGradient id="iMvf4od" x1="24.887" x2="28.077" y1="7.836" y2="6.364" gradientUnits="userSpaceOnUse"><stop offset=".616" class="w5_7ycb6b"/><stop offset=".9" class="srm_r_guo"/></linearGradient><linearGradient id="i3eMlAc" x1="25.441" x2="27.573" y1="7.714" y2="6.73" gradientUnits="userSpaceOnUse"><stop offset=".247" class="jzjqx7qlk"/><stop offset=".669" class="gl3wl_9gz"/></linearGradient><linearGradient id="ikatBke" x1="21.793" x2="23.925" y1="9.728" y2="8.744" gradientUnits="userSpaceOnUse"><stop offset=".247" class="rraw6sbsp"/><stop offset=".669" class="r8ibvzbki"/></linearGradient><linearGradient id="iEkAtWc" x1="24.563" x2="22.91" y1="8.941" y2="9.482" gradientUnits="userSpaceOnUse"><stop class="znwvjy5yx"/><stop offset="1" class="zi0lb2bns"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-getting-haircut-medium-light" /></template>
<style>
.ab4_rnbjl {
  stop-color: var(--svg-color--dcc291, #DCC291);
  stop-opacity: 0;
}

.aik_z9b6i {
  stop-color: var(--svg-color--c28775, #C28775);
}

.ajm38_jxm {
  stop-color: var(--svg-color--ff3178, #FF3178);
  stop-opacity: 0;
}

.b6k1axmhp {
  d: path("M7.31 20.49c-2.273 1.965-3.71 4.85-3.71 8.068v.463h3.71z");
}

.b941pszbd {
  stop-color: var(--svg-color--fac39e, #FAC39E);
}

.baiadf44i {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.241 11.404c-.653 0-1.204.45-1.354 1.059a.273.273 0 0 0 .267.34h2.23a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.37-1.128");
}

.bb6ud4ewj {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
  stop-opacity: 0;
}

.bmx48tuma {
  stop-color: var(--svg-color--2477dd, #2477DD);
}

.c3rrqob2u {
  d: path("m19.694 4.885l5.419 1.536l-.337 1.189l-4.313-1.223a1.15 1.15 0 0 1-.793-1.42z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnux6p8xn {
  stop-color: var(--svg-color--ff7046, #FF7046);
}

.csh7z6x1o {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("M18.353 10.115h-.001l-.002-.002l-.005-.004l-.011-.01a1.4 1.4 0 0 0-.155-.107c-.1-.062-.241-.14-.42-.21a2.83 2.83 0 0 0-1.493-.159a.534.534 0 0 0 .167 1.054c.398-.062.716.01.934.097a1.5 1.5 0 0 1 .3.16l.008.005a.534.534 0 0 0 .678-.824");
}

.cybfe7yaw {
  stop-color: var(--svg-color--27719e, #27719E);
  stop-opacity: 0;
}

.cz-qsgbfy {
  stop-color: var(--svg-color--ebdbe4, #EBDBE4);
}

.d85-ehcsj {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.75 11.865c.063.085-.07.188-.221.301s-.263.193-.327.108s.007-.246.158-.359c.152-.113.326-.135.39-.05");
}

.dit-rib8x {
  stop-color: var(--svg-color--edbe98, #EDBE98);
}

.dohbdcxhl {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
}

.duamz0b8m {
  d: path("M21.577 29.02h3.708v-.463c0-3.217-1.435-6.103-3.708-8.066z");
}

.e564nzbob {
  d: path("M13.263 12.463c0-.288-.234-.48-.297-.538l-.289.279l.178.36z");
}

.eic4j5j0i {
  fill: var(--svg-color--2b7fde, #2B7FDE);
  d: path("M7.31 20.49c-2.273 1.965-3.71 4.85-3.71 8.068v.463h3.71z");
}

.ezktjkbgg {
  stop-color: var(--svg-color--d79a76, #D79A76);
  stop-opacity: 0;
}

.f6wekcb9r {
  fill-rule: evenodd;
  d: path("M24.457 6.32a.1.1 0 0 1 .123-.071l.359.095c.08.021.163-.01.217-.072a1.842 1.842 0 1 1-.412 1.52a.22.22 0 0 0-.153-.172l-.351-.093a.1.1 0 0 1-.071-.123zm1.664 1.87a.844.844 0 1 0 .872-1.444a.844.844 0 0 0-.872 1.444");
}

.ft5dv1b6b {
  fill: none;
}

.g7lt91bhf {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gl3wl_9gz {
  stop-color: var(--svg-color--ff7e7a, #FF7E7A);
  stop-opacity: 0;
}

.gof7ehbkx {
  stop-color: var(--svg-color--a2889f, #A2889F);
  stop-opacity: 0;
}

.gs643vbjw {
  stop-color: var(--svg-color--cb9173, #CB9173);
}

.gt0_0ib7q {
  cx: 26.559px;
  cy: 7.468px;
  r: 1.671px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.gx0o3oiqw {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
  stop-opacity: 0;
}

.gx0xrfbie {
  stop-color: var(--svg-color--dca189, #DCA189);
}

.h-56b9bpz {
  stop-color: var(--svg-color--1f6ce0, #1F6CE0);
  stop-opacity: 0;
}

.hos3q5hgu {
  stop-color: var(--svg-color--367bf1, #367BF1);
}

.hpjuubccm {
  stop-color: var(--svg-color--eec19c, #EEC19C);
  stop-opacity: 0;
}

.hy0z0nf6k {
  stop-color: var(--svg-color--a4888c, #A4888C);
  stop-opacity: 0;
}

.i4pfhbczn {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
}

.ij6z4d42z {
  cx: 22.91px;
  cy: 9.482px;
  r: 1.117px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.itf2z1bmi {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("M10.861 10.116h.002l.001-.002l.005-.004l.012-.01l.036-.027q.045-.032.119-.08c.1-.062.24-.14.42-.21a2.83 2.83 0 0 1 1.492-.159a.534.534 0 0 1-.166 1.054a1.77 1.77 0 0 0-.934.097a1.5 1.5 0 0 0-.3.16l-.008.005a.534.534 0 0 1-.679-.823");
}

.j_0_l0dzh {
  cx: 9.886px;
  cy: 12.835px;
  r: 0.995px;
}

.j3anadbkm {
  stop-color: var(--svg-color--d79a76, #D79A76);
}

.j3zs1gb2z {
  stop-color: var(--svg-color--d3a294, #D3A294);
}

.j80tr6o9y {
  stop-color: var(--svg-color--c7b1b5, #C7B1B5);
}

.jaxt-o31p {
  stop-color: var(--svg-color--ff2d78, #FF2D78);
}

.jd-vaq0no {
  stop-color: var(--svg-color--93768e, #93768E);
}

.jlkbatyzp {
  stop-color: var(--svg-color--43a0f3, #43A0F3);
}

.jtnk9gb3a {
  stop-color: var(--svg-color--c9917c, #C9917C);
}

.jzjqx7qlk {
  stop-color: var(--svg-color--ff7e7a, #FF7E7A);
}

.k-z4zg2os {
  stop-color: var(--svg-color--517cc3, #517CC3);
}

.k1mq2zvhc {
  stop-color: var(--svg-color--ba7867, #BA7867);
}

.kfb9k_bug {
  d: path("m19.453 6.358l.429.213c.75.373 1.18 1.227 1.019 2.133l-.59 3.04c-.053.314-.26.525-.572.533h-.018s.053-.906.107-1.44c.044-.433-.032-.565-.429-.96a1.25 1.25 0 0 1-.375-.853v-.853c0-.267-.215-.48-.43-.533c-.643-.16-1.984-.427-3.915-.427c-1.93 0-3.271.267-3.915.427a.52.52 0 0 0-.43.533v.853c0 .32-.107.64-.375.853l-.16.16c-.215.16-.322.48-.322.747c.053.587.107 1.44.107 1.44l-.05-.002a.63.63 0 0 1-.594-.531l-.59-3.04c-.107-.853.322-1.707 1.073-2.08l.43-.213c.267-.16.535-.374.804-.587l.965-1.013c.59-.533 1.448-.693 2.2-.32a2.94 2.94 0 0 0 1.662 0c.804-.267 1.716-.053 2.36.533l.804.8c.215.267.483.427.805.587");
}

.kin3dabop {
  stop-color: var(--svg-color--43a2ff, #43A2FF);
}

.klq83xb8g {
  stop-color: var(--svg-color--a7727c, #A7727C);
}

.kwz3apblc {
  stop-color: var(--svg-color--f5c8a5, #F5C8A5);
}

.kxzxrmw_u {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
}

.lapvr59ed {
  stop-color: var(--svg-color--d9b4c8, #D9B4C8);
}

.leh3g6bge {
  cx: 12.179px;
  cy: 12.057px;
  rx: 0.389px;
  ry: 0.197px;
}

.lemuo5beu {
  stop-color: var(--svg-color--c98583, #C98583);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lnwtx-bmv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.075 10.49c.327-.29 1.042-.594 1.927-.453");
}

.ls27mhbfe {
  stop-color: var(--svg-color--d99e84, #D99E84);
}

.ls62f1bvq {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
}

.lxc0fmbqt {
  stop-color: var(--svg-color--c0a0b5, #C0A0B5);
  stop-opacity: 0;
}

.m-fo0lvbc {
  stop-color: var(--svg-color--407da5, #407DA5);
}

.m5h_2yb7z {
  cx: 19.399px;
  cy: 12.835px;
  r: 0.995px;
  fill: var(--svg-color--d79e81, #D79E81);
}

.m8bo-jb-t {
  stop-color: var(--svg-color--996e9f, #996E9F);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mnikv3jnk {
  stop-color: var(--svg-color--ecc69a, #ECC69A);
}

.mq0bii3nt {
  stop-color: var(--svg-color--459bfc, #459BFC);
  stop-opacity: 0;
}

.mzd4cyb6c {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.022 11.404c.652 0 1.204.45 1.354 1.059a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.n8442jnle {
  d: path("M16.75 11.865c.063.085-.07.188-.221.301s-.263.193-.327.108s.007-.246.158-.359c.152-.113.326-.135.39-.05");
}

.ni_6htbzm {
  stop-color: var(--svg-color--b71143, #B71143);
}

.npxh6t9ui {
  cx: 26.559px;
  cy: 7.468px;
  r: 1.117px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.o6sle6pni {
  stop-color: var(--svg-color--b87862, #B87862);
}

.o79a7bclz {
  fill: var(--svg-color--c68378, #C68378);
  d: path("m14.359 12.713l-.82 1.7c-.102.349.142.698.488.698h.737c.345 0 .59-.355.488-.699l-.498-1.7c-.107-.376-.284-.376-.395 0");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.omozuebmd {
  fill: var(--svg-color--000, #000);
  d: path("M12.959 12.568a.51.51 0 0 0-.511-.51a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .061-.236");
}

.op2kwubyv {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
}

.oxun88gow {
  stop-color: var(--svg-color--438dec, #438DEC);
}

.p9lsnsm5t {
  stop-color: var(--svg-color--9b8299, #9B8299);
}

.pj18qir8q {
  d: path("M17.61 12.45a.84.84 0 0 0-.232-.462l-.26.285l.118.229z");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pn2_jabhi {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
}

.pqf0u3bgb {
  stop-color: var(--svg-color--a57146, #A57146);
}

.puczgzv3j {
  stop-color: var(--svg-color--459bfc, #459BFC);
}

.pv5af87fu {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.272 15.592c.393.205.862.323 1.362.323c.505 0 .968-.118 1.362-.323a.2.2 0 0 1 .242.04a.19.19 0 0 1 .02.24m-2.986-.28l2.945.253m-2.945-.253a.2.2 0 0 0-.242.041a.19.19 0 0 0-.02.24m.262-.281l-.22.253m3.207.028l-.042-.028m.042.028l-.042-.028m.042.028a1.94 1.94 0 0 1-1.625.868c-.682 0-1.28-.347-1.624-.868m3.207-.028a1.9 1.9 0 0 1-1.583.846a1.9 1.9 0 0 1-1.583-.846m-.041.028l.041-.028m-.041.028l.041-.028");
}

.pzhgobu-w {
  stop-color: var(--svg-color--a7727c, #A7727C);
  stop-opacity: 0;
}

.qi89ecakj {
  cx: 19.399px;
  cy: 12.835px;
  r: 1.669px;
}

.qryqg8hpq {
  cx: 22.91px;
  cy: 9.482px;
  r: 1.652px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qyobb4hvj {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
}

.r8ibvzbki {
  stop-color: var(--svg-color--ff9266, #FF9266);
  stop-opacity: 0;
}

.ropjnrb-t {
  cx: 19.399px;
  cy: 12.835px;
  r: 0.995px;
}

.rraw6sbsp {
  stop-color: var(--svg-color--ff9266, #FF9266);
}

.rxh459f4v {
  stop-color: var(--svg-color--c98583, #C98583);
}

.rxprtfb0z {
  stop-color: var(--svg-color--407da5, #407DA5);
  stop-opacity: 0;
}

.s236rjbsc {
  stop-color: var(--svg-color--af6f5d, #AF6F5D);
}

.sbp9bz1ap {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
}

.sdwn2xbgr {
  d: path("M12.63 17.64h3.985v1.383c0 1.1-.892 1.812-1.992 1.812s-1.992-.712-1.992-1.812z");
}

.sgrzynbwj {
  stop-color: var(--svg-color--fcf6ba, #FCF6BA);
}

.son215bua {
  d: path("M20.283 5.531c-1.214-.027-1.641-.098-2.18-.285l1.27 1.728l.159.165c.2.209.48.324.766.278c.754-.122 1.862-.454 2.47-1c.844-.757.785-1.491.715-1.757s-.211-.445-.352-.453s-.26.061-.39.375c-.212.508-.883.984-2.458.949");
}

.srm_r_guo {
  stop-color: var(--svg-color--ff6792, #FF6792);
}

.sxf8lwb7u {
  stop-color: var(--svg-color--d3a294, #D3A294);
  stop-opacity: 0;
}

.szm1jtb2t {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
  stop-opacity: 0;
}

.t-xw98brg {
  cx: 9.887px;
  cy: 12.835px;
  r: 1.669px;
}

.td5sfhbse {
  d: path("m9.535 12.222l.049.002s-.054-.853-.107-1.44c0-.267.107-.587.321-.747l.161-.16c.268-.213.376-.533.376-.853v-.853c0-.267.16-.48.429-.533c.643-.16 1.984-.427 3.915-.427s3.272.267 3.915.427c.215.053.43.266.43.533v.853c0 .32.16.64.375.853c.502.352.47.546.43.96c-.055.534-.108 1.44-.108 1.44h.018l-.266 3.958c-.16 1.77-1.551 3.003-3.21 3.003h-3.21c-1.712 0-3.05-1.233-3.21-3.003z");
}

.tet72waca {
  stop-color: var(--svg-color--339ff3, #339FF3);
}

.tq594abms {
  d: path("m14.252 12.55l-.531 1.7a.54.54 0 0 0 .52.698h.786a.54.54 0 0 0 .52-.699l-.53-1.7c-.114-.376-.646-.376-.765 0");
}

.ts8ii3fly {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
}

.txm2ysbkn {
  stop-color: var(--svg-color--367bf1, #367BF1);
  stop-opacity: 0;
}

.u207l-w-d {
  fill: var(--svg-color--e4ac8f, #E4AC8F);
  d: path("m14.252 12.55l-.531 1.7a.54.54 0 0 0 .52.698h.786a.54.54 0 0 0 .52-.699l-.53-1.7c-.114-.376-.646-.376-.765 0");
}

.u7v6tactn {
  stop-color: var(--svg-color--eec19c, #EEC19C);
}

.upbi0xbpg {
  stop-color: var(--svg-color--9f6e75, #9F6E75);
}

.urv0wcclq {
  stop-color: var(--svg-color--d6ad80, #D6AD80);
}

.uylyaxbnq {
  stop-color: var(--svg-color--c2837a, #C2837A);
  stop-opacity: 0;
}

.v4v-qb7kx {
  stop-color: var(--svg-color--cb9173, #CB9173);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vfpxgxdvv {
  cx: 23.739px;
  cy: 6.664px;
  r: 0.313px;
}

.vp_-q7ldm {
  stop-color: var(--svg-color--517cc3, #517CC3);
  stop-opacity: 0;
}

.vpd4dcexx {
  stop-color: var(--svg-color--c88d87, #C88D87);
  stop-opacity: 0;
}

.vs8934bpj {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
  stop-opacity: 0;
}

.vsd5z4bzn {
  d: path("M3.601 28.557c0-5.915 4.854-10.71 10.842-10.71s10.842 4.795 10.842 10.71v.463H3.601z");
}

.w-a4mnbis {
  stop-color: var(--svg-color--dcc291, #DCC291);
}

.w288a_boz {
  fill: var(--svg-color--000, #000);
  d: path("M16.304 12.568c0-.284.227-.51.51-.51a.51.51 0 0 1 .455.746h-.904a.46.46 0 0 1-.061-.236");
}

.w5_7ycb6b {
  stop-color: var(--svg-color--ff4f4f, #FF4F4F);
}

.w9pwl7bon {
  stop-color: var(--svg-color--edbe98, #EDBE98);
  stop-opacity: 0;
}

.wbyyasbet {
  d: path("M24.342 2.308L22.954 7.14l1.187.345l1.071-3.73a1.15 1.15 0 0 0-.784-1.421z");
}

.wke-8-xfb {
  stop-color: var(--svg-color--1f6ce0, #1F6CE0);
}

.wmbqnx98e {
  cx: 12.179px;
  cy: 12.057px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.wodlq0j2b {
  fill: var(--svg-color--ebcc94, #EBCC94);
  d: path("m19.453 6.358l.429.213c.75.373 1.18 1.227 1.019 2.133l-.59 3.04c-.053.314-.26.525-.572.533h-.018s.053-.906.107-1.44c.044-.433-.032-.565-.429-.96a1.25 1.25 0 0 1-.375-.853v-.853c0-.267-.215-.48-.43-.533c-.643-.16-1.984-.427-3.915-.427c-1.93 0-3.271.267-3.915.427a.52.52 0 0 0-.43.533v.853c0 .32-.107.64-.375.853l-.16.16c-.215.16-.322.48-.322.747c.053.587.107 1.44.107 1.44l-.05-.002a.63.63 0 0 1-.594-.531l-.59-3.04c-.107-.853.322-1.707 1.073-2.08l.43-.213c.267-.16.535-.374.804-.587l.965-1.013c.59-.533 1.448-.693 2.2-.32a2.94 2.94 0 0 0 1.662 0c.804-.267 1.716-.053 2.36.533l.804.8c.215.267.483.427.805.587");
}

.wvivicznw {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
  stop-opacity: 0;
}

.wy7e69bbh {
  stop-color: var(--svg-color--c8b3b7, #C8B3B7);
  stop-opacity: 0;
}

.xjk10obil {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
  stop-opacity: 0;
}

.xogpiobqs {
  stop-color: var(--svg-color--a57146, #A57146);
  stop-opacity: 0;
}

.xrkexibub {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
  stop-opacity: 0;
}

.xtr1tybzs {
  fill: var(--svg-color--d39488, #D39488);
  d: path("M12.63 17.64h3.985v1.383c0 1.1-.892 1.812-1.992 1.812s-1.992-.712-1.992-1.812z");
}

.xuv1spb_l {
  d: path("M16.815 11.676a.892.892 0 0 1 .86 1.127H15.95a.896.896 0 0 1 .864-1.127");
}

.xx8xnnb2g {
  d: path("M12.448 11.676a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.y7nn5tbfc {
  stop-color: var(--svg-color--c2837a, #C2837A);
}

.ydiskrbte {
  stop-color: var(--svg-color--ecc69a, #ECC69A);
  stop-opacity: 0;
}

.yp7sw01gc {
  fill-rule: evenodd;
  d: path("M23.013 7.107a.1.1 0 0 0-.124.068l-.104.357a.22.22 0 0 1-.174.148a1.842 1.842 0 1 0 1.514.433a.22.22 0 0 1-.068-.22l.102-.348a.1.1 0 0 0-.069-.124zm.74 2.39a.844.844 0 1 1-1.687 0a.844.844 0 0 1 1.688 0");
}

.yqrihcbbb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M16.294 9.97c.43-.075 1.27-.053 1.85.398");
}

.ys1ri2qqc {
  stop-color: var(--svg-color--d99e84, #D99E84);
  stop-opacity: 0;
}

.z9945l-5h {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
  stop-opacity: 0;
}

.zdar40bkv {
  stop-color: var(--svg-color--145491, #145491);
}

.ze1cb0iau {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
  stop-opacity: 0;
}

.zi0iv1bfj {
  stop-color: var(--svg-color--438dec, #438DEC);
  stop-opacity: 0;
}

.zi0lb2bns {
  stop-color: var(--svg-color--ff5185, #FF5185);
  stop-opacity: 0;
}

.zk512ndyg {
  stop-color: var(--svg-color--a4888c, #A4888C);
}

.zl0fwhbas {
  stop-color: var(--svg-color--a28b95, #A28B95);
}

.zlpmx2b9v {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
  stop-opacity: 0;
}

.znwvjy5yx {
  stop-color: var(--svg-color--ff5c88, #FF5C88);
}

</style>
