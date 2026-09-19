<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iGyDTil)"><path fill="url(#i3JoEEd)" class="y5h98bc-a"/><path fill="url(#iqatzCe)" class="y5h98bc-a"/></g><g filter="url(#ix5Ed2b)"><path fill="url(#i9KOU6b)" class="kkue_wb7v"/></g><path fill="url(#iN5wv5A)" class="kkue_wb7v"/><g filter="url(#iiyQVVb)"><path class="d98osxiir"/><path fill="url(#iFJJfkS)" class="v1kdh7m2c"/></g><g filter="url(#iIGF45d)"><path fill="url(#iBVNdPB)" clip-rule="evenodd" class="ue1cg0jtk"/></g><g filter="url(#itjVTSs)"><circle stroke="url(#iMqUPPc)" class="f2dg1pymm"/></g><path fill="url(#ir9Uywd)" class="hk_2rww3p"/><path class="q04uptb_f"/><path fill="url(#iAUidTI)" class="yhwal5uej"/><path fill="url(#ipimVNe)" class="yhwal5uej"/><path fill="url(#ikI6zud)" clip-rule="evenodd" class="mvvhg6bob"/><path fill="url(#ioqA6Ec)" clip-rule="evenodd" class="mvvhg6bob"/><path fill="url(#iByKjmc)" clip-rule="evenodd" class="fuvqv0efx"/><path fill="url(#ilystOc)" clip-rule="evenodd" class="cc4vvtr3m"/><path fill="url(#iyuxnsc)" clip-rule="evenodd" class="cc4vvtr3m"/><g filter="url(#iUiedme)"><path fill="url(#iXjYTba)" clip-rule="evenodd" class="pfbx1ib6q"/><path fill="url(#iWYSLge)" clip-rule="evenodd" class="pfbx1ib6q"/></g><path fill="url(#iDeh7Jb)" clip-rule="evenodd" class="nrp3vkbjq"/><path fill="url(#i7VZLSd)" clip-rule="evenodd" class="wjs_nsbuh"/><path fill="url(#iAoLEke)" clip-rule="evenodd" class="wjs_nsbuh"/><path fill="url(#iX1cArb)" clip-rule="evenodd" class="wjs_nsbuh"/><path fill="url(#iaB7XVr)" class="b3q5ubbch"/><path fill="url(#iBC4vge)" class="b3q5ubbch"/><path fill="url(#ioviqld)" class="b3q5ubbch"/><path fill="url(#i8GpRbG)" class="h-r_c9b7x"/><path fill="url(#iqttsuc)" class="h-r_c9b7x"/><g filter="url(#iuLmSLc)"><path fill="url(#iv0gtpe)" class="wm4p2nf6o"/><path fill="url(#iUb7kZR)" class="wm4p2nf6o"/></g><circle fill="url(#iliKE4b)" class="rrfczgbhc"/><circle fill="url(#iNgFFMe)" class="rrfczgbhc"/><g filter="url(#iBIYBVc)"><path class="hz6yw06qq"/><path fill="url(#iQhym4p)" class="um4kzybeo"/><path fill="url(#iCW6Pzb)" class="um4kzybeo"/></g><path fill="url(#i0pmBre)" transform="rotate(-55.397 13.554 7.913)" class="czabn_xgs"/><path fill="url(#ixYQKHd)" transform="rotate(-55.397 13.554 7.913)" class="czabn_xgs"/><g filter="url(#i0Ejijc)"><path fill="url(#iq3zi1d)" class="o0tyh0b-k"/><path fill="url(#ikHZRUb)" class="o0tyh0b-k"/></g><g filter="url(#iPskwjd)"><path fill="url(#iLd5sqb)" class="e_--_59xk"/><path fill="url(#iATYDXc)" class="e_--_59xk"/></g><g filter="url(#iBt9zwn)"><path fill="url(#iH0vVxd)" class="hla563ezk"/></g><g filter="url(#inbtUbM)"><path class="pzip1rpvk"/><path fill="url(#i0P2tWc)" class="iy0i0xbqt"/></g><g filter="url(#iRcIcPv)"><path clip-rule="evenodd" class="u3_kb5fuo"/></g><g filter="url(#i3hO3XB)"><path clip-rule="evenodd" class="k14lsyzjk"/><path fill="url(#inFqrHe)" clip-rule="evenodd" class="cpzd76x5u"/></g><path fill="url(#i2Zwted)" clip-rule="evenodd" class="bleghrbgv"/><path fill="url(#iLjhO7c)" clip-rule="evenodd" class="bleghrbgv"/><g filter="url(#i264rOe)"><path fill="url(#iYiWRhd)" class="qc8cprh-k"/></g><path fill="url(#iSMKmod)" clip-rule="evenodd" class="pypniyb9c"/><path fill="url(#ivLrJyw)" clip-rule="evenodd" class="pypniyb9c"/><path fill="url(#iEcd0Jc)" clip-rule="evenodd" class="tks1wp4pj"/><path fill="url(#iH0iWce)" clip-rule="evenodd" class="tks1wp4pj"/><g filter="url(#icCUF7d)"><circle class="zlie59b6o"/></g><path fill="url(#i8Jcowb)" class="oxni39rcm"/><g filter="url(#ibZokyc)"><path fill="url(#iBqQT1I)" class="ewlxb1b8e"/><path fill="url(#iNjsIyd)" class="ewlxb1b8e"/><path fill="url(#iKEClUc)" class="ewlxb1b8e"/><path fill="url(#iCmjZFQ)" class="ewlxb1b8e"/></g><path clip-rule="evenodd" class="e4rocubwy"/><path class="wo6zfvbcw"/><path class="p1mhlac7z"/><path class="q4qmhdcyz"/><path fill="url(#iFgL5wb)" class="wuejk-0mo"/><g filter="url(#iu4zYHd)"><path fill="url(#i8uM9kb)" class="luorv-7fc"/></g><circle transform="rotate(-65.31 11.159 6.856)" class="wem5pbj-u"/><circle fill="url(#iwWI1ZI)" transform="rotate(-65.31 13.489 5.752)" class="u7zxukb7a"/><path clip-rule="evenodd" class="ppui9tpqg"/><path fill="url(#ieFk6mc)" clip-rule="evenodd" class="t5qustb5j"/><path fill="url(#i1NlFwg)" clip-rule="evenodd" class="t5qustb5j"/><path fill="url(#irHMZvb)" clip-rule="evenodd" class="t5qustb5j"/><g filter="url(#iUyYELb)"><path fill="url(#ibXte0u)" class="bgnynkbvn"/></g><g filter="url(#ial1Qae)"><path fill="url(#iAEzulC)" class="m94qeobdh"/></g><defs><radialGradient id="iN5wv5A" cx="0" cy="0" r="1" gradientTransform="rotate(150.331 11.807 6.045)scale(3.70975 8.36641)" gradientUnits="userSpaceOnUse"><stop offset=".19" class="l4_q8ccja"/><stop offset="1" class="fy0gg3b4w"/></radialGradient><radialGradient id="iFJJfkS" cx="0" cy="0" r="1" gradientTransform="matrix(4.42529 4.18325 -2.33905 2.47438 19.748 26.802)" gradientUnits="userSpaceOnUse"><stop class="qfj7itbso"/><stop offset="1" class="p1dkvx0ja"/></radialGradient><radialGradient id="iBVNdPB" cx="0" cy="0" r="1" gradientTransform="rotate(126.943 -.1 13.106)scale(9.77501 9.43553)" gradientUnits="userSpaceOnUse"><stop class="y16t4y92n"/><stop offset="1" class="hqorccbwh"/></radialGradient><radialGradient id="ipimVNe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53127 2.45312 -.44454 -.27749 20.346 20.953)" gradientUnits="userSpaceOnUse"><stop class="m3q9izqvj"/><stop offset="1" class="gxtng2bih"/></radialGradient><radialGradient id="ioqA6Ec" cx="0" cy="0" r="1" gradientTransform="rotate(-68.026 17.608 .423)scale(2.88119 .32513)" gradientUnits="userSpaceOnUse"><stop class="f-r3ld20z"/><stop offset="1" class="qnv5cwbcc"/></radialGradient><radialGradient id="ilystOc" cx="0" cy="0" r="1" gradientTransform="matrix(6.71875 4.82813 -1.31599 1.83131 10.22 18.516)" gradientUnits="userSpaceOnUse"><stop class="zo6cprbov"/><stop offset="1" class="cc9670aeb"/></radialGradient><radialGradient id="iXjYTba" cx="0" cy="0" r="1" gradientTransform="rotate(134.451 10.034 17.078)scale(9.80603 9.46548)" gradientUnits="userSpaceOnUse"><stop offset=".427" class="msqk4cb8o"/><stop offset="1" class="wc0bxtmli"/></radialGradient><radialGradient id="iAoLEke" cx="0" cy="0" r="1" gradientTransform="rotate(103.707 3.238 16.627)scale(4.61583 .44083)" gradientUnits="userSpaceOnUse"><stop class="rgol9fpyb"/><stop offset="1" class="jk5eocp2v"/></radialGradient><radialGradient id="iX1cArb" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 -1.0625 1.65481 -.04867 18.502 23.75)" gradientUnits="userSpaceOnUse"><stop class="d-6jagb2y"/><stop offset="1" class="zd8v8x_xx"/></radialGradient><radialGradient id="iaB7XVr" cx="0" cy="0" r="1" gradientTransform="matrix(-.28125 3.99268 -5.05379 -.356 15.415 15.187)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="c_y4ucu-s"/><stop offset=".868" class="tg-9ku_mf"/></radialGradient><radialGradient id="iBC4vge" cx="0" cy="0" r="1" gradientTransform="matrix(1.21875 .45313 -.35 .94138 15.783 17.156)" gradientUnits="userSpaceOnUse"><stop offset=".346" class="m_jah6j1d"/><stop offset="1" class="truymkbqg"/></radialGradient><radialGradient id="ioviqld" cx="0" cy="0" r="1" gradientTransform="rotate(-167.255 8.833 7.73)scale(2.69131 3.58612)" gradientUnits="userSpaceOnUse"><stop offset=".738" class="gtw3mmb0a"/><stop offset="1" class="p0n-v6bwi"/></radialGradient><radialGradient id="i8GpRbG" cx="0" cy="0" r="1" gradientTransform="rotate(143.881 6.994 9.938)scale(2.86275 1.23215)" gradientUnits="userSpaceOnUse"><stop offset=".255" class="o5ujuoler"/><stop offset="1" class="cvi6_hb_e"/></radialGradient><radialGradient id="iUb7kZR" cx="0" cy="0" r="1" gradientTransform="matrix(-.86719 0 0 -.96875 25.62 24.813)" gradientUnits="userSpaceOnUse"><stop class="nus19y6ts"/><stop offset="1" class="aiqsdtepb"/></radialGradient><radialGradient id="iliKE4b" cx="0" cy="0" r="1" gradientTransform="matrix(1.5625 -.65625 .66797 1.5904 17.72 25.172)" gradientUnits="userSpaceOnUse"><stop offset=".47" class="v5ts0ibjo"/><stop offset="1" class="huz3s4d_a"/></radialGradient><radialGradient id="iNgFFMe" cx="0" cy="0" r="1" gradientTransform="rotate(151.189 6.29 14.782)scale(1.78324)" gradientUnits="userSpaceOnUse"><stop offset=".632" class="da9xf6l5p"/><stop offset="1" class="cbgow0bwo"/></radialGradient><radialGradient id="iCW6Pzb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1094 -2 6.41983 -3.56106 16.3 25.516)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="egxex7b7c"/><stop offset=".943" class="hs-_dnasa"/></radialGradient><radialGradient id="ixYQKHd" cx="0" cy="0" r="1" gradientTransform="matrix(.03133 1.4211 -.52543 .01158 14.98 8.897)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="xy5gddgio"/><stop offset="1" class="vkl0cy_kr"/></radialGradient><radialGradient id="iq3zi1d" cx="0" cy="0" r="1" gradientTransform="matrix(-.75 -8.78125 2.52881 -.21598 17.94 23.906)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="xfmd1de7c"/><stop offset="1" class="kp4s9ga9x"/></radialGradient><radialGradient id="ikHZRUb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6875 .0625 -.11168 -3.01554 18.846 17.625)" gradientUnits="userSpaceOnUse"><stop offset=".284" class="ue87k_xsx"/><stop offset="1" class="vb5f4n1_q"/></radialGradient><radialGradient id="iLd5sqb" cx="0" cy="0" r="1" gradientTransform="matrix(5.125 -4.9297 2.6132 2.71672 16.815 15.531)" gradientUnits="userSpaceOnUse"><stop offset=".148" class="zwrak1b2j"/><stop offset="1" class="zvme7yb8w"/></radialGradient><radialGradient id="iATYDXc" cx="0" cy="0" r="1" gradientTransform="matrix(2.59375 -.09375 .01804 .49916 18.237 13.813)" gradientUnits="userSpaceOnUse"><stop offset=".22" class="aw4amab0f"/><stop offset="1" class="jqhw67baa"/></radialGradient><radialGradient id="iH0vVxd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.49999 -4.06251 1.70908 -1.47243 21.127 11.5)" gradientUnits="userSpaceOnUse"><stop class="tp4v0d6vm"/><stop offset="1" class="bptoyu2vz"/></radialGradient><radialGradient id="i0P2tWc" cx="0" cy="0" r="1" gradientTransform="matrix(3.25232 0 0 1.29925 10.078 12.938)" gradientUnits="userSpaceOnUse"><stop offset=".254" class="qktpib9mi"/><stop offset="1" class="ms8ncfh9g"/></radialGradient><radialGradient id="inFqrHe" cx="0" cy="0" r="1" gradientTransform="rotate(158.559 7.971 6.041)scale(1.11134 1.23837)" gradientUnits="userSpaceOnUse"><stop class="uos5e2bnd"/><stop offset="1" class="mp1bj4bkr"/></radialGradient><radialGradient id="i2Zwted" cx="0" cy="0" r="1" gradientTransform="matrix(1.70877 .92892 -1.02417 1.884 7.029 12.767)" gradientUnits="userSpaceOnUse"><stop offset=".686" class="srl5vfq7e"/><stop offset="1" class="csy3b3b7l"/></radialGradient><radialGradient id="iLjhO7c" cx="0" cy="0" r="1" gradientTransform="rotate(-169.577 4.854 6.554)scale(1.33255 2.06198)" gradientUnits="userSpaceOnUse"><stop offset=".68" class="vplpfacmu"/><stop offset="1" class="ijex08bei"/></radialGradient><radialGradient id="iYiWRhd" cx="0" cy="0" r="1" gradientTransform="matrix(5.5 -1.4375 2.00475 7.67032 17.377 14.688)" gradientUnits="userSpaceOnUse"><stop offset=".625" class="f6rwhfb_k"/><stop offset=".905" class="aw8cj7bar"/></radialGradient><radialGradient id="iSMKmod" cx="0" cy="0" r="1" gradientTransform="matrix(1.04759 .75841 -1.02541 1.4164 7.404 13.45)" gradientUnits="userSpaceOnUse"><stop offset=".686" class="srl5vfq7e"/><stop offset="1" class="csy3b3b7l"/></radialGradient><radialGradient id="ivLrJyw" cx="0" cy="0" r="1" gradientTransform="rotate(-167.973 4.888 6.752)scale(.83427 1.78585)" gradientUnits="userSpaceOnUse"><stop offset=".68" class="vplpfacmu"/><stop offset="1" class="ijex08bei"/></radialGradient><radialGradient id="iEcd0Jc" cx="0" cy="0" r="1" gradientTransform="matrix(1.01589 .59884 -.82449 1.39869 7.737 13.758)" gradientUnits="userSpaceOnUse"><stop offset=".686" class="srl5vfq7e"/><stop offset="1" class="csy3b3b7l"/></radialGradient><radialGradient id="iH0iWce" cx="0" cy="0" r="1" gradientTransform="matrix(-.75 -.07813 .17332 -1.6638 8.598 14.53)" gradientUnits="userSpaceOnUse"><stop offset=".68" class="vplpfacmu"/><stop offset="1" class="ijex08bei"/></radialGradient><radialGradient id="i8Jcowb" cx="0" cy="0" r="1" gradientTransform="rotate(33.66 -7.343 21.799)scale(.80591 .63241)" gradientUnits="userSpaceOnUse"><stop offset=".391" class="p62i0qb1k"/><stop offset="1" class="d7aonq0wf"/></radialGradient><radialGradient id="iBqQT1I" cx="0" cy="0" r="1" gradientTransform="matrix(3.09317 -1.20011 1.2447 3.20812 11.601 7.834)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="gro4u4t-y"/><stop offset="1" class="x8-nb-ihc"/></radialGradient><radialGradient id="iNjsIyd" cx="0" cy="0" r="1" gradientTransform="rotate(53.957 1.584 15.355)scale(1.91175 1.54264)" gradientUnits="userSpaceOnUse"><stop class="wxl7pfshq"/><stop offset="1" class="ghwh3eklg"/></radialGradient><radialGradient id="iKEClUc" cx="0" cy="0" r="1" gradientTransform="matrix(.19521 2.51495 -3.16966 .24603 12.885 6.917)" gradientUnits="userSpaceOnUse"><stop offset=".571" class="xsksv_erp"/><stop offset="1" class="mkydtabhq"/></radialGradient><radialGradient id="iCmjZFQ" cx="0" cy="0" r="1" gradientTransform="rotate(133.853 6.226 6.05)scale(2.3474 2.6131)" gradientUnits="userSpaceOnUse"><stop offset=".368" class="zpplycc0o"/><stop offset="1" class="cm0gm6bcb"/></radialGradient><radialGradient id="i8uM9kb" cx="0" cy="0" r="1" gradientTransform="rotate(108.778 6.273 7.838)scale(2.63871 3.80525)" gradientUnits="userSpaceOnUse"><stop offset=".094" class="gs2o78_ix"/><stop offset="1" class="kjuj_ebnl"/></radialGradient><radialGradient id="iwWI1ZI" cx="0" cy="0" r="1" gradientTransform="matrix(-.64 -.57853 .57853 -.64 13.958 6.09)" gradientUnits="userSpaceOnUse"><stop class="hxeazccbz"/><stop offset="1" class="lr--i_bdd"/></radialGradient><radialGradient id="irHMZvb" cx="0" cy="0" r="1" gradientTransform="matrix(.1877 -.0902 .5287 1.10021 13.444 6.372)" gradientUnits="userSpaceOnUse"><stop class="pav55masc"/><stop offset="1" class="egqy8jbwr"/></radialGradient><radialGradient id="ibXte0u" cx="0" cy="0" r="1" gradientTransform="matrix(1.02975 2.14753 -2.52412 1.21033 11.885 3.225)" gradientUnits="userSpaceOnUse"><stop offset=".045" class="w9h_a4buy"/><stop offset=".919" class="jvvv5bmeo"/></radialGradient><radialGradient id="iAEzulC" cx="0" cy="0" r="1" gradientTransform="matrix(-.30299 -.6133 1.57273 -.77698 12.41 4.979)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="chmofghwi"/><stop offset="1" class="tn7myqe_j"/></radialGradient><filter id="iGyDTil" width="28.938" height="27.87" x="2.031" y="3.105" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.219608 0 0 0 0 0.658824 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23491"/></filter><filter id="ix5Ed2b" width="8.378" height="5.198" x="17.771" y="3.105" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.705882 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23491"/></filter><filter id="iiyQVVb" width="27.922" height="3.388" x="2.047" y="26.802" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.258824 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23491"/></filter><filter id="iIGF45d" width="9.938" height="9.938" x="2.104" y="20.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.227451 0 0 0 0 0.156863 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23491"/></filter><filter id="itjVTSs" width="10.409" height="10.409" x="1.868" y="19.772" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23491" stdDeviation=".25"/></filter><filter id="iUiedme" width="10.037" height="10.037" x="20.049" y="19.908" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.152941 0 0 0 0 0.0862745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23491"/></filter><filter id="iuLmSLc" width="9.188" height="4.077" x="16.682" y="22.863" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.341176 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23491"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.490196 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23491" result="effect2_innerShadow_3987_23491"/></filter><filter id="iBIYBVc" width="4.034" height="2.181" x="13.544" y="23.076" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.188235 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23491"/></filter><filter id="i0Ejijc" width="3.572" height="8.62" x="15.217" y="15.486" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.890196 0 0 0 0 0.654902 0 0 0 0 0.54902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23491"/></filter><filter id="iPskwjd" width="6.668" height="7.67" x="16.596" y="10.352" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.360784 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23491"/></filter><filter id="iBt9zwn" width="7.971" height="5.869" x="15.054" y="7.256" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.301961 0 0 0 0 0.243137 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23491"/></filter><filter id="inbtUbM" width="6.005" height="4.259" x="6.951" y="11.034" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.505882 0 0 0 0 0.529412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23491"/></filter><filter id="iRcIcPv" width="3.137" height="2.915" x="6.951" y="12.629" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.117647 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23491"/></filter><filter id="i3hO3XB" width="10.272" height="6.937" x="7.828" y="7.591" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.478431 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23491"/></filter><filter id="i264rOe" width="5.496" height="6.372" x="17.742" y="10.775" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23491" stdDeviation=".3"/></filter><filter id="icCUF7d" width="2.969" height="2.969" x="7.756" y="11.939" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23491" stdDeviation=".3"/></filter><filter id="ibZokyc" width="5.55" height="5.068" x="10.354" y="4.623" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.670588 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23491"/></filter><filter id="iu4zYHd" width="4.513" height="3.779" x="12.86" y="3.933" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.607843 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23491"/></filter><filter id="iUyYELb" width="5.921" height="5.085" x="9.292" y="1.828" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.556863 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23491"/></filter><filter id="ial1Qae" width="1.998" height="1.386" x="11.255" y="3.983" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.482353 0 0 0 0 0.796078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23491"/></filter><linearGradient id="i3JoEEd" x1="9.65" x2="27.955" y1="21.049" y2="8.859" gradientUnits="userSpaceOnUse"><stop class="jk9sxjbtz"/><stop offset="1" class="bsmaek8tk"/></linearGradient><linearGradient id="iqatzCe" x1="29.363" x2="25.903" y1="12.037" y2="14.451" gradientUnits="userSpaceOnUse"><stop offset=".164" class="lc4-hmwkn"/><stop offset="1" class="jvv3w_k0n"/></linearGradient><linearGradient id="i9KOU6b" x1="21.156" x2="24.898" y1="7.049" y2="4.957" gradientUnits="userSpaceOnUse"><stop class="tw0q1w8vf"/><stop offset="1" class="icj8g3w8l"/></linearGradient><linearGradient id="iMqUPPc" x1="9.283" x2="3.252" y1="21.313" y2="28.344" gradientUnits="userSpaceOnUse"><stop class="aqhis8bfy"/><stop offset="1" class="dicaxrbsa"/></linearGradient><linearGradient id="ir9Uywd" x1="17.752" x2="18.721" y1="20.516" y2="19.51" gradientUnits="userSpaceOnUse"><stop offset=".573" class="xlkews62x"/><stop offset="1" class="ma809rb2k"/></linearGradient><linearGradient id="iAUidTI" x1="22.268" x2="17.674" y1="22.084" y2="21.625" gradientUnits="userSpaceOnUse"><stop offset=".891" class="eper2rg6p"/><stop offset="1" class="btv0f_swr"/></linearGradient><linearGradient id="ikI6zud" x1="11.549" x2="10.674" y1="14.906" y2="14.625" gradientUnits="userSpaceOnUse"><stop class="b32taybyq"/><stop offset="1" class="cq_k1jhvn"/></linearGradient><linearGradient id="iByKjmc" x1="9.783" x2="8.502" y1="19.86" y2="19.375" gradientUnits="userSpaceOnUse"><stop offset=".146" class="l2qa6pp5f"/><stop offset="1" class="j4w4r7dqg"/></linearGradient><linearGradient id="iyuxnsc" x1="13.002" x2="13.393" y1="21.907" y2="21.407" gradientUnits="userSpaceOnUse"><stop class="xlcjgwbhs"/><stop offset="1" class="xdbcf5brc"/><stop offset="1" class="dkvvw7m1c"/></linearGradient><linearGradient id="iWYSLge" x1="20.049" x2="27.804" y1="27.417" y2="24.977" gradientUnits="userSpaceOnUse"><stop class="qkrvzzbyd"/><stop offset="1" class="zaq2lsbln"/></linearGradient><linearGradient id="iDeh7Jb" x1="23.83" x2="22.768" y1="21.844" y2="22.594" gradientUnits="userSpaceOnUse"><stop class="ikszdii2u"/><stop offset="1" class="li38i4ecv"/></linearGradient><linearGradient id="i7VZLSd" x1="19.627" x2="18.612" y1="20.617" y2="20.469" gradientUnits="userSpaceOnUse"><stop class="wjlh8kb9f"/><stop offset="1" class="pf-dzrbda"/></linearGradient><linearGradient id="iqttsuc" x1="16.635" x2="17.002" y1="13.742" y2="14.273" gradientUnits="userSpaceOnUse"><stop class="oqmso-c_s"/><stop offset="1" class="s2g06frqj"/></linearGradient><linearGradient id="iv0gtpe" x1="25.346" x2="16.682" y1="24.977" y2="24.977" gradientUnits="userSpaceOnUse"><stop class="jk12cqb2p"/><stop offset="1" class="bjfaebcql"/></linearGradient><linearGradient id="iQhym4p" x1="17.479" x2="16.721" y1="24.844" y2="24.844" gradientUnits="userSpaceOnUse"><stop class="z_jgx_kqm"/><stop offset="1" class="ktkvjmbcj"/></linearGradient><linearGradient id="i0pmBre" x1="15.565" x2="13.52" y1="9.375" y2="9.458" gradientUnits="userSpaceOnUse"><stop class="ehwoun8pp"/><stop offset="1" class="euksxhdfs"/></linearGradient><linearGradient id="iFgL5wb" x1="11.182" x2="11.42" y1="7.21" y2="7.063" gradientUnits="userSpaceOnUse"><stop offset=".242" class="qrd5snbhi"/><stop offset=".667" class="ywpul_b7i"/></linearGradient><linearGradient id="ieFk6mc" x1="13.816" x2="13.399" y1="6.553" y2="6.775" gradientUnits="userSpaceOnUse"><stop class="zcigs7bii"/><stop offset="1" class="nr87if9lw"/></linearGradient><linearGradient id="i1NlFwg" x1="13.694" x2="14.216" y1="8.373" y2="8.048" gradientUnits="userSpaceOnUse"><stop offset=".324" class="x0zx5qyer"/><stop offset="1" class="k6zficbhz"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-mountain-biking-medium-light" /></template>
<style>
.aiqsdtepb {
  stop-color: var(--svg-color--ffd359, #FFD359);
  stop-opacity: 0;
}

.aqhis8bfy {
  stop-color: var(--svg-color--302a5b, #302A5B);
}

.aw4amab0f {
  stop-color: var(--svg-color--736e75, #736E75);
}

.aw8cj7bar {
  stop-color: var(--svg-color--afa6a9, #AFA6A9);
}

.b32taybyq {
  stop-color: var(--svg-color--bfa8c7, #BFA8C7);
}

.b3q5ubbch {
  d: path("m14.015 15.445l1.34-.836l1.038 1.04l-.765 3.53a200 200 0 0 0-1.688-1.241c-.148-.102-.66-.543-.653-1.239c.008-.71.477-1.071.727-1.254");
}

.bgnynkbvn {
  d: path("m15.065 4.332l-4.65 2.546a.26.26 0 0 1-.341-.069a5.6 5.6 0 0 1-.603-1.121c-.576-1.435.412-2.275.54-2.404c.187-.187.703-.65 1.826-1.097c1.318-.525 2.179.043 2.607.582c.268.34.566.852.74 1.198a.275.275 0 0 1-.12.365");
}

.bjfaebcql {
  stop-color: var(--svg-color--e8774d, #E8774D);
}

.bleghrbgv {
  fill-rule: evenodd;
  d: path("M9.337 12.922a.35.35 0 0 1-.35.35c-.173 0-.436.043-.663.15c-.226.106-.37.252-.415.438a.35.35 0 0 1-.68-.165c.113-.466.462-.748.796-.906s.7-.217.962-.217a.35.35 0 0 1 .35.35");
}

.bptoyu2vz {
  stop-color: var(--svg-color--674e9f, #674E9F);
}

.bsmaek8tk {
  stop-color: var(--svg-color--36c571, #36C571);
}

.btv0f_swr {
  stop-color: var(--svg-color--615f76, #615F76);
}

.c_y4ucu-s {
  stop-color: var(--svg-color--b57d68, #B57D68);
}

.cbgow0bwo {
  stop-color: var(--svg-color--e2dfe5, #E2DFE5);
}

.cc4vvtr3m {
  fill-rule: evenodd;
  d: path("M9.647 18.563c.101-.222.43-.466.672-.282l6.25 4.75a.55.55 0 1 1-.665.876l-6.081-4.61c-.242-.184-.305-.453-.176-.734");
}

.cc9670aeb {
  stop-color: var(--svg-color--932145, #932145);
}

.chmofghwi {
  stop-color: var(--svg-color--4b89d0, #4B89D0);
}

.cm0gm6bcb {
  stop-color: var(--svg-color--d59e88, #D59E88);
  stop-opacity: 0;
}

.cpzd76x5u {
  fill-rule: evenodd;
  d: path("M17.142 8.274c.479.327.601.98.274 1.46c-.783 1.144-3.152 4.302-7.933 4.787c-.577.059-1.594-.319-1.653-.896s.865-1.134 1.441-1.193c3.844-.39 5.741-2.904 6.412-3.884a1.05 1.05 0 0 1 1.459-.274");
}

.cq_k1jhvn {
  stop-color: var(--svg-color--908590, #908590);
}

.csy3b3b7l {
  stop-color: var(--svg-color--bc7c7f, #BC7C7F);
}

.cvi6_hb_e {
  stop-color: var(--svg-color--564a5a, #564A5A);
}

.czabn_xgs {
  d: path("M13.554 7.913h2.154v2.668h-2.154z");
}

.d-6jagb2y {
  stop-color: var(--svg-color--ac2735, #AC2735);
}

.d7aonq0wf {
  stop-color: var(--svg-color--d4997b, #D4997B);
}

.d98osxiir {
  fill: var(--svg-color--97595f, #97595F);
  d: path("m5.663 27.16l-3.616 2.158v.672h27.922v-.672l-3.532-2.15a2.4 2.4 0 0 0-2.429-.04l-.817.462a2 2 0 0 1-1.838.067l-1.319-.622a2.25 2.25 0 0 0-1.965.02l-1.176.587a2 2 0 0 1-1.823-.019l-1.126-.591a2 2 0 0 0-1.783-.04l-1.42.67a2 2 0 0 1-1.825-.062l-.855-.476a2.4 2.4 0 0 0-2.398.036");
}

.da9xf6l5p {
  stop-color: var(--svg-color--e2dfe5, #E2DFE5);
  stop-opacity: 0;
}

.dicaxrbsa {
  stop-color: var(--svg-color--302a5b, #302A5B);
  stop-opacity: 0;
}

.dkvvw7m1c {
  stop-color: var(--svg-color--9c2649, #9C2649);
  stop-opacity: 0;
}

.e_--_59xk {
  d: path("m18.38 13.777l-.636-.699l4.032-2.476c1.422 1.867 1.5 3.21.836 4.273s-1.582 2.05-2.618 2.945c-.271.235-.802.362-1.359-.18c-.707-.687-1.578-1.578-2.04-2.113l1.778-1.608a.1.1 0 0 0 .007-.142");
}

.e4rocubwy {
  fill: var(--svg-color--86004d, #86004D);
  fill-rule: evenodd;
  d: path("M11.97 8.632a.117.117 0 0 1 .038-.162c.1-.063.232-.216.298-.534a.117.117 0 1 1 .23.047c-.075.363-.235.58-.404.686a.117.117 0 0 1-.161-.037");
}

.egqy8jbwr {
  stop-color: var(--svg-color--4d3a6e, #4D3A6E);
  stop-opacity: 0;
}

.egxex7b7c {
  stop-color: var(--svg-color--5c4f86, #5C4F86);
  stop-opacity: 0;
}

.ehwoun8pp {
  stop-color: var(--svg-color--e1ae8c, #E1AE8C);
}

.eper2rg6p {
  stop-color: var(--svg-color--615f76, #615F76);
  stop-opacity: 0;
}

.euksxhdfs {
  stop-color: var(--svg-color--b66c66, #B66C66);
}

.ewlxb1b8e {
  d: path("M12.092 9.159c-.797-.724-1.469-1.902-1.738-2.362l3.41-2.174l1.89 1.635a5.2 5.2 0 0 1-.888 1.932c-.688.904-1.63 1.92-2.674.969");
}

.f-r3ld20z {
  stop-color: var(--svg-color--baa3b9, #BAA3B9);
}

.f2dg1pymm {
  cx: 7.072px;
  cy: 24.977px;
  r: 4.555px;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
}

.f6rwhfb_k {
  stop-color: var(--svg-color--afa6a9, #AFA6A9);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fuvqv0efx {
  fill-rule: evenodd;
  d: path("M10.57 16.335a.55.55 0 0 1 .3.718l-3.289 8a.55.55 0 0 1-1.017-.418l3.289-8a.55.55 0 0 1 .718-.3");
}

.fy0gg3b4w {
  stop-color: var(--svg-color--d9d1df, #D9D1DF);
  stop-opacity: 0;
}

.ghwh3eklg {
  stop-color: var(--svg-color--a46f70, #A46F70);
  stop-opacity: 0;
}

.gro4u4t-y {
  stop-color: var(--svg-color--d19f82, #D19F82);
}

.gs2o78_ix {
  stop-color: var(--svg-color--fee0b4, #FEE0B4);
}

.gtw3mmb0a {
  stop-color: var(--svg-color--dca28a, #DCA28A);
  stop-opacity: 0;
}

.gxtng2bih {
  stop-color: var(--svg-color--5d5c7e, #5D5C7E);
  stop-opacity: 0;
}

.h-r_c9b7x {
  d: path("m15.295 14.645l2.64-1.61l1.208.63l-2.727 2.476c-.268-.232-.84-1.051-1.12-1.496");
}

.hk_2rww3p {
  d: path("m19.204 20.133l-1.827-1.988l-.423 2.058l1 .706z");
}

.hla563ezk {
  d: path("M16.112 11.156c.664.625 1.363 1.586 1.671 1.969l4.243-2.18c-.586-.976-2.07-2.53-3.54-3.359c-1.718-.813-2.672 0-3.305 1.07c-.413.852.259 1.781.93 2.5");
}

.hqorccbwh {
  stop-color: var(--svg-color--3c2150, #3C2150);
}

.hs-_dnasa {
  stop-color: var(--svg-color--493b63, #493B63);
}

.huz3s4d_a {
  stop-color: var(--svg-color--c5bfcb, #C5BFCB);
}

.hxeazccbz {
  stop-color: var(--svg-color--e8bda2, #E8BDA2);
}

.hz6yw06qq {
  fill: var(--svg-color--5b4e85, #5B4E85);
  d: path("m16.115 23.226l-1.809.861c-.43.212-.756.465-.762.956c0 .124.108.214.231.214h3.504a.2.2 0 0 0 .2-.2v-1.15z");
}

.icj8g3w8l {
  stop-color: var(--svg-color--e2dce7, #E2DCE7);
}

.ijex08bei {
  stop-color: var(--svg-color--d29a8c, #D29A8C);
}

.ikszdii2u {
  stop-color: var(--svg-color--fd5a60, #FD5A60);
}

.iy0i0xbqt {
  d: path("M12.955 11.61a.575.575 0 0 0-.575-.576H9.33a2.13 2.13 0 0 0 0 4.26h.183a.575.575 0 1 0 0-1.15H9.33a.98.98 0 1 1 0-1.96h3.05a.575.575 0 0 0 .575-.575");
}

.j4w4r7dqg {
  stop-color: var(--svg-color--973c50, #973C50);
}

.jk12cqb2p {
  stop-color: var(--svg-color--f7b14e, #F7B14E);
}

.jk5eocp2v {
  stop-color: var(--svg-color--e44354, #E44354);
  stop-opacity: 0;
}

.jk9sxjbtz {
  stop-color: var(--svg-color--37c173, #37C173);
}

.jqhw67baa {
  stop-color: var(--svg-color--736e75, #736E75);
  stop-opacity: 0;
}

.jvv3w_k0n {
  stop-color: var(--svg-color--36c871, #36C871);
  stop-opacity: 0;
}

.jvvv5bmeo {
  stop-color: var(--svg-color--52abe4, #52ABE4);
}

.k14lsyzjk {
  fill: var(--svg-color--d19e7f, #D19E7F);
  fill-rule: evenodd;
  d: path("M17.142 8.274c.479.327.601.98.274 1.46c-.783 1.144-3.152 4.302-7.933 4.787c-.577.059-1.594-.319-1.653-.896s.865-1.134 1.441-1.193c3.844-.39 5.741-2.904 6.412-3.884a1.05 1.05 0 0 1 1.459-.274");
}

.k6zficbhz {
  stop-color: var(--svg-color--72687c, #72687C);
  stop-opacity: 0;
}

.kjuj_ebnl {
  stop-color: var(--svg-color--e7bca0, #E7BCA0);
}

.kkue_wb7v {
  d: path("m17.771 7.508l2.247-1.314a.4.4 0 0 1 .511.09l1.07 1.3a.6.6 0 0 0 .927 0l1.067-1.296a.4.4 0 0 1 .515-.089L25.9 7.276l-2.07-3.138a2.3 2.3 0 0 0-3.841.002z");
}

.kp4s9ga9x {
  stop-color: var(--svg-color--d29a7d, #D29A7D);
}

.ktkvjmbcj {
  stop-color: var(--svg-color--605c92, #605C92);
  stop-opacity: 0;
}

.l2qa6pp5f {
  stop-color: var(--svg-color--d4385b, #D4385B);
}

.l4_q8ccja {
  stop-color: var(--svg-color--ebeaed, #EBEAED);
}

.lc4-hmwkn {
  stop-color: var(--svg-color--4cdd80, #4CDD80);
}

.li38i4ecv {
  stop-color: var(--svg-color--af253c, #AF253C);
}

.lr--i_bdd {
  stop-color: var(--svg-color--c48b7a, #C48B7A);
}

.luorv-7fc {
  d: path("m14.433 7.221l-1.014-1.04l-.559-.913l2.226-1.135c.066.098.33.327.856.464a1.75 1.75 0 0 1 1.098.858c.135.233.543 1.298-.586 2c-.904.56-1.724.078-2.021-.234");
}

.m_jah6j1d {
  stop-color: var(--svg-color--ad6e5f, #AD6E5F);
}

.m3q9izqvj {
  stop-color: var(--svg-color--5d5c7e, #5D5C7E);
}

.m94qeobdh {
  d: path("M11.296 5.18a.354.354 0 0 1 .148-.479l1.29-.677a.354.354 0 0 1 .329.627l-1.29.677a.354.354 0 0 1-.477-.148");
}

.ma809rb2k {
  stop-color: var(--svg-color--c6957f, #C6957F);
}

.mkydtabhq {
  stop-color: var(--svg-color--bd7678, #BD7678);
}

.mp1bj4bkr {
  stop-color: var(--svg-color--ebbca0, #EBBCA0);
  stop-opacity: 0;
}

.ms8ncfh9g {
  stop-color: var(--svg-color--8c5ea8, #8C5EA8);
  stop-opacity: 0;
}

.msqk4cb8o {
  stop-color: var(--svg-color--373c67, #373C67);
}

.mvvhg6bob {
  fill-rule: evenodd;
  d: path("M12.505 11.6a.5.5 0 0 1 .271.653l-2.54 6.247a.5.5 0 0 1-.924-.381l2.54-6.247a.5.5 0 0 1 .653-.272");
}

.nr87if9lw {
  stop-color: var(--svg-color--37234c, #37234C);
  stop-opacity: 0;
}

.nrp3vkbjq {
  fill-rule: evenodd;
  d: path("M19.756 16.62a.55.55 0 0 0-.172.76l4.719 7.476a.55.55 0 1 0 .93-.587l-4.719-7.477a.55.55 0 0 0-.758-.171");
}

.nus19y6ts {
  stop-color: var(--svg-color--ffd359, #FFD359);
}

.o0tyh0b-k {
  d: path("m16.096 16l.553-.514l2.04 1.916c-.273.154-.886.464-1.03.582c-.11.091-.11.235-.11.329l-.046 5.593l-1.407-.672c-.138-.794-.42-2.708-.769-4.3c-.395-1.801.376-2.593.77-2.934");
}

.o5ujuoler {
  stop-color: var(--svg-color--4f414e, #4F414E);
}

.oqmso-c_s {
  stop-color: var(--svg-color--72696b, #72696B);
}

.oxni39rcm {
  d: path("M10.895 8.428c-.206-.135-.213-.295-.155-.651a.82.82 0 0 0-.074-.535l.835.975c-.104.225-.401.346-.606.21");
}

.p0n-v6bwi {
  stop-color: var(--svg-color--dca28a, #DCA28A);
}

.p1dkvx0ja {
  stop-color: var(--svg-color--8a4c56, #8A4C56);
  stop-opacity: 0;
}

.p1mhlac7z {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.04 6.75c-.064.23.077.455.153.569l.876-.545c-.54-.581-.94-.337-1.028-.024");
}

.p62i0qb1k {
  stop-color: var(--svg-color--cc9778, #CC9778);
}

.pav55masc {
  stop-color: var(--svg-color--564975, #564975);
}

.pf-dzrbda {
  stop-color: var(--svg-color--a62f2f, #A62F2F);
}

.pfbx1ib6q {
  fill-rule: evenodd;
  d: path("M25.018 21.008a3.969 3.969 0 1 0 0 7.937a3.969 3.969 0 0 0 0-7.937m-4.969 3.969a4.969 4.969 0 1 1 9.938 0a4.969 4.969 0 0 1-9.938 0");
}

.ppui9tpqg {
  fill: var(--svg-color--4d3771, #4D3771);
  fill-rule: evenodd;
  d: path("M12.713 5.053a.293.293 0 0 1 .39.138l1.576 3.296a.293.293 0 1 1-.529.253l-1.575-3.296a.293.293 0 0 1 .138-.391");
}

.pypniyb9c {
  fill-rule: evenodd;
  d: path("M8.827 13.457a.35.35 0 0 1-.227.44a.6.6 0 0 0-.406.457a.35.35 0 1 1-.683-.152c.05-.223.235-.767.876-.972a.35.35 0 0 1 .44.227");
}

.pzip1rpvk {
  fill: var(--svg-color--c0b9bc, #C0B9BC);
  d: path("M12.955 11.61a.575.575 0 0 0-.575-.576H9.33a2.13 2.13 0 0 0 0 4.26h.183a.575.575 0 1 0 0-1.15H9.33a.98.98 0 1 1 0-1.96h3.05a.575.575 0 0 0 .575-.575");
}

.q04uptb_f {
  fill: var(--svg-color--413354, #413354);
  d: path("m17.898 20.866l-.3 1.98c-.067.477-.04.888.364 1.168c.102.07.238.03.307-.072l1.964-2.901a.2.2 0 0 0-.054-.278l-.952-.644z");
}

.q4qmhdcyz {
  fill: var(--svg-color--654b4b, #654B4B);
  d: path("m11.685 7.013l-.03-.048c-.166-.246-.407-.373-.54-.283c-.132.089-.105.36.06.606l.02.03z");
}

.qc8cprh-k {
  d: path("m21.006 12.895l-.523-.863l1.125-.656c.968 1.312 1.343 2.296.734 2.875c-.487.462-2.87 1.723-4 2.296l2.503-2.414a1 1 0 0 0 .161-1.238");
}

.qfj7itbso {
  stop-color: var(--svg-color--8a4c56, #8A4C56);
}

.qkrvzzbyd {
  stop-color: var(--svg-color--352542, #352542);
}

.qktpib9mi {
  stop-color: var(--svg-color--8c5ea8, #8C5EA8);
}

.qnv5cwbcc {
  stop-color: var(--svg-color--baa3b9, #BAA3B9);
  stop-opacity: 0;
}

.qrd5snbhi {
  stop-color: var(--svg-color--5f5451, #5F5451);
}

.rgol9fpyb {
  stop-color: var(--svg-color--e44354, #E44354);
}

.rrfczgbhc {
  cx: 18.389px;
  cy: 24.977px;
  r: 1.027px;
}

.s2g06frqj {
  stop-color: var(--svg-color--72696b, #72696B);
  stop-opacity: 0;
}

.srl5vfq7e {
  stop-color: var(--svg-color--c38a80, #C38A80);
}

.t5qustb5j {
  fill-rule: evenodd;
  d: path("M12.713 5.053a.293.293 0 0 1 .39.138l1.576 3.296a.293.293 0 1 1-.529.253l-1.575-3.296a.293.293 0 0 1 .138-.391");
}

.tg-9ku_mf {
  stop-color: var(--svg-color--bf7a7b, #BF7A7B);
}

.tks1wp4pj {
  fill-rule: evenodd;
  d: path("M8.974 13.516a.33.33 0 0 1 0 .403c-.151.125-.343.389-.372.593a.35.35 0 0 1-.693-.1c.019-.13.077-.286.155-.43c.08-.147.196-.312.354-.443c.148-.123.433-.171.556-.023");
}

.tn7myqe_j {
  stop-color: var(--svg-color--337bcd, #337BCD);
}

.tp4v0d6vm {
  stop-color: var(--svg-color--977ed0, #977ED0);
}

.truymkbqg {
  stop-color: var(--svg-color--b57b69, #B57B69);
  stop-opacity: 0;
}

.tw0q1w8vf {
  stop-color: var(--svg-color--d7cfdf, #D7CFDF);
}

.u3_kb5fuo {
  fill: var(--svg-color--2b174f, #2B174F);
  fill-rule: evenodd;
  d: path("M8.35 13.223V13.2a.572.572 0 1 0-1.145 0v.022h-.004a2.13 2.13 0 0 0 2.13 2.07h.182a.575.575 0 0 0 0-1.15H9.33a.98.98 0 0 1-.978-.92z");
}

.u7zxukb7a {
  cx: 13.489px;
  cy: 5.752px;
  r: 0.655px;
}

.ue1cg0jtk {
  fill-rule: evenodd;
  d: path("M7.073 21.008a3.969 3.969 0 1 0 0 7.937a3.969 3.969 0 0 0 0-7.937m-4.97 3.969a4.969 4.969 0 1 1 9.938 0a4.969 4.969 0 0 1-9.937 0");
}

.ue87k_xsx {
  stop-color: var(--svg-color--b7707a, #B7707A);
}

.um4kzybeo {
  d: path("m16.115 23.226l-1.809.861c-.43.212-.756.465-.762.956c0 .124.108.214.231.214h3.504a.2.2 0 0 0 .2-.2v-1.15z");
}

.uos5e2bnd {
  stop-color: var(--svg-color--ebbca0, #EBBCA0);
}

.v1kdh7m2c {
  d: path("m5.663 27.16l-3.616 2.158v.672h27.922v-.672l-3.532-2.15a2.4 2.4 0 0 0-2.429-.04l-.817.462a2 2 0 0 1-1.838.067l-1.319-.622a2.25 2.25 0 0 0-1.965.02l-1.176.587a2 2 0 0 1-1.823-.019l-1.126-.591a2 2 0 0 0-1.783-.04l-1.42.67a2 2 0 0 1-1.825-.062l-.855-.476a2.4 2.4 0 0 0-2.398.036");
}

.v5ts0ibjo {
  stop-color: var(--svg-color--d8cfe2, #D8CFE2);
}

.vb5f4n1_q {
  stop-color: var(--svg-color--b7707a, #B7707A);
  stop-opacity: 0;
}

.vkl0cy_kr {
  stop-color: var(--svg-color--e0a588, #E0A588);
  stop-opacity: 0;
}

.vplpfacmu {
  stop-color: var(--svg-color--d29a8c, #D29A8C);
  stop-opacity: 0;
}

.w9h_a4buy {
  stop-color: var(--svg-color--4fbdff, #4FBDFF);
}

.wc0bxtmli {
  stop-color: var(--svg-color--38144f, #38144F);
}

.wem5pbj-u {
  cx: 11.159px;
  cy: 6.856px;
  r: 0.085px;
  fill: var(--svg-color--dfdfdf, #DFDFDF);
}

.wjlh8kb9f {
  stop-color: var(--svg-color--e5435f, #E5435F);
}

.wjs_nsbuh {
  fill-rule: evenodd;
  d: path("M20.06 16.541a.55.55 0 0 1 .417.657l-1.579 7.078a.55.55 0 0 1-1.073-.24l1.578-7.078a.55.55 0 0 1 .657-.417");
}

.wm4p2nf6o {
  d: path("M18.93 26.8a1.863 1.863 0 1 1 .018-3.643l5.898.906a.927.927 0 0 1-.086 1.837z");
}

.wo6zfvbcw {
  fill: var(--svg-color--1b131c, #1B131C);
  d: path("M11.946 6.416a.82.82 0 0 0-.59.016c.286.143.345.376.503.353c.206-.029.287-.293.087-.37");
}

.wuejk-0mo {
  d: path("M11.499 7.13a1 1 0 0 0-.05-.092c-.093-.137-.226-.21-.298-.16c-.072.048-.056.198.037.335a1 1 0 0 0 .058.073z");
}

.wxl7pfshq {
  stop-color: var(--svg-color--a46f70, #A46F70);
}

.x0zx5qyer {
  stop-color: var(--svg-color--72687c, #72687C);
}

.x8-nb-ihc {
  stop-color: var(--svg-color--cf9388, #CF9388);
}

.xdbcf5brc {
  stop-color: var(--svg-color--96275e, #96275E);
  stop-opacity: 0;
}

.xfmd1de7c {
  stop-color: var(--svg-color--e2ae96, #E2AE96);
}

.xlcjgwbhs {
  stop-color: var(--svg-color--96275e, #96275E);
}

.xlkews62x {
  stop-color: var(--svg-color--bb7774, #BB7774);
}

.xsksv_erp {
  stop-color: var(--svg-color--ca9081, #CA9081);
  stop-opacity: 0;
}

.xy5gddgio {
  stop-color: var(--svg-color--e0a588, #E0A588);
}

.y16t4y92n {
  stop-color: var(--svg-color--32295b, #32295B);
}

.y5h98bc-a {
  d: path("m3.898 16.756l-1.867 1.937v11.282H29.97V13.443l-6.14-9.305a2.3 2.3 0 0 0-3.841.002l-8.916 13.55a.5.5 0 0 1-.715.126L8.309 16.3c-1.32-.98-3.2-.8-4.41.457");
}

.yhwal5uej {
  d: path("m17.898 20.866l-.3 1.98c-.067.477-.04.888.364 1.168c.102.07.238.03.307-.072l1.964-2.901a.2.2 0 0 0-.054-.278l-.952-.644z");
}

.ywpul_b7i {
  stop-color: var(--svg-color--383838, #383838);
}

.z_jgx_kqm {
  stop-color: var(--svg-color--605c92, #605C92);
}

.zaq2lsbln {
  stop-color: var(--svg-color--352542, #352542);
  stop-opacity: 0;
}

.zcigs7bii {
  stop-color: var(--svg-color--37234c, #37234C);
}

.zd8v8x_xx {
  stop-color: var(--svg-color--ac2735, #AC2735);
  stop-opacity: 0;
}

.zlie59b6o {
  cx: 9.24px;
  cy: 13.424px;
  r: 0.885px;
  fill: var(--svg-color--d7a58b, #D7A58B);
}

.zo6cprbov {
  stop-color: var(--svg-color--ce3d5e, #CE3D5E);
}

.zpplycc0o {
  stop-color: var(--svg-color--d59e88, #D59E88);
}

.zvme7yb8w {
  stop-color: var(--svg-color--a3a1a2, #A3A1A2);
}

.zwrak1b2j {
  stop-color: var(--svg-color--726b71, #726B71);
}

</style>
