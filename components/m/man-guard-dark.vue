<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="iOuiBXb" class="cku-u8b3i"/></defs><g class="ft5dv1b6b"><path fill="url(#iJ0Nzyc)" class="xzot6tb3a"/><path fill="url(#iQ3Jo1d)" class="xzot6tb3a"/><path fill="url(#iu4BL0y)" class="xzot6tb3a"/><path fill="url(#i6kQckA)" class="xzot6tb3a"/><path fill="url(#iEbtPxb)" class="h83slyb1a"/><path fill="url(#imxslwc)" class="h83slyb1a"/><path fill="url(#iAPRHYd)" class="sllpz02jo"/><path fill="url(#iegNxyc)" class="sllpz02jo"/><g filter="url(#iU9HJIG)"><path fill="url(#i6aJFZY)" class="i8us91y_g"/><path fill="url(#izDA0dI)" class="i8us91y_g"/></g><g filter="url(#ievEKzb)"><path class="a7obdqv4r"/><path fill="url(#iDMsGJb)" class="e4qvstbaw"/><path fill="url(#izjH7xz)" class="e4qvstbaw"/></g><g filter="url(#iXHsJDd)"><ellipse transform="rotate(-40.534 9.937 22.243)" class="si-u7d6wp"/></g><ellipse fill="url(#iuxxmBb)" transform="rotate(-40.534 9.886 22.154)" class="fvifkjh5i"/><g filter="url(#iIvozjb)"><ellipse transform="scale(-1 1)rotate(-35.343 23.848 45.555)" class="n11xmqb_x"/></g><ellipse fill="url(#imtwsXc)" transform="scale(-1 1)rotate(-40.534 18.954 40.982)" class="tto44ccna"/><g filter="url(#iHous6b)"><rect fill="url(#icTwalH)" class="qyeoy6a8h"/><rect fill="url(#iFB7LRc)" class="qyeoy6a8h"/><rect fill="url(#izJ86Ne)" class="qyeoy6a8h"/></g><rect fill="url(#izayU8c)" class="kav9ef57d"/><path fill="url(#iYKVIWb)" class="g4mvl20po"/><path fill="url(#iDWpPDG)" class="g4mvl20po"/><g filter="url(#iJfNF4d)"><circle class="d0e6vrb_a"/></g><g filter="url(#iVEiSEc)"><circle class="b4n-hsbxm"/></g><circle fill="url(#itFpnJb)" class="sx6q1cbyi"/><circle fill="url(#iOrZVKb)" class="cad66eb8i"/><g filter="url(#i9vtB1b)"><circle fill="url(#iJMWKve)" class="y8anxkb7y"/></g><g filter="url(#iH0mSdc)"><circle fill="url(#i1zdkhb)" class="rzc2r7sar"/></g><g filter="url(#iXF2kHZ)"><circle fill="url(#iMZaBGH)" class="nue3-zbhn"/><circle fill="url(#isrk5eA)" class="nue3-zbhn"/></g><g filter="url(#iLJJE6r)"><circle class="jvqf56-fi"/><circle fill="url(#i1pOnqd)" class="mjdjf5bim"/><circle fill="url(#isUUz5X)" class="mjdjf5bim"/></g><g filter="url(#idkbAOV)"><path fill="url(#iXcYLNc)" class="ud55lqbwg"/><path fill="url(#iwa9rsd)" class="ud55lqbwg"/><path fill="url(#ieJKNQp)" class="ud55lqbwg"/><path fill="url(#itdOtFd)" class="ud55lqbwg"/><path fill="url(#iP8uted)" class="ud55lqbwg"/><path fill="url(#ihU0pAd)" class="ud55lqbwg"/><path fill="url(#iPoHWve)" class="ud55lqbwg"/></g><g filter="url(#iUremQv)"><path class="tx1v1j5ms"/><path fill="url(#icHVdHc)" class="bxx0_vbbt"/><path fill="url(#iCQL8SE)" class="bxx0_vbbt"/><path fill="url(#idyWGAt)" class="bxx0_vbbt"/><path fill="url(#inD6aXN)" class="bxx0_vbbt"/></g><g filter="url(#iwisJde)"><path class="x0u2ifbcg"/></g><g filter="url(#ibaRIfY)"><path class="t2_mvwo4l"/><path fill="url(#iR9xnFc)" class="tpl37kb9s"/><path fill="url(#iSQYVrk)" class="tpl37kb9s"/><path fill="url(#iW0TjLd)" class="tpl37kb9s"/><path fill="url(#iosNehc)" class="tpl37kb9s"/></g><g filter="url(#ixbRiTu)"><path fill="url(#iDslg7d)" class="zhhemcczf"/></g><g filter="url(#itPAtce)"><use href="#iOuiBXb"/><path stroke="url(#iyMx0Tb)" class="a4oruccyg"/></g><use href="#iOuiBXb"/><path class="sja7w1bgs"/><path fill="url(#i55G5xe)" class="tke_o8blf"/><path class="k_s2w1dct"/><g filter="url(#iyKvhRb)"><path class="kgzhyibaa"/><path fill="url(#iPfgOqd)" class="p3y01yb_j"/></g><g filter="url(#ihgOEhc)"><path fill="url(#iL1z5Lb)" class="hmruq8pha"/></g><path class="sb4ba8u2t"/><path fill="url(#i03QdHb)" class="lr9eev_bw"/><path class="g5h8yv90b"/><g filter="url(#i9aECpd)"><path fill="url(#in1nizc)" class="eyigulw8n"/></g><g filter="url(#iy8i87b)"><ellipse transform="rotate(-27.914 13.474 14.477)" class="uykgqsakj"/><ellipse fill="url(#iDnlkQi)" transform="rotate(-27.914 13.474 14.477)" class="xebz-abtf"/></g><g filter="url(#i3voOEb)"><path fill="url(#il1AcPe)" class="gw4u-ub3u"/><path fill="url(#is0vYcc)" class="gw4u-ub3u"/></g><path fill="url(#iWLVOVc)" class="gw4u-ub3u"/><path fill="url(#i2pBBLt)" class="gw4u-ub3u"/><path fill="url(#isYcgqc)" class="gw4u-ub3u"/><g filter="url(#iYFmwdE)"><path fill="url(#iU1wwRb)" class="vo1nmubta"/><path fill="url(#iqjjYJa)" class="vo1nmubta"/><path fill="url(#iyBJvOb)" class="vo1nmubta"/></g><defs><radialGradient id="iJ0Nzyc" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.71875 -19.3424 0 16 26.989)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="u2-vnsrzx"/><stop offset="1" class="u25v0cb4e"/></radialGradient><radialGradient id="iQ3Jo1d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.6875 0 0 -8.81836 22.928 27.145)" gradientUnits="userSpaceOnUse"><stop offset=".24" class="hztqsacfn"/><stop offset="1" class="g15tcgc_e"/></radialGradient><radialGradient id="iEbtPxb" cx="0" cy="0" r="1" gradientTransform="matrix(1.96876 -8.07812 2.82155 .68765 6.74 29.91)" gradientUnits="userSpaceOnUse"><stop offset=".232" class="y6ictpbdv"/><stop offset="1" class="exer9ybqp"/></radialGradient><radialGradient id="iAPRHYd" cx="0" cy="0" r="1" gradientTransform="rotate(-101.449 24.978 4.726)scale(7.55662 1.96679)" gradientUnits="userSpaceOnUse"><stop class="z2ubpb-up"/><stop offset="1" class="icppbwd3b"/></radialGradient><radialGradient id="iegNxyc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.366 .65507 0 22.942 29.91)" gradientUnits="userSpaceOnUse"><stop offset=".443" class="p9dhe0cfb"/><stop offset="1" class="m7r_2tbtp"/></radialGradient><radialGradient id="i6aJFZY" cx="0" cy="0" r="1" gradientTransform="matrix(1.35937 1.64062 -3.29137 2.72714 9.71 21.208)" gradientUnits="userSpaceOnUse"><stop class="tuvqdtb4j"/><stop offset="1" class="mw-6yhbvl"/></radialGradient><radialGradient id="izDA0dI" cx="0" cy="0" r="1" gradientTransform="matrix(1.78125 1.85937 -.47826 .45816 8.381 22.458)" gradientUnits="userSpaceOnUse"><stop offset=".435" class="aok9j0bwd"/><stop offset="1" class="ul3ws4blr"/></radialGradient><radialGradient id="iDMsGJb" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 .25 -.73637 3.86594 19.569 21.145)" gradientUnits="userSpaceOnUse"><stop offset=".032" class="wcylmi-4x"/><stop offset="1" class="lcybi9bke"/></radialGradient><radialGradient id="izjH7xz" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21875 1.09375 -.16383 -.18256 23.498 22.2)" gradientUnits="userSpaceOnUse"><stop class="dwh48tz1p"/><stop offset="1" class="b5_53rm9x"/></radialGradient><radialGradient id="iuxxmBb" cx="0" cy="0" r="1" gradientTransform="rotate(-169.136 6.388 10.772)scale(1.64141 .91814)" gradientUnits="userSpaceOnUse"><stop offset=".525" class="k5s0mt74t"/><stop offset="1" class="hfobxebps"/></radialGradient><radialGradient id="imtwsXc" cx="0" cy="0" r="1" gradientTransform="matrix(.678 .80592 -1.4278 1.20118 .1 .257)" gradientUnits="userSpaceOnUse"><stop class="w_-x-cc4i"/><stop offset="1" class="xbkp5vbln"/></radialGradient><radialGradient id="icTwalH" cx="0" cy="0" r="1" gradientTransform="matrix(-2.68749 -3.76563 4.9287 -3.51755 18.1 23.91)" gradientUnits="userSpaceOnUse"><stop class="mg6vw6bqp"/><stop offset="1" class="f_x1tcb5s"/></radialGradient><radialGradient id="iFB7LRc" cx="0" cy="0" r="1" gradientTransform="matrix(-.39844 0 0 -.91123 15.538 23.762)" gradientUnits="userSpaceOnUse"><stop offset=".244" class="w_5lucbuv"/><stop offset="1" class="x_olikxjr"/></radialGradient><radialGradient id="izJ86Ne" cx="0" cy="0" r="1" gradientTransform="rotate(112.38 -.17 15.586)scale(1.14905 2.6882)" gradientUnits="userSpaceOnUse"><stop class="ay981bbmw"/><stop offset="1" class="co8373ibr"/></radialGradient><radialGradient id="izayU8c" cx="0" cy="0" r="1" gradientTransform="rotate(51.989 -14.74 27.087)scale(1.72534 2.83656)" gradientUnits="userSpaceOnUse"><stop class="ph3vvlbzk"/><stop offset="1" class="q7xwx5btw"/></radialGradient><radialGradient id="itFpnJb" cx="0" cy="0" r="1" gradientTransform="matrix(-.71875 .59375 -.75915 -.91896 17.85 25.16)" gradientUnits="userSpaceOnUse"><stop class="x2r0w67qw"/><stop offset="1" class="e2y-fbcxj"/></radialGradient><radialGradient id="iOrZVKb" cx="0" cy="0" r="1" gradientTransform="matrix(-.71875 .59375 -.75915 -.91896 17.85 28.16)" gradientUnits="userSpaceOnUse"><stop class="x2r0w67qw"/><stop offset="1" class="e2y-fbcxj"/></radialGradient><radialGradient id="iJMWKve" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 9.508 15.255)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="x3sd7rf5r"/><stop offset="1" class="dsm4f-bda"/></radialGradient><radialGradient id="isrk5eA" cx="0" cy="0" r="1" gradientTransform="matrix(.82748 -.60254 .68772 .94447 21.074 14.99)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ytssyfa7a"/><stop offset="1" class="fnfe_1psv"/></radialGradient><radialGradient id="i1pOnqd" cx="0" cy="0" r="1" gradientTransform="matrix(.82204 -1.51196 .88496 .48114 20.66 16.077)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="lvos55blo"/><stop offset=".916" class="bvmj8ubsx"/></radialGradient><radialGradient id="isUUz5X" cx="0" cy="0" r="1" gradientTransform="matrix(.25953 .2569 -.33118 .33457 20.702 15.255)" gradientUnits="userSpaceOnUse"><stop class="iqm2531qk"/><stop offset="1" class="n3g96cceg"/></radialGradient><radialGradient id="iXcYLNc" cx="0" cy="0" r="1" gradientTransform="rotate(178.041 9.687 8.435)scale(7.33387 8.20007)" gradientUnits="userSpaceOnUse"><stop offset=".24" class="y14k4lb6j"/><stop offset=".848" class="ahguepbtf"/></radialGradient><radialGradient id="ieJKNQp" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.11187 -9.65399 0 15.63 15.056)" gradientUnits="userSpaceOnUse"><stop offset=".561" class="g0r5sc7jj"/><stop offset="1" class="i5c5eto6f"/></radialGradient><radialGradient id="itdOtFd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.61023 0 18.28 13.982)" gradientUnits="userSpaceOnUse"><stop class="kb28pwbin"/><stop offset="1" class="uck_nmbag"/></radialGradient><radialGradient id="iP8uted" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39218 1.7313 0 13.718 13.949)" gradientUnits="userSpaceOnUse"><stop class="j7sc31byj"/><stop offset="1" class="e9zt2gbxt"/></radialGradient><radialGradient id="ihU0pAd" cx="0" cy="0" r="1" gradientTransform="rotate(-166.409 11.378 9.506)scale(2.92567 1.71902)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="ph-yb3bws"/><stop offset="1" class="az2la2bjr"/></radialGradient><radialGradient id="icHVdHc" cx="0" cy="0" r="1" gradientTransform="matrix(.79857 -2.95942 1.09745 .29614 20.28 11.145)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="iCQL8SE" cx="0" cy="0" r="1" gradientTransform="matrix(3.82845 .35231 -.18944 2.05853 18.637 9.383)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="idyWGAt" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68076 -2.60303 0 15.932 6.646)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="inD6aXN" cx="0" cy="0" r="1" gradientTransform="matrix(3.07685 -2.2548 3.53253 4.82042 9.477 13.47)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="iosNehc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19709 -.6332 0 16.26 16.863)" gradientUnits="userSpaceOnUse"><stop class="ldpzz4bsg"/><stop offset="1" class="xtaxaigve"/></radialGradient><radialGradient id="i55G5xe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.03986 1.32558 0 18.113 15.135)" gradientUnits="userSpaceOnUse"><stop offset=".676" class="yc-28ccmm"/><stop offset="1" class="zh79qu0oc"/></radialGradient><radialGradient id="iPfgOqd" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 17.884 14.657)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i03QdHb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.03991 1.32565 0 13.745 15.135)" gradientUnits="userSpaceOnUse"><stop offset=".676" class="yc-28ccmm"/><stop offset="1" class="zh79qu0oc"/></radialGradient><radialGradient id="iDnlkQi" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.01 .771)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iWLVOVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -12.3535 18.2706 0 15.953 14.155)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="guwslmx9m"/><stop offset="1" class="csva0fh9x"/></radialGradient><radialGradient id="i2pBBLt" cx="0" cy="0" r="1" gradientTransform="rotate(-179.736 10.798 2.33)scale(6.78132 1.9151)" gradientUnits="userSpaceOnUse"><stop class="ak4i8vy1v"/><stop offset="1" class="d0nv29baz"/></radialGradient><radialGradient id="iyBJvOb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.46875 -.51569 0 21.381 16.27)" gradientUnits="userSpaceOnUse"><stop class="qqll8tbvj"/><stop offset="1" class="i1pxvjzop"/></radialGradient><filter id="iU9HJIG" width="4.755" height="3.491" x="8.464" y="20.061" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.172549 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2839"/></filter><filter id="ievEKzb" width="4.705" height="3.591" x="18.753" y="19.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.172549 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2839"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.0666667 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2839" result="effect2_innerShadow_4002_2839"/></filter><filter id="iXHsJDd" width="2.189" height="2.153" x="8.842" y="21.167" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2839" stdDeviation=".25"/></filter><filter id="iIvozjb" width="1.692" height="1.595" x="21.111" y="21.394" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2839" stdDeviation=".125"/></filter><filter id="iHous6b" width="7.744" height="9.694" x="12.072" y="14.826" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.384314 0 0 0 0 0.47451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2839"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.384314 0 0 0 0 0.47451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2839" result="effect2_innerShadow_4002_2839"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.172549 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_2839" result="effect3_innerShadow_4002_2839"/></filter><filter id="iJfNF4d" width="2.09" height="2.09" x="16.395" y="24.399" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2839" stdDeviation=".25"/></filter><filter id="iVEiSEc" width="2.09" height="2.09" x="16.395" y="27.399" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2839" stdDeviation=".25"/></filter><filter id="i9vtB1b" width="3.542" height="3.342" x="9.508" y="13.584" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.270588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2839"/></filter><filter id="iH0mSdc" width="2.992" height="2.992" x="9.683" y="13.759" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2839" stdDeviation=".25"/></filter><filter id="iXF2kHZ" width="3.592" height="3.592" x="19.03" y="13.334" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.141176 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2839"/></filter><filter id="iLJJE6r" width="2.992" height="2.992" x="19.206" y="13.759" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2839" stdDeviation=".25"/></filter><filter id="idkbAOV" width="10.883" height="12.689" x="10.269" y="9.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.0509804 0 0 0 0 0.0509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2839"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.65" dy="-.65"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0941176 0 0 0 0 0.121569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2839" result="effect2_innerShadow_4002_2839"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.65"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.172549 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_2839" result="effect3_innerShadow_4002_2839"/></filter><filter id="iUremQv" width="12.614" height="8.551" x="9.625" y="6.146" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2839"/></filter><filter id="iwisJde" width="3.262" height="4.184" x="14.062" y="14.1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2839" stdDeviation=".375"/></filter><filter id="ibaRIfY" width="2.379" height="3.184" x="14.742" y="14.437" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2839" stdDeviation=".125"/></filter><filter id="ixbRiTu" width="2.379" height="3.184" x="14.742" y="14.353" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2839" stdDeviation=".125"/></filter><filter id="itPAtce" width="3.621" height="1.474" x="14.121" y="17.842" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2839" stdDeviation=".05"/></filter><filter id="iyKvhRb" width=".787" height=".697" x="17.378" y="14.132" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2839" stdDeviation=".05"/></filter><filter id="ihgOEhc" width=".892" height=".914" x="18.219" y="14.207" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2839" stdDeviation=".1"/></filter><filter id="i9aECpd" width=".987" height="1.041" x="13.773" y="14.144" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2839" stdDeviation=".1"/></filter><filter id="iy8i87b" width=".914" height=".705" x="13.017" y="14.124" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2839" stdDeviation=".05"/></filter><filter id="i3voOEb" width="13.655" height="12.317" x="9.076" y="1.839" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.203922 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2839"/></filter><filter id="iYFmwdE" width="10.882" height="7.996" x="10.499" y="14.055" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.635294 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2839"/></filter><linearGradient id="iu4BL0y" x1="9.026" x2="9.233" y1="29.911" y2="29.911" gradientUnits="userSpaceOnUse"><stop class="g-00mbcgn"/><stop offset="1" class="tvzw53atw"/></linearGradient><linearGradient id="i6kQckA" x1="22.975" x2="22.827" y1="29.911" y2="29.911" gradientUnits="userSpaceOnUse"><stop offset=".118" class="yacpd-mqw"/><stop offset="1" class="m2jbcqdpu"/></linearGradient><linearGradient id="imxslwc" x1="9.397" x2="8.084" y1="29.739" y2="29.739" gradientUnits="userSpaceOnUse"><stop class="s2ol_bbam"/><stop offset="1" class="hm-si4p_s"/></linearGradient><linearGradient id="iYKVIWb" x1="15.984" x2="15.984" y1="23.197" y2="29.911" gradientUnits="userSpaceOnUse"><stop class="ty59qw5cn"/><stop offset="1" class="jwfvhhlnv"/></linearGradient><linearGradient id="iDWpPDG" x1="16.479" x2="16.147" y1="27.271" y2="27.271" gradientUnits="userSpaceOnUse"><stop class="z_332kbzw"/><stop offset="1" class="v6fzn4zbl"/></linearGradient><linearGradient id="i1zdkhb" x1="11.179" x2="10.538" y1="15.534" y2="15.534" gradientUnits="userSpaceOnUse"><stop class="fbs6uccsw"/><stop offset="1" class="np-b1wbds"/></linearGradient><linearGradient id="iMZaBGH" x1="21.789" x2="20.97" y1="14.163" y2="16.701" gradientUnits="userSpaceOnUse"><stop class="o1rzobcjq"/><stop offset="1" class="acjykw8xe"/></linearGradient><linearGradient id="iwa9rsd" x1="10.531" x2="12.798" y1="18.343" y2="18.202" gradientUnits="userSpaceOnUse"><stop offset=".283" class="j-n0q842a"/><stop offset="1" class="o-j_7gbpq"/></linearGradient><linearGradient id="iPoHWve" x1="15.96" x2="15.96" y1="13.908" y2="16.252" gradientUnits="userSpaceOnUse"><stop offset=".048" class="fpg6z3u3b"/><stop offset="1" class="ho7pyab5n"/></linearGradient><linearGradient id="iR9xnFc" x1="15.067" x2="16.006" y1="16.305" y2="16.305" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="iSQYVrk" x1="16.871" x2="15.844" y1="16.628" y2="16.613" gradientUnits="userSpaceOnUse"><stop class="yww6tz8di"/><stop offset="1" class="n-4z7qb5o"/></linearGradient><linearGradient id="iW0TjLd" x1="16.126" x2="16.126" y1="17.37" y2="16.797" gradientUnits="userSpaceOnUse"><stop class="xtiplndwl"/><stop offset="1" class="h8-lntwqp"/></linearGradient><linearGradient id="iDslg7d" x1="15.932" x2="16.18" y1="14.603" y2="15.945" gradientUnits="userSpaceOnUse"><stop class="k61ttub0l"/><stop offset="1" class="p6ukb41qm"/></linearGradient><linearGradient id="iyMx0Tb" x1="14.894" x2="15.329" y1="18.987" y2="18.299" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="iL1z5Lb" x1="18.891" x2="18.577" y1="14.626" y2="14.82" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="in1nizc" x1="14.49" x2="14.176" y1="14.626" y2="14.82" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="il1AcPe" x1="19.866" x2="12.584" y1="11.708" y2="11.708" gradientUnits="userSpaceOnUse"><stop class="j8rdzr3lb"/><stop offset=".554" class="h5foydtlz"/><stop offset="1" class="roy3-sbpo"/></linearGradient><linearGradient id="is0vYcc" x1="9.709" x2="12.428" y1="11.989" y2="11.989" gradientUnits="userSpaceOnUse"><stop class="bamb_e30h"/><stop offset="1" class="szoje-bkc"/></linearGradient><linearGradient id="isYcgqc" x1="16.538" x2="16.538" y1="14.155" y2="13.88" gradientUnits="userSpaceOnUse"><stop class="ip1t-iw4f"/><stop offset="1" class="l0ic_xblz"/></linearGradient><linearGradient id="iU1wwRb" x1="21.116" x2="15.022" y1="18.489" y2="18.489" gradientUnits="userSpaceOnUse"><stop class="it4bksbcb"/><stop offset="1" class="twe7w31pl"/></linearGradient><linearGradient id="iqjjYJa" x1="15.941" x2="15.941" y1="13.927" y2="16.029" gradientUnits="userSpaceOnUse"><stop class="x-67tmbrg"/><stop offset="1" class="bkz397hyg"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-guard-dark" /></template>
<style>
.a4oruccyg {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.932 18.388a3 3 0 0 1-1.387-.329c-.137-.07-.284.085-.198.21c.335.508.92.846 1.585.846s1.249-.338 1.584-.846c.087-.13-.06-.28-.198-.21a3 3 0 0 1-1.386.33Z");
}

