<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i1JElyc)"><path fill="url(#i7CK71b)" clip-rule="evenodd" class="jx32ovy0j"/><path fill="url(#ia85cGd)" clip-rule="evenodd" class="jx32ovy0j"/><path fill="url(#iXW6csd)" clip-rule="evenodd" class="jx32ovy0j"/><path fill="url(#iElEcpc)" clip-rule="evenodd" class="jx32ovy0j"/><path fill="url(#idIq0wE)" clip-rule="evenodd" class="jx32ovy0j"/><path fill="url(#iOQHowT)" clip-rule="evenodd" class="jx32ovy0j"/><path fill="url(#iShAhGb)" clip-rule="evenodd" class="jx32ovy0j"/><path fill="url(#iZkg3ib)" clip-rule="evenodd" class="jx32ovy0j"/><path fill="url(#iFZKGHe)" clip-rule="evenodd" class="jx32ovy0j"/><path fill="url(#iEH3NJS)" clip-rule="evenodd" class="jx32ovy0j"/><path fill="url(#ihPa4be)" clip-rule="evenodd" class="jx32ovy0j"/></g><path fill="url(#iYpna8t)" class="h064k9b1n"/><path fill="url(#iUKebPb)" class="h064k9b1n"/><path fill="url(#ic5d39d)" class="h064k9b1n"/><path fill="url(#ihEx4Ab)" class="h064k9b1n"/><path fill="url(#itb84Mb)" class="h064k9b1n"/><path fill="url(#iVhpSld)" class="nm6odobve"/><path fill="url(#il0VLoc)" class="nm6odobve"/><path class="x7bl4zbkb"/><path fill="url(#i3eTupc)" class="d0mty6dok"/><path fill="url(#iQULaLb)" class="d0mty6dok"/><path class="gl7hf2blh"/><path fill="url(#id9STvb)" class="x_nfl_ozw"/><path fill="url(#iagJHdo)" class="x_nfl_ozw"/><path fill="url(#ieqwvgd)" class="r_t9aq_-g"/><path fill="url(#i3U51ac)" class="a-cgv50-r"/><g filter="url(#iGpBDYc)"><path fill="url(#iWrdw9d)" class="vb9hamb2p"/></g><g filter="url(#izkGzhu)"><path fill="url(#ipI4Fid)" class="afdt9hpbc"/><path fill="url(#iQG7qgd)" class="afdt9hpbc"/></g><g filter="url(#iUTPwkd)"><path class="c20aqh0vw"/><path fill="url(#iIbjhEd)" class="ah1jb-22d"/></g><g filter="url(#iethP0d)"><path class="o70f9fbyi"/><path fill="url(#iz0jgsb)" class="km2ignmjc"/></g><g filter="url(#ihblsjb)"><path fill="url(#imWhRZb)" class="mnj4ecbxj"/><path fill="url(#iUgvEDc)" class="mnj4ecbxj"/><path fill="url(#inJCf1R)" class="mnj4ecbxj"/><path fill="url(#ivDnMEc)" class="mnj4ecbxj"/><path fill="url(#iseLzhc)" class="mnj4ecbxj"/><path fill="url(#i0E9eud)" class="mnj4ecbxj"/><path fill="url(#i2Hf5xb)" class="mnj4ecbxj"/></g><path fill="url(#iWz8pUb)" class="mnj4ecbxj"/><path fill="url(#i4RVXyc)" class="mnj4ecbxj"/><g filter="url(#iNnzxvc)"><path class="l7ry8rboi"/></g><g filter="url(#i7C5lFc)"><path class="nohhk2bof"/><path fill="url(#i9TOuHb)" class="xele9f15f"/><path fill="url(#iV2Mt7c)" class="xele9f15f"/><path fill="url(#i6TfJwc)" class="xele9f15f"/><path fill="url(#ie1Qgxe)" class="xele9f15f"/></g><g filter="url(#iOD0oBd)"><path stroke="url(#iVzSMwb)" class="oyqxcccjr"/></g><path class="c1vrl0ban"/><g filter="url(#iR61E7b)"><path class="crgcoebcf"/></g><g filter="url(#ipSGAYP)"><path class="vo-5c_b0h"/></g><g filter="url(#ictlS8j)"><path class="fiwextbac"/></g><g filter="url(#ixoQctb)"><path clip-rule="evenodd" class="kg_c-rbpr"/></g><path class="jsdz5mbzw"/><path fill="url(#igIxZrb)" class="dsu_l3b4g"/><path class="yewopxysi"/><g filter="url(#iiffLbd)"><path class="rm-21olxw"/><path fill="url(#i0ldmib)" class="xkdv6ybqk"/></g><g filter="url(#i6HfTke)"><path fill="url(#irlrGEe)" class="dvfzjqbos"/></g><path class="usjme_bkn"/><path fill="url(#iGGZPXv)" class="ejwmi_b_x"/><path class="g3i35ac9y"/><g filter="url(#iuxrtjK)"><path fill="url(#icoXwQk)" class="bxrhycbkq"/></g><g filter="url(#ijl5Pje)"><ellipse transform="rotate(-27.914 12.177 12.372)" class="e7d2boxfi"/><ellipse fill="url(#ia9Wvne)" transform="rotate(-27.914 12.177 12.372)" class="p0qxmpf9n"/></g><g filter="url(#i3Pz9jb)"><path class="u3s0_kqys"/></g><g filter="url(#iTegKde)"><path class="fm1qrjg_z"/></g><g filter="url(#i6Xf3gr)"><path class="k7vepx8sv"/><path fill="url(#irREXqb)" class="y-yheec7q"/></g><g filter="url(#iGaicQc)"><path class="wrm-qpibj"/><path fill="url(#iBRaQPb)" class="qe5e1hb-k"/><path fill="url(#iuxzwJe)" class="qe5e1hb-k"/></g><g filter="url(#iVHXuxe)"><path stroke="url(#iV0CF7Q)" class="a85znabqw"/></g><g filter="url(#i3fyxEd)"><path class="ndjzgnbjo"/></g><path fill="url(#ijp5GKd)" class="c094r_bvs"/><path fill="url(#ipYPb9b)" class="a41xocxec"/><path fill="url(#iwWxddP)" class="a41xocxec"/><path fill="url(#iaC38ue)" class="jrx3i8b1t"/><path fill="url(#irzfGIb)" class="jrx3i8b1t"/><g filter="url(#iPlFuHc)"><circle fill="url(#iVmkACb)" class="m8gsznlzl"/><circle fill="url(#iRQA0se)" class="m8gsznlzl"/><circle fill="url(#iu94fIb)" class="m8gsznlzl"/></g><g filter="url(#iOGnFKe)"><path fill="url(#if1AEES)" clip-rule="evenodd" class="bqqvv7bor"/></g><path fill="url(#ipFIR2b)" clip-rule="evenodd" class="bqqvv7bor"/><g filter="url(#iY0kZOb)"><path fill="url(#iqfCaLe)" clip-rule="evenodd" class="a4_5g-kex"/></g><g filter="url(#it9c08c)"><circle stroke="url(#iGw8SZc)" class="gm_5gldko"/></g><g filter="url(#iFlZMed)"><circle stroke="url(#i25s7Yc)" class="v83a3u3_r"/></g><g filter="url(#iC00Uye)"><circle stroke="url(#iNMJJ0c)" class="uxe1igbwt"/></g><g filter="url(#iguJyYO)"><circle stroke="url(#iLnBePe)" class="wj0k-xifb"/></g><defs><radialGradient id="ia85cGd" cx="0" cy="0" r="1" gradientTransform="matrix(-.6034 4.55907 -5.6952 -.75377 14.329 15.566)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="iXW6csd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88301 1.94432 -2.5547 -3.78806 11.513 15.834)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="iElEcpc" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 1.61 9.061)scale(2.15225 1.65263)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="idIq0wE" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 1.963 8.5)scale(2.47506 1.74346)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="iOQHowT" cx="0" cy="0" r="1" gradientTransform="matrix(1.37443 2.61477 -3.62969 1.90792 11.11 5.006)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="iShAhGb" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 8.764 7.78)scale(2.03849 2.84876)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iZkg3ib" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.11855 -3.8448 22.14 12.213)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="iFZKGHe" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 9.806 9.142)scale(2.90248 3.69733)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="iEH3NJS" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 13.18 -2.036)scale(2.80034 2.21491)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="ihPa4be" cx="0" cy="0" r="1" gradientTransform="matrix(1.50392 .15775 -.2556 2.43678 8.489 12.177)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="iYpna8t" cx="0" cy="0" r="1" gradientTransform="rotate(154.071 8.317 13.902)scale(15.0662 17.3462)" gradientUnits="userSpaceOnUse"><stop class="m5wv9vbgf"/><stop offset="1" class="ok0s313ee"/></radialGradient><radialGradient id="iUKebPb" cx="0" cy="0" r="1" gradientTransform="matrix(-7.90627 -10.81244 15.55864 -11.37678 17.476 29.861)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="je8i96bea"/><stop offset="1" class="r-plgxbvx"/></radialGradient><radialGradient id="ic5d39d" cx="0" cy="0" r="1" gradientTransform="rotate(168.453 5.763 9.951)scale(5.93256 1.70339)" gradientUnits="userSpaceOnUse"><stop class="u4cmqnbdb"/><stop offset="1" class="sncijkqpo"/></radialGradient><radialGradient id="ihEx4Ab" cx="0" cy="0" r="1" gradientTransform="matrix(-3.93377 0 0 -19.371 21.553 29.356)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="p47-3c-mm"/><stop offset="1" class="vzbvt7b3z"/></radialGradient><radialGradient id="itb84Mb" cx="0" cy="0" r="1" gradientTransform="matrix(1.5 0 0 23.8126 7.432 29.356)" gradientUnits="userSpaceOnUse"><stop class="g6dgamb9p"/><stop offset="1" class="hnlppfbil"/></radialGradient><radialGradient id="iVhpSld" cx="0" cy="0" r="1" gradientTransform="matrix(3.25185 0 0 9.13279 21.584 28.577)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="zduonub6o"/><stop offset="1" class="cuty5mbvc"/></radialGradient><radialGradient id="il0VLoc" cx="0" cy="0" r="1" gradientTransform="matrix(.87006 0 0 11.9715 21.584 29.356)" gradientUnits="userSpaceOnUse"><stop class="iwql9tbwr"/><stop offset="1" class="cpuxbvbrp"/></radialGradient><radialGradient id="i3eTupc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.70862 0 0 -8.85437 7.317 29.356)" gradientUnits="userSpaceOnUse"><stop offset=".614" class="fxt5p0b8w"/><stop offset="1" class="f4vmrjbib"/></radialGradient><radialGradient id="iQULaLb" cx="0" cy="0" r="1" gradientTransform="matrix(-.8463 0 0 -10.457 7.317 29.356)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="f3tc_zfmh"/><stop offset="1" class="nhus6q3at"/></radialGradient><radialGradient id="id9STvb" cx="0" cy="0" r="1" gradientTransform="matrix(.5625 1.75 -3.03541 .97567 13.708 18.647)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="cvfl2_nnj"/><stop offset="1" class="v5pn-pcxn"/></radialGradient><radialGradient id="iagJHdo" cx="0" cy="0" r="1" gradientTransform="matrix(-2.9674 2.28562 -.98994 -1.28524 17.598 19.517)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="egu8xgzbw"/><stop offset="1" class="clod7-bap"/></radialGradient><radialGradient id="ipI4Fid" cx="0" cy="0" r="1" gradientTransform="matrix(1.82698 -2.0365 2.48647 2.23066 19.14 14.04)" gradientUnits="userSpaceOnUse"><stop offset=".444" class="w--6bgeqj"/><stop offset=".944" class="sheftacio"/></radialGradient><radialGradient id="iQG7qgd" cx="0" cy="0" r="1" gradientTransform="matrix(1.31576 .7375 -.2085 .37199 19.7 11.384)" gradientUnits="userSpaceOnUse"><stop class="ynae43ovp"/><stop offset="1" class="v-9tn59hb"/></radialGradient><radialGradient id="iIbjhEd" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 19.022 13.177)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="k2oqpgb0o"/><stop offset="1" class="dkw8bsvxv"/></radialGradient><radialGradient id="iz0jgsb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.20681 0 0 -.95203 10.03 13.065)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="b55qklbsj"/><stop offset="1" class="uaoaczbhz"/></radialGradient><radialGradient id="imWhRZb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50357 2.99901 -4.01413 -8.70492 17.49 12.527)" gradientUnits="userSpaceOnUse"><stop class="v5rheyc4i"/><stop offset="1" class="wum9l96_j"/></radialGradient><radialGradient id="iUgvEDc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.46116 .45112 -.49796 -3.82051 17.882 13.89)" gradientUnits="userSpaceOnUse"><stop class="z-rzt8b_f"/><stop offset="1" class="tk20gvbnd"/></radialGradient><radialGradient id="inJCf1R" cx="0" cy="0" r="1" gradientTransform="matrix(1.30737 -3.78806 4.80634 1.6588 12.251 19.856)" gradientUnits="userSpaceOnUse"><stop class="fvm07vbkd"/><stop offset="1" class="n1w64orcn"/></radialGradient><radialGradient id="ivDnMEc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.72467 -7.78405 0 14.63 12.31)" gradientUnits="userSpaceOnUse"><stop offset=".567" class="ptt7y_f2j"/><stop offset="1" class="afhf0tbjs"/></radialGradient><radialGradient id="iseLzhc" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 7.528 7.928)scale(7.03738 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="brg8dbpny"/><stop offset="1" class="d_t8kfbgb"/></radialGradient><radialGradient id="i0E9eud" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 16.932 12.109)" gradientUnits="userSpaceOnUse"><stop class="e2earo80w"/><stop offset="1" class="xl9xm7bnj"/></radialGradient><radialGradient id="i2Hf5xb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 12.554 11.88)" gradientUnits="userSpaceOnUse"><stop class="suybu51ug"/><stop offset="1" class="intda8ekf"/></radialGradient><radialGradient id="iWz8pUb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28528 0 0 -6.44557 19.726 13.597)" gradientUnits="userSpaceOnUse"><stop class="sqxrh1b6n"/><stop offset="1" class="eodwsybla"/></radialGradient><radialGradient id="i4RVXyc" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 4 -6.96848 2.28654 12.446 6.529)" gradientUnits="userSpaceOnUse"><stop class="f_q-3cc4h"/><stop offset="1" class="s44y8_wdc"/></radialGradient><radialGradient id="i9TOuHb" cx="0" cy="0" r="1" gradientTransform="matrix(-.45554 -2.04401 .62995 -.1404 15.415 14.324)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xbgj88f0b"/><stop offset="1" class="y_9l2i5ww"/></radialGradient><radialGradient id="ie1Qgxe" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.2179 15.175 14.535)" gradientUnits="userSpaceOnUse"><stop class="qpkqxibzk"/><stop offset="1" class="nwt8glb0m"/></radialGradient><radialGradient id="igIxZrb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 16.813 12.468)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i0ldmib" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 16.585 12.552)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iGGZPXv" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 12.449 12.468)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ia9Wvne" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.326 .357)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="irREXqb" cx="0" cy="0" r="1" gradientTransform="rotate(-65.391 12.546 -1.815)scale(3.03069 1.55043)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="iBRaQPb" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 6.655 7.77)scale(4.8729 7.96691)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="iuxzwJe" cx="0" cy="0" r="1" gradientTransform="matrix(-.21034 1.3672 -2.94144 -.45253 14.84 5.51)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><radialGradient id="ijp5GKd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.21875 1.75 -2.17983 -7.74618 23.463 6.204)" gradientUnits="userSpaceOnUse"><stop class="qtibqw8vp"/><stop offset=".687" class="il490o5xd"/><stop offset=".843" class="f44xh0bnc"/></radialGradient><radialGradient id="iVmkACb" cx="0" cy="0" r="1" gradientTransform="rotate(141.18 10.736 7.664)scale(.43619)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="cz-qsgbfy"/><stop offset="1" class="j80tr6o9y"/></radialGradient><radialGradient id="iRQA0se" cx="0" cy="0" r="1" gradientTransform="matrix(.19922 -.48438 1.17186 .48198 23.586 7.347)" gradientUnits="userSpaceOnUse"><stop offset=".147" class="m8bo-jb-t"/><stop offset="1" class="wy7e69bbh"/></radialGradient><radialGradient id="iu94fIb" cx="0" cy="0" r="1" gradientTransform="matrix(.4375 .04684 -.05916 .55254 23.361 6.91)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="zk512ndyg"/><stop offset="1" class="hy0z0nf6k"/></radialGradient><radialGradient id="if1AEES" cx="0" cy="0" r="1" gradientTransform="matrix(2.20247 -1.61719 2.56784 3.49718 21.389 10.096)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="cnux6p8xn"/><stop offset="1" class="jaxt-o31p"/></radialGradient><radialGradient id="iqfCaLe" cx="0" cy="0" r="1" gradientTransform="matrix(2.53124 -1.40627 1.98705 3.57664 24.535 8.273)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="cnux6p8xn"/><stop offset="1" class="jaxt-o31p"/></radialGradient><filter id="i1JElyc" width="15.268" height="15.768" x="7.121" y="3.787" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_37"/></filter><filter id="iGpBDYc" width="3.368" height="3.218" x="8.336" y="11.456" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.682353 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_37"/></filter><filter id="izkGzhu" width="3.218" height="3.468" x="17.849" y="11.206" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.572549 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_37"/></filter><filter id="iUTPwkd" width="3.148" height="3.148" x="17.884" y="11.491" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_37" stdDeviation=".25"/></filter><filter id="iethP0d" width="2.948" height="2.948" x="8.49" y="11.591" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_37" stdDeviation=".2"/></filter><filter id="ihblsjb" width="10.191" height="11.277" x="9.535" y="8.158" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.592157 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_37"/></filter><filter id="iNnzxvc" width="2.877" height="3.682" x="13.03" y="12.06" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_37" stdDeviation=".25"/></filter><filter id="i7C5lFc" width="2.077" height="2.882" x="13.592" y="12.321" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_37" stdDeviation=".05"/></filter><filter id="iOD0oBd" width="3.702" height="1.526" x="12.78" y="15.413" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_37" stdDeviation=".05"/></filter><filter id="iR61E7b" width="3.001" height="1.285" x="15.573" y="11.66" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_37"/></filter><filter id="ipSGAYP" width="3.001" height="1.285" x="10.687" y="11.66" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_37"/></filter><filter id="ictlS8j" width="2.453" height="1.091" x="10.823" y="10.237" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_37"/></filter><filter id="ixoQctb" width="2.453" height="1.091" x="16.24" y="10.237" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_37"/></filter><filter id="iiffLbd" width=".787" height=".696" x="16.079" y="12.028" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_37" stdDeviation=".05"/></filter><filter id="i6HfTke" width=".891" height=".913" x="16.919" y="12.103" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_37" stdDeviation=".1"/></filter><filter id="iuxrtjK" width=".986" height="1.04" x="12.476" y="12.04" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_37" stdDeviation=".1"/></filter><filter id="ijl5Pje" width=".913" height=".705" x="11.721" y="12.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_37" stdDeviation=".05"/></filter><filter id="i3Pz9jb" width="2.261" height=".978" x="16.27" y="10.359" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_37" stdDeviation=".1"/></filter><filter id="iTegKde" width="2.261" height=".978" x="10.818" y="10.359" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_37" stdDeviation=".1"/></filter><filter id="i6Xf3gr" width="4.212" height="4.513" x="8.376" y="6.223" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.341176 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_37"/><feGaussianBlur result="effect2_foregroundBlur_4002_37" stdDeviation=".15"/></filter><filter id="iGaicQc" width="8.767" height="5.782" x="11.46" y="4.989" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_37"/><feGaussianBlur result="effect2_foregroundBlur_4002_37" stdDeviation=".125"/></filter><filter id="iVHXuxe" width="1.145" height="2.31" x="11.439" y="6.223" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_37" stdDeviation=".1"/></filter><filter id="i3fyxEd" width="6.427" height="3.372" x="14.049" y="7.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_37" stdDeviation=".375"/></filter><filter id="iPlFuHc" width=".726" height=".726" x="23.418" y="6.587" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.52549 0 0 0 0 0.388235 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_37"/></filter><filter id="iOGnFKe" width="3.834" height="4.387" x="20.96" y="7.388" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.45098 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_37"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.282353 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_37" result="effect2_innerShadow_4002_37"/></filter><filter id="iY0kZOb" width="4.283" height="3.734" x="24.158" y="5.911" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.203922 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_37"/></filter><filter id="it9c08c" width="3.843" height="3.843" x="24.629" y="5.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_37" stdDeviation=".1"/></filter><filter id="iFlZMed" width="2.734" height="2.734" x="25.183" y="6.436" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_37" stdDeviation=".1"/></filter><filter id="iC00Uye" width="2.734" height="2.734" x="21.535" y="8.45" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_37" stdDeviation=".1"/></filter><filter id="iguJyYO" width="3.805" height="3.805" x="21" y="7.915" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_37" stdDeviation=".1"/></filter><linearGradient id="i7CK71b" x1="19.324" x2="12.519" y1="6.112" y2="18.717" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="ieqwvgd" x1="7.446" x2="21.822" y1="17.711" y2="17.711" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="i3U51ac" x1="7.446" x2="21.822" y1="17.681" y2="17.681" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iWrdw9d" x1="8.336" x2="11.295" y1="13.152" y2="13.152" gradientUnits="userSpaceOnUse"><stop class="ixw8njbyx"/><stop offset="1" class="me4c4fyoe"/></linearGradient><linearGradient id="iV2Mt7c" x1="13.692" x2="14.631" y1="14.396" y2="14.396" gradientUnits="userSpaceOnUse"><stop class="l38p1-72g"/><stop offset="1" class="njp0-cbrk"/></linearGradient><linearGradient id="i6TfJwc" x1="14.631" x2="14.631" y1="15.195" y2="14.585" gradientUnits="userSpaceOnUse"><stop class="vdvey0c5l"/><stop offset="1" class="tddz0-g7t"/></linearGradient><linearGradient id="iVzSMwb" x1="13.566" x2="14.027" y1="16.605" y2="15.893" gradientUnits="userSpaceOnUse"><stop class="b5nknil5b"/><stop offset=".663" class="prv6psg5p"/></linearGradient><linearGradient id="irlrGEe" x1="17.591" x2="17.277" y1="12.522" y2="12.715" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="icoXwQk" x1="13.193" x2="12.879" y1="12.522" y2="12.715" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iV0CF7Q" x1="11.739" x2="12.284" y1="6.867" y2="8.14" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><linearGradient id="ipYPb9b" x1="24.941" x2="23.75" y1="5.049" y2="4.704" gradientUnits="userSpaceOnUse"><stop class="p9lsnsm5t"/><stop offset="1" class="lapvr59ed"/></linearGradient><linearGradient id="iwWxddP" x1="23.793" x2="23.867" y1="6.542" y2="6.253" gradientUnits="userSpaceOnUse"><stop offset=".16" class="zl0fwhbas"/><stop offset="1" class="lxc0fmbqt"/></linearGradient><linearGradient id="iaC38ue" x1="22.879" x2="23.144" y1="7.398" y2="6.101" gradientUnits="userSpaceOnUse"><stop class="p9lsnsm5t"/><stop offset="1" class="lapvr59ed"/></linearGradient><linearGradient id="irzfGIb" x1="24.29" x2="24.092" y1="7.48" y2="7.424" gradientUnits="userSpaceOnUse"><stop class="jd-vaq0no"/><stop offset="1" class="gof7ehbkx"/></linearGradient><linearGradient id="ipFIR2b" x1="23.629" x2="23.57" y1="7.57" y2="7.796" gradientUnits="userSpaceOnUse"><stop offset=".209" class="ni_6htbzm"/><stop offset="1" class="ajm38_jxm"/></linearGradient><linearGradient id="iGw8SZc" x1="24.879" x2="28.069" y1="8.172" y2="6.7" gradientUnits="userSpaceOnUse"><stop offset=".616" class="w5_7ycb6b"/><stop offset=".9" class="srm_r_guo"/></linearGradient><linearGradient id="i25s7Yc" x1="25.433" x2="27.566" y1="8.05" y2="7.066" gradientUnits="userSpaceOnUse"><stop offset=".247" class="jzjqx7qlk"/><stop offset=".669" class="gl3wl_9gz"/></linearGradient><linearGradient id="iNMJJ0c" x1="21.785" x2="23.917" y1="10.064" y2="9.079" gradientUnits="userSpaceOnUse"><stop offset=".247" class="rraw6sbsp"/><stop offset=".669" class="r8ibvzbki"/></linearGradient><linearGradient id="iLnBePe" x1="24.554" x2="22.902" y1="9.276" y2="9.817" gradientUnits="userSpaceOnUse"><stop class="znwvjy5yx"/><stop offset="1" class="zi0lb2bns"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-getting-haircut-light" /></template>
<style>
.a-cgv50-r {
  d: path("M14.656 17.681h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.a4_5g-kex {
  fill-rule: evenodd;
  d: path("M24.45 6.655a.1.1 0 0 1 .122-.07l.36.095a.22.22 0 0 0 .216-.072a1.842 1.842 0 1 1-.412 1.52a.22.22 0 0 0-.152-.172l-.352-.094a.1.1 0 0 1-.07-.122zm1.663 1.87a.844.844 0 1 0 .872-1.444a.844.844 0 0 0-.872 1.445");
}

.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.a41xocxec {
  d: path("m24.334 2.644l-1.388 4.83l1.187.346l1.071-3.73a1.15 1.15 0 0 0-.784-1.421z");
}

.a85znabqw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M11.74 6.523c.023.243.234 1.156.544 1.71");
}

.afdt9hpbc {
  d: path("M19.458 14.674a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.afhf0tbjs {
  stop-color: var(--svg-color--be7c90, #BE7C90);
}

.ah1jb-22d {
  d: path("M19.458 14.14a1.074 1.074 0 1 0 0-2.15a1.074 1.074 0 0 0 0 2.15");
}

.ajm38_jxm {
  stop-color: var(--svg-color--ff3178, #FF3178);
  stop-opacity: 0;
}

.b55qklbsj {
  stop-color: var(--svg-color--bc8272, #BC8272);
  stop-opacity: 0;
}

.b5nknil5b {
  stop-color: var(--svg-color--eabbab, #EABBAB);
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bqqvv7bor {
  fill-rule: evenodd;
  d: path("M23.005 7.442a.1.1 0 0 0-.124.068l-.104.357a.21.21 0 0 1-.174.149a1.842 1.842 0 1 0 1.514.433a.21.21 0 0 1-.068-.22l.102-.349a.1.1 0 0 0-.069-.124zm.741 2.391a.844.844 0 1 1-1.688 0a.844.844 0 0 1 1.688 0");
}

.brg8dbpny {
  stop-color: var(--svg-color--e2a895, #E2A895);
  stop-opacity: 0;
}

.bxrhycbkq {
  d: path("M13.262 12.778c0-.288-.235-.48-.298-.538l-.288.278l.177.362z");
}

.c094r_bvs {
  d: path("M20.71 6.65c-1.262.462-2.101.413-2.648.171L16.89 9.673c1.29.054 3.8-.332 5.563-2.383c.843-.982.996-1.91.656-2.586c-.061-.122-.183-.172-.27-.149c-.086.024-.16.109-.187.207c-.162.567-.538 1.373-1.942 1.887");
}

.c1vrl0ban {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M14.63 15.977c-.52 0-1.01-.126-1.42-.345c-.142-.073-.293.089-.204.22a1.932 1.932 0 0 0 3.25 0c.088-.137-.063-.293-.204-.22a3 3 0 0 1-1.421.345");
}

.c20aqh0vw {
  fill: var(--svg-color--f6bca5, #F6BCA5);
  d: path("M19.458 14.14a1.074 1.074 0 1 0 0-2.15a1.074 1.074 0 0 0 0 2.15");
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

.clod7-bap {
  stop-color: var(--svg-color--fec2b9, #FEC2B9);
  stop-opacity: 0;
}

.cnux6p8xn {
  stop-color: var(--svg-color--ff7046, #FF7046);
}

.cpuxbvbrp {
  stop-color: var(--svg-color--8752d9, #8752D9);
  stop-opacity: 0;
}

.crgcoebcf {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M15.773 12.496c.265-.467.669-.836 1.537-.836c.38 0 .747.106 1.073.37c.269.216.233.494.024.598l-.555.318c-.652-.21-1.373-.24-2.08-.45");
}

.cuty5mbvc {
  stop-color: var(--svg-color--9775dd, #9775DD);
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cvfl2_nnj {
  stop-color: var(--svg-color--c7868a, #C7868A);
}

.cz-qsgbfy {
  stop-color: var(--svg-color--ebdbe4, #EBDBE4);
}

.d_t8kfbgb {
  stop-color: var(--svg-color--e2a895, #E2A895);
}

.d0mty6dok {
  d: path("M7.317 20.827C5.044 22.79 3.61 25.676 3.61 28.893v.463h3.708z");
}

.dkw8bsvxv {
  stop-color: var(--svg-color--f5b99d, #F5B99D);
}

.dsu_l3b4g {
  d: path("M16.815 11.99a.893.893 0 0 1 .86 1.129H15.95a.896.896 0 0 1 .864-1.128");
}

.dvfzjqbos {
  d: path("M17.61 12.766a.84.84 0 0 0-.232-.463l-.26.285l.118.229z");
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e2earo80w {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
}

.e7d2boxfi {
  cx: 12.177px;
  cy: 12.372px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.egu8xgzbw {
  stop-color: var(--svg-color--fec2b9, #FEC2B9);
}

.ejwmi_b_x {
  d: path("M12.447 11.99a.892.892 0 0 0-.86 1.129h1.724a1 1 0 0 0 .032-.236a.9.9 0 0 0-.896-.892");
}

.eodwsybla {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
  stop-opacity: 0;
}

.f_q-3cc4h {
  stop-color: var(--svg-color--a47463, #A47463);
}

.f3tc_zfmh {
  stop-color: var(--svg-color--9a6fdb, #9A6FDB);
}

.f44xh0bnc {
  stop-color: var(--svg-color--332a2e, #332A2E);
  stop-opacity: 0;
}

.f4vmrjbib {
  stop-color: var(--svg-color--8267b6, #8267B6);
}

.fiwextbac {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m11.233 11.287l-.004.003a.268.268 0 0 1-.276-.46l.002-.001l.002-.002l.01-.006l.032-.018l.116-.058a3 3 0 0 1 .41-.162c.34-.109.816-.2 1.329-.11a.268.268 0 0 1-.093.529a2.3 2.3 0 0 0-1.072.092a3 3 0 0 0-.456.193");
}

.fm1qrjg_z {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.78 10.692c-.323-.078-1.125-.039-1.662.345");
}

.ft5dv1b6b {
  fill: none;
}

.fvm07vbkd {
  stop-color: var(--svg-color--b87c92, #B87C92);
}

.fxt5p0b8w {
  stop-color: var(--svg-color--8052c3, #8052C3);
  stop-opacity: 0;
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g3i35ac9y {
  fill: var(--svg-color--000, #000);
  d: path("M12.958 12.883a.51.51 0 0 0-.511-.51a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.236");
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.g6dgamb9p {
  stop-color: var(--svg-color--8654d1, #8654D1);
}

.gl3wl_9gz {
  stop-color: var(--svg-color--ff7e7a, #FF7E7A);
  stop-opacity: 0;
}

.gl7hf2blh {
  fill: var(--svg-color--f0aba4, #F0ABA4);
  d: path("M12.639 17.631h3.984v1.383c0 1.1-.892 1.813-1.992 1.813s-1.992-.713-1.992-1.813z");
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

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hnlppfbil {
  stop-color: var(--svg-color--9860d3, #9860D3);
  stop-opacity: 0;
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.hy0z0nf6k {
  stop-color: var(--svg-color--a4888c, #A4888C);
  stop-opacity: 0;
}

.il490o5xd {
  stop-color: var(--svg-color--332a2e, #332A2E);
}

.intda8ekf {
  stop-color: var(--svg-color--d09790, #D09790);
  stop-opacity: 0;
}

.iwql9tbwr {
  stop-color: var(--svg-color--8752d9, #8752D9);
}

.ixw8njbyx {
  stop-color: var(--svg-color--cc9987, #CC9987);
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
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

.je8i96bea {
  stop-color: var(--svg-color--845b99, #845B99);
  stop-opacity: 0;
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jrx3i8b1t {
  d: path("m19.686 5.22l5.42 1.537l-.338 1.189l-4.312-1.223a1.15 1.15 0 0 1-.793-1.42z");
}

.jsdz5mbzw {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.022 11.719c.653 0 1.204.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.228-.271a1.4 1.4 0 0 1 1.372-1.128");
}

.jx32ovy0j {
  fill-rule: evenodd;
  d: path("M21.816 14.475a3.25 3.25 0 0 0 .324-1.427c0-.468-.097-.906-.269-1.306h.005a3 3 0 0 0-.28-.513l-.003-.003a3.24 3.24 0 0 1-.526-1.77v-.011a3.3 3.3 0 0 0-3.3-3.3a.54.54 0 0 1-.455-.232a3.3 3.3 0 0 0-2.682-1.376a3.3 3.3 0 0 0-2.681 1.376a.56.56 0 0 1-.456.233h-.085a3.3 3.3 0 0 0-3.214 3.299v.01a3.24 3.24 0 0 1-.526 1.771l-.002.004a3.3 3.3 0 0 0-.22 3.245a.52.52 0 0 1 0 .455a3.213 3.213 0 0 0 2.894 4.625h8.581a3.213 3.213 0 0 0 2.895-4.625a.52.52 0 0 1 0-.455m-12.26-2.673h-.013l1.199 2.356c.123 2.802 1.217 0 3.888 0c2.672 0 3.837 3.12 3.96.317l1.136-3.197c-.054-1.245-.956-1.333-1.136-1.333h-3.22a3.86 3.86 0 0 1-3.19-1.673a.264.264 0 0 0-.46.051l-.083.194a2.3 2.3 0 0 1-1.24 1.255l-.052.02c-.236.123-.79.49-.81 1.439l.01.306z");
}

.jzjqx7qlk {
  stop-color: var(--svg-color--ff7e7a, #FF7E7A);
}

.k2oqpgb0o {
  stop-color: var(--svg-color--f4b89e, #F4B89E);
  stop-opacity: 0;
}

.k7vepx8sv {
  fill: var(--svg-color--232121, #232121);
  d: path("M9.561 7.077c.566-.6 1.637-.6 2.131-.511l.396 1.29c-.253-.039-.478.05-.668.235c-.448 1.26-1.99 1.956-2.704 2.146c-.148-1.492.11-2.38.845-3.16");
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kg_c-rbpr {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m18.362 10.83l-.138.23za.268.268 0 0 1-.275.46l-.005-.003a1 1 0 0 0-.113-.058a3 3 0 0 0-.343-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 0 1-.093-.528c.513-.09.989 0 1.329.109a3.3 3.3 0 0 1 .558.238l.01.006l.002.002z");
}

.km2ignmjc {
  d: path("M9.964 14.14a1.074 1.074 0 1 0 0-2.15a1.074 1.074 0 0 0 0 2.15");
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l38p1-72g {
  stop-color: var(--svg-color--dfa791, #DFA791);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l7ry8rboi {
  fill: var(--svg-color--d19590, #D19590);
  d: path("m14.238 12.842l-.683 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.494-.376-.613 0");
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

.lxc0fmbqt {
  stop-color: var(--svg-color--c0a0b5, #C0A0B5);
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

.me4c4fyoe {
  stop-color: var(--svg-color--ac7864, #AC7864);
}

.mnj4ecbxj {
  d: path("M9.543 11.802h.013l-.01-.265l-.01-.306c.02-.949.574-1.316.81-1.439q.024-.008.05-.02l.052-.02a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.051a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.081.088 1.135 1.332l-.119 3.074c-.123 2.802-2.311 4.684-4.983 4.684s-4.86-1.882-4.983-4.684z");
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n1w64orcn {
  stop-color: var(--svg-color--b87c92, #B87C92);
  stop-opacity: 0;
}

.ndjzgnbjo {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m17.037 8.884l-1.425.262a.688.688 0 1 1-.125-1.365h2.34c1.385 0 1.843 1.395 1.9 1.872a3.15 3.15 0 0 0-2.69-.769");
}

.nhus6q3at {
  stop-color: var(--svg-color--9a6fdb, #9A6FDB);
  stop-opacity: 0;
}

.ni_6htbzm {
  stop-color: var(--svg-color--b71143, #B71143);
}

.njp0-cbrk {
  stop-color: var(--svg-color--dfa791, #DFA791);
  stop-opacity: 0;
}

.nm6odobve {
  d: path("M21.584 29.356h3.709v-.463c0-3.217-1.436-6.103-3.709-8.067z");
}

.nohhk2bof {
  fill: var(--svg-color--f1c4b2, #F1C4B2);
  d: path("m14.248 12.704l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.645-.377-.765 0");
}

.nwt8glb0m {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
  stop-opacity: 0;
}

.o70f9fbyi {
  fill: var(--svg-color--c58c80, #C58C80);
  d: path("M9.964 14.14a1.074 1.074 0 1 0 0-2.15a1.074 1.074 0 0 0 0 2.15");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ok0s313ee {
  stop-color: var(--svg-color--8956cf, #8956CF);
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.oyqxcccjr {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.63 15.977c-.52 0-1.01-.126-1.42-.345c-.142-.073-.293.089-.204.22a1.932 1.932 0 0 0 3.25 0c.088-.137-.063-.293-.204-.22a3 3 0 0 1-1.421.345Z");
}

.p0qxmpf9n {
  cx: 12.177px;
  cy: 12.372px;
  rx: 0.39px;
  ry: 0.197px;
}

.p47-3c-mm {
  stop-color: var(--svg-color--ae81f2, #AE81F2);
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

.prv6psg5p {
  stop-color: var(--svg-color--eabbab, #EABBAB);
  stop-opacity: 0;
}

.ptt7y_f2j {
  stop-color: var(--svg-color--cc9299, #CC9299);
  stop-opacity: 0;
}

.qe5e1hb-k {
  d: path("M14.027 5.274c-1.132-.25-2.15.88-2.267 1.3c1.052 3.544 3.713 3.35 6.34 3.058c1.573-.175 1.743.542 1.877.889c0-3.933-3.344-4.671-5.921-5.24z");
}

.qpkqxibzk {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
}

.qtibqw8vp {
  stop-color: var(--svg-color--1f1021, #1F1021);
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

.rm-21olxw {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.75 12.18c.063.085-.07.188-.221.301s-.264.193-.327.108c-.064-.085.007-.246.158-.359c.152-.113.326-.136.39-.05");
}

.rraw6sbsp {
  stop-color: var(--svg-color--ff9266, #FF9266);
}

.s44y8_wdc {
  stop-color: var(--svg-color--a47463, #A47463);
  stop-opacity: 0;
}

.sheftacio {
  stop-color: var(--svg-color--ffd8c1, #FFD8C1);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sncijkqpo {
  stop-color: var(--svg-color--643a7c, #643A7C);
  stop-opacity: 0;
}

.sqxrh1b6n {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
}

.srm_r_guo {
  stop-color: var(--svg-color--ff6792, #FF6792);
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.suybu51ug {
  stop-color: var(--svg-color--d09790, #D09790);
}

.tddz0-g7t {
  stop-color: var(--svg-color--d29394, #D29394);
  stop-opacity: 0;
}

.tk20gvbnd {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
  stop-opacity: 0;
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.u3s0_kqys {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.57 10.692c.323-.078 1.125-.039 1.661.345");
}

.u4cmqnbdb {
  stop-color: var(--svg-color--412558, #412558);
}

.uaoaczbhz {
  stop-color: var(--svg-color--bc8272, #BC8272);
}

.usjme_bkn {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.24 11.719c-.654 0-1.205.45-1.355 1.059a.273.273 0 0 0 .268.34h2.23a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.uxe1igbwt {
  cx: 22.902px;
  cy: 9.817px;
  r: 1.117px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.v-9tn59hb {
  stop-color: var(--svg-color--dba98b, #DBA98B);
  stop-opacity: 0;
}

.v5pn-pcxn {
  stop-color: var(--svg-color--c7868a, #C7868A);
  stop-opacity: 0;
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.v83a3u3_r {
  cx: 26.551px;
  cy: 7.804px;
  r: 1.117px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.vb9hamb2p {
  d: path("M9.945 14.674a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.vdvey0c5l {
  stop-color: var(--svg-color--d29394, #D29394);
}

.vo-5c_b0h {
  fill: var(--svg-color--272528, #272528);
  d: path("M13.489 12.496c-.266-.467-.67-.836-1.538-.836c-.38 0-.747.106-1.072.37c-.27.216-.233.494-.025.598l.556.318c.652-.21 1.373-.24 2.079-.45");
}

.vzbvt7b3z {
  stop-color: var(--svg-color--a46bd8, #A46BD8);
  stop-opacity: 0;
}

.w--6bgeqj {
  stop-color: var(--svg-color--e5b1a5, #E5B1A5);
}

.w5_7ycb6b {
  stop-color: var(--svg-color--ff4f4f, #FF4F4F);
}

.wj0k-xifb {
  cx: 22.902px;
  cy: 9.817px;
  r: 1.652px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.wrm-qpibj {
  fill: var(--svg-color--2a2a2a, #2A2A2A);
  d: path("M14.027 5.274c-1.132-.25-2.15.88-2.267 1.3c1.052 3.544 3.713 3.35 6.34 3.058c1.573-.175 1.743.542 1.877.889c0-3.933-3.344-4.671-5.921-5.24z");
}

.wum9l96_j {
  stop-color: var(--svg-color--d59f97, #D59F97);
}

.wy7e69bbh {
  stop-color: var(--svg-color--c8b3b7, #C8B3B7);
  stop-opacity: 0;
}

.x_nfl_ozw {
  d: path("M12.639 17.631h3.984v1.383c0 1.1-.892 1.813-1.992 1.813s-1.992-.713-1.992-1.813z");
}

.x7bl4zbkb {
  fill: var(--svg-color--955ece, #955ECE);
  d: path("M7.317 20.827C5.044 22.79 3.61 25.676 3.61 28.893v.463h3.708z");
}

.xbgj88f0b {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xele9f15f {
  d: path("m14.248 12.704l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.645-.377-.765 0");
}

.xkdv6ybqk {
  d: path("M16.75 12.18c.063.085-.07.188-.221.301s-.264.193-.327.108c-.064-.085.007-.246.158-.359c.152-.113.326-.136.39-.05");
}

.xl9xm7bnj {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
  stop-opacity: 0;
}

.y_9l2i5ww {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
  stop-opacity: 0;
}

.y-yheec7q {
  d: path("M9.561 7.077c.566-.6 1.637-.6 2.131-.511l.396 1.29c-.253-.039-.478.05-.668.235c-.448 1.26-1.99 1.956-2.704 2.146c-.148-1.492.11-2.38.845-3.16");
}

.yewopxysi {
  fill: var(--svg-color--000, #000);
  d: path("M16.304 12.883c0-.284.227-.51.51-.51a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.06-.236");
}

.ynae43ovp {
  stop-color: var(--svg-color--dba98b, #DBA98B);
}

.z-rzt8b_f {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.zduonub6o {
  stop-color: var(--svg-color--a677eb, #A677EB);
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

</style>
