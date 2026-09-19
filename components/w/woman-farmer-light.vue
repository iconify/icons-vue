<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i24nLMb)" class="bi735-8gp"/><path fill="url(#inOg6Qc)" class="e5itq2e9v"/><path fill="url(#iBYetHb)" class="e5itq2e9v"/><g filter="url(#i4SYBJK)"><path fill="url(#iCnjJxe)" class="f7k54pbsz"/><path fill="url(#i66qVUc)" class="f7k54pbsz"/><path fill="url(#itCIv7i)" class="f7k54pbsz"/></g><g filter="url(#ijtRSzd)"><path fill="url(#ignS2Wc)" class="ivsq875yj"/><path fill="url(#iE3807b)" class="ivsq875yj"/></g><g filter="url(#iUiWpqe)"><path fill="url(#ikMFXNF)" class="v3q9_hbbs"/><path fill="url(#i8k9CUb)" class="v3q9_hbbs"/><path fill="url(#iJkoQBq)" class="v3q9_hbbs"/></g><path class="p5m7l5lux"/><path fill="url(#iaWPHxc)" class="sa4iv-boa"/><path fill="url(#i7ICm8d)" class="q3_rwp8df"/><path fill="url(#iefZh9c)" class="q3_rwp8df"/><path fill="url(#inhUu0b)" class="fep1h1smi"/><path fill="url(#ij6KKbd)" class="fep1h1smi"/><g filter="url(#i2EGzJd)"><path fill="url(#im6NVub)" class="ez9pkcbii"/><path fill="url(#idQxERx)" class="ez9pkcbii"/><path fill="url(#iLmxzNe)" class="ez9pkcbii"/></g><path fill="url(#ivJCMOb)" class="ez9pkcbii"/><path fill="url(#iv1O2Bd)" class="ez9pkcbii"/><path fill="url(#ijI3wne)" class="vryawy-6e"/><path fill="url(#iKTaTZc)" class="ruump_bfn"/><path fill="url(#iUuDaHd)" class="ruump_bfn"/><path fill="url(#iPoH8Dg)" class="k28lh7wur"/><path fill="url(#iaVwZxc)" class="k28lh7wur"/><path fill="url(#iicLAvV)" class="k28lh7wur"/><path fill="url(#irUV7Me)" class="k28lh7wur"/><path fill="url(#ifXHzbc)" class="k28lh7wur"/><g filter="url(#iXDnjEe)"><path class="pujrc2bni"/></g><g filter="url(#iWP3gRb)"><path fill="url(#iHQrAGc)" class="c-9i3f-ld"/></g><path fill="url(#iydkw3i)" class="ykhy9yb4g"/><path fill="url(#iqyrmFc)" class="ykhy9yb4g"/><path fill="url(#i3NRnUb)" class="c1y_kibti"/><path fill="url(#iDvCpnc)" class="c1y_kibti"/><path fill="url(#iEFhnTc)" class="kqdmkkpda"/><path fill="url(#i0vKEJF)" class="kqdmkkpda"/><path fill="url(#i6CfYud)" class="kqdmkkpda"/><g filter="url(#ikyritd)"><path fill="url(#i9LtDUc)" class="nky_yfblw"/><path fill="url(#iQLYFFc)" class="nky_yfblw"/><path fill="url(#ie3YMEc)" class="nky_yfblw"/><path fill="url(#iIA2QMd)" class="nky_yfblw"/><path fill="url(#iihiuhe)" class="nky_yfblw"/></g><g filter="url(#iG0yiJb)"><path stroke="url(#iAKHBYc)" class="l92vtzblj"/></g><g filter="url(#i6W76rb)"><path stroke="url(#ipQSXxc)" class="dfxbm7b6s"/></g><g filter="url(#iRdsvSX)"><path stroke="url(#iVqGnqd)" class="xdi9wqbra"/></g><g filter="url(#iBKI0rs)"><path class="wruv5824x"/><path fill="url(#iiWtd3s)" class="k-27-rbxs"/></g><path fill="url(#iESrOte)" class="txm18jrit"/><path fill="url(#i21TgJN)" class="txm18jrit"/><g filter="url(#i3o2Zme)"><path fill="url(#iVPUvFb)" class="z6plkxa1j"/></g><g filter="url(#i6SbRpc)"><path fill="url(#iaypDIX)" class="ad2jkibtc"/></g><g filter="url(#iE0GFFb)"><path fill="url(#ivBGRQB)" class="eep3opbgb"/></g><path fill="url(#iEHVcFc)" class="turl0o68q"/><path fill="url(#iIeJJSd)" class="turl0o68q"/><path fill="url(#iND1CNc)" class="turl0o68q"/><path fill="url(#is6DkfF)" class="turl0o68q"/><g filter="url(#inx4ZYc)"><path stroke="url(#ifBZUce)" class="qok44-bhf"/></g><path fill="url(#iEKSYGd)" class="nyysd-7fx"/><g filter="url(#iOAaNvb)"><path class="v93svlujl"/></g><g filter="url(#inm9Kfc)"><path class="dsu9l31wr"/><path fill="url(#i8Iwzwb)" class="pk0ymrp0a"/><path fill="url(#ihHABib)" class="pk0ymrp0a"/><path fill="url(#i7r4zre)" class="pk0ymrp0a"/><path fill="url(#i77BMre)" class="pk0ymrp0a"/><path fill="url(#iLWB1Ne)" class="pk0ymrp0a"/></g><g filter="url(#iHp2cxu)"><path class="mnidd95nq"/></g><g filter="url(#ipI7zHb)"><path class="cp_0q9b1n"/></g><g filter="url(#iH5iaNV)"><path class="wvv92-bqk"/></g><g filter="url(#ieWwnib)"><path class="a1i9c3b7d"/></g><path class="jlef8suqq"/><path fill="url(#iLfMgTI)" class="sjjzhrr4a"/><path class="vwhs-0blc"/><g filter="url(#iJ7rrKS)"><path class="yv6vzebbo"/><path fill="url(#iF3hAyd)" class="f-vrcnbpj"/></g><g filter="url(#iQUgYXs)"><path fill="url(#imlSLid)" class="tzunxobuv"/></g><path class="n6tp2sy4o"/><path fill="url(#i3bwrGc)" class="vi4mtz2pd"/><path class="owu6h_2xv"/><g filter="url(#i3E6NOe)"><path fill="url(#icc5ihd)" class="hzmh33hrd"/></g><g filter="url(#ikKTbde)"><ellipse transform="rotate(-27.914 13.65 10.008)" class="tfz5b9oyk"/><ellipse fill="url(#i7vCU7b)" transform="rotate(-27.914 13.65 10.008)" class="xx3sv-b8t"/></g><g filter="url(#ibuua6b)"><path class="zonfpmhlw"/></g><g filter="url(#ipH9rbc)"><path class="ezb71f64k"/></g><g filter="url(#i6tOQFd)"><path fill="url(#iwgYnhc)" class="e6e1ymbml"/></g><g filter="url(#izLxNAd)"><path class="mbpkcyklt"/></g><defs><radialGradient id="i24nLMb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.28126 -2.7131 2.52682 -3.98732 19.857 3.96)" gradientUnits="userSpaceOnUse"><stop class="lgo9yub8v"/><stop offset="1" class="ltcbfxk7p"/></radialGradient><radialGradient id="inOg6Qc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.15625 8.40625 0 19.732 5.122)" gradientUnits="userSpaceOnUse"><stop class="ya4lejb1r"/><stop offset="1" class="r9exlwbyv"/></radialGradient><radialGradient id="i66qVUc" cx="0" cy="0" r="1" gradientTransform="rotate(-115.388 9.63 3.904)scale(4.08169 6.42739)" gradientUnits="userSpaceOnUse"><stop class="yc_s6bd2r"/><stop offset="1" class="e2_jykbzy"/></radialGradient><radialGradient id="itCIv7i" cx="0" cy="0" r="1" gradientTransform="matrix(6.90227 -3.56704 2.32702 4.50282 16.04 10.135)" gradientUnits="userSpaceOnUse"><stop offset=".209" class="s0qpik8kr"/><stop offset="1" class="y2pqqr5ks"/></radialGradient><radialGradient id="ignS2Wc" cx="0" cy="0" r="1" gradientTransform="matrix(1.65625 -6.4375 7.87502 2.0261 19.535 16.372)" gradientUnits="userSpaceOnUse"><stop class="vz8fcrkfe"/><stop offset="1" class="rbuuvqb-n"/></radialGradient><radialGradient id="iE3807b" cx="0" cy="0" r="1" gradientTransform="matrix(2.76563 -.5625 .27296 1.34206 22.097 11.145)" gradientUnits="userSpaceOnUse"><stop offset=".203" class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><radialGradient id="i8k9CUb" cx="0" cy="0" r="1" gradientTransform="rotate(106.741 2.027 7.443)scale(6.18397 1.94761)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="qxarokbzg"/><stop offset="1" class="jn8004cwc"/></radialGradient><radialGradient id="iJkoQBq" cx="0" cy="0" r="1" gradientTransform="rotate(-46.106 17.016 -8.635)scale(2.86211 1.6392)" gradientUnits="userSpaceOnUse"><stop class="cwohembfi"/><stop offset="1" class="ml-iambtc"/></radialGradient><radialGradient id="iaWPHxc" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.16424 -8.99366 0 15.969 16.285)" gradientUnits="userSpaceOnUse"><stop offset=".53" class="oolzzy49q"/><stop offset="1" class="kc6n1tb_x"/></radialGradient><radialGradient id="iefZh9c" cx="0" cy="0" r="1" gradientTransform="matrix(2.6875 .4375 -2.13811 13.1341 3.826 25.247)" gradientUnits="userSpaceOnUse"><stop class="d6r03hc-n"/><stop offset="1" class="h29l8x_8c"/></radialGradient><radialGradient id="ij6KKbd" cx="0" cy="0" r="1" gradientTransform="matrix(.79488 -.01787 .1758 7.81887 23 24.71)" gradientUnits="userSpaceOnUse"><stop offset=".249" class="du4i2cruh"/><stop offset="1" class="a2gn4iuzk"/></radialGradient><radialGradient id="im6NVub" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.49005 -3.73669 0 16.039 16.153)" gradientUnits="userSpaceOnUse"><stop offset=".232" class="w6969eyte"/><stop offset="1" class="nb487cbvy"/></radialGradient><radialGradient id="iLmxzNe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.27543 1.55452 -.96733 -1.41593 15.184 19.551)" gradientUnits="userSpaceOnUse"><stop class="zif_-obqz"/><stop offset="1" class="j3eudux9e"/></radialGradient><radialGradient id="iv1O2Bd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.28924 -4.48731 0 15.432 15.97)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="rs3k7gc8p"/><stop offset=".987" class="zm4f_vbug"/></radialGradient><radialGradient id="ijI3wne" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.58005 5.35185 0 15.96 19.652)" gradientUnits="userSpaceOnUse"><stop offset=".027" class="h7qlxhb-a"/><stop offset=".737" class="wly33_qqy"/></radialGradient><radialGradient id="iKTaTZc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.87968 -1.90863 0 15.96 16.78)" gradientUnits="userSpaceOnUse"><stop class="s7aakmgnr"/><stop offset="1" class="l212nr2yp"/></radialGradient><radialGradient id="iUuDaHd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.50225 -2.55179 0 15.96 15.32)" gradientUnits="userSpaceOnUse"><stop offset=".691" class="az3jcdmty"/><stop offset=".944" class="z48shob3w"/></radialGradient><radialGradient id="iaVwZxc" cx="0" cy="0" r="1" gradientTransform="rotate(154.069 9.55 11.79)scale(3.78757 11.2112)" gradientUnits="userSpaceOnUse"><stop class="ium6abcxp"/><stop offset="1" class="h7lqrlw1r"/></radialGradient><radialGradient id="ifXHzbc" cx="0" cy="0" r="1" gradientTransform="matrix(2.5033 -1.90624 3.00378 3.94459 8.979 18.81)" gradientUnits="userSpaceOnUse"><stop class="g3ev-1bmq"/><stop offset="1" class="hdbb6nacd"/></radialGradient><radialGradient id="iydkw3i" cx="0" cy="0" r="1" gradientTransform="rotate(154.424 11.451 15.258)scale(2.44794 2.40172)" gradientUnits="userSpaceOnUse"><stop offset=".524" class="tj2vllbvr"/><stop offset=".956" class="fop80r8ws"/></radialGradient><radialGradient id="iqyrmFc" cx="0" cy="0" r="1" gradientTransform="matrix(.78818 -.60013 .4599 .60401 27.568 23.618)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="q7l79-2rh"/><stop offset="1" class="aszpk2bre"/></radialGradient><radialGradient id="iDvCpnc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.85126 .74829 0 26.152 24.77)" gradientUnits="userSpaceOnUse"><stop class="j2-8_acvh"/><stop offset="1" class="x6aj7b3cp"/></radialGradient><radialGradient id="iEFhnTc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.82813 1.14062 0 26.176 21.59)" gradientUnits="userSpaceOnUse"><stop class="ag_y78bhq"/><stop offset="1" class="r_2nh8m3w"/></radialGradient><radialGradient id="i0vKEJF" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.14844 2.01125 0 25.677 21.974)" gradientUnits="userSpaceOnUse"><stop offset=".76" class="isjnp_l6m"/><stop offset="1" class="y9bk_9fsc"/></radialGradient><radialGradient id="iQLYFFc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.93 25.285)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="ie3YMEc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.93 26.579)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="iIA2QMd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.93 27.829)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="iihiuhe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.93 29.18)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="iiWtd3s" cx="0" cy="0" r="1" gradientTransform="matrix(-.96352 -1.32485 1.2944 -.94137 11.634 12.364)" gradientUnits="userSpaceOnUse"><stop class="en-2vgkms"/><stop offset="1" class="vvdbjrbwx"/></radialGradient><radialGradient id="i21TgJN" cx="0" cy="0" r="1" gradientTransform="rotate(-51.009 23.63 -15.984)scale(1.62706)" gradientUnits="userSpaceOnUse"><stop class="guri77_rx"/><stop offset="1" class="jvouqxrlb"/></radialGradient><radialGradient id="iVPUvFb" cx="0" cy="0" r="1" gradientTransform="rotate(91.606 5.193 15.658)scale(1.02956)" gradientUnits="userSpaceOnUse"><stop class="f4dh4oqdr"/><stop offset=".912" class="uspdh30af"/></radialGradient><radialGradient id="iaypDIX" cx="0" cy="0" r="1" gradientTransform="matrix(-1.40683 0 0 -2.0812 11.525 11.086)" gradientUnits="userSpaceOnUse"><stop offset=".149" class="ebnsn321w"/><stop offset="1" class="quk3dgi1t"/></radialGradient><radialGradient id="ivBGRQB" cx="0" cy="0" r="1" gradientTransform="matrix(-5.875 2.63281 -4.19257 -9.35552 19.066 9.614)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="bo9hvcbia"/><stop offset="1" class="zgqoc8mjm"/></radialGradient><radialGradient id="iEHVcFc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.87488 -8.98026 0 16.047 7.75)" gradientUnits="userSpaceOnUse"><stop offset=".647" class="t11jy5bth"/><stop offset=".968" class="yds08u11w"/></radialGradient><radialGradient id="iIeJJSd" cx="0" cy="0" r="1" gradientTransform="matrix(1.39286 -.8314 .61148 1.02443 18.173 9.73)" gradientUnits="userSpaceOnUse"><stop class="lk1-k5bve"/><stop offset="1" class="syybhxbau"/></radialGradient><radialGradient id="iND1CNc" cx="0" cy="0" r="1" gradientTransform="rotate(-118.968 9.717 .712)scale(1.38223 1.08515)" gradientUnits="userSpaceOnUse"><stop class="nht4bcbod"/><stop offset="1" class="ywpvidbgc"/></radialGradient><radialGradient id="is6DkfF" cx="0" cy="0" r="1" gradientTransform="matrix(3.18521 -2.02335 .70369 1.10776 11.44 7.372)" gradientUnits="userSpaceOnUse"><stop offset=".274" class="b7govjavj"/><stop offset="1" class="gahamco-n"/></radialGradient><radialGradient id="iEKSYGd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.7506 2.95973 0 16.054 14.233)" gradientUnits="userSpaceOnUse"><stop class="hwx_eib-x"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="ihHABib" cx="0" cy="0" r="1" gradientTransform="matrix(0 .21614 -.73448 0 16.533 12.247)" gradientUnits="userSpaceOnUse"><stop class="t40345qox"/><stop offset="1" class="mrnsdcbqx"/></radialGradient><radialGradient id="i77BMre" cx="0" cy="0" r="1" gradientTransform="rotate(157.021 7.129 7.563)scale(1.58183 2.41168)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="o0aif1l1c"/><stop offset="1" class="vni43obah"/></radialGradient><radialGradient id="iLfMgTI" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.184 10.104)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iF3hAyd" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.473 .697)scale(.37798 .52039)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i3bwrGc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.92 10.104)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i7vCU7b" cx="0" cy="0" r="1" gradientTransform="matrix(-.00773 -.49366 .5934 -.0093 13.634 10.323)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="i4SYBJK" width="20.537" height="10.328" x="5.52" y="4.81" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.384314 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1814"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.243137 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1814" result="effect2_innerShadow_4002_1814"/></filter><filter id="ijtRSzd" width="9.49" height="10.956" x="14.074" y="6.815" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0666667 0 0 0 0 0.0156863 0 0 0 0 0.0431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1814"/></filter><filter id="iUiWpqe" width="6.144" height="10.985" x="8.614" y="6.746" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.164706 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1814"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.239216 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1814" result="effect2_innerShadow_4002_1814"/></filter><filter id="i2EGzJd" width="8" height="6.44" x="12.039" y="15.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.47451 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1814"/></filter><filter id="iXDnjEe" width="8.45" height="4.612" x="11.769" y="25.56" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1814" stdDeviation=".125"/></filter><filter id="iWP3gRb" width="8.05" height="4.28" x="11.919" y="25.81" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.67451 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1814"/></filter><filter id="ikyritd" width="4.468" height="5.556" x="23.493" y="24.424" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.509804 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1814"/></filter><filter id="iG0yiJb" width="2.097" height=".3" x="23.864" y="25.808" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1814" stdDeviation=".05"/></filter><filter id="i6W76rb" width="2.097" height=".3" x="23.785" y="27.113" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1814" stdDeviation=".05"/></filter><filter id="iRdsvSX" width="2.097" height=".3" x="23.951" y="28.324" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1814" stdDeviation=".05"/></filter><filter id="iBKI0rs" width="3.318" height="3.218" x="9.687" y="9.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.643137 0 0 0 0 0.568627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1814"/></filter><filter id="i3o2Zme" width="2.648" height="2.648" x="19.502" y="9.582" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1814" stdDeviation=".125"/></filter><filter id="i6SbRpc" width="2.648" height="2.648" x="9.991" y="9.582" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1814" stdDeviation=".125"/></filter><filter id="iE0GFFb" width="10.425" height="9.709" x="11.135" y="6.915" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.890196 0 0 0 0 0.67451 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1814"/></filter><filter id="inx4ZYc" width="3.685" height="1.517" x="14.212" y="13.004" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1814" stdDeviation=".05"/></filter><filter id="iOAaNvb" width="3.797" height="4.568" x="13.961" y="9.365" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1814" stdDeviation=".5"/></filter><filter id="inm9Kfc" width="2.197" height="2.968" x="14.988" y="9.939" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1814" stdDeviation=".1"/></filter><filter id="iHp2cxu" width="2.247" height="1.019" x="12.288" y="7.857" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0823529 0 0 0 0 0.0980392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1814"/></filter><filter id="ipI7zHb" width="2.237" height="1.009" x="17.614" y="7.866" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0823529 0 0 0 0 0.0980392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1814"/></filter><filter id="iH5iaNV" width="3.001" height="1.285" x="17.144" y="9.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1814"/></filter><filter id="ieWwnib" width="3.001" height="1.285" x="12.16" y="9.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1814"/></filter><filter id="iJ7rrKS" width=".786" height=".696" x="17.45" y="9.665" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1814" stdDeviation=".05"/></filter><filter id="iQUgYXs" width=".891" height=".913" x="18.29" y="9.739" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1814" stdDeviation=".1"/></filter><filter id="i3E6NOe" width=".986" height="1.04" x="13.948" y="9.676" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1814" stdDeviation=".1"/></filter><filter id="ikKTbde" width=".912" height=".704" x="13.193" y="9.656" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1814" stdDeviation=".05"/></filter><filter id="ibuua6b" width="2.132" height=".75" x="17.7" y="8.022" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1814" stdDeviation=".075"/></filter><filter id="ipH9rbc" width="2.132" height=".75" x="12.341" y="8.022" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1814" stdDeviation=".075"/></filter><filter id="i6tOQFd" width="5.819" height=".998" x="15.478" y="6.846" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1814" stdDeviation=".075"/></filter><filter id="izLxNAd" width="7.625" height="9.853" x="21.892" y="10.644" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.470588 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1814"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.776471 0 0 0 0 0.796078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1814" result="effect2_innerShadow_4002_1814"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.517647 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1814" result="effect3_innerShadow_4002_1814"/></filter><linearGradient id="iBYetHb" x1="15.959" x2="15.959" y1="4.01" y2="4.063" gradientUnits="userSpaceOnUse"><stop class="xjz9wom2l"/><stop offset="1" class="pqe0dnzfz"/></linearGradient><linearGradient id="iCnjJxe" x1="16.039" x2="16.039" y1="4.81" y2="14.841" gradientUnits="userSpaceOnUse"><stop class="do1aj8bav"/><stop offset=".842" class="w-37x5bhe"/></linearGradient><linearGradient id="ikMFXNF" x1="11.561" x2="11.561" y1="6.996" y2="17.731" gradientUnits="userSpaceOnUse"><stop class="x5dyrqz_l"/><stop offset="1" class="xuadj21pj"/></linearGradient><linearGradient id="i7ICm8d" x1="8.979" x2="5.389" y1="28.434" y2="28.434" gradientUnits="userSpaceOnUse"><stop class="rhalidc9f"/><stop offset="1" class="wevrdub6o"/></linearGradient><linearGradient id="inhUu0b" x1="26.542" x2="22.999" y1="22.864" y2="29.17" gradientUnits="userSpaceOnUse"><stop class="kcb1h97-p"/><stop offset="1" class="c6jm60b1r"/></linearGradient><linearGradient id="idQxERx" x1="20.039" x2="19.104" y1="18.497" y2="18.497" gradientUnits="userSpaceOnUse"><stop class="lzh17ac1w"/><stop offset="1" class="yrr42qhfr"/></linearGradient><linearGradient id="ivJCMOb" x1="12.039" x2="12.373" y1="18.497" y2="18.497" gradientUnits="userSpaceOnUse"><stop offset=".143" class="pescu9bef"/><stop offset="1" class="fl69hubql"/></linearGradient><linearGradient id="iPoH8Dg" x1="17.201" x2="15.254" y1="29.122" y2="19.958" gradientUnits="userSpaceOnUse"><stop class="ym265mvaz"/><stop offset="1" class="k0c3dfbas"/></linearGradient><linearGradient id="iicLAvV" x1="23.053" x2="22.826" y1="29.653" y2="29.653" gradientUnits="userSpaceOnUse"><stop class="zjnvspbhz"/><stop offset="1" class="mo7a9nshu"/></linearGradient><linearGradient id="irUV7Me" x1="8.979" x2="9.103" y1="29.653" y2="29.653" gradientUnits="userSpaceOnUse"><stop class="zjnvspbhz"/><stop offset="1" class="mo7a9nshu"/></linearGradient><linearGradient id="iHQrAGc" x1="13.826" x2="20.357" y1="28.341" y2="28.341" gradientUnits="userSpaceOnUse"><stop class="tbsuik4az"/><stop offset="1" class="mkeehnh5k"/></linearGradient><linearGradient id="i3NRnUb" x1="25.649" x2="25.649" y1="21.591" y2="24.77" gradientUnits="userSpaceOnUse"><stop class="rl_kfsb7q"/><stop offset=".997" class="va-kb9bvg"/></linearGradient><linearGradient id="i6CfYud" x1="25.677" x2="25.677" y1="22.294" y2="21.7" gradientUnits="userSpaceOnUse"><stop class="lmnxagbed"/><stop offset="1" class="ztn8dybrr"/></linearGradient><linearGradient id="i9LtDUc" x1="27.521" x2="23.493" y1="28.043" y2="28.043" gradientUnits="userSpaceOnUse"><stop offset=".146" class="v5rheyc4i"/><stop offset=".861" class="j1qr75obr"/></linearGradient><linearGradient id="iAKHBYc" x1="24.014" x2="25.723" y1="26.036" y2="26.036" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="ipQSXxc" x1="23.936" x2="25.645" y1="27.341" y2="27.341" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="iVqGnqd" x1="24.101" x2="25.81" y1="28.552" y2="28.552" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="iESrOte" x1="21.891" x2="20.826" y1="10.106" y2="12.515" gradientUnits="userSpaceOnUse"><stop class="vgzo13b2o"/><stop offset="1" class="ccj7rwekm"/></linearGradient><linearGradient id="ifBZUce" x1="14.828" x2="15.164" y1="14.073" y2="13.208" gradientUnits="userSpaceOnUse"><stop class="i4xwdrbot"/><stop offset="1" class="a2_5cmbky"/></linearGradient><linearGradient id="i8Iwzwb" x1="16.889" x2="16.087" y1="11.639" y2="11.675" gradientUnits="userSpaceOnUse"><stop offset=".36" class="af2d-kbww"/><stop offset="1" class="fkbu2fb2z"/></linearGradient><linearGradient id="i7r4zre" x1="16.087" x2="16.087" y1="12.648" y2="12.236" gradientUnits="userSpaceOnUse"><stop class="y8u9aob3m"/><stop offset="1" class="w22vs7beb"/></linearGradient><linearGradient id="iLWB1Ne" x1="16.087" x2="16.087" y1="10.139" y2="10.737" gradientUnits="userSpaceOnUse"><stop class="au2s26bkj"/><stop offset="1" class="e0f0u6bhi"/></linearGradient><linearGradient id="imlSLid" x1="18.962" x2="18.648" y1="10.158" y2="10.351" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="icc5ihd" x1="14.664" x2="14.351" y1="10.158" y2="10.351" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iwgYnhc" x1="19.284" x2="16.159" y1="6.996" y2="8.543" gradientUnits="userSpaceOnUse"><stop class="urzuj9che"/><stop offset="1" class="ev34ly_6u"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-farmer-light" /></template>
<style>
.a1i9c3b7d {
  fill: var(--svg-color--1d1b1f, #1D1B1F);
  d: path("M14.961 10.132c-.265-.466-.669-.835-1.537-.835c-.38 0-.747.105-1.073.369c-.269.217-.233.495-.025.599l.556.317c.652-.21 1.373-.239 2.079-.45");
}

.a2_5cmbky {
  stop-color: var(--svg-color--dfaca3, #DFACA3);
  stop-opacity: 0;
}

.a2gn4iuzk {
  stop-color: var(--svg-color--28a96b, #28A96B);
  stop-opacity: 0;
}

.ad2jkibtc {
  d: path("M11.315 11.98a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.af2d-kbww {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
}

.ag_y78bhq {
  stop-color: var(--svg-color--c7c1cc, #C7C1CC);
}

.aszpk2bre {
  stop-color: var(--svg-color--f7ceb9, #F7CEB9);
  stop-opacity: 0;
}

.au2s26bkj {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
}

.az3jcdmty {
  stop-color: var(--svg-color--906549, #906549);
  stop-opacity: 0;
}

.b570nlb5r {
  stop-color: var(--svg-color--ffd1bb, #FFD1BB);
  stop-opacity: 0;
}

.b7govjavj {
  stop-color: var(--svg-color--b17c69, #B17C69);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bi735-8gp {
  d: path("M21.959 5.91h-12l.18-.36a6.549 6.549 0 0 1 11.65.03z");
}

.bo9hvcbia {
  stop-color: var(--svg-color--ffd6bb, #FFD6BB);
}

.c-9i3f-ld {
  d: path("M19.46 25.81h-6.94c-.28 0-.5.22-.5.5v3.68h7.95v-3.68a.517.517 0 0 0-.51-.5");
}

.c1y_kibti {
  d: path("M26.152 21.77h-1v3h1z");
}

.c6jm60b1r {
  stop-color: var(--svg-color--368d6e, #368D6E);
}

.ccj7rwekm {
  stop-color: var(--svg-color--e9b69f, #E9B69F);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cp_0q9b1n {
  fill: var(--svg-color--130e18, #130E18);
  d: path("M19.593 8.875a.24.24 0 0 1-.135-.038c-.01 0-.732-.414-1.53-.26a.26.26 0 0 1-.309-.212a.26.26 0 0 1 .212-.308c.991-.183 1.858.308 1.887.327a.27.27 0 0 1 .096.366a.24.24 0 0 1-.221.125");
}

.cwohembfi {
  stop-color: var(--svg-color--040102, #040102);
}

.d6r03hc-n {
  stop-color: var(--svg-color--63c890, #63C890);
}

.dfxbm7b6s {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.936 27.263h1.796");
}

.do1aj8bav {
  stop-color: var(--svg-color--6e4648, #6E4648);
}

.dsu9l31wr {
  fill: var(--svg-color--f6bfab, #F6BFAB);
  d: path("m15.713 10.406l-.5 1.627a.518.518 0 0 0 .5.674h.751a.526.526 0 0 0 .5-.674l-.5-1.627c-.135-.356-.645-.356-.75 0");
}

.du4i2cruh {
  stop-color: var(--svg-color--2aaa64, #2AAA64);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e0f0u6bhi {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
  stop-opacity: 0;
}

.e2_jykbzy {
  stop-color: var(--svg-color--6e4f4b, #6E4F4B);
  stop-opacity: 0;
}

.e5itq2e9v {
  d: path("m10.139 5.55l-.18.36h12l-.17-.33c-.3-.59-.68-1.11-1.12-1.57h-9.42c-.43.45-.81.97-1.11 1.54");
}

.e6e1ymbml {
  d: path("M19.214 7.113c1.237.056 1.561.238 1.933.453c-.31-.15-1.346-.375-2.777-.062c-1.431.312-2.425.172-2.742.062l.14-.57c1.5.453 1.899.047 3.446.117");
}

.ebnsn321w {
  stop-color: var(--svg-color--c68976, #C68976);
}

.eep3opbgb {
  d: path("M19.383 7.998h-2.619c-1.38 0-2.044-.559-2.628-1.083c0 0-.927.042-1.259.101c-.215.234-.443.53-.977.886c-.23.116-.756.527-.765 1.46l.063 2.594c.106 2.801 2.262 4.669 4.88 4.669c2.62 0 4.766-1.868 4.881-4.67V9.454c0-1.34-1.393-1.455-1.576-1.455");
}

.en-2vgkms {
  stop-color: var(--svg-color--d09480, #D09480);
}

.ev34ly_6u {
  stop-color: var(--svg-color--4c4649, #4C4649);
  stop-opacity: 0;
}

.ez9pkcbii {
  d: path("m13.003 21.473l3.036-2.123l2.987 2.084c.421.325 1.013.465 1.013-.354v-4.81c-1.24-.48-2.59-.77-4-.77s-2.76.24-4 .72v4.69c0 .954.594.823.964.563");
}

.ezb71f64k {
  stroke: var(--svg-color--545154, #545154);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.274 8.26c-.237-.1-1.325 0-1.732.312");
}

.f-vrcnbpj {
  d: path("M18.12 9.816c.063.085-.07.189-.22.302c-.151.113-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.05");
}

.f4dh4oqdr {
  stop-color: var(--svg-color--efbba2, #EFBBA2);
}

.f7k54pbsz {
  d: path("M11.603 4.81c-.85.03-2.678.228-4.102 1.336c-1.238.962-1.477 2.117-1.477 3.085v.477c-.093 1.781 1.446 4.93 6.883 4.93h6.264c5.437 0 6.976-3.149 6.883-4.93v-.477c0-.968-.24-2.123-1.477-3.085c-1.423-1.108-3.252-1.305-4.101-1.336z");
}

.fep1h1smi {
  d: path("M23 29.98V18.01h.006a10.95 10.95 0 0 1 3.993 8.47v2.5a1 1 0 0 1-1 1z");
}

.fkbu2fb2z {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
  stop-opacity: 0;
}

.fl69hubql {
  stop-color: var(--svg-color--6a9e7e, #6A9E7E);
  stop-opacity: 0;
}

.fop80r8ws {
  stop-color: var(--svg-color--c79175, #C79175);
}

.ft5dv1b6b {
  fill: none;
}

.g3ev-1bmq {
  stop-color: var(--svg-color--3da0db, #3DA0DB);
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.gahamco-n {
  stop-color: var(--svg-color--b17c69, #B17C69);
  stop-opacity: 0;
}

.guri77_rx {
  stop-color: var(--svg-color--e4b39c, #E4B39C);
}

.h29l8x_8c {
  stop-color: var(--svg-color--63c890, #63C890);
  stop-opacity: 0;
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

.hwx_eib-x {
  stop-color: var(--svg-color--89024e, #89024E);
}

.hzmh33hrd {
  d: path("M14.734 10.414c0-.288-.235-.48-.298-.538l-.288.279l.177.36z");
}

.i4xwdrbot {
  stop-color: var(--svg-color--dfaca3, #DFACA3);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.isjnp_l6m {
  stop-color: var(--svg-color--85808c, #85808C);
  stop-opacity: 0;
}

.ium6abcxp {
  stop-color: var(--svg-color--47b2f6, #47B2F6);
}

.ivsq875yj {
  d: path("M16.875 8.013c-1.715 0-2.526-.732-2.801-1.098c.836.027 2.457 0 4.584 0c2.658 0 4.35 1.048 4.702 2.971c.257 1.647-.241 2.689-.12 3.172c.12.484.564 1.763-.282 3.012c-.677.999-2.108 1.55-2.74 1.701h-2.185v-1.853c2.367-.725 2.32-3 2.37-3.212s.422-1.94.297-3.337c-.096-1.072-.788-1.325-1.298-1.302c-.205 0-1.004-.054-2.527-.054");
}

.j1qr75obr {
  stop-color: var(--svg-color--d8a696, #D8A696);
}

.j2-8_acvh {
  stop-color: var(--svg-color--88625f, #88625F);
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j3eudux9e {
  stop-color: var(--svg-color--519473, #519473);
  stop-opacity: 0;
}

.jlef8suqq {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.393 9.355c.653 0 1.205.45 1.355 1.06a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.228-.272a1.4 1.4 0 0 1 1.371-1.128");
}

.jn8004cwc {
  stop-color: var(--svg-color--423735, #423735);
  stop-opacity: 0;
}

.jvouqxrlb {
  stop-color: var(--svg-color--e4b39c, #E4B39C);
  stop-opacity: 0;
}

.k-27-rbxs {
  d: path("M11.296 12.515a1.609 1.609 0 1 0 0-3.218a1.609 1.609 0 0 0 0 3.218");
}

.k0c3dfbas {
  stop-color: var(--svg-color--309edd, #309EDD);
}

.k28lh7wur {
  d: path("M22.999 18.04c-.63-.53-1.33-.99-2.07-1.36v5.9c0 .23-.18.41-.41.41h-9.07c-.23 0-.41-.18-.41-.41v-5.92c-.74.37-1.43.82-2.06 1.35v11.97h14.02z");
}

.kc6n1tb_x {
  stop-color: var(--svg-color--399967, #399967);
  stop-opacity: 0;
}

.kcb1h97-p {
  stop-color: var(--svg-color--63d591, #63D591);
}

.kqdmkkpda {
  d: path("M24.916 19.99h1.523v1.734a.25.25 0 0 1-.25.25h-1.023a.25.25 0 0 1-.25-.25z");
}

.l212nr2yp {
  stop-color: var(--svg-color--bb9282, #BB9282);
}

.l92vtzblj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.014 25.958h1.797");
}

.lgo9yub8v {
  stop-color: var(--svg-color--7f5f58, #7F5F58);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lk1-k5bve {
  stop-color: var(--svg-color--f3bda8, #F3BDA8);
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

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbpkcyklt {
  fill: var(--svg-color--c0b8c5, #C0B8C5);
  d: path("M22.794 11.044a.6.6 0 0 0-.602.601v6.852a1.5 1.5 0 0 0 1.5 1.5h4.125a1.5 1.5 0 0 0 1.5-1.5v-6.851a.602.602 0 1 0-1.203 0v4.449a.879.879 0 0 1-1.758 0v-4.45a.602.602 0 0 0-1.203 0v4.45a.879.879 0 0 1-1.758 0v-4.45a.6.6 0 0 0-.601-.601");
}

.mkeehnh5k {
  stop-color: var(--svg-color--319ce4, #319CE4);
}

.ml-iambtc {
  stop-color: var(--svg-color--040102, #040102);
  stop-opacity: 0;
}

.mnidd95nq {
  fill: var(--svg-color--130e18, #130E18);
  d: path("M12.556 8.875a.26.26 0 0 1-.231-.134a.27.27 0 0 1 .096-.366c.039-.02.895-.51 1.896-.327a.26.26 0 0 1 .212.308c-.029.154-.163.25-.308.221c-.809-.144-1.53.26-1.53.26a.24.24 0 0 1-.135.038");
}

.mo7a9nshu {
  stop-color: var(--svg-color--28659f, #28659F);
  stop-opacity: 0;
}

.mrnsdcbqx {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
  stop-opacity: 0;
}

.n6tp2sy4o {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.712 9.355c-.653 0-1.205.45-1.355 1.06c-.045.174.09.34.268.34h2.23a.23.23 0 0 0 .228-.272a1.4 1.4 0 0 0-1.371-1.128");
}

.nb487cbvy {
  stop-color: var(--svg-color--3d8f6c, #3D8F6C);
}

.nht4bcbod {
  stop-color: var(--svg-color--d39d91, #D39D91);
}

.nky_yfblw {
  d: path("M23.493 25.306c0-.402.326-.732.727-.732h2.391a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1H24.22a.731.731 0 0 1-.32-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.nyysd-7fx {
  d: path("M16.054 13.56a3.1 3.1 0 0 1-1.415-.337c-.135-.077-.289.087-.202.222c.347.53.934.876 1.617.876c.684 0 1.27-.347 1.617-.876c.087-.135-.067-.289-.202-.222a3.1 3.1 0 0 1-1.415.337");
}

.o0aif1l1c {
  stop-color: var(--svg-color--d3968c, #D3968C);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oolzzy49q {
  stop-color: var(--svg-color--399967, #399967);
}

.owu6h_2xv {
  fill: var(--svg-color--000, #000);
  d: path("M14.43 10.52a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.p5m7l5lux {
  fill: var(--svg-color--45bb85, #45BB85);
  d: path("M15.969 15.5c-6.07 0-10.99 4.91-10.99 10.98v3.5h21.98v-3.5c0-6.07-4.92-10.98-10.99-10.98");
}

.pescu9bef {
  stop-color: var(--svg-color--6a9e7e, #6A9E7E);
}

.pk0ymrp0a {
  d: path("m15.713 10.406l-.5 1.627a.518.518 0 0 0 .5.674h.751a.526.526 0 0 0 .5-.674l-.5-1.627c-.135-.356-.645-.356-.75 0");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pqe0dnzfz {
  stop-color: var(--svg-color--4e2d3a, #4E2D3A);
  stop-opacity: 0;
}

.pujrc2bni {
  fill: var(--svg-color--3661c6, #3661C6);
  d: path("M19.46 25.81h-6.94a.49.49 0 0 0-.5.492v3.62h7.95v-3.62a.513.513 0 0 0-.51-.492");
}

.q3_rwp8df {
  d: path("M8.979 29.98V18.01h-.006a10.95 10.95 0 0 0-3.994 8.47v3.5z");
}

.q7l79-2rh {
  stop-color: var(--svg-color--f7ceb9, #F7CEB9);
}

.qok44-bhf {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.395 13.472a1.97 1.97 0 0 0 1.66.899c.7 0 1.303-.356 1.658-.899a.2.2 0 0 0-.023-.248a.21.21 0 0 0-.243-.045a3.1 3.1 0 0 1-1.393.331c-.511 0-.984-.123-1.391-.33a.2.2 0 0 0-.245.04a.2.2 0 0 0-.023.252Z");
}

.quk3dgi1t {
  stop-color: var(--svg-color--cd9282, #CD9282);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxarokbzg {
  stop-color: var(--svg-color--423735, #423735);
}

.r_2nh8m3w {
  stop-color: var(--svg-color--a099a8, #A099A8);
}

.r0p9vfbnw {
  stop-color: var(--svg-color--ca8b73, #CA8B73);
  stop-opacity: 0;
}

.r9exlwbyv {
  stop-color: var(--svg-color--4f3b60, #4F3B60);
}

.rbuuvqb-n {
  stop-color: var(--svg-color--1e1723, #1E1723);
}

.rhalidc9f {
  stop-color: var(--svg-color--3d935b, #3D935B);
}

.rl_kfsb7q {
  stop-color: var(--svg-color--784853, #784853);
}

.rs3k7gc8p {
  stop-color: var(--svg-color--2a5923, #2A5923);
}

.ruump_bfn {
  d: path("M15.96 18.66c-1.14 0-2.06-.92-2.06-2.06v-2.56c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v2.56a2.07 2.07 0 0 1-2.06 2.06");
}

.s0qpik8kr {
  stop-color: var(--svg-color--4c2524, #4C2524);
}

.s7aakmgnr {
  stop-color: var(--svg-color--b58885, #B58885);
}

.sa4iv-boa {
  d: path("M15.969 15.5c-6.07 0-10.99 4.91-10.99 10.98v3.5h21.98v-3.5c0-6.07-4.92-10.98-10.99-10.98");
}

.sjjzhrr4a {
  d: path("M18.186 9.627a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.syybhxbau {
  stop-color: var(--svg-color--f3bda8, #F3BDA8);
  stop-opacity: 0;
}

.t11jy5bth {
  stop-color: var(--svg-color--cd9b96, #CD9B96);
  stop-opacity: 0;
}

.t40345qox {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
}

.tbsuik4az {
  stop-color: var(--svg-color--36a9f3, #36A9F3);
}

.tfz5b9oyk {
  cx: 13.649px;
  cy: 10.008px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.tj2vllbvr {
  stop-color: var(--svg-color--f3c6af, #F3C6AF);
}

.turl0o68q {
  d: path("M19.383 7.998h-2.619c-1.38 0-2.044-.559-2.628-1.083c0 0-.86.042-1.259.101c-.215.234-.443.53-.977.886c-.23.116-.756.527-.765 1.46l.063 2.594c.106 2.801 2.262 4.669 4.88 4.669c2.62 0 4.766-1.868 4.881-4.67V9.454c0-1.34-1.393-1.455-1.576-1.455");
}

.txm18jrit {
  d: path("M20.826 12.515a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.tzunxobuv {
  d: path("M18.98 10.402a.84.84 0 0 0-.23-.463l-.26.286l.117.227z");
}

.urzuj9che {
  stop-color: var(--svg-color--4c4649, #4C4649);
}

.uspdh30af {
  stop-color: var(--svg-color--e4af95, #E4AF95);
}

.uzac_3qef {
  stop-color: var(--svg-color--ffd1bb, #FFD1BB);
}

.v3q9_hbbs {
  d: path("M10.54 7.55c.978-.499 2.223-.544 2.65-.554l-.514 4.653l1.832 4.33L11.9 17.73c-3.585-.735-3.348-3.564-3.137-4.355c.222-.831.028-1.02-.085-1.788c-.272-1.833.329-3.255 1.863-4.038");
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.v93svlujl {
  fill: var(--svg-color--d69790, #D69790);
  d: path("m15.486 10.632l-.5 1.627a.518.518 0 0 0 .5.674h.75a.526.526 0 0 0 .501-.674l-.5-1.627c-.135-.356-.645-.356-.751 0");
}

.va-kb9bvg {
  stop-color: var(--svg-color--7d5248, #7D5248);
}

.vgzo13b2o {
  stop-color: var(--svg-color--edc0ab, #EDC0AB);
}

.vi4mtz2pd {
  d: path("M13.919 9.627a.892.892 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.893");
}

.vni43obah {
  stop-color: var(--svg-color--d3968c, #D3968C);
}

.vryawy-6e {
  d: path("m16.89 19.69l-.65.58c-.16.14-.39.14-.55 0l-.65-.58a3.45 3.45 0 0 1-1.14-2.55v-3.09c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v3.09c0 .97-.41 1.9-1.13 2.55");
}

.vvdbjrbwx {
  stop-color: var(--svg-color--d09480, #D09480);
  stop-opacity: 0;
}

.vwhs-0blc {
  fill: var(--svg-color--000, #000);
  d: path("M17.675 10.52c0-.284.227-.511.511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.06-.235");
}

.vx-77wbda {
  stop-color: var(--svg-color--ca8b73, #CA8B73);
}

.vz8fcrkfe {
  stop-color: var(--svg-color--131720, #131720);
}

.w-37x5bhe {
  stop-color: var(--svg-color--7c5351, #7C5351);
}

.w22vs7beb {
  stop-color: var(--svg-color--d89793, #D89793);
  stop-opacity: 0;
}

.w6969eyte {
  stop-color: var(--svg-color--387c46, #387C46);
}

.wevrdub6o {
  stop-color: var(--svg-color--5cc585, #5CC585);
}

.wly33_qqy {
  stop-color: var(--svg-color--9c8f92, #9C8F92);
}

.wruv5824x {
  fill: var(--svg-color--cd9684, #CD9684);
  d: path("M11.296 12.515a1.609 1.609 0 1 0 0-3.218a1.609 1.609 0 0 0 0 3.218");
}

.wvv92-bqk {
  fill: var(--svg-color--1d1b1f, #1D1B1F);
  d: path("M17.144 10.132c.266-.466.67-.835 1.538-.835c.38 0 .747.105 1.073.369c.268.217.232.495.024.599l-.556.317c-.652-.21-1.372-.239-2.079-.45");
}

.x5dyrqz_l {
  stop-color: var(--svg-color--1f171b, #1F171B);
}

.x6aj7b3cp {
  stop-color: var(--svg-color--88625f, #88625F);
  stop-opacity: 0;
}

.xdi9wqbra {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.1 28.474h1.797");
}

.xjz9wom2l {
  stop-color: var(--svg-color--4e2d3a, #4E2D3A);
}

.xuadj21pj {
  stop-color: var(--svg-color--18111b, #18111B);
}

.xx3sv-b8t {
  cx: 13.649px;
  cy: 10.008px;
  rx: 0.389px;
  ry: 0.197px;
}

.y2pqqr5ks {
  stop-color: var(--svg-color--4c2524, #4C2524);
  stop-opacity: 0;
}

.y8u9aob3m {
  stop-color: var(--svg-color--d89793, #D89793);
}

.y9bk_9fsc {
  stop-color: var(--svg-color--85808c, #85808C);
}

.ya4lejb1r {
  stop-color: var(--svg-color--6e5980, #6E5980);
}

.yc_s6bd2r {
  stop-color: var(--svg-color--6e4f4b, #6E4F4B);
}

.yds08u11w {
  stop-color: var(--svg-color--b8877d, #B8877D);
}

.ykhy9yb4g {
  d: path("M26.811 23.12c.55 0 1 .45 1 1v2.29h-2v-2.29c0-.55.44-1 1-1");
}

.ym265mvaz {
  stop-color: var(--svg-color--2d5ca0, #2D5CA0);
}

.yrr42qhfr {
  stop-color: var(--svg-color--5aa37a, #5AA37A);
  stop-opacity: 0;
}

.yv6vzebbo {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.12 9.816c.063.085-.07.189-.22.302c-.151.113-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.05");
}

.ywpvidbgc {
  stop-color: var(--svg-color--d39d91, #D39D91);
  stop-opacity: 0;
}

.z48shob3w {
  stop-color: var(--svg-color--906549, #906549);
}

.z6plkxa1j {
  d: path("M20.826 11.98a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.zgqoc8mjm {
  stop-color: var(--svg-color--d59f92, #D59F92);
}

.zif_-obqz {
  stop-color: var(--svg-color--519473, #519473);
}

.zjnvspbhz {
  stop-color: var(--svg-color--28659f, #28659F);
}

.zm4f_vbug {
  stop-color: var(--svg-color--2a5923, #2A5923);
  stop-opacity: 0;
}

.zonfpmhlw {
  stroke: var(--svg-color--545154, #545154);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.9 8.26c.236-.1 1.324 0 1.732.312");
}

.ztn8dybrr {
  stop-color: var(--svg-color--89829d, #89829D);
  stop-opacity: 0;
}

</style>
