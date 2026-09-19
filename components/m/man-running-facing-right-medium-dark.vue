<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iJee6Kb)" transform="scale(-1 1)rotate(-4.337 80.242 265.278)" class="z8jy9-b3h"/><path fill="url(#iSBG9Qb)" transform="scale(-1 1)rotate(-4.337 80.242 265.278)" class="z8jy9-b3h"/><path fill="url(#iXK82th)" transform="scale(-1 1)rotate(-4.337 80.242 265.278)" class="z8jy9-b3h"/><g filter="url(#i4ll9Ub)"><path class="ime0cp0_o"/><path fill="url(#ihe6t3R)" class="juw4f_u-e"/><path fill="url(#iXb9xLe)" class="juw4f_u-e"/><path fill="url(#ikwxgbc)" class="juw4f_u-e"/></g><path fill="url(#iGoNA5c)" class="prk_spbyi"/><path fill="url(#ifgGiCb)" class="prk_spbyi"/><path fill="url(#i6fy4Ne)" class="prk_spbyi"/><path fill="url(#iwx76ae)" class="prk_spbyi"/><path fill="url(#iluzTqe)" class="prk_spbyi"/><path fill="url(#ixraqne)" class="prk_spbyi"/><g filter="url(#i7tE2wd)"><path stroke="url(#iAEoGgd)" class="diygx-k0o"/></g><circle fill="url(#iBzEled)" transform="matrix(-1 0 0 1 10.426 11.383)" class="mftxrcb_l"/><g filter="url(#ivQ6kbe)"><path clip-rule="evenodd" class="v6nrgabwc"/></g><path class="ak8t8kb4p"/><path fill="url(#iircEbc)" class="u2y29_b_y"/><path fill="url(#itOBVLd)" class="u2y29_b_y"/><path fill="url(#i0cbMqc)" class="u2y29_b_y"/><rect transform="matrix(-1 0 0 1 27.262 9.968)" class="jwv936b1l"/><rect fill="url(#iqtkM4c)" transform="matrix(-1 0 0 1 27.262 9.968)" class="x0ov6mb_y"/><rect fill="url(#iidqk4c)" transform="matrix(-1 0 0 1 27.262 9.968)" class="x0ov6mb_y"/><path fill="url(#iSRybHb)" class="ardo6lwye"/><path fill="url(#iCjz1Ad)" class="ardo6lwye"/><path fill="url(#i0EnV7d)" class="ardo6lwye"/><path fill="url(#i6oCEzc)" class="ardo6lwye"/><g filter="url(#itoZ2PL)"><path class="eb0u3-b5q"/><path fill="url(#i32jd2b)" class="nxjjhjnjz"/><path fill="url(#iccN8ae)" class="nxjjhjnjz"/></g><path fill="url(#iWKhdAa)" class="nxjjhjnjz"/><g filter="url(#iY3MBzc)"><path class="feuh1-etw"/><path fill="url(#ijCXfWC)" class="ottdm216w"/><path fill="url(#iqaaLbe)" class="ottdm216w"/></g><g filter="url(#i2v1Geb)"><path class="h6mz3ebpk"/></g><path class="x67arib7h"/><path fill="url(#i3Szipd)" class="fbic__gsw"/><path fill="url(#iGEg5Aa)" class="fbic__gsw"/><path fill="url(#ixtk7nb)" class="fbic__gsw"/><g filter="url(#iXoACjc)"><path class="fz20k0zvy"/><path fill="url(#iGj1dxb)" class="deqixdb1j"/></g><path class="av_fgi-cw"/><path fill="url(#i22ofOb)" class="xfghwx9_b"/><path fill="url(#i7mNMGb)" class="xfghwx9_b"/><path fill="url(#izRktWb)" class="xfghwx9_b"/><path fill="url(#ijFWumb)" class="xfghwx9_b"/><path fill="url(#i26ZrvJ)" class="xfghwx9_b"/><g filter="url(#iUgNrvc)"><path class="sbh75zbmf"/></g><path fill="url(#iK9eI5c)" class="bbd75qi9i"/><g filter="url(#id4XCad)"><path fill="url(#iz1ayfe)" class="rf-7bwj8w"/><path fill="url(#iPydaub)" class="rf-7bwj8w"/><path fill="url(#ihLW9De)" class="rf-7bwj8w"/><path fill="url(#iycIrub)" class="rf-7bwj8w"/></g><g filter="url(#ifzZIJc)"><path fill="url(#iPCHYnd)" class="prsf6ka-g"/><path fill="url(#i0ZGzUc)" class="prsf6ka-g"/><path fill="url(#iNjSOge)" class="prsf6ka-g"/></g><path fill="url(#iaWRpCb)" class="jca5wxbec"/><path fill="url(#i0EfHbb)" class="jca5wxbec"/><path fill="url(#iOT2XKS)" class="jca5wxbec"/><path clip-rule="evenodd" class="p8j_4ij_b"/><path class="x4krg7bkn"/><path fill="url(#iwHqOdc)" class="no96t0c8o"/><path fill="url(#iY27UIK)" class="am7diwv3o"/><ellipse fill="url(#ipECBte)" transform="scale(-1 1)rotate(24.61 -22.833 -45.84)" class="m1l7k9jve"/><g filter="url(#iTDDXjb)"><path clip-rule="evenodd" class="k0c7kq1cg"/></g><defs><radialGradient id="iJee6Kb" cx="0" cy="0" r="1" gradientTransform="matrix(-.05152 -2.21336 1.59858 -.0372 1.708 2.01)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="e41njl2ig"/><stop offset="1" class="gu98zdb9e"/></radialGradient><radialGradient id="iSBG9Qb" cx="0" cy="0" r="1" gradientTransform="matrix(-.53617 .66448 -.89991 -.72614 2.062 .438)" gradientUnits="userSpaceOnUse"><stop class="tiwfp2v4s"/><stop offset="1" class="ol9lfys-r"/></radialGradient><radialGradient id="iXK82th" cx="0" cy="0" r="1" gradientTransform="matrix(.01105 -.86884 .23985 .00305 .214 2.413)" gradientUnits="userSpaceOnUse"><stop class="dcxl663ne"/><stop offset="1" class="jtmedjbua"/><stop offset="1" class="hl-6b4apm"/></radialGradient><radialGradient id="ihe6t3R" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21002 -.125 .20081 -1.94388 28.465 11.638)" gradientUnits="userSpaceOnUse"><stop class="cn_0g9b1k"/><stop offset="1" class="ml97gccia"/></radialGradient><radialGradient id="iXb9xLe" cx="0" cy="0" r="1" gradientTransform="matrix(.28127 3.65625 -2.22242 .17097 20.348 11.366)" gradientUnits="userSpaceOnUse"><stop class="l_6ml5z1n"/><stop offset="1" class="h1tnakbtm"/></radialGradient><radialGradient id="ikwxgbc" cx="0" cy="0" r="1" gradientTransform="matrix(.59375 .3125 -.5067 .96275 26.662 10.93)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="leghz1bmd"/><stop offset="1" class="f0qe2eg6v"/></radialGradient><radialGradient id="ifgGiCb" cx="0" cy="0" r="1" gradientTransform="matrix(1.22254 -5.1875 2.96948 .69982 17.606 16.91)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="s6seicc8w"/><stop offset="1" class="yjn3q9srk"/></radialGradient><radialGradient id="i6fy4Ne" cx="0" cy="0" r="1" gradientTransform="matrix(-.5907 5.65625 -2.14876 -.2244 20.575 12.502)" gradientUnits="userSpaceOnUse"><stop class="kve1gec_d"/><stop offset="1" class="r0_3lybww"/></radialGradient><radialGradient id="iwx76ae" cx="0" cy="0" r="1" gradientTransform="matrix(2.40625 .71875 -1.45293 4.86416 14.891 13.315)" gradientUnits="userSpaceOnUse"><stop class="wpy2jtqib"/><stop offset="1" class="u6kcyml4j"/></radialGradient><radialGradient id="iluzTqe" cx="0" cy="0" r="1" gradientTransform="rotate(-155.706 9.976 3.557)scale(1.76241 2.14376)" gradientUnits="userSpaceOnUse"><stop offset=".238" class="p5n-ewbqx"/><stop offset="1" class="q11m-vutr"/></radialGradient><radialGradient id="ixraqne" cx="0" cy="0" r="1" gradientTransform="matrix(1.03125 .60937 -.64188 1.08628 18.323 10.597)" gradientUnits="userSpaceOnUse"><stop class="gjadyfboc"/><stop offset="1" class="asuvzebmi"/></radialGradient><radialGradient id="iBzEled" cx="0" cy="0" r="1" gradientTransform="matrix(1.01953 .46875 -.49222 1.07057 0 .714)" gradientUnits="userSpaceOnUse"><stop class="ztpt-rb1m"/><stop offset=".906" class="cirfawbak"/></radialGradient><radialGradient id="itOBVLd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 .1875 -.31663 -2.16355 19.328 9.91)" gradientUnits="userSpaceOnUse"><stop class="wtj81mbzy"/><stop offset="1" class="k870jjb1v"/></radialGradient><radialGradient id="i0cbMqc" cx="0" cy="0" r="1" gradientTransform="matrix(.875 .42187 -.65917 1.36718 14.641 8.394)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="gz3om4b5e"/><stop offset="1" class="s9nkndynh"/></radialGradient><radialGradient id="iqtkM4c" cx="0" cy="0" r="1" gradientTransform="matrix(.4375 -.74756 1.05666 .6184 .538 1.324)" gradientUnits="userSpaceOnUse"><stop class="gsodk4bkm"/><stop offset="1" class="wy6du73xp"/></radialGradient><radialGradient id="iidqk4c" cx="0" cy="0" r="1" gradientTransform="matrix(.5586 0 0 1.24803 -.02 .662)" gradientUnits="userSpaceOnUse"><stop class="qp5z_0beh"/><stop offset="1" class="qdq50sbvg"/></radialGradient><radialGradient id="i0EnV7d" cx="0" cy="0" r="1" gradientTransform="matrix(4.65317 9.34098 -2.71885 1.35439 17.916 21.083)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="aw8qrjbpp"/><stop offset="1" class="c3lo31rgp"/></radialGradient><radialGradient id="i6oCEzc" cx="0" cy="0" r="1" gradientTransform="matrix(1.82682 4.82558 -1.33887 .50686 18.089 21.048)" gradientUnits="userSpaceOnUse"><stop class="htnxfn4ti"/><stop offset="1" class="ufy99pbfg"/></radialGradient><radialGradient id="iWKhdAa" cx="0" cy="0" r="1" gradientTransform="rotate(-161.643 16.288 11.687)scale(.94262 1.56541)" gradientUnits="userSpaceOnUse"><stop class="rmzq06bzd"/><stop offset="1" class="n1b4mhj1w"/></radialGradient><radialGradient id="ijCXfWC" cx="0" cy="0" r="1" gradientTransform="matrix(-.53907 1.6172 -.97015 -.32338 12.099 19.88)" gradientUnits="userSpaceOnUse"><stop class="p9sn1rbpn"/><stop offset="1" class="y4vc4jbhj"/></radialGradient><radialGradient id="iqaaLbe" cx="0" cy="0" r="1" gradientTransform="rotate(122.005 1.308 14.303)scale(1.32665 3.03372)" gradientUnits="userSpaceOnUse"><stop class="scsc9dbso"/><stop offset="1" class="b00wh9z0c"/></radialGradient><radialGradient id="iGj1dxb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.4375 4.75 -1.7011 -.87293 14.985 18.722)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="v1sha93vg"/><stop offset="1" class="kg-rnkb9f"/></radialGradient><radialGradient id="i22ofOb" cx="0" cy="0" r="1" gradientTransform="rotate(128.66 4.968 12.815)scale(4.60225 17.5153)" gradientUnits="userSpaceOnUse"><stop offset=".554" class="j96xv6b5h"/><stop offset="1" class="osaguabiz"/></radialGradient><radialGradient id="i7mNMGb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.01137 -2.1808 7.2546 -3.3644 17.464 22.42)" gradientUnits="userSpaceOnUse"><stop class="sq7_rccwx"/><stop offset="1" class="n8gqlhnrc"/></radialGradient><radialGradient id="izRktWb" cx="0" cy="0" r="1" gradientTransform="matrix(2.05437 1.35958 -1.29324 1.95413 13.956 16.763)" gradientUnits="userSpaceOnUse"><stop class="gewgt1jbg"/><stop offset="1" class="roa1y3bvy"/></radialGradient><radialGradient id="i26ZrvJ" cx="0" cy="0" r="1" gradientTransform="rotate(-154.573 11.166 6.44)scale(2.11071 .26513)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="c6vpnsb1w"/><stop offset="1" class="j23k_cb2p"/></radialGradient><radialGradient id="iK9eI5c" cx="0" cy="0" r="1" gradientTransform="rotate(151.587 10.357 6.033)scale(.54183 .76481)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="n304-r4kd"/><stop offset=".684" class="uk3jx7nau"/></radialGradient><radialGradient id="iPydaub" cx="0" cy="0" r="1" gradientTransform="matrix(.84375 -.04687 .05715 1.0287 18.675 5.707)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="jijo4-b9s"/><stop offset="1" class="ni_rkbnps"/></radialGradient><radialGradient id="ihLW9De" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.1875 1.40625 0 21.572 6.895)" gradientUnits="userSpaceOnUse"><stop offset=".163" class="dd9hd6bwg"/><stop offset="1" class="aw2d6h33n"/></radialGradient><radialGradient id="iycIrub" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39063 -.60919 0 20.743 5.754)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="jynvl5b3k"/><stop offset="1" class="b-jom1b0d"/></radialGradient><radialGradient id="iPCHYnd" cx="0" cy="0" r="1" gradientTransform="matrix(3.4375 3.125 -3.54355 3.8979 16.8 3.045)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="lgum6kbvi"/><stop offset="1" class="ri9ygtemw"/></radialGradient><radialGradient id="i0ZGzUc" cx="0" cy="0" r="1" gradientTransform="matrix(-.39452 2.68273 -1.18513 -.17428 16.907 3.795)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="x4tqf8rmd"/><stop offset="1" class="m5kggdiwk"/></radialGradient><radialGradient id="iNjSOge" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5 -.09374 .18396 -2.94358 22.097 3.66)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="bd_cirbzn"/><stop offset="1" class="u8iayhb4j"/></radialGradient><radialGradient id="iaWRpCb" cx="0" cy="0" r="1" gradientTransform="rotate(-163.812 9.847 1.451)scale(.75656 .36927)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="rovuy_e_s"/><stop offset="1" class="r42gxacgx"/></radialGradient><radialGradient id="i0EfHbb" cx="0" cy="0" r="1" gradientTransform="rotate(100.843 7.248 10.443)scale(1.20119 1.25169)" gradientUnits="userSpaceOnUse"><stop offset=".716" class="mkaeqfx_v"/><stop offset="1" class="bw90kjbqe"/></radialGradient><radialGradient id="iwHqOdc" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 0 0 -.53125 21.038 5.782)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="iY27UIK" cx="0" cy="0" r="1" gradientTransform="matrix(-.25 0 0 -.54102 21.206 5.803)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><linearGradient id="iGoNA5c" x1="17.606" x2="17.606" y1="8.347" y2="17.466" gradientUnits="userSpaceOnUse"><stop class="s-mmaacyl"/><stop offset="1" class="b108nwbbf"/></linearGradient><linearGradient id="iAEoGgd" x1="26.396" x2="23.459" y1="11.405" y2="13.03" gradientUnits="userSpaceOnUse"><stop class="ff-2ozx2x"/><stop offset="1" class="qzzesm9df"/></linearGradient><linearGradient id="iircEbc" x1="15.485" x2="16.891" y1="10.941" y2="8.503" gradientUnits="userSpaceOnUse"><stop class="cx6lx2x4e"/><stop offset="1" class="sbq6vwbkt"/></linearGradient><linearGradient id="iSRybHb" x1="19.547" x2="22.922" y1="20.003" y2="28.128" gradientUnits="userSpaceOnUse"><stop class="t_zpwqbmw"/><stop offset="1" class="yknew8brm"/></linearGradient><linearGradient id="iCjz1Ad" x1="24.155" x2="22.88" y1="24.667" y2="25.15" gradientUnits="userSpaceOnUse"><stop class="lx_kelx-v"/><stop offset="1" class="ql6p40bwg"/></linearGradient><linearGradient id="i32jd2b" x1="26.102" x2="25.946" y1="28.964" y2="28.651" gradientUnits="userSpaceOnUse"><stop class="vrnt79u8g"/><stop offset="1" class="z-p3-w_an"/></linearGradient><linearGradient id="iccN8ae" x1="23.86" x2="24.516" y1="29.362" y2="28.925" gradientUnits="userSpaceOnUse"><stop class="sted03b1z"/><stop offset="1" class="ubkqlww9x"/></linearGradient><linearGradient id="i3Szipd" x1="5.86" x2="5.36" y1="19.558" y2="20.722" gradientUnits="userSpaceOnUse"><stop offset=".024" class="ruyfycb4r"/><stop offset="1" class="vuvc8_ujh"/></linearGradient><linearGradient id="iGEg5Aa" x1="5.86" x2="5.096" y1="22.519" y2="21.713" gradientUnits="userSpaceOnUse"><stop class="clpaphbux"/><stop offset="1" class="gei07kbgq"/></linearGradient><linearGradient id="ixtk7nb" x1="4.078" x2="4.485" y1="21.8" y2="21.94" gradientUnits="userSpaceOnUse"><stop offset=".213" class="e2g34f-cy"/><stop offset="1" class="vx88q5bse"/></linearGradient><linearGradient id="ijFWumb" x1="18.828" x2="18.141" y1="17.19" y2="18.122" gradientUnits="userSpaceOnUse"><stop class="hv04c4bjr"/><stop offset="1" class="j2u_3dtev"/></linearGradient><linearGradient id="iz1ayfe" x1="18.988" x2="21.85" y1="6.45" y2="6.622" gradientUnits="userSpaceOnUse"><stop class="co18c5bwy"/><stop offset="1" class="kj_uw-bok"/></linearGradient><linearGradient id="iOT2XKS" x1="19.001" x2="18.72" y1="5.625" y2="5.703" gradientUnits="userSpaceOnUse"><stop class="q_8osebjr"/><stop offset="1" class="ay5mqacxq"/></linearGradient><linearGradient id="ipECBte" x1="-.007" x2=".179" y1=".05" y2=".11" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><filter id="i4ll9Ub" width="10.979" height="5.402" x="17.486" y="9.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.305882 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_10097"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.6"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.462745 0 0 0 0 0.239216 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_10097" result="effect2_innerShadow_2_10097"/></filter><filter id="i7tE2wd" width="4.059" height="2.455" x="23.015" y="10.767" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_10097" stdDeviation=".1"/></filter><filter id="ivQ6kbe" width="10.118" height="6.174" x="7.605" y="6.622" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.8"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.486275 0 0 0 0 0.282353 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_10097"/></filter><filter id="itoZ2PL" width="4.813" height="3.178" x="23.453" y="27.058" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.286275 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_10097"/></filter><filter id="iY3MBzc" width="9.043" height="4.345" x="5.922" y="19.159" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.486275 0 0 0 0 0.266667 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_10097"/></filter><filter id="i2v1Geb" width="7.552" height="2.409" x="5.693" y="19.695" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_10097" stdDeviation=".2"/></filter><filter id="iXoACjc" width="3.978" height="6.092" x="11.71" y="15.465" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.458824 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_10097"/></filter><filter id="iUgNrvc" width="5.797" height="4.302" x="7.42" y="8.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_10097" stdDeviation=".25"/></filter><filter id="id4XCad" width="4.443" height="5.249" x="17.407" y="3.509" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.278431 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_10097"/></filter><filter id="ifzZIJc" width="6.391" height="5.479" x="15.992" y="1.864" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.211765 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_10097"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.168627 0 0 0 0 0.0862745 0 0 0 0 0.105882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_10097" result="effect2_innerShadow_2_10097"/></filter><filter id="iTDDXjb" width="1.117" height=".649" x="20.129" y="4.435" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.219608 0 0 0 0 0.168627 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_10097"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-running-facing-right-medium-dark" /></template>
<style>
.ak8t8kb4p {
  fill: var(--svg-color--379ffb, #379FFB);
  d: path("m14.151 10l1.324-2.717l2.764 1.322a1.483 1.483 0 0 1-1.255 2.687z");
}

.am7diwv3o {
  d: path("m20.906 5.803l-.004-.072c0-.186.078-.336.175-.336s.176.15.176.336l-.004.072z");
}

.ardo6lwye {
  d: path("M22.985 21.91c.515 1.76 1.457 4.933 1.547 5.218l-1.075 1.39c-.86-1.614-2.641-4.986-2.93-5.66c-.242-.566-.566-.71-.808-.855l-1.34-.805l1.973-2.472c.12.093.594.444 1.32 1.074c.735.636 1.169 1.617 1.313 2.11");
}

.asuvzebmi {
  stop-color: var(--svg-color--529cea, #529CEA);
  stop-opacity: 0;
}

.av_fgi-cw {
  fill: var(--svg-color--918996, #918996);
  d: path("M14.649 14.23s4.125 3.03 6.023 4.703a17.7 17.7 0 0 1-2.544 2.853a.92.92 0 0 1-1.23-.012c-.92-.81-1.78-1.601-2.616-2.552c-1.375-1.563-1.047-2.663-.766-3.313c.244-.562.857-1.354 1.133-1.68");
}

.aw2d6h33n {
  stop-color: var(--svg-color--9a7468, #9A7468);
  stop-opacity: 0;
}

.aw8qrjbpp {
  stop-color: var(--svg-color--804d5f, #804D5F);
}

.ay5mqacxq {
  stop-color: var(--svg-color--825c51, #825C51);
  stop-opacity: 0;
}

.b-jom1b0d {
  stop-color: var(--svg-color--845a4e, #845A4E);
  stop-opacity: 0;
}

.b00wh9z0c {
  stop-color: var(--svg-color--74446c, #74446C);
  stop-opacity: 0;
}

.b108nwbbf {
  stop-color: var(--svg-color--337fe1, #337FE1);
}

.bbd75qi9i {
  d: path("M22.046 5.973a1 1 0 0 1-.258-.457h-.18v1.125c.215.137.523.115.614-.09c.078-.176.02-.394-.176-.578");
}

.bd_cirbzn {
  stop-color: var(--svg-color--514342, #514342);
}

.bw90kjbqe {
  stop-color: var(--svg-color--7b4845, #7B4845);
}

.c3lo31rgp {
  stop-color: var(--svg-color--804d5f, #804D5F);
  stop-opacity: 0;
}

.c6vpnsb1w {
  stop-color: var(--svg-color--9c959a, #9C959A);
}

.cirfawbak {
  stop-color: var(--svg-color--733f61, #733F61);
}

.clpaphbux {
  stop-color: var(--svg-color--5a418f, #5A418F);
}

.cn_0g9b1k {
  stop-color: var(--svg-color--9b7467, #9B7467);
}

.co18c5bwy {
  stop-color: var(--svg-color--825756, #825756);
}

.cx6lx2x4e {
  stop-color: var(--svg-color--2c6bd5, #2C6BD5);
}

.dcxl663ne {
  stop-color: var(--svg-color--916b63, #916B63);
}

.dd9hd6bwg {
  stop-color: var(--svg-color--9d726c, #9D726C);
}

.deqixdb1j {
  d: path("m14.774 21.558l.914-2.149l-1.793-3.844c-1.258 1.754-1.739 2.665-1.98 3.055c-.269.433-.298.922.062 1.281c.637.57 2.13 1.342 2.797 1.657");
}

.diygx-k0o {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m26.787 11.147l-3.485 1.695");
}

.e2g34f-cy {
  stop-color: var(--svg-color--5e5d8f, #5E5D8F);
}

.e41njl2ig {
  stop-color: var(--svg-color--8a675c, #8A675C);
}

.eb0u3-b5q {
  fill: var(--svg-color--534e8c, #534E8C);
  d: path("m26.961 27.058l-2.46.07l-1.048 1.39l.624 1.184a.25.25 0 0 0 .335.106l3.41-1.749c.197-.1.317-.328.197-.513c-.247-.381-.74-.488-1.058-.488");
}

.f0qe2eg6v {
  stop-color: var(--svg-color--70433c, #70433C);
  stop-opacity: 0;
}

.fbic__gsw {
  d: path("m5.263 19.574l1.234.473l.16 1.749a45 45 0 0 1-1.715 1.634c-.428.387-.844.467-1.146.432c-.23-.026-.312-.276-.23-.492l1.374-3.65a.25.25 0 0 1 .323-.146");
}

.feuh1-etw {
  fill: var(--svg-color--805b4e, #805B4E);
  d: path("m14.063 22.62l.652-1.277l-2.613-1.684l-.344 1.016l-5.836-.688l.625 1.774c1.422.445 4.465 1.407 5.504 1.68c1.074.28 1.848-.434 2.012-.82");
}

.ff-2ozx2x {
  stop-color: var(--svg-color--845c57, #845C57);
}

.ft5dv1b6b {
  fill: none;
}

.fz20k0zvy {
  fill: var(--svg-color--97919e, #97919E);
  d: path("m14.774 21.558l.914-2.149l-1.793-3.844c-1.258 1.754-1.739 2.665-1.98 3.055c-.269.433-.298.922.062 1.281c.637.57 2.13 1.342 2.797 1.657");
}

.gei07kbgq {
  stop-color: var(--svg-color--5a418f, #5A418F);
  stop-opacity: 0;
}

.gewgt1jbg {
  stop-color: var(--svg-color--afa8b2, #AFA8B2);
}

.gjadyfboc {
  stop-color: var(--svg-color--529cea, #529CEA);
}

.gsodk4bkm {
  stop-color: var(--svg-color--7d4858, #7D4858);
}

.gu98zdb9e {
  stop-color: var(--svg-color--7b4d47, #7B4D47);
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gz3om4b5e {
  stop-color: var(--svg-color--4db0fb, #4DB0FB);
}

.h1tnakbtm {
  stop-color: var(--svg-color--754242, #754242);
  stop-opacity: 0;
}

.h6mz3ebpk {
  stroke: var(--svg-color--8f6d69, #8F6D69);
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m12.703 20.144l-.392 1.14a.4.4 0 0 1-.435.265l-5.761-.833");
}

.hl-6b4apm {
  stop-color: var(--svg-color--916b63, #916B63);
  stop-opacity: 0;
}

.htnxfn4ti {
  stop-color: var(--svg-color--733e65, #733E65);
}

.hv04c4bjr {
  stop-color: var(--svg-color--908582, #908582);
}

.ime0cp0_o {
  fill: var(--svg-color--7b5046, #7B5046);
  d: path("M28.239 11.8c.285-.364.293-.871.07-1.293s-.547-.832-1.016-.813c-.328.014-.598.276-.711.62a1 1 0 0 0-.206.076l-3 1.447a1.6 1.6 0 0 1-1.639-.149l-2.223-1.622a1.15 1.15 0 1 0-1.356 1.858l2.224 1.622a3.9 3.9 0 0 0 3.993.363l2.918-1.422c.246-.12.72-.399.946-.687");
}

.j23k_cb2p {
  stop-color: var(--svg-color--9c959a, #9C959A);
  stop-opacity: 0;
}

.j2u_3dtev {
  stop-color: var(--svg-color--908582, #908582);
  stop-opacity: 0;
}

.j96xv6b5h {
  stop-color: var(--svg-color--917ea3, #917EA3);
  stop-opacity: 0;
}

.jca5wxbec {
  d: path("m19.051 6.463l-.2-1.44a.727.727 0 0 0 .2 1.44");
}

.jijo4-b9s {
  stop-color: var(--svg-color--794b40, #794B40);
}

.jtmedjbua {
  stop-color: var(--svg-color--614e4a, #614E4A);
  stop-opacity: 0;
}

.juw4f_u-e {
  d: path("M28.239 11.8c.285-.364.293-.871.07-1.293s-.547-.832-1.016-.813c-.328.014-.598.276-.711.62a1 1 0 0 0-.206.076l-3 1.447a1.6 1.6 0 0 1-1.639-.149l-2.223-1.622a1.15 1.15 0 1 0-1.356 1.858l2.224 1.622a3.9 3.9 0 0 0 3.993.363l2.918-1.422c.246-.12.72-.399.946-.687");
}

.jwv936b1l {
  width: 1.484px;
  height: 1.324px;
  fill: var(--svg-color--835c4f, #835C4F);
  rx: 0.662px;
}

.jynvl5b3k {
  stop-color: var(--svg-color--845a4e, #845A4E);
}

.k0c7kq1cg {
  fill: var(--svg-color--403235, #403235);
  fill-rule: evenodd;
  d: path("M20.546 4.946c.147-.106.363-.11.5-.11a.2.2 0 0 0 0-.4h-.009c-.128-.001-.464-.001-.724.185a.2.2 0 1 0 .233.325");
}

.k870jjb1v {
  stop-color: var(--svg-color--5aa7ea, #5AA7EA);
  stop-opacity: 0;
}

.kg-rnkb9f {
  stop-color: var(--svg-color--827483, #827483);
  stop-opacity: 0;
}

.kj_uw-bok {
  stop-color: var(--svg-color--875d51, #875D51);
}

.kve1gec_d {
  stop-color: var(--svg-color--63a0db, #63A0DB);
}

.l_6ml5z1n {
  stop-color: var(--svg-color--754242, #754242);
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.leghz1bmd {
  stop-color: var(--svg-color--70433c, #70433C);
}

.lgum6kbvi {
  stop-color: var(--svg-color--35232c, #35232C);
}

.lx_kelx-v {
  stop-color: var(--svg-color--a27a6c, #A27A6C);
}

.m1l7k9jve {
  cx: 0.064px;
  cy: 0.088px;
  rx: 0.064px;
  ry: 0.088px;
}

.m5kggdiwk {
  stop-color: var(--svg-color--3f3035, #3F3035);
  stop-opacity: 0;
}

.mftxrcb_l {
  cx: 0.63px;
  cy: 0.63px;
  r: 0.63px;
}

.mkaeqfx_v {
  stop-color: var(--svg-color--7b4845, #7B4845);
  stop-opacity: 0;
}

.ml97gccia {
  stop-color: var(--svg-color--9b7467, #9B7467);
  stop-opacity: 0;
}

.n1b4mhj1w {
  stop-color: var(--svg-color--64628c, #64628C);
  stop-opacity: 0;
}

.n304-r4kd {
  stop-color: var(--svg-color--9e746b, #9E746B);
}

.n8gqlhnrc {
  stop-color: var(--svg-color--9583a6, #9583A6);
  stop-opacity: 0;
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.ni_rkbnps {
  stop-color: var(--svg-color--794b40, #794B40);
  stop-opacity: 0;
}

.no96t0c8o {
  d: path("M20.71 5.803V5.8c0-.32.137-.58.307-.58s.306.26.306.58v.004z");
}

.nxjjhjnjz {
  d: path("m26.961 27.058l-2.46.07l-1.048 1.39l.624 1.184a.25.25 0 0 0 .335.106l3.41-1.749c.197-.1.317-.328.197-.513c-.247-.381-.74-.488-1.058-.488");
}

.ol9lfys-r {
  stop-color: var(--svg-color--6d3d30, #6D3D30);
  stop-opacity: 0;
}

.osaguabiz {
  stop-color: var(--svg-color--917ea3, #917EA3);
}

.ottdm216w {
  d: path("m14.063 22.62l.652-1.277l-2.613-1.684l-.344 1.016l-5.836-.688l.625 1.774c1.422.445 4.465 1.407 5.504 1.68c1.074.28 1.848-.434 2.012-.82");
}

.p5n-ewbqx {
  stop-color: var(--svg-color--2b71e5, #2B71E5);
}

.p8j_4ij_b {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M20.57 6.917a.125.125 0 0 0 .002.177c.238.233.582.293.692.304a.125.125 0 0 0 .025-.248c-.093-.01-.366-.062-.542-.235a.125.125 0 0 0-.177.002");
}

.p9sn1rbpn {
  stop-color: var(--svg-color--96736c, #96736C);
}

.prk_spbyi {
  d: path("m18.864 8.882l-.74-.39a1 1 0 0 0-.584-.106l-2.003 1.774c.229 1.788-.13 3.007-.9 4.076l4.253 3.23c1.517-2.635 1.93-5.072 1.556-6.354c-.318-1.228-1.05-1.898-1.582-2.23");
}

.prsf6ka-g {
  d: path("M21.183 4.256c.656 0 .969-.37 1-.836c0-.656-.501-.795-.695-.816c-.219-.024-.305-.047-.61-.262a.9.9 0 0 0-.91-.097c-.148.07-.476.105-.71.035c-.391-.118-.696-.114-.997.117c-.209.16-.363.16-.613.16c-.344 0-.636.154-.855.32c-.658.498-.583 2.207-.258 3.168c.31.92.777 1.028 1.168.992c.47-.042.59-.398.66-.695c.056-.237.2-.99.265-1.237c.136-.063.432-.086.532-.474c.1-.387.492-.432.758-.406c.16.016.609.031 1.265.031");
}

.q_8osebjr {
  stop-color: var(--svg-color--8a655b, #8A655B);
}

.q11m-vutr {
  stop-color: var(--svg-color--2b71e5, #2B71E5);
  stop-opacity: 0;
}

.qdq50sbvg {
  stop-color: var(--svg-color--98756a, #98756A);
  stop-opacity: 0;
}

.ql6p40bwg {
  stop-color: var(--svg-color--8b605a, #8B605A);
  stop-opacity: 0;
}

.qp5z_0beh {
  stop-color: var(--svg-color--98756a, #98756A);
}

.qzzesm9df {
  stop-color: var(--svg-color--845c57, #845C57);
  stop-opacity: 0;
}

.r0_3lybww {
  stop-color: var(--svg-color--347cdb, #347CDB);
  stop-opacity: 0;
}

.r42gxacgx {
  stop-color: var(--svg-color--7f5a4d, #7F5A4D);
}

.rf-7bwj8w {
  d: path("M21.822 5.01c-.038-.802-.298-1.188-.42-1.301H17.67l-.063 3.164c.867 2.121 3.512 2.212 3.907 1.445s.353-2.381.308-3.309");
}

.ri9ygtemw {
  stop-color: var(--svg-color--2a1528, #2A1528);
}

.rmzq06bzd {
  stop-color: var(--svg-color--64628c, #64628C);
}

.roa1y3bvy {
  stop-color: var(--svg-color--9b92a1, #9B92A1);
  stop-opacity: 0;
}

.rovuy_e_s {
  stop-color: var(--svg-color--917169, #917169);
}

.ruyfycb4r {
  stop-color: var(--svg-color--444367, #444367);
}

.s-mmaacyl {
  stop-color: var(--svg-color--4091ec, #4091EC);
}

.s6seicc8w {
  stop-color: var(--svg-color--346ece, #346ECE);
}

.s9nkndynh {
  stop-color: var(--svg-color--4db0fb, #4DB0FB);
  stop-opacity: 0;
}

.sbh75zbmf {
  fill: var(--svg-color--8d6c65, #8D6C65);
  d: path("M11.295 9.279c.563-.488 1.182-.714 1.422-.766c-.704-.058-1.422.41-1.766.668l-2.468 2.035H7.92l.563.594c.703-.64 2.25-2.044 2.812-2.531");
}

.sbq6vwbkt {
  stop-color: var(--svg-color--2f89f4, #2F89F4);
  stop-opacity: 0;
}

.scsc9dbso {
  stop-color: var(--svg-color--74446c, #74446C);
}

.sq7_rccwx {
  stop-color: var(--svg-color--885fa7, #885FA7);
}

.sted03b1z {
  stop-color: var(--svg-color--4c438d, #4C438D);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.t_zpwqbmw {
  stop-color: var(--svg-color--865a5d, #865A5D);
}

.tiwfp2v4s {
  stop-color: var(--svg-color--6d3d30, #6D3D30);
}

.u2y29_b_y {
  d: path("m14.151 10l1.324-2.717l2.764 1.322a1.483 1.483 0 0 1-1.255 2.687z");
}

.u6kcyml4j {
  stop-color: var(--svg-color--598fc9, #598FC9);
  stop-opacity: 0;
}

.u8iayhb4j {
  stop-color: var(--svg-color--514342, #514342);
  stop-opacity: 0;
}

.ubkqlww9x {
  stop-color: var(--svg-color--4c438d, #4C438D);
  stop-opacity: 0;
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.ufy99pbfg {
  stop-color: var(--svg-color--733e65, #733E65);
  stop-opacity: 0;
}

.uk3jx7nau {
  stop-color: var(--svg-color--8a5752, #8A5752);
}

.v1sha93vg {
  stop-color: var(--svg-color--746484, #746484);
}

.v6nrgabwc {
  fill: var(--svg-color--856051, #856051);
  fill-rule: evenodd;
  d: path("M12.296 10.144a1.85 1.85 0 0 1 1.873-.285l2.687 1.092l.866-2.13l-2.687-1.093a4.15 4.15 0 0 0-4.2.64l-2.997 2.508a.65.65 0 0 0-.085.912l.636.771a.65.65 0 0 0 .918.086z");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vrnt79u8g {
  stop-color: var(--svg-color--443088, #443088);
}

.vuvc8_ujh {
  stop-color: var(--svg-color--444367, #444367);
  stop-opacity: 0;
}

.vx88q5bse {
  stop-color: var(--svg-color--484083, #484083);
  stop-opacity: 0;
}

.wpy2jtqib {
  stop-color: var(--svg-color--598fc9, #598FC9);
}

.wtj81mbzy {
  stop-color: var(--svg-color--5aa7ea, #5AA7EA);
}

.wy6du73xp {
  stop-color: var(--svg-color--7d4858, #7D4858);
  stop-opacity: 0;
}

.x0ov6mb_y {
  width: 1.484px;
  height: 1.324px;
  rx: 0.662px;
}

.x4krg7bkn {
  fill: var(--svg-color--fff, #fff);
  d: path("M21.316 5.803h-.989c0-.391.222-.709.494-.709c.273 0 .495.318.495.71");
}

.x4tqf8rmd {
  stop-color: var(--svg-color--3f3035, #3F3035);
}

.x67arib7h {
  fill: var(--svg-color--473f82, #473F82);
  d: path("m5.263 19.574l1.234.473l.16 1.749a45 45 0 0 1-1.715 1.634c-.428.387-.844.467-1.146.432c-.23-.026-.312-.276-.23-.492l1.374-3.65a.25.25 0 0 1 .323-.146");
}

.xfghwx9_b {
  d: path("M14.649 14.23s4.125 3.03 6.023 4.703a17.7 17.7 0 0 1-2.544 2.853a.92.92 0 0 1-1.23-.012c-.92-.81-1.78-1.601-2.616-2.552c-1.375-1.563-1.047-2.663-.766-3.313c.244-.562.857-1.354 1.133-1.68");
}

.y4vc4jbhj {
  stop-color: var(--svg-color--96736c, #96736C);
  stop-opacity: 0;
}

.yjn3q9srk {
  stop-color: var(--svg-color--346ece, #346ECE);
  stop-opacity: 0;
}

.yknew8brm {
  stop-color: var(--svg-color--855956, #855956);
}

.z-p3-w_an {
  stop-color: var(--svg-color--534f8c, #534F8C);
  stop-opacity: 0;
}

.z8jy9-b3h {
  d: path("M0 0h1.946v3.44H0z");
}

.ztpt-rb1m {
  stop-color: var(--svg-color--80504f, #80504F);
}

</style>