.a7obdqv4r {
  fill: var(--svg-color--554b59, #554B59);
  d: path("M20.046 20.16c1.364.419 2.538 1.308 3.179 1.936a.46.46 0 0 1-.011.659l-.65.65a.523.523 0 0 1-.704.02a12.3 12.3 0 0 0-3.107-1.858z");
}

.acjykw8xe {
  stop-color: var(--svg-color--452a31, #452A31);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.ak4i8vy1v {
  stop-color: var(--svg-color--686070, #686070);
}

.aok9j0bwd {
  stop-color: var(--svg-color--4b4551, #4B4551);
}

.ay981bbmw {
  stop-color: var(--svg-color--452139, #452139);
}

.az2la2bjr {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
  stop-opacity: 0;
}

.b4n-hsbxm {
  cx: 17.439px;
  cy: 28.444px;
  r: 0.545px;
  fill: var(--svg-color--f6265e, #F6265E);
}

.b5_53rm9x {
  stop-color: var(--svg-color--5e5864, #5E5864);
  stop-opacity: 0;
}

.bamb_e30h {
  stop-color: var(--svg-color--4d4c50, #4D4C50);
}

.bkz397hyg {
  stop-color: var(--svg-color--c7aed9, #C7AED9);
  stop-opacity: 0;
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bvmj8ubsx {
  stop-color: var(--svg-color--31191a, #31191A);
}

.bxx0_vbbt {
  d: path("m20.755 8.771l.43.214c.751.373 1.18 1.228 1.02 2.135l-.59 3.043c-.053.314-.261.526-.573.534h-.019s.054-.908.108-1.441c.043-.434-.032-.566-.43-.961c-.214-.214-.375-.534-.375-.855v-.854c0-.267-.215-.48-.43-.534c-.644-.16-1.986-.427-3.92-.427c-1.932 0-3.274.267-3.919.428a.52.52 0 0 0-.43.533v.854c0 .32-.107.641-.375.855l-.161.16c-.215.16-.322.48-.322.747c.053.587.107 1.441.107 1.441l-.049-.001a.634.634 0 0 1-.595-.532l-.59-3.043c-.108-.854.321-1.709 1.073-2.082l.43-.214a8 8 0 0 0 .805-.587l.966-1.014c.59-.534 1.45-.694 2.202-.32c.537.16 1.127.16 1.664 0c.805-.268 1.718-.054 2.362.533l.806.801c.215.267.483.427.805.587");
}

.cad66eb8i {
  cx: 17.494px;
  cy: 28.374px;
  r: 0.545px;
}

.cku-u8b3i {
  fill: var(--svg-color--2a0219, #2A0219);
  d: path("M15.932 18.388a3 3 0 0 1-1.387-.329c-.137-.07-.284.085-.198.21c.335.508.92.846 1.585.846s1.249-.338 1.584-.846c.087-.13-.06-.28-.198-.21a3 3 0 0 1-1.386.33");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.co8373ibr {
  stop-color: var(--svg-color--452139, #452139);
  stop-opacity: 0;
}

.csva0fh9x {
  stop-color: var(--svg-color--403947, #403947);
}

.d0e6vrb_a {
  cx: 17.439px;
  cy: 25.444px;
  r: 0.545px;
  fill: var(--svg-color--f6265e, #F6265E);
}

.d0nv29baz {
  stop-color: var(--svg-color--686070, #686070);
  stop-opacity: 0;
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.dsm4f-bda {
  stop-color: var(--svg-color--332423, #332423);
}

.dwh48tz1p {
  stop-color: var(--svg-color--5e5864, #5E5864);
}

.e2y-fbcxj {
  stop-color: var(--svg-color--fca239, #FCA239);
}

.e4qvstbaw {
  d: path("M20.046 20.16c1.364.419 2.538 1.308 3.179 1.936a.46.46 0 0 1-.011.659l-.65.65a.523.523 0 0 1-.704.02a12.3 12.3 0 0 0-3.107-1.858z");
}

.e9zt2gbxt {
  stop-color: var(--svg-color--351d26, #351D26);
  stop-opacity: 0;
}

.exer9ybqp {
  stop-color: var(--svg-color--b13b50, #B13B50);
}

.eyigulw8n {
  d: path("M14.56 14.883c0-.288-.235-.48-.299-.539l-.288.28l.177.36z");
}

.f_x1tcb5s {
  stop-color: var(--svg-color--482949, #482949);
}

.fbs6uccsw {
  stop-color: var(--svg-color--281920, #281920);
}

.fnfe_1psv {
  stop-color: var(--svg-color--40272a, #40272A);
  stop-opacity: 0;
}

.fpg6z3u3b {
  stop-color: var(--svg-color--30171f, #30171F);
}

.ft5dv1b6b {
  fill: none;
}

.fvifkjh5i {
  cx: 9.886px;
  cy: 22.154px;
  rx: 0.641px;
  ry: 0.524px;
}

.g-00mbcgn {
  stop-color: var(--svg-color--c2254a, #C2254A);
}

.g0r5sc7jj {
  stop-color: var(--svg-color--3d2138, #3D2138);
  stop-opacity: 0;
}

.g15tcgc_e {
  stop-color: var(--svg-color--ff6085, #FF6085);
  stop-opacity: 0;
}

.g4mvl20po {
  d: path("M15.49 23.203v6.708h.989v-6.714a2 2 0 0 1-.409.042h-.203q-.194 0-.377-.036");
}

.g5h8yv90b {
  fill: var(--svg-color--000, #000);
  d: path("M14.255 14.988a.51.51 0 0 0-.512-.511a.51.51 0 0 0-.454.747h.905a.5.5 0 0 0 .061-.236");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.guwslmx9m {
  stop-color: var(--svg-color--403947, #403947);
  stop-opacity: 0;
}

.gw4u-ub3u {
  d: path("M10.31 14.155c-.278-.016-.842-.08-1.054-.728c-.11-.37.082-.779.143-.91l.004-.008l.02-.04c.061-.121.152-.298-.02-.578c-.193-.313-.375-.615-.045-1.257c.207-.405.093-.652-.032-.875c-.183-.327-.166-.604 0-.938c.07-.143.173-.275.173-.472c0-.198-.07-.335-.141-.474c-.074-.143-.148-.289-.148-.504c0-.23.084-.398.161-.554c.066-.133.128-.257.128-.402c0-.129-.06-.24-.125-.364c-.094-.178-.201-.38-.164-.69c.071-.59.537-.787.756-.879l.02-.008c.21-.089.364-.163.452-.58c.046-.215.132-.502.293-.663a1.06 1.06 0 0 1 .791-.3c.257.007.535-.03.752-.254c.217-.225.458-.413.699-.453s.471.014.725.144c.281.145.567.07.705-.035c.34-.262.718-.32 1.158-.141c.18.072.295.112.394.112c.098 0 .214-.04.393-.112c.44-.18.819-.12 1.159.141a.68.68 0 0 0 .704.035c.254-.13.484-.184.725-.144s.483.228.7.453s.494.261.75.253a1.06 1.06 0 0 1 .793.301c.16.161.246.448.292.663c.088.417.243.491.452.58l.02.008c.219.092.685.288.756.878c.038.31-.07.513-.164.69c-.065.124-.125.236-.125.365c0 .145.062.269.128.402c.078.156.161.324.161.554c0 .215-.074.36-.147.504a.94.94 0 0 0-.105.466c0 .528.496.742.176 1.422c-.125.223-.324.455-.117.86c.33.641.193.955 0 1.268c-.171.28-.081.457-.02.577l.02.041l.005.009c.06.13.252.54.142.909c-.212.649-.775.712-1.054.728z");
}

.h5foydtlz {
  stop-color: var(--svg-color--4b3c5b, #4B3C5B);
}

.h8-lntwqp {
  stop-color: var(--svg-color--3f222f, #3F222F);
  stop-opacity: 0;
}

.h83slyb1a {
  d: path("M9.058 29.91h-3.63a9.98 9.98 0 0 1 3.63-7.354z");
}

.hfobxebps {
  stop-color: var(--svg-color--dcb144, #DCB144);
}

.hm-si4p_s {
  stop-color: var(--svg-color--c9345b, #C9345B);
  stop-opacity: 0;
}

.hmruq8pha {
  d: path("M18.91 14.87a.84.84 0 0 0-.231-.462l-.26.285l.117.228z");
}

.ho7pyab5n {
  stop-color: var(--svg-color--30171f, #30171F);
  stop-opacity: 0;
}

.hztqsacfn {
  stop-color: var(--svg-color--ff6085, #FF6085);
}

.i1pxvjzop {
  stop-color: var(--svg-color--f6dcf7, #F6DCF7);
  stop-opacity: 0;
}

.i5c5eto6f {
  stop-color: var(--svg-color--3d2138, #3D2138);
}

.i8us91y_g {
  d: path("M11.926 20.16c-1.363.419-2.538 1.308-3.179 1.936a.46.46 0 0 0 .011.659l.65.65a.523.523 0 0 0 .705.02a12.3 12.3 0 0 1 3.106-1.858z");
}

.icppbwd3b {
  stop-color: var(--svg-color--e34c67, #E34C67);
}

.ip1t-iw4f {
  stop-color: var(--svg-color--462659, #462659);
}

.iqm2531qk {
  stop-color: var(--svg-color--352123, #352123);
}

.it4bksbcb {
  stop-color: var(--svg-color--dfc6ed, #DFC6ED);
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j7sc31byj {
  stop-color: var(--svg-color--351d26, #351D26);
}

.j8rdzr3lb {
  stop-color: var(--svg-color--5d536a, #5D536A);
}

.jvqf56-fi {
  cx: 20.702px;
  cy: 15.255px;
  r: 0.996px;
  fill: var(--svg-color--463133, #463133);
}

.jwfvhhlnv {
  stop-color: var(--svg-color--d8bbeb, #D8BBEB);
}

.k_s2w1dct {
  fill: var(--svg-color--000, #000);
  d: path("M17.603 14.988a.51.51 0 0 1 .512-.511a.51.51 0 0 1 .454.747h-.905a.46.46 0 0 1-.06-.236");
}

.k5s0mt74t {
  stop-color: var(--svg-color--cc981a, #CC981A);
}

.k61ttub0l {
  stop-color: var(--svg-color--341b21, #341B21);
}

.kav9ef57d {
  width: 4.141px;
  height: 5.141px;
  x: 13.898px;
  y: 18.098px;
  rx: 1.969px;
}

.kb28pwbin {
  stop-color: var(--svg-color--412628, #412628);
}

.kgzhyibaa {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.049 14.284c.064.085-.07.189-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.245.159-.358c.151-.114.325-.136.389-.051");
}

.l0ic_xblz {
  stop-color: var(--svg-color--462659, #462659);
  stop-opacity: 0;
}

.lcybi9bke {
  stop-color: var(--svg-color--513f4e, #513F4E);
  stop-opacity: 0;
}

.ldpzz4bsg {
  stop-color: var(--svg-color--624e4d, #624E4D);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lr9eev_bw {
  d: path("M13.744 14.095a.893.893 0 0 0-.861 1.129h1.725a1 1 0 0 0 .033-.236a.9.9 0 0 0-.898-.893");
}

.lvos55blo {
  stop-color: var(--svg-color--31191a, #31191A);
  stop-opacity: 0;
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m2jbcqdpu {
  stop-color: var(--svg-color--fc356b, #FC356B);
  stop-opacity: 0;
}

.m7r_2tbtp {
  stop-color: var(--svg-color--ee5076, #EE5076);
  stop-opacity: 0;
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mg6vw6bqp {
  stop-color: var(--svg-color--5d4364, #5D4364);
}

.mjdjf5bim {
  cx: 20.702px;
  cy: 15.255px;
  r: 0.996px;
}

.mw-6yhbvl {
  stop-color: var(--svg-color--382834, #382834);
}

.n-4z7qb5o {
  stop-color: var(--svg-color--624d4b, #624D4B);
  stop-opacity: 0;
}

.n11xmqb_x {
  fill: var(--svg-color--3e3138, #3E3138);
  rx: 0.641px;
  ry: 0.494px;
}

.n3g96cceg {
  stop-color: var(--svg-color--352123, #352123);
  stop-opacity: 0;
}

.np-b1wbds {
  stop-color: var(--svg-color--27161d, #27161D);
}

.nue3-zbhn {
  cx: 20.702px;
  cy: 15.255px;
  r: 1.671px;
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.p3y01yb_j {
  d: path("M18.049 14.284c.064.085-.07.189-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.245.159-.358c.151-.114.325-.136.389-.051");
}

.p6ukb41qm {
  stop-color: var(--svg-color--341b21, #341B21);
  stop-opacity: 0;
}

.p9dhe0cfb {
  stop-color: var(--svg-color--e11c59, #E11C59);
}

.ph-yb3bws {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
}

.ph3vvlbzk {
  stop-color: var(--svg-color--35161f, #35161F);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.q7xwx5btw {
  stop-color: var(--svg-color--462b32, #462B32);
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qqll8tbvj {
  stop-color: var(--svg-color--f6dcf7, #F6DCF7);
}

.qyeoy6a8h {
  width: 7.594px;
  height: 9.594px;
  x: 12.172px;
  y: 14.927px;
  rx: 3.797px;
}

.roy3-sbpo {
  stop-color: var(--svg-color--393341, #393341);
}

.rzc2r7sar {
  cx: 11.179px;
  cy: 15.255px;
  r: 0.996px;
}

.s2ol_bbam {
  stop-color: var(--svg-color--ac394e, #AC394E);
}

.sb4ba8u2t {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.536 13.823c-.653 0-1.205.45-1.356 1.06a.274.274 0 0 0 .268.34h2.233a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.373-1.129");
}

.si-u7d6wp {
  cx: 9.937px;
  cy: 22.243px;
  fill: var(--svg-color--321f22, #321F22);
  rx: 0.641px;
  ry: 0.524px;
}

.sja7w1bgs {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.322 13.823c.653 0 1.205.45 1.356 1.06a.274.274 0 0 1-.268.34h-2.233a.23.23 0 0 1-.227-.272a1.4 1.4 0 0 1 1.372-1.128");
}

.sllpz02jo {
  d: path("M22.942 29.91h3.63a9.98 9.98 0 0 0-3.63-7.354z");
}

.sx6q1cbyi {
  cx: 17.494px;
  cy: 25.374px;
  r: 0.545px;
}

.szoje-bkc {
  stop-color: var(--svg-color--393341, #393341);
  stop-opacity: 0;
}

.t2_mvwo4l {
  fill: var(--svg-color--4b3034, #4B3034);
  d: path("m15.549 14.97l-.532 1.7a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .521-.7l-.532-1.7c-.114-.377-.646-.377-.765 0");
}

.tke_o8blf {
  d: path("M18.115 14.095a.893.893 0 0 1 .86 1.128H17.25a.897.897 0 0 1 .865-1.128");
}

.tpl37kb9s {
  d: path("m15.549 14.97l-.532 1.7a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .521-.7l-.532-1.7c-.114-.377-.646-.377-.765 0");
}

.tto44ccna {
  rx: 0.641px;
  ry: 0.524px;
}

.tuvqdtb4j {
  stop-color: var(--svg-color--454048, #454048);
}

.tvzw53atw {
  stop-color: var(--svg-color--c2254a, #C2254A);
  stop-opacity: 0;
}

.twe7w31pl {
  stop-color: var(--svg-color--c9b0d8, #C9B0D8);
}

.tx1v1j5ms {
  fill: var(--svg-color--21181b, #21181B);
  d: path("m20.755 8.771l.43.214c.751.373 1.18 1.228 1.02 2.135l-.59 3.043c-.053.314-.261.526-.573.534h-.019s.054-.908.108-1.441c.043-.434-.032-.566-.43-.961c-.214-.214-.375-.534-.375-.855v-.854c0-.267-.215-.48-.43-.534c-.644-.16-1.986-.427-3.92-.427c-1.932 0-3.274.267-3.919.428a.52.52 0 0 0-.43.533v.854c0 .32-.107.641-.375.855l-.161.16c-.215.16-.322.48-.322.747c.053.587.107 1.441.107 1.441l-.049-.001a.634.634 0 0 1-.595-.532l-.59-3.043c-.108-.854.321-1.709 1.073-2.082l.43-.214a8 8 0 0 0 .805-.587l.966-1.014c.59-.534 1.45-.694 2.202-.32c.537.16 1.127.16 1.664 0c.805-.268 1.718-.054 2.362.533l.806.801c.215.267.483.427.805.587");
}

.ty59qw5cn {
  stop-color: var(--svg-color--dbb8dd, #DBB8DD);
}

.u2-vnsrzx {
  stop-color: var(--svg-color--f73c71, #F73C71);
}

.u25v0cb4e {
  stop-color: var(--svg-color--d6274f, #D6274F);
}

.uck_nmbag {
  stop-color: var(--svg-color--412628, #412628);
  stop-opacity: 0;
}

.ud55lqbwg {
  d: path("m10.827 14.642l.05.001s-.055-.854-.108-1.441c0-.267.107-.587.322-.747l.161-.16c.268-.214.376-.534.376-.855v-.854a.52.52 0 0 1 .43-.534c.644-.16 1.986-.427 3.919-.427s3.275.267 3.92.427c.214.054.429.267.429.534v.854c0 .32.16.64.375.854c.503.353.472.546.43.961a46 46 0 0 0-.107 1.442h.018l-.266 3.962c-.161 1.771-1.553 3.006-3.214 3.006H14.35c-1.714 0-3.053-1.235-3.214-3.006z");
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.ul3ws4blr {
  stop-color: var(--svg-color--4b4551, #4B4551);
  stop-opacity: 0;
}

.uykgqsakj {
  cx: 13.474px;
  cy: 14.477px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.v6fzn4zbl {
  stop-color: var(--svg-color--eacceb, #EACCEB);
  stop-opacity: 0;
}

.vo1nmubta {
  d: path("m10.5 14.155l.12 3.518c.082 2.425 2.07 4.379 4.497 4.379h1.677c2.44 0 4.436-1.977 4.498-4.416l.09-3.481h-.909l-.12 3.48c-.049 1.898-1.661 3.487-3.56 3.487h-1.676c-1.887 0-3.489-1.597-3.553-3.483l-.09-3.484z");
}

.w_-x-cc4i {
  stop-color: var(--svg-color--ffff50, #FFFF50);
}

.w_5lucbuv {
  stop-color: var(--svg-color--4a2e4f, #4A2E4F);
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.wcylmi-4x {
  stop-color: var(--svg-color--513f4e, #513F4E);
}

.x_olikxjr {
  stop-color: var(--svg-color--4a2e4f, #4A2E4F);
  stop-opacity: 0;
}

.x-67tmbrg {
  stop-color: var(--svg-color--b593cf, #B593CF);
}

.x0u2ifbcg {
  fill: var(--svg-color--332024, #332024);
  d: path("m15.656 15.133l-.821 1.701c-.102.35.142.7.488.7h.738c.346 0 .59-.355.489-.7l-.499-1.701c-.107-.377-.283-.377-.395 0");
}

.x2r0w67qw {
  stop-color: var(--svg-color--fff153, #FFF153);
}

.x3sd7rf5r {
  stop-color: var(--svg-color--362324, #362324);
}

.xbkp5vbln {
  stop-color: var(--svg-color--f6cf1c, #F6CF1C);
}

.xebz-abtf {
  cx: 13.474px;
  cy: 14.477px;
  rx: 0.39px;
  ry: 0.197px;
}

.xtaxaigve {
  stop-color: var(--svg-color--624e4d, #624E4D);
  stop-opacity: 0;
}

.xtiplndwl {
  stop-color: var(--svg-color--3f222f, #3F222F);
}

.xzot6tb3a {
  d: path("M5.428 29.91h21.144c-.19-5.355-4.591-9.64-9.994-9.64h-1.156c-5.403 0-9.805 4.285-9.994 9.64");
}

.y14k4lb6j {
  stop-color: var(--svg-color--523330, #523330);
}

.y6ictpbdv {
  stop-color: var(--svg-color--e43669, #E43669);
}

.y8anxkb7y {
  cx: 11.179px;
  cy: 15.255px;
  r: 1.671px;
}

.yacpd-mqw {
  stop-color: var(--svg-color--fc356b, #FC356B);
}

.yc-28ccmm {
  stop-color: var(--svg-color--6c4a41, #6C4A41);
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.ytssyfa7a {
  stop-color: var(--svg-color--40272a, #40272A);
}

.yww6tz8di {
  stop-color: var(--svg-color--624d4b, #624D4B);
}

.z_332kbzw {
  stop-color: var(--svg-color--eacceb, #EACCEB);
}

.z2ubpb-up {
  stop-color: var(--svg-color--ff5c85, #FF5C85);
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zh79qu0oc {
  stop-color: var(--svg-color--452d27, #452D27);
}

.zhhemcczf {
  d: path("m15.549 14.885l-.532 1.702a.54.54 0 0 0 .521.7h.787c.37 0 .63-.356.521-.7l-.532-1.702c-.114-.376-.646-.376-.765 0");
}

</style>
