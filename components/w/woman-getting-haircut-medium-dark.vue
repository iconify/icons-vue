<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="iOPiyVc" class="j4dxu6b2c"/></defs><g class="ft5dv1b6b"><g filter="url(#ilP4xGd)"><path fill="url(#iwviawe)" clip-rule="evenodd" class="sitfol3cj"/><path fill="url(#iu9Zekd)" clip-rule="evenodd" class="sitfol3cj"/><path fill="url(#itSKYVb)" clip-rule="evenodd" class="sitfol3cj"/><path fill="url(#i1KeIHc)" clip-rule="evenodd" class="sitfol3cj"/><path fill="url(#iNHg0mh)" clip-rule="evenodd" class="sitfol3cj"/><path fill="url(#ig9fz0b)" clip-rule="evenodd" class="sitfol3cj"/><path fill="url(#ip1T5dc)" clip-rule="evenodd" class="sitfol3cj"/><path fill="url(#iUSfdLc)" clip-rule="evenodd" class="sitfol3cj"/><path fill="url(#iLAW79d)" clip-rule="evenodd" class="sitfol3cj"/><path fill="url(#ite5MGn)" clip-rule="evenodd" class="sitfol3cj"/><path fill="url(#iZinvGc)" clip-rule="evenodd" class="sitfol3cj"/></g><path fill="url(#iYpna8t)" class="h064k9b1n"/><path fill="url(#iUKebPb)" class="h064k9b1n"/><path fill="url(#ic5d39d)" class="h064k9b1n"/><path fill="url(#ihEx4Ab)" class="h064k9b1n"/><path fill="url(#itb84Mb)" class="h064k9b1n"/><path fill="url(#imb632d)" class="k_9tcyber"/><path fill="url(#il0VLoc)" class="k_9tcyber"/><path class="x7bl4zbkb"/><path fill="url(#i3eTupc)" class="d0mty6dok"/><path fill="url(#iQULaLb)" class="d0mty6dok"/><path class="c1uh7gbbk"/><path fill="url(#i1r835b)" class="s5j9zog_u"/><path fill="url(#idSeNMn)" class="s5j9zog_u"/><path fill="url(#ieqwvgd)" class="r_t9aq_-g"/><path fill="url(#i3U51ac)" class="a-cgv50-r"/><g filter="url(#i2L0Q6b)"><path fill="url(#iVp3Bmc)" class="pzph9acww"/></g><g filter="url(#iqyYemd)"><path fill="url(#i1BpAFc)" class="xzg31ccqm"/><path fill="url(#iYuEHhd)" class="xzg31ccqm"/></g><g filter="url(#iYVr1vd)"><path class="qu42xotyf"/><path fill="url(#i46Yjlc)" class="x6yzvt1od"/></g><g filter="url(#iLZvJbc)"><path class="uelu8baaf"/><path fill="url(#i81apWp)" class="nrqb0zb7k"/></g><g filter="url(#i6JCEoe)"><path fill="url(#iGdz7xe)" class="su9pt7edc"/><path fill="url(#iuGzKdn)" class="su9pt7edc"/><path fill="url(#ioJwmGB)" class="su9pt7edc"/><path fill="url(#iGeVOnd)" class="su9pt7edc"/><path fill="url(#ibQGdpb)" class="su9pt7edc"/><path fill="url(#iJppIrb)" class="su9pt7edc"/><path fill="url(#i1VzMKb)" class="su9pt7edc"/><path fill="url(#iehv4hb)" class="su9pt7edc"/></g><path fill="url(#iKSVIie)" class="su9pt7edc"/><path fill="url(#iChEZdb)" class="su9pt7edc"/><path fill="url(#iTsVq9b)" class="su9pt7edc"/><g filter="url(#ipoGvFd)"><path class="egfidgb4a"/></g><g filter="url(#i8gsz0b)"><path class="rr5dsobch"/><path fill="url(#iBQiaPe)" class="cibiz2b0f"/><path fill="url(#iuekKgn)" class="cibiz2b0f"/><path fill="url(#iz7tP3k)" class="cibiz2b0f"/><path fill="url(#idWEWfb)" class="cibiz2b0f"/></g><g filter="url(#iSTqtXb)"><use href="#iOPiyVc"/><path stroke="url(#iK9tPbb)" class="p5t7enbym"/></g><use href="#iOPiyVc"/><g filter="url(#isHeSoe)"><path class="i5bhawuus"/></g><g filter="url(#iFhWcIx)"><path class="ej_uxe27h"/></g><g filter="url(#itYuqvA)"><path class="quqm6o37z"/></g><g filter="url(#ic1Hdqc)"><path clip-rule="evenodd" class="av86ribkj"/></g><path class="dablr4u0o"/><path fill="url(#i7essOd)" class="ia1qxot8h"/><path class="bs2iicb4y"/><g filter="url(#iAWUppd)"><path class="tu-1otsuf"/><path fill="url(#iYjJGRc)" class="ay3imeglw"/></g><g filter="url(#icGBAze)"><path fill="url(#ipTUJuc)" class="e45vwmmsf"/></g><path class="i4_k3omhh"/><path fill="url(#izUGykd)" class="tgx7usrie"/><path class="yb6y2bchp"/><g filter="url(#iBKe8Zc)"><path fill="url(#idxvHEe)" class="equqpob_m"/></g><g filter="url(#igGWzEd)"><ellipse transform="rotate(-27.914 12.177 12.209)" class="uke-p0u6q"/><ellipse fill="url(#i7o7whc)" transform="rotate(-27.914 12.177 12.209)" class="xa_8_1bke"/></g><g filter="url(#i35zqYc)"><path class="qls0ocb-h"/></g><g filter="url(#iSollUd)"><path class="ajbrntixp"/></g><g filter="url(#ivG9jvd)"><path class="i1zo_pb3h"/><path fill="url(#iYnBHOe)" class="wm0pkrbcc"/></g><g filter="url(#iS47qvc)"><path class="hqyrwybyl"/><path fill="url(#iXKvtSb)" class="v_ah93bpt"/><path fill="url(#imOgnyb)" class="v_ah93bpt"/></g><g filter="url(#igA7lYw)"><path stroke="url(#id2eeBc)" class="qdra35bpg"/></g><g filter="url(#i7rUwcc)"><path class="tlhm2gbow"/></g><path fill="url(#i1J0ijc)" class="c_9-m-bzq"/><path fill="url(#ipYPb9b)" class="a41xocxec"/><path fill="url(#iwWxddP)" class="a41xocxec"/><path fill="url(#iaC38ue)" class="jrx3i8b1t"/><path fill="url(#irzfGIb)" class="jrx3i8b1t"/><g filter="url(#ieDoAMd)"><circle fill="url(#iVmkACb)" class="m8gsznlzl"/><circle fill="url(#iRQA0se)" class="m8gsznlzl"/><circle fill="url(#iu94fIb)" class="m8gsznlzl"/></g><g filter="url(#iukHNYc)"><path fill="url(#if1AEES)" clip-rule="evenodd" class="bqqvv7bor"/></g><path fill="url(#ipFIR2b)" clip-rule="evenodd" class="bqqvv7bor"/><g filter="url(#iJWdytb)"><path fill="url(#iqfCaLe)" clip-rule="evenodd" class="a4_5g-kex"/></g><g filter="url(#ihjOIcb)"><circle stroke="url(#iGw8SZc)" class="gm_5gldko"/></g><g filter="url(#iLhb6Me)"><circle stroke="url(#i25s7Yc)" class="v83a3u3_r"/></g><g filter="url(#i9VaRDb)"><circle stroke="url(#iGE3fSd)" class="uxe1igbwt"/></g><g filter="url(#iPru7id)"><circle stroke="url(#iLnBePe)" class="wj0k-xifb"/></g><defs><radialGradient id="iu9Zekd" cx="0" cy="0" r="1" gradientTransform="matrix(-.60337 4.55908 -5.69522 -.75373 14.329 15.403)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="itSKYVb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88301 1.94432 -2.5547 -3.78806 11.513 15.67)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="i1KeIHc" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 1.65 8.98)scale(2.15225 1.65263)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="iNHg0mh" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 2.008 8.418)scale(2.47506 1.74346)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="ig9fz0b" cx="0" cy="0" r="1" gradientTransform="rotate(62.272 1.547 11.618)scale(2.95399 4.10059)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="ip1T5dc" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 8.798 7.699)scale(2.03849 2.84876)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iUSfdLc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.11855 -3.84482 22.14 12.05)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="iLAW79d" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 9.816 9.06)scale(2.90248 3.69733)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="ite5MGn" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 13.121 -2.118)scale(2.80034 2.21491)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="iZinvGc" cx="0" cy="0" r="1" gradientTransform="matrix(1.50392 .15775 -.2556 2.43678 8.489 12.014)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="iYpna8t" cx="0" cy="0" r="1" gradientTransform="rotate(154.071 8.317 13.902)scale(15.0662 17.3462)" gradientUnits="userSpaceOnUse"><stop class="m5wv9vbgf"/><stop offset="1" class="ok0s313ee"/></radialGradient><radialGradient id="iUKebPb" cx="0" cy="0" r="1" gradientTransform="matrix(-7.90627 -10.81244 15.55864 -11.37678 17.476 29.861)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="je8i96bea"/><stop offset="1" class="r-plgxbvx"/></radialGradient><radialGradient id="ic5d39d" cx="0" cy="0" r="1" gradientTransform="rotate(168.453 5.763 9.951)scale(5.93256 1.70339)" gradientUnits="userSpaceOnUse"><stop class="u4cmqnbdb"/><stop offset="1" class="sncijkqpo"/></radialGradient><radialGradient id="ihEx4Ab" cx="0" cy="0" r="1" gradientTransform="matrix(-3.93377 0 0 -19.371 21.553 29.356)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="p47-3c-mm"/><stop offset="1" class="vzbvt7b3z"/></radialGradient><radialGradient id="itb84Mb" cx="0" cy="0" r="1" gradientTransform="matrix(1.5 0 0 23.8126 7.432 29.356)" gradientUnits="userSpaceOnUse"><stop class="g6dgamb9p"/><stop offset="1" class="hnlppfbil"/></radialGradient><radialGradient id="imb632d" cx="0" cy="0" r="1" gradientTransform="matrix(3.25185 0 0 9.13279 21.584 28.578)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="zduonub6o"/><stop offset="1" class="cuty5mbvc"/></radialGradient><radialGradient id="il0VLoc" cx="0" cy="0" r="1" gradientTransform="matrix(.87006 0 0 11.9715 21.584 29.356)" gradientUnits="userSpaceOnUse"><stop class="iwql9tbwr"/><stop offset="1" class="cpuxbvbrp"/></radialGradient><radialGradient id="i3eTupc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.70862 0 0 -8.85437 7.317 29.356)" gradientUnits="userSpaceOnUse"><stop offset=".614" class="fxt5p0b8w"/><stop offset="1" class="f4vmrjbib"/></radialGradient><radialGradient id="iQULaLb" cx="0" cy="0" r="1" gradientTransform="matrix(-.8463 0 0 -10.457 7.317 29.356)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="f3tc_zfmh"/><stop offset="1" class="nhus6q3at"/></radialGradient><radialGradient id="i1r835b" cx="0" cy="0" r="1" gradientTransform="matrix(.5625 1.75 -3.03541 .97567 13.708 18.707)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="zq9vt79xj"/><stop offset="1" class="u0qkrccus"/></radialGradient><radialGradient id="idSeNMn" cx="0" cy="0" r="1" gradientTransform="matrix(-2.9674 2.28562 -.98994 -1.28524 17.598 19.578)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="hph--cc6x"/><stop offset="1" class="zg-89ub5t"/></radialGradient><radialGradient id="i1BpAFc" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 18.67 13.34)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="olqyf7fmb"/><stop offset=".944" class="hpeo8yzih"/></radialGradient><radialGradient id="iYuEHhd" cx="0" cy="0" r="1" gradientTransform="matrix(1.31577 .7375 -.2085 .37199 19.7 11.22)" gradientUnits="userSpaceOnUse"><stop class="mt9k2qzvi"/><stop offset="1" class="fx1tjiblm"/></radialGradient><radialGradient id="i46Yjlc" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 19.022 13.014)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="l__dw9bpv"/><stop offset="1" class="wrh2b4bbx"/></radialGradient><radialGradient id="i81apWp" cx="0" cy="0" r="1" gradientTransform="rotate(180 5.015 6.45)scale(1.05596)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="o3wo53bzp"/><stop offset="1" class="eo_7g0bzd"/></radialGradient><radialGradient id="iGdz7xe" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50358 2.99902 -4.01413 -8.70492 17.49 12.364)" gradientUnits="userSpaceOnUse"><stop class="crj44uotj"/><stop offset="1" class="yamoh3dov"/></radialGradient><radialGradient id="iuGzKdn" cx="0" cy="0" r="1" gradientTransform="rotate(156.249 6.91 8.354)scale(2.38203 1.65881)" gradientUnits="userSpaceOnUse"><stop class="up8l18w-p"/><stop offset="1" class="ai95fabuh"/></radialGradient><radialGradient id="ioJwmGB" cx="0" cy="0" r="1" gradientTransform="matrix(1.28915 -3.92836 4.98436 1.6357 12.468 18.871)" gradientUnits="userSpaceOnUse"><stop class="osxg47drp"/><stop offset="1" class="da7h3oe0u"/></radialGradient><radialGradient id="iGeVOnd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28468 7.37319 -9.2164 -1.60583 15.653 11.948)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="mg10me7tz"/><stop offset="1" class="kitn3twkh"/></radialGradient><radialGradient id="ibQGdpb" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 7.535 7.846)scale(7.03739 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="opgioqbtx"/><stop offset="1" class="wg3eepbwp"/></radialGradient><radialGradient id="iJppIrb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 16.932 11.945)" gradientUnits="userSpaceOnUse"><stop class="t9k87pm2r"/><stop offset="1" class="ax9af2vtk"/></radialGradient><radialGradient id="i1VzMKb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 12.554 11.717)" gradientUnits="userSpaceOnUse"><stop class="x_ik4kbfh"/><stop offset="1" class="gcfqr7bfg"/></radialGradient><radialGradient id="iehv4hb" cx="0" cy="0" r="1" gradientTransform="matrix(-.87016 3.22674 -2.58193 -.69627 16.014 9.63)" gradientUnits="userSpaceOnUse"><stop class="uj7hgsb3u"/><stop offset="1" class="p88c31myn"/></radialGradient><radialGradient id="iKSVIie" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28528 0 0 -6.44557 19.726 13.433)" gradientUnits="userSpaceOnUse"><stop class="zoq8fuaif"/><stop offset="1" class="ycrcotb4u"/></radialGradient><radialGradient id="iChEZdb" cx="0" cy="0" r="1" gradientTransform="rotate(-121.569 14.197 3.947)scale(1.52213 1.61741)" gradientUnits="userSpaceOnUse"><stop class="ni-4se4rm"/><stop offset="1" class="wsh5tsbcf"/></radialGradient><radialGradient id="iTsVq9b" cx="0" cy="0" r="1" gradientTransform="matrix(1.75 -1.56249 1.85525 2.0779 10.594 18.093)" gradientUnits="userSpaceOnUse"><stop class="z26rrllgi"/><stop offset="1" class="fs9pa7bci"/></radialGradient><radialGradient id="iBQiaPe" cx="0" cy="0" r="1" gradientTransform="matrix(-.45554 -2.04401 .62995 -.1404 15.415 14.16)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="idWEWfb" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.2179 15.175 14.371)" gradientUnits="userSpaceOnUse"><stop class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="i7essOd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 16.813 12.304)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iYjJGRc" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 16.585 12.389)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="izUGykd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 12.449 12.304)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i7o7whc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.246 .275)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iYnBHOe" cx="0" cy="0" r="1" gradientTransform="rotate(-65.391 12.419 -1.897)scale(3.03069 1.55043)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="iXKvtSb" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 6.706 7.688)scale(4.8729 7.96691)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="imOgnyb" cx="0" cy="0" r="1" gradientTransform="matrix(-.21033 1.3672 -2.94145 -.45252 14.841 5.347)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><radialGradient id="i1J0ijc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.21875 1.75 -2.17983 -7.74618 23.463 6.204)" gradientUnits="userSpaceOnUse"><stop class="mdf3fza3l"/><stop offset=".687" class="ls9453boy"/><stop offset=".843" class="m026r4b6e"/></radialGradient><radialGradient id="iVmkACb" cx="0" cy="0" r="1" gradientTransform="rotate(141.18 10.736 7.664)scale(.43619)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="cz-qsgbfy"/><stop offset="1" class="j80tr6o9y"/></radialGradient><radialGradient id="iRQA0se" cx="0" cy="0" r="1" gradientTransform="matrix(.19922 -.48438 1.17186 .48198 23.586 7.347)" gradientUnits="userSpaceOnUse"><stop offset=".147" class="m8bo-jb-t"/><stop offset="1" class="wy7e69bbh"/></radialGradient><radialGradient id="iu94fIb" cx="0" cy="0" r="1" gradientTransform="matrix(.4375 .04684 -.05916 .55254 23.361 6.91)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="zk512ndyg"/><stop offset="1" class="hy0z0nf6k"/></radialGradient><radialGradient id="if1AEES" cx="0" cy="0" r="1" gradientTransform="matrix(2.20247 -1.61719 2.56784 3.49718 21.389 10.096)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="cnux6p8xn"/><stop offset="1" class="jaxt-o31p"/></radialGradient><radialGradient id="iqfCaLe" cx="0" cy="0" r="1" gradientTransform="matrix(2.53124 -1.40627 1.98705 3.57664 24.535 8.273)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="cnux6p8xn"/><stop offset="1" class="jaxt-o31p"/></radialGradient><filter id="ilP4xGd" width="15.268" height="15.768" x="7.121" y="3.623" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_28"/></filter><filter id="i2L0Q6b" width="3.368" height="3.218" x="8.336" y="11.293" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.376471 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_28"/></filter><filter id="iqyYemd" width="3.218" height="3.468" x="17.849" y="11.043" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.243137 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_28"/></filter><filter id="iYVr1vd" width="3.148" height="3.148" x="17.884" y="11.327" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_28" stdDeviation=".25"/></filter><filter id="iLZvJbc" width="2.648" height="2.648" x="8.64" y="11.577" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_28" stdDeviation=".125"/></filter><filter id="i6JCEoe" width="10.191" height="11.127" x="9.535" y="7.995" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_28"/></filter><filter id="ipoGvFd" width="2.877" height="3.682" x="13.03" y="11.896" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_28" stdDeviation=".25"/></filter><filter id="i8gsz0b" width="2.377" height="3.182" x="13.442" y="12.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_28" stdDeviation=".125"/></filter><filter id="iSTqtXb" width="3.702" height="1.526" x="12.78" y="15.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_28" stdDeviation=".05"/></filter><filter id="isHeSoe" width="3.001" height="1.285" x="15.573" y="11.497" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_28"/></filter><filter id="iFhWcIx" width="3.001" height="1.285" x="10.687" y="11.497" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_28"/></filter><filter id="itYuqvA" width="2.453" height="1.091" x="10.822" y="10.073" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_28"/></filter><filter id="ic1Hdqc" width="2.453" height="1.091" x="16.24" y="10.073" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_28"/></filter><filter id="iAWUppd" width=".787" height=".696" x="16.079" y="11.865" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_28" stdDeviation=".05"/></filter><filter id="icGBAze" width=".891" height=".913" x="16.918" y="11.94" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_28" stdDeviation=".1"/></filter><filter id="iBKe8Zc" width=".986" height="1.04" x="12.475" y="11.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_28" stdDeviation=".1"/></filter><filter id="igGWzEd" width=".913" height=".705" x="11.721" y="11.856" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_28" stdDeviation=".05"/></filter><filter id="i35zqYc" width="2.261" height=".978" x="16.27" y="10.195" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_28" stdDeviation=".1"/></filter><filter id="iSollUd" width="2.261" height=".978" x="10.818" y="10.195" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_28" stdDeviation=".1"/></filter><filter id="ivG9jvd" width="4.312" height="4.613" x="8.276" y="5.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.262745 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_28"/><feGaussianBlur result="effect2_foregroundBlur_4002_28" stdDeviation=".2"/></filter><filter id="iS47qvc" width="8.767" height="5.782" x="11.46" y="4.825" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_28"/><feGaussianBlur result="effect2_foregroundBlur_4002_28" stdDeviation=".125"/></filter><filter id="igA7lYw" width="1.145" height="2.31" x="11.439" y="6.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_28" stdDeviation=".1"/></filter><filter id="i7rUwcc" width="6.927" height="3.872" x="13.799" y="6.618" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_28" stdDeviation=".5"/></filter><filter id="ieDoAMd" width=".726" height=".726" x="23.418" y="6.587" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.52549 0 0 0 0 0.388235 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_28"/></filter><filter id="iukHNYc" width="3.834" height="4.387" x="20.96" y="7.388" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.45098 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_28"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.282353 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_28" result="effect2_innerShadow_4002_28"/></filter><filter id="iJWdytb" width="4.283" height="3.734" x="24.158" y="5.911" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.203922 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_28"/></filter><filter id="ihjOIcb" width="3.843" height="3.843" x="24.629" y="5.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_28" stdDeviation=".1"/></filter><filter id="iLhb6Me" width="2.734" height="2.734" x="25.183" y="6.436" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_28" stdDeviation=".1"/></filter><filter id="i9VaRDb" width="2.734" height="2.734" x="21.535" y="8.45" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_28" stdDeviation=".1"/></filter><filter id="iPru7id" width="3.805" height="3.805" x="21" y="7.915" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_28" stdDeviation=".1"/></filter><linearGradient id="iwviawe" x1="19.324" x2="12.519" y1="5.949" y2="18.553" gradientUnits="userSpaceOnUse"><stop class="c1nwhtznm"/><stop offset="1" class="ogqxd-bue"/></linearGradient><linearGradient id="ieqwvgd" x1="7.446" x2="21.822" y1="17.711" y2="17.711" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="i3U51ac" x1="7.446" x2="21.822" y1="17.681" y2="17.681" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iVp3Bmc" x1="8.387" x2="9.627" y1="12.989" y2="12.989" gradientUnits="userSpaceOnUse"><stop class="b9k-3ybvb"/><stop offset="1" class="vbw-bobru"/></linearGradient><linearGradient id="iuekKgn" x1="13.692" x2="14.631" y1="14.233" y2="14.233" gradientUnits="userSpaceOnUse"><stop class="rby1z7ber"/><stop offset="1" class="dl0nwov2w"/></linearGradient><linearGradient id="iz7tP3k" x1="14.631" x2="14.631" y1="15.032" y2="14.421" gradientUnits="userSpaceOnUse"><stop class="cyl8wapbv"/><stop offset="1" class="jplc2lvem"/></linearGradient><linearGradient id="iK9tPbb" x1="13.566" x2="14.027" y1="16.442" y2="15.729" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="ipTUJuc" x1="17.59" x2="17.277" y1="12.358" y2="12.552" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="idxvHEe" x1="13.192" x2="12.879" y1="12.358" y2="12.552" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="id2eeBc" x1="11.739" x2="12.284" y1="6.703" y2="7.977" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><linearGradient id="ipYPb9b" x1="24.941" x2="23.75" y1="5.049" y2="4.704" gradientUnits="userSpaceOnUse"><stop class="p9lsnsm5t"/><stop offset="1" class="lapvr59ed"/></linearGradient><linearGradient id="iwWxddP" x1="23.793" x2="23.867" y1="6.542" y2="6.253" gradientUnits="userSpaceOnUse"><stop offset=".16" class="zl0fwhbas"/><stop offset="1" class="lxc0fmbqt"/></linearGradient><linearGradient id="iaC38ue" x1="22.879" x2="23.144" y1="7.398" y2="6.101" gradientUnits="userSpaceOnUse"><stop class="p9lsnsm5t"/><stop offset="1" class="lapvr59ed"/></linearGradient><linearGradient id="irzfGIb" x1="24.29" x2="24.092" y1="7.48" y2="7.424" gradientUnits="userSpaceOnUse"><stop class="jd-vaq0no"/><stop offset="1" class="gof7ehbkx"/></linearGradient><linearGradient id="ipFIR2b" x1="23.629" x2="23.57" y1="7.57" y2="7.796" gradientUnits="userSpaceOnUse"><stop offset=".209" class="ni_6htbzm"/><stop offset="1" class="ajm38_jxm"/></linearGradient><linearGradient id="iGw8SZc" x1="24.879" x2="28.069" y1="8.172" y2="6.7" gradientUnits="userSpaceOnUse"><stop offset=".616" class="w5_7ycb6b"/><stop offset=".9" class="srm_r_guo"/></linearGradient><linearGradient id="i25s7Yc" x1="25.433" x2="27.566" y1="8.05" y2="7.066" gradientUnits="userSpaceOnUse"><stop offset=".247" class="jzjqx7qlk"/><stop offset=".669" class="gl3wl_9gz"/></linearGradient><linearGradient id="iGE3fSd" x1="21.785" x2="23.917" y1="10.064" y2="9.08" gradientUnits="userSpaceOnUse"><stop offset=".247" class="rraw6sbsp"/><stop offset=".669" class="r8ibvzbki"/></linearGradient><linearGradient id="iLnBePe" x1="24.554" x2="22.902" y1="9.276" y2="9.817" gradientUnits="userSpaceOnUse"><stop class="znwvjy5yx"/><stop offset="1" class="zi0lb2bns"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-getting-haircut-medium-dark" /></template>
<style>
.a-cgv50-r {
  d: path("M14.656 17.681h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.a4_5g-kex {
  fill-rule: evenodd;
  d: path("M24.45 6.655a.1.1 0 0 1 .122-.07l.36.095a.22.22 0 0 0 .216-.072a1.842 1.842 0 1 1-.412 1.52a.22.22 0 0 0-.152-.172l-.352-.094a.1.1 0 0 1-.07-.122zm1.663 1.87a.844.844 0 1 0 .872-1.444a.844.844 0 0 0-.872 1.445");
}

.a41xocxec {
  d: path("m24.334 2.644l-1.388 4.83l1.187.346l1.071-3.73a1.15 1.15 0 0 0-.784-1.421z");
}

.ai95fabuh {
  stop-color: var(--svg-color--986b5a, #986B5A);
  stop-opacity: 0;
}

.ajbrntixp {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.78 10.529c-.323-.079-1.125-.04-1.662.344");
}

.ajm38_jxm {
  stop-color: var(--svg-color--ff3178, #FF3178);
  stop-opacity: 0;
}

.av86ribkj {
  fill: var(--svg-color--352827, #352827);
  fill-rule: evenodd;
  d: path("m18.362 10.666l-.138.23za.268.268 0 0 1-.275.46l-.005-.002l-.022-.013l-.091-.046a3 3 0 0 0-.343-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 1 1-.093-.528c.513-.09.989 0 1.329.11a3.3 3.3 0 0 1 .526.22l.032.018l.01.005l.002.002z");
}

.ax9af2vtk {
  stop-color: var(--svg-color--875555, #875555);
  stop-opacity: 0;
}

.ay3imeglw {
  d: path("M16.75 12.016c.063.085-.07.189-.221.302s-.264.192-.327.107c-.064-.085.007-.245.158-.358c.152-.113.326-.136.39-.05");
}

.b9k-3ybvb {
  stop-color: var(--svg-color--6a4745, #6A4745);
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bof3uzbpf {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
}

.bqqvv7bor {
  fill-rule: evenodd;
  d: path("M23.005 7.442a.1.1 0 0 0-.124.068l-.104.357a.21.21 0 0 1-.174.149a1.842 1.842 0 1 0 1.514.433a.21.21 0 0 1-.068-.22l.102-.349a.1.1 0 0 0-.069-.124zm.741 2.391a.844.844 0 1 1-1.688 0a.844.844 0 0 1 1.688 0");
}

.bs2iicb4y {
  fill: var(--svg-color--000, #000);
  d: path("M16.304 12.72c0-.284.227-.511.51-.511a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.06-.235");
}

.c_9-m-bzq {
  d: path("M20.71 6.65c-1.262.462-2.101.413-2.648.171L16.89 9.673c1.29.054 3.8-.332 5.563-2.383c.843-.982.996-1.91.656-2.586c-.061-.122-.183-.172-.27-.148c-.086.023-.16.108-.187.207c-.162.566-.538 1.372-1.942 1.886");
}

.c1nwhtznm {
  stop-color: var(--svg-color--45363a, #45363A);
}

.c1uh7gbbk {
  fill: var(--svg-color--854e52, #854E52);
  d: path("M12.639 17.691h3.984v1.383c0 1.1-.892 1.813-1.992 1.813s-1.992-.713-1.992-1.813z");
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.cibiz2b0f {
  d: path("m14.248 12.54l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.645-.376-.765 0");
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnux6p8xn {
  stop-color: var(--svg-color--ff7046, #FF7046);
}

.cpuxbvbrp {
  stop-color: var(--svg-color--8752d9, #8752D9);
  stop-opacity: 0;
}

.crj44uotj {
  stop-color: var(--svg-color--996b5e, #996B5E);
}

.cuty5mbvc {
  stop-color: var(--svg-color--9775dd, #9775DD);
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cyl8wapbv {
  stop-color: var(--svg-color--7c455c, #7C455C);
}

.cz-qsgbfy {
  stop-color: var(--svg-color--ebdbe4, #EBDBE4);
}

.d0mty6dok {
  d: path("M7.317 20.827C5.044 22.79 3.61 25.676 3.61 28.893v.463h3.708z");
}

.da7h3oe0u {
  stop-color: var(--svg-color--743f5a, #743F5A);
  stop-opacity: 0;
}

.dablr4u0o {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.022 11.556c.653 0 1.204.45 1.355 1.058a.274.274 0 0 1-.268.341h-2.231a.23.23 0 0 1-.228-.272c.126-.64.69-1.127 1.372-1.127");
}

.dl0nwov2w {
  stop-color: var(--svg-color--744c45, #744C45);
  stop-opacity: 0;
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e45vwmmsf {
  d: path("M17.61 12.602a.84.84 0 0 0-.232-.462l-.26.285l.117.228z");
}

.egfidgb4a {
  fill: var(--svg-color--70404a, #70404A);
  d: path("m14.238 12.679l-.683 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.494-.377-.613 0");
}

.ej_uxe27h {
  fill: var(--svg-color--272528, #272528);
  d: path("M13.489 12.332c-.266-.466-.67-.835-1.538-.835c-.38 0-.747.105-1.072.369c-.27.217-.233.495-.025.599l.556.317c.652-.21 1.373-.239 2.079-.45");
}

.eo_7g0bzd {
  stop-color: var(--svg-color--5a3638, #5A3638);
}

.equqpob_m {
  d: path("M13.262 12.615c0-.289-.235-.48-.298-.539l-.289.28l.178.36z");
}

.f3tc_zfmh {
  stop-color: var(--svg-color--9a6fdb, #9A6FDB);
}

.f4vmrjbib {
  stop-color: var(--svg-color--8267b6, #8267B6);
}

.fs9pa7bci {
  stop-color: var(--svg-color--6e494b, #6E494B);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fx1tjiblm {
  stop-color: var(--svg-color--755041, #755041);
  stop-opacity: 0;
}

.fxt5p0b8w {
  stop-color: var(--svg-color--8052c3, #8052C3);
  stop-opacity: 0;
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.g6dgamb9p {
  stop-color: var(--svg-color--8654d1, #8654D1);
}

.gcfqr7bfg {
  stop-color: var(--svg-color--714350, #714350);
  stop-opacity: 0;
}

.gl3wl_9gz {
  stop-color: var(--svg-color--ff7e7a, #FF7E7A);
  stop-opacity: 0;
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gm_5gldko {
  cx: 26.551px;
  cy: 7.804px;
  r: 1.671px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.gof7ehbkx {
  stop-color: var(--svg-color--a2889f, #A2889F);
  stop-opacity: 0;
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h064k9b1n {
  d: path("M3.609 28.893c0-5.916 4.854-10.711 10.842-10.711s10.842 4.795 10.842 10.71v.464H3.609z");
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hnlppfbil {
  stop-color: var(--svg-color--9860d3, #9860D3);
  stop-opacity: 0;
}

.hpeo8yzih {
  stop-color: var(--svg-color--9d7e72, #9D7E72);
}

.hph--cc6x {
  stop-color: var(--svg-color--8d6262, #8D6262);
}

.hqyrwybyl {
  fill: var(--svg-color--2f1920, #2F1920);
  d: path("M14.027 5.11c-1.132-.25-2.15.88-2.267 1.3c1.052 3.545 3.713 3.35 6.34 3.059c1.573-.175 1.743.542 1.877.888c0-3.932-3.344-4.67-5.921-5.24z");
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.hy0z0nf6k {
  stop-color: var(--svg-color--a4888c, #A4888C);
  stop-opacity: 0;
}

.i1zo_pb3h {
  fill: var(--svg-color--2a191e, #2A191E);
  d: path("M9.561 6.913c.566-.6 1.637-.6 2.131-.51l.396 1.29c-.253-.04-.478.05-.668.235c-.448 1.26-1.99 1.955-2.704 2.145c-.148-1.492.11-2.38.845-3.16");
}

.i4_k3omhh {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.24 11.556c-.654 0-1.205.45-1.355 1.058a.274.274 0 0 0 .268.341h2.23a.23.23 0 0 0 .228-.272a1.4 1.4 0 0 0-1.371-1.127");
}

.i5bhawuus {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M15.773 12.332c.265-.466.669-.835 1.537-.835c.38 0 .747.105 1.073.369c.269.217.233.495.024.599l-.555.317c-.652-.21-1.373-.239-2.08-.45");
}

.ia1qxot8h {
  d: path("M16.815 11.827a.892.892 0 0 1 .86 1.128H15.95a.896.896 0 0 1 .864-1.128");
}

.iwql9tbwr {
  stop-color: var(--svg-color--8752d9, #8752D9);
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j4dxu6b2c {
  fill: var(--svg-color--88014f, #88014F);
  d: path("M14.63 15.813c-.52 0-1.01-.125-1.42-.345c-.142-.073-.293.09-.204.22a1.932 1.932 0 0 0 3.25 0c.088-.136-.063-.293-.204-.22a3 3 0 0 1-1.421.345");
}

.j80tr6o9y {
  stop-color: var(--svg-color--c7b1b5, #C7B1B5);
}

.jaf6nfbfs {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
  stop-opacity: 0;
}

.jaxt-o31p {
  stop-color: var(--svg-color--ff2d78, #FF2D78);
}

.jd-vaq0no {
  stop-color: var(--svg-color--93768e, #93768E);
}

.je8i96bea {
  stop-color: var(--svg-color--845b99, #845B99);
  stop-opacity: 0;
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jplc2lvem {
  stop-color: var(--svg-color--7c455c, #7C455C);
  stop-opacity: 0;
}

.jrx3i8b1t {
  d: path("m19.686 5.22l5.42 1.537l-.338 1.189l-4.312-1.223a1.15 1.15 0 0 1-.793-1.42z");
}

.jzjqx7qlk {
  stop-color: var(--svg-color--ff7e7a, #FF7E7A);
}

.k_9tcyber {
  d: path("M21.584 29.356h3.709v-.463c0-3.217-1.436-6.103-3.709-8.066z");
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kitn3twkh {
  stop-color: var(--svg-color--5f363f, #5F363F);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.l__dw9bpv {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
  stop-opacity: 0;
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lapvr59ed {
  stop-color: var(--svg-color--d9b4c8, #D9B4C8);
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

.ls9453boy {
  stop-color: var(--svg-color--25171e, #25171E);
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.lxc0fmbqt {
  stop-color: var(--svg-color--c0a0b5, #C0A0B5);
  stop-opacity: 0;
}

.m026r4b6e {
  stop-color: var(--svg-color--25171e, #25171E);
  stop-opacity: 0;
}

.m5wv9vbgf {
  stop-color: var(--svg-color--a46ee0, #A46EE0);
}

.m8bo-jb-t {
  stop-color: var(--svg-color--996e9f, #996E9F);
}

.m8gsznlzl {
  cx: 23.731px;
  cy: 7px;
  r: 0.313px;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mdf3fza3l {
  stop-color: var(--svg-color--291028, #291028);
}

.mg10me7tz {
  stop-color: var(--svg-color--794958, #794958);
  stop-opacity: 0;
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mt9k2qzvi {
  stop-color: var(--svg-color--755041, #755041);
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.nhus6q3at {
  stop-color: var(--svg-color--9a6fdb, #9A6FDB);
  stop-opacity: 0;
}

.ni_6htbzm {
  stop-color: var(--svg-color--b71143, #B71143);
}

.ni-4se4rm {
  stop-color: var(--svg-color--836462, #836462);
}

.nrqb0zb7k {
  d: path("M9.964 13.976a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.o3wo53bzp {
  stop-color: var(--svg-color--5a3638, #5A3638);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ogqxd-bue {
  stop-color: var(--svg-color--1c151f, #1C151F);
}

.ok0s313ee {
  stop-color: var(--svg-color--8956cf, #8956CF);
}

.olqyf7fmb {
  stop-color: var(--svg-color--875e5e, #875E5E);
}

.opgioqbtx {
  stop-color: var(--svg-color--805c54, #805C54);
  stop-opacity: 0;
}

.osxg47drp {
  stop-color: var(--svg-color--743f5a, #743F5A);
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.p47-3c-mm {
  stop-color: var(--svg-color--ae81f2, #AE81F2);
}

.p5t7enbym {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.63 15.813c-.52 0-1.01-.125-1.42-.345c-.142-.073-.293.09-.204.22a1.932 1.932 0 0 0 3.25 0c.088-.136-.063-.293-.204-.22a3 3 0 0 1-1.421.345Z");
}

.p88c31myn {
  stop-color: var(--svg-color--815a5b, #815A5B);
  stop-opacity: 0;
}

.p9lsnsm5t {
  stop-color: var(--svg-color--9b8299, #9B8299);
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pzph9acww {
  d: path("M9.945 14.51a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.219");
}

.qdra35bpg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M11.74 6.36c.023.242.234 1.156.544 1.709");
}

.qls0ocb-h {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.57 10.529c.323-.079 1.125-.04 1.661.344");
}

.qu42xotyf {
  fill: var(--svg-color--845f59, #845F59);
  d: path("M19.458 13.976a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.quqm6o37z {
  fill: var(--svg-color--352827, #352827);
  d: path("m11.233 11.124l-.005.002a.268.268 0 0 1-.275-.46l.001-.001l.003-.002l.01-.005a2 2 0 0 1 .148-.077a3 3 0 0 1 .41-.162c.34-.108.816-.2 1.329-.109a.268.268 0 1 1-.094.528a2.3 2.3 0 0 0-1.072.092a3 3 0 0 0-.455.194");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.r_t9aq_-g {
  d: path("M14.986 17.681c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r-plgxbvx {
  stop-color: var(--svg-color--845b99, #845B99);
}

.r8ibvzbki {
  stop-color: var(--svg-color--ff9266, #FF9266);
  stop-opacity: 0;
}

.rby1z7ber {
  stop-color: var(--svg-color--744c45, #744C45);
}

.rr5dsobch {
  fill: var(--svg-color--8a6058, #8A6058);
  d: path("m14.248 12.54l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.645-.376-.765 0");
}

.rraw6sbsp {
  stop-color: var(--svg-color--ff9266, #FF9266);
}

.s5j9zog_u {
  d: path("M12.639 17.691h3.984v1.383c0 1.1-.892 1.813-1.992 1.813s-1.992-.713-1.992-1.813z");
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sitfol3cj {
  fill-rule: evenodd;
  d: path("M21.816 14.311c.212-.435.324-.92.324-1.427c0-.467-.096-.906-.269-1.305h.005a3 3 0 0 0-.28-.513l-.003-.003a3.24 3.24 0 0 1-.526-1.771v-.01a3.3 3.3 0 0 0-3.3-3.3a.54.54 0 0 1-.455-.232a3.3 3.3 0 0 0-2.682-1.377a3.3 3.3 0 0 0-2.68 1.377a.56.56 0 0 1-.456.232l-.085.001a3.3 3.3 0 0 0-3.214 3.299v.01a3.24 3.24 0 0 1-.526 1.77l-.002.004a3.3 3.3 0 0 0-.22 3.245c.07.142.07.314 0 .456a3.213 3.213 0 0 0 2.894 4.625h8.581a3.213 3.213 0 0 0 3.219-3.219c0-.506-.122-.981-.324-1.406a.51.51 0 0 1 0-.456M9.556 11.64h-.013l1.199 2.355c.123 2.803 1.217 0 3.888 0c2.672 0 3.837 3.12 3.96.317l1.136-3.197c-.054-1.245-.956-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.19-1.673a.264.264 0 0 0-.46.05l-.083.194a2.3 2.3 0 0 1-1.24 1.255q-.027.013-.052.02c-.236.123-.79.49-.81 1.44l.01.306z");
}

.sncijkqpo {
  stop-color: var(--svg-color--643a7c, #643A7C);
  stop-opacity: 0;
}

.srm_r_guo {
  stop-color: var(--svg-color--ff6792, #FF6792);
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.su9pt7edc {
  d: path("M9.543 11.639h.013l-.01-.265l-.011-.307c.02-.949.574-1.316.81-1.438l.051-.02q.027-.013.052-.021a2.3 2.3 0 0 0 1.19-1.235l.081-.193a.264.264 0 0 1 .462-.051a3.86 3.86 0 0 0 3.189 1.673h3.22c.18 0 1.082.087 1.136 1.332l-.119 3.073c-.123 2.803-2.312 4.684-4.983 4.684s-4.86-1.881-4.983-4.684z");
}

.t9k87pm2r {
  stop-color: var(--svg-color--875555, #875555);
}

.tgx7usrie {
  d: path("M12.447 11.827a.892.892 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.893");
}

.tlhm2gbow {
  fill: var(--svg-color--47383d, #47383D);
  d: path("m17.037 8.72l-1.426.263a.688.688 0 1 1-.125-1.365h2.341c1.384 0 1.843 1.395 1.899 1.872a3.15 3.15 0 0 0-2.69-.77");
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.tu-1otsuf {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.75 12.016c.063.085-.07.189-.221.302s-.264.192-.327.107c-.064-.085.007-.245.158-.358c.152-.113.326-.136.39-.05");
}

.u0qkrccus {
  stop-color: var(--svg-color--6c394d, #6C394D);
  stop-opacity: 0;
}

.u4cmqnbdb {
  stop-color: var(--svg-color--412558, #412558);
}

.uelu8baaf {
  fill: var(--svg-color--5f3c45, #5F3C45);
  d: path("M9.964 13.976a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.uj7hgsb3u {
  stop-color: var(--svg-color--815a5b, #815A5B);
}

.uke-p0u6q {
  cx: 12.177px;
  cy: 12.209px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.up8l18w-p {
  stop-color: var(--svg-color--986b5a, #986B5A);
}

.uxe1igbwt {
  cx: 22.902px;
  cy: 9.817px;
  r: 1.117px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.v_ah93bpt {
  d: path("M14.027 5.11c-1.132-.25-2.15.88-2.267 1.3c1.052 3.545 3.713 3.35 6.34 3.059c1.573-.175 1.743.542 1.877.888c0-3.932-3.344-4.67-5.921-5.24z");
}

.v83a3u3_r {
  cx: 26.551px;
  cy: 7.804px;
  r: 1.117px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.vbw-bobru {
  stop-color: var(--svg-color--533335, #533335);
}

.vzbvt7b3z {
  stop-color: var(--svg-color--a46bd8, #A46BD8);
  stop-opacity: 0;
}

.w5_7ycb6b {
  stop-color: var(--svg-color--ff4f4f, #FF4F4F);
}

.wg3eepbwp {
  stop-color: var(--svg-color--805c54, #805C54);
}

.wj0k-xifb {
  cx: 22.902px;
  cy: 9.817px;
  r: 1.652px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.wm0pkrbcc {
  d: path("M9.561 6.913c.566-.6 1.637-.6 2.131-.51l.396 1.29c-.253-.04-.478.05-.668.235c-.448 1.26-1.99 1.955-2.704 2.145c-.148-1.492.11-2.38.845-3.16");
}

.wrh2b4bbx {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
}

.wsh5tsbcf {
  stop-color: var(--svg-color--836462, #836462);
  stop-opacity: 0;
}

.wy7e69bbh {
  stop-color: var(--svg-color--c8b3b7, #C8B3B7);
  stop-opacity: 0;
}

.x_ik4kbfh {
  stop-color: var(--svg-color--714350, #714350);
}

.x6yzvt1od {
  d: path("M19.458 13.976a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.x7bl4zbkb {
  fill: var(--svg-color--955ece, #955ECE);
  d: path("M7.317 20.827C5.044 22.79 3.61 25.676 3.61 28.893v.463h3.708z");
}

.xa_8_1bke {
  cx: 12.177px;
  cy: 12.209px;
  rx: 0.39px;
  ry: 0.197px;
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xzg31ccqm {
  d: path("M19.458 14.51a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.219");
}

.yamoh3dov {
  stop-color: var(--svg-color--764e4c, #764E4C);
}

.yb6y2bchp {
  fill: var(--svg-color--000, #000);
  d: path("M12.958 12.72a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.ycrcotb4u {
  stop-color: var(--svg-color--986f60, #986F60);
  stop-opacity: 0;
}

.z26rrllgi {
  stop-color: var(--svg-color--6e494b, #6E494B);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.zduonub6o {
  stop-color: var(--svg-color--a677eb, #A677EB);
}

.zg-89ub5t {
  stop-color: var(--svg-color--8d6262, #8D6262);
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

.znwvjy5yx {
  stop-color: var(--svg-color--ff5c88, #FF5C88);
}

.zoq8fuaif {
  stop-color: var(--svg-color--986f60, #986F60);
}

.zq9vt79xj {
  stop-color: var(--svg-color--6c394d, #6C394D);
}

</style>
