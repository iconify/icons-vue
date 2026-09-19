<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iGyeQuc)"><path fill="url(#im9sInc)" clip-rule="evenodd" class="f1zcm9akr"/><path fill="url(#iQ91JuG)" clip-rule="evenodd" class="f1zcm9akr"/><path fill="url(#i9vFNrc)" clip-rule="evenodd" class="f1zcm9akr"/><path fill="url(#iYi4Gfc)" clip-rule="evenodd" class="f1zcm9akr"/><path fill="url(#inOPFde)" clip-rule="evenodd" class="f1zcm9akr"/><path fill="url(#iP6WJvd)" clip-rule="evenodd" class="f1zcm9akr"/><path fill="url(#iayGWGc)" clip-rule="evenodd" class="f1zcm9akr"/><path fill="url(#iOSeZdc)" clip-rule="evenodd" class="f1zcm9akr"/><path fill="url(#iuZd3eb)" clip-rule="evenodd" class="f1zcm9akr"/><path fill="url(#i5xubHW)" clip-rule="evenodd" class="f1zcm9akr"/><path fill="url(#ibYaAgb)" clip-rule="evenodd" class="f1zcm9akr"/></g><path fill="url(#i6iFVUb)" class="c7t_ubv2h"/><path fill="url(#iFem5Ib)" class="c7t_ubv2h"/><g filter="url(#iD9b0Ph)"><path class="z_fvebb5d"/></g><g filter="url(#iy737sO)"><path class="z6rpzli7h"/></g><path fill="url(#iiaYuFe)" class="hhpztvblo"/><path fill="url(#itRn15b)" class="hhpztvblo"/><path fill="url(#ieNGVne)" class="hhpztvblo"/><path fill="url(#iMW5GGb)" class="y8tu8dbcm"/><path fill="url(#iuLvfbR)" class="y8tu8dbcm"/><g filter="url(#i2o9Lsd)"><path fill="url(#iVQobQc)" class="jtck_gbig"/><path fill="url(#iM5kmgb)" class="jtck_gbig"/><path fill="url(#ivj2yoo)" class="jtck_gbig"/></g><path fill="url(#iyCVi6b)" class="jtck_gbig"/><path fill="url(#i5TpvKc)" class="jtck_gbig"/><g filter="url(#iibYNAd)"><path fill="url(#iubvqrb)" class="hmuhvgbey"/></g><g filter="url(#izuczhc)"><path class="ix4m4bceo"/><path fill="url(#iFhrcyd)" class="vo75e7bfz"/></g><path fill="url(#iAyOK1c)" class="apm92hb5d"/><path fill="url(#iaJmMoe)" class="apm92hb5d"/><path fill="url(#iReq52b)" class="jhz75cc3u"/><path fill="url(#iKu1Jjc)" class="h6-v2u2iz"/><path fill="url(#iqKI9Ld)" class="h6-v2u2iz"/><path fill="url(#i83jFwa)" class="h6-v2u2iz"/><path fill="url(#iJiPXQd)" class="mke2pz_al"/><path fill="url(#iUkUQ2b)" class="xbfu1itob"/><path fill="url(#iUhqAAe)" class="tgiuuaboq"/><g filter="url(#iqRI5fS)"><path fill="url(#i0CLjEb)" class="obcwk1b3o"/></g><g filter="url(#i1FFpiU)"><path fill="url(#itnNneb)" class="r9488kb6n"/><path fill="url(#ihGbWke)" class="r9488kb6n"/></g><g filter="url(#isZln8V)"><path class="c1iziib3t"/><path fill="url(#iWEynWU)" class="gduosbcxu"/></g><g filter="url(#iDLUZLd)"><path class="sj28mac3i"/><path fill="url(#iVoa8Lc)" class="ib_op1bfg"/></g><g filter="url(#ibNplYs)"><path fill="url(#iGdcoKI)" class="twkot3bqm"/><path fill="url(#iVc84Pb)" class="twkot3bqm"/><path fill="url(#io36m6b)" class="twkot3bqm"/><path fill="url(#in5n2Ee)" class="twkot3bqm"/><path fill="url(#iNlGXhd)" class="twkot3bqm"/><path fill="url(#iWX8HSe)" class="twkot3bqm"/><path fill="url(#ipzxi7C)" class="twkot3bqm"/><path fill="url(#iHSQ0dd)" class="twkot3bqm"/></g><path fill="url(#iEHqpJe)" class="twkot3bqm"/><path fill="url(#iyszCjc)" class="twkot3bqm"/><path fill="url(#iMcYDik)" class="twkot3bqm"/><g filter="url(#iPBUCNA)"><path class="pwom2q-fh"/></g><g filter="url(#iRiukpi)"><path class="hr-qb25sn"/><path fill="url(#i9YuIyN)" class="x-4htd_rb"/><path fill="url(#in18X7j)" class="x-4htd_rb"/><path fill="url(#iCCuX2d)" class="x-4htd_rb"/><path fill="url(#iNikDuc)" class="x-4htd_rb"/></g><path fill="url(#iQto2od)" class="x-4htd_rb"/><path fill="url(#iXe53De)" class="x-4htd_rb"/><path stroke="url(#ih00q6d)" class="z71m_ba6i"/><g filter="url(#i8iTYBd)"><path class="pzfns_6uz"/></g><g filter="url(#iKJRZqe)"><path class="kil_u_idv"/></g><g filter="url(#ivImYme)"><path class="xjwttd8ow"/></g><g filter="url(#ixHj7Ic)"><path clip-rule="evenodd" class="qsvq8gn7f"/></g><path class="gc98rzbmn"/><path fill="url(#ijiTRYb)" class="dppebsd1o"/><path class="ja_9lc_2e"/><g filter="url(#iyrSGue)"><path class="m7tcxo76r"/><path fill="url(#itgvc3c)" class="fohaseb4j"/></g><g filter="url(#iMSlSDb)"><path fill="url(#iMV5GWd)" class="hvsbaddlf"/></g><path class="ri9l6nbtx"/><path fill="url(#i0cQoPr)" class="r88deebyo"/><path class="ye5gqoics"/><g filter="url(#iwGY4gd)"><path fill="url(#iIgGFUc)" class="hdf-adbmu"/></g><g filter="url(#iWby7Me)"><ellipse transform="rotate(-27.914 13.532 10.309)" class="ran5uq2mg"/><ellipse fill="url(#iBOKJPO)" transform="rotate(-27.914 13.532 10.309)" class="c6vz32b3d"/></g><g filter="url(#ifmpKoc)"><path class="v7yg4rbyg"/></g><g filter="url(#i4pBmOc)"><path class="d00heltoe"/></g><g filter="url(#izkTSBb)"><path class="p4vy1ovbe"/><path fill="url(#i78YTHb)" class="qtc95bbzx"/></g><g filter="url(#iAvWxmb)"><path class="kd-4c0ovp"/><path fill="url(#iAXW9Rd)" class="uv1mp4g3h"/><path fill="url(#idffzWd)" class="uv1mp4g3h"/></g><g filter="url(#iZNsSZc)"><path stroke="url(#iI1Orna)" class="yad6lvxsv"/></g><g filter="url(#ixSv3Hc)"><path class="x0u1810qj"/></g><defs><radialGradient id="iQ91JuG" cx="0" cy="0" r="1" gradientTransform="matrix(-.60337 4.55908 -5.69522 -.75373 15.683 13.502)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="i9vFNrc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88301 1.94432 -2.5547 -3.78806 12.867 13.77)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="iYi4Gfc" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.798 8.364)scale(2.15225 1.65263)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="inOPFde" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 3.218 7.848)scale(2.47506 1.74346)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="iP6WJvd" cx="0" cy="0" r="1" gradientTransform="rotate(62.272 3.797 11.789)scale(2.95399 4.10059)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="iayGWGc" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 9.869 7.03)scale(2.03849 2.84876)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iOSeZdc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.11855 -3.84482 23.494 10.15)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="iuZd3eb" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.61 8.194)scale(2.90248 3.69733)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="i5xubHW" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 13.119 -3.552)scale(2.80034 2.21491)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="ibYaAgb" cx="0" cy="0" r="1" gradientTransform="matrix(1.50392 .15775 -.2556 2.43678 9.843 10.114)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="iFem5Ib" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16.4313 6.37009 0 22.995 25.118)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="m5bm-ccxd"/><stop offset="1" class="q8ootib3t"/></radialGradient><radialGradient id="iiaYuFe" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.1215 -4.59696 0 16 22.69)" gradientUnits="userSpaceOnUse"><stop offset=".397" class="wdy63qb5p"/><stop offset="1" class="gkzmut59n"/></radialGradient><radialGradient id="iMW5GGb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.3135 1.68433 0 25 29.625)" gradientUnits="userSpaceOnUse"><stop class="omh3jbc5e"/><stop offset="1" class="g1k32m_rh"/></radialGradient><radialGradient id="ivj2yoo" cx="0" cy="0" r="1" gradientTransform="rotate(126.18 2.798 11.48)scale(2.59394 3.59462)" gradientUnits="userSpaceOnUse"><stop class="yfhz1ybyq"/><stop offset="1" class="kyt4h2bsk"/></radialGradient><radialGradient id="i5TpvKc" cx="0" cy="0" r="1" gradientTransform="matrix(1.09375 -.3125 .15357 .53751 11.395 19.381)" gradientUnits="userSpaceOnUse"><stop offset=".241" class="som6k-b6q"/><stop offset="1" class="pc2b66ykc"/></radialGradient><radialGradient id="iAyOK1c" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.75 -4.3769 0 16 18.14)" gradientUnits="userSpaceOnUse"><stop offset=".362" class="ft6yvtbqk"/><stop offset="1" class="i_25dj3ib"/></radialGradient><radialGradient id="iaJmMoe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.1875 6.81546 0 16 20.637)" gradientUnits="userSpaceOnUse"><stop offset=".533" class="kx98i3bkm"/><stop offset=".876" class="mf716dhmi"/></radialGradient><radialGradient id="iKu1Jjc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.8125 -3.45478 0 15.983 21.03)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="lv0iykbih"/><stop offset=".94" class="s3tb_6b2n"/></radialGradient><radialGradient id="iJiPXQd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.3026 -2.71576 0 16.03 16.886)" gradientUnits="userSpaceOnUse"><stop class="dfz7so2-c"/><stop offset="1" class="mabnc95ph"/></radialGradient><radialGradient id="itnNneb" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 20.025 11.44)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="olqyf7fmb"/><stop offset=".944" class="hpeo8yzih"/></radialGradient><radialGradient id="ihGbWke" cx="0" cy="0" r="1" gradientTransform="matrix(1.31577 .7375 -.2085 .37199 21.055 9.32)" gradientUnits="userSpaceOnUse"><stop class="mt9k2qzvi"/><stop offset="1" class="fx1tjiblm"/></radialGradient><radialGradient id="iWEynWU" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 20.377 11.114)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="l__dw9bpv"/><stop offset="1" class="wrh2b4bbx"/></radialGradient><radialGradient id="iVoa8Lc" cx="0" cy="0" r="1" gradientTransform="rotate(180 5.692 5.5)scale(1.05596)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="o3wo53bzp"/><stop offset="1" class="eo_7g0bzd"/></radialGradient><radialGradient id="iGdcoKI" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50358 2.99902 -4.01413 -8.70492 18.844 10.464)" gradientUnits="userSpaceOnUse"><stop class="crj44uotj"/><stop offset="1" class="yamoh3dov"/></radialGradient><radialGradient id="iVc84Pb" cx="0" cy="0" r="1" gradientTransform="rotate(156.249 7.788 7.547)scale(2.38203 1.65881)" gradientUnits="userSpaceOnUse"><stop class="up8l18w-p"/><stop offset="1" class="ai95fabuh"/></radialGradient><radialGradient id="io36m6b" cx="0" cy="0" r="1" gradientTransform="matrix(1.28915 -3.92836 4.98436 1.6357 13.823 16.972)" gradientUnits="userSpaceOnUse"><stop class="osxg47drp"/><stop offset="1" class="da7h3oe0u"/></radialGradient><radialGradient id="in5n2Ee" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28468 7.37319 -9.2164 -1.60583 17.008 10.048)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="mg10me7tz"/><stop offset="1" class="kitn3twkh"/></radialGradient><radialGradient id="iNlGXhd" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.305 6.962)scale(7.03739 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="opgioqbtx"/><stop offset="1" class="wg3eepbwp"/></radialGradient><radialGradient id="iWX8HSe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.286 10.046)" gradientUnits="userSpaceOnUse"><stop class="t9k87pm2r"/><stop offset="1" class="ax9af2vtk"/></radialGradient><radialGradient id="ipzxi7C" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 13.909 9.817)" gradientUnits="userSpaceOnUse"><stop class="x_ik4kbfh"/><stop offset="1" class="gcfqr7bfg"/></radialGradient><radialGradient id="iHSQ0dd" cx="0" cy="0" r="1" gradientTransform="matrix(-.87016 3.22674 -2.58193 -.69627 17.368 7.73)" gradientUnits="userSpaceOnUse"><stop class="uj7hgsb3u"/><stop offset="1" class="p88c31myn"/></radialGradient><radialGradient id="iEHqpJe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28528 0 0 -6.44557 21.08 11.533)" gradientUnits="userSpaceOnUse"><stop class="zoq8fuaif"/><stop offset="1" class="ycrcotb4u"/></radialGradient><radialGradient id="iyszCjc" cx="0" cy="0" r="1" gradientTransform="rotate(-121.569 14.343 2.618)scale(1.52213 1.61741)" gradientUnits="userSpaceOnUse"><stop class="ni-4se4rm"/><stop offset="1" class="wsh5tsbcf"/></radialGradient><radialGradient id="iMcYDik" cx="0" cy="0" r="1" gradientTransform="matrix(1.75 -1.56249 1.85525 2.0779 11.949 16.194)" gradientUnits="userSpaceOnUse"><stop class="z26rrllgi"/><stop offset="1" class="fs9pa7bci"/></radialGradient><radialGradient id="i9YuIyN" cx="0" cy="0" r="1" gradientTransform="matrix(-.45554 -2.04401 .62995 -.1404 16.77 12.26)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="iNikDuc" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.2179 16.53 12.472)" gradientUnits="userSpaceOnUse"><stop class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="iXe53De" cx="0" cy="0" r="1" gradientTransform="rotate(145.529 6.339 8.476)scale(1.66326 1.99898)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="wln98ypvp"/><stop offset="1" class="p13423bzd"/></radialGradient><radialGradient id="ijiTRYb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.167 10.405)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="itgvc3c" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 17.939 10.489)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i0cQoPr" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.803 10.405)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iBOKJPO" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.988 -1.341)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i78YTHb" cx="0" cy="0" r="1" gradientTransform="rotate(-65.391 11.616 -3.902)scale(3.03069 1.55043)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="iAXW9Rd" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 7.98 7.164)scale(4.8729 7.96691)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="idffzWd" cx="0" cy="0" r="1" gradientTransform="matrix(-.21033 1.3672 -2.94145 -.45252 16.196 3.445)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><filter id="iGyeQuc" width="15.268" height="15.768" x="8.476" y="1.724" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2097"/></filter><filter id="iD9b0Ph" width="6.556" height="14.595" x="9.212" y="15.472" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2097" stdDeviation=".5"/></filter><filter id="iy737sO" width="3.95" height="13.362" x="17.96" y="15.95" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2097" stdDeviation=".375"/></filter><filter id="i2o9Lsd" width="2.897" height="14" x="10.503" y="15.715" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.368627 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2097"/></filter><filter id="iibYNAd" width="2.734" height="2.883" x="14.624" y="17.852" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0980392 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2097"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0980392 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2097" result="effect2_innerShadow_4002_2097"/></filter><filter id="izuczhc" width="2.902" height="14.05" x="18.61" y="15.665" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.415686 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2097"/></filter><filter id="iqRI5fS" width="3.368" height="3.218" x="9.69" y="9.393" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.376471 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2097"/></filter><filter id="i1FFpiU" width="3.218" height="3.468" x="19.203" y="9.143" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.243137 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2097"/></filter><filter id="isZln8V" width="3.148" height="3.148" x="19.238" y="9.428" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2097" stdDeviation=".25"/></filter><filter id="iDLUZLd" width="2.648" height="2.648" x="9.995" y="9.678" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2097" stdDeviation=".125"/></filter><filter id="ibNplYs" width="10.191" height="11.127" x="10.889" y="6.095" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2097"/></filter><filter id="iPBUCNA" width="2.877" height="3.682" x="14.384" y="9.997" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2097" stdDeviation=".25"/></filter><filter id="iRiukpi" width="2.377" height="3.182" x="14.796" y="10.108" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2097" stdDeviation=".125"/></filter><filter id="i8iTYBd" width="3.001" height="1.285" x="16.927" y="9.597" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2097"/></filter><filter id="iKJRZqe" width="3.001" height="1.285" x="12.042" y="9.597" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2097"/></filter><filter id="ivImYme" width="2.453" height="1.091" x="12.177" y="8.174" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2097"/></filter><filter id="ixHj7Ic" width="2.453" height="1.091" x="17.594" y="8.174" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2097"/></filter><filter id="iyrSGue" width=".787" height=".696" x="17.433" y="9.965" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2097" stdDeviation=".05"/></filter><filter id="iMSlSDb" width=".891" height=".913" x="18.273" y="10.04" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2097" stdDeviation=".1"/></filter><filter id="iwGY4gd" width=".986" height="1.04" x="13.83" y="9.976" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2097" stdDeviation=".1"/></filter><filter id="iWby7Me" width=".913" height=".705" x="13.075" y="9.957" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2097" stdDeviation=".05"/></filter><filter id="ifmpKoc" width="2.661" height="1.378" x="17.424" y="8.096" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2097" stdDeviation=".2"/></filter><filter id="i4pBmOc" width="2.661" height="1.378" x="11.973" y="8.096" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2097" stdDeviation=".2"/></filter><filter id="izkTSBb" width="4.312" height="4.613" x="9.631" y="4.06" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.262745 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2097"/><feGaussianBlur result="effect2_foregroundBlur_4002_2097" stdDeviation=".2"/></filter><filter id="iAvWxmb" width="8.767" height="5.782" x="12.815" y="2.925" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2097"/><feGaussianBlur result="effect2_foregroundBlur_4002_2097" stdDeviation=".125"/></filter><filter id="iZNsSZc" width="1.145" height="2.31" x="12.794" y="4.16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2097" stdDeviation=".1"/></filter><filter id="ixSv3Hc" width="6.927" height="3.872" x="15.153" y="4.718" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2097" stdDeviation=".5"/></filter><linearGradient id="im9sInc" x1="20.678" x2="13.873" y1="4.049" y2="16.654" gradientUnits="userSpaceOnUse"><stop class="c1nwhtznm"/><stop offset="1" class="ogqxd-bue"/></linearGradient><linearGradient id="i6iFVUb" x1="16" x2="16" y1="15.937" y2="30.874" gradientUnits="userSpaceOnUse"><stop class="hac9w68gp"/><stop offset="1" class="u61ykmvtc"/></linearGradient><linearGradient id="itRn15b" x1="18.903" x2="17.059" y1="24.936" y2="24.936" gradientUnits="userSpaceOnUse"><stop class="ugh29hhiz"/><stop offset="1" class="knib4pb5u"/></linearGradient><linearGradient id="ieNGVne" x1="15.591" x2="15.669" y1="17.483" y2="21.374" gradientUnits="userSpaceOnUse"><stop class="ft2atdbel"/><stop offset="1" class="r8964-bmu"/></linearGradient><linearGradient id="iuLvfbR" x1="23" x2="23.744" y1="29.112" y2="29.088" gradientUnits="userSpaceOnUse"><stop offset=".276" class="alwwvg18b"/><stop offset="1" class="r8-nbsf4i"/></linearGradient><linearGradient id="iVQobQc" x1="11.902" x2="11.902" y1="15.715" y2="29.615" gradientUnits="userSpaceOnUse"><stop class="j-er45bzw"/><stop offset=".524" class="iwz00abqx"/></linearGradient><linearGradient id="iM5kmgb" x1="13.671" x2="13.05" y1="22.174" y2="22.174" gradientUnits="userSpaceOnUse"><stop class="recxkftoe"/><stop offset="1" class="btkjyionj"/></linearGradient><linearGradient id="iyCVi6b" x1="11.902" x2="12.839" y1="25.591" y2="25.189" gradientUnits="userSpaceOnUse"><stop offset=".196" class="yqlqjsfuk"/><stop offset="1" class="c8t-c_brq"/></linearGradient><linearGradient id="iubvqrb" x1="15.988" x2="15.988" y1="18.608" y2="20.593" gradientUnits="userSpaceOnUse"><stop offset=".006" class="mu96iuqwe"/><stop offset="1" class="p-sb3ibac"/></linearGradient><linearGradient id="iFhrcyd" x1="18.71" x2="20.111" y1="21.222" y2="21.222" gradientUnits="userSpaceOnUse"><stop offset=".093" class="fxp5v2b6t"/><stop offset="1" class="zm9c_pbne"/></linearGradient><linearGradient id="iReq52b" x1="9.452" x2="7.02" y1="23.632" y2="23.632" gradientUnits="userSpaceOnUse"><stop class="rpmno-b9y"/><stop offset="1" class="a9ts2kezv"/></linearGradient><linearGradient id="iqKI9Ld" x1="14.606" x2="14.899" y1="24.495" y2="24.534" gradientUnits="userSpaceOnUse"><stop class="jybxgogov"/><stop offset="1" class="rop63gbyj"/></linearGradient><linearGradient id="i83jFwa" x1="17.411" x2="17.012" y1="24.311" y2="24.358" gradientUnits="userSpaceOnUse"><stop class="jybxgogov"/><stop offset="1" class="rop63gbyj"/></linearGradient><linearGradient id="iUkUQ2b" x1="8.862" x2="23.238" y1="15.954" y2="15.954" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iUhqAAe" x1="8.862" x2="23.238" y1="15.924" y2="15.924" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="i0CLjEb" x1="9.741" x2="10.982" y1="11.089" y2="11.089" gradientUnits="userSpaceOnUse"><stop class="b9k-3ybvb"/><stop offset="1" class="vbw-bobru"/></linearGradient><linearGradient id="in18X7j" x1="15.046" x2="15.985" y1="12.333" y2="12.333" gradientUnits="userSpaceOnUse"><stop class="rby1z7ber"/><stop offset="1" class="dl0nwov2w"/></linearGradient><linearGradient id="iCCuX2d" x1="15.985" x2="15.985" y1="13.132" y2="12.522" gradientUnits="userSpaceOnUse"><stop class="cyl8wapbv"/><stop offset="1" class="jplc2lvem"/></linearGradient><linearGradient id="iQto2od" x1="16.063" x2="16.063" y1="13.106" y2="12.966" gradientUnits="userSpaceOnUse"><stop class="p13423bzd"/><stop offset="1" class="wln98ypvp"/></linearGradient><linearGradient id="ih00q6d" x1="14.921" x2="15.382" y1="14.542" y2="13.829" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="iMV5GWd" x1="18.945" x2="18.631" y1="10.459" y2="10.652" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iIgGFUc" x1="14.547" x2="14.233" y1="10.459" y2="10.652" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iI1Orna" x1="13.094" x2="13.639" y1="4.803" y2="6.077" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-office-worker-medium-dark" /></template>
<style>
.a9ts2kezv {
  stop-color: var(--svg-color--584a7e, #584A7E);
  stop-opacity: 0;
}

.ai95fabuh {
  stop-color: var(--svg-color--986b5a, #986B5A);
  stop-opacity: 0;
}

.alwwvg18b {
  stop-color: var(--svg-color--504176, #504176);
}

.apm92hb5d {
  d: path("M16 14.682h-2.71v4.74c0 .31.36.49.61.29l2.1-1.393l2.1 1.393c.25.2.61.02.61-.29v-4.74z");
}

.ax9af2vtk {
  stop-color: var(--svg-color--875555, #875555);
  stop-opacity: 0;
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

.btkjyionj {
  stop-color: var(--svg-color--553a63, #553A63);
  stop-opacity: 0;
}

.c1iziib3t {
  fill: var(--svg-color--845f59, #845F59);
  d: path("M20.812 12.076a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.c1nwhtznm {
  stop-color: var(--svg-color--45363a, #45363A);
}

.c6vz32b3d {
  cx: 13.532px;
  cy: 10.309px;
  rx: 0.39px;
  ry: 0.197px;
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.c7t_ubv2h {
  d: path("M16 15.125c-6.08 0-11 4.92-11 11v3.5h22v-3.5c0-6.07-4.93-11-11-11");
}

.c8t-c_brq {
  stop-color: var(--svg-color--594c7d, #594C7D);
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

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crj44uotj {
  stop-color: var(--svg-color--996b5e, #996B5E);
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cyl8wapbv {
  stop-color: var(--svg-color--7c455c, #7C455C);
}

.d00heltoe {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.134 8.63c-.323-.08-1.125-.04-1.661.343");
}

.da7h3oe0u {
  stop-color: var(--svg-color--743f5a, #743F5A);
  stop-opacity: 0;
}

.dfz7so2-c {
  stop-color: var(--svg-color--663a3f, #663A3F);
}

.dl0nwov2w {
  stop-color: var(--svg-color--744c45, #744C45);
  stop-opacity: 0;
}

.dppebsd1o {
  d: path("M18.17 9.928a.892.892 0 0 1 .86 1.127h-1.725a.896.896 0 0 1 .864-1.128");
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.eo_7g0bzd {
  stop-color: var(--svg-color--5a3638, #5A3638);
}

.f1zcm9akr {
  fill-rule: evenodd;
  d: path("M23.17 12.411c.213-.435.324-.92.324-1.426c0-.468-.096-.906-.268-1.306h.005a3 3 0 0 0-.281-.513l-.002-.003a3.24 3.24 0 0 1-.527-1.771v-.01a3.3 3.3 0 0 0-3.299-3.3a.54.54 0 0 1-.455-.232a3.3 3.3 0 0 0-2.682-1.376a3.3 3.3 0 0 0-2.682 1.376a.56.56 0 0 1-.455.233h-.085a3.3 3.3 0 0 0-3.214 3.299v.01a3.24 3.24 0 0 1-.527 1.77l-.002.005a3.3 3.3 0 0 0-.22 3.244c.07.142.07.314 0 .456a3.213 3.213 0 0 0 2.894 4.625h8.582a3.213 3.213 0 0 0 2.894-4.625a.52.52 0 0 1 0-.456M10.91 9.74h-.012l1.199 2.355c.123 2.803 1.217 0 3.888 0s3.836 3.12 3.96.317l1.136-3.197c-.054-1.245-.956-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.19-1.673a.264.264 0 0 0-.461.05l-.082.195a2.3 2.3 0 0 1-1.241 1.255l-.051.02c-.236.122-.79.49-.81 1.439l.01.306z");
}

.fohaseb4j {
  d: path("M18.103 10.116c.064.085-.069.189-.22.302s-.263.193-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.05");
}

.fs9pa7bci {
  stop-color: var(--svg-color--6e494b, #6E494B);
  stop-opacity: 0;
}

.ft2atdbel {
  stop-color: var(--svg-color--877f93, #877F93);
}

.ft5dv1b6b {
  fill: none;
}

.ft6yvtbqk {
  stop-color: var(--svg-color--cac3d3, #CAC3D3);
}

.fx1tjiblm {
  stop-color: var(--svg-color--755041, #755041);
  stop-opacity: 0;
}

.fxp5v2b6t {
  stop-color: var(--svg-color--453d68, #453D68);
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g1k32m_rh {
  stop-color: var(--svg-color--6d6193, #6D6193);
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.gc98rzbmn {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.376 9.656c.653 0 1.205.45 1.355 1.058a.274.274 0 0 1-.268.341h-2.231a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.371-1.128");
}

.gcfqr7bfg {
  stop-color: var(--svg-color--714350, #714350);
  stop-opacity: 0;
}

.gduosbcxu {
  d: path("M20.812 12.076a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.gkzmut59n {
  stop-color: var(--svg-color--a89cb3, #A89CB3);
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h6-v2u2iz {
  d: path("M15.505 20.735a.25.25 0 0 0-.247.212l-1.328 8.668h4.11l-1.318-8.668a.25.25 0 0 0-.247-.212z");
}

.hac9w68gp {
  stop-color: var(--svg-color--534973, #534973);
}

.hdf-adbmu {
  d: path("M14.616 10.715c0-.288-.234-.48-.298-.539l-.288.28l.177.36z");
}

.hhpztvblo {
  d: path("M18.71 15.745h-5.42v13.89h5.42z");
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hmuhvgbey {
  d: path("m16.01 17.952l-1.24 1.204a.15.15 0 0 0-.033.168l.547 1.26c.04.092.13.15.23.15h.952c.1 0 .19-.059.23-.15l.55-1.28a.15.15 0 0 0-.033-.167z");
}

.hpeo8yzih {
  stop-color: var(--svg-color--9d7e72, #9D7E72);
}

.hr-qb25sn {
  fill: var(--svg-color--8a6058, #8A6058);
  d: path("m15.603 10.64l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.114-.376-.646-.376-.765 0");
}

.hvsbaddlf {
  d: path("M18.964 10.703a.84.84 0 0 0-.231-.463l-.26.285l.117.228z");
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.i_25dj3ib {
  stop-color: var(--svg-color--a093a3, #A093A3);
}

.ib_op1bfg {
  d: path("M11.319 12.076a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.iwz00abqx {
  stop-color: var(--svg-color--5f5289, #5F5289);
}

.ix4m4bceo {
  fill: var(--svg-color--605890, #605890);
  d: path("m21.22 20.745l-1.36-1.33a.262.262 0 0 1 .19-.45h1.05c.21 0 .35-.22.26-.41l-1.23-2.62c-.24-.1-.49-.19-.74-.27h-.68v13.95l2.75-7.86c.12-.36.03-.75-.24-1.01");
}

.j-er45bzw {
  stop-color: var(--svg-color--544a76, #544A76);
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.ja_9lc_2e {
  fill: var(--svg-color--000, #000);
  d: path("M17.658 10.82c0-.284.227-.511.511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.235");
}

.jaf6nfbfs {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
  stop-opacity: 0;
}

.jhz75cc3u {
  d: path("M7.032 29.625H8.97V17.66a11 11 0 0 0-3.656 5.842a11 11 0 0 0-.304 2.632l.02 3.49z");
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jplc2lvem {
  stop-color: var(--svg-color--7c455c, #7C455C);
  stop-opacity: 0;
}

.jtck_gbig {
  d: path("M13.29 15.715h-.85c-.18.06-.36.13-.53.2l-1.27 2.69c-.09.19.06.41.27.41h1.05c.24 0 .35.29.19.45l-1.36 1.33c-.26.26-.36.65-.23 1l2.73 7.82h.01v-13.9z");
}

.jybxgogov {
  stop-color: var(--svg-color--2b1b3a, #2B1B3A);
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kd-4c0ovp {
  fill: var(--svg-color--2f1920, #2F1920);
  d: path("M15.382 3.211c-1.133-.25-2.15.88-2.267 1.299c1.051 3.545 3.713 3.35 6.34 3.059c1.572-.175 1.743.542 1.877.888c0-3.932-3.344-4.67-5.922-5.24z");
}

.kil_u_idv {
  fill: var(--svg-color--272528, #272528);
  d: path("M14.843 10.433c-.265-.467-.669-.836-1.537-.836c-.38 0-.747.106-1.073.369c-.269.217-.233.495-.025.6l.556.317c.652-.211 1.373-.24 2.08-.45");
}

.kitn3twkh {
  stop-color: var(--svg-color--5f363f, #5F363F);
}

.knib4pb5u {
  stop-color: var(--svg-color--c7bcd2, #C7BCD2);
  stop-opacity: 0;
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kx98i3bkm {
  stop-color: var(--svg-color--837a8d, #837A8D);
  stop-opacity: 0;
}

.kyt4h2bsk {
  stop-color: var(--svg-color--3c2e57, #3C2E57);
  stop-opacity: 0;
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

.lv0iykbih {
  stop-color: var(--svg-color--56406d, #56406D);
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.m5bm-ccxd {
  stop-color: var(--svg-color--7b74a6, #7B74A6);
}

.m7tcxo76r {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.103 10.116c.064.085-.069.189-.22.302s-.263.193-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.05");
}

.mabnc95ph {
  stop-color: var(--svg-color--6a443f, #6A443F);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mf716dhmi {
  stop-color: var(--svg-color--544a5f, #544A5F);
}

.mg10me7tz {
  stop-color: var(--svg-color--794958, #794958);
  stop-opacity: 0;
}

.mke2pz_al {
  d: path("M14.045 16.515c.02.213.205.69.746 1.054c.214.144 1.213.629 1.193.62c.156-.079.807-.3 1.284-.62c.54-.363.725-.84.746-1.054l-1.985-.953z");
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mt9k2qzvi {
  stop-color: var(--svg-color--755041, #755041);
}

.mu96iuqwe {
  stop-color: var(--svg-color--4b375e, #4B375E);
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.ni-4se4rm {
  stop-color: var(--svg-color--836462, #836462);
}

.o3wo53bzp {
  stop-color: var(--svg-color--5a3638, #5A3638);
  stop-opacity: 0;
}

.obcwk1b3o {
  d: path("M11.3 12.61a1.61 1.61 0 1 0 0-3.217a1.61 1.61 0 0 0 0 3.218");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ogqxd-bue {
  stop-color: var(--svg-color--1c151f, #1C151F);
}

.olqyf7fmb {
  stop-color: var(--svg-color--875e5e, #875E5E);
}

.omh3jbc5e {
  stop-color: var(--svg-color--776d9f, #776D9F);
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

.p-sb3ibac {
  stop-color: var(--svg-color--483b55, #483B55);
}

.p13423bzd {
  stop-color: var(--svg-color--693b40, #693B40);
}

.p4vy1ovbe {
  fill: var(--svg-color--2a191e, #2A191E);
  d: path("M10.916 5.013c.566-.599 1.636-.6 2.13-.51l.396 1.29c-.252-.039-.478.05-.667.235c-.449 1.26-1.99 1.955-2.704 2.145c-.148-1.491.109-2.38.845-3.16");
}

.p88c31myn {
  stop-color: var(--svg-color--815a5b, #815A5B);
  stop-opacity: 0;
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pc2b66ykc {
  stop-color: var(--svg-color--4b3b6d, #4B3B6D);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pwom2q-fh {
  fill: var(--svg-color--70404a, #70404A);
  d: path("m15.592 10.779l-.683 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.493-.377-.613 0");
}

.pzfns_6uz {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M17.127 10.433c.266-.467.67-.836 1.538-.836c.38 0 .746.106 1.072.369c.27.217.233.495.025.6l-.556.317c-.652-.211-1.373-.24-2.079-.45");
}

.q8ootib3t {
  stop-color: var(--svg-color--5f5490, #5F5490);
  stop-opacity: 0;
}

.qsvq8gn7f {
  fill: var(--svg-color--352827, #352827);
  fill-rule: evenodd;
  d: path("m19.717 8.766l-.138.23za.268.268 0 0 1-.275.46l-.005-.002a1 1 0 0 0-.113-.058a3 3 0 0 0-.342-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 0 1-.093-.529c.513-.09.988.001 1.328.11a3.3 3.3 0 0 1 .559.238l.009.006l.003.001z");
}

.qtc95bbzx {
  d: path("M10.916 5.013c.566-.599 1.636-.6 2.13-.51l.396 1.29c-.252-.039-.478.05-.667.235c-.449 1.26-1.99 1.955-2.704 2.145c-.148-1.491.109-2.38.845-3.16");
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

.r8-nbsf4i {
  stop-color: var(--svg-color--504176, #504176);
  stop-opacity: 0;
}

.r88deebyo {
  d: path("M13.8 9.928a.893.893 0 0 0-.86 1.127h1.725a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.r8964-bmu {
  stop-color: var(--svg-color--877f93, #877F93);
  stop-opacity: 0;
}

.r9488kb6n {
  d: path("M20.812 12.61a1.61 1.61 0 1 0 0-3.217a1.61 1.61 0 0 0 0 3.218");
}

.ran5uq2mg {
  cx: 13.532px;
  cy: 10.309px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.rby1z7ber {
  stop-color: var(--svg-color--744c45, #744C45);
}

.recxkftoe {
  stop-color: var(--svg-color--3e305b, #3E305B);
}

.ri9l6nbtx {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.594 9.656c-.653 0-1.205.45-1.355 1.058a.274.274 0 0 0 .268.341h2.231a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.rop63gbyj {
  stop-color: var(--svg-color--2b1b3a, #2B1B3A);
  stop-opacity: 0;
}

.rpmno-b9y {
  stop-color: var(--svg-color--41375c, #41375C);
}

.s3tb_6b2n {
  stop-color: var(--svg-color--3d3247, #3D3247);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sj28mac3i {
  fill: var(--svg-color--5f3c45, #5F3C45);
  d: path("M11.319 12.076a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.som6k-b6q {
  stop-color: var(--svg-color--4b3b6d, #4B3B6D);
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.t9k87pm2r {
  stop-color: var(--svg-color--875555, #875555);
}

.tgiuuaboq {
  d: path("M16.072 15.924h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.twkot3bqm {
  d: path("M10.898 9.739h.012l-.01-.265l-.01-.306c.02-.95.574-1.317.81-1.439l.05-.02q.029-.013.052-.02a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.051a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.082.087 1.135 1.332l-.118 3.073c-.124 2.803-2.312 4.685-4.984 4.685c-2.671 0-4.86-1.882-4.983-4.685z");
}

.u61ykmvtc {
  stop-color: var(--svg-color--584982, #584982);
}

.ugh29hhiz {
  stop-color: var(--svg-color--7a6c85, #7A6C85);
}

.uj7hgsb3u {
  stop-color: var(--svg-color--815a5b, #815A5B);
}

.up8l18w-p {
  stop-color: var(--svg-color--986b5a, #986B5A);
}

.uv1mp4g3h {
  d: path("M15.382 3.211c-1.133-.25-2.15.88-2.267 1.299c1.051 3.545 3.713 3.35 6.34 3.059c1.572-.175 1.743.542 1.877.888c0-3.932-3.344-4.67-5.922-5.24z");
}

.v7yg4rbyg {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.925 8.63c.322-.08 1.124-.04 1.66.343");
}

.vbw-bobru {
  stop-color: var(--svg-color--533335, #533335);
}

.vo75e7bfz {
  d: path("m21.22 20.745l-1.36-1.33a.262.262 0 0 1 .19-.45h1.05c.21 0 .35-.22.26-.41l-1.23-2.62c-.24-.1-.49-.19-.74-.27h-.68v13.95l2.75-7.86c.12-.36.03-.75-.24-1.01");
}

.wdy63qb5p {
  stop-color: var(--svg-color--c6bbd1, #C6BBD1);
}

.wg3eepbwp {
  stop-color: var(--svg-color--805c54, #805C54);
}

.wln98ypvp {
  stop-color: var(--svg-color--693b40, #693B40);
  stop-opacity: 0;
}

.wrh2b4bbx {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
}

.wsh5tsbcf {
  stop-color: var(--svg-color--836462, #836462);
  stop-opacity: 0;
}

.x_ik4kbfh {
  stop-color: var(--svg-color--714350, #714350);
}

.x-4htd_rb {
  d: path("m15.603 10.64l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.114-.376-.646-.376-.765 0");
}

.x0u1810qj {
  fill: var(--svg-color--47383d, #47383D);
  d: path("m18.391 6.82l-1.425.263a.688.688 0 1 1-.125-1.365h2.34c1.385 0 1.843 1.395 1.9 1.872a3.15 3.15 0 0 0-2.69-.77");
}

.xbfu1itob {
  d: path("M16.402 15.924c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xjwttd8ow {
  fill: var(--svg-color--352827, #352827);
  d: path("m12.587 9.224l-.004.002a.268.268 0 0 1-.276-.46h.002l.003-.002l.01-.006a2 2 0 0 1 .148-.077c.098-.047.239-.107.41-.161c.34-.109.815-.2 1.328-.11a.268.268 0 1 1-.093.529a2.3 2.3 0 0 0-1.072.092a3 3 0 0 0-.456.193");
}

.y8tu8dbcm {
  d: path("M23 17.643v11.982h4v-3.5a10.98 10.98 0 0 0-4-8.482");
}

.yad6lvxsv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.094 4.46c.023.243.235 1.156.545 1.71");
}

.yamoh3dov {
  stop-color: var(--svg-color--764e4c, #764E4C);
}

.ycrcotb4u {
  stop-color: var(--svg-color--986f60, #986F60);
  stop-opacity: 0;
}

.ye5gqoics {
  fill: var(--svg-color--000, #000);
  d: path("M14.312 10.82a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .061-.235");
}

.yfhz1ybyq {
  stop-color: var(--svg-color--3c2e57, #3C2E57);
}

.yqlqjsfuk {
  stop-color: var(--svg-color--55477c, #55477C);
}

.z_fvebb5d {
  fill: var(--svg-color--41355c, #41355C);
  d: path("M13.419 16.474c-.513 0-1.296-.03-1.77.166l-1.38 2.724c-.09.19.06.41.27.41h1.55c.24 0 .35.29.19.45l-1.78 1.343c-.26.26-.36.65-.23 1l2.912 6.5l1.587-1.116l-1.34-11.477z");
}

.z26rrllgi {
  stop-color: var(--svg-color--6e494b, #6E494B);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.z6rpzli7h {
  fill: var(--svg-color--463d68, #463D68);
  d: path("m20.905 20.806l-1.19-.828a.23.23 0 0 1 .166-.393h.919a.252.252 0 0 0 .227-.358l-1.076-2.291a8 8 0 0 0-.646-.236h-.595v11.862l2.404-6.873a.85.85 0 0 0-.21-.883");
}

.z71m_ba6i {
  fill: var(--svg-color--88014f, #88014F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.652 13.815a.2.2 0 0 0-.021-.25a.205.205 0 0 0-.247-.04a3 3 0 0 1-1.399.338a3 3 0 0 1-1.398-.339a.204.204 0 0 0-.248.044a.196.196 0 0 0-.02.248m3.333 0l-.042-.028l.042.027Zm0 0a1.982 1.982 0 0 1-3.333 0m0 0l.041-.028m-.041.027l.041-.027m0 0a1.932 1.932 0 0 0 3.25 0c.088-.136-.063-.293-.203-.22c-.412.22-.896.345-1.422.345a3 3 0 0 1-1.421-.344c-.141-.074-.292.088-.204.219Z");
}

.zm9c_pbne {
  stop-color: var(--svg-color--625a91, #625A91);
  stop-opacity: 0;
}

.zoq8fuaif {
  stop-color: var(--svg-color--986f60, #986F60);
}

</style>
