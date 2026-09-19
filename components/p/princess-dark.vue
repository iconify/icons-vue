<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="ia98V1b" class="h-ngu4b2o"/></defs><g class="ft5dv1b6b"><g filter="url(#iltwdgc)"><path fill="url(#itk2M7X)" clip-rule="evenodd" class="ivh048xhs"/><path fill="url(#i683Ysd)" clip-rule="evenodd" class="ivh048xhs"/><path fill="url(#i4QT9Kc)" clip-rule="evenodd" class="ivh048xhs"/><path fill="url(#itCrSNd)" clip-rule="evenodd" class="ivh048xhs"/><path fill="url(#i4ai64d)" clip-rule="evenodd" class="ivh048xhs"/><path fill="url(#imFkj4c)" clip-rule="evenodd" class="ivh048xhs"/><path fill="url(#iIOvSWc)" clip-rule="evenodd" class="ivh048xhs"/><path fill="url(#iQkgXid)" clip-rule="evenodd" class="ivh048xhs"/><path fill="url(#icdDqJS)" clip-rule="evenodd" class="ivh048xhs"/><path fill="url(#ilsENSb)" clip-rule="evenodd" class="ivh048xhs"/><path fill="url(#iKB642o)" clip-rule="evenodd" class="ivh048xhs"/><path fill="url(#i0Ss8kd)" clip-rule="evenodd" class="ivh048xhs"/></g><path fill="url(#ihQi12b)" class="n6d_jnr9j"/><path fill="url(#ikQH8cb)" class="n6d_jnr9j"/><path fill="url(#iNUvqbF)" class="kcmmk5bxb"/><path fill="url(#iZIIgrd)" class="kcmmk5bxb"/><path fill="url(#iLkQkbd)" class="kcmmk5bxb"/><path fill="url(#iecRI9d)" class="w78c_mbga"/><path fill="url(#iDsAFBc)" class="w78c_mbga"/><path fill="url(#iSPlgje)" class="w78c_mbga"/><path fill="url(#ic2fKLc)" class="w78c_mbga"/><path fill="url(#ijG4gop)" class="e304mibzr"/><path fill="url(#ir2U4mb)" class="e304mibzr"/><path fill="url(#i0MLaVu)" class="e304mibzr"/><path fill="url(#iFO9tQd)" class="e304mibzr"/><path fill="url(#iyormFc)" class="pyjhqsreq"/><path fill="url(#ipazNNu)" class="pyjhqsreq"/><path fill="url(#iWfGsyb)" class="vl7hh0bdy"/><path fill="url(#iHrUmsd)" class="vl7hh0bdy"/><g filter="url(#i0beQ9Y)"><path clip-rule="evenodd" class="ovkwvebhl"/></g><g filter="url(#ikup5RX)"><path fill="url(#iAhj8Hn)" clip-rule="evenodd" class="inuz7fbaa"/></g><path fill="url(#iB6tLsc)" clip-rule="evenodd" class="inuz7fbaa"/><path fill="url(#ifi30ue)" clip-rule="evenodd" class="inuz7fbaa"/><path fill="url(#iRI4m7h)" clip-rule="evenodd" class="inuz7fbaa"/><path fill="url(#iolaald)" clip-rule="evenodd" class="inuz7fbaa"/><g filter="url(#iz1kL1c)"><path clip-rule="evenodd" class="mobf8tbpp"/></g><circle fill="url(#iPmHRmc)" transform="matrix(-1 0 0 1 19.557 19.986)" class="ean9ofhjo"/><circle fill="url(#ianTTFc)" transform="matrix(-1 0 0 1 19.557 19.986)" class="ean9ofhjo"/><circle fill="url(#ihF3OKd)" transform="matrix(-1 0 0 1 19.057 21.744)" class="ean9ofhjo"/><circle fill="url(#iUtrbGD)" transform="matrix(-1 0 0 1 19.057 21.744)" class="ean9ofhjo"/><circle fill="url(#ixjPQUb)" transform="matrix(-1 0 0 1 17.792 23.111)" class="ean9ofhjo"/><circle fill="url(#ikD1Ide)" transform="matrix(-1 0 0 1 17.792 23.111)" class="ean9ofhjo"/><circle fill="url(#isuVgPF)" transform="matrix(-1 0 0 1 17.792 23.111)" class="ean9ofhjo"/><g filter="url(#iqyMzkd)"><circle fill="url(#iuTMqgc)" class="g6hzctbpu"/><circle fill="url(#iMTto5b)" class="g6hzctbpu"/><circle fill="url(#ibKaeAo)" class="g6hzctbpu"/></g><g filter="url(#in5FNwb)"><circle fill="url(#izwboXE)" class="oo7p4ebqa"/><circle fill="url(#ijSHste)" class="oo7p4ebqa"/><circle fill="url(#iqdo5md)" class="oo7p4ebqa"/><circle fill="url(#iRxLk5d)" class="oo7p4ebqa"/></g><g filter="url(#ilGVVIe)"><circle fill="url(#iY7ZVWc)" class="n0x7ebc8c"/><circle fill="url(#ibnwHYt)" class="n0x7ebc8c"/><circle fill="url(#iMGUs4b)" class="n0x7ebc8c"/><circle fill="url(#ie2nM2s)" class="n0x7ebc8c"/></g><g filter="url(#itI4Rzc)"><circle fill="url(#iHzkxde)" class="dvuac4bxb"/><circle fill="url(#i7dGJyb)" class="dvuac4bxb"/><circle fill="url(#iR45lBb)" class="dvuac4bxb"/></g><rect fill="url(#ivZVDro)" class="na-ss_5-a"/><rect fill="url(#iYUvu9c)" class="na-ss_5-a"/><path fill="url(#ilABBKc)" class="n261g_b5l"/><path fill="url(#i30rZSc)" class="gfzgh5bel"/><g filter="url(#iKfbzLt)"><path fill="url(#i9SzZlc)" class="v5l-j3bvb"/></g><g filter="url(#id9KLlM)"><path fill="url(#iqwlsbk)" class="sspmcqbor"/><path fill="url(#iQ4EiFe)" class="sspmcqbor"/></g><g filter="url(#ieRh6lb)"><path class="uhu16ny2z"/><path fill="url(#iu6B9oS)" class="tt-kr1b-n"/></g><g filter="url(#iNloBUc)"><path class="nduru5xwu"/><path fill="url(#iScjATc)" class="wg_j-qo3v"/></g><g filter="url(#itgscOb)"><path fill="url(#iRPSarc)" class="l_ewlebdc"/><path fill="url(#iacqAWc)" class="l_ewlebdc"/><path fill="url(#iN5SDpa)" class="l_ewlebdc"/><path fill="url(#iLlA68d)" class="l_ewlebdc"/><path fill="url(#iSSSvqe)" class="l_ewlebdc"/><path fill="url(#i54B1re)" class="l_ewlebdc"/><path fill="url(#i7MxD2z)" class="l_ewlebdc"/><path fill="url(#iRYJisd)" class="l_ewlebdc"/></g><path fill="url(#iH2eUbd)" class="l_ewlebdc"/><path fill="url(#i8Ne6sp)" class="l_ewlebdc"/><g filter="url(#iSwCxuc)"><path class="buo7-obdy"/></g><g filter="url(#inIKF4Z)"><path class="w4tdaku_b"/><path fill="url(#iLkp7Dc)" class="zzkdlsoov"/><path fill="url(#iY8oHlc)" class="zzkdlsoov"/><path fill="url(#iXJWtYr)" class="zzkdlsoov"/><path fill="url(#iO5iAZb)" class="zzkdlsoov"/></g><g filter="url(#iYtVNOc)"><use href="#ia98V1b"/><path stroke="url(#i1Qjkub)" class="mam21uzwo"/></g><use href="#ia98V1b"/><g filter="url(#ivylNBd)"><path class="cakm38t-m"/></g><g filter="url(#iJjJLLb)"><path class="r7y8-fuqh"/></g><g filter="url(#ikswBDc)"><path class="w1-gvmrbk"/></g><g filter="url(#ix3Qfqc)"><path clip-rule="evenodd" class="ez8x1mb2s"/></g><path class="bee5xpc4n"/><path fill="url(#iANFVae)" class="ebp3oh52k"/><path class="kx-k2bm9u"/><g filter="url(#ifJaP6b)"><path class="tbk29ybzd"/><path fill="url(#iNZbqrd)" class="nc960pbfz"/></g><g filter="url(#ixptWLp)"><path fill="url(#i4DLCWc)" class="g0bd9ib2e"/></g><path class="j707yuzrq"/><path fill="url(#ihVGiDd)" class="xkvq89bye"/><path class="v8pgeumfm"/><g filter="url(#iRPQVZV)"><path fill="url(#il4USve)" class="hf_fcmwun"/></g><g filter="url(#iiXpqZd)"><ellipse transform="rotate(-27.914 13.54 13.9)" class="dvfwus5_j"/><ellipse fill="url(#icm9F2c)" transform="rotate(-27.914 13.54 13.9)" class="wq49cmbeq"/></g><g filter="url(#iwa1qcc)"><path class="w6eefwb-r"/></g><g filter="url(#io6RD1d)"><path class="j9-kjkbge"/></g><g filter="url(#itV6mdd)"><path class="rxbeu-beb"/><path fill="url(#ia0chrb)" class="ii093lbht"/></g><g filter="url(#i7DZAib)"><path class="iw3rcybbt"/><path fill="url(#iUqMwxb)" class="dl-fg6u5t"/><path fill="url(#iEonI4b)" class="dl-fg6u5t"/></g><g filter="url(#iBRHAed)"><path stroke="url(#iTZQTPe)" class="fbn9skb1g"/></g><g filter="url(#id7gi8c)"><path class="cg61kj_fh"/></g><g filter="url(#iUeX6Nc)"><path class="bicb17dvp"/></g><circle fill="url(#icRhpDc)" class="q8l1y6b0l"/><circle fill="url(#iQREtnd)" class="q8l1y6b0l"/><circle fill="url(#iBRKmve)" class="o6_n3pbob"/><g filter="url(#ipnJ7Xd)"><path fill="url(#iUZ7Ske)" class="fus8l7b8h"/><path fill="url(#iVERpqe)" class="fus8l7b8h"/></g><path fill="url(#iw9QqUc)" class="cm8_bn2mq"/><path fill="url(#iBqn1xd)" class="cm8_bn2mq"/><path fill="url(#iwacREz)" class="cm8_bn2mq"/><g filter="url(#ilSA0He)"><circle fill="url(#ic9SDUc)" class="mxq0h6ljd"/><circle fill="url(#iQiXRXd)" class="mxq0h6ljd"/></g><g filter="url(#iQuE4rb)"><circle fill="url(#iDI5g0V)" class="uegyi0cvz"/><circle fill="url(#i53KubP)" class="uegyi0cvz"/></g><g filter="url(#iu9cynd)"><path fill="url(#iEEEWSb)" class="huvog8bmh"/><path fill="url(#iWRW5Zd)" class="huvog8bmh"/><path fill="url(#ieWHizW)" class="huvog8bmh"/><path fill="url(#iS293Ii)" class="huvog8bmh"/><path fill="url(#ihSSm7d)" class="huvog8bmh"/><path fill="url(#iBw0BYb)" class="huvog8bmh"/><path fill="url(#ifeMfDb)" class="huvog8bmh"/><path fill="url(#izm3X0b)" class="huvog8bmh"/></g><g filter="url(#itZSccb)"><circle fill="url(#iZzVw3c)" class="q0597ob7u"/><circle fill="url(#ilaTEnd)" class="q0597ob7u"/></g><g filter="url(#i2huQnx)"><circle fill="url(#i0wBymb)" class="tobb-5f3c"/><circle fill="url(#i5B04wi)" class="tobb-5f3c"/></g><g filter="url(#iFioCtc)"><circle class="h88_-5b3g"/></g><g filter="url(#iFaGyqe)"><circle class="lbkb08b7q"/></g><g filter="url(#ihXBA0b)"><circle class="a6mi8bcxq"/></g><g filter="url(#iyaTCUb)"><circle fill="url(#igxjaic)" class="rqzct4dku"/><circle fill="url(#iH9PggR)" class="rqzct4dku"/></g><g filter="url(#iBuga9c)"><circle fill="url(#iHcrFqe)" class="rg4_m7b_n"/></g><g filter="url(#ijMow7d)"><circle fill="url(#iNmQTwe)" class="lvm1e4qso"/></g><g filter="url(#izOQrmc)"><path stroke="url(#iYpqpOA)" class="re4dv2b7j"/></g><g filter="url(#i6C6bJd)"><circle fill="url(#iD4RU4b)" class="uo29cubui"/><circle fill="url(#iEeNFte)" class="uo29cubui"/></g><defs><radialGradient id="i683Ysd" cx="0" cy="0" r="1" gradientTransform="matrix(-.60337 4.55908 -5.69522 -.75373 15.691 17.092)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="i4QT9Kc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88301 1.94432 -2.5547 -3.78806 12.876 17.362)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="itCrSNd" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 1.914 10.162)scale(2.15225 1.65263)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="i4ai64d" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 2.216 9.646)scale(2.47506 1.74346)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="imFkj4c" cx="0" cy="0" r="1" gradientTransform="rotate(62.272 .829 13.59)scale(2.95399 4.10059)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="iIOvSWc" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 9.13 8.827)scale(2.03849 2.84876)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iQkgXid" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.11855 -3.84482 23.502 13.741)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="icdDqJS" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.393 9.99)scale(2.90248 3.69733)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="ilsENSb" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 14.407 -1.76)scale(2.80034 2.21491)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="iKB642o" cx="0" cy="0" r="1" gradientTransform="matrix(1.50392 .15775 -.2556 2.43678 9.851 13.705)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="i0Ss8kd" cx="0" cy="0" r="1" gradientTransform="rotate(107.382 1.28 9.115)scale(2.91973 2.69143)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="gcrmpdfop"/><stop offset="1" class="nd--cppfl"/></radialGradient><radialGradient id="ihQi12b" cx="0" cy="0" r="1" gradientTransform="matrix(.41273 -1.93102 2.1235 .45387 5.646 29.99)" gradientUnits="userSpaceOnUse"><stop class="g049h7flb"/><stop offset="1" class="hoqi9e01c"/></radialGradient><radialGradient id="iNUvqbF" cx="0" cy="0" r="1" gradientTransform="matrix(.40626 2.08282 -3.53623 .68974 25.776 28.73)" gradientUnits="userSpaceOnUse"><stop class="k5zu23s6k"/><stop offset="0" class="bp0jotlxe"/><stop offset="1" class="z54rox6ux"/></radialGradient><radialGradient id="iZIIgrd" cx="0" cy="0" r="1" gradientTransform="matrix(.153 1.2035 -2.47782 .31501 25.009 28.28)" gradientUnits="userSpaceOnUse"><stop offset=".812" class="cunr-1bwb"/><stop offset=".95" class="yind2xb3b"/></radialGradient><radialGradient id="iecRI9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.1875 2.41638 0 8.4 28.49)" gradientUnits="userSpaceOnUse"><stop offset=".223" class="jypakik4k"/><stop offset="1" class="spc75r5za"/></radialGradient><radialGradient id="iDsAFBc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65087 -5.32423 3.75234 -1.16348 7.152 27.94)" gradientUnits="userSpaceOnUse"><stop offset=".512" class="z_f48dbjf"/><stop offset="1" class="mjrstybho"/></radialGradient><radialGradient id="iSPlgje" cx="0" cy="0" r="1" gradientTransform="matrix(-.31987 0 0 -6.06796 8.41 25.857)" gradientUnits="userSpaceOnUse"><stop offset=".323" class="kf6yzhcxx"/><stop offset="1" class="if8ggt7lg"/></radialGradient><radialGradient id="ic2fKLc" cx="0" cy="0" r="1" gradientTransform="matrix(-.37502 3.78125 -4.19096 -.41565 7.463 25.52)" gradientUnits="userSpaceOnUse"><stop offset=".94" class="jhbwcacjr"/><stop offset="1" class="lxwln9mzq"/></radialGradient><radialGradient id="ijG4gop" cx="0" cy="0" r="1" gradientTransform="matrix(4.71875 -5.90625 1.33451 1.0662 23.995 28.584)" gradientUnits="userSpaceOnUse"><stop offset=".14" class="lkxhe0bym"/><stop offset="1" class="zn9diyb1a"/></radialGradient><radialGradient id="ir2U4mb" cx="0" cy="0" r="1" gradientTransform="matrix(2.6562 6.25003 -5.11847 2.1753 23.495 23.052)" gradientUnits="userSpaceOnUse"><stop class="k3jt88b8m"/><stop offset=".783" class="k3jt88b8m"/><stop offset="1" class="t70q9k_cc"/></radialGradient><radialGradient id="i0MLaVu" cx="0" cy="0" r="1" gradientTransform="matrix(.5625 0 0 8.2125 23.37 27.709)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="lqhq5vk7o"/><stop offset="1" class="axbh60bsz"/></radialGradient><radialGradient id="iFO9tQd" cx="0" cy="0" r="1" gradientTransform="matrix(4.625 -4.96875 2.03088 1.89038 22.65 23.74)" gradientUnits="userSpaceOnUse"><stop class="rlxb2vbdo"/><stop offset="1" class="h55xk6bmz"/></radialGradient><radialGradient id="ipazNNu" cx="0" cy="0" r="1" gradientTransform="matrix(-3.51563 0 0 -10.7812 23.635 26.459)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="toy3i-56q"/><stop offset="1" class="a3n886b5x"/></radialGradient><radialGradient id="iWfGsyb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.28125 0 0 -5.36523 21.588 22.521)" gradientUnits="userSpaceOnUse"><stop class="k7acx4bkv"/><stop offset="1" class="t18jwhbnk"/></radialGradient><radialGradient id="iHrUmsd" cx="0" cy="0" r="1" gradientTransform="rotate(-137.291 13.972 10.311)scale(6.08156 10.1177)" gradientUnits="userSpaceOnUse"><stop class="j47fkwbxf"/><stop offset="1" class="st2gozbew"/></radialGradient><radialGradient id="ifi30ue" cx="0" cy="0" r="1" gradientTransform="matrix(4.55232 5.22072 -.2143 .18687 10.393 21.734)" gradientUnits="userSpaceOnUse"><stop class="bmln26pap"/><stop offset="1" class="yb1xaiemt"/></radialGradient><radialGradient id="iRI4m7h" cx="0" cy="0" r="1" gradientTransform="rotate(122.137 5.436 17.063)scale(.71964 .79411)" gradientUnits="userSpaceOnUse"><stop offset=".107" class="vfe9g3b6u"/><stop offset="1" class="kth1ncger"/></radialGradient><radialGradient id="iolaald" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.62442 -16.4807 0 15.992 22.99)" gradientUnits="userSpaceOnUse"><stop offset=".739" class="uzx-du17j"/><stop offset="1" class="sbez_4byf"/></radialGradient><radialGradient id="iPmHRmc" cx="0" cy="0" r="1" gradientTransform="rotate(24.193 -1.558 .6)scale(1.18194)" gradientUnits="userSpaceOnUse"><stop offset=".039" class="pmg10qb6b"/><stop offset="1" class="q-wkihbps"/></radialGradient><radialGradient id="ianTTFc" cx="0" cy="0" r="1" gradientTransform="rotate(26.328 -1.599 1.184)scale(1.69104)" gradientUnits="userSpaceOnUse"><stop offset=".492" class="fkfx3o27i"/><stop offset="1" class="voqk07baz"/></radialGradient><radialGradient id="ihF3OKd" cx="0" cy="0" r="1" gradientTransform="matrix(.65625 .59375 -.52749 .58302 .469 .637)" gradientUnits="userSpaceOnUse"><stop class="ls12e09pb"/><stop offset="1" class="tfsbwvbnl"/></radialGradient><radialGradient id="iUtrbGD" cx="0" cy="0" r="1" gradientTransform="rotate(17.956 -3.342 1.542)scale(1.7739 2.2924)" gradientUnits="userSpaceOnUse"><stop offset=".485" class="ceou1rsni"/><stop offset="1" class="tknr5ybzo"/></radialGradient><radialGradient id="ixjPQUb" cx="0" cy="0" r="1" gradientTransform="matrix(.70313 .57812 -.5501 .66904 .563 .832)" gradientUnits="userSpaceOnUse"><stop class="z9cu3vbra"/><stop offset="1" class="t2krvpb6g"/></radialGradient><radialGradient id="ikD1Ide" cx="0" cy="0" r="1" gradientTransform="rotate(-124.498 1.26 .614)scale(1.07592)" gradientUnits="userSpaceOnUse"><stop class="biu9whxny"/><stop offset="1" class="eh1sqyczn"/></radialGradient><radialGradient id="isuVgPF" cx="0" cy="0" r="1" gradientTransform="matrix(1.71875 -.0625 .06517 1.79228 .39 1.254)" gradientUnits="userSpaceOnUse"><stop offset=".541" class="kr7xbubfl"/><stop offset=".978" class="ftn-nj88l"/></radialGradient><radialGradient id="iuTMqgc" cx="0" cy="0" r="1" gradientTransform="rotate(150.945 4.004 11.562)scale(1.93043)" gradientUnits="userSpaceOnUse"><stop offset=".105" class="oj0sgcj4p"/><stop offset="1" class="eapmb-b-r"/></radialGradient><radialGradient id="iMTto5b" cx="0" cy="0" r="1" gradientTransform="matrix(1.08593 -.28907 .36133 1.35742 11.784 20.201)" gradientUnits="userSpaceOnUse"><stop class="vavjlxdpa"/><stop offset="1" class="o8dw4p7vp"/></radialGradient><radialGradient id="ibKaeAo" cx="0" cy="0" r="1" gradientTransform="matrix(-.20313 -.58594 1.12396 -.38964 12.745 21.03)" gradientUnits="userSpaceOnUse"><stop class="n6j5avbvg"/><stop offset="1" class="pj5su6bsv"/></radialGradient><radialGradient id="izwboXE" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03125 .53906 -.49728 -.95134 13.245 21.584)" gradientUnits="userSpaceOnUse"><stop class="rr9pqccyi"/><stop offset="1" class="j-hgq5bil"/></radialGradient><radialGradient id="ijSHste" cx="0" cy="0" r="1" gradientTransform="rotate(-90 17.69 5.054)scale(1.30078)" gradientUnits="userSpaceOnUse"><stop class="xjhzw6b4m"/><stop offset="1" class="vlr1jy-qw"/></radialGradient><radialGradient id="iqdo5md" cx="0" cy="0" r="1" gradientTransform="matrix(-.53125 -.32812 .45767 -.741 13.659 22.81)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="da38a73_c"/><stop offset="1" class="kijt7rb5s"/></radialGradient><radialGradient id="iRxLk5d" cx="0" cy="0" r="1" gradientTransform="rotate(16.869 -67.097 54.03)scale(1.26538)" gradientUnits="userSpaceOnUse"><stop offset=".708" class="d7gnwkbua"/><stop offset="1" class="xg0mdnbqj"/></radialGradient><radialGradient id="iY7ZVWc" cx="0" cy="0" r="1" gradientTransform="rotate(144.31 3.603 13.786)scale(1.36591)" gradientUnits="userSpaceOnUse"><stop class="fg8vwkbfq"/><stop offset="1" class="kqlr11b-y"/><stop offset="1" class="gsgx-m-kb"/></radialGradient><radialGradient id="ibnwHYt" cx="0" cy="0" r="1" gradientTransform="matrix(2 -.98437 1.00596 2.04386 13.573 23.443)" gradientUnits="userSpaceOnUse"><stop offset=".6" class="fga1l482e"/><stop offset="1" class="owyqbq1bg"/></radialGradient><radialGradient id="iMGUs4b" cx="0" cy="0" r="1" gradientTransform="rotate(69.444 -9.015 21.41)scale(2.0025 1.86717)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="cy4ujdbiq"/><stop offset=".942" class="esixkvbpd"/></radialGradient><radialGradient id="ie2nM2s" cx="0" cy="0" r="1" gradientTransform="matrix(-.48437 -.0547 .10997 -.97398 15.159 23.49)" gradientUnits="userSpaceOnUse"><stop offset=".115" class="u-wvucrhg"/><stop offset="1" class="yidq71bjl"/></radialGradient><radialGradient id="iHzkxde" cx="0" cy="0" r="1" gradientTransform="rotate(144.31 4.424 14.318)scale(1.36591)" gradientUnits="userSpaceOnUse"><stop class="xf3nhjbpw"/><stop offset="1" class="kqlr11b-y"/></radialGradient><radialGradient id="i7dGJyb" cx="0" cy="0" r="1" gradientTransform="rotate(-142.172 12.357 9.09)scale(1.68149 1.71836)" gradientUnits="userSpaceOnUse"><stop offset=".472" class="xpqto8b3q"/><stop offset="1" class="gag6ovb3k"/></radialGradient><radialGradient id="iR45lBb" cx="0" cy="0" r="1" gradientTransform="matrix(-.64062 1.9375 -1.79684 -.5941 16.276 22.85)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="fr4aurb9m"/><stop offset=".904" class="fpyoctiow"/></radialGradient><radialGradient id="iYUvu9c" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.07812 -2.78906 0 16.003 19.936)" gradientUnits="userSpaceOnUse"><stop offset=".823" class="tljjlvbsz"/><stop offset="1" class="seh-d5byd"/></radialGradient><radialGradient id="iqwlsbk" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 20.033 15.032)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="ayiod_bfg"/><stop offset=".944" class="wb78_hxsc"/></radialGradient><radialGradient id="iQ4EiFe" cx="0" cy="0" r="1" gradientTransform="matrix(1.31577 .7375 -.2085 .37199 21.064 12.911)" gradientUnits="userSpaceOnUse"><stop class="s9u3_wbrp"/><stop offset="1" class="crde6o_5i"/></radialGradient><radialGradient id="iu6B9oS" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 20.385 14.705)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="rmmi4abgs"/><stop offset="1" class="xuyenabum"/></radialGradient><radialGradient id="iScjATc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.20681 0 0 -.95203 11.392 14.593)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="pj2ff5nxp"/><stop offset="1" class="sdufqstmc"/></radialGradient><radialGradient id="iRPSarc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50358 2.99902 -4.01413 -8.70492 18.852 14.055)" gradientUnits="userSpaceOnUse"><stop class="aj61gebdf"/><stop offset="1" class="v2xpqhbrh"/></radialGradient><radialGradient id="iacqAWc" cx="0" cy="0" r="1" gradientTransform="rotate(154.513 7.225 9.464)scale(2.25599 1.57104)" gradientUnits="userSpaceOnUse"><stop class="o3k0towjz"/><stop offset="1" class="x7h3p2bdy"/></radialGradient><radialGradient id="iN5SDpa" cx="0" cy="0" r="1" gradientTransform="matrix(1.0735 -3.47607 4.41049 1.36207 13.813 20.837)" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></radialGradient><radialGradient id="iLlA68d" cx="0" cy="0" r="1" gradientTransform="rotate(96.727 1.95 14.455)scale(6.84714 6.88381)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="m6mmhsf1n"/><stop offset="1" class="do3fwrbgr"/></radialGradient><radialGradient id="iSSSvqe" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.56691 -6.60207 0 15.731 14.445)" gradientUnits="userSpaceOnUse"><stop offset=".794" class="d0fyzsbqc"/><stop offset="1" class="n8ysctycz"/></radialGradient><radialGradient id="i54B1re" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.134 8.758)scale(7.03739 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="f6uv1pf_h"/><stop offset="1" class="fp6zmm73k"/></radialGradient><radialGradient id="i7MxD2z" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.294 13.636)" gradientUnits="userSpaceOnUse"><stop class="yv4uycbmh"/><stop offset="1" class="wgpm0ibqw"/></radialGradient><radialGradient id="iRYJisd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 13.917 13.408)" gradientUnits="userSpaceOnUse"><stop class="f82mfcbsw"/><stop offset="1" class="xkhh7vb2n"/></radialGradient><radialGradient id="iH2eUbd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28528 0 0 -6.44557 21.088 15.124)" gradientUnits="userSpaceOnUse"><stop class="jids0zpwm"/><stop offset="1" class="zz4mcgrzh"/></radialGradient><radialGradient id="i8Ne6sp" cx="0" cy="0" r="1" gradientTransform="matrix(-1.829 1.57435 -1.05517 -1.22584 19.914 19.17)" gradientUnits="userSpaceOnUse"><stop class="ybvm9tprh"/><stop offset=".694" class="yxwqgvbem"/></radialGradient><radialGradient id="iLkp7Dc" cx="0" cy="0" r="1" gradientTransform="matrix(-.45554 -2.04401 .62995 -.1404 16.778 15.85)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="x_sue_b_g"/><stop offset="1" class="gl9okfban"/></radialGradient><radialGradient id="iO5iAZb" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.2179 16.538 16.062)" gradientUnits="userSpaceOnUse"><stop class="t5djkhb4t"/><stop offset="1" class="qm132ccsa"/></radialGradient><radialGradient id="iANFVae" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.175 13.996)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iNZbqrd" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 17.947 14.08)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ihVGiDd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.81 13.996)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="icm9F2c" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 13.76 .45)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ia0chrb" cx="0" cy="0" r="1" gradientTransform="rotate(-65.391 14.418 -2.113)scale(3.03069 1.55043)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="iUqMwxb" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 6.856 8.962)scale(4.8729 7.96691)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="iEonI4b" cx="0" cy="0" r="1" gradientTransform="matrix(-.21033 1.3672 -2.94145 -.45252 16.204 7.038)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><radialGradient id="icRhpDc" cx="0" cy="0" r="1" gradientTransform="rotate(117.967 9.13 10.283)scale(1.06405 1.3957)" gradientUnits="userSpaceOnUse"><stop offset=".265" class="dakdtmo8r"/><stop offset="1" class="arn54kl4j"/></radialGradient><radialGradient id="iQREtnd" cx="0" cy="0" r="1" gradientTransform="matrix(.33234 -.2841 .1844 .21572 22.489 7.084)" gradientUnits="userSpaceOnUse"><stop offset=".234" class="n-7gz4alz"/><stop offset="1" class="v8gtn-b7b"/></radialGradient><radialGradient id="iBRKmve" cx="0" cy="0" r="1" gradientTransform="matrix(.69557 .35875 -.43597 .8453 9.317 7.265)" gradientUnits="userSpaceOnUse"><stop class="sti3oxbeq"/><stop offset="1" class="x5-3y6xrq"/></radialGradient><radialGradient id="iVERpqe" cx="0" cy="0" r="1" gradientTransform="matrix(.07422 .35146 -.52397 .11065 12.276 5.217)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="itk3z-5ip"/><stop offset="1" class="j8q5y3jei"/></radialGradient><radialGradient id="iw9QqUc" cx="0" cy="0" r="1" gradientTransform="rotate(-80.737 13.6 -8.133)scale(1.02905 .94206)" gradientUnits="userSpaceOnUse"><stop class="nj0s1tj2o"/><stop offset="1" class="z1-7jowoz"/></radialGradient><radialGradient id="iBqn1xd" cx="0" cy="0" r="1" gradientTransform="matrix(-.4922 -1.07031 .2266 -.1042 20.526 6.217)" gradientUnits="userSpaceOnUse"><stop offset=".149" class="o9ez09qax"/><stop offset="1" class="qrzlg2j4q"/></radialGradient><radialGradient id="iwacREz" cx="0" cy="0" r="1" gradientTransform="matrix(.10156 .3749 -.50936 .138 19.854 5.217)" gradientUnits="userSpaceOnUse"><stop offset=".299" class="hv46-obcm"/><stop offset="1" class="g7x6q-lxe"/></radialGradient><radialGradient id="ic9SDUc" cx="0" cy="0" r="1" gradientTransform="matrix(-.97508 .53473 -.2619 -.47757 20.426 4.355)" gradientUnits="userSpaceOnUse"><stop class="td2tyjbuq"/><stop offset="1" class="byw-t0bic"/></radialGradient><radialGradient id="iQiXRXd" cx="0" cy="0" r="1" gradientTransform="matrix(.62908 -.93084 .84184 .56893 19.403 5.412)" gradientUnits="userSpaceOnUse"><stop class="a7hrg2b7m"/><stop offset="1" class="kgfm8cpgt"/></radialGradient><radialGradient id="iDI5g0V" cx="0" cy="0" r="1" gradientTransform="matrix(-.97508 .53473 -.2619 -.47757 12.8 4.355)" gradientUnits="userSpaceOnUse"><stop class="td2tyjbuq"/><stop offset="1" class="t36lxpgxn"/></radialGradient><radialGradient id="i53KubP" cx="0" cy="0" r="1" gradientTransform="matrix(.62908 -.93084 .84184 .56893 11.778 5.412)" gradientUnits="userSpaceOnUse"><stop class="a7hrg2b7m"/><stop offset="1" class="kgfm8cpgt"/></radialGradient><radialGradient id="iEEEWSb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.01175 4.40623 -6.6297 -3.02692 18.026 4.74)" gradientUnits="userSpaceOnUse"><stop offset=".272" class="aet_92b8f"/><stop offset="1" class="rfjsk2b_a"/></radialGradient><radialGradient id="iWRW5Zd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.67579 8.23047 0 16.014 8.74)" gradientUnits="userSpaceOnUse"><stop class="yexd1o2nx"/><stop offset="1" class="ue47neksc"/></radialGradient><radialGradient id="ieWHizW" cx="0" cy="0" r="1" gradientTransform="rotate(154.043 10.593 5.217)scale(3.62333 .22378)" gradientUnits="userSpaceOnUse"><stop offset=".097" class="m7zijhbgc"/><stop offset="1" class="lkpz06t1a"/></radialGradient><radialGradient id="ihSSm7d" cx="0" cy="0" r="1" gradientTransform="rotate(61.663 .03 10.263)scale(2.48532 2.58254)" gradientUnits="userSpaceOnUse"><stop class="l4i7jj__c"/><stop offset="1" class="z2xtp70hc"/></radialGradient><radialGradient id="iBw0BYb" cx="0" cy="0" r="1" gradientTransform="matrix(2.95313 1.56248 -.1016 .19204 9.338 5.084)" gradientUnits="userSpaceOnUse"><stop offset=".387" class="pmc291bsf"/><stop offset="1" class="tjgrrcbfz"/></radialGradient><radialGradient id="ifeMfDb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15625 1.375 -.42997 -.36157 22.62 5.24)" gradientUnits="userSpaceOnUse"><stop offset=".2" class="vb43as5rm"/><stop offset="1" class="kvxx5e97u"/></radialGradient><radialGradient id="izm3X0b" cx="0" cy="0" r="1" gradientTransform="rotate(175.929 7.948 1.952)scale(1.10043 .71838)" gradientUnits="userSpaceOnUse"><stop class="bfog00mit"/><stop offset="1" class="tk7r3ryjq"/></radialGradient><radialGradient id="iZzVw3c" cx="0" cy="0" r="1" gradientTransform="matrix(-.96874 .53125 -.2602 -.47447 9.645 4.834)" gradientUnits="userSpaceOnUse"><stop class="td2tyjbuq"/><stop offset="1" class="t36lxpgxn"/></radialGradient><radialGradient id="ilaTEnd" cx="0" cy="0" r="1" gradientTransform="matrix(.625 -.9248 .83637 .56524 8.629 5.884)" gradientUnits="userSpaceOnUse"><stop class="a7hrg2b7m"/><stop offset="1" class="kgfm8cpgt"/></radialGradient><radialGradient id="i0wBymb" cx="0" cy="0" r="1" gradientTransform="matrix(-.96874 .53125 -.2602 -.47447 23.573 4.834)" gradientUnits="userSpaceOnUse"><stop class="td2tyjbuq"/><stop offset="1" class="t36lxpgxn"/></radialGradient><radialGradient id="i5B04wi" cx="0" cy="0" r="1" gradientTransform="matrix(.625 -.9248 .83637 .56524 22.557 5.884)" gradientUnits="userSpaceOnUse"><stop class="a7hrg2b7m"/><stop offset="1" class="kgfm8cpgt"/></radialGradient><radialGradient id="igxjaic" cx="0" cy="0" r="1" gradientTransform="rotate(-90 11.776 -4.218)scale(1.36805)" gradientUnits="userSpaceOnUse"><stop class="m8_9xackt"/><stop offset="1" class="sblhzud6f"/></radialGradient><radialGradient id="iH9PggR" cx="0" cy="0" r="1" gradientTransform="matrix(.88821 -.82696 .53708 .57686 16.426 6.66)" gradientUnits="userSpaceOnUse"><stop class="jxvb9w84e"/><stop offset="1" class="a-oylkk7f"/></radialGradient><radialGradient id="iHcrFqe" cx="0" cy="0" r="1" gradientTransform="matrix(-.72788 .60361 -.58534 -.70585 19.74 7.24)" gradientUnits="userSpaceOnUse"><stop class="wmixudboe"/><stop offset="1" class="bzekojbcn"/></radialGradient><radialGradient id="iNmQTwe" cx="0" cy="0" r="1" gradientTransform="matrix(-.72788 .60361 -.58534 -.70585 12.986 7.24)" gradientUnits="userSpaceOnUse"><stop class="wmixudboe"/><stop offset="1" class="bzekojbcn"/></radialGradient><radialGradient id="iD4RU4b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.10171 .60417 -.29591 -.5396 16.777 2.516)" gradientUnits="userSpaceOnUse"><stop class="td2tyjbuq"/><stop offset="1" class="t36lxpgxn"/></radialGradient><radialGradient id="iEeNFte" cx="0" cy="0" r="1" gradientTransform="matrix(.71079 -1.05173 .95117 .64282 15.621 3.709)" gradientUnits="userSpaceOnUse"><stop class="a7hrg2b7m"/><stop offset="1" class="kgfm8cpgt"/></radialGradient><filter id="iltwdgc" width="15.268" height="15.768" x="8.484" y="5.314" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3069"/></filter><filter id="i0beQ9Y" width="13.918" height="7.56" x="8.979" y="21.298" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3069" stdDeviation=".075"/></filter><filter id="ikup5RX" width="14.05" height="7.692" x="8.967" y="21.072" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.560784 0 0 0 0 0.364706 0 0 0 0 0.772549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3069"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.627451 0 0 0 0 0.498039 0 0 0 0 0.890196 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3069" result="effect2_innerShadow_4002_3069"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.345098 0 0 0 0 0.866667 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_3069" result="effect3_innerShadow_4002_3069"/></filter><filter id="iz1kL1c" width="10.238" height="6.794" x="10.485" y="18.818" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3069" stdDeviation=".325"/></filter><filter id="iqyMzkd" width="2.05" height="2.05" x="11.382" y="18.936" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy="-.05"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.654902 0 0 0 0 0.478431 0 0 0 0 0.447059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3069"/></filter><filter id="in5FNwb" width="2.1" height="2.1" x="11.932" y="20.744" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.756863 0 0 0 0 0.698039 0 0 0 0 0.74902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3069"/></filter><filter id="ilGVVIe" width="2.05" height="2.05" x="13.198" y="22.111" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.796078 0 0 0 0 0.72549 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3069"/></filter><filter id="itI4Rzc" width="2.05" height="2.05" x="14.995" y="22.596" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.796078 0 0 0 0 0.72549 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3069"/></filter><filter id="iKfbzLt" width="3.368" height="3.218" x="9.698" y="12.983" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.266667 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3069"/></filter><filter id="id9KLlM" width="3.218" height="3.468" x="19.211" y="12.733" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.0901961 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3069"/></filter><filter id="ieRh6lb" width="3.148" height="3.148" x="19.246" y="13.019" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3069" stdDeviation=".25"/></filter><filter id="iNloBUc" width="2.648" height="2.648" x="10.003" y="13.269" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3069" stdDeviation=".125"/></filter><filter id="itgscOb" width="10.191" height="11.127" x="10.898" y="9.686" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.0901961 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3069"/></filter><filter id="iSwCxuc" width="2.877" height="3.682" x="14.392" y="13.587" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3069" stdDeviation=".25"/></filter><filter id="inIKF4Z" width="2.377" height="3.182" x="14.804" y="13.699" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3069" stdDeviation=".125"/></filter><filter id="iYtVNOc" width="3.702" height="1.526" x="14.147" y="17.253" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3069" stdDeviation=".05"/></filter><filter id="ivylNBd" width="3.001" height="1.285" x="16.935" y="13.188" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3069"/></filter><filter id="iJjJLLb" width="3.001" height="1.285" x="12.05" y="13.188" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3069"/></filter><filter id="ikswBDc" width="2.453" height="1.091" x="12.185" y="11.764" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3069"/></filter><filter id="ix3Qfqc" width="2.453" height="1.091" x="17.602" y="11.764" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3069"/></filter><filter id="ifJaP6b" width=".787" height=".696" x="17.441" y="13.556" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3069" stdDeviation=".05"/></filter><filter id="ixptWLp" width=".891" height=".913" x="18.281" y="13.631" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3069" stdDeviation=".1"/></filter><filter id="iRPQVZV" width=".986" height="1.04" x="13.838" y="13.567" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3069" stdDeviation=".1"/></filter><filter id="iiXpqZd" width=".913" height=".705" x="13.083" y="13.547" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3069" stdDeviation=".05"/></filter><filter id="iwa1qcc" width="2.261" height=".978" x="17.633" y="11.886" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3069" stdDeviation=".1"/></filter><filter id="io6RD1d" width="2.461" height="1.178" x="12.081" y="11.787" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3069" stdDeviation=".1"/></filter><filter id="itV6mdd" width="4.412" height="4.713" x="9.539" y="7.551" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.341176 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3069"/><feGaussianBlur result="effect2_foregroundBlur_4002_3069" stdDeviation=".25"/></filter><filter id="i7DZAib" width="8.767" height="5.782" x="12.823" y="6.516" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3069"/><feGaussianBlur result="effect2_foregroundBlur_4002_3069" stdDeviation=".125"/></filter><filter id="iBRHAed" width="1.145" height="2.31" x="12.802" y="7.751" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3069" stdDeviation=".1"/></filter><filter id="id7gi8c" width="6.427" height="3.372" x="15.411" y="8.559" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3069" stdDeviation=".375"/></filter><filter id="iUeX6Nc" width="10.911" height="1.365" x="10.492" y="7.94" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3069" stdDeviation=".2"/></filter><filter id="ipnJ7Xd" width="2.517" height="1.953" x="11.339" y="5.217" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.619608 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3069"/></filter><filter id="ilSA0He" width="1.604" height="1.554" x="19.053" y="3.858" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.05"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.639216 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3069"/></filter><filter id="iQuE4rb" width="1.604" height="1.554" x="11.428" y="3.858" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.05"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.639216 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3069"/></filter><filter id="iu9cynd" width="13.93" height="5.045" x="9.049" y="3.592" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.811765 0 0 0 0 0.619608 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3069"/></filter><filter id="itZSccb" width="1.594" height="1.544" x="8.282" y="4.34" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.05"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.639216 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3069"/></filter><filter id="i2huQnx" width="1.544" height="1.544" x="22.21" y="4.34" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.788235 0 0 0 0 0.611765 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3069"/></filter><filter id="iFioCtc" width="3.152" height="3.152" x="14.222" y="5.693" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3069" stdDeviation=".25"/></filter><filter id="iFaGyqe" width="2.116" height="2.116" x="18.116" y="6.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3069" stdDeviation=".25"/></filter><filter id="ihXBA0b" width="2.116" height="2.116" x="11.363" y="6.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3069" stdDeviation=".25"/></filter><filter id="iyaTCUb" width="2.152" height="2.152" x="14.917" y="6.002" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.168627 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3069"/></filter><filter id="iBuga9c" width="1.116" height="1.166" x="18.812" y="6.79" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.619608 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3069"/></filter><filter id="ijMow7d" width="1.116" height="1.166" x="12.058" y="6.79" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.619608 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3069"/></filter><filter id="izOQrmc" width="6.248" height="3.259" x="15.987" y="3.525" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3069" stdDeviation=".025"/></filter><filter id="i6C6bJd" width="1.799" height="1.749" x="15.226" y="1.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.05"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.639216 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3069"/></filter><linearGradient id="itk2M7X" x1="20.686" x2="13.881" y1="7.64" y2="20.244" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="ikQH8cb" x1="8.354" x2="8.104" y1="29.819" y2="29.819" gradientUnits="userSpaceOnUse"><stop class="x8dk6bl6o"/><stop offset="1" class="g-8u40lzl"/></linearGradient><linearGradient id="iLkQkbd" x1="23.635" x2="23.842" y1="29.99" y2="29.99" gradientUnits="userSpaceOnUse"><stop class="qrto2_zpw"/><stop offset="1" class="z2_l0sbav"/></linearGradient><linearGradient id="iyormFc" x1="23.932" x2="11.557" y1="29.99" y2="29.99" gradientUnits="userSpaceOnUse"><stop class="k_ugj6bqp"/><stop offset="1" class="etwgthjom"/></linearGradient><linearGradient id="iAhj8Hn" x1="18.463" x2="13.276" y1="27.646" y2="20.99" gradientUnits="userSpaceOnUse"><stop class="y-c-j769e"/><stop offset="1" class="t9knx544b"/></linearGradient><linearGradient id="iB6tLsc" x1="9.682" x2="13.727" y1="21.713" y2="28.005" gradientUnits="userSpaceOnUse"><stop class="odnc1cb0i"/><stop offset="1" class="foqmp2bms"/></linearGradient><linearGradient id="ivZVDro" x1="17.516" x2="14.656" y1="21.115" y2="21.115" gradientUnits="userSpaceOnUse"><stop class="tt0m3dw5o"/><stop offset="1" class="hpwhw6buq"/></linearGradient><linearGradient id="ilABBKc" x1="8.808" x2="23.184" y1="19.402" y2="19.402" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="i30rZSc" x1="8.808" x2="23.184" y1="19.372" y2="19.372" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="i9SzZlc" x1="9.698" x2="12.658" y1="14.68" y2="14.68" gradientUnits="userSpaceOnUse"><stop class="z_wfxjr5n"/><stop offset="1" class="qenr6bbwz"/></linearGradient><linearGradient id="iY8oHlc" x1="15.054" x2="15.993" y1="15.924" y2="15.924" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="iXJWtYr" x1="15.993" x2="15.993" y1="16.723" y2="16.112" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></linearGradient><linearGradient id="i1Qjkub" x1="14.934" x2="15.395" y1="18.445" y2="17.733" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="i4DLCWc" x1="18.953" x2="18.639" y1="14.049" y2="14.243" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="il4USve" x1="14.555" x2="14.241" y1="14.049" y2="14.242" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iTZQTPe" x1="13.102" x2="13.646" y1="8.394" y2="9.668" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><linearGradient id="iUZ7Ske" x1="11.885" x2="13.229" y1="5.959" y2="5.912" gradientUnits="userSpaceOnUse"><stop class="pd0xkfcwk"/><stop offset="1" class="mjtjw9d9u"/></linearGradient><linearGradient id="iS293Ii" x1="16.745" x2="16.745" y1="8.709" y2="8.334" gradientUnits="userSpaceOnUse"><stop class="sc708_bbk"/><stop offset="1" class="i_l5iobrn"/></linearGradient><linearGradient id="iYpqpOA" x1="16.042" x2="22.167" y1="3.803" y2="5.631" gradientUnits="userSpaceOnUse"><stop class="rapvxtblm"/><stop offset=".144" class="phj38-blk"/><stop offset=".842" class="zxi6lwb9j"/><stop offset="1" class="nu4sh_bsg"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:princess-dark" /></template>
<style>
.a-oylkk7f {
  stop-color: var(--svg-color--fc586e, #FC586E);
  stop-opacity: 0;
}

.a3n886b5x {
  stop-color: var(--svg-color--907bd1, #907BD1);
  stop-opacity: 0;
}

.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.a6mi8bcxq {
  cx: 12.421px;
  cy: 7.589px;
  r: 0.558px;
  fill: var(--svg-color--d37b55, #D37B55);
}

.a7hrg2b7m {
  stop-color: var(--svg-color--dc9640, #DC9640);
}

.aet_92b8f {
  stop-color: var(--svg-color--edad5e, #EDAD5E);
}

.aj61gebdf {
  stop-color: var(--svg-color--4f322e, #4F322E);
}

.arn54kl4j {
  stop-color: var(--svg-color--3293cc, #3293CC);
}

.axbh60bsz {
  stop-color: var(--svg-color--6d4bc2, #6D4BC2);
  stop-opacity: 0;
}

.ayiod_bfg {
  stop-color: var(--svg-color--493033, #493033);
}

.bee5xpc4n {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.384 13.247c.653 0 1.205.45 1.355 1.058a.274.274 0 0 1-.268.341H17.24a.23.23 0 0 1-.227-.272c.126-.64.69-1.127 1.371-1.127");
}

.bfog00mit {
  stop-color: var(--svg-color--d79747, #D79747);
}

.bicb17dvp {
  fill: var(--svg-color--250a03, #250A03);
  d: path("M10.898 8.34h10.105v.565s-3.685-.565-10.105 0c-.013-.22 0-.565 0-.565");
}

.biu9whxny {
  stop-color: var(--svg-color--d69fd3, #D69FD3);
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bmln26pap {
  stop-color: var(--svg-color--7a5298, #7A5298);
}

.bp0jotlxe {
  stop-color: var(--svg-color--9c76eb, #9C76EB);
}

.buo7-obdy {
  fill: var(--svg-color--331b25, #331B25);
  d: path("m15.6 14.37l-.683 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.493-.377-.613 0");
}

.byw-t0bic {
  stop-color: var(--svg-color--d9a83d, #D9A83D);
}

.bzekojbcn {
  stop-color: var(--svg-color--3caef0, #3CAEF0);
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.cakm38t-m {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M17.135 14.024c.265-.467.669-.836 1.537-.836c.38 0 .747.105 1.073.369c.27.217.233.495.025.599l-.556.317c-.652-.21-1.373-.239-2.079-.45");
}

.cctx1cb1y {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
}

.ceou1rsni {
  stop-color: var(--svg-color--d3b0a8, #D3B0A8);
  stop-opacity: 0;
}

.cg61kj_fh {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m18.4 10.411l-1.426.263a.688.688 0 1 1-.125-1.365h2.34c1.385 0 1.843 1.395 1.9 1.872a3.15 3.15 0 0 0-2.69-.77");
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cm8_bn2mq {
  d: path("M20.256 5.712c.1.175.302.541.391.703l-1.515.755l-.902-.903l.902-.785c.114-.104.36-.294.582-.261c.248.036.417.272.542.49");
}

.crde6o_5i {
  stop-color: var(--svg-color--402824, #402824);
  stop-opacity: 0;
}

.cunr-1bwb {
  stop-color: var(--svg-color--7d48de, #7D48DE);
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cy4ujdbiq {
  stop-color: var(--svg-color--e7c7ff, #E7C7FF);
  stop-opacity: 0;
}

.d0fyzsbqc {
  stop-color: var(--svg-color--3b232b, #3B232B);
  stop-opacity: 0;
}

.d7gnwkbua {
  stop-color: var(--svg-color--e2c0ab, #E2C0AB);
  stop-opacity: 0;
}

.da38a73_c {
  stop-color: var(--svg-color--b99bb6, #B99BB6);
}

.dakdtmo8r {
  stop-color: var(--svg-color--37cbf4, #37CBF4);
}

.dl-fg6u5t {
  d: path("M15.39 6.802c-1.133-.25-2.15.88-2.267 1.299c1.052 3.545 3.713 3.35 6.34 3.059c1.572-.175 1.743.542 1.877.888c0-3.933-3.344-4.67-5.922-5.24z");
}

.do3fwrbgr {
  stop-color: var(--svg-color--3f243b, #3F243B);
}

.dvfwus5_j {
  cx: 13.54px;
  cy: 13.9px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.dvuac4bxb {
  cx: 15.995px;
  cy: 23.596px;
  r: 1px;
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e304mibzr {
  d: path("M21.187 25.801a3.502 3.502 0 1 0 7.004 0c0-1.934-1.568-3.389-3.502-3.389c-3.782 0-3.502 1.455-3.502 3.389");
}

.ean9ofhjo {
  r: 1px;
}

.eapmb-b-r {
  stop-color: var(--svg-color--c0abb3, #C0ABB3);
}

.ebp3oh52k {
  d: path("M18.177 13.519a.892.892 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.128");
}

.eh1sqyczn {
  stop-color: var(--svg-color--d69fd3, #D69FD3);
  stop-opacity: 0;
}

.esixkvbpd {
  stop-color: var(--svg-color--cc9dd5, #CC9DD5);
}

.etwgthjom {
  stop-color: var(--svg-color--755cc0, #755CC0);
}

.ez8x1mb2s {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m19.725 12.357l-.138.23za.268.268 0 0 1-.276.46l-.005-.002l-.021-.012l-.091-.047a3 3 0 0 0-.343-.135a2.3 2.3 0 0 0-1.072-.091a.268.268 0 0 1-.093-.529c.513-.09.988.001 1.328.11a3.3 3.3 0 0 1 .559.238l.01.005l.002.002z");
}

.f6uv1pf_h {
  stop-color: var(--svg-color--5e4543, #5E4543);
  stop-opacity: 0;
}

.f82mfcbsw {
  stop-color: var(--svg-color--371e27, #371E27);
}

.fbn9skb1g {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.102 8.05c.023.244.234 1.157.544 1.71");
}

.fg8vwkbfq {
  stop-color: var(--svg-color--fce9ff, #FCE9FF);
}

.fga1l482e {
  stop-color: var(--svg-color--efd2c5, #EFD2C5);
  stop-opacity: 0;
}

.fkfx3o27i {
  stop-color: var(--svg-color--cfacbc, #CFACBC);
  stop-opacity: 0;
}

.foqmp2bms {
  stop-color: var(--svg-color--705693, #705693);
  stop-opacity: 0;
}

.fp6zmm73k {
  stop-color: var(--svg-color--5e4543, #5E4543);
}

.fpyoctiow {
  stop-color: var(--svg-color--dbaaf7, #DBAAF7);
}

.fr4aurb9m {
  stop-color: var(--svg-color--e6d7e6, #E6D7E6);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.ftn-nj88l {
  stop-color: var(--svg-color--cca389, #CCA389);
}

.fus8l7b8h {
  d: path("M11.73 5.712c-.1.175-.302.541-.39.703l1.514.755l.902-.903l-.902-.785c-.114-.104-.359-.294-.582-.261c-.247.036-.417.272-.542.49");
}

.g-8u40lzl {
  stop-color: var(--svg-color--7045c9, #7045C9);
  stop-opacity: 0;
}

.g049h7flb {
  stop-color: var(--svg-color--8461d2, #8461D2);
}

.g0bd9ib2e {
  d: path("M18.972 14.293a.84.84 0 0 0-.231-.462l-.26.285l.117.228z");
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.g6hzctbpu {
  cx: 12.432px;
  cy: 19.986px;
  r: 1px;
}

.g7x6q-lxe {
  stop-color: var(--svg-color--c98b19, #C98B19);
  stop-opacity: 0;
}

.gag6ovb3k {
  stop-color: var(--svg-color--d0b5b2, #D0B5B2);
}

.gcrmpdfop {
  stop-color: var(--svg-color--585352, #585352);
}

.gfzgh5bel {
  d: path("M16.018 19.373h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.gl9okfban {
  stop-color: var(--svg-color--634d4b, #634D4B);
  stop-opacity: 0;
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gsgx-m-kb {
  stop-color: var(--svg-color--e0ccec, #E0CCEC);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h-ngu4b2o {
  fill: var(--svg-color--2a0219, #2A0219);
  d: path("M15.998 17.816a3 3 0 0 1-1.421-.344c-.14-.073-.292.088-.203.22a1.932 1.932 0 0 0 3.25 0c.088-.137-.063-.293-.204-.22c-.411.22-.896.344-1.422.344");
}

.h55xk6bmz {
  stop-color: var(--svg-color--7a5fc2, #7A5FC2);
  stop-opacity: 0;
}

.h88_-5b3g {
  cx: 15.798px;
  cy: 7.269px;
  r: 1.076px;
  fill: var(--svg-color--d37b55, #D37B55);
}

.hf_fcmwun {
  d: path("M14.624 14.306c0-.288-.234-.48-.298-.539l-.288.279l.178.361z");
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hoqi9e01c {
  stop-color: var(--svg-color--845bd7, #845BD7);
}

.hpwhw6buq {
  stop-color: var(--svg-color--271718, #271718);
}

.huvog8bmh {
  d: path("m9.05 5.572l1.272 2.876a.15.15 0 0 0 .138.09h11.056a.15.15 0 0 0 .136-.088l1.327-2.878l-.187-.437c-.438.19-1.124.521-1.736.816c-.43.207-.824.397-1.07.508c-.403.183-.857.087-1.046-.125c-.25-.28-.711-.81-1.14-1.305c-.35-.402-.677-.779-.852-.976c-.342-.386-.722-.453-.914-.46l-.02-.001h-.02c-.192.007-.571.075-.913.46c-.175.198-.503.575-.852.977c-.43.494-.89 1.025-1.14 1.305c-.19.212-.643.308-1.047.125a64 64 0 0 1-1.07-.508a62 62 0 0 0-1.735-.816z");
}

.hv46-obcm {
  stop-color: var(--svg-color--c98b19, #C98B19);
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.i_l5iobrn {
  stop-color: var(--svg-color--f9711e, #F9711E);
  stop-opacity: 0;
}

.if8ggt7lg {
  stop-color: var(--svg-color--6046a6, #6046A6);
  stop-opacity: 0;
}

.ii093lbht {
  d: path("M10.924 8.604c.566-.599 1.636-.6 2.13-.51l.397 1.29c-.253-.039-.479.05-.668.235c-.449 1.26-1.99 1.955-2.704 2.145c-.148-1.492.109-2.38.845-3.16");
}

.inuz7fbaa {
  fill-rule: evenodd;
  d: path("m14.07 27.625l-4.954-5.688a.2.2 0 0 1 .025-.286l.536-.434a.2.2 0 0 1 .276.024l4.949 5.664c.558.566 1.784.464 2.19.002l4.939-5.657a.2.2 0 0 1 .273-.026l.537.418a.2.2 0 0 1 .027.289l-4.946 5.697c-1.032 1.26-2.673 1.37-3.852-.003");
}

.itk3z-5ip {
  stop-color: var(--svg-color--d59b33, #D59B33);
}

.ivh048xhs {
  fill-rule: evenodd;
  d: path("M23.178 16.002c.213-.435.324-.92.324-1.427c0-.467-.096-.905-.268-1.305h.005a3 3 0 0 0-.281-.513l-.002-.003a3.24 3.24 0 0 1-.526-1.771v-.01a3.3 3.3 0 0 0-3.3-3.3a.54.54 0 0 1-.455-.232a3.3 3.3 0 0 0-2.682-1.377a3.3 3.3 0 0 0-2.682 1.377a.56.56 0 0 1-.455.233h-.085a3.3 3.3 0 0 0-3.214 3.299v.01a3.24 3.24 0 0 1-.527 1.77l-.002.005a3.3 3.3 0 0 0-.22 3.244c.07.142.07.314 0 .456a3.213 3.213 0 0 0 2.894 4.625h8.582a3.213 3.213 0 0 0 3.218-3.219c0-.506-.121-.981-.324-1.406a.51.51 0 0 1 0-.456m-12.26-2.672h-.012l1.199 2.355c.123 2.803 1.217 0 3.888 0c2.672 0 3.836 3.12 3.96.317l1.136-3.197c-.054-1.245-.956-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.19-1.673a.264.264 0 0 0-.461.05l-.082.195c-.226.56-.656.99-1.19 1.234l-.05.02l-.052.02c-.236.123-.79.49-.81 1.44l.01.306z");
}

.iw3rcybbt {
  fill: var(--svg-color--2f2428, #2F2428);
  d: path("M15.39 6.802c-1.133-.25-2.15.88-2.267 1.299c1.052 3.545 3.713 3.35 6.34 3.059c1.572-.175 1.743.542 1.877.888c0-3.933-3.344-4.67-5.922-5.24z");
}

.j-hgq5bil {
  stop-color: var(--svg-color--d5c2e3, #D5C2E3);
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j47fkwbxf {
  stop-color: var(--svg-color--4f3639, #4F3639);
}

.j707yuzrq {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.602 13.247c-.653 0-1.205.45-1.355 1.058a.275.275 0 0 0 .268.341h2.231a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.371-1.127");
}

.j8q5y3jei {
  stop-color: var(--svg-color--d59b33, #D59B33);
  stop-opacity: 0;
}

.j9-kjkbge {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M14.142 12.22c-.323-.079-1.125-.04-1.661.344");
}

.jhbwcacjr {
  stop-color: var(--svg-color--7143c9, #7143C9);
  stop-opacity: 0;
}

.jids0zpwm {
  stop-color: var(--svg-color--59403d, #59403D);
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jxvb9w84e {
  stop-color: var(--svg-color--fc586e, #FC586E);
}

.jypakik4k {
  stop-color: var(--svg-color--8c69d4, #8C69D4);
}

.k_ugj6bqp {
  stop-color: var(--svg-color--876ecd, #876ECD);
}

.k3jt88b8m {
  stop-color: var(--svg-color--866bca, #866BCA);
  stop-opacity: 0;
}

.k5zu23s6k {
  stop-color: var(--svg-color--9c78ec, #9C78EC);
}

.k7acx4bkv {
  stop-color: var(--svg-color--563c39, #563C39);
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kcmmk5bxb {
  d: path("M26.833 27.014c.388.97.698 2.388.805 2.976h-4.953v-2.976z");
}

.kf6yzhcxx {
  stop-color: var(--svg-color--6046a6, #6046A6);
}

.kgfm8cpgt {
  stop-color: var(--svg-color--dc9640, #DC9640);
  stop-opacity: 0;
}

.kijt7rb5s {
  stop-color: var(--svg-color--b99bb6, #B99BB6);
  stop-opacity: 0;
}

.kqlr11b-y {
  stop-color: var(--svg-color--d4c1d3, #D4C1D3);
}

.kr7xbubfl {
  stop-color: var(--svg-color--dcc4d2, #DCC4D2);
  stop-opacity: 0;
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kth1ncger {
  stop-color: var(--svg-color--9376c4, #9376C4);
  stop-opacity: 0;
}

.kvxx5e97u {
  stop-color: var(--svg-color--ce8f45, #CE8F45);
  stop-opacity: 0;
}

.kx-k2bm9u {
  fill: var(--svg-color--000, #000);
  d: path("M17.666 14.411c0-.284.227-.511.511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.235");
}

.l_ewlebdc {
  d: path("M10.906 13.33h.012l-.01-.266l-.01-.306c.02-.948.574-1.316.81-1.438l.051-.02q.028-.013.051-.021A2.3 2.3 0 0 0 13 10.044l.082-.194a.264.264 0 0 1 .461-.05a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.082.087 1.136 1.332l-.12 3.073c-.123 2.802-2.311 4.684-4.983 4.684c-2.67 0-4.86-1.882-4.983-4.684z");
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l4i7jj__c {
  stop-color: var(--svg-color--daa24e, #DAA24E);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lbkb08b7q {
  cx: 19.175px;
  cy: 7.589px;
  r: 0.558px;
  fill: var(--svg-color--d37b55, #D37B55);
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkpz06t1a {
  stop-color: var(--svg-color--c89751, #C89751);
  stop-opacity: 0;
}

.lkxhe0bym {
  stop-color: var(--svg-color--987ae1, #987AE1);
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.lqhq5vk7o {
  stop-color: var(--svg-color--6d4bc2, #6D4BC2);
}

.ls12e09pb {
  stop-color: var(--svg-color--fff8ff, #FFF8FF);
}

.lvm1e4qso {
  cx: 12.616px;
  cy: 7.399px;
  r: 0.558px;
}

.lxwln9mzq {
  stop-color: var(--svg-color--7143c9, #7143C9);
}

.m6mmhsf1n {
  stop-color: var(--svg-color--3f243b, #3F243B);
  stop-opacity: 0;
}

.m7zijhbgc {
  stop-color: var(--svg-color--c89751, #C89751);
}

.m8_9xackt {
  stop-color: var(--svg-color--e7175a, #E7175A);
}

.mam21uzwo {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.998 17.816a3 3 0 0 1-1.421-.344c-.14-.073-.292.088-.203.22a1.932 1.932 0 0 0 3.25 0c.088-.137-.063-.293-.204-.22c-.411.22-.896.344-1.422.344Z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mjrstybho {
  stop-color: var(--svg-color--635385, #635385);
}

.mjtjw9d9u {
  stop-color: var(--svg-color--f2bd5c, #F2BD5C);
}

.mobf8tbpp {
  fill: var(--svg-color--301b26, #301B26);
  fill-rule: evenodd;
  d: path("M12.743 21.2a.98.98 0 1 0-.766.218a.98.98 0 0 0 .986 1.664a.98.98 0 0 0 1.668 1.01a.98.98 0 0 0 1.947 0a.978.978 0 0 0 1.766-.583a1 1 0 0 0-.098-.428a.978.978 0 0 0 1.337-.912a.98.98 0 0 0-.351-.751a.98.98 0 1 0-.766-.218a.98.98 0 0 0-.744 1.397a.98.98 0 0 0-1.331.803a.978.978 0 0 0-1.573 0a.98.98 0 0 0-1.332-.803a.98.98 0 0 0-.744-1.397");
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.mxq0h6ljd {
  cx: 19.805px;
  cy: 4.66px;
  r: 0.752px;
}

.n-7gz4alz {
  stop-color: var(--svg-color--53d8f2, #53D8F2);
}

.n0x7ebc8c {
  cx: 14.198px;
  cy: 23.111px;
  r: 1px;
}

.n261g_b5l {
  d: path("M16.348 19.373c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.n6d_jnr9j {
  d: path("M5.167 27.014c-.388.97-.698 2.388-.805 2.976h4.953v-2.976z");
}

.n6j5avbvg {
  stop-color: var(--svg-color--ab877b, #AB877B);
}

.n8ysctycz {
  stop-color: var(--svg-color--2b151b, #2B151B);
}

.na-ss_5-a {
  width: 4.359px;
  height: 4.703px;
  x: 13.823px;
  y: 17.225px;
  rx: 2px;
}

.nc960pbfz {
  d: path("M18.112 13.707c.063.085-.07.189-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.389-.05");
}

.nd--cppfl {
  stop-color: var(--svg-color--585352, #585352);
  stop-opacity: 0;
}

.nduru5xwu {
  fill: var(--svg-color--35252b, #35252B);
  d: path("M11.327 15.667a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.nj0s1tj2o {
  stop-color: var(--svg-color--c88c35, #C88C35);
}

.nu4sh_bsg {
  stop-color: var(--svg-color--f2bb64, #F2BB64);
  stop-opacity: 0;
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.o6_n3pbob {
  cx: 9.905px;
  cy: 7.313px;
  r: 0.558px;
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.o8dw4p7vp {
  stop-color: var(--svg-color--ba93b0, #BA93B0);
  stop-opacity: 0;
}

.o9ez09qax {
  stop-color: var(--svg-color--d3a150, #D3A150);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odnc1cb0i {
  stop-color: var(--svg-color--705693, #705693);
}

.oj0sgcj4p {
  stop-color: var(--svg-color--b78eae, #B78EAE);
}

.oo7p4ebqa {
  cx: 12.932px;
  cy: 21.744px;
  r: 1px;
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.ovkwvebhl {
  fill: var(--svg-color--7359bc, #7359BC);
  fill-rule: evenodd;
  d: path("m14.049 27.743l-4.871-5.548a.194.194 0 0 1 .024-.28l.527-.423a.2.2 0 0 1 .272.023l4.865 5.525c.549.552 2.02.666 2.418.215l4.782-5.522a.2.2 0 0 1 .27-.026l.336.2a.194.194 0 0 1 .027.281l-4.864 5.558c-1.014 1.229-2.627 1.336-3.786-.003");
}

.owyqbq1bg {
  stop-color: var(--svg-color--efd2c5, #EFD2C5);
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pd0xkfcwk {
  stop-color: var(--svg-color--f1ba66, #F1BA66);
}

.phj38-blk {
  stop-color: var(--svg-color--efb65d, #EFB65D);
}

.pj2ff5nxp {
  stop-color: var(--svg-color--2d181a, #2D181A);
  stop-opacity: 0;
}

.pj5su6bsv {
  stop-color: var(--svg-color--ab877b, #AB877B);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmc291bsf {
  stop-color: var(--svg-color--e3b560, #E3B560);
}

.pmg10qb6b {
  stop-color: var(--svg-color--fffaff, #FFFAFF);
}

.pyjhqsreq {
  d: path("M8.338 22.428c1.11-1.089 4.193-3.219 7.649-3.219s6.539 2.13 7.648 3.219v7.562H8.338z");
}

.q-wkihbps {
  stop-color: var(--svg-color--e5c8e2, #E5C8E2);
}

.q0597ob7u {
  cx: 9.029px;
  cy: 5.137px;
  r: 0.747px;
}

.q8l1y6b0l {
  cx: 22.089px;
  cy: 7.324px;
  r: 0.558px;
}

.qenr6bbwz {
  stop-color: var(--svg-color--2a1c1f, #2A1C1F);
}

.qm132ccsa {
  stop-color: var(--svg-color--655251, #655251);
  stop-opacity: 0;
}

.qrto2_zpw {
  stop-color: var(--svg-color--814fe0, #814FE0);
}

.qrzlg2j4q {
  stop-color: var(--svg-color--d3a150, #D3A150);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r7y8-fuqh {
  fill: var(--svg-color--272528, #272528);
  d: path("M14.851 14.024c-.265-.467-.669-.836-1.537-.836c-.38 0-.747.105-1.073.369c-.269.217-.233.495-.025.599l.556.317c.652-.21 1.373-.239 2.08-.45");
}

.rapvxtblm {
  stop-color: var(--svg-color--efb65d, #EFB65D);
  stop-opacity: 0;
}

.re4dv2b7j {
  stroke-width: var(--svg-stroke-width--0-08px, 0.08px);
  d: path("M16.042 3.615c.098.01.432.13.664.348c.23.219 1.53 1.71 2.144 2.383c.207.226.568.502 1.2.246c.63-.256 1.674-.774 2.117-1");
}

.rfjsk2b_a {
  stop-color: var(--svg-color--e59e51, #E59E51);
}

.rg4_m7b_n {
  cx: 19.37px;
  cy: 7.399px;
  r: 0.558px;
}

.rlxb2vbdo {
  stop-color: var(--svg-color--7a5fc2, #7A5FC2);
}

.rmmi4abgs {
  stop-color: var(--svg-color--371d1f, #371D1F);
  stop-opacity: 0;
}

.rqzct4dku {
  cx: 15.993px;
  cy: 7.078px;
  r: 1.076px;
}

.rr9pqccyi {
  stop-color: var(--svg-color--f5dff7, #F5DFF7);
}

.rxbeu-beb {
  fill: var(--svg-color--20171a, #20171A);
  d: path("M10.924 8.604c.566-.599 1.636-.6 2.13-.51l.397 1.29c-.253-.039-.479.05-.668.235c-.449 1.26-1.99 1.955-2.704 2.145c-.148-1.492.109-2.38.845-3.16");
}

.s9u3_wbrp {
  stop-color: var(--svg-color--402824, #402824);
}

.sbez_4byf {
  stop-color: var(--svg-color--945cee, #945CEE);
}

.sblhzud6f {
  stop-color: var(--svg-color--e11f40, #E11F40);
}

.sc708_bbk {
  stop-color: var(--svg-color--f9711e, #F9711E);
}

.sdufqstmc {
  stop-color: var(--svg-color--2d181a, #2D181A);
}

.seh-d5byd {
  stop-color: var(--svg-color--442e2e, #442E2E);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.spc75r5za {
  stop-color: var(--svg-color--805fc9, #805FC9);
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.sspmcqbor {
  d: path("M20.82 16.202a1.61 1.61 0 1 0 0-3.219a1.61 1.61 0 0 0 0 3.219");
}

.st2gozbew {
  stop-color: var(--svg-color--4f3639, #4F3639);
  stop-opacity: 0;
}

.sti3oxbeq {
  stop-color: var(--svg-color--33a6c5, #33A6C5);
}

.t18jwhbnk {
  stop-color: var(--svg-color--402a2a, #402A2A);
}

.t2krvpb6g {
  stop-color: var(--svg-color--e3cde6, #E3CDE6);
}

.t36lxpgxn {
  stop-color: var(--svg-color--e5ba4b, #E5BA4B);
}

.t5djkhb4t {
  stop-color: var(--svg-color--655251, #655251);
}

.t70q9k_cc {
  stop-color: var(--svg-color--814fdf, #814FDF);
}

.t9knx544b {
  stop-color: var(--svg-color--835fc6, #835FC6);
}

.tbk29ybzd {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.112 13.707c.063.085-.07.189-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.389-.05");
}

.td2tyjbuq {
  stop-color: var(--svg-color--fdd172, #FDD172);
}

.tfsbwvbnl {
  stop-color: var(--svg-color--ebccff, #EBCCFF);
}

.tjgrrcbfz {
  stop-color: var(--svg-color--e3b560, #E3B560);
  stop-opacity: 0;
}

.tk7r3ryjq {
  stop-color: var(--svg-color--d79747, #D79747);
  stop-opacity: 0;
}

.tknr5ybzo {
  stop-color: var(--svg-color--bd9b8f, #BD9B8F);
}

.tljjlvbsz {
  stop-color: var(--svg-color--442e2e, #442E2E);
  stop-opacity: 0;
}

.tobb-5f3c {
  cx: 22.957px;
  cy: 5.137px;
  r: 0.747px;
}

.toy3i-56q {
  stop-color: var(--svg-color--907bd1, #907BD1);
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.tt-kr1b-n {
  d: path("M20.82 15.667a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.tt0m3dw5o {
  stop-color: var(--svg-color--473031, #473031);
}

.u-wvucrhg {
  stop-color: var(--svg-color--c3a8aa, #C3A8AA);
}

.ue47neksc {
  stop-color: var(--svg-color--e77953, #E77953);
  stop-opacity: 0;
}

.uegyi0cvz {
  cx: 12.18px;
  cy: 4.66px;
  r: 0.752px;
}

.uhu16ny2z {
  fill: var(--svg-color--4c3637, #4C3637);
  d: path("M20.82 15.667a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.uo29cubui {
  cx: 16.076px;
  cy: 2.859px;
  r: 0.85px;
}

.uzx-du17j {
  stop-color: var(--svg-color--945cee, #945CEE);
  stop-opacity: 0;
}

.v2xpqhbrh {
  stop-color: var(--svg-color--402a29, #402A29);
}

.v5l-j3bvb {
  d: path("M11.308 16.202a1.61 1.61 0 1 0 0-3.219a1.61 1.61 0 0 0 0 3.219");
}

.v8gtn-b7b {
  stop-color: var(--svg-color--53d8f2, #53D8F2);
  stop-opacity: 0;
}

.v8pgeumfm {
  fill: var(--svg-color--000, #000);
  d: path("M14.32 14.411a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .061-.235");
}

.vavjlxdpa {
  stop-color: var(--svg-color--cfbadc, #CFBADC);
}

.vb43as5rm {
  stop-color: var(--svg-color--ce8f45, #CE8F45);
}

.vfe9g3b6u {
  stop-color: var(--svg-color--9376c4, #9376C4);
}

.vl7hh0bdy {
  d: path("m9.539 21.45l5.55 6.493h2.015l5.453-6.407c-1.49-1.075-3.92-2.327-6.57-2.327c-2.579 0-4.95 1.186-6.448 2.24");
}

.vlr1jy-qw {
  stop-color: var(--svg-color--ce9fd2, #CE9FD2);
  stop-opacity: 0;
}

.voqk07baz {
  stop-color: var(--svg-color--b89174, #B89174);
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.w1-gvmrbk {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m12.596 12.815l-.005.002a.268.268 0 0 1-.276-.46h.002l.003-.003l.01-.005l.032-.018l.116-.059a3 3 0 0 1 .41-.162c.34-.108.815-.2 1.328-.109a.268.268 0 1 1-.093.529a2.3 2.3 0 0 0-1.072.091a3 3 0 0 0-.434.182z");
}

.w4tdaku_b {
  fill: var(--svg-color--4a302d, #4A302D);
  d: path("m15.61 14.231l-.53 1.7a.54.54 0 0 0 .52.7h.786a.54.54 0 0 0 .52-.7l-.53-1.7c-.114-.376-.646-.376-.765 0");
}

.w6eefwb-r {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.933 12.22c.322-.079 1.124-.04 1.66.344");
}

.w78c_mbga {
  d: path("M10.813 25.801a3.502 3.502 0 1 1-7.004 0c0-1.934 1.568-3.389 3.502-3.389c3.781 0 3.502 1.455 3.502 3.389");
}

.wb78_hxsc {
  stop-color: var(--svg-color--6a5956, #6A5956);
}

.wg_j-qo3v {
  d: path("M11.327 15.667a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.wgpm0ibqw {
  stop-color: var(--svg-color--43272a, #43272A);
  stop-opacity: 0;
}

.wmixudboe {
  stop-color: var(--svg-color--50d5fe, #50D5FE);
}

.wq49cmbeq {
  cx: 13.54px;
  cy: 13.9px;
  rx: 0.39px;
  ry: 0.197px;
}

.x_sue_b_g {
  stop-color: var(--svg-color--634d4b, #634D4B);
}

.x5-3y6xrq {
  stop-color: var(--svg-color--2783b8, #2783B8);
}

.x7h3p2bdy {
  stop-color: var(--svg-color--533632, #533632);
  stop-opacity: 0;
}

.x8dk6bl6o {
  stop-color: var(--svg-color--7045c9, #7045C9);
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xf3nhjbpw {
  stop-color: var(--svg-color--fff6ff, #FFF6FF);
}

.xfmbn4_bb {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
  stop-opacity: 0;
}

.xg0mdnbqj {
  stop-color: var(--svg-color--e2c0ab, #E2C0AB);
}

.xjhzw6b4m {
  stop-color: var(--svg-color--ce9fd2, #CE9FD2);
}

.xkhh7vb2n {
  stop-color: var(--svg-color--371e27, #371E27);
  stop-opacity: 0;
}

.xkvq89bye {
  d: path("M13.809 13.519a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.xpqto8b3q {
  stop-color: var(--svg-color--e8d9e7, #E8D9E7);
  stop-opacity: 0;
}

.xuyenabum {
  stop-color: var(--svg-color--371d1f, #371D1F);
}

.y-c-j769e {
  stop-color: var(--svg-color--9869eb, #9869EB);
}

.yb1xaiemt {
  stop-color: var(--svg-color--7a5298, #7A5298);
  stop-opacity: 0;
}

.ybvm9tprh {
  stop-color: var(--svg-color--594d4d, #594D4D);
}

.yexd1o2nx {
  stop-color: var(--svg-color--e77953, #E77953);
}

.yidq71bjl {
  stop-color: var(--svg-color--c3a8aa, #C3A8AA);
  stop-opacity: 0;
}

.yind2xb3b {
  stop-color: var(--svg-color--7d48de, #7D48DE);
  stop-opacity: 0;
}

.yv4uycbmh {
  stop-color: var(--svg-color--43272a, #43272A);
}

.yxwqgvbem {
  stop-color: var(--svg-color--594d4d, #594D4D);
  stop-opacity: 0;
}

.z_f48dbjf {
  stop-color: var(--svg-color--735fab, #735FAB);
  stop-opacity: 0;
}

.z_wfxjr5n {
  stop-color: var(--svg-color--392526, #392526);
}

.z1-7jowoz {
  stop-color: var(--svg-color--d09731, #D09731);
}

.z2_l0sbav {
  stop-color: var(--svg-color--814fe0, #814FE0);
  stop-opacity: 0;
}

.z2xtp70hc {
  stop-color: var(--svg-color--daa24e, #DAA24E);
  stop-opacity: 0;
}

.z54rox6ux {
  stop-color: var(--svg-color--8a5ee4, #8A5EE4);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.z9cu3vbra {
  stop-color: var(--svg-color--fff7ff, #FFF7FF);
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zn9diyb1a {
  stop-color: var(--svg-color--8569c9, #8569C9);
}

.zxi6lwb9j {
  stop-color: var(--svg-color--f2bb64, #F2BB64);
}

.zz4mcgrzh {
  stop-color: var(--svg-color--59403d, #59403D);
  stop-opacity: 0;
}

.zzkdlsoov {
  d: path("m15.61 14.231l-.53 1.7a.54.54 0 0 0 .52.7h.786a.54.54 0 0 0 .52-.7l-.53-1.7c-.114-.376-.646-.376-.765 0");
}

</style>
