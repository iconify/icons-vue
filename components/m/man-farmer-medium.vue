<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iMdPbqe)" class="yp08p_blq"/><path fill="url(#imtXFrd)" class="oum2dd_7s"/><path fill="url(#iCV2uie)" class="oum2dd_7s"/><g filter="url(#ihGYetd)"><path fill="url(#iUWdLjI)" class="x_5xqwbuj"/><path fill="url(#imY84Fb)" class="x_5xqwbuj"/></g><path class="debh25b6n"/><path fill="url(#i61gKKc)" class="qful1wpim"/><path fill="url(#iWeyW8j)" class="v6j_arbpy"/><path fill="url(#iqHyYxe)" class="v6j_arbpy"/><path fill="url(#iDWfNsd)" class="gkc627t-z"/><path fill="url(#ihy4w0b)" class="gkc627t-z"/><g filter="url(#iLxxvPc)"><path fill="url(#inEudeb)" class="kqztxxbtu"/><path fill="url(#i2TpDkb)" class="kqztxxbtu"/><path fill="url(#iZQafJR)" class="kqztxxbtu"/></g><path fill="url(#iqgS9Gb)" class="kqztxxbtu"/><path fill="url(#iTaeZfe)" class="kqztxxbtu"/><path fill="url(#iO92pSd)" class="prorwkb4s"/><path fill="url(#iYd6CtP)" class="am3kgkbwr"/><path fill="url(#iQwef4c)" class="am3kgkbwr"/><g filter="url(#iHJvkDe)"><path class="mg0a58tbq"/><path fill="url(#iQo8Uwd)" class="fv0x46bue"/></g><g filter="url(#iD1BYtd)"><path fill="url(#iRyuAbb)" class="yqignq8nw"/><path fill="url(#iK5DgNB)" class="yqignq8nw"/></g><path fill="url(#iej3Hic)" class="n_qe0-a_d"/><path fill="url(#iq1N7Ot)" class="n_qe0-a_d"/><path fill="url(#iFTL3zb)" class="n_qe0-a_d"/><path fill="url(#iRJueVc)" class="n_qe0-a_d"/><g filter="url(#i3VBaZc)"><path fill="url(#iYgugTc)" class="maklkcq7c"/><path fill="url(#il8edcd)" class="maklkcq7c"/></g><path fill="url(#iuYjH9c)" class="bbdczxw8c"/><path fill="url(#ixNDlpe)" class="bbdczxw8c"/><path fill="url(#iVo46Jc)" class="yh0xfd23l"/><path fill="url(#iYmZ1ic)" class="pbfq705wj"/><path fill="url(#i1BS04c)" class="pbfq705wj"/><path fill="url(#i4fM6Dc)" class="pbfq705wj"/><path fill="url(#iYnOASd)" class="pbfq705wj"/><path fill="url(#iFniQ8d)" class="pbfq705wj"/><g filter="url(#iHQ8X7b)"><path class="j403gj70r"/></g><g filter="url(#iIts4ib)"><path fill="url(#izfIk8d)" class="st6ihdcnf"/></g><g filter="url(#iuHKvpu)"><path fill="url(#itpuwKt)" class="zfr_dbbtg"/></g><path fill="url(#i3RPtoc)" class="zfr_dbbtg"/><path fill="url(#iIJdcfd)" class="zfr_dbbtg"/><path fill="url(#i8SV72b)" class="zfr_dbbtg"/><path fill="url(#iaqkdjR)" class="zfr_dbbtg"/><path fill="url(#iY289Xr)" class="zfr_dbbtg"/><g filter="url(#iTyLfib)"><path class="zhri926iw"/></g><g filter="url(#ikrw9qe)"><path class="sa19i-y8k"/><path fill="url(#iEB8C5d)" class="fv53q1bnm"/><path fill="url(#iDskhfd)" class="fv53q1bnm"/><path fill="url(#ibbZY7c)" class="fv53q1bnm"/><path fill="url(#iyCnoVc)" class="fv53q1bnm"/><path fill="url(#iuHmmfe)" class="fv53q1bnm"/></g><g filter="url(#iM1yDys)"><path stroke="url(#iMIC8WH)" class="b3-e1tbeq"/></g><path class="gjeztxb4l"/><path fill="url(#ic9Bx5c)" class="s1yo5-bze"/><path fill="url(#itJhove)" class="s1yo5-bze"/><path fill="url(#i85zXbb)" class="kd-olwbcr"/><path fill="url(#iAJs0Dd)" class="kd-olwbcr"/><path fill="url(#iGV0Lcb)" class="teqjn2bac"/><path fill="url(#iPcCcgb)" class="teqjn2bac"/><path fill="url(#is80UUL)" class="teqjn2bac"/><g filter="url(#izrSXlb)"><path class="y_klt4bgy"/></g><path class="pzgz70rhv"/><path fill="url(#iPALSUc)" class="viz48byvw"/><path class="v4fyh9bof"/><g filter="url(#iGJOOra)"><path class="im6pbbc8v"/><path fill="url(#iDwwMDb)" class="c392ft7tk"/></g><g filter="url(#if6kVec)"><path fill="url(#iQzcKEb)" class="m8_f8sbvv"/></g><path class="iplo5nbkc"/><path fill="url(#i9EjNCc)" class="m5xv22viy"/><path class="izuk-bqvv"/><g filter="url(#i2hgwHm)"><path fill="url(#iSU8dab)" class="ajcqqcwyx"/></g><g filter="url(#iXmd21d)"><ellipse transform="rotate(-27.914 13.51 9.908)" class="cf0lpn8oo"/><ellipse fill="url(#iMexY0K)" transform="rotate(-27.914 13.51 9.908)" class="fo00f_-hd"/></g><g filter="url(#idUh8Uc)"><path fill="url(#iAVdEVc)" class="yzhaj994c"/><path fill="url(#iFkIlwc)" class="yzhaj994c"/><path fill="url(#iGGgL5c)" class="yzhaj994c"/><path fill="url(#iQjTiZc)" class="yzhaj994c"/><path fill="url(#iWgUYAc)" class="yzhaj994c"/></g><g filter="url(#i7NmnUd)"><path stroke="url(#iviITCc)" class="f2_cz0v9z"/></g><g filter="url(#iV0QQjK)"><path stroke="url(#iMvnCwK)" class="b0115xbxz"/></g><g filter="url(#i7JLUie)"><path stroke="url(#i4PYJId)" class="jnvzjw9uu"/></g><g filter="url(#iYbaYvd)"><path clip-rule="evenodd" class="thw19dvgl"/></g><g filter="url(#igC2hyi)"><path clip-rule="evenodd" class="tc5_6ybav"/></g><g filter="url(#i2otK3b)"><path class="wn_y-ob0v"/></g><g filter="url(#itRRAxe)"><path class="evdhv9byz"/></g><defs><radialGradient id="iMdPbqe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.28126 -2.7131 2.52682 -3.98732 19.818 3.995)" gradientUnits="userSpaceOnUse"><stop class="lgo9yub8v"/><stop offset="1" class="ltcbfxk7p"/></radialGradient><radialGradient id="imtXFrd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.15625 8.40625 0 19.693 5.157)" gradientUnits="userSpaceOnUse"><stop class="ya4lejb1r"/><stop offset="1" class="r9exlwbyv"/></radialGradient><radialGradient id="imY84Fb" cx="0" cy="0" r="1" gradientTransform="rotate(-115.388 9.622 3.934)scale(4.08169 6.42739)" gradientUnits="userSpaceOnUse"><stop class="yc_s6bd2r"/><stop offset="1" class="e2_jykbzy"/></radialGradient><radialGradient id="i61gKKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.16424 -8.99366 0 15.93 16.32)" gradientUnits="userSpaceOnUse"><stop offset=".53" class="oolzzy49q"/><stop offset="1" class="kc6n1tb_x"/></radialGradient><radialGradient id="iqHyYxe" cx="0" cy="0" r="1" gradientTransform="matrix(2.6875 .4375 -2.13811 13.1341 3.787 25.282)" gradientUnits="userSpaceOnUse"><stop class="d6r03hc-n"/><stop offset="1" class="h29l8x_8c"/></radialGradient><radialGradient id="ihy4w0b" cx="0" cy="0" r="1" gradientTransform="matrix(.79488 -.01787 .1758 7.81887 22.96 24.745)" gradientUnits="userSpaceOnUse"><stop offset=".249" class="dz1f1dx9q"/><stop offset="1" class="a2gn4iuzk"/></radialGradient><radialGradient id="inEudeb" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.49005 -3.73669 0 16 16.189)" gradientUnits="userSpaceOnUse"><stop offset=".232" class="w6969eyte"/><stop offset="1" class="nb487cbvy"/></radialGradient><radialGradient id="iZQafJR" cx="0" cy="0" r="1" gradientTransform="matrix(-2.27543 1.55452 -.96733 -1.41593 15.145 19.587)" gradientUnits="userSpaceOnUse"><stop class="zif_-obqz"/><stop offset="1" class="j3eudux9e"/></radialGradient><radialGradient id="iTaeZfe" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.28924 -4.48731 0 15.393 16.005)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="rs3k7gc8p"/><stop offset=".987" class="zm4f_vbug"/></radialGradient><radialGradient id="iO92pSd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.58005 5.35185 0 15.92 19.687)" gradientUnits="userSpaceOnUse"><stop offset=".027" class="h7qlxhb-a"/><stop offset=".737" class="wly33_qqy"/></radialGradient><radialGradient id="iYd6CtP" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.46875 -2.55512 0 15.93 16.688)" gradientUnits="userSpaceOnUse"><stop class="du0zoacsy"/><stop offset="1" class="u0ewzac_g"/></radialGradient><radialGradient id="iQwef4c" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.35347 -2.33637 0 15.93 15.365)" gradientUnits="userSpaceOnUse"><stop offset=".734" class="vo7-53hhd"/><stop offset="1" class="n_23u1b6b"/></radialGradient><radialGradient id="iQo8Uwd" cx="0" cy="0" r="1" gradientTransform="rotate(-114.07 9.305 2.636)scale(1.73157)" gradientUnits="userSpaceOnUse"><stop class="jqq5_cbzl"/><stop offset="1" class="e4q48c0eh"/></radialGradient><radialGradient id="iRyuAbb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46687 0 0 -2.17002 11.25 10.813)" gradientUnits="userSpaceOnUse"><stop offset=".149" class="prkeaabuo"/><stop offset="1" class="r445c2j1q"/></radialGradient><radialGradient id="iK5DgNB" cx="0" cy="0" r="1" gradientTransform="rotate(90 .202 10.828)scale(1.11995)" gradientUnits="userSpaceOnUse"><stop offset=".509" class="hr7rx-btp"/><stop offset="1" class="p185h896h"/></radialGradient><radialGradient id="iq1N7Ot" cx="0" cy="0" r="1" gradientTransform="rotate(-33.074 27.348 -27.198)scale(2.07337 1.66975)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w_o-5kbak"/><stop offset="1" class="mb4bnzbbk"/></radialGradient><radialGradient id="iFTL3zb" cx="0" cy="0" r="1" gradientTransform="matrix(.86341 -2.14596 2.91895 1.17442 20.142 10.74)" gradientUnits="userSpaceOnUse"><stop offset=".683" class="sxoyafbbn"/><stop offset=".972" class="tri7bg95c"/></radialGradient><radialGradient id="iRJueVc" cx="0" cy="0" r="1" gradientTransform="rotate(-47.534 24.297 -17.673)scale(2.11072 1.8094)" gradientUnits="userSpaceOnUse"><stop class="qrtt6bb6h"/><stop offset="1" class="jyn3bzb2d"/></radialGradient><radialGradient id="iYgugTc" cx="0" cy="0" r="1" gradientTransform="rotate(91.606 5.333 15.521)scale(1.11515)" gradientUnits="userSpaceOnUse"><stop class="zqtv86tqc"/><stop offset=".912" class="d1kj1wnus"/></radialGradient><radialGradient id="il8edcd" cx="0" cy="0" r="1" gradientTransform="rotate(-32.623 28.564 -30.26)scale(1.15983)" gradientUnits="userSpaceOnUse"><stop offset=".398" class="d1ghobc8y"/><stop offset="1" class="cxor92biy"/></radialGradient><radialGradient id="iuYjH9c" cx="0" cy="0" r="1" gradientTransform="matrix(1.03903 -.98438 2.30833 2.4365 20.398 8.485)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="u3u8jgbsg"/><stop offset=".879" class="zpvtvnbep"/></radialGradient><radialGradient id="ixNDlpe" cx="0" cy="0" r="1" gradientTransform="matrix(1.97272 .98047 -.09594 .19302 19.898 7.184)" gradientUnits="userSpaceOnUse"><stop class="hz3tyhiea"/><stop offset="1" class="zpejver4o"/></radialGradient><radialGradient id="iVo46Jc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1641 -.71876 .94072 -1.52358 11.602 8.813)" gradientUnits="userSpaceOnUse"><stop offset=".521" class="al51fozhq"/><stop offset=".94" class="k1j028b_u"/></radialGradient><radialGradient id="i1BS04c" cx="0" cy="0" r="1" gradientTransform="rotate(154.069 9.527 11.803)scale(3.78757 11.2112)" gradientUnits="userSpaceOnUse"><stop class="ium6abcxp"/><stop offset="1" class="h7lqrlw1r"/></radialGradient><radialGradient id="iFniQ8d" cx="0" cy="0" r="1" gradientTransform="matrix(2.5033 -1.90624 3.00378 3.94459 8.94 18.845)" gradientUnits="userSpaceOnUse"><stop class="g3ev-1bmq"/><stop offset="1" class="hdbb6nacd"/></radialGradient><radialGradient id="itpuwKt" cx="0" cy="0" r="1" gradientTransform="matrix(-5.9544 1.19435 -2.01845 -10.06296 19.451 10.416)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="mikfk6bja"/><stop offset="1" class="hdk36ccnl"/></radialGradient><radialGradient id="i3RPtoc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.13592 1.13266 0 14.095 9.688)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="ijs540dvc"/><stop offset="1" class="gdsm5cb9d"/></radialGradient><radialGradient id="iIJdcfd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.04388 1.15848 0 18.427 9.493)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="ub0upebjn"/><stop offset="1" class="coed5bbvh"/></radialGradient><radialGradient id="i8SV72b" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.73704 -10.9444 0 16 8.494)" gradientUnits="userSpaceOnUse"><stop offset=".633" class="ftb9gq14w"/><stop offset=".96" class="ucblpgx5e"/></radialGradient><radialGradient id="iaqkdjR" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.6875 3.6875 0 15.813 17.587)" gradientUnits="userSpaceOnUse"><stop class="p996l9hhh"/><stop offset="1" class="tz-f0l45j"/></radialGradient><radialGradient id="iY289Xr" cx="0" cy="0" r="1" gradientTransform="rotate(137.827 8.07 6.86)scale(3.58407 2.1419)" gradientUnits="userSpaceOnUse"><stop offset=".121" class="b4nr1bc0v"/><stop offset="1" class="m9ju14b0a"/></radialGradient><radialGradient id="iDskhfd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .22684 -.76458 0 16.465 12.273)" gradientUnits="userSpaceOnUse"><stop class="ifoj0vbnx"/><stop offset="1" class="fd01o6-ig"/></radialGradient><radialGradient id="iyCnoVc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.68633 .69705 -1.06744 -2.58237 16.58 11.743)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="xqbp6db-u"/><stop offset="1" class="l6ffphqdg"/><stop offset="1" class="bi0efq_rm"/></radialGradient><radialGradient id="ic9Bx5c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.99943 1.36453 -1.33986 -1.96328 28.12 23.804)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="v0ox3l-0u"/><stop offset="1" class="x78tqlban"/></radialGradient><radialGradient id="itJhove" cx="0" cy="0" r="1" gradientTransform="matrix(.78818 -.60013 .4599 .60401 27.529 23.653)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="ruv4dbc7o"/><stop offset="1" class="meeoi68df"/></radialGradient><radialGradient id="iAJs0Dd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.85126 .74829 0 26.113 24.805)" gradientUnits="userSpaceOnUse"><stop class="j2-8_acvh"/><stop offset="1" class="x6aj7b3cp"/></radialGradient><radialGradient id="iGV0Lcb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.82813 1.14062 0 26.137 21.626)" gradientUnits="userSpaceOnUse"><stop class="f1e16d8dl"/><stop offset="1" class="r_2nh8m3w"/><stop offset="1" class="pe7ydabrg"/></radialGradient><radialGradient id="iPcCcgb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.14844 2.01125 0 25.638 22.009)" gradientUnits="userSpaceOnUse"><stop offset=".76" class="ajwv7ubbs"/><stop offset="1" class="ljk-gfbyr"/></radialGradient><radialGradient id="iPALSUc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82316 -1.30932 0 18.214 10.005)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iDwwMDb" cx="0" cy="0" r="1" gradientTransform="matrix(-.2353 -.30322 .41746 -.32395 17.982 10.09)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i9EjNCc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8232 -1.30939 0 13.786 10.005)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iMexY0K" cx="0" cy="0" r="1" gradientTransform="matrix(-.00785 -.5013 .60257 -.00943 13.495 10.227)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iFkIlwc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.892 25.32)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iGGgL5c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.892 26.614)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iQjTiZc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.892 27.864)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iWgUYAc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.892 29.216)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><filter id="ihGYetd" width="20.537" height="10.328" x="5.481" y="4.845" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.384314 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1809"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.243137 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1809" result="effect2_innerShadow_4002_1809"/></filter><filter id="iLxxvPc" width="8" height="6.44" x="12" y="15.285" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.47451 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1809"/></filter><filter id="iHJvkDe" width="3.44" height="3.34" x="9.36" y="8.955" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 0.439216 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1809"/></filter><filter id="iD1BYtd" width="2.54" height="2.54" x="9.76" y="9.355" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1809" stdDeviation=".075"/></filter><filter id="i3VBaZc" width="3.027" height="3.027" x="19.307" y="9.112" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1809" stdDeviation=".175"/></filter><filter id="iHQ8X7b" width="8.45" height="4.612" x="11.73" y="25.595" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1809" stdDeviation=".125"/></filter><filter id="iIts4ib" width="8.05" height="4.28" x="11.88" y="25.845" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.67451 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1809"/></filter><filter id="iuHKvpu" width="10.66" height="10.004" x="10.92" y="7.018" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.580392 0 0 0 0 0.439216 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1809"/></filter><filter id="iTyLfib" width="3.871" height="4.695" x="13.872" y="9.285" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1809" stdDeviation=".5"/></filter><filter id="ikrw9qe" width="2.271" height="3.095" x="14.865" y="9.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1809" stdDeviation=".1"/></filter><filter id="iM1yDys" width="3.833" height="1.572" x="14.023" y="13.143" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1809" stdDeviation=".05"/></filter><filter id="izrSXlb" width="7.625" height="9.853" x="21.853" y="10.679" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 0.478431 0 0 0 0 0.698039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1809"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.776471 0 0 0 0 0.796078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1809" result="effect2_innerShadow_4002_1809"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.517647 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1809" result="effect3_innerShadow_4002_1809"/></filter><filter id="iGJOOra" width=".795" height=".703" x="17.47" y="9.56" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1809" stdDeviation=".05"/></filter><filter id="if6kVec" width=".898" height=".921" x="18.324" y="9.638" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1809" stdDeviation=".1"/></filter><filter id="i2hgwHm" width=".995" height="1.05" x="13.816" y="9.573" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1809" stdDeviation=".1"/></filter><filter id="iXmd21d" width=".923" height=".712" x="13.049" y="9.552" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1809" stdDeviation=".05"/></filter><filter id="idUh8Uc" width="4.468" height="5.556" x="23.454" y="24.459" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.313726 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1809"/></filter><filter id="i7NmnUd" width="2.097" height=".3" x="23.825" y="25.843" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1809" stdDeviation=".05"/></filter><filter id="iV0QQjK" width="2.097" height=".3" x="23.747" y="27.148" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1809" stdDeviation=".05"/></filter><filter id="i7JLUie" width="2.097" height=".3" x="23.825" y="28.453" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1809" stdDeviation=".05"/></filter><filter id="iYbaYvd" width="2.573" height="1.468" x="12.134" y="7.352" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.129412 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1809"/></filter><filter id="igC2hyi" width="2.573" height="1.468" x="17.293" y="7.352" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.129412 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1809"/></filter><filter id="i2otK3b" width="2.123" height=".868" x="17.56" y="7.61" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1809" stdDeviation=".075"/></filter><filter id="itRRAxe" width="2.123" height=".868" x="12.3" y="7.61" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1809" stdDeviation=".075"/></filter><linearGradient id="iCV2uie" x1="15.92" x2="15.92" y1="4.045" y2="4.099" gradientUnits="userSpaceOnUse"><stop class="xjz9wom2l"/><stop offset="1" class="pqe0dnzfz"/></linearGradient><linearGradient id="iUWdLjI" x1="16" x2="16" y1="4.845" y2="14.876" gradientUnits="userSpaceOnUse"><stop class="s1b5eccno"/><stop offset="1" class="rmy8pbgez"/></linearGradient><linearGradient id="iWeyW8j" x1="8.94" x2="5.35" y1="28.47" y2="28.47" gradientUnits="userSpaceOnUse"><stop class="es32odbdd"/><stop offset="1" class="wevrdub6o"/></linearGradient><linearGradient id="iDWfNsd" x1="26.503" x2="22.96" y1="22.9" y2="29.206" gradientUnits="userSpaceOnUse"><stop class="kcb1h97-p"/><stop offset="1" class="c6jm60b1r"/></linearGradient><linearGradient id="i2TpDkb" x1="20" x2="19.066" y1="18.532" y2="18.532" gradientUnits="userSpaceOnUse"><stop class="lzh17ac1w"/><stop offset="1" class="yrr42qhfr"/></linearGradient><linearGradient id="iqgS9Gb" x1="12" x2="12.334" y1="18.532" y2="18.532" gradientUnits="userSpaceOnUse"><stop offset=".143" class="pescu9bef"/><stop offset="1" class="fl69hubql"/></linearGradient><linearGradient id="iej3Hic" x1="22.17" x2="22.6" y1="9.399" y2="11.667" gradientUnits="userSpaceOnUse"><stop class="rozhtxbew"/><stop offset="1" class="wdid2qbjr"/></linearGradient><linearGradient id="iYmZ1ic" x1="17.162" x2="15.95" y1="29.157" y2="22.032" gradientUnits="userSpaceOnUse"><stop class="h3q0cq17v"/><stop offset="1" class="zykvaibcy"/></linearGradient><linearGradient id="i4fM6Dc" x1="23.014" x2="22.787" y1="29.688" y2="29.688" gradientUnits="userSpaceOnUse"><stop class="w-ul8jbeq"/><stop offset="1" class="vtbjbdc7x"/></linearGradient><linearGradient id="iYnOASd" x1="8.94" x2="9.064" y1="29.688" y2="29.688" gradientUnits="userSpaceOnUse"><stop class="w-ul8jbeq"/><stop offset="1" class="vtbjbdc7x"/></linearGradient><linearGradient id="izfIk8d" x1="13.787" x2="20.318" y1="28.376" y2="28.376" gradientUnits="userSpaceOnUse"><stop class="ym_13nbvu"/><stop offset="1" class="kehse99iu"/></linearGradient><linearGradient id="iEB8C5d" x1="16.835" x2="16" y1="11.635" y2="11.673" gradientUnits="userSpaceOnUse"><stop offset=".36" class="gb7af0bvz"/><stop offset="1" class="gafrz43pc"/></linearGradient><linearGradient id="ibbZY7c" x1="16" x2="16" y1="12.694" y2="12.262" gradientUnits="userSpaceOnUse"><stop class="q7066kb0m"/><stop offset="1" class="se5f_fbvx"/></linearGradient><linearGradient id="iuHmmfe" x1="16" x2="16" y1="10.18" y2="10.688" gradientUnits="userSpaceOnUse"><stop class="bl4x47bvc"/><stop offset="1" class="nv0opqb4i"/></linearGradient><linearGradient id="iMIC8WH" x1="14.658" x2="15.011" y1="14.255" y2="13.35" gradientUnits="userSpaceOnUse"><stop class="sjwz8ccmm"/><stop offset="1" class="itcx93bci"/></linearGradient><linearGradient id="i85zXbb" x1="25.61" x2="25.61" y1="21.626" y2="24.805" gradientUnits="userSpaceOnUse"><stop class="rl_kfsb7q"/><stop offset=".997" class="va-kb9bvg"/></linearGradient><linearGradient id="is80UUL" x1="25.638" x2="25.638" y1="22.329" y2="21.735" gradientUnits="userSpaceOnUse"><stop class="lmnxagbed"/><stop offset="1" class="ztn8dybrr"/></linearGradient><linearGradient id="iQzcKEb" x1="19.003" x2="18.685" y1="10.06" y2="10.256" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iSU8dab" x1="14.541" x2="14.223" y1="10.06" y2="10.256" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iAVdEVc" x1="27.483" x2="23.454" y1="28.078" y2="28.078" gradientUnits="userSpaceOnUse"><stop offset=".146" class="fd7w0ysog"/><stop offset=".861" class="wtwh9i50b"/></linearGradient><linearGradient id="iviITCc" x1="23.975" x2="25.684" y1="26.071" y2="26.071" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="iMvnCwK" x1="23.896" x2="25.606" y1="27.376" y2="27.376" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="i4PYJId" x1="23.975" x2="25.684" y1="28.681" y2="28.681" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-farmer-medium" /></template>
<style>
.a2gn4iuzk {
  stop-color: var(--svg-color--28a96b, #28A96B);
  stop-opacity: 0;
}

.ajcqqcwyx {
  d: path("M14.611 10.32c0-.293-.238-.488-.302-.547l-.292.283l.18.367z");
}

.ajwv7ubbs {
  stop-color: var(--svg-color--92879d, #92879D);
  stop-opacity: 0;
}

.al51fozhq {
  stop-color: var(--svg-color--341927, #341927);
}

.am3kgkbwr {
  d: path("M15.93 18.705c-1.14 0-2.06-.92-2.06-2.06v-2.56c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v2.56a2.07 2.07 0 0 1-2.06 2.06");
}

.b0115xbxz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.897 27.298h1.796");
}

.b3-e1tbeq {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.484 13.321c-.199-.106-.392.12-.276.301a2.07 2.07 0 0 0 1.732.943c.728 0 1.363-.38 1.732-.942a.2.2 0 0 0-.024-.256a.21.21 0 0 0-.25-.047l-.002.001a3.1 3.1 0 0 1-1.456.354a3.1 3.1 0 0 1-1.456-.354Z");
}

.b4nr1bc0v {
  stop-color: var(--svg-color--b68f80, #B68F80);
}

.bbdczxw8c {
  d: path("M21.492 7.756c-.418-.64-1.996-.738-2.566-.738l1.726 3.18h.53c.177 0 .35-.076.433-.231c.286-.528.438-1.467-.123-2.211");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bi0efq_rm {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
}

.bl4x47bvc {
  stop-color: var(--svg-color--a4786e, #A4786E);
}

.c392ft7tk {
  d: path("M18.15 9.713c.064.086-.071.191-.224.306s-.267.195-.332.109c-.064-.087.008-.25.16-.364c.154-.115.33-.138.395-.051");
}

.c6jm60b1r {
  stop-color: var(--svg-color--368d6e, #368D6E);
}

.cf0lpn8oo {
  cx: 13.511px;
  cy: 9.908px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.395px;
  ry: 0.2px;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.coed5bbvh {
  stop-color: var(--svg-color--a8776d, #A8776D);
  stop-opacity: 0;
}

.cxor92biy {
  stop-color: var(--svg-color--88594c, #88594C);
}

.d1ghobc8y {
  stop-color: var(--svg-color--88594c, #88594C);
  stop-opacity: 0;
}

.d1kj1wnus {
  stop-color: var(--svg-color--a47562, #A47562);
}

.d1vocvbes {
  stop-color: var(--svg-color--c99e80, #C99E80);
  stop-opacity: 0;
}

.d6r03hc-n {
  stop-color: var(--svg-color--63c890, #63C890);
}

.debh25b6n {
  fill: var(--svg-color--45bb85, #45BB85);
  d: path("M15.93 15.535c-6.07 0-10.99 4.91-10.99 10.98v3.5h21.98v-3.5c0-6.07-4.92-10.98-10.99-10.98");
}

.du0zoacsy {
  stop-color: var(--svg-color--815461, #815461);
}

.dz1f1dx9q {
  stop-color: var(--svg-color--28a96b, #28A96B);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e2_jykbzy {
  stop-color: var(--svg-color--6e4f4b, #6E4F4B);
  stop-opacity: 0;
}

.e4q48c0eh {
  stop-color: var(--svg-color--81545e, #81545E);
  stop-opacity: 0;
}

.es32odbdd {
  stop-color: var(--svg-color--399965, #399965);
}

.evdhv9byz {
  stroke: var(--svg-color--553e3e, #553E3E);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.5 8.277s.6-.58 1.723-.448");
}

.f1e16d8dl {
  stop-color: var(--svg-color--cbc1d6, #CBC1D6);
}

.f2_cz0v9z {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.975 25.993h1.796");
}

.fd01o6-ig {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
  stop-opacity: 0;
}

.fd7w0ysog {
  stop-color: var(--svg-color--c89a81, #C89A81);
}

.fl69hubql {
  stop-color: var(--svg-color--6a9e7e, #6A9E7E);
  stop-opacity: 0;
}

.fo00f_-hd {
  cx: 13.511px;
  cy: 9.908px;
  rx: 0.395px;
  ry: 0.2px;
}

.ft5dv1b6b {
  fill: none;
}

.ftb9gq14w {
  stop-color: var(--svg-color--915e6f, #915E6F);
  stop-opacity: 0;
}

.fv0x46bue {
  d: path("M11.03 12.295a1.67 1.67 0 1 0 0-3.34a1.67 1.67 0 0 0 0 3.34");
}

.fv53q1bnm {
  d: path("m15.62 10.345l-.53 1.71c-.11.35.15.7.52.7h.78c.37 0 .63-.35.52-.7l-.52-1.71a.403.403 0 0 0-.77 0");
}

.g3ev-1bmq {
  stop-color: var(--svg-color--3da0db, #3DA0DB);
}

.gafrz43pc {
  stop-color: var(--svg-color--cea58c, #CEA58C);
  stop-opacity: 0;
}

.gb7af0bvz {
  stop-color: var(--svg-color--cea58c, #CEA58C);
}

.gdsm5cb9d {
  stop-color: var(--svg-color--8d5e64, #8D5E64);
  stop-opacity: 0;
}

.gjeztxb4l {
  fill: var(--svg-color--88014e, #88014E);
  d: path("M15.94 13.725c-.54 0-1.05-.13-1.48-.36c-.15-.08-.3.09-.21.23c.36.55.98.92 1.69.92s1.33-.37 1.69-.92c.09-.14-.07-.3-.21-.23c-.43.23-.94.36-1.48.36");
}

.gkc627t-z {
  d: path("M22.96 30.015v-11.97h.006a10.95 10.95 0 0 1 3.994 8.47v3.5z");
}

.h29l8x_8c {
  stop-color: var(--svg-color--63c890, #63C890);
  stop-opacity: 0;
}

.h3q0cq17v {
  stop-color: var(--svg-color--3560c5, #3560C5);
}

.h7lqrlw1r {
  stop-color: var(--svg-color--47b2f6, #47B2F6);
  stop-opacity: 0;
}

.h7qlxhb-a {
  stop-color: var(--svg-color--e9cee6, #E9CEE6);
}

.hdbb6nacd {
  stop-color: var(--svg-color--3aa1e0, #3AA1E0);
  stop-opacity: 0;
}

.hdk36ccnl {
  stop-color: var(--svg-color--946765, #946765);
}

.hr7rx-btp {
  stop-color: var(--svg-color--6d443c, #6D443C);
  stop-opacity: 0;
}

.hz3tyhiea {
  stop-color: var(--svg-color--5d4242, #5D4242);
}

.ifoj0vbnx {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
}

.ijs540dvc {
  stop-color: var(--svg-color--8d5e64, #8D5E64);
}

.im6pbbc8v {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.15 9.713c.064.086-.071.191-.224.306s-.267.195-.332.109c-.064-.087.008-.25.16-.364c.154-.115.33-.138.395-.051");
}

.iplo5nbkc {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.574 9.245c-.662 0-1.222.457-1.375 1.075a.278.278 0 0 0 .272.345h2.264c.144 0 .26-.131.23-.275a1.42 1.42 0 0 0-1.39-1.145");
}

.itcx93bci {
  stop-color: var(--svg-color--ab817b, #AB817B);
  stop-opacity: 0;
}

.ium6abcxp {
  stop-color: var(--svg-color--47b2f6, #47B2F6);
}

.izuk-bqvv {
  fill: var(--svg-color--000, #000);
  d: path("M14.303 10.427a.516.516 0 0 0-.519-.519a.516.516 0 0 0-.461.757h.918a.5.5 0 0 0 .062-.238");
}

.j2-8_acvh {
  stop-color: var(--svg-color--88625f, #88625F);
}

.j3eudux9e {
  stop-color: var(--svg-color--519473, #519473);
  stop-opacity: 0;
}

.j403gj70r {
  fill: var(--svg-color--3661c6, #3661C6);
  d: path("M19.42 25.845h-6.94c-.28 0-.5.217-.5.492v3.62h7.95v-3.62a.513.513 0 0 0-.51-.492");
}

.jnvzjw9uu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.975 28.603h1.796");
}

.jqq5_cbzl {
  stop-color: var(--svg-color--81545e, #81545E);
}

.jyn3bzb2d {
  stop-color: var(--svg-color--9a716b, #9A716B);
  stop-opacity: 0;
}

.k1j028b_u {
  stop-color: var(--svg-color--483332, #483332);
}

.kc6n1tb_x {
  stop-color: var(--svg-color--399967, #399967);
  stop-opacity: 0;
}

.kcb1h97-p {
  stop-color: var(--svg-color--63d591, #63D591);
}

.kd-olwbcr {
  d: path("M26.113 21.805h-1v3h1z");
}

.kehse99iu {
  stop-color: var(--svg-color--389dff, #389DFF);
}

.kqztxxbtu {
  d: path("M12.964 21.509L16 19.385l2.987 2.085c.421.324 1.013.465 1.013-.355v-4.81c-1.24-.48-2.59-.77-4-.77s-2.76.24-4 .72v4.691c0 .953.594.823.964.563");
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.l731pf7zh {
  stop-color: var(--svg-color--835646, #835646);
}

.lgo9yub8v {
  stop-color: var(--svg-color--7f5f58, #7F5F58);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ljk-gfbyr {
  stop-color: var(--svg-color--92879d, #92879D);
}

.lmnxagbed {
  stop-color: var(--svg-color--89829d, #89829D);
}

.ltcbfxk7p {
  stop-color: var(--svg-color--644841, #644841);
}

.lzh17ac1w {
  stop-color: var(--svg-color--5aa37a, #5AA37A);
}

.m5xv22viy {
  d: path("M13.784 9.521a.906.906 0 0 0-.873 1.144h1.75a1 1 0 0 0 .033-.238a.91.91 0 0 0-.91-.906");
}

.m8_f8sbvv {
  d: path("M19.022 10.307a.85.85 0 0 0-.234-.47l-.264.29l.119.232z");
}

.m9ju14b0a {
  stop-color: var(--svg-color--b68f80, #B68F80);
  stop-opacity: 0;
}

.maklkcq7c {
  d: path("M20.82 11.789a1.163 1.163 0 1 0 0-2.327a1.163 1.163 0 0 0 0 2.327");
}

.mb4bnzbbk {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.meeoi68df {
  stop-color: var(--svg-color--cba68e, #CBA68E);
  stop-opacity: 0;
}

.mg0a58tbq {
  fill: var(--svg-color--8a6160, #8A6160);
  d: path("M11.03 12.295a1.67 1.67 0 1 0 0-3.34a1.67 1.67 0 0 0 0 3.34");
}

.mikfk6bja {
  stop-color: var(--svg-color--c19579, #C19579);
}

.n_23u1b6b {
  stop-color: var(--svg-color--3c2923, #3C2923);
}

.n_qe0-a_d {
  d: path("M20.82 12.295a1.67 1.67 0 1 0 0-3.34a1.67 1.67 0 0 0 0 3.34");
}

.nb487cbvy {
  stop-color: var(--svg-color--3d8f6c, #3D8F6C);
}

.njj87ojhb {
  stop-color: var(--svg-color--c2998b, #C2998B);
}

.nv0opqb4i {
  stop-color: var(--svg-color--a4786e, #A4786E);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oolzzy49q {
  stop-color: var(--svg-color--399967, #399967);
}

.oum2dd_7s {
  d: path("m10.1 5.585l-.18.36h12l-.17-.33c-.3-.59-.68-1.11-1.12-1.57h-9.42c-.43.45-.81.97-1.11 1.54");
}

.p185h896h {
  stop-color: var(--svg-color--6d443c, #6D443C);
}

.p996l9hhh {
  stop-color: var(--svg-color--825f6a, #825F6A);
}

.pbfq705wj {
  d: path("M22.96 18.075c-.63-.53-1.33-.99-2.07-1.36v5.9c0 .23-.18.41-.41.41h-9.07c-.23 0-.41-.18-.41-.41v-5.92c-.74.37-1.43.82-2.06 1.35v11.97h14.02z");
}

.pe7ydabrg {
  stop-color: var(--svg-color--aa9ab9, #AA9AB9);
}

.pescu9bef {
  stop-color: var(--svg-color--6a9e7e, #6A9E7E);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pqe0dnzfz {
  stop-color: var(--svg-color--4e2d3a, #4E2D3A);
  stop-opacity: 0;
}

.prkeaabuo {
  stop-color: var(--svg-color--734b49, #734B49);
}

.prorwkb4s {
  d: path("m16.85 19.725l-.65.58c-.16.14-.39.14-.55 0l-.65-.58a3.45 3.45 0 0 1-1.14-2.55v-3.09c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v3.09c0 .97-.41 1.9-1.13 2.55");
}

.pzgz70rhv {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.426 9.245c.663 0 1.222.457 1.375 1.075a.278.278 0 0 1-.272.345h-2.264a.234.234 0 0 1-.23-.275c.127-.65.7-1.145 1.391-1.145");
}

.q7066kb0m {
  stop-color: var(--svg-color--9c6376, #9C6376);
}

.qful1wpim {
  d: path("M15.93 15.535c-6.07 0-10.99 4.91-10.99 10.98v3.5h21.98v-3.5c0-6.07-4.92-10.98-10.99-10.98");
}

.qrtt6bb6h {
  stop-color: var(--svg-color--9a716b, #9A716B);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_2nh8m3w {
  stop-color: var(--svg-color--a099a8, #A099A8);
}

.r445c2j1q {
  stop-color: var(--svg-color--845b5a, #845B5A);
}

.r9exlwbyv {
  stop-color: var(--svg-color--4f3b60, #4F3B60);
}

.rl_kfsb7q {
  stop-color: var(--svg-color--784853, #784853);
}

.rmy8pbgez {
  stop-color: var(--svg-color--734f51, #734F51);
}

.rozhtxbew {
  stop-color: var(--svg-color--c19e89, #C19E89);
}

.rs3k7gc8p {
  stop-color: var(--svg-color--2a5923, #2A5923);
}

.ruv4dbc7o {
  stop-color: var(--svg-color--cba68e, #CBA68E);
}

.s1b5eccno {
  stop-color: var(--svg-color--643643, #643643);
}

.s1yo5-bze {
  d: path("M26.772 23.155c.55 0 1 .45 1 1v2.29h-2v-2.29c0-.55.44-1 1-1");
}

.sa19i-y8k {
  fill: var(--svg-color--9e7169, #9E7169);
  d: path("m15.62 10.345l-.53 1.71c-.11.35.15.7.52.7h.78c.37 0 .63-.35.52-.7l-.52-1.71a.403.403 0 0 0-.77 0");
}

.se5f_fbvx {
  stop-color: var(--svg-color--9c6376, #9C6376);
  stop-opacity: 0;
}

.sjwz8ccmm {
  stop-color: var(--svg-color--ab817b, #AB817B);
}

.st6ihdcnf {
  d: path("M19.42 25.845h-6.94c-.28 0-.5.22-.5.5v3.68h7.95v-3.68a.517.517 0 0 0-.51-.5");
}

.sxoyafbbn {
  stop-color: var(--svg-color--805d4c, #805D4C);
  stop-opacity: 0;
}

.tc5_6ybav {
  fill: var(--svg-color--492f2d, #492F2D);
  fill-rule: evenodd;
  d: path("M19.15 8.703a.425.425 0 0 0 .587-.614c-.493.51 0 0 0 0l-.001-.001l-.002-.002l-.004-.004l-.01-.01a1 1 0 0 0-.144-.113a2.3 2.3 0 0 0-.403-.227a2.85 2.85 0 0 0-1.505-.208a.425.425 0 0 0 .1.845c.477-.057.831.039 1.06.14a1.5 1.5 0 0 1 .312.186z");
}

.teqjn2bac {
  d: path("M24.877 20.024H26.4v1.735a.25.25 0 0 1-.25.25h-1.023a.25.25 0 0 1-.25-.25z");
}

.thw19dvgl {
  fill: var(--svg-color--492f2d, #492F2D);
  fill-rule: evenodd;
  d: path("M12.85 8.703a.425.425 0 0 1-.587-.614l.296.305l-.295-.305v-.001l.002-.002l.004-.004l.01-.01a1 1 0 0 1 .144-.113c.094-.066.229-.15.403-.227a2.85 2.85 0 0 1 1.505-.208a.425.425 0 1 1-.1.845a2 2 0 0 0-1.06.14a1.5 1.5 0 0 0-.312.186z");
}

.tri7bg95c {
  stop-color: var(--svg-color--805d4c, #805D4C);
}

.tz-f0l45j {
  stop-color: var(--svg-color--825f6a, #825F6A);
  stop-opacity: 0;
}

.u0ewzac_g {
  stop-color: var(--svg-color--805f59, #805F59);
}

.u3u8jgbsg {
  stop-color: var(--svg-color--2f1922, #2F1922);
}

.ub0upebjn {
  stop-color: var(--svg-color--a8776d, #A8776D);
}

.ucblpgx5e {
  stop-color: var(--svg-color--7c5962, #7C5962);
}

.ucdgelbmi {
  stop-color: var(--svg-color--835646, #835646);
  stop-opacity: 0;
}

.v0ox3l-0u {
  stop-color: var(--svg-color--a27f66, #A27F66);
}

.v4fyh9bof {
  fill: var(--svg-color--000, #000);
  d: path("M17.697 10.427c0-.289.23-.519.519-.519a.516.516 0 0 1 .46.757h-.917a.47.47 0 0 1-.062-.238");
}

.v6j_arbpy {
  d: path("M8.94 30.015v-11.97h-.006a10.95 10.95 0 0 0-3.994 8.47v3.5z");
}

.va-kb9bvg {
  stop-color: var(--svg-color--7d5248, #7D5248);
}

.viz48byvw {
  d: path("M18.216 9.521a.905.905 0 0 1 .872 1.144H17.34a.91.91 0 0 1 .877-1.144");
}

.vo7-53hhd {
  stop-color: var(--svg-color--3c2923, #3C2923);
  stop-opacity: 0;
}

.vtbjbdc7x {
  stop-color: var(--svg-color--356ebb, #356EBB);
  stop-opacity: 0;
}

.w_o-5kbak {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
}

.w-ul8jbeq {
  stop-color: var(--svg-color--356ebb, #356EBB);
}

.w6969eyte {
  stop-color: var(--svg-color--387c46, #387C46);
}

.wdid2qbjr {
  stop-color: var(--svg-color--a97e72, #A97E72);
}

.wevrdub6o {
  stop-color: var(--svg-color--5cc585, #5CC585);
}

.wly33_qqy {
  stop-color: var(--svg-color--9c8f92, #9C8F92);
}

.wn_y-ob0v {
  stroke: var(--svg-color--553e3e, #553E3E);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.483 8.277s-.6-.58-1.723-.448");
}

.wtwh9i50b {
  stop-color: var(--svg-color--94616d, #94616D);
}

.x_5xqwbuj {
  d: path("M11.564 4.845c-.85.031-2.679.228-4.102 1.336c-1.238.962-1.477 2.117-1.477 3.086v.476c-.093 1.781 1.446 4.93 6.883 4.93h6.264c5.437 0 6.976-3.149 6.883-4.93v-.476c0-.97-.24-2.124-1.477-3.086c-1.423-1.108-3.253-1.305-4.101-1.336z");
}

.x6aj7b3cp {
  stop-color: var(--svg-color--88625f, #88625F);
  stop-opacity: 0;
}

.x78tqlban {
  stop-color: var(--svg-color--6f4745, #6F4745);
}

.xjz9wom2l {
  stop-color: var(--svg-color--4e2d3a, #4E2D3A);
}

.xqbp6db-u {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
  stop-opacity: 0;
}

.y_klt4bgy {
  fill: var(--svg-color--bfb2cd, #BFB2CD);
  d: path("M22.755 11.08a.6.6 0 0 0-.602.6v6.852a1.5 1.5 0 0 0 1.5 1.5h4.125a1.5 1.5 0 0 0 1.5-1.5v-6.851a.602.602 0 1 0-1.203 0v4.449a.879.879 0 0 1-1.758 0v-4.45a.602.602 0 1 0-1.203 0v4.45a.879.879 0 0 1-1.757 0v-4.45a.6.6 0 0 0-.602-.6");
}

.ya4lejb1r {
  stop-color: var(--svg-color--6e5980, #6E5980);
}

.yc_s6bd2r {
  stop-color: var(--svg-color--6e4f4b, #6E4F4B);
}

.yh0xfd23l {
  d: path("M10.508 7.756c.418-.64 1.996-.738 2.566-.738l-1.726 3.18h-.53c-.177 0-.35-.076-.433-.231c-.285-.528-.438-1.467.123-2.211");
}

.ym_13nbvu {
  stop-color: var(--svg-color--3ca9ff, #3CA9FF);
}

.yp08p_blq {
  d: path("M21.92 5.945h-12l.18-.36a6.549 6.549 0 0 1 11.65.03z");
}

.yqignq8nw {
  d: path("M11.03 11.745a1.12 1.12 0 1 0 0-2.24a1.12 1.12 0 0 0 0 2.24");
}

.yrr42qhfr {
  stop-color: var(--svg-color--5aa37a, #5AA37A);
  stop-opacity: 0;
}

.yzhaj994c {
  d: path("M23.455 25.341c0-.401.325-.732.726-.732h2.391a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.591a.731.731 0 0 1-.32-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.zfr_dbbtg {
  d: path("M19.082 7.018h-6.168c-1.127 0-2.086 1.008-1.987 2.125l.184 4.942c.168 1.71 1.532 2.936 3.193 2.936h3.394c1.661 0 3.026-1.226 3.194-2.936l.187-5.04c.04-1.078-.91-2.027-1.997-2.027");
}

.zhri926iw {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.427 10.57l-.53 1.71c-.11.35.15.7.52.7h.78c.37 0 .63-.35.52-.7l-.52-1.71a.403.403 0 0 0-.77 0");
}

.zif_-obqz {
  stop-color: var(--svg-color--519473, #519473);
}

.zm4f_vbug {
  stop-color: var(--svg-color--2a5923, #2A5923);
  stop-opacity: 0;
}

.zpejver4o {
  stop-color: var(--svg-color--5d4242, #5D4242);
  stop-opacity: 0;
}

.zpvtvnbep {
  stop-color: var(--svg-color--4c2e35, #4C2E35);
}

.zqtv86tqc {
  stop-color: var(--svg-color--b08975, #B08975);
}

.ztn8dybrr {
  stop-color: var(--svg-color--89829d, #89829D);
  stop-opacity: 0;
}

.zykvaibcy {
  stop-color: var(--svg-color--329fea, #329FEA);
}

</style>
