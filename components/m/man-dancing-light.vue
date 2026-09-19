<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iLe9wFb)"><path fill="url(#iDxo0eI)" class="mt-vedbkv"/><path fill="url(#iUnhLfc)" class="mt-vedbkv"/></g><g filter="url(#iOL9Xib)"><path fill="url(#imwSJ8b)" class="vqp8gziqg"/><path fill="url(#i8zPUwe)" class="vqp8gziqg"/></g><g filter="url(#iIMBY2b)"><path clip-rule="evenodd" class="irtsewoae"/><path fill="url(#iQZzNfc)" clip-rule="evenodd" class="d7z8f74ij"/><path fill="url(#i1ctYud)" clip-rule="evenodd" class="d7z8f74ij"/></g><g filter="url(#i6tYnMe)"><path fill="url(#iacCiae)" class="a1bm4qc3u"/></g><g filter="url(#itGdv3d)"><path fill="url(#iMovpyz)" class="vuihc-bcj"/><path fill="url(#iZUw8Bd)" class="vuihc-bcj"/><path fill="url(#it7XaSd)" class="vuihc-bcj"/><path fill="url(#icED1YI)" class="vuihc-bcj"/></g><g filter="url(#i6xjZre)"><path fill="url(#iKJ5SJE)" class="vm6ce_jmk"/><path fill="url(#iNtDdEc)" class="vm6ce_jmk"/><path fill="url(#iZSwmbe)" class="vm6ce_jmk"/><path fill="url(#iCEHRqb)" class="vm6ce_jmk"/></g><path fill="url(#izAx3Ud)" clip-rule="evenodd" class="eiz9jcf6n"/><path fill="url(#iQp1XNe)" clip-rule="evenodd" class="eiz9jcf6n"/><g filter="url(#iWPKLkb)"><path clip-rule="evenodd" class="bzjjhsbjs"/></g><path fill="url(#ihi3Nge)" class="z5ewkjg-x"/><g filter="url(#iq1jmoe)"><path class="hi05lwx5z"/></g><path fill="url(#igOfCoc)" class="eqxpq3aoz"/><path fill="url(#iXmPazd)" class="eqxpq3aoz"/><path fill="url(#iw40SNu)" class="eqxpq3aoz"/><g filter="url(#ivsEo3O)"><path class="hebmvfbjm"/></g><g filter="url(#inoJW6N)"><path class="hd_pc76ps"/></g><g filter="url(#i4ejOTc)"><path class="s5iez-b2n"/><path fill="url(#inF27se)" class="a9sssdqqd"/></g><path fill="url(#iKnRNQc)" class="b3k1q3bat"/><path fill="url(#ihXZZqb)" class="b3k1q3bat"/><path fill="url(#iGst4RH)" class="b3k1q3bat"/><g filter="url(#ig5UrOb)"><path class="n-o01qbda"/><path fill="url(#ixP2S7d)" class="eeo67f0sx"/></g><g filter="url(#iMIbbzc)"><circle fill="url(#i4G1Wfd)" class="lyqmr2bbc"/></g><g filter="url(#impUAEb)"><circle fill="url(#iXXLOli)" class="bhb8ipbdm"/></g><g filter="url(#iWetYbd)"><circle fill="url(#imFUp4b)" class="ol6g7lb1q"/></g><g filter="url(#iH5FIkd)"><rect transform="rotate(32.175 10.93 16.017)" class="kjp___bnd"/></g><g filter="url(#ijRYZac)"><path fill="url(#ibNxRle)" class="ball_rb6t"/><path fill="url(#iXcXaEb)" class="ball_rb6t"/></g><g filter="url(#iCYi4ye)"><path fill="url(#iRRrLYL)" class="yqnsa3b2w"/></g><path fill="url(#iUhse5Y)" class="oyt5f2bkb"/><rect fill="url(#iyaHUAb)" class="jzo6g3ltx"/><rect fill="url(#iQf9xLc)" class="jzo6g3ltx"/><g filter="url(#i9zSE9d)"><path class="le_jibc-q"/></g><g filter="url(#iJ8ERJX)"><rect class="j9vpvpb6t"/></g><g filter="url(#iZGftSU)"><rect class="uph8jub-u"/></g><g filter="url(#iY62o7d)"><rect class="hrr-d093p"/></g><g filter="url(#iqlmqZc)"><path fill="url(#iQtyKTb)" class="su2ao5zll"/></g><g filter="url(#iXjNC3W)"><circle fill="url(#iJ1FBAY)" class="rj_fg2b_y"/></g><g filter="url(#iuB9HXd)"><circle fill="url(#i5o62Ke)" class="hrvpkcfen"/></g><g filter="url(#iQtkpuc)"><circle fill="url(#i1VLNbd)" class="drygnxbpr"/><circle fill="url(#iBf2hMc)" class="drygnxbpr"/></g><g filter="url(#i3MjABd)"><circle class="ihmb0ewkn"/><circle fill="url(#iW64Sac)" class="d9e478b-p"/><circle fill="url(#ilb7sHc)" class="d9e478b-p"/></g><g filter="url(#iNkugCc)"><path fill="url(#isZ3Lic)" class="d5agk7qnv"/><path fill="url(#izpRslc)" class="d5agk7qnv"/><path fill="url(#ikXEsHe)" class="d5agk7qnv"/><path fill="url(#iosFOoe)" class="d5agk7qnv"/><path fill="url(#izIT4pb)" class="d5agk7qnv"/><path fill="url(#iB4DSyU)" class="d5agk7qnv"/></g><g filter="url(#ijkJ3UC)"><path fill="url(#ineYrkc)" class="o-nc8gboa"/></g><g filter="url(#i7aOFae)"><path class="u7-t_bctv"/><path fill="url(#iWuuoze)" class="m3nhnl3qz"/><path fill="url(#iV5N5Lb)" class="m3nhnl3qz"/><path fill="url(#iESgkov)" class="m3nhnl3qz"/><path fill="url(#iDSn8vd)" class="m3nhnl3qz"/></g><g filter="url(#iOppf5b)"><path class="ku_a5l0vz"/></g><g filter="url(#iSd4nOe)"><path class="t6xzzwb_a"/><path fill="url(#iWsixDc)" class="jh5yrm30e"/><path fill="url(#iIHuxjd)" class="jh5yrm30e"/><path fill="url(#iEy5vew)" class="jh5yrm30e"/><path fill="url(#iGdmk3c)" class="jh5yrm30e"/></g><path class="sh-1wjb0z"/><g filter="url(#ifBy2pc)"><path class="j_zhygbpv"/></g><g filter="url(#ilI6lXR)"><path class="nioxf_ges"/></g><path class="v_1-k8b0k"/><path fill="url(#ivOn5Dd)" class="v_yd_iblu"/><path class="hi87h5a7i"/><g filter="url(#i3LmFve)"><path class="gi7qf7idp"/><path fill="url(#iJXNoke)" class="qmtvrbb-m"/></g><g filter="url(#iKxtn7b)"><path fill="url(#iFXYMws)" class="ejpl11bao"/></g><path class="jjs34rboa"/><path fill="url(#idCUetd)" class="fiknuo0lj"/><path class="fot63ob9g"/><g filter="url(#iEWMdxb)"><path fill="url(#iVJvJ9d)" class="i14k845su"/></g><g filter="url(#iihDQDb)"><ellipse transform="rotate(-27.914 14.536 7.611)" class="ukq_x9bby"/><ellipse fill="url(#ipAWcBb)" transform="rotate(-27.914 14.536 7.611)" class="lqeg3kbfi"/></g><g filter="url(#iNlpbmb)"><path stroke="url(#iRIJyme)" class="v3ajz9bsa"/></g><defs><radialGradient id="iUnhLfc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.88287 -.57813 .14717 -.4793 13.905 29.648)" gradientUnits="userSpaceOnUse"><stop class="vxv2m-bqm"/><stop offset="1" class="y8kcl1bix"/></radialGradient><radialGradient id="i8zPUwe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.88287 -.57813 .14717 -.4793 23.772 29.648)" gradientUnits="userSpaceOnUse"><stop class="vxv2m-bqm"/><stop offset="1" class="y8kcl1bix"/></radialGradient><radialGradient id="iQZzNfc" cx="0" cy="0" r="1" gradientTransform="rotate(26.222 -7.656 45.296)scale(1.16697 .3839)" gradientUnits="userSpaceOnUse"><stop class="f0cucabtr"/><stop offset="1" class="rcasxucso"/></radialGradient><radialGradient id="iacCiae" cx="0" cy="0" r="1" gradientTransform="rotate(100.074 5.636 12.842)scale(6.98265 6.28539)" gradientUnits="userSpaceOnUse"><stop offset=".436" class="olwuq14vq"/><stop offset="1" class="g4r-t1bcl"/></radialGradient><radialGradient id="iZUw8Bd" cx="0" cy="0" r="1" gradientTransform="matrix(2.48435 3.38708 -1.82506 1.33864 17.053 19.619)" gradientUnits="userSpaceOnUse"><stop class="hxi88nbzr"/><stop offset="1" class="l3am5pbvj"/></radialGradient><radialGradient id="it7XaSd" cx="0" cy="0" r="1" gradientTransform="rotate(147.653 8.167 14.057)scale(1.92338 4.56348)" gradientUnits="userSpaceOnUse"><stop class="mygo_91-e"/><stop offset="1" class="w30s_lbtj"/></radialGradient><radialGradient id="icED1YI" cx="0" cy="0" r="1" gradientTransform="matrix(3.27144 3.19771 -1.19038 1.21783 18.456 17.996)" gradientUnits="userSpaceOnUse"><stop class="gnb7t6epd"/><stop offset="1" class="oxm2fc9jy"/></radialGradient><radialGradient id="iNtDdEc" cx="0" cy="0" r="1" gradientTransform="matrix(4.9441 -8.0188 3.4438 2.12332 10.387 28.67)" gradientUnits="userSpaceOnUse"><stop class="yh2psxb-p"/><stop offset="1" class="i8l7fq6-h"/></radialGradient><radialGradient id="iZSwmbe" cx="0" cy="0" r="1" gradientTransform="rotate(122.867 4.189 13.371)scale(2.40221 3.19663)" gradientUnits="userSpaceOnUse"><stop class="qg9ghcbvt"/><stop offset="1" class="tcm98nmkx"/></radialGradient><radialGradient id="iCEHRqb" cx="0" cy="0" r="1" gradientTransform="rotate(171.215 6.309 10.008)scale(2.38461 1.04291)" gradientUnits="userSpaceOnUse"><stop class="i0b_c8grj"/><stop offset="1" class="nxhf2dq-t"/></radialGradient><radialGradient id="iQp1XNe" cx="0" cy="0" r="1" gradientTransform="rotate(79.509 1.846 15.83)scale(.8581 .41486)" gradientUnits="userSpaceOnUse"><stop offset=".224" class="fglzf7x9d"/><stop offset="1" class="ch_7khbnn"/></radialGradient><radialGradient id="ihi3Nge" cx="0" cy="0" r="1" gradientTransform="rotate(-105.555 11.257 1.57)scale(1.57324 4.12566)" gradientUnits="userSpaceOnUse"><stop class="pb7i5tbeh"/><stop offset="1" class="zkcw-qija"/></radialGradient><radialGradient id="iXmPazd" cx="0" cy="0" r="1" gradientTransform="rotate(117.353 4.025 9.146)scale(3.64758 .73156)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="tp3-xrbff"/><stop offset="1" class="s3rc45b6k"/></radialGradient><radialGradient id="iw40SNu" cx="0" cy="0" r="1" gradientTransform="matrix(-.75783 1.92969 -.78376 -.3078 14.271 9.766)" gradientUnits="userSpaceOnUse"><stop class="c1gbyobwf"/><stop offset="1" class="kzysqdbiz"/></radialGradient><radialGradient id="inF27se" cx="0" cy="0" r="1" gradientTransform="rotate(-148.57 10.887 2.8)scale(1.64805 1.14906)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="kd54_6u1z"/><stop offset="1" class="u8aws4lgo"/></radialGradient><radialGradient id="iKnRNQc" cx="0" cy="0" r="1" gradientTransform="rotate(-112.917 12.347 .255)scale(2.08657 3.55629)" gradientUnits="userSpaceOnUse"><stop class="hkpzwdbin"/><stop offset="1" class="pa-xpmw0g"/></radialGradient><radialGradient id="ihXZZqb" cx="0" cy="0" r="1" gradientTransform="matrix(.42187 1.42187 -.59557 .1767 16.967 10.102)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="e96zuxb7m"/><stop offset="1" class="unfdbqymh"/></radialGradient><radialGradient id="iGst4RH" cx="0" cy="0" r="1" gradientTransform="matrix(.75781 .60547 -1.03195 1.29159 15.538 10.371)" gradientUnits="userSpaceOnUse"><stop class="g214jj2ff"/><stop offset="1" class="qv6zwkcgg"/></radialGradient><radialGradient id="ixP2S7d" cx="0" cy="0" r="1" gradientTransform="matrix(-.34375 2 -3.37016 -.57925 14.858 9.742)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="omhpq8bny"/><stop offset=".75" class="x6-zvqbsc"/></radialGradient><radialGradient id="i4G1Wfd" cx="0" cy="0" r="1" gradientTransform="rotate(140.38 6.637 9.589)scale(.63706)" gradientUnits="userSpaceOnUse"><stop class="qkeppfmvx"/><stop offset="1" class="u2-6tpbfe"/></radialGradient><radialGradient id="iXXLOli" cx="0" cy="0" r="1" gradientTransform="rotate(140.38 6.477 10.411)scale(.63706)" gradientUnits="userSpaceOnUse"><stop class="qkeppfmvx"/><stop offset="1" class="u2-6tpbfe"/></radialGradient><radialGradient id="imFUp4b" cx="0" cy="0" r="1" gradientTransform="rotate(140.38 6.224 11.287)scale(.63706)" gradientUnits="userSpaceOnUse"><stop class="qkeppfmvx"/><stop offset="1" class="u2-6tpbfe"/></radialGradient><radialGradient id="ibNxRle" cx="0" cy="0" r="1" gradientTransform="rotate(79.499 -4.177 14.405)scale(1.94812 .738)" gradientUnits="userSpaceOnUse"><stop class="mjqvhljds"/><stop offset="1" class="n5u_3996t"/></radialGradient><radialGradient id="iRRrLYL" cx="0" cy="0" r="1" gradientTransform="matrix(-.88648 .98484 -1.05171 -.94667 10.533 14.808)" gradientUnits="userSpaceOnUse"><stop class="vyopt_bxu"/><stop offset="1" class="mo3rc5bif"/></radialGradient><radialGradient id="iUhse5Y" cx="0" cy="0" r="1" gradientTransform="rotate(-141.642 11.803 -1.223)scale(1.56107 2.05437)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="r5qf2jd1a"/><stop offset="1" class="y6-1-fjof"/></radialGradient><radialGradient id="iyaHUAb" cx="0" cy="0" r="1" gradientTransform="matrix(-.3125 .38281 -.31148 -.25427 20.151 2.113)" gradientUnits="userSpaceOnUse"><stop class="iv-2-l6ct"/><stop offset="1" class="tlfmt020n"/></radialGradient><radialGradient id="iQtyKTb" cx="0" cy="0" r="1" gradientTransform="rotate(131.576 9.578 7.561)scale(1.29499 1.38067)" gradientUnits="userSpaceOnUse"><stop class="vyopt_bxu"/><stop offset="1" class="mo3rc5bif"/></radialGradient><radialGradient id="iJ1FBAY" cx="0" cy="0" r="1" gradientTransform="matrix(.76295 0 0 1.33517 12.814 7.95)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="crp6d4bqv"/><stop offset="1" class="lu78seb9e"/></radialGradient><radialGradient id="iBf2hMc" cx="0" cy="0" r="1" gradientTransform="matrix(.35942 -.26171 .29871 .41023 17.837 7.835)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="wdqn7tq-u"/><stop offset="1" class="r3t82tbzk"/></radialGradient><radialGradient id="iW64Sac" cx="0" cy="0" r="1" gradientTransform="matrix(.35705 -.65672 .38438 .20899 17.658 8.307)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="n7c5lw_4k"/><stop offset=".916" class="bw8j_5egh"/></radialGradient><radialGradient id="ilb7sHc" cx="0" cy="0" r="1" gradientTransform="rotate(44.709 -.827 25.466)scale(.15862 .20447)" gradientUnits="userSpaceOnUse"><stop class="fa9i5bbvu"/><stop offset="1" class="x8d9utbsu"/></radialGradient><radialGradient id="izpRslc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.10211 -5.5684 0 15.616 7.113)" gradientUnits="userSpaceOnUse"><stop offset=".557" class="p7jmmxb2h"/><stop offset="1" class="uzkpn5btf"/></radialGradient><radialGradient id="izIT4pb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.56827 .6994 0 16.624 7.397)" gradientUnits="userSpaceOnUse"><stop class="m459pab_j"/><stop offset="1" class="rcuz4uefu"/></radialGradient><radialGradient id="iB4DSyU" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.6047 .752 0 14.642 7.382)" gradientUnits="userSpaceOnUse"><stop class="hplqxft1w"/><stop offset="1" class="ay1rn8bxh"/></radialGradient><radialGradient id="iWuuoze" cx="0" cy="0" r="1" gradientTransform="matrix(.34686 -1.28543 .47668 .12863 17.493 6.164)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="iV5N5Lb" cx="0" cy="0" r="1" gradientTransform="matrix(1.6629 .15303 -.08228 .89413 16.779 5.4)" gradientUnits="userSpaceOnUse"><stop offset=".335" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="iESgkov" cx="0" cy="0" r="1" gradientTransform="matrix(0 .73004 -1.13063 0 15.604 4.21)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="iDSn8vd" cx="0" cy="0" r="1" gradientTransform="matrix(1.33644 -.97938 1.53436 2.09376 12.8 7.174)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="iGdmk3c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .0856 -.27503 0 15.746 8.648)" gradientUnits="userSpaceOnUse"><stop class="a7vfdrbiy"/><stop offset="1" class="x6mjr8bji"/></radialGradient><radialGradient id="ivOn5Dd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35265 -.56093 0 16.551 7.653)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iJXNoke" cx="0" cy="0" r="1" gradientTransform="matrix(-.1008 -.1299 .17884 -.13879 16.452 7.69)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="idCUetd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35267 -.56096 0 14.654 7.653)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ipAWcBb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00336 -.21476 .25815 -.00404 14.53 7.748)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iLe9wFb" width="5.373" height="2.752" x="8.532" y="27.311" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.117647 0 0 0 0 0.290196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_622"/></filter><filter id="iOL9Xib" width="5.373" height="2.752" x="18.399" y="27.311" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.117647 0 0 0 0 0.290196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_622"/></filter><filter id="iIMBY2b" width="6.055" height="5.783" x="15.962" y="6.237" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.192157 0 0 0 0 0.54902 0 0 0 0 0.772549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_622"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.580392 0 0 0 0 0.760784 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_622" result="effect2_innerShadow_4002_622"/></filter><filter id="i6tYnMe" width="5.188" height="8.109" x="16.797" y="9.289" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.352941 0 0 0 0 0.752941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_622"/></filter><filter id="itGdv3d" width="6.705" height="12.103" x="16.587" y="16.855" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.4 0 0 0 0 0.858824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_622"/></filter><filter id="i6xjZre" width="11.118" height="12.357" x="8.285" y="16.909" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.509804 0 0 0 0 0.74902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_622"/></filter><filter id="iWPKLkb" width="6.488" height="5.992" x="8.619" y="9.83" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.160784 0 0 0 0 0.501961 0 0 0 0 0.717647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_622"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.541176 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_622" result="effect2_innerShadow_4002_622"/></filter><filter id="iq1jmoe" width="4.196" height="9.342" x="12.799" y="9.887" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.458824 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_622"/></filter><filter id="ivsEo3O" width="3.018" height="6.455" x="13.628" y="11.143" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_622" stdDeviation=".1"/></filter><filter id="inoJW6N" width="2.718" height="6.155" x="13.977" y="11.064" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.670588 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_622"/></filter><filter id="i4ejOTc" width="2.18" height="1.491" x="16.731" y="9.787" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.388235 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_622"/></filter><filter id="ig5UrOb" width="2.654" height="2.575" x="13.768" y="9.733" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.403922 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_622"/></filter><filter id="iMIbbzc" width="1.225" height="1.225" x="16.839" y="12.433" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.352941 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_622"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_622" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.025" dy=".03"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.878431 0 0 0 0 0.976471 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_4002_622"/></filter><filter id="impUAEb" width="1.225" height="1.225" x="17.081" y="13.991" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.996078 0 0 0 0 0.321569 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_622"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_622" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.025" dy=".03"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.878431 0 0 0 0 0.976471 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_4002_622"/></filter><filter id="iWetYbd" width="1.225" height="1.225" x="17.191" y="15.702" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.27451 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_622"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_622" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.025" dy=".03"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.878431 0 0 0 0 0.976471 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_4002_622"/></filter><filter id="iH5FIkd" width="1.124" height="1.036" x="10.671" y="16.11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.533333 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_622"/></filter><filter id="ijRYZac" width="2.496" height="2.609" x="9.04" y="15.586" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.52549 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_622"/></filter><filter id="iCYi4ye" width="3.308" height="2.19" x="8.228" y="14.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.34902 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_622"/></filter><filter id="i9zSE9d" width="1.381" height="1.353" x="18.793" y="3.298" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.6 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_622"/></filter><filter id="iJ8ERJX" width=".87" height="1.395" x="21.197" y="2.871" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.623529 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_622"/></filter><filter id="iZGftSU" width=".87" height="1.395" x="20.578" y="2.871" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.623529 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_622"/></filter><filter id="iY62o7d" width=".87" height="1.395" x="19.958" y="2.871" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.623529 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_622"/></filter><filter id="iqlmqZc" width="3.212" height="2.158" x="19.357" y="4.765" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.8 0 0 0 0 0.34902 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_622"/></filter><filter id="iXjNC3W" width="1.652" height="1.452" x="12.814" y="7.224" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.694118 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_622"/></filter><filter id="iuB9HXd" width="1.865" height="1.865" x="12.607" y="7.017" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_622" stdDeviation=".25"/></filter><filter id="iQtkpuc" width="1.702" height="1.702" x="16.95" y="6.974" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.623529 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_622"/></filter><filter id="i3MjABd" width="1.865" height="1.865" x="16.743" y="7.017" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_622" stdDeviation=".25"/></filter><filter id="iNkugCc" width="4.51" height="5.479" x="13.361" y="5.504" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.615686 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_622"/></filter><filter id="ijkJ3UC" width="3.846" height="3.333" x="14.678" y="4.504" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_622" stdDeviation=".5"/></filter><filter id="i7aOFae" width="5.479" height="3.597" x="12.864" y="4.11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_622"/></filter><filter id="iOppf5b" width="2.265" height="2.666" x="14.367" y="7.024" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_622" stdDeviation=".375"/></filter><filter id="iSd4nOe" width=".916" height="1.266" x="15.146" y="7.653" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_622" stdDeviation=".025"/></filter><filter id="ifBy2pc" width="1.437" height="1.04" x="16.118" y="6.137" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_622"/></filter><filter id="ilI6lXR" width="1.437" height="1.04" x="13.88" y="6.137" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_622"/></filter><filter id="i3LmFve" width=".455" height=".416" x="16.175" y="7.405" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_622" stdDeviation=".05"/></filter><filter id="iKxtn7b" width=".614" height=".623" x="16.484" y="7.382" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_622" stdDeviation=".1"/></filter><filter id="iEWMdxb" width=".655" height=".678" x="14.553" y="7.354" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_622" stdDeviation=".1"/></filter><filter id="iihDQDb" width=".51" height=".419" x="14.281" y="7.402" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_622" stdDeviation=".05"/></filter><filter id="iNlpbmb" width=".862" height="1.411" x="13.146" y="5.483" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_622" stdDeviation=".125"/></filter><linearGradient id="iDxo0eI" x1="13.397" x2="8.532" y1="29.57" y2="29.57" gradientUnits="userSpaceOnUse"><stop class="leyn8uhkc"/><stop offset="1" class="m4prq-bhs"/></linearGradient><linearGradient id="imwSJ8b" x1="23.264" x2="18.399" y1="29.57" y2="29.57" gradientUnits="userSpaceOnUse"><stop class="leyn8uhkc"/><stop offset="1" class="m4prq-bhs"/></linearGradient><linearGradient id="i1ctYud" x1="21.817" x2="21.588" y1="6.747" y2="7.607" gradientUnits="userSpaceOnUse"><stop offset=".193" class="phi9sxixy"/><stop offset="1" class="y3iq9j8og"/></linearGradient><linearGradient id="iMovpyz" x1="19.689" x2="19.689" y1="17.492" y2="28.957" gradientUnits="userSpaceOnUse"><stop class="chtjorcfq"/><stop offset="1" class="a3ta3d8-l"/></linearGradient><linearGradient id="iKJ5SJE" x1="17.299" x2="12.085" y1="17.307" y2="25.695" gradientUnits="userSpaceOnUse"><stop class="wbm6gtb2b"/><stop offset="1" class="wsr-x9y-q"/></linearGradient><linearGradient id="izAx3Ud" x1="16.623" x2="16.623" y1="11.602" y2="17.289" gradientUnits="userSpaceOnUse"><stop class="ft8y4ezam"/><stop offset="1" class="dpzeg8stn"/></linearGradient><linearGradient id="igOfCoc" x1="14.389" x2="15.076" y1="19.664" y2="17.477" gradientUnits="userSpaceOnUse"><stop class="czfaoab9t"/><stop offset="1" class="q9y6v7blv"/></linearGradient><linearGradient id="iXcXaEb" x1="9.123" x2="9.795" y1="16.227" y2="17.305" gradientUnits="userSpaceOnUse"><stop class="ctmo8abbc"/><stop offset="1" class="p99znfbzx"/></linearGradient><linearGradient id="iQf9xLc" x1="19.912" x2="19.912" y1="3.891" y2="3.195" gradientUnits="userSpaceOnUse"><stop class="m02kntife"/><stop offset="1" class="zc6yl0bhp"/></linearGradient><linearGradient id="i5o62Ke" x1="13.539" x2="13.261" y1="8.071" y2="8.071" gradientUnits="userSpaceOnUse"><stop class="wachewblq"/><stop offset="1" class="px4pa2bzd"/></linearGradient><linearGradient id="i1VLNbd" x1="18.148" x2="17.792" y1="7.475" y2="8.578" gradientUnits="userSpaceOnUse"><stop class="fuy988_rs"/><stop offset="1" class="h2u-65bda"/></linearGradient><linearGradient id="isZ3Lic" x1="17.358" x2="14.038" y1="8.119" y2="8.614" gradientUnits="userSpaceOnUse"><stop class="z8y6fgvmn"/><stop offset="1" class="tqgh1edwg"/></linearGradient><linearGradient id="ikXEsHe" x1="13.151" x2="14.611" y1="8.783" y2="8.833" gradientUnits="userSpaceOnUse"><stop class="z3n_1mwef"/><stop offset="1" class="rvf3-0bfj"/></linearGradient><linearGradient id="iosFOoe" x1="13.258" x2="14.076" y1="9.291" y2="9.262" gradientUnits="userSpaceOnUse"><stop class="hmo3unbrx"/><stop offset="1" class="yyvs3obha"/></linearGradient><linearGradient id="ineYrkc" x1="15.373" x2="18.913" y1="6.821" y2="5.554" gradientUnits="userSpaceOnUse"><stop class="sbbw_6vcc"/><stop offset="1" class="b7cutjkii"/></linearGradient><linearGradient id="iWsixDc" x1="15.228" x2="15.636" y1="8.406" y2="8.406" gradientUnits="userSpaceOnUse"><stop class="h7h6nwjtb"/><stop offset="1" class="btip4dbzo"/></linearGradient><linearGradient id="iIHuxjd" x1="16.012" x2="15.566" y1="8.546" y2="8.539" gradientUnits="userSpaceOnUse"><stop class="ag4c77bht"/><stop offset="1" class="qb120pbsb"/></linearGradient><linearGradient id="iEy5vew" x1="15.688" x2="15.688" y1="8.869" y2="8.619" gradientUnits="userSpaceOnUse"><stop class="rlzetx3ey"/><stop offset="1" class="zf2atv-8x"/></linearGradient><linearGradient id="iFXYMws" x1="16.889" x2="16.753" y1="7.677" y2="7.761" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iVJvJ9d" x1="14.977" x2="14.841" y1="7.677" y2="7.761" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iRIJyme" x1="13.577" x2="13.577" y1="5.815" y2="6.753" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-dancing-light" /></template>
<style>
.a1bm4qc3u {
  d: path("M19.438 11.086c-.8-.988-1.708-1.432-2.078-1.547l-.562.188l1.234 7.671c1.576 0 2.842-.575 3.51-1.022a.45.45 0 0 0 .18-.48a13.3 13.3 0 0 0-2.284-4.81");
}

.a3ta3d8-l {
  stop-color: var(--svg-color--357ad1, #357AD1);
}

.a7vfdrbiy {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
}

.a9sssdqqd {
  d: path("M18.577 10.89c-.23-.26-.686-.706-1.229-1.003h-.617l.316 1.39c.273-.042.976-.12 1.441-.172c.11-.013.162-.13.089-.214");
}

.ag4c77bht {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
}

.ay1rn8bxh {
  stop-color: var(--svg-color--d0958d, #D0958D);
  stop-opacity: 0;
}

.b3k1q3bat {
  d: path("M17.232 11.542c-.02-.47-.113-.86-.197-1.095c-.044-.126-.167-.197-.3-.197h-.952a.377.377 0 0 0-.212.689l1.225.83c.19.129.446.003.436-.227");
}

.b7cutjkii {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
  stop-opacity: 0;
}

.ball_rb6t {
  d: path("m9.322 17.597l-.282-1.363l2.172-.648l.31 1.548a.75.75 0 0 1-.572.878l-.729.164a.75.75 0 0 1-.899-.58");
}

.bhb8ipbdm {
  cx: 17.794px;
  cy: 14.504px;
  r: 0.313px;
}

.btip4dbzo {
  stop-color: var(--svg-color--dfa790, #DFA790);
  stop-opacity: 0;
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bw8j_5egh {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
}

.bzjjhsbjs {
  fill: var(--svg-color--34a1f0, #34A1F0);
  fill-rule: evenodd;
  d: path("m10.035 11.029l4.216-1.199l.656 2.309l-3.852 1.095l.24 2.342l-2.387.246l-.279-2.718a1.95 1.95 0 0 1 1.406-2.075");
}

.c1gbyobwf {
  stop-color: var(--svg-color--307ba7, #307BA7);
}

.ch_7khbnn {
  stop-color: var(--svg-color--ff5d09, #FF5D09);
  stop-opacity: 0;
}

.chtjorcfq {
  stop-color: var(--svg-color--44b9ff, #44B9FF);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crp6d4bqv {
  stop-color: var(--svg-color--cf9888, #CF9888);
}

.ctmo8abbc {
  stop-color: var(--svg-color--cf979c, #CF979C);
}

.czfaoab9t {
  stop-color: var(--svg-color--225fcf, #225FCF);
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.d5agk7qnv {
  d: path("M13.361 7.058c0-.116.047-.255.14-.325l.07-.07a.46.46 0 0 0 .163-.37v-.371c0-.116.07-.209.187-.232c.28-.07.863-.186 1.702-.186c.84 0 1.423.116 1.703.186a.25.25 0 0 1 .186.232v.37c0 .14.07.279.163.372c.219.153.205.237.187.417c-.023.232-.047.626-.047.626h.008l-.115 1.721c-.07.77-.675 1.306-1.396 1.306h-1.396c-.744 0-1.326-.537-1.396-1.306c-.06-.79-.087-1.582-.159-2.37");
}

.d7z8f74ij {
  fill-rule: evenodd;
  d: path("M21.817 6.383L21.69 8.46a2.2 2.2 0 0 1-1.335 1.89l-3.454 1.47l-.939-2.21l3.34-1.42l.12-1.954z");
}

.d9e478b-p {
  cx: 17.676px;
  cy: 7.95px;
  r: 0.433px;
}

.dpzeg8stn {
  stop-color: var(--svg-color--ff6b3b, #FF6B3B);
}

.drygnxbpr {
  cx: 17.675px;
  cy: 7.95px;
  r: 0.726px;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e96zuxb7m {
  stop-color: var(--svg-color--c49282, #C49282);
}

.eeo67f0sx {
  d: path("m13.77 11.97l.262-2.087h.418l1.833 1.408a.1.1 0 0 1-.024.172l-2.08.823a.3.3 0 0 1-.408-.316");
}

.eiz9jcf6n {
  fill-rule: evenodd;
  d: path("M18.407 10.93c.515 1.086 1.031 3.898.515 6.36H14.83c-.058-1.746-.282-5.607-.719-7.095h3.438zm-1.457-.68c.088.15.254.644.282 1.292c.01.23-.246.356-.436.227l-2.24-1.519z");
}

.ejpl11bao {
  d: path("M16.898 7.783a.37.37 0 0 0-.101-.201l-.113.124l.05.099z");
}

.eqxpq3aoz {
  d: path("m12.876 12.71l1.157-2.827l1.64 1.422c1.34 2.11.963 5.853.465 7.596a.465.465 0 0 1-.592.306l-2.604-.797a.204.204 0 0 1-.136-.25c.195-.695.49-2.014.546-2.933c.056-.907-.273-2.024-.476-2.516");
}

.f0cucabtr {
  stop-color: var(--svg-color--1e8acb, #1E8ACB);
}

.fa9i5bbvu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
}

.fglzf7x9d {
  stop-color: var(--svg-color--ff5d09, #FF5D09);
}

.fiknuo0lj {
  d: path("M14.653 7.446a.388.388 0 0 0-.374.49h.75a.39.39 0 0 0-.376-.49");
}

.fot63ob9g {
  fill: var(--svg-color--000, #000);
  d: path("M14.875 7.834a.22.22 0 0 0-.222-.222a.22.22 0 0 0-.197.324h.393a.2.2 0 0 0 .026-.102");
}

.ft5dv1b6b {
  fill: none;
}

.ft8y4ezam {
  stop-color: var(--svg-color--ff9255, #FF9255);
}

.fuy988_rs {
  stop-color: var(--svg-color--fbd3bd, #FBD3BD);
}

.g214jj2ff {
  stop-color: var(--svg-color--b17464, #B17464);
}

.g4r-t1bcl {
  stop-color: var(--svg-color--4087da, #4087DA);
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gi7qf7idp {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.523 7.528c.028.037-.03.082-.096.13c-.065.05-.114.085-.142.048s.003-.107.07-.156c.065-.05.14-.06.168-.022");
}

.gnb7t6epd {
  stop-color: var(--svg-color--40b1ff, #40B1FF);
}

.h2u-65bda {
  stop-color: var(--svg-color--f0b8a4, #F0B8A4);
}

.h7h6nwjtb {
  stop-color: var(--svg-color--dfa790, #DFA790);
}

.hd_pc76ps {
  fill: var(--svg-color--40c2ff, #40C2FF);
  d: path("m15.509 11.164l.163.134c.99 1.557 1.043 4.003.804 5.878c-.008.056-.087.058-.099.003c-.444-2.034-1.175-3.34-1.597-3.825a.106.106 0 0 1 .035-.166l.576-.251a.04.04 0 0 0-.001-.074l-1.413-.581z");
}

.hebmvfbjm {
  fill: var(--svg-color--239cfd, #239CFD);
  d: path("m15.36 11.343l.163.134c.99 1.557 1.043 4.003.803 5.879c-.007.055-.086.057-.098.002c-.444-2.033-1.175-3.339-1.597-3.824a.106.106 0 0 1 .035-.167l.575-.25a.04.04 0 0 0 0-.074l-1.413-.582z");
}

.hi05lwx5z {
  fill: var(--svg-color--3ea3f7, #3EA3F7);
  d: path("m12.876 12.71l1.153-2.823l1.643 1.418c1.34 2.11.963 5.853.466 7.596a.465.465 0 0 1-.592.306l-2.604-.797a.204.204 0 0 1-.136-.25c.195-.695.49-2.014.546-2.933c.056-.907-.273-2.024-.476-2.516");
}

.hi87h5a7i {
  fill: var(--svg-color--000, #000);
  d: path("M16.33 7.834a.22.22 0 0 1 .222-.222a.22.22 0 0 1 .197.324h-.393a.2.2 0 0 1-.027-.102");
}

.hkpzwdbin {
  stop-color: var(--svg-color--f6c9b8, #F6C9B8);
}

.hmo3unbrx {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
}

.hplqxft1w {
  stop-color: var(--svg-color--d0958d, #D0958D);
}

.hrr-d093p {
  width: 0.62px;
  height: 1.395px;
  x: 19.958px;
  y: 2.871px;
  fill: var(--svg-color--e8b8a2, #E8B8A2);
  rx: 0.31px;
}

.hrvpkcfen {
  cx: 13.539px;
  cy: 7.95px;
  r: 0.433px;
}

.hxi88nbzr {
  stop-color: var(--svg-color--2b8afb, #2B8AFB);
}

.i0b_c8grj {
  stop-color: var(--svg-color--2774e5, #2774E5);
}

.i14k845su {
  d: path("M15.008 7.788c0-.125-.102-.209-.13-.234l-.125.121l.077.157z");
}

.i8l7fq6-h {
  stop-color: var(--svg-color--4081dd, #4081DD);
  stop-opacity: 0;
}

.ihmb0ewkn {
  cx: 17.676px;
  cy: 7.95px;
  r: 0.433px;
  fill: var(--svg-color--e4af9a, #E4AF9A);
}

.irtsewoae {
  fill: var(--svg-color--35abf6, #35ABF6);
  fill-rule: evenodd;
  d: path("M21.817 6.383L21.69 8.46a2.2 2.2 0 0 1-1.335 1.89l-3.454 1.47l-.939-2.21l3.34-1.42l.12-1.954z");
}

.iv-2-l6ct {
  stop-color: var(--svg-color--f6c8ae, #F6C8AE);
}

.j_zhygbpv {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M17.22 6.767v-.001l-.003-.002l-.005-.004l-.067-.047a1.23 1.23 0 0 0-.831-.16a.232.232 0 0 0 .072.458a.77.77 0 0 1 .512.096l.024.016l.004.002a.232.232 0 0 0 .295-.358");
}

.j9vpvpb6t {
  width: 0.62px;
  height: 1.395px;
  x: 21.197px;
  y: 2.871px;
  fill: var(--svg-color--e8b8a2, #E8B8A2);
  rx: 0.31px;
}

.jh5yrm30e {
  d: path("m15.438 7.826l-.232.739a.234.234 0 0 0 .227.304h.342c.16 0 .273-.155.226-.304l-.231-.74c-.05-.163-.28-.163-.332 0");
}

.jjs34rboa {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.563 7.328a.61.61 0 0 0-.589.46a.12.12 0 0 0 .117.148h.97a.1.1 0 0 0 .098-.118a.61.61 0 0 0-.596-.49");
}

.jzo6g3ltx {
  width: 0.645px;
  height: 2.293px;
  x: 19.547px;
  y: 1.938px;
  rx: 0.322px;
}

.kd54_6u1z {
  stop-color: var(--svg-color--ff8337, #FF8337);
  stop-opacity: 0;
}

.kjp___bnd {
  width: 1.191px;
  height: 0.754px;
  x: 10.929px;
  y: 16.017px;
  fill: var(--svg-color--ebaa96, #EBAA96);
  rx: 0.377px;
}

.ku_a5l0vz {
  fill: var(--svg-color--d89992, #D89992);
  d: path("m15.484 7.896l-.357.74c-.044.151.062.303.212.303h.32c.151 0 .257-.154.213-.304l-.216-.739c-.047-.163-.123-.163-.172 0");
}

.kzysqdbiz {
  stop-color: var(--svg-color--307ba7, #307BA7);
  stop-opacity: 0;
}

.l3am5pbvj {
  stop-color: var(--svg-color--2b8afb, #2B8AFB);
  stop-opacity: 0;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.le_jibc-q {
  fill: var(--svg-color--daa592, #DAA592);
  d: path("M18.882 3.54a.39.39 0 0 1 .546-.053l.497.411c.165.136.21.274.051.546c-.054.093-.207.298-.372.162l-.67-.521a.39.39 0 0 1-.052-.546");
}

.leyn8uhkc {
  stop-color: var(--svg-color--3f3641, #3F3641);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lqeg3kbfi {
  cx: 14.536px;
  cy: 7.611px;
  rx: 0.169px;
  ry: 0.086px;
}

.lu78seb9e {
  stop-color: var(--svg-color--be8c77, #BE8C77);
}

.lyqmr2bbc {
  cx: 17.551px;
  cy: 12.945px;
  r: 0.313px;
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m02kntife {
  stop-color: var(--svg-color--d49c84, #D49C84);
}

.m3nhnl3qz {
  d: path("m17.699 5.133l.186.093a.855.855 0 0 1 .443.928l-.256 1.321c-.023.137-.113.229-.249.232h-.008s.024-.394.047-.626c.019-.188-.014-.246-.186-.417a.55.55 0 0 1-.164-.371v-.371a.25.25 0 0 0-.186-.232a7 7 0 0 0-1.703-.186c-.84 0-1.422.116-1.702.186a.226.226 0 0 0-.187.232v.37a.46.46 0 0 1-.163.372l-.07.07c-.093.069-.14.208-.14.324c.023.255.047.626.047.626h-.021a.275.275 0 0 1-.259-.232l-.257-1.322a.89.89 0 0 1 .467-.904l.186-.093c.117-.07.234-.162.35-.255l.42-.44a.85.85 0 0 1 .956-.14c.233.07.49.07.723 0c.35-.115.746-.023 1.026.233l.35.347c.093.116.21.186.35.255");
}

.m459pab_j {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
}

.m4prq-bhs {
  stop-color: var(--svg-color--311e34, #311E34);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mjqvhljds {
  stop-color: var(--svg-color--f8c5b5, #F8C5B5);
}

.mo3rc5bif {
  stop-color: var(--svg-color--f97b38, #F97B38);
}

.mt-vedbkv {
  d: path("M8.532 29.863V27.46h1.726l1.641.844c.499.404 1.211.712 1.715.904a.445.445 0 0 1 .264.565a.44.44 0 0 1-.411.288h-2.652a.26.26 0 0 1-.224-.123l-.424-.678a.14.14 0 0 0-.26.075v.625a.1.1 0 0 1-.102.102H8.732a.2.2 0 0 1-.2-.2");
}

.mygo_91-e {
  stop-color: var(--svg-color--4ab6fb, #4AB6FB);
}

.n-o01qbda {
  fill: var(--svg-color--ff8146, #FF8146);
  d: path("m13.77 11.97l.262-2.087h.418l1.833 1.408a.1.1 0 0 1-.024.172l-2.08.823a.3.3 0 0 1-.408-.316");
}

.n5u_3996t {
  stop-color: var(--svg-color--e1ab9e, #E1AB9E);
}

.n7c5lw_4k {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
  stop-opacity: 0;
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.nioxf_ges {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M13.963 6.767v-.001l.003-.002l.005-.004l.067-.047q.066-.043.183-.091c.156-.062.379-.112.649-.069a.232.232 0 1 1-.073.458a.77.77 0 0 0-.512.096l-.024.016l-.004.002a.232.232 0 0 1-.295-.358");
}

.nxhf2dq-t {
  stop-color: var(--svg-color--3fa1f0, #3FA1F0);
  stop-opacity: 0;
}

.o-nc8gboa {
  d: path("m17.327 5.504l-1.338.446a.455.455 0 0 0 .204.884l1.33-.178z");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ol6g7lb1q {
  cx: 17.903px;
  cy: 16.215px;
  r: 0.313px;
}

.olwuq14vq {
  stop-color: var(--svg-color--499ee2, #499EE2);
}

.omhpq8bny {
  stop-color: var(--svg-color--d93d03, #D93D03);
}

.oxm2fc9jy {
  stop-color: var(--svg-color--40b1ff, #40B1FF);
  stop-opacity: 0;
}

.oyt5f2bkb {
  d: path("M19.591 3.594h2.226v2.004h-2.226z");
}

.p7jmmxb2h {
  stop-color: var(--svg-color--d7a09d, #D7A09D);
  stop-opacity: 0;
}

.p99znfbzx {
  stop-color: var(--svg-color--cf979c, #CF979C);
  stop-opacity: 0;
}

.pa-xpmw0g {
  stop-color: var(--svg-color--ddad9b, #DDAD9B);
}

.pb7i5tbeh {
  stop-color: var(--svg-color--346dd8, #346DD8);
}

.phi9sxixy {
  stop-color: var(--svg-color--3779d3, #3779D3);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.px4pa2bzd {
  stop-color: var(--svg-color--be8474, #BE8474);
}

.q9y6v7blv {
  stop-color: var(--svg-color--2f82e6, #2F82E6);
  stop-opacity: 0;
}

.qb120pbsb {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
  stop-opacity: 0;
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qg9ghcbvt {
  stop-color: var(--svg-color--42aff6, #42AFF6);
}

.qkeppfmvx {
  stop-color: var(--svg-color--ded7f4, #DED7F4);
}

.qmtvrbb-m {
  d: path("M16.523 7.528c.028.037-.03.082-.096.13c-.065.05-.114.085-.142.048s.003-.107.07-.156c.065-.05.14-.06.168-.022");
}

.qv6zwkcgg {
  stop-color: var(--svg-color--c58f7e, #C58F7E);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r3t82tbzk {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
  stop-opacity: 0;
}

.r5qf2jd1a {
  stop-color: var(--svg-color--f4cbb8, #F4CBB8);
}

.rcasxucso {
  stop-color: var(--svg-color--349fe1, #349FE1);
  stop-opacity: 0;
}

.rcuz4uefu {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
  stop-opacity: 0;
}

.rj_fg2b_y {
  cx: 13.539px;
  cy: 7.95px;
  r: 0.726px;
}

.rlzetx3ey {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
}

.rvf3-0bfj {
  stop-color: var(--svg-color--dead9d, #DEAD9D);
  stop-opacity: 0;
}

.s3rc45b6k {
  stop-color: var(--svg-color--3197dd, #3197DD);
  stop-opacity: 0;
}

.s5iez-b2n {
  fill: var(--svg-color--ff9457, #FF9457);
  d: path("M18.577 10.89c-.23-.26-.686-.706-1.229-1.003h-.617l.316 1.39c.273-.042.976-.12 1.441-.172c.11-.013.162-.13.089-.214");
}

.sbbw_6vcc {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
}

.sh-1wjb0z {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M15.604 9.31a1.3 1.3 0 0 1-.603-.142c-.06-.03-.123.036-.086.09c.146.221.4.368.689.368a.82.82 0 0 0 .688-.368c.037-.056-.027-.12-.086-.09a1.3 1.3 0 0 1-.602.142");
}

.su2ao5zll {
  d: path("m19.434 5.153l-.077 1.385a.1.1 0 0 0 .09.105l2.64.277a.3.3 0 0 0 .316-.391l-.464-1.42a.15.15 0 0 0-.14-.103l-2.161-.041a.2.2 0 0 0-.204.188");
}

.t6xzzwb_a {
  fill: var(--svg-color--fbc4b1, #FBC4B1);
  d: path("m15.438 7.826l-.232.739a.234.234 0 0 0 .227.304h.342c.16 0 .273-.155.226-.304l-.231-.74c-.05-.163-.28-.163-.332 0");
}

.tcm98nmkx {
  stop-color: var(--svg-color--42aff6, #42AFF6);
  stop-opacity: 0;
}

.tlfmt020n {
  stop-color: var(--svg-color--e3ac94, #E3AC94);
}

.tp3-xrbff {
  stop-color: var(--svg-color--3197dd, #3197DD);
}

.tqgh1edwg {
  stop-color: var(--svg-color--eaab97, #EAAB97);
}

.u2-6tpbfe {
  stop-color: var(--svg-color--d8cdf0, #D8CDF0);
}

.u7-t_bctv {
  fill: var(--svg-color--242324, #242324);
  d: path("m17.699 5.133l.186.093a.855.855 0 0 1 .443.928l-.256 1.321c-.023.137-.113.229-.249.232h-.008s.024-.394.047-.626c.019-.188-.014-.246-.186-.417a.55.55 0 0 1-.164-.371v-.371a.25.25 0 0 0-.186-.232a7 7 0 0 0-1.703-.186c-.84 0-1.422.116-1.702.186a.226.226 0 0 0-.187.232v.37a.46.46 0 0 1-.163.372l-.07.07c-.093.069-.14.208-.14.324c.023.255.047.626.047.626h-.021a.275.275 0 0 1-.259-.232l-.257-1.322a.89.89 0 0 1 .467-.904l.186-.093c.117-.07.234-.162.35-.255l.42-.44a.85.85 0 0 1 .956-.14c.233.07.49.07.723 0c.35-.115.746-.023 1.026.233l.35.347c.093.116.21.186.35.255");
}

.u8aws4lgo {
  stop-color: var(--svg-color--ff8337, #FF8337);
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.ukq_x9bby {
  cx: 14.536px;
  cy: 7.611px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.169px;
  ry: 0.086px;
}

.unfdbqymh {
  stop-color: var(--svg-color--f2c4b3, #F2C4B3);
  stop-opacity: 0;
}

.uph8jub-u {
  width: 0.62px;
  height: 1.395px;
  x: 20.578px;
  y: 2.871px;
  fill: var(--svg-color--e8b8a2, #E8B8A2);
  rx: 0.31px;
}

.uzkpn5btf {
  stop-color: var(--svg-color--b07f87, #B07F87);
}

.v_1-k8b0k {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.642 7.328c.284 0 .523.195.589.46a.12.12 0 0 1-.117.148h-.97a.1.1 0 0 1-.098-.118c.054-.279.3-.49.596-.49");
}

.v_yd_iblu {
  d: path("M16.552 7.446a.388.388 0 0 1 .374.49h-.75a.39.39 0 0 1 .376-.49");
}

.v3ajz9bsa {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M13.633 5.858v.39c-.003.065-.03.21-.112.27");
}

.vm6ce_jmk {
  d: path("M12.766 21.523c.217-.748.766-3.252 1.031-4.414l.422.18h4.684c-.816 2.398-2.664 3.657-4.004 5.875c-.409.677-.914 1.43-1.352 2.438c-.37.853-1.054 2.326-1.516 3.324a.574.574 0 0 1-.625.33c-1.533-.293-2.385-.943-3.014-1.765a.49.49 0 0 1-.012-.598c.72-.969 2.73-2.974 3.34-3.569c.675-.66.796-.937 1.046-1.8");
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.vqp8gziqg {
  d: path("M18.399 29.863V27.46h1.727l1.64.844c.5.404 1.212.712 1.715.904a.445.445 0 0 1 .265.565a.44.44 0 0 1-.412.288h-2.652a.26.26 0 0 1-.224-.123l-.424-.678a.141.141 0 0 0-.26.075v.625a.1.1 0 0 1-.102.102h-1.073a.2.2 0 0 1-.2-.2");
}

.vuihc-bcj {
  d: path("M21.438 20.164c-.824-.753-1.943-2.294-2.594-3.11l-2.258 2.97c1.874 1.219 2.775 1.939 3.346 2.404a.39.39 0 0 1 .111.463a55 55 0 0 1-1.011 2.03c-.439.853-.938 1.86-1.186 2.565a.5.5 0 0 0 .157.559c.28.22.74.51 1.447.744c.745.246 1.602.178 2.092.075a.43.43 0 0 0 .33-.36c.272-1.551.707-4.215.812-4.742c.09-.45.188-1.117 0-1.75c-.187-.633-.52-1.184-1.246-1.848");
}

.vxv2m-bqm {
  stop-color: var(--svg-color--48454b, #48454B);
}

.vyopt_bxu {
  stop-color: var(--svg-color--ff9a58, #FF9A58);
}

.w30s_lbtj {
  stop-color: var(--svg-color--4ab6fb, #4AB6FB);
  stop-opacity: 0;
}

.wachewblq {
  stop-color: var(--svg-color--ba7c6b, #BA7C6B);
}

.wbm6gtb2b {
  stop-color: var(--svg-color--3fb1fe, #3FB1FE);
}

.wdqn7tq-u {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
}

.wsr-x9y-q {
  stop-color: var(--svg-color--4195ec, #4195EC);
}

.x6-zvqbsc {
  stop-color: var(--svg-color--d93d03, #D93D03);
  stop-opacity: 0;
}

.x6mjr8bji {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
  stop-opacity: 0;
}

.x8d9utbsu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
  stop-opacity: 0;
}

.y3iq9j8og {
  stop-color: var(--svg-color--3779d3, #3779D3);
  stop-opacity: 0;
}

.y6-1-fjof {
  stop-color: var(--svg-color--d3a08f, #D3A08F);
}

.y8kcl1bix {
  stop-color: var(--svg-color--48454b, #48454B);
  stop-opacity: 0;
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.yh2psxb-p {
  stop-color: var(--svg-color--4081dd, #4081DD);
}

.yqnsa3b2w {
  d: path("m11.099 14.352l-2.586.139a.3.3 0 0 0-.252.434l.668 1.334a.15.15 0 0 0 .156.08l2.173-.318a.15.15 0 0 0 .128-.163l-.13-1.37a.15.15 0 0 0-.157-.136");
}

.yyvs3obha {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
  stop-opacity: 0;
}

.z3n_1mwef {
  stop-color: var(--svg-color--a58787, #A58787);
}

.z5ewkjg-x {
  d: path("m14.25 9.83l-4.215 1.199a1.95 1.95 0 0 0-.937.595l1.958 1.623l-.001-.013l3.852-1.095z");
}

.z8y6fgvmn {
  stop-color: var(--svg-color--ffdabf, #FFDABF);
}

.zc6yl0bhp {
  stop-color: var(--svg-color--d49c84, #D49C84);
  stop-opacity: 0;
}

.zf2atv-8x {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
  stop-opacity: 0;
}

.zkcw-qija {
  stop-color: var(--svg-color--2688ed, #2688ED);
  stop-opacity: 0;
}

</style>
