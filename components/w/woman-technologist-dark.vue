<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ib6uWLY)"><path fill="url(#ikN729b)" clip-rule="evenodd" class="bi4mzcbhr"/><path fill="url(#imoHmCd)" clip-rule="evenodd" class="bi4mzcbhr"/><path fill="url(#iWU5mNc)" clip-rule="evenodd" class="bi4mzcbhr"/><path fill="url(#iqFUw3i)" clip-rule="evenodd" class="bi4mzcbhr"/><path fill="url(#iTn0Osd)" clip-rule="evenodd" class="bi4mzcbhr"/><path fill="url(#i5d56qb)" clip-rule="evenodd" class="bi4mzcbhr"/><path fill="url(#iX13Dbc)" clip-rule="evenodd" class="bi4mzcbhr"/><path fill="url(#iswmVtG)" clip-rule="evenodd" class="bi4mzcbhr"/><path fill="url(#iRFq3zd)" clip-rule="evenodd" class="bi4mzcbhr"/><path fill="url(#ix1Cwid)" clip-rule="evenodd" class="bi4mzcbhr"/><path fill="url(#iaepPwc)" clip-rule="evenodd" class="bi4mzcbhr"/><path fill="url(#ieQOEad)" clip-rule="evenodd" class="bi4mzcbhr"/></g><path fill="url(#iqrRyTh)" class="lp-jspbxv"/><path fill="url(#iqexxae)" class="a_spo2cop"/><g filter="url(#i2OMQNd)"><path fill="url(#ixpxIdb)" class="glnfjzbdq"/></g><g filter="url(#iqwk5Hc)"><path fill="url(#iD9pUqb)" class="kmbgvqb8x"/><path fill="url(#iFlZvKe)" class="kmbgvqb8x"/></g><g filter="url(#irrwkqb)"><path class="xfko61b4t"/><path fill="url(#iGri1lc)" class="j9z76nbfg"/></g><g filter="url(#ikP3lbd)"><path class="tuiticc0a"/><path fill="url(#iQ8lIac)" class="eur0b6bpq"/></g><g filter="url(#iDb2Rwc)"><path fill="url(#imY1N1c)" class="f443huont"/><path fill="url(#i9CVBwc)" class="f443huont"/><path fill="url(#i4gusDc)" class="f443huont"/><path fill="url(#izdygDb)" class="f443huont"/><path fill="url(#i6671uc)" class="f443huont"/><path fill="url(#iEvJXje)" class="f443huont"/><path fill="url(#ixvo2oP)" class="f443huont"/><path fill="url(#ic4df0K)" class="f443huont"/></g><path fill="url(#iwENnCx)" class="f443huont"/><path fill="url(#iMXDyxc)" class="f443huont"/><g filter="url(#ioPBuAd)"><path class="pxpgdvb7j"/></g><g filter="url(#iIaEQOb)"><path class="d1szpqbot"/><path fill="url(#iwV9Emd)" class="qqb9fccqv"/><path fill="url(#icyXqdc)" class="qqb9fccqv"/><path fill="url(#i2uhSAd)" class="qqb9fccqv"/><path fill="url(#iIBv6de)" class="qqb9fccqv"/></g><path fill="url(#itBRUte)" class="qqb9fccqv"/><path fill="url(#i20Mo4p)" class="qqb9fccqv"/><path stroke="url(#i0Vfwyd)" class="k0f91xc-h"/><g filter="url(#i46oqog)"><path class="d5cumfbeh"/></g><g filter="url(#i23j7qd)"><path class="mah7hvb-b"/></g><g filter="url(#ia87Tjd)"><path class="y-0wdxbdo"/></g><g filter="url(#iawFwJb)"><path clip-rule="evenodd" class="ez8-_ybbt"/></g><path class="uf5rerbdy"/><path fill="url(#iE8oPbX)" class="y1gxombgs"/><path class="jo8lxfo6c"/><g filter="url(#iWfS1Sb)"><path class="segtjobkz"/><path fill="url(#iNO0awb)" class="zhb5rly-q"/></g><g filter="url(#iLW339c)"><path fill="url(#ieaxaTb)" class="n3eifgatt"/></g><path class="i6bji0ert"/><path fill="url(#iortVcX)" class="w80gnzyby"/><path class="ebv6t9bbq"/><g filter="url(#iVk48sd)"><path fill="url(#iJg10Sc)" class="xuflm6bwg"/></g><g filter="url(#i64guSz)"><ellipse transform="rotate(-27.914 13.547 9.816)" class="pdyfmt2wz"/><ellipse fill="url(#iBTecCL)" transform="rotate(-27.914 13.547 9.816)" class="w2q6f6-7d"/></g><g filter="url(#iChkVJy)"><path class="i6h4x1urm"/></g><g filter="url(#ij3PFod)"><path class="otj2-4byw"/></g><g filter="url(#isVP8zY)"><path class="qsd57_bml"/><path fill="url(#iOZxwjr)" class="ntb7br0fn"/></g><g filter="url(#iWgzrYd)"><path class="xrzdifaqt"/><path fill="url(#iXXwmeb)" class="ttb9dxbfy"/><path fill="url(#iJqevdb)" class="ttb9dxbfy"/></g><g filter="url(#i8b2dCr)"><path stroke="url(#i9JgFtd)" class="zpok88b9y"/></g><g filter="url(#ioVMUOd)"><path class="b9-f3tbdy"/></g><path fill="url(#ipot32b)" class="ax3t7fbst"/><path fill="url(#ir8tAWb)" class="ax3t7fbst"/><path class="t9w88ccap"/><path fill="url(#icKH4Wd)" class="td7qnxbmr"/><path fill="url(#iqqDZPU)" class="td7qnxbmr"/><path fill="url(#iRI2yhd)" class="g3ux3cbys"/><path fill="url(#ihnjaeb)" class="ny9_xhbeh"/><g filter="url(#iSeoJkb)"><path fill="url(#iHXaVce)" class="jsqgobbht"/><path fill="url(#i2BUj5L)" class="jsqgobbht"/><path fill="url(#iqtSqJd)" class="jsqgobbht"/><path fill="url(#iNN1SaK)" class="jsqgobbht"/><path fill="url(#irzSjbb)" class="jsqgobbht"/><path fill="url(#ihI2zKe)" class="jsqgobbht"/></g><path fill="url(#ixwQhto)" class="ppwrykbzp"/><path fill="url(#i8N6NDd)" class="ppwrykbzp"/><path fill="url(#ilcEH9d)" class="ppwrykbzp"/><path fill="url(#iKDpaee)" class="ppwrykbzp"/><path fill="url(#i2FoUFP)" class="ppwrykbzp"/><path fill="url(#iWis4Qd)" class="w6exmsbsa"/><defs><radialGradient id="imoHmCd" cx="0" cy="0" r="1" gradientTransform="matrix(-.60337 4.55908 -5.69522 -.75373 15.698 13.008)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="iWU5mNc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88301 1.94432 -2.5547 -3.78806 12.883 13.278)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="iqFUw3i" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.927 8.121)scale(2.15225 1.65263)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="iTn0Osd" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 3.364 7.606)scale(2.47506 1.74346)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="i5d56qb" cx="0" cy="0" r="1" gradientTransform="rotate(62.272 4.212 11.555)scale(2.95399 4.10059)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="iX13Dbc" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 9.979 6.786)scale(2.03849 2.84876)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iswmVtG" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.11855 -3.84482 23.51 9.657)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="iRFq3zd" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.648 7.948)scale(2.90248 3.69733)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="ix1Cwid" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 12.95 -3.804)scale(2.80034 2.21491)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="iaepPwc" cx="0" cy="0" r="1" gradientTransform="matrix(1.50392 .15775 -.2556 2.43678 9.858 9.621)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="ieQOEad" cx="0" cy="0" r="1" gradientTransform="rotate(107.382 2.784 7.075)scale(2.91973 2.69143)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="gcrmpdfop"/><stop offset="1" class="nd--cppfl"/></radialGradient><radialGradient id="iD9pUqb" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 20.04 10.948)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="ayiod_bfg"/><stop offset=".944" class="wb78_hxsc"/></radialGradient><radialGradient id="iFlZvKe" cx="0" cy="0" r="1" gradientTransform="matrix(1.31577 .7375 -.2085 .37199 21.07 8.827)" gradientUnits="userSpaceOnUse"><stop class="s9u3_wbrp"/><stop offset="1" class="crde6o_5i"/></radialGradient><radialGradient id="iGri1lc" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 20.392 10.62)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="rmmi4abgs"/><stop offset="1" class="xuyenabum"/></radialGradient><radialGradient id="iQ8lIac" cx="0" cy="0" r="1" gradientTransform="matrix(-1.20681 0 0 -.95203 11.4 10.508)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="pj2ff5nxp"/><stop offset="1" class="sdufqstmc"/></radialGradient><radialGradient id="imY1N1c" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50358 2.99902 -4.01413 -8.70492 18.86 9.971)" gradientUnits="userSpaceOnUse"><stop class="aj61gebdf"/><stop offset="1" class="v2xpqhbrh"/></radialGradient><radialGradient id="i9CVBwc" cx="0" cy="0" r="1" gradientTransform="rotate(154.513 7.69 7.423)scale(2.25599 1.57104)" gradientUnits="userSpaceOnUse"><stop class="o3k0towjz"/><stop offset="1" class="x7h3p2bdy"/></radialGradient><radialGradient id="i4gusDc" cx="0" cy="0" r="1" gradientTransform="matrix(1.0735 -3.47607 4.41049 1.36207 13.82 16.753)" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></radialGradient><radialGradient id="izdygDb" cx="0" cy="0" r="1" gradientTransform="rotate(96.727 3.768 12.416)scale(6.84714 6.88381)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="m6mmhsf1n"/><stop offset="1" class="do3fwrbgr"/></radialGradient><radialGradient id="i6671uc" cx="0" cy="0" r="1" gradientTransform="scale(6.60207 6.56691)rotate(90 .403 1.98)" gradientUnits="userSpaceOnUse"><stop offset=".794" class="d0fyzsbqc"/><stop offset="1" class="n8ysctycz"/></radialGradient><radialGradient id="iEvJXje" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.336 6.717)scale(7.03739 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="f6uv1pf_h"/><stop offset="1" class="fp6zmm73k"/></radialGradient><radialGradient id="ixvo2oP" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.301 9.553)" gradientUnits="userSpaceOnUse"><stop class="yv4uycbmh"/><stop offset="1" class="wgpm0ibqw"/></radialGradient><radialGradient id="ic4df0K" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 13.924 9.324)" gradientUnits="userSpaceOnUse"><stop class="f82mfcbsw"/><stop offset="1" class="xkhh7vb2n"/></radialGradient><radialGradient id="iwENnCx" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28528 0 0 -6.44557 21.096 11.04)" gradientUnits="userSpaceOnUse"><stop class="jids0zpwm"/><stop offset="1" class="zz4mcgrzh"/></radialGradient><radialGradient id="iMXDyxc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.829 1.57435 -1.05517 -1.22584 19.921 15.087)" gradientUnits="userSpaceOnUse"><stop class="ybvm9tprh"/><stop offset=".694" class="yxwqgvbem"/></radialGradient><radialGradient id="iwV9Emd" cx="0" cy="0" r="1" gradientTransform="matrix(-.45554 -2.04401 .62995 -.1404 16.784 11.767)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="x_sue_b_g"/><stop offset="1" class="gl9okfban"/></radialGradient><radialGradient id="iIBv6de" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.2179 16.545 11.979)" gradientUnits="userSpaceOnUse"><stop class="t5djkhb4t"/><stop offset="1" class="qm132ccsa"/></radialGradient><radialGradient id="i20Mo4p" cx="0" cy="0" r="1" gradientTransform="rotate(145.529 6.423 8.232)scale(1.66326 1.99898)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="i669rlbzr"/><stop offset="1" class="yt9sv1b9n"/></radialGradient><radialGradient id="iE8oPbX" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.182 9.911)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iNO0awb" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 17.954 9.995)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iortVcX" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.818 9.911)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iBTecCL" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.752 -1.595)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iOZxwjr" cx="0" cy="0" r="1" gradientTransform="rotate(-65.391 11.24 -4.16)scale(3.03069 1.55043)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="iXXwmeb" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 8.143 6.922)scale(4.8729 7.96691)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="iJqevdb" cx="0" cy="0" r="1" gradientTransform="matrix(-.21033 1.3672 -2.94145 -.45252 16.21 2.953)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><radialGradient id="ipot32b" cx="0" cy="0" r="1" gradientTransform="matrix(2.80769 -1.3591 1.47615 3.04949 2.747 30.02)" gradientUnits="userSpaceOnUse"><stop offset=".406" class="xomn_jqkl"/><stop offset="1" class="yvpae5bzc"/></radialGradient><radialGradient id="ir8tAWb" cx="0" cy="0" r="1" gradientTransform="rotate(177.157 2.332 14.994)scale(3.35044 4.79049)" gradientUnits="userSpaceOnUse"><stop offset=".764" class="ff9bywbjm"/><stop offset=".927" class="bf-s3qwzt"/></radialGradient><radialGradient id="icKH4Wd" cx="0" cy="0" r="1" gradientTransform="matrix(5.64062 -3.71875 1.03844 1.57511 27.091 30.119)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="nbncwobqn"/><stop offset=".988" class="n55x1ubvq"/></radialGradient><radialGradient id="i2BUj5L" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.59705 13.2772 0 17.243 31.067)" gradientUnits="userSpaceOnUse"><stop offset=".027" class="o1-qqkidl"/><stop offset="1" class="q0dxfdmim"/></radialGradient><radialGradient id="ihI2zKe" cx="0" cy="0" r="1" gradientTransform="matrix(-.78125 .4375 -.4057 -.72446 26.696 16.66)" gradientUnits="userSpaceOnUse"><stop class="nonrr22es"/><stop offset=".724" class="jehi2ihjx"/></radialGradient><radialGradient id="iWis4Qd" cx="0" cy="0" r="1" gradientTransform="matrix(-.0957 .08008 -.11939 -.14269 17.371 21.824)" gradientUnits="userSpaceOnUse"><stop class="a-otvg7dq"/><stop offset="1" class="t_w5hobcp"/></radialGradient><linearGradient id="ikN729b" x1="20.693" x2="13.888" y1="3.556" y2="16.161" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="iqrRyTh" x1="8.815" x2="23.191" y1="15.318" y2="15.318" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iqexxae" x1="8.815" x2="23.191" y1="15.288" y2="15.288" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="ixpxIdb" x1="9.705" x2="12.665" y1="10.596" y2="10.596" gradientUnits="userSpaceOnUse"><stop class="z_wfxjr5n"/><stop offset="1" class="qenr6bbwz"/></linearGradient><linearGradient id="icyXqdc" x1="15.062" x2="16" y1="11.84" y2="11.84" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="i2uhSAd" x1="16" x2="16" y1="12.639" y2="12.029" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></linearGradient><linearGradient id="itBRUte" x1="16.078" x2="16.078" y1="12.613" y2="12.473" gradientUnits="userSpaceOnUse"><stop class="kos78---c"/><stop offset="1" class="wq1w-qb8s"/></linearGradient><linearGradient id="i0Vfwyd" x1="14.936" x2="15.397" y1="14.048" y2="13.336" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="ieaxaTb" x1="18.96" x2="18.646" y1="9.965" y2="10.159" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iJg10Sc" x1="14.562" x2="14.248" y1="9.965" y2="10.159" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i9JgFtd" x1="13.109" x2="13.653" y1="4.31" y2="5.584" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><linearGradient id="iqqDZPU" x1="26.966" x2="27.302" y1="28.838" y2="28.838" gradientUnits="userSpaceOnUse"><stop class="msex9gbuq"/><stop offset="1" class="eu7hrybov"/></linearGradient><linearGradient id="iRI2yhd" x1="10.918" x2="1.428" y1="24.003" y2="24.044" gradientUnits="userSpaceOnUse"><stop class="vuad6pb7r"/><stop offset="1" class="zaeth0b6d"/></linearGradient><linearGradient id="ihnjaeb" x1="22.998" x2="28.652" y1="24.02" y2="24.02" gradientUnits="userSpaceOnUse"><stop class="vuad6pb7r"/><stop offset="1" class="zaeth0b6d"/></linearGradient><linearGradient id="iHXaVce" x1="7.493" x2="11.284" y1="19.754" y2="30.805" gradientUnits="userSpaceOnUse"><stop class="ux-m5bn7d"/><stop offset="1" class="l294t3zvi"/></linearGradient><linearGradient id="iqtSqJd" x1="16" x2="16" y1="16.02" y2="17.379" gradientUnits="userSpaceOnUse"><stop class="dmu1fh1sq"/><stop offset=".268" class="gzfhb8b1n"/><stop offset=".863" class="szjcm-w7x"/></linearGradient><linearGradient id="iNN1SaK" x1="5" x2="6.055" y1="24.254" y2="24.254" gradientUnits="userSpaceOnUse"><stop class="a61ap5b7j"/><stop offset="1" class="p9llu9bpa"/></linearGradient><linearGradient id="irzSjbb" x1="27" x2="25.524" y1="25.192" y2="25.192" gradientUnits="userSpaceOnUse"><stop offset=".174" class="yr342ibfl"/><stop offset="1" class="d9m_15bme"/></linearGradient><linearGradient id="ixwQhto" x1="17.977" x2="13.911" y1="23.099" y2="23.099" gradientUnits="userSpaceOnUse"><stop offset=".096" class="qufyc6r7b"/><stop offset=".13" class="xqmtwwbyq"/><stop offset=".165" class="k71v6_7um"/><stop offset="1" class="uem0lbchq"/></linearGradient><linearGradient id="i8N6NDd" x1="15.999" x2="15.999" y1="21.641" y2="23.196" gradientUnits="userSpaceOnUse"><stop class="w9bfwpbnq"/><stop offset="1" class="zt_ualb3u"/></linearGradient><linearGradient id="ilcEH9d" x1="15.999" x2="15.999" y1="21.641" y2="24.557" gradientUnits="userSpaceOnUse"><stop class="l17xqebtl"/><stop offset=".037" class="r1d3vkbxd"/><stop offset=".058" class="bowxt9bwr"/><stop offset=".097" class="g48yfbn9k"/></linearGradient><linearGradient id="iKDpaee" x1="14.444" x2="15.02" y1="23.122" y2="23.122" gradientUnits="userSpaceOnUse"><stop offset=".086" class="v1n2dlbml"/><stop offset=".663" class="ohv650iba"/></linearGradient><linearGradient id="i2FoUFP" x1="15.999" x2="15.999" y1="24.842" y2="24.168" gradientUnits="userSpaceOnUse"><stop offset=".507" class="qqk6g6zlh"/><stop offset=".736" class="auud8yb7i"/></linearGradient><filter id="ib6uWLY" width="15.268" height="15.768" x="8.491" y="1.23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_837"/></filter><filter id="i2OMQNd" width="3.368" height="3.218" x="9.705" y="8.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.266667 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_837"/></filter><filter id="iqwk5Hc" width="3.218" height="3.468" x="19.218" y="8.649" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.0901961 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_837"/></filter><filter id="irrwkqb" width="3.148" height="3.148" x="19.253" y="8.934" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_837" stdDeviation=".25"/></filter><filter id="ikP3lbd" width="2.648" height="2.648" x="10.01" y="9.184" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_837" stdDeviation=".125"/></filter><filter id="iDb2Rwc" width="10.191" height="11.127" x="10.905" y="5.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.0901961 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_837"/></filter><filter id="ioPBuAd" width="2.877" height="3.682" x="14.399" y="9.503" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_837" stdDeviation=".25"/></filter><filter id="iIaEQOb" width="2.377" height="3.182" x="14.812" y="9.615" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_837" stdDeviation=".125"/></filter><filter id="i46oqog" width="3.001" height="1.285" x="16.942" y="9.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_837"/></filter><filter id="i23j7qd" width="3.001" height="1.285" x="12.057" y="9.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_837"/></filter><filter id="ia87Tjd" width="2.453" height="1.091" x="12.192" y="7.68" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_837"/></filter><filter id="iawFwJb" width="2.453" height="1.091" x="17.609" y="7.68" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_837"/></filter><filter id="iWfS1Sb" width=".787" height=".696" x="17.448" y="9.472" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_837" stdDeviation=".05"/></filter><filter id="iLW339c" width=".891" height=".913" x="18.288" y="9.547" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_837" stdDeviation=".1"/></filter><filter id="iVk48sd" width=".986" height="1.04" x="13.845" y="9.483" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_837" stdDeviation=".1"/></filter><filter id="i64guSz" width=".913" height=".705" x="13.09" y="9.463" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_837" stdDeviation=".05"/></filter><filter id="iChkVJy" width="2.861" height="1.578" x="17.34" y="7.503" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_837" stdDeviation=".2"/></filter><filter id="ij3PFod" width="2.861" height="1.578" x="11.888" y="7.503" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_837" stdDeviation=".2"/></filter><filter id="isVP8zY" width="4.412" height="4.713" x="9.546" y="3.467" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.341176 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_837"/><feGaussianBlur result="effect2_foregroundBlur_3_837" stdDeviation=".25"/></filter><filter id="iWgzrYd" width="8.767" height="5.782" x="12.83" y="2.432" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_837"/><feGaussianBlur result="effect2_foregroundBlur_3_837" stdDeviation=".125"/></filter><filter id="i8b2dCr" width="1.145" height="2.31" x="12.809" y="3.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_837" stdDeviation=".1"/></filter><filter id="ioVMUOd" width="6.427" height="3.372" x="15.418" y="4.475" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_837" stdDeviation=".375"/></filter><filter id="iSeoJkb" width="22" height="14.1" x="5" y="16.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.670588 0 0 0 0 0.682353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_837"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-technologist-dark" /></template>
<style>
.a_spo2cop {
  d: path("M16.025 15.289h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.a-otvg7dq {
  stop-color: var(--svg-color--806b97, #806B97);
}

.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.a61ap5b7j {
  stop-color: var(--svg-color--9f93b2, #9F93B2);
}

.aj61gebdf {
  stop-color: var(--svg-color--4f322e, #4F322E);
}

.auud8yb7i {
  stop-color: var(--svg-color--4a3261, #4A3261);
  stop-opacity: 0;
}

.ax3t7fbst {
  d: path("M8.329 30.02q.004-.082.004-.163a3.138 3.138 0 1 0-6.271.162z");
}

.ayiod_bfg {
  stop-color: var(--svg-color--493033, #493033);
}

.b9-f3tbdy {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m18.406 6.328l-1.425.262a.688.688 0 1 1-.125-1.365h2.34c1.385 0 1.843 1.395 1.9 1.872a3.15 3.15 0 0 0-2.69-.77");
}

.bf-s3qwzt {
  stop-color: var(--svg-color--634d49, #634D49);
}

.bi4mzcbhr {
  fill-rule: evenodd;
  d: path("M23.185 11.918c.213-.435.324-.92.324-1.427c0-.467-.096-.905-.268-1.305h.005a3 3 0 0 0-.281-.513l-.002-.003a3.24 3.24 0 0 1-.527-1.771v-.01a3.3 3.3 0 0 0-3.299-3.3a.54.54 0 0 1-.455-.232A3.3 3.3 0 0 0 16 1.98a3.3 3.3 0 0 0-2.682 1.377a.56.56 0 0 1-.455.233h-.085a3.3 3.3 0 0 0-3.214 3.3v.01a3.24 3.24 0 0 1-.527 1.77l-.002.004a3.3 3.3 0 0 0-.22 3.245c.07.142.07.314 0 .456A3.213 3.213 0 0 0 11.709 17h8.582a3.213 3.213 0 0 0 3.218-3.219c0-.506-.121-.981-.324-1.406a.51.51 0 0 1 0-.456m-12.26-2.672h-.012l1.198 2.355c.124 2.803 1.217 0 3.889 0s3.836 3.12 3.96.317l1.136-3.197c-.054-1.245-.956-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.19-1.673a.264.264 0 0 0-.461.05l-.082.195a2.3 2.3 0 0 1-1.292 1.275c-.236.122-.79.49-.81 1.439l.01.306z");
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bowxt9bwr {
  stop-color: var(--svg-color--6f5783, #6F5783);
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.cctx1cb1y {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
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

.crde6o_5i {
  stop-color: var(--svg-color--402824, #402824);
  stop-opacity: 0;
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.d0fyzsbqc {
  stop-color: var(--svg-color--3b232b, #3B232B);
  stop-opacity: 0;
}

.d1szpqbot {
  fill: var(--svg-color--4a302d, #4A302D);
  d: path("m15.618 10.147l-.532 1.7a.54.54 0 0 0 .521.7h.786a.54.54 0 0 0 .521-.7l-.532-1.7c-.113-.376-.645-.376-.764 0");
}

.d5cumfbeh {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M17.142 9.94c.266-.467.67-.836 1.538-.836c.38 0 .747.105 1.072.369c.27.217.233.495.025.599l-.556.317c-.652-.21-1.373-.239-2.079-.45");
}

.d9m_15bme {
  stop-color: var(--svg-color--a191b5, #A191B5);
  stop-opacity: 0;
}

.dmu1fh1sq {
  stop-color: var(--svg-color--beb0b0, #BEB0B0);
}

.do3fwrbgr {
  stop-color: var(--svg-color--3f243b, #3F243B);
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.ebv6t9bbq {
  fill: var(--svg-color--000, #000);
  d: path("M14.327 10.327a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .061-.235");
}

.eu7hrybov {
  stop-color: var(--svg-color--533e40, #533E40);
  stop-opacity: 0;
}

.eur0b6bpq {
  d: path("M11.334 11.583a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.ez8-_ybbt {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m19.732 8.273l-.138.23za.268.268 0 0 1-.275.46l-.005-.002a1 1 0 0 0-.113-.059a3 3 0 0 0-.342-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 1 1-.093-.528c.513-.09.988.001 1.328.11a3.3 3.3 0 0 1 .559.238l.009.005z");
}

.f443huont {
  d: path("M10.913 9.246h.012l-.01-.265l-.01-.306c.02-.95.574-1.317.81-1.439l.051-.02l.051-.02a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.051a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.082.087 1.136 1.332l-.12 3.073c-.122 2.803-2.311 4.685-4.982 4.685s-4.86-1.882-4.984-4.685z");
}

.f6uv1pf_h {
  stop-color: var(--svg-color--5e4543, #5E4543);
  stop-opacity: 0;
}

.f82mfcbsw {
  stop-color: var(--svg-color--371e27, #371E27);
}

.ff9bywbjm {
  stop-color: var(--svg-color--634d49, #634D49);
  stop-opacity: 0;
}

.fp6zmm73k {
  stop-color: var(--svg-color--5e4543, #5E4543);
}

.ft5dv1b6b {
  fill: none;
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g3ux3cbys {
  d: path("M8.98 18.02a10.99 10.99 0 0 0-3.97 8.5l.02 3.5l4-.02z");
}

.g48yfbn9k {
  stop-color: var(--svg-color--5f447b, #5F447B);
  stop-opacity: 0;
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.gcrmpdfop {
  stop-color: var(--svg-color--585352, #585352);
}

.gl9okfban {
  stop-color: var(--svg-color--634d4b, #634D4B);
  stop-opacity: 0;
}

.glnfjzbdq {
  d: path("M11.314 12.118a1.61 1.61 0 1 0 0-3.219a1.61 1.61 0 0 0 0 3.219");
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gzfhb8b1n {
  stop-color: var(--svg-color--beb7c7, #BEB7C7);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.i669rlbzr {
  stop-color: var(--svg-color--2d151c, #2D151C);
  stop-opacity: 0;
}

.i6bji0ert {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.61 9.163c-.654 0-1.206.45-1.356 1.058a.275.275 0 0 0 .268.341h2.231a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.37-1.127");
}

.i6h4x1urm {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M17.94 8.136c.322-.079 1.124-.04 1.66.344");
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j9z76nbfg {
  d: path("M20.827 11.583a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.jehi2ihjx {
  stop-color: var(--svg-color--e5dff1, #E5DFF1);
  stop-opacity: 0;
}

.jids0zpwm {
  stop-color: var(--svg-color--59403d, #59403D);
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jo8lxfo6c {
  fill: var(--svg-color--000, #000);
  d: path("M17.673 10.327c0-.284.227-.511.511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.235");
}

.jsqgobbht {
  d: path("M26.03 16.02H5.97a.97.97 0 0 0-.97.97v13.03h22V16.99a.97.97 0 0 0-.97-.97");
}

.k0f91xc-h {
  fill: var(--svg-color--2a0219, #2A0219);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.602 13.031a.204.204 0 0 0-.248.043a.196.196 0 0 0-.02.248a1.982 1.982 0 0 0 3.333 0a.2.2 0 0 0-.022-.25a.205.205 0 0 0-.246-.041A3 3 0 0 1 16 13.37a3 3 0 0 1-1.398-.339Z");
}

.k71v6_7um {
  stop-color: var(--svg-color--51366c, #51366C);
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kmbgvqb8x {
  d: path("M20.827 12.118a1.61 1.61 0 1 0 0-3.219a1.61 1.61 0 0 0 0 3.219");
}

.kos78---c {
  stop-color: var(--svg-color--311620, #311620);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l17xqebtl {
  stop-color: var(--svg-color--594170, #594170);
}

.l294t3zvi {
  stop-color: var(--svg-color--847498, #847498);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.lp-jspbxv {
  d: path("M16.355 15.289c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.m6mmhsf1n {
  stop-color: var(--svg-color--3f243b, #3F243B);
  stop-opacity: 0;
}

.mah7hvb-b {
  fill: var(--svg-color--272528, #272528);
  d: path("M14.858 9.94c-.265-.467-.669-.836-1.537-.836c-.38 0-.747.105-1.073.369c-.269.217-.233.495-.025.599l.556.317c.652-.21 1.373-.239 2.08-.45");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.msex9gbuq {
  stop-color: var(--svg-color--533e40, #533E40);
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n3eifgatt {
  d: path("M18.98 10.21a.84.84 0 0 0-.232-.463l-.26.285l.117.228z");
}

.n55x1ubvq {
  stop-color: var(--svg-color--533837, #533837);
  stop-opacity: 0;
}

.n8ysctycz {
  stop-color: var(--svg-color--2b151b, #2B151B);
}

.nbncwobqn {
  stop-color: var(--svg-color--6b5957, #6B5957);
}

.nd--cppfl {
  stop-color: var(--svg-color--585352, #585352);
  stop-opacity: 0;
}

.nonrr22es {
  stop-color: var(--svg-color--e5dff1, #E5DFF1);
}

.ntb7br0fn {
  d: path("M10.93 4.52c.567-.599 1.637-.6 2.132-.51l.396 1.29c-.253-.039-.479.05-.668.235c-.449 1.26-1.99 1.955-2.704 2.145c-.148-1.492.109-2.38.845-3.16");
}

.ny9_xhbeh {
  d: path("M23 18.03v11.98h4v-3.5c0-3.41-1.56-6.46-4-8.48");
}

.o1-qqkidl {
  stop-color: var(--svg-color--78698c, #78698C);
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ohv650iba {
  stop-color: var(--svg-color--52376c, #52376C);
  stop-opacity: 0;
}

.otj2-4byw {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M14.149 8.136c-.323-.079-1.125-.04-1.661.344");
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.p9llu9bpa {
  stop-color: var(--svg-color--9f93b2, #9F93B2);
  stop-opacity: 0;
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pdyfmt2wz {
  cx: 13.547px;
  cy: 9.816px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.pj2ff5nxp {
  stop-color: var(--svg-color--2d181a, #2D181A);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppwrykbzp {
  d: path("M14.444 21.89a.25.25 0 0 1 .25-.25h2.61a.25.25 0 0 1 .25.25v2.417a.25.25 0 0 1-.25.25h-2.61a.25.25 0 0 1-.25-.25z");
}

.pxpgdvb7j {
  fill: var(--svg-color--331b25, #331B25);
  d: path("m15.608 10.286l-.684 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.377-.494-.377-.613 0");
}

.q0dxfdmim {
  stop-color: var(--svg-color--7a6b8e, #7A6B8E);
  stop-opacity: 0;
}

.qenr6bbwz {
  stop-color: var(--svg-color--2a1c1f, #2A1C1F);
}

.qm132ccsa {
  stop-color: var(--svg-color--655251, #655251);
  stop-opacity: 0;
}

.qqb9fccqv {
  d: path("m15.618 10.147l-.532 1.7a.54.54 0 0 0 .521.7h.786a.54.54 0 0 0 .521-.7l-.532-1.7c-.113-.376-.645-.376-.764 0");
}

.qqk6g6zlh {
  stop-color: var(--svg-color--3d2555, #3D2555);
}

.qsd57_bml {
  fill: var(--svg-color--20171a, #20171A);
  d: path("M10.93 4.52c.567-.599 1.637-.6 2.132-.51l.396 1.29c-.253-.039-.479.05-.668.235c-.449 1.26-1.99 1.955-2.704 2.145c-.148-1.492.109-2.38.845-3.16");
}

.qufyc6r7b {
  stop-color: var(--svg-color--56416b, #56416B);
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

.r1d3vkbxd {
  stop-color: var(--svg-color--6d5686, #6D5686);
}

.rmmi4abgs {
  stop-color: var(--svg-color--371d1f, #371D1F);
  stop-opacity: 0;
}

.s9u3_wbrp {
  stop-color: var(--svg-color--402824, #402824);
}

.sdufqstmc {
  stop-color: var(--svg-color--2d181a, #2D181A);
}

.segtjobkz {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.119 9.623c.063.085-.07.189-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.389-.051");
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.szjcm-w7x {
  stop-color: var(--svg-color--beb7c7, #BEB7C7);
  stop-opacity: 0;
}

.t_w5hobcp {
  stop-color: var(--svg-color--8d78a4, #8D78A4);
  stop-opacity: 0;
}

.t5djkhb4t {
  stop-color: var(--svg-color--655251, #655251);
}

.t9w88ccap {
  fill: var(--svg-color--533836, #533836);
  d: path("M29.938 30.02q.005-.082.005-.163a3.138 3.138 0 1 0-6.272.162z");
}

.td7qnxbmr {
  d: path("M29.938 30.02q.005-.082.005-.163a3.138 3.138 0 1 0-6.272.162z");
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.ttb9dxbfy {
  d: path("M15.397 2.718c-1.133-.25-2.15.88-2.267 1.299c1.051 3.545 3.713 3.35 6.34 3.059c1.572-.175 1.743.542 1.877.888c0-3.933-3.344-4.67-5.922-5.24z");
}

.tuiticc0a {
  fill: var(--svg-color--35252b, #35252B);
  d: path("M11.334 11.583a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.uem0lbchq {
  stop-color: var(--svg-color--4f3568, #4F3568);
}

.uf5rerbdy {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.391 9.163c.653 0 1.205.45 1.355 1.058a.274.274 0 0 1-.268.341h-2.23a.23.23 0 0 1-.228-.272c.126-.64.69-1.127 1.371-1.127");
}

.ux-m5bn7d {
  stop-color: var(--svg-color--ab9cbe, #AB9CBE);
}

.v1n2dlbml {
  stop-color: var(--svg-color--3b2b50, #3B2B50);
}

.v2xpqhbrh {
  stop-color: var(--svg-color--402a29, #402A29);
}

.vuad6pb7r {
  stop-color: var(--svg-color--1c1c1c, #1C1C1C);
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.w2q6f6-7d {
  cx: 13.547px;
  cy: 9.816px;
  rx: 0.39px;
  ry: 0.197px;
}

.w6exmsbsa {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M14.444 21.89a.25.25 0 0 1 .25-.25h2.61a.25.25 0 0 1 .25.25v2.417a.25.25 0 0 1-.25.25h-2.61a.25.25 0 0 1-.25-.25z");
}

.w80gnzyby {
  d: path("M13.816 9.434a.892.892 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.893");
}

.w9bfwpbnq {
  stop-color: var(--svg-color--60407f, #60407F);
}

.wb78_hxsc {
  stop-color: var(--svg-color--6a5956, #6A5956);
}

.wgpm0ibqw {
  stop-color: var(--svg-color--43272a, #43272A);
  stop-opacity: 0;
}

.wq1w-qb8s {
  stop-color: var(--svg-color--311620, #311620);
  stop-opacity: 0;
}

.x_sue_b_g {
  stop-color: var(--svg-color--634d4b, #634D4B);
}

.x7h3p2bdy {
  stop-color: var(--svg-color--533632, #533632);
  stop-opacity: 0;
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xfko61b4t {
  fill: var(--svg-color--4c3637, #4C3637);
  d: path("M20.827 11.583a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.xfmbn4_bb {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
  stop-opacity: 0;
}

.xkhh7vb2n {
  stop-color: var(--svg-color--371e27, #371E27);
  stop-opacity: 0;
}

.xomn_jqkl {
  stop-color: var(--svg-color--503c3b, #503C3B);
}

.xqmtwwbyq {
  stop-color: var(--svg-color--614c77, #614C77);
}

.xrzdifaqt {
  fill: var(--svg-color--2f2428, #2F2428);
  d: path("M15.397 2.718c-1.133-.25-2.15.88-2.267 1.299c1.051 3.545 3.713 3.35 6.34 3.059c1.572-.175 1.743.542 1.877.888c0-3.933-3.344-4.67-5.922-5.24z");
}

.xuflm6bwg {
  d: path("M14.631 10.222c0-.288-.234-.48-.298-.539l-.288.28l.177.36z");
}

.xuyenabum {
  stop-color: var(--svg-color--371d1f, #371D1F);
}

.y-0wdxbdo {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m12.602 8.73l-.004.003a.268.268 0 0 1-.276-.46h.002l.003-.003l.01-.005a2 2 0 0 1 .148-.077a3 3 0 0 1 .41-.162c.34-.108.815-.2 1.328-.109a.268.268 0 1 1-.093.528a2.3 2.3 0 0 0-1.072.092a3 3 0 0 0-.434.182z");
}

.y1gxombgs {
  d: path("M18.184 9.434a.892.892 0 0 1 .86 1.128H17.32a.896.896 0 0 1 .864-1.128");
}

.ybvm9tprh {
  stop-color: var(--svg-color--594d4d, #594D4D);
}

.yr342ibfl {
  stop-color: var(--svg-color--bab9c0, #BAB9C0);
}

.yt9sv1b9n {
  stop-color: var(--svg-color--2d151c, #2D151C);
}

.yv4uycbmh {
  stop-color: var(--svg-color--43272a, #43272A);
}

.yvpae5bzc {
  stop-color: var(--svg-color--3b2a28, #3B2A28);
}

.yxwqgvbem {
  stop-color: var(--svg-color--594d4d, #594D4D);
  stop-opacity: 0;
}

.z_wfxjr5n {
  stop-color: var(--svg-color--392526, #392526);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.zaeth0b6d {
  stop-color: var(--svg-color--636363, #636363);
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zhb5rly-q {
  d: path("M18.119 9.623c.063.085-.07.189-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.389-.051");
}

.zpok88b9y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.109 3.967c.023.243.234 1.156.544 1.71");
}

.zt_ualb3u {
  stop-color: var(--svg-color--543870, #543870);
  stop-opacity: 0;
}

.zz4mcgrzh {
  stop-color: var(--svg-color--59403d, #59403D);
  stop-opacity: 0;
}

</style>
