<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iqC7Yxk)" clip-rule="evenodd" class="icncv2mqv"/><path fill="url(#iMRjGCv)" clip-rule="evenodd" class="jfusrx6ed"/><g filter="url(#iiyr9mb)"><path fill="url(#iSuVWgb)" class="c56wt9b_p"/><path fill="url(#iju7awd)" class="c56wt9b_p"/></g><path fill="url(#igrr9bc)" class="eyfprhbml"/><path fill="url(#islyQFe)" class="eyfprhbml"/><g filter="url(#i2EQIyb)"><path class="cr4sxsh_p"/></g><path fill="url(#i0a1jac)" class="tdqm2_hbg"/><path fill="url(#iBfNslb)" class="tdqm2_hbg"/><path fill="url(#iQV6NXa)" class="tdqm2_hbg"/><path fill="url(#iKoHPAe)" class="j393hh9jx"/><path fill="url(#iIy7Ryc)" class="j393hh9jx"/><path fill="url(#iKVO9Zb)" class="j393hh9jx"/><path fill="url(#iGBdH9c)" class="io78i4bem"/><path fill="url(#iuilNwe)" class="io78i4bem"/><path fill="url(#iIrAzhe)" class="io78i4bem"/><path class="q-rxwlb3c"/><path fill="url(#iSq3Ivb)" class="rond61bua"/><path fill="url(#ifhliKd)" class="rond61bua"/><path fill="url(#iMdunfc)" class="rond61bua"/><g filter="url(#irNKyZm)"><path class="mblkjgfgo"/><path fill="url(#izKyXkd)" class="rsucbzb8b"/><path fill="url(#iHb6CBe)" class="rsucbzb8b"/><path fill="url(#iRa5bde)" class="rsucbzb8b"/></g><g filter="url(#izeKIwj)"><path fill="url(#itc7hkf)" class="h5sl0ws-f"/></g><g filter="url(#iTcVfAd)"><path fill="url(#ijnUYlc)" class="lgo3_ibwu"/><path fill="url(#ioMDxIe)" class="lgo3_ibwu"/></g><g filter="url(#iMcbfRd)"><path fill="url(#i7EEymg)" class="n32upfbdg"/><path fill="url(#iADPLse)" class="n32upfbdg"/></g><path fill="url(#iplOczb)" class="n32upfbdg"/><path clip-rule="evenodd" class="elqd_wbxf"/><path fill="url(#iz6ucle)" clip-rule="evenodd" class="ixa22uwgh"/><path clip-rule="evenodd" class="wyplhh6vs"/><path fill="url(#i7Tgzib)" clip-rule="evenodd" class="lrg695bhi"/><path clip-rule="evenodd" class="hd_puhbmm"/><path fill="url(#iRmR28b)" clip-rule="evenodd" class="s76wkwjkc"/><path clip-rule="evenodd" class="npcds_a-e"/><path fill="url(#iNMpu3c)" clip-rule="evenodd" class="abaaqi4hd"/><path clip-rule="evenodd" class="rgyldmb2f"/><path fill="url(#iLLwgto)" clip-rule="evenodd" class="ikftlibzf"/><path clip-rule="evenodd" class="lf2bt8iil"/><path fill="url(#i6K6vWb)" clip-rule="evenodd" class="j5jwh7nhs"/><path clip-rule="evenodd" class="k4hz-8mpo"/><path fill="url(#iSkcYJb)" clip-rule="evenodd" class="izn3gebed"/><path fill="url(#i7fW8bd)" clip-rule="evenodd" class="vr7wkveui"/><path fill="url(#iAIZjIb)" clip-rule="evenodd" class="vr7wkveui"/><g filter="url(#iNE5iPc)"><path class="jmu11so3o"/></g><g filter="url(#iFOktRm)"><path stroke="url(#iWCRWac)" class="otb15gs_b"/></g><g filter="url(#iWcf9lc)"><path class="bx715sbde"/></g><g filter="url(#ismxiue)"><path stroke="url(#ilqlYgc)" class="eb_2xn5cr"/></g><g filter="url(#igb8J1b)"><path class="e1c9g0nzk"/></g><g filter="url(#i2Aqj0d)"><path stroke="url(#i3vD1fc)" class="y18e3vr-p"/></g><g filter="url(#ibk2qbb)"><path class="no4stnzsa"/></g><g filter="url(#ijG915d)"><path stroke="url(#iCP1Psc)" class="y-cl0nb4x"/></g><g filter="url(#idiqtcb)"><circle fill="url(#ibNiWYb)" class="pbs08gb_s"/></g><g filter="url(#i92oUrb)"><circle fill="url(#ioc81sK)" class="yaziv6vbg"/></g><g filter="url(#ilQtspe)"><circle fill="url(#iphQ8zJ)" class="t1gv-kuzc"/><circle fill="url(#iAgYTEm)" class="t1gv-kuzc"/></g><g filter="url(#i735W7c)"><circle class="dowt8slro"/><circle fill="url(#is8RU5b)" class="n_mkc3sue"/><circle fill="url(#iLVPnob)" class="n_mkc3sue"/></g><g filter="url(#idqvQHb)"><path fill="url(#iITMOOe)" class="wnsy6lbqz"/><path fill="url(#iM5wazc)" class="wnsy6lbqz"/><path fill="url(#i4QPFjd)" class="wnsy6lbqz"/><path fill="url(#iCQiInc)" class="wnsy6lbqz"/><path fill="url(#igHk4kd)" class="wnsy6lbqz"/><path fill="url(#iopaSyb)" class="wnsy6lbqz"/></g><g filter="url(#iaXTkzb)"><path fill="url(#iGdQQEu)" class="ao8i07ojf"/></g><g filter="url(#iAoZtub)"><path class="rrcpaobql"/><path fill="url(#iXDMSud)" class="lki9gu6ms"/><path fill="url(#iQiZ1Nb)" class="lki9gu6ms"/><path fill="url(#i0aqPGP)" class="lki9gu6ms"/><path fill="url(#i52iLPd)" class="lki9gu6ms"/></g><g filter="url(#iE2nKRb)"><path class="aa1y203ns"/></g><g filter="url(#iRRMEfc)"><path class="pozyi7kum"/><path fill="url(#igWbRQd)" class="wxmf-_9lj"/><path fill="url(#i1x34ib)" class="wxmf-_9lj"/><path fill="url(#iky64cj)" class="wxmf-_9lj"/><path fill="url(#iDOkvne)" class="wxmf-_9lj"/></g><path stroke="url(#ibS0rOc)" class="rcjpccczl"/><g filter="url(#iv3BbHf)"><path class="zi4fq8b6p"/></g><g filter="url(#iE9aJte)"><path class="aw0tqqb3g"/></g><g filter="url(#iag3abc)"><path stroke="url(#iwJBlXb)" class="jz2_x8s6i"/></g><g filter="url(#irgldtc)"><path stroke="url(#ican9Xd)" class="p7g3vi7qa"/></g><g filter="url(#iA5uyCc)"><path stroke="url(#iTbsUHA)" class="kg83acbbc"/></g><path class="rvsip-wmc"/><g filter="url(#iU6JSzc)"><path class="u6hurh-xl"/></g><path class="p8u9_0brf"/><g filter="url(#iu6sR9d)"><path class="cy1ejrbxr"/></g><defs><radialGradient id="iqC7Yxk" cx="0" cy="0" r="1" gradientTransform="rotate(109.231 -5.356 13.09)scale(.71158 1.43628)" gradientUnits="userSpaceOnUse"><stop class="lsnfobzbz"/><stop offset="1" class="gf6fosb8y"/></radialGradient><radialGradient id="iMRjGCv" cx="0" cy="0" r="1" gradientTransform="rotate(174.454 13.31 11.987)scale(.83202 .3356)" gradientUnits="userSpaceOnUse"><stop class="cxkykm1df"/><stop offset="1" class="pgvvb0b4v"/></radialGradient><radialGradient id="iSuVWgb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.10352 0 0 -6.94644 26.355 25.193)" gradientUnits="userSpaceOnUse"><stop class="ihlvscyun"/><stop offset="1" class="jr2ezs63s"/></radialGradient><radialGradient id="iju7awd" cx="0" cy="0" r="1" gradientTransform="rotate(63.783 -6.873 31.622)scale(1.72425 1.82152)" gradientUnits="userSpaceOnUse"><stop class="w_0x8cbdi"/><stop offset="1" class="u_uylxu0j"/></radialGradient><radialGradient id="igrr9bc" cx="0" cy="0" r="1" gradientTransform="matrix(2.59375 .71875 -.52498 1.8945 9.876 28.537)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="kaew0_2pl"/><stop offset="1" class="a-cjnzu_f"/></radialGradient><radialGradient id="islyQFe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.40625 -.59375 1.5068 -6.10651 12.06 29.178)" gradientUnits="userSpaceOnUse"><stop offset=".753" class="z260igbpj"/><stop offset="1" class="qcf9xbgxm"/></radialGradient><radialGradient id="i0a1jac" cx="0" cy="0" r="1" gradientTransform="matrix(-.875 .21875 -.60896 -2.43587 21.294 25.87)" gradientUnits="userSpaceOnUse"><stop class="s_ql7obry"/><stop offset="1" class="zpmzd2b_c"/></radialGradient><radialGradient id="iBfNslb" cx="0" cy="0" r="1" gradientTransform="matrix(2.3125 -.7705 1.76305 5.29137 5.576 25.745)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="f7iqbccaz"/><stop offset="1" class="ygetoyo1j"/></radialGradient><radialGradient id="iQV6NXa" cx="0" cy="0" r="1" gradientTransform="matrix(.67187 .90625 -1.49816 1.1107 7.232 23.88)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="jvt0tewya"/><stop offset="1" class="lpv9r5l0o"/></radialGradient><radialGradient id="iKoHPAe" cx="0" cy="0" r="1" gradientTransform="matrix(4.5 0 0 1.90625 19.533 23.1)" gradientUnits="userSpaceOnUse"><stop class="w20zx1b6w"/><stop offset="1" class="njjkphbnd"/></radialGradient><radialGradient id="iGBdH9c" cx="0" cy="0" r="1" gradientTransform="matrix(3.875 0 0 1.91303 8.607 22.825)" gradientUnits="userSpaceOnUse"><stop class="bcwu99b2k"/><stop offset="1" class="ikuj7j5dl"/></radialGradient><radialGradient id="iSq3Ivb" cx="0" cy="0" r="1" gradientTransform="matrix(3.44922 -3.1199 1.05784 1.1695 7.157 23.5)" gradientUnits="userSpaceOnUse"><stop class="nh2d_e3ja"/><stop offset="1" class="s1mkhyyat"/></radialGradient><radialGradient id="iMdunfc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.61326 3.09376 -1.04179 -.54325 12.24 20.006)" gradientUnits="userSpaceOnUse"><stop class="k_38rrb4p"/><stop offset="1" class="jq958cc5h"/></radialGradient><radialGradient id="iHb6CBe" cx="0" cy="0" r="1" gradientTransform="rotate(-142.496 17.238 7.534)scale(1.69385 2.1643)" gradientUnits="userSpaceOnUse"><stop offset=".03" class="rx794hb8i"/><stop offset="1" class="jh2mh4wye"/></radialGradient><radialGradient id="iRa5bde" cx="0" cy="0" r="1" gradientTransform="matrix(4.85545 9.53121 -4.36739 2.22486 21.47 13.1)" gradientUnits="userSpaceOnUse"><stop class="j2u72qbdb"/><stop offset="1" class="r2rd1hnwy"/></radialGradient><radialGradient id="itc7hkf" cx="0" cy="0" r="1" gradientTransform="matrix(-.6875 4.03125 -8.3959 -1.43187 18.439 21.1)" gradientUnits="userSpaceOnUse"><stop offset=".126" class="ai9-2ku0o"/><stop offset=".925" class="gsv8efolz"/></radialGradient><radialGradient id="ijnUYlc" cx="0" cy="0" r="1" gradientTransform="rotate(-128.1 12.07 2.401)scale(3.49455 5.00001)" gradientUnits="userSpaceOnUse"><stop class="epy_aimha"/><stop offset="1" class="p6bgw4n9x"/></radialGradient><radialGradient id="ioMDxIe" cx="0" cy="0" r="1" gradientTransform="rotate(118.757 4.538 9.69)scale(3.02046 3.40652)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="tx5q7hblx"/><stop offset="1" class="iu30sbc6i"/></radialGradient><radialGradient id="i7EEymg" cx="0" cy="0" r="1" gradientTransform="matrix(.5 8.04173 -7.73502 .48093 17.689 13.287)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="afioo-bwu"/><stop offset="1" class="h1j0-fblz"/></radialGradient><radialGradient id="iADPLse" cx="0" cy="0" r="1" gradientTransform="rotate(141.869 7.576 10.755)scale(10.274 13.0752)" gradientUnits="userSpaceOnUse"><stop offset=".407" class="bakt0qbwy"/><stop offset="1" class="ltpsj2n6q"/></radialGradient><radialGradient id="iplOczb" cx="0" cy="0" r="1" gradientTransform="matrix(3.75 2.0625 -5.62896 10.23446 11.627 11.818)" gradientUnits="userSpaceOnUse"><stop offset=".074" class="rx6_xs15m"/><stop offset="1" class="keibw1bxy"/><stop offset="1" class="z321yabtz"/></radialGradient><radialGradient id="iz6ucle" cx="0" cy="0" r="1" gradientTransform="matrix(.11328 .6422 -3.96388 .69921 4.51 23.053)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="n6m3gkbee"/><stop offset="1" class="zk-sr297c"/></radialGradient><radialGradient id="i7Tgzib" cx="0" cy="0" r="1" gradientTransform="matrix(-.11328 .6422 -3.96388 -.69922 27.49 23.053)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="s86ss6vyf"/><stop offset=".878" class="m69lyob2q"/></radialGradient><radialGradient id="iRmR28b" cx="0" cy="0" r="1" gradientTransform="matrix(.12686 .83746 -4.47454 .67782 4.517 23.678)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="n6m3gkbee"/><stop offset="1" class="zk-sr297c"/></radialGradient><radialGradient id="iNMpu3c" cx="0" cy="0" r="1" gradientTransform="matrix(-.12686 .83746 -4.47454 -.67782 27.483 23.678)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="s86ss6vyf"/><stop offset=".878" class="m69lyob2q"/></radialGradient><radialGradient id="iLLwgto" cx="0" cy="0" r="1" gradientTransform="matrix(.11226 .95131 -3.99486 .47143 5 24.232)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="n6m3gkbee"/><stop offset="1" class="zk-sr297c"/></radialGradient><radialGradient id="i6K6vWb" cx="0" cy="0" r="1" gradientTransform="rotate(96.73 2.73 24.116)scale(.95791 4.02259)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="s86ss6vyf"/><stop offset=".878" class="m69lyob2q"/></radialGradient><radialGradient id="iSkcYJb" cx="0" cy="0" r="1" gradientTransform="matrix(.10014 1.0686 -3.5818 .33567 5.935 24.417)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="n6m3gkbee"/><stop offset="1" class="zk-sr297c"/></radialGradient><radialGradient id="iAIZjIb" cx="0" cy="0" r="1" gradientTransform="rotate(95.537 1.947 24.09)scale(.99219 3.43822)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="s86ss6vyf"/><stop offset=".878" class="m69lyob2q"/></radialGradient><radialGradient id="ibNiWYb" cx="0" cy="0" r="1" gradientTransform="matrix(1.11106 0 0 1.94437 11.951 7.663)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="crp6d4bqv"/><stop offset="1" class="lu78seb9e"/></radialGradient><radialGradient id="iAgYTEm" cx="0" cy="0" r="1" gradientTransform="matrix(.52341 -.38113 .435 .5974 19.267 7.496)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="wdqn7tq-u"/><stop offset="1" class="r3t82tbzk"/></radialGradient><radialGradient id="is8RU5b" cx="0" cy="0" r="1" gradientTransform="matrix(.51997 -.95637 .55977 .30434 19.005 8.183)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="n7c5lw_4k"/><stop offset=".916" class="bw8j_5egh"/></radialGradient><radialGradient id="iLVPnob" cx="0" cy="0" r="1" gradientTransform="matrix(.16416 .1625 -.20948 .21163 19.031 7.663)" gradientUnits="userSpaceOnUse"><stop class="fa9i5bbvu"/><stop offset="1" class="x8d9utbsu"/></radialGradient><radialGradient id="iM5wazc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.9738 -8.10911 0 16.032 6.445)" gradientUnits="userSpaceOnUse"><stop offset=".557" class="p7jmmxb2h"/><stop offset="1" class="uzkpn5btf"/></radialGradient><radialGradient id="igHk4kd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.82756 1.01853 0 17.5 6.858)" gradientUnits="userSpaceOnUse"><stop class="m459pab_j"/><stop offset="1" class="rcuz4uefu"/></radialGradient><radialGradient id="iopaSyb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.8806 1.09511 0 14.613 6.837)" gradientUnits="userSpaceOnUse"><stop class="hplqxft1w"/><stop offset="1" class="ay1rn8bxh"/></radialGradient><radialGradient id="iXDMSud" cx="0" cy="0" r="1" gradientTransform="matrix(.50513 -1.87194 .69417 .18732 18.765 5.064)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="iQiZ1Nb" cx="0" cy="0" r="1" gradientTransform="matrix(2.42163 .22285 -.11983 1.3021 17.725 3.95)" gradientUnits="userSpaceOnUse"><stop offset=".335" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="i0aqPGP" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.06314 -1.64651 0 16.014 2.218)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="i52iLPd" cx="0" cy="0" r="1" gradientTransform="matrix(1.94622 -1.42624 2.23445 3.04908 11.93 6.534)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="iDOkvne" cx="0" cy="0" r="1" gradientTransform="matrix(0 .12466 -.40052 0 16.221 8.68)" gradientUnits="userSpaceOnUse"><stop class="a7vfdrbiy"/><stop offset="1" class="x6mjr8bji"/></radialGradient><filter id="iiyr9mb" width="9.729" height="6.156" x="17.627" y="21.787" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.635294 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23999"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.521569 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23999" result="effect2_innerShadow_3987_23999"/></filter><filter id="i2EQIyb" width="17.213" height="8.245" x="5.751" y="21.537" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.658824 0 0 0 0 0.658824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23999"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.537255 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23999" result="effect2_innerShadow_3987_23999"/></filter><filter id="irNKyZm" width="7.621" height="12.797" x="19.836" y="11.795" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.54902 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23999"/></filter><filter id="izeKIwj" width="8.502" height="3.19" x="11.869" y="21.129" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.247059 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23999"/></filter><filter id="iTcVfAd" width="5.834" height="4.108" x="13.158" y="10.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.643137 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23999"/></filter><filter id="iMcbfRd" width="8.289" height="10.271" x="11.888" y="11.157" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.176471 0 0 0 0 0.556863 0 0 0 0 0.858824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23999"/></filter><filter id="iNE5iPc" width="1.684" height="1.255" x="5.351" y="24.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23999" stdDeviation=".075"/></filter><filter id="iFOktRm" width="1.684" height="1.255" x="24.965" y="24.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23999" stdDeviation=".075"/></filter><filter id="iWcf9lc" width="2.04" height="1.095" x="4.237" y="23.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23999" stdDeviation=".075"/></filter><filter id="ismxiue" width="2.04" height="1.095" x="25.723" y="23.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23999" stdDeviation=".075"/></filter><filter id="igb8J1b" width="2.223" height=".888" x="3.593" y="23.359" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23999" stdDeviation=".075"/></filter><filter id="i2Aqj0d" width="2.223" height=".888" x="26.184" y="23.359" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23999" stdDeviation=".075"/></filter><filter id="ibk2qbb" width="2.031" height=".566" x="3.653" y="22.937" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23999" stdDeviation=".075"/></filter><filter id="ijG915d" width="2.031" height=".566" x="26.317" y="22.937" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23999" stdDeviation=".075"/></filter><filter id="idiqtcb" width="2.314" height="2.114" x="11.951" y="6.606" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.694118 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23999"/></filter><filter id="i92oUrb" width="2.26" height="2.26" x="11.878" y="6.533" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23999" stdDeviation=".25"/></filter><filter id="ilQtspe" width="2.364" height="2.364" x="17.975" y="6.356" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.623529 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23999"/></filter><filter id="i735W7c" width="2.26" height="2.26" x="17.901" y="6.533" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23999" stdDeviation=".25"/></filter><filter id="idqvQHb" width="6.568" height="7.865" x="12.748" y="4.102" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.615686 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23999"/></filter><filter id="iaXTkzb" width="6.688" height="5.942" x="14.122" y="2.102" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23999" stdDeviation="1"/></filter><filter id="iAoZtub" width="7.978" height="5.243" x="12.024" y="2.068" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23999"/></filter><filter id="iE2nKRb" width="2.614" height="3.198" x="14.556" y="6.657" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23999" stdDeviation=".375"/></filter><filter id="iRRMEfc" width="1.488" height="1.998" x="15.27" y="7.154" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23999" stdDeviation=".075"/></filter><filter id="iv3BbHf" width="1.978" height="1.333" x="16.763" y="5.206" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23999"/></filter><filter id="iE9aJte" width="1.978" height="1.333" x="13.503" y="5.206" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23999"/></filter><filter id="iag3abc" width="1.621" height=".723" x="16.84" y="5.604" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23999" stdDeviation=".075"/></filter><filter id="irgldtc" width="1.67" height=".759" x="13.536" y="5.644" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23999" stdDeviation=".075"/></filter><filter id="iA5uyCc" width=".913" height="1.712" x="12.605" y="4.242" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23999" stdDeviation=".125"/></filter><filter id="iU6JSzc" width="1.628" height=".644" x="13.82" y="7.159" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23999" stdDeviation=".05"/></filter><filter id="iu6sR9d" width="1.628" height=".644" x="16.609" y="7.159" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23999" stdDeviation=".05"/></filter><linearGradient id="iIy7Ryc" x1="21.525" x2="21.525" y1="21.037" y2="22.193" gradientUnits="userSpaceOnUse"><stop class="h58pkjbsd"/><stop offset="1" class="pub21ekls"/></linearGradient><linearGradient id="iKVO9Zb" x1="18.658" x2="19.892" y1="24.321" y2="24.725" gradientUnits="userSpaceOnUse"><stop offset=".106" class="l2-xyub4i"/><stop offset="1" class="yi9dofbqv"/></linearGradient><linearGradient id="iuilNwe" x1="10.822" x2="10.822" y1="21.037" y2="22.193" gradientUnits="userSpaceOnUse"><stop class="w9r_6_bym"/><stop offset="1" class="v6lc275im"/></linearGradient><linearGradient id="iIrAzhe" x1="13.689" x2="12.455" y1="24.321" y2="24.725" gradientUnits="userSpaceOnUse"><stop offset=".106" class="d934ondjd"/><stop offset="1" class="vcwi5gbcl"/></linearGradient><linearGradient id="ifhliKd" x1="12.24" x2="10.033" y1="20.642" y2="20.452" gradientUnits="userSpaceOnUse"><stop offset=".184" class="sl8i30onx"/><stop offset="1" class="b39l_ob7e"/></linearGradient><linearGradient id="izKyXkd" x1="19.835" x2="22.042" y1="20.642" y2="20.452" gradientUnits="userSpaceOnUse"><stop offset=".184" class="bvjkc1dux"/><stop offset="1" class="im_-qcomr"/></linearGradient><linearGradient id="i7fW8bd" x1="26.505" x2="25.169" y1="25.253" y2="24.096" gradientUnits="userSpaceOnUse"><stop offset=".569" class="s_h949kal"/><stop offset="1" class="f-865jbco"/></linearGradient><linearGradient id="iWCRWac" x1="26.516" x2="25.268" y1="25.12" y2="24.992" gradientUnits="userSpaceOnUse"><stop class="e0us9sblp"/><stop offset="1" class="wp12h1b1k"/></linearGradient><linearGradient id="ilqlYgc" x1="27.656" x2="26.075" y1="24.799" y2="24.54" gradientUnits="userSpaceOnUse"><stop class="e0us9sblp"/><stop offset="1" class="wp12h1b1k"/></linearGradient><linearGradient id="i3vD1fc" x1="28.314" x2="26.645" y1="24.053" y2="24.149" gradientUnits="userSpaceOnUse"><stop class="e0us9sblp"/><stop offset="1" class="wp12h1b1k"/></linearGradient><linearGradient id="iCP1Psc" x1="28.24" x2="26.724" y1="23.279" y2="23.217" gradientUnits="userSpaceOnUse"><stop class="e0us9sblp"/><stop offset="1" class="wp12h1b1k"/></linearGradient><linearGradient id="ioc81sK" x1="13.008" x2="12.602" y1="7.84" y2="7.84" gradientUnits="userSpaceOnUse"><stop class="wachewblq"/><stop offset="1" class="px4pa2bzd"/></linearGradient><linearGradient id="iphQ8zJ" x1="19.72" x2="19.201" y1="6.972" y2="8.578" gradientUnits="userSpaceOnUse"><stop class="fuy988_rs"/><stop offset="1" class="h2u-65bda"/></linearGradient><linearGradient id="iITMOOe" x1="18.569" x2="13.734" y1="7.91" y2="8.63" gradientUnits="userSpaceOnUse"><stop class="z8y6fgvmn"/><stop offset="1" class="tqgh1edwg"/></linearGradient><linearGradient id="i4QPFjd" x1="12.441" x2="14.568" y1="8.877" y2="8.949" gradientUnits="userSpaceOnUse"><stop class="z3n_1mwef"/><stop offset="1" class="rvf3-0bfj"/></linearGradient><linearGradient id="iCQiInc" x1="12.598" x2="13.789" y1="9.617" y2="9.574" gradientUnits="userSpaceOnUse"><stop class="hmo3unbrx"/><stop offset="1" class="yyvs3obha"/></linearGradient><linearGradient id="iGdQQEu" x1="15.678" x2="20.834" y1="6.02" y2="4.174" gradientUnits="userSpaceOnUse"><stop class="sbbw_6vcc"/><stop offset="1" class="b7cutjkii"/></linearGradient><linearGradient id="igWbRQd" x1="15.467" x2="16.061" y1="8.327" y2="8.327" gradientUnits="userSpaceOnUse"><stop class="h7h6nwjtb"/><stop offset="1" class="btip4dbzo"/></linearGradient><linearGradient id="i1x34ib" x1="16.608" x2="15.959" y1="8.532" y2="8.522" gradientUnits="userSpaceOnUse"><stop class="ag4c77bht"/><stop offset="1" class="qb120pbsb"/></linearGradient><linearGradient id="iky64cj" x1="16.137" x2="16.137" y1="9.002" y2="8.639" gradientUnits="userSpaceOnUse"><stop class="rlzetx3ey"/><stop offset="1" class="zf2atv-8x"/></linearGradient><linearGradient id="ibS0rOc" x1="15.357" x2="15.633" y1="10.024" y2="9.589" gradientUnits="userSpaceOnUse"><stop class="wl-j51biu"/><stop offset=".663" class="i-vkeo5mo"/></linearGradient><linearGradient id="iwJBlXb" x1="17.896" x2="17.63" y1="5.911" y2="5.367" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="ican9Xd" x1="14.537" x2="13.784" y1="5.83" y2="5.514" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iTbsUHA" x1="13.062" x2="13.062" y1="4.555" y2="5.92" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-in-lotus-position-light" /></template>
<style>
.a-cjnzu_f {
  stop-color: var(--svg-color--c38390, #C38390);
}

.a7vfdrbiy {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
}

.aa1y203ns {
  fill: var(--svg-color--d89992, #D89992);
  d: path("m15.84 7.586l-.52 1.076c-.064.221.09.443.31.443h.466c.22 0 .374-.225.31-.443l-.316-1.076c-.068-.238-.18-.238-.25 0");
}

.abaaqi4hd {
  fill-rule: evenodd;
  d: path("M26.175 23.53a.4.4 0 0 0 .18.537a4.4 4.4 0 0 0 1.823.448a.4.4 0 0 0 0-.8a3.6 3.6 0 0 1-1.466-.364a.4.4 0 0 0-.537.18");
}

.afioo-bwu {
  stop-color: var(--svg-color--53adfc, #53ADFC);
}

.ag4c77bht {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
}

.ai9-2ku0o {
  stop-color: var(--svg-color--9f96a7, #9F96A7);
}

.ao8i07ojf {
  d: path("m18.524 4.102l-1.949.65a.663.663 0 0 0 .298 1.286l1.937-.26z");
}

.aw0tqqb3g {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m13.625 5.941l.002-.001l.003-.003l.007-.006a1 1 0 0 1 .098-.068a1.8 1.8 0 0 1 1.21-.234a.338.338 0 1 1-.104.668a1.12 1.12 0 0 0-.747.139l-.04.027a.338.338 0 0 1-.43-.522");
}

.ay1rn8bxh {
  stop-color: var(--svg-color--d0958d, #D0958D);
  stop-opacity: 0;
}

.b39l_ob7e {
  stop-color: var(--svg-color--df947d, #DF947D);
  stop-opacity: 0;
}

.b7cutjkii {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
  stop-opacity: 0;
}

.bakt0qbwy {
  stop-color: var(--svg-color--3482d0, #3482D0);
  stop-opacity: 0;
}

.bcwu99b2k {
  stop-color: var(--svg-color--f2b59c, #F2B59C);
}

.btip4dbzo {
  stop-color: var(--svg-color--dfa790, #DFA790);
  stop-opacity: 0;
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bvjkc1dux {
  stop-color: var(--svg-color--dc8368, #DC8368);
}

.bw8j_5egh {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
}

.bx715sbde {
  stroke: var(--svg-color--ffccb6, #FFCCB6);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M4.462 24.752c.41-.066 1.204-.313 1.59-.645");
}

.c56wt9b_p {
  d: path("M17.627 27.943h4.244c2.93 0 4.28-1.916 4.484-2.828l-2.531-2.328l-3.62 1.422l-2.578.11z");
}

.cr4sxsh_p {
  fill: var(--svg-color--fdcab1, #FDCAB1);
  d: path("M10.236 27.943c-2.93 0-4.281-1.916-4.485-2.828l2.532-2.328l3.453 1.445l8.18.086a1 1 0 0 1 .944.67c.407 1.171.96 2.765 1.032 3.002c.11.36.25 1.453-.875 1.766c-.78.216-1.523-.938-2.11-1.813z");
}

.crp6d4bqv {
  stop-color: var(--svg-color--cf9888, #CF9888);
}

.cxkykm1df {
  stop-color: var(--svg-color--efc3ad, #EFC3AD);
}

.cy1ejrbxr {
  stroke: var(--svg-color--2c2c2c, #2C2C2C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.76 7.31a.81.81 0 0 0 .671.343c.297 0 .591-.23.656-.344");
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.d934ondjd {
  stop-color: var(--svg-color--b17369, #B17369);
}

.dowt8slro {
  cx: 19.031px;
  cy: 7.663px;
  r: 0.63px;
  fill: var(--svg-color--e4af9a, #E4AF9A);
}

.e0us9sblp {
  stop-color: var(--svg-color--eec0af, #EEC0AF);
}

.e1c9g0nzk {
  stroke: var(--svg-color--ffccb6, #FFCCB6);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M3.818 24.022c.398 0 1.015-.055 1.773-.438");
}

.eb_2xn5cr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M27.538 24.752c-.41-.066-1.204-.313-1.59-.645");
}

.elqd_wbxf {
  fill: var(--svg-color--fcc0a6, #FCC0A6);
  fill-rule: evenodd;
  d: path("M5.697 23.053a.4.4 0 0 1-.266.5c-.536.163-1.099.145-1.367.136l-.124-.002a.4.4 0 0 1-.018-.8q.104-.002.23.003c.286.007.656.017 1.045-.103a.4.4 0 0 1 .5.266");
}

.epy_aimha {
  stop-color: var(--svg-color--ffceb8, #FFCEB8);
}

.eyfprhbml {
  d: path("M13.22 24.318h-1.429a1 1 0 0 0-.943.67c-.408 1.171-.96 2.765-1.032 3.002c-.11.36-.25 1.453.875 1.766c.757.21 1.48-.871 2.057-1.735l.052-.078h.42z");
}

.f-865jbco {
  stop-color: var(--svg-color--da9982, #DA9982);
}

.f7iqbccaz {
  stop-color: var(--svg-color--ffcab4, #FFCAB4);
}

.fa9i5bbvu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
}

.ft5dv1b6b {
  fill: none;
}

.fuy988_rs {
  stop-color: var(--svg-color--fbd3bd, #FBD3BD);
}

.gf6fosb8y {
  stop-color: var(--svg-color--ffc2a4, #FFC2A4);
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gsv8efolz {
  stop-color: var(--svg-color--6e6773, #6E6773);
}

.h1j0-fblz {
  stop-color: var(--svg-color--3181d9, #3181D9);
}

.h2u-65bda {
  stop-color: var(--svg-color--f0b8a4, #F0B8A4);
}

.h58pkjbsd {
  stop-color: var(--svg-color--b66c55, #B66C55);
}

.h5sl0ws-f {
  d: path("m13.447 24.318l-1.578-2.99h8.301l-1.551 2.99z");
}

.h7h6nwjtb {
  stop-color: var(--svg-color--dfa790, #DFA790);
}

.hd_puhbmm {
  fill: var(--svg-color--fcc0a6, #FCC0A6);
  fill-rule: evenodd;
  d: path("M5.825 23.53a.4.4 0 0 1-.18.537a4.4 4.4 0 0 1-1.823.448a.4.4 0 0 1 0-.8a3.6 3.6 0 0 0 1.466-.364a.4.4 0 0 1 .537.18");
}

.hmo3unbrx {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
}

.hplqxft1w {
  stop-color: var(--svg-color--d0958d, #D0958D);
}

.i-vkeo5mo {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
  stop-opacity: 0;
}

.icncv2mqv {
  fill-rule: evenodd;
  d: path("M6.76 22.963a.5.5 0 0 1-.5.5c-.632 0-1.257-.193-1.501-.268l-.04-.012a.5.5 0 0 1 .293-.957l.029.01c.246.075.743.227 1.219.227a.5.5 0 0 1 .5.5");
}

.ihlvscyun {
  stop-color: var(--svg-color--e2b3a5, #E2B3A5);
}

.ikftlibzf {
  fill-rule: evenodd;
  d: path("M6.099 23.953a.4.4 0 0 1-.044.564c-.34.29-.628.456-.903.549c-.254.086-.478.101-.655.114l-.037.002a.4.4 0 1 1-.057-.798l.018-.001c.19-.014.32-.023.475-.075s.356-.158.639-.4a.4.4 0 0 1 .564.045");
}

.ikuj7j5dl {
  stop-color: var(--svg-color--ce927d, #CE927D);
}

.im_-qcomr {
  stop-color: var(--svg-color--dc8368, #DC8368);
  stop-opacity: 0;
}

.io78i4bem {
  d: path("M13.83 21.329H7.814v2.692c2.531.352 6.016.297 6.016.297z");
}

.iu30sbc6i {
  stop-color: var(--svg-color--e6ab90, #E6AB90);
  stop-opacity: 0;
}

.ixa22uwgh {
  fill-rule: evenodd;
  d: path("M5.697 23.053a.4.4 0 0 1-.266.5c-.536.163-1.099.145-1.367.136l-.124-.002a.4.4 0 0 1-.018-.8q.104-.002.23.003c.286.007.656.017 1.045-.103a.4.4 0 0 1 .5.266");
}

.izn3gebed {
  fill-rule: evenodd;
  d: path("M6.818 24.178c.14.17.272.303.101.443a5.8 5.8 0 0 1-1.193.783l-.072.037a.4.4 0 0 1-.367-.711l.074-.038a5 5 0 0 0 1.051-.69c.17-.14.266.005.406.176");
}

.j2u72qbdb {
  stop-color: var(--svg-color--ffd3ba, #FFD3BA);
}

.j393hh9jx {
  d: path("M18.517 21.329h6.016v2.692c-2.532.352-6.016.297-6.016.297z");
}

.j5jwh7nhs {
  fill-rule: evenodd;
  d: path("M25.902 23.953a.4.4 0 0 0 .043.564c.34.29.628.456.903.549c.254.086.478.101.655.114l.037.002a.4.4 0 1 0 .057-.798l-.018-.001a1.8 1.8 0 0 1-.474-.075c-.156-.052-.357-.158-.64-.4a.4.4 0 0 0-.564.045");
}

.jfusrx6ed {
  fill-rule: evenodd;
  d: path("M25.316 22.963a.5.5 0 0 0 .5.5c.632 0 1.257-.193 1.5-.268l.04-.012a.5.5 0 0 0-.292-.957l-.03.01c-.246.075-.743.227-1.218.227a.5.5 0 0 0-.5.5");
}

.jh2mh4wye {
  stop-color: var(--svg-color--f1c0a6, #F1C0A6);
  stop-opacity: 0;
}

.jmu11so3o {
  stroke: var(--svg-color--ffccb6, #FFCCB6);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M5.576 25.06c.25-.145.847-.51 1.234-.804");
}

.jq958cc5h {
  stop-color: var(--svg-color--d2826a, #D2826A);
  stop-opacity: 0;
}

.jr2ezs63s {
  stop-color: var(--svg-color--f1b9a0, #F1B9A0);
}

.jvt0tewya {
  stop-color: var(--svg-color--f3a98c, #F3A98C);
}

.jz2_x8s6i {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M17.065 5.85c.273-.048.804-.034 1.171.252");
}

.k_38rrb4p {
  stop-color: var(--svg-color--ac5d47, #AC5D47);
}

.k4hz-8mpo {
  fill: var(--svg-color--fcc0a6, #FCC0A6);
  fill-rule: evenodd;
  d: path("M6.818 24.178c.14.17.272.303.101.443a5.8 5.8 0 0 1-1.193.783l-.072.037a.4.4 0 0 1-.367-.711l.074-.038a5 5 0 0 0 1.051-.69c.17-.14.266.005.406.176");
}

.kaew0_2pl {
  stop-color: var(--svg-color--dc9fa1, #DC9FA1);
}

.keibw1bxy {
  stop-color: var(--svg-color--398dce, #398DCE);
  stop-opacity: 0;
}

.kg83acbbc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M13.144 4.617v.568c-.005.095-.045.305-.164.394");
}

.l2-xyub4i {
  stop-color: var(--svg-color--af7875, #AF7875);
}

.lf2bt8iil {
  fill: var(--svg-color--e2af9a, #E2AF9A);
  fill-rule: evenodd;
  d: path("M25.902 23.953a.4.4 0 0 0 .043.564c.34.29.628.456.903.549c.254.086.478.101.655.114l.037.002a.4.4 0 1 0 .057-.798l-.018-.001a1.8 1.8 0 0 1-.474-.075c-.156-.052-.357-.158-.64-.4a.4.4 0 0 0-.564.045");
}

.lgo3_ibwu {
  d: path("M18.892 11.159v.722a2.5 2.5 0 0 1-2.5 2.5h-.734a2.5 2.5 0 0 1-2.5-2.5v-.724c.763-.417 1.77-.784 2.914-.784c1.05 0 2.055.375 2.82.786");
}

.lki9gu6ms {
  d: path("m19.065 3.562l.271.135c.476.237.748.777.646 1.35l-.374 1.926c-.033.198-.165.332-.362.337h-.011s.033-.574.067-.911c.028-.275-.02-.358-.271-.608a.8.8 0 0 1-.238-.54v-.54a.364.364 0 0 0-.272-.339c-.407-.1-1.256-.27-2.479-.27s-2.072.17-2.479.27a.33.33 0 0 0-.272.338v.54a.67.67 0 0 1-.237.54l-.102.102c-.136.101-.204.304-.204.473c.034.371.068.911.068.911h-.031a.4.4 0 0 1-.377-.337l-.373-1.925c-.068-.54.204-1.08.679-1.317l.272-.135c.17-.101.34-.236.51-.371l.61-.642a1.24 1.24 0 0 1 1.393-.203c.34.102.713.102 1.053 0a1.53 1.53 0 0 1 1.494.338l.51.507c.135.168.305.27.509.371");
}

.lpv9r5l0o {
  stop-color: var(--svg-color--f3a98c, #F3A98C);
  stop-opacity: 0;
}

.lrg695bhi {
  fill-rule: evenodd;
  d: path("M26.304 23.053a.4.4 0 0 0 .265.5c.536.163 1.099.145 1.367.136l.124-.002a.4.4 0 0 0 .018-.8a5 5 0 0 0-.23.003c-.286.007-.656.017-1.045-.103a.4.4 0 0 0-.5.266");
}

.lsnfobzbz {
  stop-color: var(--svg-color--fdc3a2, #FDC3A2);
}

.ltpsj2n6q {
  stop-color: var(--svg-color--3c515d, #3C515D);
}

.lu78seb9e {
  stop-color: var(--svg-color--be8c77, #BE8C77);
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m459pab_j {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
}

.m69lyob2q {
  stop-color: var(--svg-color--d69f8f, #D69F8F);
}

.mblkjgfgo {
  fill: var(--svg-color--f0b99e, #F0B99E);
  d: path("M22.32 16.086c-.22-1.858-1.605-3.58-2.152-4.041l-.332.315v7.276c.25.652.719 1.33 1.125 1.652c0 0 .867.814 4.172 3.304c1.325-.185 2.094-1.094 2.073-1.703c-.874-.5-3.37-2.969-4.01-3.606c-.538-.535-.641-1.215-.876-3.197");
}

.n_mkc3sue {
  cx: 19.031px;
  cy: 7.663px;
  r: 0.63px;
}

.n32upfbdg {
  d: path("M18.892 11.159v.722a2.5 2.5 0 0 1-2.5 2.5h-.734a2.5 2.5 0 0 1-2.5-2.5v-.724a6.5 6.5 0 0 0-1.27.896v9.276h8.289v-9.276c-.198-.2-.662-.559-1.285-.894");
}

.n6m3gkbee {
  stop-color: var(--svg-color--e0a6a7, #E0A6A7);
  stop-opacity: 0;
}

.n7c5lw_4k {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
  stop-opacity: 0;
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.nh2d_e3ja {
  stop-color: var(--svg-color--f3bea3, #F3BEA3);
}

.njjkphbnd {
  stop-color: var(--svg-color--ce8c76, #CE8C76);
}

.no4stnzsa {
  stroke: var(--svg-color--ffccb6, #FFCCB6);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M3.878 23.271c.398 0 .893.047 1.58-.109");
}

.npcds_a-e {
  fill: var(--svg-color--e2af9a, #E2AF9A);
  fill-rule: evenodd;
  d: path("M26.175 23.53a.4.4 0 0 0 .18.537a4.4 4.4 0 0 0 1.823.448a.4.4 0 0 0 0-.8a3.6 3.6 0 0 1-1.466-.364a.4.4 0 0 0-.537.18");
}

.otb15gs_b {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M26.424 25.06c-.25-.145-.847-.51-1.234-.804");
}

.p6bgw4n9x {
  stop-color: var(--svg-color--f5bca5, #F5BCA5);
}

.p7g3vi7qa {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.76 6.178c.208-.183.66-.376 1.22-.286");
}

.p7jmmxb2h {
  stop-color: var(--svg-color--d7a09d, #D7A09D);
  stop-opacity: 0;
}

.p8u9_0brf {
  stroke: var(--svg-color--4b3833, #4B3833);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M16.76 7.31a.81.81 0 0 0 .671.343c.297 0 .591-.23.656-.344");
}

.pbs08gb_s {
  cx: 13.008px;
  cy: 7.663px;
  r: 1.057px;
}

.pgvvb0b4v {
  stop-color: var(--svg-color--eabfa6, #EABFA6);
}

.pozyi7kum {
  fill: var(--svg-color--fbc4b1, #FBC4B1);
  d: path("m15.772 7.483l-.336 1.076a.34.34 0 0 0 .33.443h.497a.342.342 0 0 0 .33-.443l-.337-1.076c-.072-.239-.408-.239-.484 0");
}

.pub21ekls {
  stop-color: var(--svg-color--cd846b, #CD846B);
  stop-opacity: 0;
}

.px4pa2bzd {
  stop-color: var(--svg-color--be8474, #BE8474);
}

.q-rxwlb3c {
  fill: var(--svg-color--fabc9f, #FABC9F);
  d: path("M9.755 16.086c.22-1.858 1.605-3.58 2.152-4.041l.332.315v7.276c-.25.652-.719 1.33-1.125 1.652c0 0-.867.814-4.171 3.304c-1.325-.185-2.095-1.094-2.074-1.703c.875-.5 3.37-2.969 4.011-3.606c.537-.535.64-1.215.875-3.197");
}

.qb120pbsb {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
  stop-opacity: 0;
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qcf9xbgxm {
  stop-color: var(--svg-color--f9bcae, #F9BCAE);
}

.r2rd1hnwy {
  stop-color: var(--svg-color--ffd3ba, #FFD3BA);
  stop-opacity: 0;
}

.r3t82tbzk {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
  stop-opacity: 0;
}

.rcjpccczl {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M15.16 9.393c.246.128.54.202.854.202c.316 0 .607-.074.854-.202a.15.15 0 0 1 .174.028a.14.14 0 0 1 .016.176m-1.898-.204l1.856.176m-1.856-.176a.15.15 0 0 0-.175.03a.14.14 0 0 0-.015.174m.19-.204l-.149.176m2.047.028l-.042-.028m.042.028l-.042-.028m.042.028a1.25 1.25 0 0 1-1.044.558c-.438 0-.823-.223-1.044-.558m2.046-.028a1.2 1.2 0 0 1-1.002.536a1.2 1.2 0 0 1-1.003-.536m-.041.028l.041-.028m-.041.028l.041-.028");
}

.rcuz4uefu {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
  stop-opacity: 0;
}

.rgyldmb2f {
  fill: var(--svg-color--fcc0a6, #FCC0A6);
  fill-rule: evenodd;
  d: path("M6.099 23.953a.4.4 0 0 1-.044.564c-.34.29-.628.456-.903.549c-.254.086-.478.101-.655.114l-.037.002a.4.4 0 1 1-.057-.798l.018-.001c.19-.014.32-.023.475-.075s.356-.158.639-.4a.4.4 0 0 1 .564.045");
}

.rlzetx3ey {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
}

.rond61bua {
  d: path("M9.755 16.086c.22-1.858 1.605-3.58 2.152-4.041l.332.315v7.276c-.25.652-.719 1.33-1.125 1.652c0 0-.867.814-4.171 3.304c-1.325-.185-2.095-1.094-2.074-1.703c.875-.5 3.37-2.969 4.011-3.606c.537-.535.64-1.215.875-3.197");
}

.rrcpaobql {
  fill: var(--svg-color--242324, #242324);
  d: path("m19.065 3.562l.271.135c.476.237.748.777.646 1.35l-.374 1.926c-.033.198-.165.332-.362.337h-.011s.033-.574.067-.911c.028-.275-.02-.358-.271-.608a.8.8 0 0 1-.238-.54v-.54a.364.364 0 0 0-.272-.339c-.407-.1-1.256-.27-2.479-.27s-2.072.17-2.479.27a.33.33 0 0 0-.272.338v.54a.67.67 0 0 1-.237.54l-.102.102c-.136.101-.204.304-.204.473c.034.371.068.911.068.911h-.031a.4.4 0 0 1-.377-.337l-.373-1.925c-.068-.54.204-1.08.679-1.317l.272-.135c.17-.101.34-.236.51-.371l.61-.642a1.24 1.24 0 0 1 1.393-.203c.34.102.713.102 1.053 0a1.53 1.53 0 0 1 1.494.338l.51.507c.135.168.305.27.509.371");
}

.rsucbzb8b {
  d: path("M22.32 16.086c-.22-1.858-1.605-3.58-2.152-4.041l-.332.315v7.276c.25.652.719 1.33 1.125 1.652c0 0 .867.814 4.172 3.304c1.325-.185 2.094-1.094 2.073-1.703c-.874-.5-3.37-2.969-4.01-3.606c-.538-.535-.641-1.215-.876-3.197");
}

.rvf3-0bfj {
  stop-color: var(--svg-color--dead9d, #DEAD9D);
  stop-opacity: 0;
}

.rvsip-wmc {
  stroke: var(--svg-color--4b3833, #4B3833);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M13.97 7.31a.81.81 0 0 0 .672.343c.297 0 .591-.23.656-.344");
}

.rx6_xs15m {
  stop-color: var(--svg-color--3d84ae, #3D84AE);
}

.rx794hb8i {
  stop-color: var(--svg-color--f0c1ae, #F0C1AE);
}

.s_h949kal {
  stop-color: var(--svg-color--e4b6a0, #E4B6A0);
}

.s_ql7obry {
  stop-color: var(--svg-color--ffceba, #FFCEBA);
}

.s1mkhyyat {
  stop-color: var(--svg-color--efba94, #EFBA94);
  stop-opacity: 0;
}

.s76wkwjkc {
  fill-rule: evenodd;
  d: path("M5.825 23.53a.4.4 0 0 1-.18.537a4.4 4.4 0 0 1-1.823.448a.4.4 0 0 1 0-.8a3.6 3.6 0 0 0 1.466-.364a.4.4 0 0 1 .537.18");
}

.s86ss6vyf {
  stop-color: var(--svg-color--d69f8f, #D69F8F);
  stop-opacity: 0;
}

.sbbw_6vcc {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
}

.sl8i30onx {
  stop-color: var(--svg-color--df947d, #DF947D);
}

.t1gv-kuzc {
  cx: 19.032px;
  cy: 7.663px;
  r: 1.057px;
}

.tdqm2_hbg {
  d: path("M10.236 27.943c-2.93 0-4.281-1.916-4.485-2.828l2.532-2.328l3.453 1.445l8.18.086a1 1 0 0 1 .944.67c.407 1.171.96 2.765 1.032 3.002c.11.36.25 1.453-.875 1.766c-.78.216-1.523-.938-2.11-1.813z");
}

.tqgh1edwg {
  stop-color: var(--svg-color--eaab97, #EAAB97);
}

.tx5q7hblx {
  stop-color: var(--svg-color--de9b7b, #DE9B7B);
}

.u_uylxu0j {
  stop-color: var(--svg-color--d08c76, #D08C76);
  stop-opacity: 0;
}

.u6hurh-xl {
  stroke: var(--svg-color--2c2c2c, #2C2C2C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.97 7.31a.81.81 0 0 0 .672.343c.297 0 .591-.23.656-.344");
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.uzkpn5btf {
  stop-color: var(--svg-color--b07f87, #B07F87);
}

.v6lc275im {
  stop-color: var(--svg-color--c5856f, #C5856F);
  stop-opacity: 0;
}

.vcwi5gbcl {
  stop-color: var(--svg-color--c98e79, #C98E79);
  stop-opacity: 0;
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.vr7wkveui {
  fill-rule: evenodd;
  d: path("M25.276 24.178c-.14.171-.273.304-.102.444c.566.464.85.628 1.109.76l.072.037a.4.4 0 1 0 .367-.712l-.075-.037c-.242-.123-.38-.123-.879-.532c-.17-.14-.352-.13-.492.04");
}

.w_0x8cbdi {
  stop-color: var(--svg-color--d08c76, #D08C76);
}

.w20zx1b6w {
  stop-color: var(--svg-color--ce9b8a, #CE9B8A);
}

.w9r_6_bym {
  stop-color: var(--svg-color--b3715e, #B3715E);
}

.wachewblq {
  stop-color: var(--svg-color--ba7c6b, #BA7C6B);
}

.wdqn7tq-u {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wl-j51biu {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
}

.wnsy6lbqz {
  d: path("M12.748 6.365c0-.17.068-.372.204-.473l.102-.101a.67.67 0 0 0 .237-.54v-.54a.33.33 0 0 1 .272-.339c.408-.1 1.257-.27 2.48-.27c1.222 0 2.07.17 2.478.27a.36.36 0 0 1 .272.338v.54a.8.8 0 0 0 .238.54c.318.223.298.346.271.609c-.033.337-.067.911-.067.911h.011l-.168 2.506c-.102 1.12-.983 1.902-2.033 1.902h-2.033c-1.084 0-1.93-.781-2.032-1.902c-.088-1.15-.127-2.303-.232-3.451");
}

.wp12h1b1k {
  stop-color: var(--svg-color--eec0af, #EEC0AF);
  stop-opacity: 0;
}

.wxmf-_9lj {
  d: path("m15.772 7.483l-.336 1.076a.34.34 0 0 0 .33.443h.497a.342.342 0 0 0 .33-.443l-.337-1.076c-.072-.239-.408-.239-.484 0");
}

.wyplhh6vs {
  fill: var(--svg-color--e2af9a, #E2AF9A);
  fill-rule: evenodd;
  d: path("M26.304 23.053a.4.4 0 0 0 .265.5c.536.163 1.099.145 1.367.136l.124-.002a.4.4 0 0 0 .018-.8a5 5 0 0 0-.23.003c-.286.007-.656.017-1.045-.103a.4.4 0 0 0-.5.266");
}

.x6mjr8bji {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
  stop-opacity: 0;
}

.x8d9utbsu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
  stop-opacity: 0;
}

.y-cl0nb4x {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M28.122 23.271c-.398 0-.893.047-1.58-.109");
}

.y18e3vr-p {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M28.182 24.022a3.8 3.8 0 0 1-1.773-.438");
}

.yaziv6vbg {
  cx: 13.008px;
  cy: 7.663px;
  r: 0.63px;
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.ygetoyo1j {
  stop-color: var(--svg-color--ffcab4, #FFCAB4);
  stop-opacity: 0;
}

.yi9dofbqv {
  stop-color: var(--svg-color--c79383, #C79383);
  stop-opacity: 0;
}

.yyvs3obha {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
  stop-opacity: 0;
}

.z260igbpj {
  stop-color: var(--svg-color--f9bcae, #F9BCAE);
  stop-opacity: 0;
}

.z321yabtz {
  stop-color: var(--svg-color--d3612e, #D3612E);
  stop-opacity: 0;
}

.z3n_1mwef {
  stop-color: var(--svg-color--a58787, #A58787);
}

.z8y6fgvmn {
  stop-color: var(--svg-color--ffdabf, #FFDABF);
}

.zf2atv-8x {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
  stop-opacity: 0;
}

.zi4fq8b6p {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M18.37 5.941h-.002V5.94l-.004-.003l-.007-.006a1 1 0 0 0-.098-.068a1.6 1.6 0 0 0-.266-.133a1.8 1.8 0 0 0-.945-.1a.338.338 0 0 0 .105.667a1.12 1.12 0 0 1 .747.139l.04.027a.338.338 0 0 0 .43-.522");
}

.zk-sr297c {
  stop-color: var(--svg-color--e0a6a7, #E0A6A7);
}

.zpmzd2b_c {
  stop-color: var(--svg-color--ffceba, #FFCEBA);
  stop-opacity: 0;
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

</style>
