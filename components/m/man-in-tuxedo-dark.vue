<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iqehyGd)" class="ypm46bm8d"/><path fill="url(#iCixeAd)" class="ypm46bm8d"/><path fill="url(#inZdjlb)" class="ypm46bm8d"/><path fill="url(#ihQGmVb)" class="ypm46bm8d"/><path fill="url(#iTWIrfc)" class="ypm46bm8d"/><path fill="url(#i002cjd)" class="wybie4bpu"/><path fill="url(#irLbDOc)" class="wybie4bpu"/><g filter="url(#iPxzuqb)"><path fill="url(#idvFVTc)" class="wbjjo4b2k"/><path fill="url(#iu9ReAb)" class="wbjjo4b2k"/></g><path fill="url(#idk9juB)" class="s798t3bdo"/><g filter="url(#iMV5geq)"><path fill="url(#i0wn0tp)" class="aoyotcbvb"/><path fill="url(#iHDpKIb)" class="aoyotcbvb"/></g><g filter="url(#iXELc4c)"><path clip-rule="evenodd" class="kggfwm80d"/></g><path fill="url(#i8PbVSc)" class="glvtrfr2v"/><path fill="url(#itJNtOc)" class="glvtrfr2v"/><path fill="url(#i4RfRRb)" class="glvtrfr2v"/><path fill="url(#inxcfCd)" class="glvtrfr2v"/><path fill="url(#i3jdcdd)" class="lntfqwb7g"/><path fill="url(#iMbIGTb)" class="lntfqwb7g"/><path fill="url(#iyTQ8Wc)" class="lntfqwb7g"/><path fill="url(#iB3a55c)" class="lntfqwb7g"/><g filter="url(#itQl1Bd)"><path fill="url(#iTfuFHc)" class="lp_-l2bmu"/></g><g filter="url(#iNKyDHN)"><path fill="url(#iFtZZhb)" class="mkv8j1exr"/></g><path fill="url(#iQh2WWd)" class="mkv8j1exr"/><path fill="url(#irUY0bc)" class="mkv8j1exr"/><path fill="url(#inj2CWb)" class="mkv8j1exr"/><g filter="url(#iIvZ1Vd)"><path class="zr5ogpbvn"/></g><g filter="url(#ioW0gPD)"><circle class="ox_gd9ayz"/></g><g filter="url(#iAbIgYb)"><circle class="aumbfpbca"/></g><g filter="url(#i8eg8gW)"><circle fill="url(#i9uS03c)" class="mcmaclfsj"/></g><g filter="url(#iM73sse)"><circle fill="url(#iGFZpab)" class="gwzuulbku"/></g><rect fill="url(#itkLGre)" class="x320pei4a"/><rect fill="url(#ibjU1sb)" class="x320pei4a"/><rect fill="url(#i8NjNFT)" class="x320pei4a"/><g filter="url(#iZEYcab)"><path fill="url(#i6eH8Mc)" class="vn5g4v4qh"/></g><path fill="url(#iEX3QEe)" class="vn5g4v4qh"/><g filter="url(#iED2hgd)"><path class="aa5rw4bti"/><path fill="url(#iGEzMGd)" class="m13akuj_w"/><path fill="url(#iWaORMy)" class="m13akuj_w"/><path fill="url(#ircJB0c)" class="m13akuj_w"/></g><g filter="url(#iigyAvd)"><circle fill="url(#iyd5Q3Y)" class="grj3g7q3o"/><circle fill="url(#ikE8UFc)" class="grj3g7q3o"/></g><g filter="url(#iB7UlLe)"><circle fill="url(#in8UdzR)" class="r02tz2b0r"/></g><g filter="url(#iWAXEWc)"><circle fill="url(#iJ9evdb)" class="thy8yeb6d"/></g><g filter="url(#i3gvlAd)"><circle fill="url(#ifwi2Ud)" class="jmehufgoz"/><circle fill="url(#iYXm5Cd)" class="jmehufgoz"/></g><g filter="url(#imQZoce)"><circle class="jqyun2zac"/><circle fill="url(#ioyJxae)" class="n46ke_bam"/><circle fill="url(#i7nRsqH)" class="n46ke_bam"/></g><g filter="url(#i6xBu5M)"><path fill="url(#i4lSnAd)" class="y66v8lwde"/><path fill="url(#iguC3Bd)" class="y66v8lwde"/><path fill="url(#i9nFL1c)" class="y66v8lwde"/><path fill="url(#i4Q4Ozb)" class="y66v8lwde"/><path fill="url(#iAIB7Hd)" class="y66v8lwde"/><path fill="url(#iNRFnvc)" class="y66v8lwde"/></g><g filter="url(#i5YhCzF)"><path fill="url(#iDlAGqd)" class="s1lwivuxm"/></g><g filter="url(#i38a5pd)"><path class="oai3qksig"/><path fill="url(#iBfOkNd)" class="z-laafbkb"/><path fill="url(#iHDTXmd)" class="z-laafbkb"/><path fill="url(#iWd6T3c)" class="z-laafbkb"/><path fill="url(#iWCYxre)" class="z-laafbkb"/></g><g filter="url(#irN6TJc)"><path class="aiteubc9i"/></g><g filter="url(#iuU8J4c)"><path class="czm_igbfi"/><path fill="url(#imtPpkb)" class="due5vpb4t"/><path fill="url(#iQRlADd)" class="due5vpb4t"/><path fill="url(#ixtyB7d)" class="due5vpb4t"/><path fill="url(#igt3KCc)" class="due5vpb4t"/></g><path stroke="url(#i4alFoc)" class="i6thhwv-o"/><g filter="url(#iH8rSub)"><path class="bdqdgodyd"/></g><g filter="url(#iT8EIlc)"><path class="vba9bnb1q"/></g><path class="q_xo_k70x"/><path fill="url(#ifwigRc)" class="vccmbtqmb"/><path class="jajfc3b7m"/><g filter="url(#iimEN8A)"><path class="b8de55bok"/><path fill="url(#iGqsTpd)" class="q_mytjzbn"/></g><g filter="url(#ibyDDlY)"><path fill="url(#itnkRYd)" class="z5yl9p_cw"/></g><path class="s88dzp0gq"/><path fill="url(#iyCLvpc)" class="iwyt6eb8e"/><path class="c59u66bmf"/><g filter="url(#iHPxiTd)"><path fill="url(#iIM6YMb)" class="rxsnsjcfw"/></g><g filter="url(#iNED0ve)"><ellipse transform="rotate(-27.914 13.538 9.912)" class="qaet2-o1d"/><ellipse fill="url(#igCKxBF)" transform="rotate(-27.914 13.538 9.912)" class="z4_3iybub"/></g><g filter="url(#i8Cehzi)"><path stroke="url(#iBf4rvc)" class="wpndgxlac"/></g><g filter="url(#irTz0IA)"><path stroke="url(#ioZrdfe)" class="jyg2j8bit"/></g><g filter="url(#ihdkdZd)"><path stroke="url(#iKyJOec)" class="jfjpaytza"/></g><defs><radialGradient id="iqehyGd" cx="0" cy="0" r="1" gradientTransform="matrix(-10.875 0 0 -9.21464 22.408 25.322)" gradientUnits="userSpaceOnUse"><stop class="rp3tqelhu"/><stop offset="1" class="nwb1x8bnq"/></radialGradient><radialGradient id="iCixeAd" cx="0" cy="0" r="1" gradientTransform="rotate(133.011 2.768 10.816)scale(6.32206 7.4475)" gradientUnits="userSpaceOnUse"><stop class="cosmi4y3y"/><stop offset="1" class="fs5qncc9z"/></radialGradient><radialGradient id="inZdjlb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.5 0 0 -14.0625 23.19 23.233)" gradientUnits="userSpaceOnUse"><stop offset=".143" class="b_mjjkbmw"/><stop offset="1" class="tg6m8fb0a"/></radialGradient><radialGradient id="i002cjd" cx="0" cy="0" r="1" gradientTransform="rotate(-91.369 27.245 2.613)scale(11.2456 1.27919)" gradientUnits="userSpaceOnUse"><stop offset=".008" class="uc5leibtb"/><stop offset="1" class="j8ireobfm"/><stop offset="1" class="hj096sb7e"/></radialGradient><radialGradient id="irLbDOc" cx="0" cy="0" r="1" gradientTransform="matrix(.5755 0 0 15.6193 23.099 28.134)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="n_pmxxxsa"/><stop offset="1" class="a_orf89wt"/></radialGradient><radialGradient id="idvFVTc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.9375 4 0 6.69 30.39)" gradientUnits="userSpaceOnUse"><stop class="cm2l5-bra"/><stop offset="1" class="z_d2yzmmm"/></radialGradient><radialGradient id="idk9juB" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55519 1.9364 -1.64284 -1.31942 8.901 18.545)" gradientUnits="userSpaceOnUse"><stop class="aba3uxblf"/><stop offset="1" class="bbv_pqbfl"/></radialGradient><radialGradient id="i0wn0tp" cx="0" cy="0" r="1" gradientTransform="matrix(-.03127 9.1875 -4.7805 -.01627 17.097 22.513)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="geqh5zowk"/><stop offset="1" class="u21vfmbcf"/></radialGradient><radialGradient id="iHDpKIb" cx="0" cy="0" r="1" gradientTransform="rotate(116.36 1.347 13.028)scale(5.4245 1.91221)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="lf_z1-eut"/><stop offset="1" class="safapbcnd"/></radialGradient><radialGradient id="itJNtOc" cx="0" cy="0" r="1" gradientTransform="rotate(-152.488 10.105 8.36)scale(1.16274 3.57827)" gradientUnits="userSpaceOnUse"><stop class="ff2asxc8d"/><stop offset="1" class="c5vb29odw"/></radialGradient><radialGradient id="i4RfRRb" cx="0" cy="0" r="1" gradientTransform="matrix(.79687 -.22754 .55824 1.95507 13.236 18.654)" gradientUnits="userSpaceOnUse"><stop class="vdt_t3f2x"/><stop offset="1" class="v0ftcskkn"/></radialGradient><radialGradient id="iMbIGTb" cx="0" cy="0" r="1" gradientTransform="matrix(1.39062 .34376 -1.28105 5.18228 17.174 18.748)" gradientUnits="userSpaceOnUse"><stop offset=".616" class="fojlwlb9t"/><stop offset="1" class="cyzx27bkq"/></radialGradient><radialGradient id="iyTQ8Wc" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 .35156 -1.56152 -1.21452 17.276 19.388)" gradientUnits="userSpaceOnUse"><stop class="ojp787kql"/><stop offset="1" class="zhh5xs6ht"/></radialGradient><radialGradient id="iFtZZhb" cx="0" cy="0" r="1" gradientTransform="rotate(172.755 6.074 11.859)scale(1.9846 6.9682)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="z58nq_enb"/><stop offset="1" class="v5ndbpbdn"/></radialGradient><radialGradient id="iQh2WWd" cx="0" cy="0" r="1" gradientTransform="matrix(-.91838 1.78314 -4.30906 -2.21931 13.135 16.27)" gradientUnits="userSpaceOnUse"><stop class="ubq14mb-s"/><stop offset="1" class="q0kampb0a"/></radialGradient><radialGradient id="irUY0bc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.94239 -.4885 0 11.747 16.328)" gradientUnits="userSpaceOnUse"><stop offset=".252" class="ihl9krbbc"/><stop offset="1" class="vjj8ifxqk"/></radialGradient><radialGradient id="inj2CWb" cx="0" cy="0" r="1" gradientTransform="matrix(.0919 1.7035 -.36222 .01954 10.658 20.623)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="jfikb2f0k"/><stop offset="1" class="k5y7j_bmf"/></radialGradient><radialGradient id="i9uS03c" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 2.873 16.047)scale(.5552)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="iGFZpab" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 3.492 14.543)scale(.5552)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="ibjU1sb" cx="0" cy="0" r="1" gradientTransform="rotate(142.524 6.248 11.683)scale(2.36263 1.82529)" gradientUnits="userSpaceOnUse"><stop class="m_h8nlt2c"/><stop offset="1" class="ry4ntn_xd"/></radialGradient><radialGradient id="i8NjNFT" cx="0" cy="0" r="1" gradientTransform="rotate(-114.513 13.242 4.328)scale(2.1466 .74211)" gradientUnits="userSpaceOnUse"><stop class="gf3qz39cu"/><stop offset="1" class="gycts7b7d"/></radialGradient><radialGradient id="i6eH8Mc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.39331 0 0 -1.18711 18.294 18.737)" gradientUnits="userSpaceOnUse"><stop class="udzp2zp0e"/><stop offset="1" class="mgsb3vbjk"/></radialGradient><radialGradient id="iEX3QEe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.92504 -.35938 0 18.143 18.112)" gradientUnits="userSpaceOnUse"><stop class="tayze7bgq"/><stop offset="1" class="s41karbfc"/></radialGradient><radialGradient id="iWaORMy" cx="0" cy="0" r="1" gradientTransform="rotate(-144.958 10.44 6.858)scale(1.79393 .6786)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="i8gd1zbwo"/><stop offset="1" class="fj3b0ib3x"/></radialGradient><radialGradient id="ircJB0c" cx="0" cy="0" r="1" gradientTransform="matrix(-.73438 0 0 -1.53003 15.424 18.967)" gradientUnits="userSpaceOnUse"><stop class="p5lz4ubjd"/><stop offset="1" class="tyszy7o8n"/></radialGradient><radialGradient id="iyd5Q3Y" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 4.374 12.586)scale(.89786)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="ikE8UFc" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 -1.4336 1.50732 -.5257 16.174 19.326)" gradientUnits="userSpaceOnUse"><stop offset=".741" class="yl8zw5b_j"/><stop offset="1" class="dh4f0mlhm"/></radialGradient><radialGradient id="in8UdzR" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 9.572 10.69)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="x3sd7rf5r"/><stop offset="1" class="dsm4f-bda"/></radialGradient><radialGradient id="iYXm5Cd" cx="0" cy="0" r="1" gradientTransform="matrix(.82748 -.60254 .68772 .94447 21.138 10.425)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ytssyfa7a"/><stop offset="1" class="fnfe_1psv"/></radialGradient><radialGradient id="ioyJxae" cx="0" cy="0" r="1" gradientTransform="matrix(.82204 -1.51196 .88496 .48114 20.724 11.512)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="lvos55blo"/><stop offset=".916" class="bvmj8ubsx"/></radialGradient><radialGradient id="i7nRsqH" cx="0" cy="0" r="1" gradientTransform="matrix(.25953 .2569 -.33118 .33457 20.765 10.69)" gradientUnits="userSpaceOnUse"><stop class="iqm2531qk"/><stop offset="1" class="n3g96cceg"/></radialGradient><radialGradient id="i9nFL1c" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.11187 -9.65399 0 15.694 10.49)" gradientUnits="userSpaceOnUse"><stop offset=".561" class="g0r5sc7jj"/><stop offset="1" class="i5c5eto6f"/></radialGradient><radialGradient id="i4Q4Ozb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.61023 0 18.344 9.417)" gradientUnits="userSpaceOnUse"><stop class="kb28pwbin"/><stop offset="1" class="uck_nmbag"/></radialGradient><radialGradient id="iAIB7Hd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39218 1.7313 0 13.781 9.384)" gradientUnits="userSpaceOnUse"><stop class="j7sc31byj"/><stop offset="1" class="e9zt2gbxt"/></radialGradient><radialGradient id="iNRFnvc" cx="0" cy="0" r="1" gradientTransform="rotate(-166.409 11.138 7.22)scale(2.92567 1.71902)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="ph-yb3bws"/><stop offset="1" class="az2la2bjr"/></radialGradient><radialGradient id="iBfOkNd" cx="0" cy="0" r="1" gradientTransform="matrix(.79857 -2.95942 1.09745 .29614 20.345 6.58)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="iHDTXmd" cx="0" cy="0" r="1" gradientTransform="matrix(3.82845 .35231 -.18944 2.05853 18.7 4.819)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="iWd6T3c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68076 -2.60303 0 15.996 2.08)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="iWCYxre" cx="0" cy="0" r="1" gradientTransform="matrix(3.07685 -2.2548 3.53253 4.82042 9.54 8.905)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="igt3KCc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19709 -.6332 0 16.323 12.298)" gradientUnits="userSpaceOnUse"><stop class="ldpzz4bsg"/><stop offset="1" class="xtaxaigve"/></radialGradient><radialGradient id="ifwigRc" cx="0" cy="0" r="1" gradientTransform="scale(1.29142 .8119)rotate(90 .875 13.2)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iGqsTpd" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 17.948 10.09)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iyCLvpc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81194 -1.29148 0 13.81 10.007)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="igCKxBF" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.795 -1.543)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iPxzuqb" width="4.081" height="11.683" x="5.07" y="18.236" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.345098 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3325"/></filter><filter id="iMV5geq" width="5.909" height="14.117" x="12.858" y="15.796" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.431373 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3325"/></filter><filter id="iXELc4c" width="7.13" height="5.229" x="12.285" y="16.086" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3325" stdDeviation=".3"/></filter><filter id="itQl1Bd" width="7.239" height="14.645" x="9.195" y="15.779" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3325" stdDeviation=".5"/></filter><filter id="iNKyDHN" width="5.917" height="14.31" x="10.326" y="15.603" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.113725 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3325"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.113725 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3325" result="effect2_innerShadow_4002_3325"/></filter><filter id="iIvZ1Vd" width="6.504" height="14.261" x="15.345" y="15.653" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.372549 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3325"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0901961 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3325" result="effect2_innerShadow_4002_3325"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0901961 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_3325" result="effect3_innerShadow_4002_3325"/></filter><filter id="ioW0gPD" width="2" height="2" x="14.731" y="24.854" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3325" stdDeviation=".25"/></filter><filter id="iAbIgYb" width="2" height="2" x="14.731" y="21.706" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3325" stdDeviation=".25"/></filter><filter id="i8eg8gW" width="1.05" height="1.05" x="15.504" y="25.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3325"/></filter><filter id="iM73sse" width="1.05" height="1.05" x="15.504" y="22.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3325"/></filter><filter id="iZEYcab" width="2.465" height="2.95" x="16.029" y="17.337" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.164706 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3325"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.145098 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3325" result="effect2_innerShadow_4002_3325"/></filter><filter id="iED2hgd" width="2.365" height="2.9" x="13.731" y="17.437" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3325"/></filter><filter id="iigyAvd" width="1.717" height="1.717" x="15.204" y="17.792" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3325"/></filter><filter id="iB7UlLe" width="3.542" height="3.342" x="9.572" y="9.019" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.270588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3325"/></filter><filter id="iWAXEWc" width="2.992" height="2.992" x="9.747" y="9.194" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3325" stdDeviation=".25"/></filter><filter id="i3gvlAd" width="3.592" height="3.592" x="19.095" y="8.769" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.141176 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3325"/></filter><filter id="imQZoce" width="2.992" height="2.992" x="19.27" y="9.194" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3325" stdDeviation=".25"/></filter><filter id="i6xBu5M" width="10.383" height="12.189" x="10.833" y="5.06" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.0509804 0 0 0 0 0.0509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3325"/></filter><filter id="i5YhCzF" width="6.25" height="5.07" x="15.166" y="4.06" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3325" stdDeviation=".5"/></filter><filter id="i38a5pd" width="12.614" height="8.551" x="9.689" y="1.581" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3325"/></filter><filter id="irN6TJc" width="3.262" height="4.184" x="14.126" y="9.535" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3325" stdDeviation=".375"/></filter><filter id="iuU8J4c" width="2.379" height="3.184" x="14.806" y="9.872" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3325" stdDeviation=".125"/></filter><filter id="iH8rSub" width="2.982" height="1.874" x="17.179" y="7.038" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3325"/></filter><filter id="iT8EIlc" width="2.982" height="1.874" x="12.026" y="7.038" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3325"/></filter><filter id="iimEN8A" width=".787" height=".697" x="17.442" y="9.567" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3325" stdDeviation=".05"/></filter><filter id="ibyDDlY" width=".892" height=".914" x="18.282" y="9.643" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3325" stdDeviation=".1"/></filter><filter id="iHPxiTd" width=".987" height="1.041" x="13.836" y="9.579" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3325" stdDeviation=".1"/></filter><filter id="iNED0ve" width=".914" height=".705" x="13.081" y="9.559" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3325" stdDeviation=".05"/></filter><filter id="i8Cehzi" width="2.701" height="1.281" x="17.233" y="7.365" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3325" stdDeviation=".15"/></filter><filter id="irTz0IA" width="2.779" height="1.339" x="12.008" y="7.428" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3325" stdDeviation=".15"/></filter><filter id="ihdkdZd" width="1.008" height="2.271" x="10.825" y="5.499" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3325" stdDeviation=".125"/></filter><linearGradient id="ihQGmVb" x1="23.131" x2="22.971" y1="29.912" y2="29.912" gradientUnits="userSpaceOnUse"><stop class="xg711ab6m"/><stop offset="1" class="eets9_b_s"/></linearGradient><linearGradient id="iTWIrfc" x1="8.858" x2="9.061" y1="29.912" y2="29.912" gradientUnits="userSpaceOnUse"><stop class="az-h38bei"/><stop offset="1" class="fajspub8c"/></linearGradient><linearGradient id="iu9ReAb" x1="9.19" x2="7.596" y1="29.919" y2="29.919" gradientUnits="userSpaceOnUse"><stop class="t1dt_ab6m"/><stop offset="1" class="a519fg_-g"/></linearGradient><linearGradient id="i8PbVSc" x1="14.705" x2="13.268" y1="19.982" y2="16.857" gradientUnits="userSpaceOnUse"><stop class="z7qr8pb7n"/><stop offset="1" class="zynu2nm7a"/></linearGradient><linearGradient id="inxcfCd" x1="15.518" x2="15.209" y1="20.06" y2="19.943" gradientUnits="userSpaceOnUse"><stop class="x1yfsqmdm"/><stop offset="1" class="kqc3y0bzc"/></linearGradient><linearGradient id="i3jdcdd" x1="16.799" x2="18.471" y1="19.998" y2="17.123" gradientUnits="userSpaceOnUse"><stop class="d4kfw7asd"/><stop offset="1" class="ig120dbzq"/></linearGradient><linearGradient id="iB3a55c" x1="16.486" x2="16.713" y1="19.799" y2="19.709" gradientUnits="userSpaceOnUse"><stop class="cof-_sb7w"/><stop offset="1" class="vo3um_bur"/></linearGradient><linearGradient id="iTfuFHc" x1="12.815" x2="12.815" y1="16.779" y2="29.424" gradientUnits="userSpaceOnUse"><stop class="wm85g1cnx"/><stop offset="1" class="b0z0paczy"/></linearGradient><linearGradient id="itkLGre" x1="17.033" x2="14.075" y1="18.388" y2="17.763" gradientUnits="userSpaceOnUse"><stop class="f6zsa320n"/><stop offset="1" class="i35cqvtse"/></linearGradient><linearGradient id="iGEzMGd" x1="15.205" x2="14.838" y1="19.436" y2="18.983" gradientUnits="userSpaceOnUse"><stop class="p5lz4ubjd"/><stop offset="1" class="tyszy7o8n"/></linearGradient><linearGradient id="iJ9evdb" x1="11.243" x2="10.602" y1="10.969" y2="10.969" gradientUnits="userSpaceOnUse"><stop class="fbs6uccsw"/><stop offset="1" class="np-b1wbds"/></linearGradient><linearGradient id="ifwi2Ud" x1="21.853" x2="21.034" y1="9.598" y2="12.136" gradientUnits="userSpaceOnUse"><stop class="o1rzobcjq"/><stop offset="1" class="acjykw8xe"/></linearGradient><linearGradient id="i4lSnAd" x1="20.035" x2="12.391" y1="11.08" y2="12.219" gradientUnits="userSpaceOnUse"><stop class="cdm_o50ho"/><stop offset="1" class="ahguepbtf"/></linearGradient><linearGradient id="iguC3Bd" x1="10.595" x2="12.862" y1="13.778" y2="13.637" gradientUnits="userSpaceOnUse"><stop offset=".283" class="j-n0q842a"/><stop offset="1" class="o-j_7gbpq"/></linearGradient><linearGradient id="iDlAGqd" x1="16.956" x2="25.581" y1="7.699" y2="4.73" gradientUnits="userSpaceOnUse"><stop class="cgqcq-bjq"/><stop offset="1" class="o1syipbau"/></linearGradient><linearGradient id="imtPpkb" x1="15.131" x2="16.07" y1="11.74" y2="11.74" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="iQRlADd" x1="16.935" x2="15.908" y1="12.063" y2="12.048" gradientUnits="userSpaceOnUse"><stop class="yww6tz8di"/><stop offset="1" class="n-4z7qb5o"/></linearGradient><linearGradient id="ixtyB7d" x1="16.19" x2="16.19" y1="12.806" y2="12.232" gradientUnits="userSpaceOnUse"><stop class="xtiplndwl"/><stop offset="1" class="h8-lntwqp"/></linearGradient><linearGradient id="i4alFoc" x1="14.958" x2="15.393" y1="14.422" y2="13.734" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="itnkRYd" x1="18.955" x2="18.641" y1="10.061" y2="10.255" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iIM6YMb" x1="14.554" x2="14.24" y1="10.061" y2="10.255" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iBf4rvc" x1="18.971" x2="18.55" y1="7.92" y2="7.06" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="ioZrdfe" x1="13.661" x2="12.471" y1="7.792" y2="7.292" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iKyJOec" x1="11.329" x2="11.329" y1="5.775" y2="7.934" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-in-tuxedo-dark" /></template>
<style>
.a_orf89wt {
  stop-color: var(--svg-color--4f3b7b, #4F3B7B);
  stop-opacity: 0;
}

.a519fg_-g {
  stop-color: var(--svg-color--463766, #463766);
  stop-opacity: 0;
}

.aa5rw4bti {
  fill: var(--svg-color--543b70, #543B70);
  d: path("m14.133 17.482l1.813 1.25l-1.795 1.26a.246.246 0 0 1-.389-.188c-.04-.791-.04-1.57-.007-2.143a.239.239 0 0 1 .378-.18");
}

.aba3uxblf {
  stop-color: var(--svg-color--4e475c, #4E475C);
}

.acjykw8xe {
  stop-color: var(--svg-color--452a31, #452A31);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.aiteubc9i {
  fill: var(--svg-color--332024, #332024);
  d: path("m15.72 10.568l-.821 1.7c-.102.35.142.7.489.7h.737c.346 0 .59-.355.489-.7l-.499-1.7c-.107-.377-.283-.377-.395 0");
}

.aoyotcbvb {
  d: path("M18.767 16.063a10.3 10.3 0 0 0-2.337-.267h-.86c-.795 0-1.568.09-2.312.261v5.422c0 4.175 1.065 5.972 2.654 8.433h.285c1.59-2.46 2.57-4.258 2.57-8.433z");
}

.aumbfpbca {
  cx: 15.731px;
  cy: 22.706px;
  r: 0.5px;
  fill: var(--svg-color--bfa7d5, #BFA7D5);
}

.az-h38bei {
  stop-color: var(--svg-color--4b3973, #4B3973);
}

.az2la2bjr {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
  stop-opacity: 0;
}

.b_mjjkbmw {
  stop-color: var(--svg-color--8179b0, #8179B0);
}

.b0z0paczy {
  stop-color: var(--svg-color--4f3a77, #4F3A77);
}

.b8de55bok {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.113 9.719c.064.085-.07.189-.22.302c-.152.113-.264.193-.328.107c-.063-.085.008-.245.159-.358s.325-.136.389-.051");
}

.bbv_pqbfl {
  stop-color: var(--svg-color--4e475c, #4E475C);
  stop-opacity: 0;
}

.bdqdgodyd {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m19.719 7.968l-.002-.001l-.002-.002l-.004-.004l-.012-.01a1.3 1.3 0 0 0-.155-.107c-.1-.062-.241-.14-.42-.21a2.84 2.84 0 0 0-1.494-.16a.534.534 0 0 0 .166 1.056c.399-.063.717.01.935.097a1.5 1.5 0 0 1 .3.16l.009.005a.534.534 0 0 0 .679-.824");
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bvmj8ubsx {
  stop-color: var(--svg-color--31191a, #31191A);
}

.c59u66bmf {
  fill: var(--svg-color--000, #000);
  d: path("M14.32 10.423a.51.51 0 0 0-.513-.511a.51.51 0 0 0-.454.747h.905a.5.5 0 0 0 .061-.236");
}

.c5vb29odw {
  stop-color: var(--svg-color--e0c6f9, #E0C6F9);
  stop-opacity: 0;
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

.cm2l5-bra {
  stop-color: var(--svg-color--554181, #554181);
}

.cof-_sb7w {
  stop-color: var(--svg-color--a487bb, #A487BB);
}

.cosmi4y3y {
  stop-color: var(--svg-color--4d3b5d, #4D3B5D);
}

.cyzx27bkq {
  stop-color: var(--svg-color--978394, #978394);
}

.czm_igbfi {
  fill: var(--svg-color--4b3034, #4B3034);
  d: path("m15.613 10.405l-.532 1.7a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .521-.7l-.532-1.7c-.114-.377-.646-.377-.765 0");
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.d4kfw7asd {
  stop-color: var(--svg-color--dabff4, #DABFF4);
}

.dh4f0mlhm {
  stop-color: var(--svg-color--592f4f, #592F4F);
}

.dsm4f-bda {
  stop-color: var(--svg-color--332423, #332423);
}

.due5vpb4t {
  d: path("m15.613 10.405l-.532 1.7a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .521-.7l-.532-1.7c-.114-.377-.646-.377-.765 0");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e9zt2gbxt {
  stop-color: var(--svg-color--351d26, #351D26);
  stop-opacity: 0;
}

.eets9_b_s {
  stop-color: var(--svg-color--4e377f, #4E377F);
  stop-opacity: 0;
}

.f6zsa320n {
  stop-color: var(--svg-color--3a2226, #3A2226);
}

.fajspub8c {
  stop-color: var(--svg-color--4b3973, #4B3973);
  stop-opacity: 0;
}

.fbs6uccsw {
  stop-color: var(--svg-color--281920, #281920);
}

.ff2asxc8d {
  stop-color: var(--svg-color--e0c6f9, #E0C6F9);
}

.fj3b0ib3x {
  stop-color: var(--svg-color--564561, #564561);
  stop-opacity: 0;
}

.fnfe_1psv {
  stop-color: var(--svg-color--40272a, #40272A);
  stop-opacity: 0;
}

.fojlwlb9t {
  stop-color: var(--svg-color--dfc6d4, #DFC6D4);
  stop-opacity: 0;
}

.fs5qncc9z {
  stop-color: var(--svg-color--4d3b5d, #4D3B5D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g0r5sc7jj {
  stop-color: var(--svg-color--3d2138, #3D2138);
  stop-opacity: 0;
}

.geqh5zowk {
  stop-color: var(--svg-color--e8d4fa, #E8D4FA);
}

.gf3qz39cu {
  stop-color: var(--svg-color--3e292a, #3E292A);
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.glvtrfr2v {
  d: path("M14.41 20.283c-1.185-1.235-1.403-3.046-1.367-3.871h2.969l.035 2.223l-.773 1.52c-.148.308-.608.393-.863.128");
}

.grj3g7q3o {
  cx: 16.012px;
  cy: 18.701px;
  r: 0.809px;
}

.gwzuulbku {
  cx: 16.004px;
  cy: 22.573px;
  r: 0.5px;
}

.gycts7b7d {
  stop-color: var(--svg-color--3e292a, #3E292A);
  stop-opacity: 0;
}

.h8-lntwqp {
  stop-color: var(--svg-color--3f222f, #3F222F);
  stop-opacity: 0;
}

.hj096sb7e {
  stop-color: var(--svg-color--6b628b, #6B628B);
}

.i35cqvtse {
  stop-color: var(--svg-color--2e161d, #2E161D);
}

.i5c5eto6f {
  stop-color: var(--svg-color--3d2138, #3D2138);
}

.i6thhwv-o {
  fill: var(--svg-color--2a0219, #2A0219);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.632 13.45c.394.205.864.323 1.364.323c.505 0 .97-.118 1.363-.323a.2.2 0 0 1 .242.04a.19.19 0 0 1 .02.24m-2.989-.28l2.948.253m-2.948-.253a.2.2 0 0 0-.242.041a.19.19 0 0 0-.02.24m.262-.281l-.22.253m3.21.028l-.042-.028m.042.028l-.042-.028m.042.028a1.95 1.95 0 0 1-1.626.869a1.95 1.95 0 0 1-1.626-.869m3.21-.028c-.335.508-.92.847-1.584.847c-.666 0-1.25-.339-1.585-.847m-.041.028l.041-.028m-.041.028l.041-.028");
}

.i8gd1zbwo {
  stop-color: var(--svg-color--564561, #564561);
}

.ig120dbzq {
  stop-color: var(--svg-color--aea5b6, #AEA5B6);
}

.ihl9krbbc {
  stop-color: var(--svg-color--5e5962, #5E5962);
}

.iqm2531qk {
  stop-color: var(--svg-color--352123, #352123);
}

.iwyt6eb8e {
  d: path("M13.807 9.53a.893.893 0 0 0-.86 1.129h1.725a1 1 0 0 0 .032-.236a.9.9 0 0 0-.897-.893");
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j7sc31byj {
  stop-color: var(--svg-color--351d26, #351D26);
}

.j8ireobfm {
  stop-color: var(--svg-color--72659b, #72659B);
}

.jajfc3b7m {
  fill: var(--svg-color--000, #000);
  d: path("M17.667 10.423a.51.51 0 0 1 .512-.511a.51.51 0 0 1 .454.747h-.905a.46.46 0 0 1-.06-.236");
}

.jfikb2f0k {
  stop-color: var(--svg-color--48414f, #48414F);
}

.jfjpaytza {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.458 5.874v.898c-.007.149-.07.482-.258.623");
}

.jmehufgoz {
  cx: 20.766px;
  cy: 10.69px;
  r: 1.671px;
}

.jqyun2zac {
  cx: 20.766px;
  cy: 10.69px;
  r: 0.996px;
  fill: var(--svg-color--463133, #463133);
}

.jyg2j8bit {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.433 8.342c.328-.29 1.043-.595 1.93-.453");
}

.k5y7j_bmf {
  stop-color: var(--svg-color--48414f, #48414F);
  stop-opacity: 0;
}

.kb28pwbin {
  stop-color: var(--svg-color--412628, #412628);
}

.kggfwm80d {
  fill: var(--svg-color--9c80b1, #9C80B1);
  fill-rule: evenodd;
  d: path("M12.889 16.686c-.037.825.18 2.636 1.367 3.871c.255.266.715.18.863-.128l.73-1.436l.731 1.436c.149.308.608.394.863.128c1.186-1.235 1.404-3.046 1.368-3.87z");
}

.kqc3y0bzc {
  stop-color: var(--svg-color--ccb1e3, #CCB1E3);
  stop-opacity: 0;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.ldpzz4bsg {
  stop-color: var(--svg-color--624e4d, #624E4D);
}

.lf_z1-eut {
  stop-color: var(--svg-color--705775, #705775);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lntfqwb7g {
  d: path("M17.598 20.283c1.186-1.235 1.404-3.046 1.367-3.871h-2.968l-.036 2.223l.774 1.52c.148.308.608.393.863.128");
}

.lp_-l2bmu {
  d: path("M11.242 18.346c-.03-1.01.55-1.42.819-1.502l.617-.065v5.373c0 3.575.239 4.662 2.733 7.12l.011.015c.047.082-.05.176-.132.12c-2.75-1.881-4.776-3.354-5.094-8.18a.19.19 0 0 1 .174-.198c.297-.02.56-.044.747-.061a.19.19 0 0 0 .171-.19c-.01-.532-.02-1.533-.046-2.432");
}

.lvos55blo {
  stop-color: var(--svg-color--31191a, #31191A);
  stop-opacity: 0;
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m_h8nlt2c {
  stop-color: var(--svg-color--412727, #412727);
}

.m13akuj_w {
  d: path("m14.133 17.482l1.813 1.25l-1.795 1.26a.246.246 0 0 1-.389-.188c-.04-.791-.04-1.57-.007-2.143a.239.239 0 0 1 .378-.18");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mcmaclfsj {
  cx: 16.004px;
  cy: 25.581px;
  r: 0.5px;
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mgsb3vbjk {
  stop-color: var(--svg-color--462c5b, #462C5B);
}

.mkv8j1exr {
  d: path("M11.709 17.55c-.032-1.095.595-1.538.886-1.626l.668-.07v5.815c0 3.873 1.453 6.261 2.712 8.087c.063.091-.047.201-.138.139c-2.977-2.037-4.916-4.004-5.26-9.227a.203.203 0 0 1 .188-.215c.321-.02.606-.047.808-.066c.107-.01.188-.1.186-.206c-.011-.575-.023-1.659-.05-2.632");
}

.n_pmxxxsa {
  stop-color: var(--svg-color--4f3b7b, #4F3B7B);
}

.n-4z7qb5o {
  stop-color: var(--svg-color--624d4b, #624D4B);
  stop-opacity: 0;
}

.n3g96cceg {
  stop-color: var(--svg-color--352123, #352123);
  stop-opacity: 0;
}

.n46ke_bam {
  cx: 20.766px;
  cy: 10.69px;
  r: 0.996px;
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.np-b1wbds {
  stop-color: var(--svg-color--27161d, #27161D);
}

.nwb1x8bnq {
  stop-color: var(--svg-color--594687, #594687);
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

.oai3qksig {
  fill: var(--svg-color--21181b, #21181B);
  d: path("m20.82 4.206l.429.214c.751.374 1.18 1.228 1.02 2.135l-.59 3.043c-.054.314-.261.526-.573.534h-.019s.054-.908.108-1.441c.043-.434-.032-.566-.43-.961c-.214-.214-.375-.534-.375-.854V6.02c0-.267-.215-.48-.43-.533c-.644-.16-1.986-.428-3.92-.428c-1.932 0-3.274.267-3.919.428a.52.52 0 0 0-.43.533v.855c0 .32-.107.64-.375.854l-.161.16c-.215.16-.322.48-.322.747c.053.587.107 1.442.107 1.442l-.05-.002a.634.634 0 0 1-.594-.532l-.59-3.043c-.108-.854.321-1.708 1.073-2.082l.43-.214a8 8 0 0 0 .805-.587l.966-1.014c.59-.534 1.45-.694 2.202-.32c.537.16 1.127.16 1.664 0c.805-.267 1.718-.054 2.362.533l.806.801c.215.267.483.427.805.587");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ojp787kql {
  stop-color: var(--svg-color--bb9dd6, #BB9DD6);
}

.ox_gd9ayz {
  cx: 15.731px;
  cy: 25.854px;
  r: 0.5px;
  fill: var(--svg-color--c5a9df, #C5A9DF);
}

.p5lz4ubjd {
  stop-color: var(--svg-color--391f50, #391F50);
}

.ph-yb3bws {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.q_mytjzbn {
  d: path("M18.113 9.719c.064.085-.07.189-.22.302c-.152.113-.264.193-.328.107c-.063-.085.008-.245.159-.358s.325-.136.389-.051");
}

.q_xo_k70x {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.386 9.259c.653 0 1.205.45 1.355 1.06a.274.274 0 0 1-.267.34H17.24a.23.23 0 0 1-.227-.272a1.4 1.4 0 0 1 1.372-1.128");
}

.q0kampb0a {
  stop-color: var(--svg-color--422131, #422131);
  stop-opacity: 0;
}

.qaet2-o1d {
  cx: 13.538px;
  cy: 9.912px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r02tz2b0r {
  cx: 11.243px;
  cy: 10.69px;
  r: 1.671px;
}

.rp3tqelhu {
  stop-color: var(--svg-color--63519f, #63519F);
}

.rxsnsjcfw {
  d: path("M14.623 10.318c0-.288-.234-.48-.298-.539l-.288.28l.177.36z");
}

.ry4ntn_xd {
  stop-color: var(--svg-color--412727, #412727);
  stop-opacity: 0;
}

.s1lwivuxm {
  d: path("m19.963 5.06l-3.08 1.027a1.048 1.048 0 0 0 .47 2.034l3.063-.41z");
}

.s41karbfc {
  stop-color: var(--svg-color--5a4772, #5A4772);
  stop-opacity: 0;
}

.s798t3bdo {
  d: path("M8.901 18.236a10.68 10.68 0 0 0-3.831 8.18v3.497H8.9z");
}

.s88dzp0gq {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.6 9.258c-.653 0-1.205.45-1.356 1.06a.274.274 0 0 0 .268.34h2.233a.23.23 0 0 0 .228-.272A1.4 1.4 0 0 0 13.6 9.258");
}

.safapbcnd {
  stop-color: var(--svg-color--937da2, #937DA2);
  stop-opacity: 0;
}

.t1dt_ab6m {
  stop-color: var(--svg-color--463766, #463766);
}

.t1trakjku {
  stop-color: var(--svg-color--635275, #635275);
}

.tayze7bgq {
  stop-color: var(--svg-color--60556d, #60556D);
}

.tg6m8fb0a {
  stop-color: var(--svg-color--8179b0, #8179B0);
  stop-opacity: 0;
}

.thy8yeb6d {
  cx: 11.243px;
  cy: 10.69px;
  r: 0.996px;
}

.tyszy7o8n {
  stop-color: var(--svg-color--391f50, #391F50);
  stop-opacity: 0;
}

.u21vfmbcf {
  stop-color: var(--svg-color--c6b5d5, #C6B5D5);
}

.ubq14mb-s {
  stop-color: var(--svg-color--422131, #422131);
}

.uc5leibtb {
  stop-color: var(--svg-color--796ba6, #796BA6);
}

.uck_nmbag {
  stop-color: var(--svg-color--412628, #412628);
  stop-opacity: 0;
}

.udzp2zp0e {
  stop-color: var(--svg-color--4e3566, #4E3566);
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.v0ftcskkn {
  stop-color: var(--svg-color--866c89, #866C89);
  stop-opacity: 0;
}

.v5ndbpbdn {
  stop-color: var(--svg-color--463856, #463856);
}

.vba9bnb1q {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m12.219 7.968l.001-.001l.002-.002l.004-.004l.012-.01a2 2 0 0 1 .155-.107c.1-.062.242-.14.42-.21a2.84 2.84 0 0 1 1.495-.16a.534.534 0 1 1-.167 1.056a1.77 1.77 0 0 0-.935.097a1.5 1.5 0 0 0-.308.165a.534.534 0 0 1-.68-.824");
}

.vccmbtqmb {
  d: path("M18.179 9.53a.893.893 0 0 1 .86 1.129h-1.725a.897.897 0 0 1 .865-1.129");
}

.vdt_t3f2x {
  stop-color: var(--svg-color--866c89, #866C89);
}

.vjj8ifxqk {
  stop-color: var(--svg-color--5e5962, #5E5962);
  stop-opacity: 0;
}

.vn5g4v4qh {
  d: path("m17.892 17.482l-1.813 1.25l1.795 1.26c.159.11.378.006.388-.188c.041-.791.041-1.57.008-2.143a.239.239 0 0 0-.378-.18");
}

.vo3um_bur {
  stop-color: var(--svg-color--dcc1f4, #DCC1F4);
  stop-opacity: 0;
}

.voa0z2bgu {
  stop-color: var(--svg-color--47305d, #47305D);
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.wbjjo4b2k {
  d: path("M8.901 18.236a10.69 10.69 0 0 0-3.831 8.185v3.498H8.9z");
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wm85g1cnx {
  stop-color: var(--svg-color--4b385d, #4B385D);
}

.wpndgxlac {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.658 7.823c.43-.075 1.27-.054 1.851.398");
}

.wybie4bpu {
  d: path("M23.099 18.236a10.68 10.68 0 0 1 3.831 8.18v3.497H23.1z");
}

.x1yfsqmdm {
  stop-color: var(--svg-color--ab90c0, #AB90C0);
}

.x320pei4a {
  width: 3.875px;
  height: 4.5px;
  x: 14.075px;
  y: 14.287px;
  rx: 1.938px;
}

.x3sd7rf5r {
  stop-color: var(--svg-color--362324, #362324);
}

.xg711ab6m {
  stop-color: var(--svg-color--4e377f, #4E377F);
}

.xtaxaigve {
  stop-color: var(--svg-color--624e4d, #624E4D);
  stop-opacity: 0;
}

.xtiplndwl {
  stop-color: var(--svg-color--3f222f, #3F222F);
}

.y66v8lwde {
  d: path("m10.89 10.077l.05.001s-.054-.854-.107-1.44c0-.268.107-.588.322-.748l.16-.16c.27-.214.377-.534.377-.855v-.854a.52.52 0 0 1 .43-.534c.643-.16 1.986-.427 3.919-.427c1.932 0 3.275.267 3.919.427c.215.054.43.267.43.534v.854c0 .32.16.641.375.855c.503.352.472.545.43.96c-.054.534-.108 1.442-.108 1.442h.019l-.267 3.962c-.16 1.771-1.553 3.006-3.213 3.006h-3.213c-1.714 0-3.053-1.235-3.214-3.006z");
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.yl8zw5b_j {
  stop-color: var(--svg-color--592f4f, #592F4F);
  stop-opacity: 0;
}

.ypm46bm8d {
  d: path("M5.07 26.416c0-5.796 4.7-10.62 10.5-10.62h.86c5.8 0 10.5 4.824 10.5 10.62v3.496H5.07z");
}

.ytssyfa7a {
  stop-color: var(--svg-color--40272a, #40272A);
}

.yww6tz8di {
  stop-color: var(--svg-color--624d4b, #624D4B);
}

.z_d2yzmmm {
  stop-color: var(--svg-color--4b435b, #4B435B);
}

.z-laafbkb {
  d: path("m20.82 4.206l.429.214c.751.374 1.18 1.228 1.02 2.135l-.59 3.043c-.054.314-.261.526-.573.534h-.019s.054-.908.108-1.441c.043-.434-.032-.566-.43-.961c-.214-.214-.375-.534-.375-.854V6.02c0-.267-.215-.48-.43-.533c-.644-.16-1.986-.428-3.92-.428c-1.932 0-3.274.267-3.919.428a.52.52 0 0 0-.43.533v.855c0 .32-.107.64-.375.854l-.161.16c-.215.16-.322.48-.322.747c.053.587.107 1.442.107 1.442l-.05-.002a.634.634 0 0 1-.594-.532l-.59-3.043c-.108-.854.321-1.708 1.073-2.082l.43-.214a8 8 0 0 0 .805-.587l.966-1.014c.59-.534 1.45-.694 2.202-.32c.537.16 1.127.16 1.664 0c.805-.267 1.718-.054 2.362.533l.806.801c.215.267.483.427.805.587");
}

.z4_3iybub {
  cx: 13.538px;
  cy: 9.912px;
  rx: 0.39px;
  ry: 0.197px;
}

.z58nq_enb {
  stop-color: var(--svg-color--5e536c, #5E536C);
}

.z5yl9p_cw {
  d: path("M18.974 10.306a.84.84 0 0 0-.231-.463l-.26.285l.117.228z");
}

.z7qr8pb7n {
  stop-color: var(--svg-color--ba9fd3, #BA9FD3);
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zhh5xs6ht {
  stop-color: var(--svg-color--bb9dd6, #BB9DD6);
  stop-opacity: 0;
}

.zr5ogpbvn {
  fill: var(--svg-color--443452, #443452);
  d: path("M20.316 17.55c.031-1.095-.595-1.538-.887-1.626l-.668-.07v5.815c0 3.873-1.388 6.264-2.648 8.089c-.062.091.047.201.139.139c2.976-2.037 4.851-4.006 5.196-9.229a.203.203 0 0 0-.188-.215c-.321-.02-.607-.047-.809-.066a.204.204 0 0 1-.185-.206c.011-.575.022-1.659.05-2.632");
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

.zynu2nm7a {
  stop-color: var(--svg-color--6b5977, #6B5977);
}

</style>
