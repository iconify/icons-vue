<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iz3mQQb)" class="aws_nt4ci"/><path fill="url(#i1cRYFd)" class="aws_nt4ci"/><path fill="url(#icnhZDc)" class="aws_nt4ci"/><path fill="url(#iOP2Ohd)" class="aws_nt4ci"/><path fill="url(#ijJ67Ab)" class="aws_nt4ci"/><path fill="url(#iTurAae)" class="j6d89oxit"/><path fill="url(#i5scyjb)" class="j6d89oxit"/><path class="wipobbytx"/><path fill="url(#icw5Hdb)" class="ddy_m7bwz"/><path fill="url(#ijj3D0b)" class="ddy_m7bwz"/><path class="gjxytnb1g"/><path fill="url(#iRSMENc)" class="b_h5u3bsb"/><path fill="url(#iB8trud)" class="b_h5u3bsb"/><g filter="url(#i6axmKe)"><circle fill="url(#ia3z8Xc)" class="c6creuxtu"/></g><g filter="url(#iDi9hSd)"><circle fill="url(#iUgRBSc)" class="v--lu-jvm"/></g><g filter="url(#iV2C5qb)"><circle fill="url(#i59tAQe)" class="kro2j8blb"/><circle fill="url(#ir10nKb)" class="kro2j8blb"/></g><g filter="url(#iWCxD5b)"><circle class="m2qoroo_y"/><circle fill="url(#i2riH8d)" class="n3nm0bosk"/><circle fill="url(#iSTJfbX)" class="n3nm0bosk"/></g><g filter="url(#i2Wjsne)"><path fill="url(#imREQKe)" class="v6sq6d8jx"/><path fill="url(#i5BI7Qc)" class="v6sq6d8jx"/><path fill="url(#iz3RnFc)" class="v6sq6d8jx"/><path fill="url(#izMM9vc)" class="v6sq6d8jx"/><path fill="url(#iFjg5lc)" class="v6sq6d8jx"/><path fill="url(#iQWTt9d)" class="v6sq6d8jx"/></g><g filter="url(#ifoiZec)"><path fill="url(#iu8KpEc)" class="ro8jsitoo"/></g><g filter="url(#iiTW8ho)"><path class="uha2wl_iu"/><path fill="url(#iGywhoc)" class="bhmjdkq1e"/><path fill="url(#ihbx9Wc)" class="bhmjdkq1e"/><path fill="url(#iVFKuPd)" class="bhmjdkq1e"/><path fill="url(#iKY0Eab)" class="bhmjdkq1e"/></g><g filter="url(#iuQxiKd)"><path class="fe1_pmbvl"/></g><g filter="url(#isnd0PG)"><path class="x0fr-9bso"/><path fill="url(#iRlSVQb)" class="sxxb_bc7b"/><path fill="url(#iVL0cfc)" class="sxxb_bc7b"/><path fill="url(#iDO1GLb)" class="sxxb_bc7b"/><path fill="url(#iVs9STb)" class="sxxb_bc7b"/></g><path stroke="url(#ijgBESP)" class="k56ipfjbe"/><g filter="url(#iwCaQlc)"><path class="idk-atbde"/></g><g filter="url(#i5yz7nb)"><path class="sk72wrbmx"/></g><path class="owz-m2ber"/><path fill="url(#i2XMyoc)" class="g9nmd7bmz"/><path class="pzptj9bmd"/><g filter="url(#i8Hczzc)"><path class="r_-9w3b2m"/><path fill="url(#ihH36te)" class="v-nc74bzb"/></g><g filter="url(#ifvcOWd)"><path fill="url(#iWyWpME)" class="g4kk9g4hm"/></g><path class="mrib0g31z"/><path fill="url(#iChKpge)" class="rcq8rz3rz"/><path class="jhma9dbgu"/><g filter="url(#itv2Gkd)"><path fill="url(#isaT3lb)" class="vlk8idp1z"/></g><g filter="url(#i8g7WGd)"><ellipse transform="rotate(-27.914 12.156 12.973)" class="qxhcviban"/><ellipse fill="url(#iO2f4EW)" transform="rotate(-27.914 12.156 12.973)" class="c2tp96bxi"/></g><g filter="url(#iEclPIo)"><path stroke="url(#ieIQOsb)" class="fsxrsabwz"/></g><g filter="url(#iYv3Dmq)"><path stroke="url(#iPAubxd)" class="r9gc4bslt"/></g><g filter="url(#icAwEsd)"><path stroke="url(#iTmWdoc)" class="l6sq_bb8t"/></g><path fill="url(#iSn49lc)" class="yljcw9bue"/><path fill="url(#i87cXfb)" class="yljcw9bue"/><path fill="url(#is68ONb)" class="pea7oobyq"/><path fill="url(#iChYE1b)" class="pea7oobyq"/><path fill="url(#iAbzS5c)" class="kj29_3k1a"/><path fill="url(#iKsfUvc)" class="kj29_3k1a"/><g filter="url(#i0S4Aye)"><circle fill="url(#iOlDWZd)" class="b0jb_1x7j"/><circle fill="url(#iUXhpdQ)" class="b0jb_1x7j"/><circle fill="url(#iO9hFtd)" class="b0jb_1x7j"/></g><g filter="url(#iRZ5yPc)"><path fill="url(#iJ0uIfb)" clip-rule="evenodd" class="ivg4irbsu"/></g><path fill="url(#iSHw5kc)" clip-rule="evenodd" class="ivg4irbsu"/><g filter="url(#i6NFxhh)"><path fill="url(#iUOwuHL)" clip-rule="evenodd" class="je3dgdm3t"/></g><g filter="url(#iXXzU9d)"><circle stroke="url(#iVD2pJb)" class="gabexwume"/></g><g filter="url(#iLKFyLo)"><circle stroke="url(#iJqurnc)" class="blcfaubqg"/></g><g filter="url(#iNr68VO)"><circle stroke="url(#iT2zksd)" class="yn6hjlequ"/></g><g filter="url(#iMSdLHW)"><circle stroke="url(#intsvLd)" class="c7f9aty3q"/></g><defs><radialGradient id="iz3mQQb" cx="0" cy="0" r="1" gradientTransform="rotate(154.071 8.245 14.195)scale(15.0662 17.3462)" gradientUnits="userSpaceOnUse"><stop class="tet72waca"/><stop offset="1" class="bmx48tuma"/></radialGradient><radialGradient id="i1cRYFd" cx="0" cy="0" r="1" gradientTransform="rotate(-115.528 17.423 10.871)scale(12.9022 18.5657)" gradientUnits="userSpaceOnUse"><stop offset=".879" class="rxprtfb0z"/><stop offset="1" class="m-fo0lvbc"/></radialGradient><radialGradient id="icnhZDc" cx="0" cy="0" r="1" gradientTransform="rotate(166.984 5.913 10.509)scale(6.38273 2.1839)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="zdar40bkv"/><stop offset="1" class="cybfe7yaw"/></radialGradient><radialGradient id="iOP2Ohd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.6713 0 0 -14.1675 21.546 29.943)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="puczgzv3j"/><stop offset="1" class="mq0bii3nt"/></radialGradient><radialGradient id="ijJ67Ab" cx="0" cy="0" r="1" gradientTransform="matrix(1.24045 0 0 9.50024 7.166 29.943)" gradientUnits="userSpaceOnUse"><stop class="wke-8-xfb"/><stop offset="1" class="h-56b9bpz"/></radialGradient><radialGradient id="iTurAae" cx="0" cy="0" r="1" gradientTransform="matrix(3.25185 0 0 9.13279 21.576 29.165)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="kin3dabop"/><stop offset="1" class="jlkbatyzp"/></radialGradient><radialGradient id="i5scyjb" cx="0" cy="0" r="1" gradientTransform="matrix(.87006 0 0 11.9715 21.576 29.943)" gradientUnits="userSpaceOnUse"><stop class="hos3q5hgu"/><stop offset="1" class="txm2ysbkn"/></radialGradient><radialGradient id="icw5Hdb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.70862 0 0 -8.85437 7.31 29.943)" gradientUnits="userSpaceOnUse"><stop offset=".614" class="vp_-q7ldm"/><stop offset=".956" class="k-z4zg2os"/></radialGradient><radialGradient id="ijj3D0b" cx="0" cy="0" r="1" gradientTransform="matrix(-.8463 0 0 -10.457 7.31 29.943)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="oxun88gow"/><stop offset="1" class="zi0iv1bfj"/></radialGradient><radialGradient id="iRSMENc" cx="0" cy="0" r="1" gradientTransform="matrix(.5625 1.75 -3.03541 .97567 13.7 19.579)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="ywa6djbto"/><stop offset="1" class="vr7u86b4e"/></radialGradient><radialGradient id="iB8trud" cx="0" cy="0" r="1" gradientTransform="rotate(139.583 4.368 13.602)scale(2.48229 1.07513)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="ri12thbtt"/><stop offset="1" class="rlb4jpb3h"/></radialGradient><radialGradient id="ia3z8Xc" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 8.19 13.751)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="x3sd7rf5r"/><stop offset="1" class="dsm4f-bda"/></radialGradient><radialGradient id="ir10nKb" cx="0" cy="0" r="1" gradientTransform="matrix(.82748 -.60254 .68772 .94447 19.756 13.486)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ytssyfa7a"/><stop offset="1" class="fnfe_1psv"/></radialGradient><radialGradient id="i2riH8d" cx="0" cy="0" r="1" gradientTransform="matrix(.82204 -1.51196 .88496 .48114 19.343 14.573)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="lvos55blo"/><stop offset=".916" class="bvmj8ubsx"/></radialGradient><radialGradient id="iSTJfbX" cx="0" cy="0" r="1" gradientTransform="matrix(.25953 .2569 -.33118 .33457 19.384 13.75)" gradientUnits="userSpaceOnUse"><stop class="iqm2531qk"/><stop offset="1" class="n3g96cceg"/></radialGradient><radialGradient id="iz3RnFc" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.11187 -9.65399 0 14.312 13.552)" gradientUnits="userSpaceOnUse"><stop offset=".561" class="vjz9_3rja"/><stop offset="1" class="my1z1hkvz"/></radialGradient><radialGradient id="izMM9vc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.61023 0 16.962 12.479)" gradientUnits="userSpaceOnUse"><stop class="kb28pwbin"/><stop offset="1" class="uck_nmbag"/></radialGradient><radialGradient id="iFjg5lc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39218 1.7313 0 12.4 12.445)" gradientUnits="userSpaceOnUse"><stop class="j7sc31byj"/><stop offset="1" class="e9zt2gbxt"/></radialGradient><radialGradient id="iQWTt9d" cx="0" cy="0" r="1" gradientTransform="rotate(-166.409 10.63 8.833)scale(2.92567 1.71902)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="ph-yb3bws"/><stop offset="1" class="az2la2bjr"/></radialGradient><radialGradient id="iGywhoc" cx="0" cy="0" r="1" gradientTransform="matrix(.79857 -2.95942 1.09745 .29614 18.963 9.64)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="ihbx9Wc" cx="0" cy="0" r="1" gradientTransform="matrix(3.82845 .35231 -.18944 2.05853 17.32 7.88)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="iVFKuPd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68076 -2.60303 0 14.614 5.142)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="iKY0Eab" cx="0" cy="0" r="1" gradientTransform="matrix(3.07685 -2.2548 3.53253 4.82042 8.159 11.966)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="iVs9STb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19709 -.6332 0 14.941 15.36)" gradientUnits="userSpaceOnUse"><stop class="ldpzz4bsg"/><stop offset="1" class="xtaxaigve"/></radialGradient><radialGradient id="i2XMyoc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8119 -1.29142 0 16.795 13.068)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ihH36te" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 16.566 13.153)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iChKpge" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81194 -1.29148 0 12.428 13.069)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iO2f4EW" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.611 .668)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iSn49lc" cx="0" cy="0" r="1" gradientTransform="rotate(152.815 10.943 5.514)scale(5.16422 4.07334)" gradientUnits="userSpaceOnUse"><stop class="vauv6-kqu"/><stop offset=".871" class="d7nlg-wae"/></radialGradient><radialGradient id="i87cXfb" cx="0" cy="0" r="1" gradientTransform="matrix(2.98437 .4375 -.0798 .54434 17.743 7.328)" gradientUnits="userSpaceOnUse"><stop offset=".037" class="yidkw-brm"/><stop offset="1" class="hv9dr3b3w"/></radialGradient><radialGradient id="iOlDWZd" cx="0" cy="0" r="1" gradientTransform="rotate(141.18 10.637 7.96)scale(.43619)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="cz-qsgbfy"/><stop offset="1" class="j80tr6o9y"/></radialGradient><radialGradient id="iUXhpdQ" cx="0" cy="0" r="1" gradientTransform="matrix(.19922 -.48438 1.17186 .48198 23.594 7.934)" gradientUnits="userSpaceOnUse"><stop offset=".147" class="m8bo-jb-t"/><stop offset="1" class="wy7e69bbh"/></radialGradient><radialGradient id="iO9hFtd" cx="0" cy="0" r="1" gradientTransform="matrix(.4375 .04684 -.05916 .55254 23.369 7.496)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="zk512ndyg"/><stop offset="1" class="hy0z0nf6k"/></radialGradient><radialGradient id="iJ0uIfb" cx="0" cy="0" r="1" gradientTransform="matrix(2.20247 -1.61719 2.56784 3.49718 21.396 10.683)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="cnux6p8xn"/><stop offset="1" class="jaxt-o31p"/></radialGradient><radialGradient id="iUOwuHL" cx="0" cy="0" r="1" gradientTransform="matrix(2.53124 -1.40627 1.98705 3.57664 24.543 8.86)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="cnux6p8xn"/><stop offset="1" class="jaxt-o31p"/></radialGradient><filter id="i6axmKe" width="3.542" height="3.342" x="8.191" y="12.08" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.270588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_26"/></filter><filter id="iDi9hSd" width="2.992" height="2.992" x="8.366" y="12.255" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_26" stdDeviation=".25"/></filter><filter id="iV2C5qb" width="3.592" height="3.592" x="17.713" y="11.83" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.141176 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_26"/></filter><filter id="iWCxD5b" width="2.992" height="2.992" x="17.888" y="12.255" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_26" stdDeviation=".25"/></filter><filter id="i2Wjsne" width="10.383" height="12.189" x="9.451" y="8.121" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.0509804 0 0 0 0 0.0509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_26"/></filter><filter id="ifoiZec" width="6.25" height="5.07" x="13.784" y="7.121" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_26" stdDeviation=".5"/></filter><filter id="iiTW8ho" width="12.614" height="8.551" x="8.307" y="4.642" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_26"/></filter><filter id="iuQxiKd" width="3.262" height="4.184" x="12.744" y="12.596" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_26" stdDeviation=".375"/></filter><filter id="isnd0PG" width="2.079" height="2.884" x="13.575" y="13.083" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_26" stdDeviation=".05"/></filter><filter id="iwCaQlc" width="2.982" height="1.874" x="15.797" y="10.099" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_26"/></filter><filter id="i5yz7nb" width="2.982" height="1.874" x="10.645" y="10.099" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_26"/></filter><filter id="i8Hczzc" width=".787" height=".697" x="16.06" y="12.628" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_26" stdDeviation=".05"/></filter><filter id="ifvcOWd" width=".892" height=".914" x="16.901" y="12.704" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_26" stdDeviation=".1"/></filter><filter id="itv2Gkd" width=".987" height="1.041" x="12.455" y="12.64" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_26" stdDeviation=".1"/></filter><filter id="i8g7WGd" width=".914" height=".705" x="11.7" y="12.62" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_26" stdDeviation=".05"/></filter><filter id="iEclPIo" width="2.701" height="1.281" x="15.851" y="10.426" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_26" stdDeviation=".15"/></filter><filter id="iYv3Dmq" width="2.779" height="1.339" x="10.627" y="10.489" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_26" stdDeviation=".15"/></filter><filter id="icAwEsd" width="1.008" height="2.271" x="9.443" y="8.56" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_26" stdDeviation=".125"/></filter><filter id="i0S4Aye" width=".726" height=".726" x="23.426" y="7.174" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.52549 0 0 0 0 0.388235 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_26"/></filter><filter id="iRZ5yPc" width="3.834" height="4.387" x="20.968" y="7.975" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.45098 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_26"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.282353 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_26" result="effect2_innerShadow_4002_26"/></filter><filter id="i6NFxhh" width="4.283" height="3.734" x="24.166" y="6.499" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.203922 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_26"/></filter><filter id="iXXzU9d" width="3.843" height="3.843" x="24.637" y="6.469" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_26" stdDeviation=".1"/></filter><filter id="iLKFyLo" width="2.734" height="2.734" x="25.191" y="7.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_26" stdDeviation=".1"/></filter><filter id="iNr68VO" width="2.734" height="2.734" x="21.543" y="9.037" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_26" stdDeviation=".1"/></filter><filter id="iMSdLHW" width="3.805" height="3.805" x="21.008" y="8.502" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_26" stdDeviation=".1"/></filter><linearGradient id="iUgRBSc" x1="9.862" x2="9.221" y1="14.03" y2="14.03" gradientUnits="userSpaceOnUse"><stop class="fbs6uccsw"/><stop offset="1" class="np-b1wbds"/></linearGradient><linearGradient id="i59tAQe" x1="20.471" x2="19.652" y1="12.659" y2="15.197" gradientUnits="userSpaceOnUse"><stop class="o1rzobcjq"/><stop offset="1" class="acjykw8xe"/></linearGradient><linearGradient id="imREQKe" x1="18.654" x2="11.01" y1="14.141" y2="15.28" gradientUnits="userSpaceOnUse"><stop class="cdm_o50ho"/><stop offset="1" class="ahguepbtf"/></linearGradient><linearGradient id="i5BI7Qc" x1="9.213" x2="11.48" y1="16.84" y2="16.698" gradientUnits="userSpaceOnUse"><stop offset=".283" class="j-n0q842a"/><stop offset="1" class="o-j_7gbpq"/></linearGradient><linearGradient id="iu8KpEc" x1="15.574" x2="24.199" y1="10.76" y2="7.791" gradientUnits="userSpaceOnUse"><stop class="cgqcq-bjq"/><stop offset="1" class="o1syipbau"/></linearGradient><linearGradient id="iRlSVQb" x1="13.749" x2="14.688" y1="14.801" y2="14.801" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="iVL0cfc" x1="15.553" x2="14.527" y1="15.124" y2="15.109" gradientUnits="userSpaceOnUse"><stop class="yww6tz8di"/><stop offset="1" class="n-4z7qb5o"/></linearGradient><linearGradient id="iDO1GLb" x1="14.809" x2="14.809" y1="15.867" y2="15.293" gradientUnits="userSpaceOnUse"><stop class="xtiplndwl"/><stop offset="1" class="h8-lntwqp"/></linearGradient><linearGradient id="ijgBESP" x1="13.576" x2="14.011" y1="17.483" y2="16.795" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="iWyWpME" x1="17.573" x2="17.259" y1="13.122" y2="13.316" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="isaT3lb" x1="13.172" x2="12.858" y1="13.122" y2="13.316" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ieIQOsb" x1="17.589" x2="17.169" y1="10.981" y2="10.121" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iPAubxd" x1="12.279" x2="11.089" y1="10.853" y2="10.354" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iTmWdoc" x1="9.948" x2="9.948" y1="8.836" y2="10.996" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient><linearGradient id="is68ONb" x1="24.949" x2="23.758" y1="5.636" y2="5.291" gradientUnits="userSpaceOnUse"><stop class="p9lsnsm5t"/><stop offset="1" class="lapvr59ed"/></linearGradient><linearGradient id="iChYE1b" x1="23.801" x2="23.875" y1="7.129" y2="6.84" gradientUnits="userSpaceOnUse"><stop offset=".16" class="zl0fwhbas"/><stop offset="1" class="lxc0fmbqt"/></linearGradient><linearGradient id="iAbzS5c" x1="22.887" x2="23.152" y1="7.985" y2="6.688" gradientUnits="userSpaceOnUse"><stop class="p9lsnsm5t"/><stop offset="1" class="lapvr59ed"/></linearGradient><linearGradient id="iKsfUvc" x1="24.298" x2="24.1" y1="8.067" y2="8.011" gradientUnits="userSpaceOnUse"><stop class="jd-vaq0no"/><stop offset="1" class="gof7ehbkx"/></linearGradient><linearGradient id="iSHw5kc" x1="23.637" x2="23.578" y1="8.157" y2="8.383" gradientUnits="userSpaceOnUse"><stop offset=".209" class="ni_6htbzm"/><stop offset="1" class="ajm38_jxm"/></linearGradient><linearGradient id="iVD2pJb" x1="24.887" x2="28.077" y1="8.759" y2="7.287" gradientUnits="userSpaceOnUse"><stop offset=".616" class="w5_7ycb6b"/><stop offset=".9" class="srm_r_guo"/></linearGradient><linearGradient id="iJqurnc" x1="25.441" x2="27.573" y1="8.637" y2="7.653" gradientUnits="userSpaceOnUse"><stop offset=".247" class="jzjqx7qlk"/><stop offset=".669" class="gl3wl_9gz"/></linearGradient><linearGradient id="iT2zksd" x1="21.793" x2="23.925" y1="10.651" y2="9.666" gradientUnits="userSpaceOnUse"><stop offset=".247" class="rraw6sbsp"/><stop offset=".669" class="r8ibvzbki"/></linearGradient><linearGradient id="intsvLd" x1="24.563" x2="22.91" y1="9.863" y2="10.404" gradientUnits="userSpaceOnUse"><stop class="znwvjy5yx"/><stop offset="1" class="zi0lb2bns"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-getting-haircut-dark" /></template>
<style>
.acjykw8xe {
  stop-color: var(--svg-color--452a31, #452A31);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.ajm38_jxm {
  stop-color: var(--svg-color--ff3178, #FF3178);
  stop-opacity: 0;
}

.aws_nt4ci {
  d: path("M3.601 29.48c0-5.916 4.854-10.711 10.842-10.711s10.842 4.796 10.842 10.711v.463H3.601z");
}

.az2la2bjr {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
  stop-opacity: 0;
}

.b_h5u3bsb {
  d: path("M12.63 18.563h3.985v1.383c0 1.1-.892 1.812-1.992 1.812s-1.992-.712-1.992-1.812z");
}

.b0jb_1x7j {
  cx: 23.739px;
  cy: 7.587px;
  r: 0.313px;
}

.bhmjdkq1e {
  d: path("m19.438 7.267l.429.214c.752.373 1.181 1.227 1.02 2.135l-.59 3.043c-.053.314-.26.526-.573.534h-.018s.054-.908.107-1.442c.044-.433-.032-.565-.43-.96c-.214-.214-.375-.534-.375-.855v-.854c0-.267-.215-.48-.43-.534c-.644-.16-1.986-.427-3.919-.427s-3.275.267-3.92.427a.52.52 0 0 0-.429.534v.854c0 .32-.107.64-.376.854l-.16.16c-.216.16-.323.481-.323.748c.054.587.107 1.441.107 1.441l-.049-.001a.634.634 0 0 1-.595-.532l-.59-3.043c-.108-.855.322-1.709 1.073-2.082l.43-.214c.268-.16.537-.374.805-.587l.967-1.014c.59-.534 1.45-.694 2.201-.32c.537.16 1.127.16 1.664 0c.806-.268 1.719-.054 2.363.533l.805.8c.215.268.483.428.805.588");
}

.blcfaubqg {
  cx: 26.558px;
  cy: 8.391px;
  r: 1.117px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.bmx48tuma {
  stop-color: var(--svg-color--2477dd, #2477DD);
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bvmj8ubsx {
  stop-color: var(--svg-color--31191a, #31191A);
}

.c2tp96bxi {
  cx: 12.156px;
  cy: 12.973px;
  rx: 0.39px;
  ry: 0.197px;
}

.c6creuxtu {
  cx: 9.862px;
  cy: 13.751px;
  r: 1.671px;
}

.c7f9aty3q {
  cx: 22.91px;
  cy: 10.404px;
  r: 1.652px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.cdm_o50ho {
  stop-color: var(--svg-color--533531, #533531);
}

.cgqcq-bjq {
  stop-color: var(--svg-color--675454, #675454);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnux6p8xn {
  stop-color: var(--svg-color--ff7046, #FF7046);
}

.cybfe7yaw {
  stop-color: var(--svg-color--27719e, #27719E);
  stop-opacity: 0;
}

.cz-qsgbfy {
  stop-color: var(--svg-color--ebdbe4, #EBDBE4);
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.d7nlg-wae {
  stop-color: var(--svg-color--322a2d, #322A2D);
}

.ddy_m7bwz {
  d: path("M7.31 21.414C5.037 23.377 3.6 26.263 3.6 29.48v.463h3.71z");
}

.dsm4f-bda {
  stop-color: var(--svg-color--332423, #332423);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e9zt2gbxt {
  stop-color: var(--svg-color--351d26, #351D26);
  stop-opacity: 0;
}

.fbs6uccsw {
  stop-color: var(--svg-color--281920, #281920);
}

.fe1_pmbvl {
  fill: var(--svg-color--332024, #332024);
  d: path("m14.338 13.629l-.82 1.701c-.103.35.142.7.488.7h.738c.346 0 .59-.355.488-.7l-.498-1.701c-.107-.377-.284-.377-.396 0");
}

.fnfe_1psv {
  stop-color: var(--svg-color--40272a, #40272A);
  stop-opacity: 0;
}

.fsxrsabwz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M16.276 10.884c.43-.075 1.27-.054 1.851.398");
}

.ft5dv1b6b {
  fill: none;
}

.g4kk9g4hm {
  d: path("M17.593 13.367a.84.84 0 0 0-.232-.463l-.26.285l.117.228z");
}

.g9nmd7bmz {
  d: path("M16.797 12.591a.893.893 0 0 1 .86 1.129h-1.725a.897.897 0 0 1 .865-1.128");
}

.gabexwume {
  cx: 26.558px;
  cy: 8.391px;
  r: 1.671px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gjxytnb1g {
  fill: var(--svg-color--3c222a, #3C222A);
  d: path("M12.63 18.563h3.985v1.383c0 1.1-.892 1.812-1.992 1.812s-1.992-.712-1.992-1.812z");
}

.gl3wl_9gz {
  stop-color: var(--svg-color--ff7e7a, #FF7E7A);
  stop-opacity: 0;
}

.gof7ehbkx {
  stop-color: var(--svg-color--a2889f, #A2889F);
  stop-opacity: 0;
}

.h-56b9bpz {
  stop-color: var(--svg-color--1f6ce0, #1F6CE0);
  stop-opacity: 0;
}

.h8-lntwqp {
  stop-color: var(--svg-color--3f222f, #3F222F);
  stop-opacity: 0;
}

.hos3q5hgu {
  stop-color: var(--svg-color--367bf1, #367BF1);
}

.hv9dr3b3w {
  stop-color: var(--svg-color--484344, #484344);
  stop-opacity: 0;
}

.hy0z0nf6k {
  stop-color: var(--svg-color--a4888c, #A4888C);
  stop-opacity: 0;
}

.idk-atbde {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m18.337 11.029l-.001-.001l-.002-.002l-.005-.004l-.012-.01a1.4 1.4 0 0 0-.155-.107c-.1-.062-.24-.14-.42-.21a2.84 2.84 0 0 0-1.494-.159a.534.534 0 1 0 .167 1.055c.398-.063.717.01.934.097a1.5 1.5 0 0 1 .301.16l.008.005a.534.534 0 0 0 .679-.824");
}

.iqm2531qk {
  stop-color: var(--svg-color--352123, #352123);
}

.ivg4irbsu {
  fill-rule: evenodd;
  d: path("M23.013 8.03a.1.1 0 0 0-.124.067l-.104.357a.22.22 0 0 1-.174.149a1.842 1.842 0 1 0 1.514.433a.21.21 0 0 1-.068-.22l.101-.349a.1.1 0 0 0-.068-.124zm.74 2.39a.844.844 0 1 1-1.687 0a.844.844 0 0 1 1.688 0");
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j6d89oxit {
  d: path("M21.577 29.943h3.708v-.463c0-3.217-1.436-6.103-3.709-8.066z");
}

.j7sc31byj {
  stop-color: var(--svg-color--351d26, #351D26);
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

.je3dgdm3t {
  fill-rule: evenodd;
  d: path("M24.457 7.242a.1.1 0 0 1 .123-.07l.36.095a.22.22 0 0 0 .216-.072a1.842 1.842 0 1 1-.412 1.52a.22.22 0 0 0-.153-.172l-.351-.094a.1.1 0 0 1-.071-.122zm1.664 1.87a.844.844 0 1 0 .872-1.444a.844.844 0 0 0-.872 1.445");
}

.jhma9dbgu {
  fill: var(--svg-color--000, #000);
  d: path("M12.938 13.484a.51.51 0 0 0-.512-.511a.51.51 0 0 0-.455.747h.906a.5.5 0 0 0 .06-.236");
}

.jlkbatyzp {
  stop-color: var(--svg-color--43a0f3, #43A0F3);
}

.jzjqx7qlk {
  stop-color: var(--svg-color--ff7e7a, #FF7E7A);
}

.k-z4zg2os {
  stop-color: var(--svg-color--517cc3, #517CC3);
}

.k56ipfjbe {
  fill: var(--svg-color--2a0219, #2A0219);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.25 16.511c.395.205.864.323 1.364.323c.505 0 .97-.118 1.363-.323a.204.204 0 0 1 .242.04a.19.19 0 0 1 .021.241m-2.99-.281l2.948.254m-2.947-.254a.2.2 0 0 0-.242.042a.19.19 0 0 0-.02.24m.262-.282l-.221.254m3.21.027l-.041-.027m.041.027l-.041-.027m.041.027a1.95 1.95 0 0 1-1.626.87a1.95 1.95 0 0 1-1.626-.87m3.21-.027c-.335.508-.919.846-1.584.846s-1.25-.338-1.585-.846m-.04.027v.001l.04-.028m-.04.027h-.001l.042-.027");
}

.kb28pwbin {
  stop-color: var(--svg-color--412628, #412628);
}

.kin3dabop {
  stop-color: var(--svg-color--43a2ff, #43A2FF);
}

.kj29_3k1a {
  d: path("m19.694 5.808l5.42 1.536l-.338 1.189l-4.313-1.223a1.15 1.15 0 0 1-.793-1.42z");
}

.kro2j8blb {
  cx: 19.384px;
  cy: 13.751px;
  r: 1.671px;
}

.l6sq_bb8t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.077 8.935v.899c-.008.148-.07.481-.259.622");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lapvr59ed {
  stop-color: var(--svg-color--d9b4c8, #D9B4C8);
}

.ldpzz4bsg {
  stop-color: var(--svg-color--624e4d, #624E4D);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lvos55blo {
  stop-color: var(--svg-color--31191a, #31191A);
  stop-opacity: 0;
}

.lxc0fmbqt {
  stop-color: var(--svg-color--c0a0b5, #C0A0B5);
  stop-opacity: 0;
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m-fo0lvbc {
  stop-color: var(--svg-color--407da5, #407DA5);
}

.m2qoroo_y {
  cx: 19.384px;
  cy: 13.751px;
  r: 0.996px;
  fill: var(--svg-color--463133, #463133);
}

.m8bo-jb-t {
  stop-color: var(--svg-color--996e9f, #996E9F);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mq0bii3nt {
  stop-color: var(--svg-color--459bfc, #459BFC);
  stop-opacity: 0;
}

.mrib0g31z {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.219 12.32c-.654 0-1.206.45-1.356 1.059a.274.274 0 0 0 .268.34h2.233a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.372-1.129");
}

.my1z1hkvz {
  stop-color: var(--svg-color--2e2840, #2E2840);
}

.n-4z7qb5o {
  stop-color: var(--svg-color--624d4b, #624D4B);
  stop-opacity: 0;
}

.n3g96cceg {
  stop-color: var(--svg-color--352123, #352123);
  stop-opacity: 0;
}

.n3nm0bosk {
  cx: 19.384px;
  cy: 13.751px;
  r: 0.996px;
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.ni_6htbzm {
  stop-color: var(--svg-color--b71143, #B71143);
}

.np-b1wbds {
  stop-color: var(--svg-color--27161d, #27161D);
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o1syipbau {
  stop-color: var(--svg-color--685654, #685654);
  stop-opacity: 0;
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.owz-m2ber {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.004 12.32c.654 0 1.206.45 1.356 1.059a.274.274 0 0 1-.268.34h-2.233a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.372-1.129");
}

.oxun88gow {
  stop-color: var(--svg-color--438dec, #438DEC);
}

.p9lsnsm5t {
  stop-color: var(--svg-color--9b8299, #9B8299);
}

.pea7oobyq {
  d: path("m24.342 3.231l-1.388 4.83l1.186.346l1.072-3.73a1.15 1.15 0 0 0-.784-1.421z");
}

.ph-yb3bws {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.puczgzv3j {
  stop-color: var(--svg-color--459bfc, #459BFC);
}

.pzptj9bmd {
  fill: var(--svg-color--000, #000);
  d: path("M16.285 13.484a.51.51 0 0 1 .512-.511a.51.51 0 0 1 .455.747h-.906a.46.46 0 0 1-.06-.236");
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxhcviban {
  cx: 12.156px;
  cy: 12.973px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.r_-9w3b2m {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.731 12.78c.064.085-.07.189-.22.302c-.151.113-.264.192-.327.107c-.064-.085.007-.245.158-.359c.152-.113.326-.135.39-.05");
}

.r8ibvzbki {
  stop-color: var(--svg-color--ff9266, #FF9266);
  stop-opacity: 0;
}

.r9gc4bslt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.052 11.403c.327-.29 1.042-.594 1.929-.453");
}

.rcq8rz3rz {
  d: path("M12.426 12.591a.893.893 0 0 0-.86 1.129h1.724a1 1 0 0 0 .033-.236a.9.9 0 0 0-.897-.893");
}

.ri12thbtt {
  stop-color: var(--svg-color--463540, #463540);
}

.rlb4jpb3h {
  stop-color: var(--svg-color--463540, #463540);
  stop-opacity: 0;
}

.ro8jsitoo {
  d: path("m18.581 8.121l-3.08 1.027a1.048 1.048 0 0 0 .47 2.034l3.063-.41z");
}

.rraw6sbsp {
  stop-color: var(--svg-color--ff9266, #FF9266);
}

.rxprtfb0z {
  stop-color: var(--svg-color--407da5, #407DA5);
  stop-opacity: 0;
}

.sk72wrbmx {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m10.837 11.029l.002-.001l.001-.002l.005-.004l.012-.01a2 2 0 0 1 .155-.107c.1-.062.241-.14.42-.21c.36-.143.872-.257 1.494-.159a.534.534 0 1 1-.167 1.055a1.77 1.77 0 0 0-.934.097a1.5 1.5 0 0 0-.3.16l-.009.005a.534.534 0 0 1-.68-.824");
}

.srm_r_guo {
  stop-color: var(--svg-color--ff6792, #FF6792);
}

.sxxb_bc7b {
  d: path("m14.231 13.466l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .521-.7l-.531-1.7c-.114-.377-.646-.377-.766 0");
}

.tet72waca {
  stop-color: var(--svg-color--339ff3, #339FF3);
}

.txm2ysbkn {
  stop-color: var(--svg-color--367bf1, #367BF1);
  stop-opacity: 0;
}

.uck_nmbag {
  stop-color: var(--svg-color--412628, #412628);
  stop-opacity: 0;
}

.uha2wl_iu {
  fill: var(--svg-color--21181b, #21181B);
  d: path("m19.438 7.267l.429.214c.752.373 1.181 1.227 1.02 2.135l-.59 3.043c-.053.314-.26.526-.573.534h-.018s.054-.908.107-1.442c.044-.433-.032-.565-.43-.96c-.214-.214-.375-.534-.375-.855v-.854c0-.267-.215-.48-.43-.534c-.644-.16-1.986-.427-3.919-.427s-3.275.267-3.92.427a.52.52 0 0 0-.429.534v.854c0 .32-.107.64-.376.854l-.16.16c-.216.16-.323.481-.323.748c.054.587.107 1.441.107 1.441l-.049-.001a.634.634 0 0 1-.595-.532l-.59-3.043c-.108-.855.322-1.709 1.073-2.082l.43-.214c.268-.16.537-.374.805-.587l.967-1.014c.59-.534 1.45-.694 2.201-.32c.537.16 1.127.16 1.664 0c.806-.268 1.719-.054 2.363.533l.805.8c.215.268.483.428.805.588");
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.v--lu-jvm {
  cx: 9.862px;
  cy: 13.751px;
  r: 0.996px;
}

.v-nc74bzb {
  d: path("M16.731 12.78c.064.085-.07.189-.22.302c-.151.113-.264.192-.327.107c-.064-.085.007-.245.158-.359c.152-.113.326-.135.39-.05");
}

.v6sq6d8jx {
  d: path("m9.51 13.138l.048.002s-.053-.855-.107-1.442c0-.267.107-.587.322-.747l.161-.16c.269-.214.376-.534.376-.855v-.854a.52.52 0 0 1 .43-.534c.644-.16 1.986-.427 3.919-.427s3.275.267 3.92.427c.214.054.429.267.429.534v.854c0 .32.161.641.376.855c.502.352.471.545.43.96a46 46 0 0 0-.108 1.442h.018l-.266 3.962c-.16 1.771-1.553 3.006-3.213 3.006H13.03c-1.714 0-3.053-1.235-3.213-3.006z");
}

.vauv6-kqu {
  stop-color: var(--svg-color--0f050b, #0F050B);
}

.vjz9_3rja {
  stop-color: var(--svg-color--412531, #412531);
  stop-opacity: 0;
}

.vlk8idp1z {
  d: path("M13.242 13.38c0-.29-.235-.482-.299-.54l-.288.28l.178.36z");
}

.vp_-q7ldm {
  stop-color: var(--svg-color--517cc3, #517CC3);
  stop-opacity: 0;
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.vr7u86b4e {
  stop-color: var(--svg-color--2a1e2f, #2A1E2F);
  stop-opacity: 0;
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.w5_7ycb6b {
  stop-color: var(--svg-color--ff4f4f, #FF4F4F);
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wipobbytx {
  fill: var(--svg-color--2b7fde, #2B7FDE);
  d: path("M7.31 21.414C5.037 23.377 3.6 26.263 3.6 29.48v.463h3.71z");
}

.wke-8-xfb {
  stop-color: var(--svg-color--1f6ce0, #1F6CE0);
}

.wy7e69bbh {
  stop-color: var(--svg-color--c8b3b7, #C8B3B7);
  stop-opacity: 0;
}

.x0fr-9bso {
  fill: var(--svg-color--4b3034, #4B3034);
  d: path("m14.231 13.466l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .521-.7l-.531-1.7c-.114-.377-.646-.377-.766 0");
}

.x3sd7rf5r {
  stop-color: var(--svg-color--362324, #362324);
}

.xtaxaigve {
  stop-color: var(--svg-color--624e4d, #624E4D);
  stop-opacity: 0;
}

.xtiplndwl {
  stop-color: var(--svg-color--3f222f, #3F222F);
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.yidkw-brm {
  stop-color: var(--svg-color--403a3d, #403A3D);
}

.yljcw9bue {
  d: path("M20.283 6.454c-1.215-.028-1.642-.098-2.18-.285v1.737l1.163.479a.86.86 0 0 0 .426.065c.796-.095 2.4-.502 3.076-1.11c.843-.757.785-1.492.715-1.757c-.07-.266-.211-.446-.352-.454c-.14-.007-.26.062-.39.375c-.212.508-.883.985-2.458.95");
}

.yn6hjlequ {
  cx: 22.91px;
  cy: 10.404px;
  r: 1.117px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.ytssyfa7a {
  stop-color: var(--svg-color--40272a, #40272A);
}

.ywa6djbto {
  stop-color: var(--svg-color--2a1e2f, #2A1E2F);
}

.yww6tz8di {
  stop-color: var(--svg-color--624d4b, #624D4B);
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zdar40bkv {
  stop-color: var(--svg-color--145491, #145491);
}

.zi0iv1bfj {
  stop-color: var(--svg-color--438dec, #438DEC);
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

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

</style>
