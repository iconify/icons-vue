<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iturgZv)" transform="scale(-1 1)rotate(-4.337 81.315 265.316)" class="z8jy9-b3h"/><path fill="url(#icSmT8b)" transform="scale(-1 1)rotate(-4.337 81.315 265.316)" class="z8jy9-b3h"/><path fill="url(#iFEzbFu)" class="r61kt0-4u"/><g filter="url(#iKdFPXb)"><path fill="url(#iSfoR2M)" class="b8d5ozb9o"/><path fill="url(#iUPJZiN)" class="b8d5ozb9o"/></g><g filter="url(#iYJmvxe)"><path class="b3uhfsy5j"/><path fill="url(#iHe3txc)" class="ns62sbcru"/><path fill="url(#iaaajgd)" class="ns62sbcru"/><path fill="url(#itvQfLR)" class="ns62sbcru"/><path fill="url(#iwkN3je)" class="ns62sbcru"/><path fill="url(#ili8lLe)" class="ns62sbcru"/></g><path fill="url(#i4Epaac)" class="laz6lfbrz"/><path clip-rule="evenodd" class="vht_kx7pc"/><g filter="url(#iN2hA7d)"><path clip-rule="evenodd" class="w7ehj54kn"/></g><path class="i-0kf8boc"/><path fill="url(#i4Q45bd)" class="wwugowm5b"/><path fill="url(#ipObX1c)" class="iql4t-bgr"/><ellipse fill="url(#ipECBte)" transform="scale(-1 1)rotate(24.61 -23.013 -46.599)" class="m1l7k9jve"/><path class="x_83z2b6u"/><path fill="url(#iF2Fbnc)" class="ijc6h2bgo"/><path fill="url(#iqrjEcr)" class="ijc6h2bgo"/><path fill="url(#iccJwVd)" class="ijc6h2bgo"/><path fill="url(#i4vqVCb)" class="ijc6h2bgo"/><path fill="url(#iNGIRvd)" class="ijc6h2bgo"/><path class="sum3tedvm"/><path fill="url(#i8sVKNd)" class="idabus57a"/><path fill="url(#iBdajHw)" class="idabus57a"/><path fill="url(#iu9WODd)" class="idabus57a"/><path fill="url(#itqRFxJ)" class="idabus57a"/><circle fill="url(#iXXSmAb)" transform="matrix(-1 0 0 1 10.426 11.464)" class="mftxrcb_l"/><g filter="url(#iyWZ08d)"><path clip-rule="evenodd" class="ni2zhibrz"/></g><path class="luz-85szx"/><path fill="url(#ilz8P4c)" class="il_l8vbxh"/><path fill="url(#ijZ8QIe)" class="il_l8vbxh"/><path fill="url(#i13s8Jd)" class="il_l8vbxh"/><rect transform="matrix(-1 0 0 1 27.262 10.05)" class="u9s7qvbon"/><path fill="url(#iPzGfCc)" class="ev6b90b_n"/><path fill="url(#iFpokNe)" class="ev6b90b_n"/><path fill="url(#iV9rgxb)" class="ev6b90b_n"/><path fill="url(#ipgPUFe)" class="ev6b90b_n"/><g filter="url(#iR47Oxa)"><path class="ny4tm1bic"/><path fill="url(#ivRqXLe)" class="evqygybcd"/><path fill="url(#irO11Oc)" class="evqygybcd"/></g><path fill="url(#iW5ZQAe)" class="evqygybcd"/><g filter="url(#iA9Nleb)"><path class="wzetdubiu"/><path fill="url(#ivkpWrd)" class="v615_eb3w"/><path fill="url(#iyGw0KA)" class="v615_eb3w"/></g><g filter="url(#iWdrqEe)"><path stroke="url(#iiF8xFb)" class="mcp5kqb8a"/></g><path class="lf-e5yw6j"/><path fill="url(#i1YEfve)" class="lzy-46bcu"/><path fill="url(#i6AuBbb)" class="lzy-46bcu"/><path fill="url(#i09wcJe)" class="lzy-46bcu"/><g filter="url(#iCULs0b)"><path class="w-qkhy6mm"/><path fill="url(#iQpm1Hb)" class="e9b3cbcix"/></g><path class="ot1utkb0u"/><path fill="url(#ikxHPOc)" class="ld86b6bkj"/><path fill="url(#ib7Kinb)" class="ld86b6bkj"/><path fill="url(#iLHYTsb)" class="ld86b6bkj"/><path fill="url(#iykOrwK)" class="ld86b6bkj"/><path fill="url(#i0dWebd)" class="ld86b6bkj"/><defs><radialGradient id="iturgZv" cx="0" cy="0" r="1" gradientTransform="matrix(-.05152 -2.21336 1.59858 -.0372 1.708 2.01)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="ld96_xbja"/><stop offset="1" class="ygjc6ybks"/></radialGradient><radialGradient id="icSmT8b" cx="0" cy="0" r="1" gradientTransform="matrix(-.53617 .66448 -.89991 -.72614 2.062 .438)" gradientUnits="userSpaceOnUse"><stop class="wlrmkubjk"/><stop offset="1" class="bdl3pn0lv"/></radialGradient><radialGradient id="iFEzbFu" cx="0" cy="0" r="1" gradientTransform="matrix(-.3125 .60583 -.77155 -.39799 22.546 6.128)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="fvok_qxen"/><stop offset="1" class="suyap8bzv"/></radialGradient><radialGradient id="iUPJZiN" cx="0" cy="0" r="1" gradientTransform="matrix(.84375 -.04687 .05715 1.0287 19.007 5.713)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="d7kch3t0q"/><stop offset="1" class="admd7db0k"/></radialGradient><radialGradient id="iHe3txc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.90805 -1.94145 2.83721 -2.78841 18.525 7.148)" gradientUnits="userSpaceOnUse"><stop class="re8izvbqw"/><stop offset="1" class="kgio6d1ee"/></radialGradient><radialGradient id="iaaajgd" cx="0" cy="0" r="1" gradientTransform="rotate(22.739 -.111 44.304)scale(2.30409 3.23462)" gradientUnits="userSpaceOnUse"><stop class="u0-djrvhx"/><stop offset="1" class="fj67tibom"/></radialGradient><radialGradient id="itvQfLR" cx="0" cy="0" r="1" gradientTransform="matrix(.8125 -.23437 .10899 .37782 17.163 6.69)" gradientUnits="userSpaceOnUse"><stop class="jkk-xsb9b"/><stop offset="1" class="g6je8pe2z"/></radialGradient><radialGradient id="iwkN3je" cx="0" cy="0" r="1" gradientTransform="matrix(1.79688 .32813 -.1515 .82965 18.75 2.127)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="t5jak8x3h"/><stop offset="1" class="hze7fms1a"/></radialGradient><radialGradient id="ili8lLe" cx="0" cy="0" r="1" gradientTransform="matrix(-.50781 .47657 -.68826 -.73338 21.664 2.04)" gradientUnits="userSpaceOnUse"><stop offset=".117" class="an20q5kfx"/><stop offset="1" class="xh4g4qbuv"/></radialGradient><radialGradient id="i4Epaac" cx="0" cy="0" r="1" gradientTransform="matrix(.45312 .9414 -1.52974 .7363 18.703 5.534)" gradientUnits="userSpaceOnUse"><stop offset=".04" class="bervkqbmz"/><stop offset="1" class="c479w-bpn"/></radialGradient><radialGradient id="i4Q45bd" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 0 0 -.53125 21.37 5.788)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="ipObX1c" cx="0" cy="0" r="1" gradientTransform="matrix(-.25 0 0 -.54102 21.538 5.81)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="iF2Fbnc" cx="0" cy="0" r="1" gradientTransform="matrix(-7.06247 3.6563 -1.3298 -2.56862 27.703 9.96)" gradientUnits="userSpaceOnUse"><stop offset=".655" class="ssz2hzbxz"/><stop offset="1" class="qi0ilhbio"/></radialGradient><radialGradient id="iqrjEcr" cx="0" cy="0" r="1" gradientTransform="matrix(-6.99996 5.0938 -5.69913 -7.8318 27.016 9.084)" gradientUnits="userSpaceOnUse"><stop offset=".757" class="txwnmebwl"/><stop offset=".956" class="lr609_zbb"/></radialGradient><radialGradient id="iccJwVd" cx="0" cy="0" r="1" gradientTransform="matrix(.85936 1.25 -.4913 .33776 26.922 10.974)" gradientUnits="userSpaceOnUse"><stop offset=".418" class="yeyqi9phi"/><stop offset="1" class="j9k09pb-s"/></radialGradient><radialGradient id="i4vqVCb" cx="0" cy="0" r="1" gradientTransform="matrix(-.59003 .20312 -.95675 -2.77925 28.464 11.132)" gradientUnits="userSpaceOnUse"><stop class="mcvrg0kam"/><stop offset="1" class="q-30hhb4p"/></radialGradient><radialGradient id="iNGIRvd" cx="0" cy="0" r="1" gradientTransform="matrix(.78125 .57812 -.69034 .93291 26.718 9.912)" gradientUnits="userSpaceOnUse"><stop class="bjjn4ob6s"/><stop offset="1" class="snqm-cbpd"/></radialGradient><radialGradient id="i8sVKNd" cx="0" cy="0" r="1" gradientTransform="matrix(1.22254 -5.1875 3.29358 .7762 17.606 16.99)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="ioo6anwhf"/><stop offset="1" class="vly_b_ldb"/></radialGradient><radialGradient id="iBdajHw" cx="0" cy="0" r="1" gradientTransform="matrix(-.125 5.84375 -2.28997 -.04898 20.11 12.397)" gradientUnits="userSpaceOnUse"><stop class="d66h0_v2y"/><stop offset="1" class="d3t9wcc9u"/></radialGradient><radialGradient id="iu9WODd" cx="0" cy="0" r="1" gradientTransform="matrix(2.40625 .71875 -1.45293 4.86416 14.89 13.397)" gradientUnits="userSpaceOnUse"><stop class="yx3aab4wz"/><stop offset="1" class="d2ptywb0c"/></radialGradient><radialGradient id="itqRFxJ" cx="0" cy="0" r="1" gradientTransform="matrix(.71875 1.53125 -1.86259 .87428 15.328 10.334)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="e_wvtt-qm"/><stop offset="1" class="f0_sezbyw"/></radialGradient><radialGradient id="iXXSmAb" cx="0" cy="0" r="1" gradientTransform="matrix(1.01953 .46875 -.49222 1.07057 0 .714)" gradientUnits="userSpaceOnUse"><stop class="bmfdee-fc"/><stop offset=".906" class="y5luhbaev"/></radialGradient><radialGradient id="ijZ8QIe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 .1875 -.31663 -2.16355 19.328 9.99)" gradientUnits="userSpaceOnUse"><stop class="hhyc553gq"/><stop offset="1" class="ss0-anvgm"/></radialGradient><radialGradient id="i13s8Jd" cx="0" cy="0" r="1" gradientTransform="matrix(.875 .42187 -.65917 1.36718 14.64 8.475)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="gtma0og_l"/><stop offset="1" class="yf8z_2acj"/></radialGradient><radialGradient id="iV9rgxb" cx="0" cy="0" r="1" gradientTransform="matrix(4.65317 9.34098 -2.71885 1.35439 17.916 21.165)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="y_4ptxbzf"/><stop offset="1" class="ado7u1b7k"/></radialGradient><radialGradient id="ipgPUFe" cx="0" cy="0" r="1" gradientTransform="matrix(1.82682 4.82558 -1.33887 .50686 18.089 21.13)" gradientUnits="userSpaceOnUse"><stop class="hpbocun_g"/><stop offset="1" class="umrurxb6b"/></radialGradient><radialGradient id="iW5ZQAe" cx="0" cy="0" r="1" gradientTransform="rotate(-161.643 16.295 11.728)scale(.94262 1.56541)" gradientUnits="userSpaceOnUse"><stop class="rmzq06bzd"/><stop offset="1" class="n1b4mhj1w"/></radialGradient><radialGradient id="iyGw0KA" cx="0" cy="0" r="1" gradientTransform="rotate(119.055 .828 14.805)scale(2.25217 1.02691)" gradientUnits="userSpaceOnUse"><stop class="nkql81bxe"/><stop offset="1" class="bi5pn_1vn"/></radialGradient><radialGradient id="iQpm1Hb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.4375 4.75 -1.7011 -.87293 14.985 18.803)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="v1sha93vg"/><stop offset="1" class="kg-rnkb9f"/></radialGradient><radialGradient id="ikxHPOc" cx="0" cy="0" r="1" gradientTransform="rotate(128.66 4.949 12.855)scale(4.60225 17.5153)" gradientUnits="userSpaceOnUse"><stop offset=".554" class="j96xv6b5h"/><stop offset="1" class="osaguabiz"/></radialGradient><radialGradient id="ib7Kinb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.01137 -2.1808 7.2546 -3.3644 17.464 22.502)" gradientUnits="userSpaceOnUse"><stop class="sq7_rccwx"/><stop offset="1" class="n8gqlhnrc"/></radialGradient><radialGradient id="iLHYTsb" cx="0" cy="0" r="1" gradientTransform="matrix(2.05437 1.35958 -1.29324 1.95413 13.956 16.844)" gradientUnits="userSpaceOnUse"><stop class="gewgt1jbg"/><stop offset="1" class="roa1y3bvy"/></radialGradient><radialGradient id="i0dWebd" cx="0" cy="0" r="1" gradientTransform="rotate(-154.573 11.175 6.48)scale(2.11071 .26513)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="c6vpnsb1w"/><stop offset="1" class="j23k_cb2p"/></radialGradient><linearGradient id="iSfoR2M" x1="19.32" x2="22.182" y1="6.456" y2="6.627" gradientUnits="userSpaceOnUse"><stop class="egm-dub4f"/><stop offset="1" class="zhwoohbuw"/></linearGradient><linearGradient id="ipECBte" x1="-.007" x2=".179" y1=".05" y2=".11" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="ilz8P4c" x1="15.485" x2="16.891" y1="11.022" y2="8.584" gradientUnits="userSpaceOnUse"><stop class="r1i9tc3bx"/><stop offset="1" class="c__hzybex"/></linearGradient><linearGradient id="iPzGfCc" x1="19.547" x2="22.922" y1="20.084" y2="28.209" gradientUnits="userSpaceOnUse"><stop class="rshq-s3st"/><stop offset="1" class="rvpou-b_v"/></linearGradient><linearGradient id="iFpokNe" x1="24.155" x2="22.88" y1="24.749" y2="25.231" gradientUnits="userSpaceOnUse"><stop class="q2m7j_fif"/><stop offset="1" class="mt6f54ber"/></linearGradient><linearGradient id="ivRqXLe" x1="26.102" x2="25.946" y1="29.045" y2="28.733" gradientUnits="userSpaceOnUse"><stop class="vrnt79u8g"/><stop offset="1" class="z-p3-w_an"/></linearGradient><linearGradient id="irO11Oc" x1="23.86" x2="24.516" y1="29.444" y2="29.006" gradientUnits="userSpaceOnUse"><stop class="sted03b1z"/><stop offset="1" class="ubkqlww9x"/></linearGradient><linearGradient id="ivkpWrd" x1="13.829" x2="12.36" y1="22.772" y2="22.116" gradientUnits="userSpaceOnUse"><stop class="rz90b38rn"/><stop offset="1" class="lngpjjb0b"/></linearGradient><linearGradient id="iiF8xFb" x1="12.563" x2="7.625" y1="21.303" y2="21.116" gradientUnits="userSpaceOnUse"><stop class="f7j3ni3bi"/><stop offset="1" class="i_d2dkbya"/></linearGradient><linearGradient id="i1YEfve" x1="5.86" x2="5.36" y1="19.639" y2="20.803" gradientUnits="userSpaceOnUse"><stop offset=".024" class="ruyfycb4r"/><stop offset="1" class="vuvc8_ujh"/></linearGradient><linearGradient id="i6AuBbb" x1="5.86" x2="5.096" y1="22.6" y2="21.795" gradientUnits="userSpaceOnUse"><stop class="clpaphbux"/><stop offset="1" class="gei07kbgq"/></linearGradient><linearGradient id="i09wcJe" x1="4.078" x2="4.485" y1="21.881" y2="22.022" gradientUnits="userSpaceOnUse"><stop offset=".213" class="e2g34f-cy"/><stop offset="1" class="vx88q5bse"/></linearGradient><linearGradient id="iykOrwK" x1="18.828" x2="18.141" y1="17.272" y2="18.204" gradientUnits="userSpaceOnUse"><stop class="hv04c4bjr"/><stop offset="1" class="j2u_3dtev"/></linearGradient><filter id="iKdFPXb" width="4.443" height="5.249" x="17.739" y="3.515" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.94902 0 0 0 0 0.533333 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_9873"/></filter><filter id="iYJmvxe" width="5.503" height="5.499" x="16.617" y="1.933" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.607843 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_9873"/></filter><filter id="iN2hA7d" width="1.013" height=".568" x="20.507" y="4.458" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.682353 0 0 0 0 0.219608 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_9873"/></filter><filter id="iyWZ08d" width="10.118" height="5.774" x="7.605" y="7.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.929412 0 0 0 0 0.552941 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_9873"/></filter><filter id="iR47Oxa" width="4.813" height="3.178" x="23.453" y="27.139" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.286275 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_9873"/></filter><filter id="iA9Nleb" width="8.943" height="4.095" x="5.772" y="19.491" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.960784 0 0 0 0 0.513726 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_9873"/></filter><filter id="iWdrqEe" width="6.408" height="2.475" x="6.884" y="19.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_9873" stdDeviation=".2"/></filter><filter id="iCULs0b" width="3.978" height="6.092" x="11.71" y="15.547" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.458824 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_9873"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-running-facing-right" /></template>
<style>
.admd7db0k {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
  stop-opacity: 0;
}

.ado7u1b7k {
  stop-color: var(--svg-color--ec8b4b, #EC8B4B);
  stop-opacity: 0;
}

.an20q5kfx {
  stop-color: var(--svg-color--e0a531, #E0A531);
}

.b3uhfsy5j {
  fill: var(--svg-color--ffba23, #FFBA23);
  d: path("M22.003 2.663a1.025 1.025 0 0 0-.984-.579c-.86.047-.977.344-1.754.184c-.822-.17-1.227-.12-1.578.039l-.007.003c-.346.158-1.063.483-1.063 1.95c0 1.352.482 2.065.715 2.32l-.046.017c-.232.084-.327.33-.244.562c.072.197.322.31.637.261c.36-.056.625-.106.832-.147a.25.25 0 0 0 .2-.244V5.916a.99.99 0 0 1 .476-.832c.015-.484.164-.707.406-.824c.401-.194.526-.098 1.485-.156c.965-.059 1.222-.832.925-1.441");
}

.b8d5ozb9o {
  d: path("M22.154 5.015c-.038-.801-.298-1.187-.42-1.3h-3.732l-.063 3.163c.867 2.122 3.512 2.213 3.907 1.446s.353-2.381.308-3.309");
}

.bdl3pn0lv {
  stop-color: var(--svg-color--fda533, #FDA533);
  stop-opacity: 0;
}

.bervkqbmz {
  stop-color: var(--svg-color--ffd040, #FFD040);
}

.bi5pn_1vn {
  stop-color: var(--svg-color--f3953d, #F3953D);
  stop-opacity: 0;
}

.bjjn4ob6s {
  stop-color: var(--svg-color--e9b636, #E9B636);
}

.bmfdee-fc {
  stop-color: var(--svg-color--fc9d34, #FC9D34);
}

.c__hzybex {
  stop-color: var(--svg-color--ff813d, #FF813D);
  stop-opacity: 0;
}

.c479w-bpn {
  stop-color: var(--svg-color--fead30, #FEAD30);
}

.c6vpnsb1w {
  stop-color: var(--svg-color--9c959a, #9C959A);
}

.clpaphbux {
  stop-color: var(--svg-color--5a418f, #5A418F);
}

.d2ptywb0c {
  stop-color: var(--svg-color--ff8750, #FF8750);
  stop-opacity: 0;
}

.d3t9wcc9u {
  stop-color: var(--svg-color--ff9056, #FF9056);
  stop-opacity: 0;
}

.d66h0_v2y {
  stop-color: var(--svg-color--ff9056, #FF9056);
}

.d7kch3t0q {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
}

.e_wvtt-qm {
  stop-color: var(--svg-color--eb784b, #EB784B);
}

.e2g34f-cy {
  stop-color: var(--svg-color--5e5d8f, #5E5D8F);
}

.e9b3cbcix {
  d: path("m14.774 21.639l.914-2.148l-1.793-3.844c-1.258 1.754-1.738 2.664-1.98 3.054c-.269.433-.297.922.062 1.282c.637.568 2.13 1.34 2.797 1.656");
}

.egm-dub4f {
  stop-color: var(--svg-color--ffc33e, #FFC33E);
}

.ev6b90b_n {
  d: path("M22.985 21.99a863 863 0 0 0 1.547 5.22l-1.075 1.39c-.859-1.615-2.641-4.987-2.93-5.66c-.242-.567-.566-.711-.808-.856l-1.34-.805l1.973-2.472c.12.094.594.444 1.32 1.074c.735.637 1.169 1.618 1.313 2.11");
}

.evqygybcd {
  d: path("m26.961 27.139l-2.46.07l-1.048 1.39l.623 1.184a.25.25 0 0 0 .336.106l3.41-1.749c.196-.1.317-.328.197-.513c-.247-.381-.74-.488-1.058-.488");
}

.f0_sezbyw {
  stop-color: var(--svg-color--eb784b, #EB784B);
  stop-opacity: 0;
}

.f7j3ni3bi {
  stop-color: var(--svg-color--ffcc43, #FFCC43);
}

.fj67tibom {
  stop-color: var(--svg-color--ffd537, #FFD537);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fvok_qxen {
  stop-color: var(--svg-color--ffbf42, #FFBF42);
}

.g6je8pe2z {
  stop-color: var(--svg-color--ffd237, #FFD237);
  stop-opacity: 0;
}

.gei07kbgq {
  stop-color: var(--svg-color--5a418f, #5A418F);
  stop-opacity: 0;
}

.gewgt1jbg {
  stop-color: var(--svg-color--afa8b2, #AFA8B2);
}

.gtma0og_l {
  stop-color: var(--svg-color--ff985a, #FF985A);
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.hhyc553gq {
  stop-color: var(--svg-color--ff9459, #FF9459);
}

.hpbocun_g {
  stop-color: var(--svg-color--d77364, #D77364);
}

.hv04c4bjr {
  stop-color: var(--svg-color--908582, #908582);
}

.hze7fms1a {
  stop-color: var(--svg-color--ffbf27, #FFBF27);
  stop-opacity: 0;
}

.i_d2dkbya {
  stop-color: var(--svg-color--ffcc43, #FFCC43);
  stop-opacity: 0;
}

.i-0kf8boc {
  fill: var(--svg-color--fff, #fff);
  d: path("M21.648 5.81h-.988c0-.392.22-.71.494-.71c.273 0 .494.318.494.71");
}

.idabus57a {
  d: path("m18.864 8.963l-.74-.39a1 1 0 0 0-.584-.106l-2.003 1.774c.229 1.789-.13 3.007-.9 4.077l4.253 3.23c1.517-2.636 1.93-5.073 1.556-6.354c-.318-1.229-1.051-1.899-1.582-2.23");
}

.ijc6h2bgo {
  d: path("M28.239 11.881c.285-.363.293-.871.07-1.293s-.547-.832-1.016-.812c-.328.013-.598.275-.711.619a1 1 0 0 0-.207.076l-3 1.447a1.6 1.6 0 0 1-1.638-.148l-2.223-1.623a1.15 1.15 0 1 0-1.356 1.858l2.224 1.623a3.9 3.9 0 0 0 3.993.362l2.918-1.421c.246-.122.72-.4.945-.688");
}

.il_l8vbxh {
  d: path("m14.15 10.082l1.325-2.718l2.764 1.322a1.483 1.483 0 0 1-1.255 2.687z");
}

.ioo6anwhf {
  stop-color: var(--svg-color--fb643e, #FB643E);
}

.iql4t-bgr {
  d: path("m21.238 5.81l-.004-.073c0-.186.078-.336.175-.336c.098 0 .176.15.176.336l-.004.072z");
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

.j9k09pb-s {
  stop-color: var(--svg-color--fea724, #FEA724);
  stop-opacity: 0;
}

.jkk-xsb9b {
  stop-color: var(--svg-color--ffd237, #FFD237);
}

.kg-rnkb9f {
  stop-color: var(--svg-color--827483, #827483);
  stop-opacity: 0;
}

.kgio6d1ee {
  stop-color: var(--svg-color--ffa526, #FFA526);
  stop-opacity: 0;
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.laz6lfbrz {
  d: path("m19.383 6.47l-.199-1.44a.727.727 0 0 0 .2 1.44");
}

.ld86b6bkj {
  d: path("M14.649 14.31s4.125 3.032 6.023 4.704a17.7 17.7 0 0 1-2.544 2.853a.92.92 0 0 1-1.23-.012c-.921-.81-1.78-1.6-2.617-2.552c-1.375-1.562-1.046-2.663-.765-3.312c.244-.563.857-1.355 1.133-1.68");
}

.ld96_xbja {
  stop-color: var(--svg-color--ffb435, #FFB435);
}

.lf-e5yw6j {
  fill: var(--svg-color--473f82, #473F82);
  d: path("m5.263 19.656l1.234.472l.16 1.75a45 45 0 0 1-1.715 1.633c-.427.387-.844.467-1.146.432c-.23-.026-.312-.276-.23-.491L4.94 19.8a.25.25 0 0 1 .323-.145");
}

.lngpjjb0b {
  stop-color: var(--svg-color--ffb657, #FFB657);
  stop-opacity: 0;
}

.lr609_zbb {
  stop-color: var(--svg-color--e77553, #E77553);
}

.luz-85szx {
  fill: var(--svg-color--ff832d, #FF832D);
  d: path("m14.15 10.082l1.325-2.718l2.764 1.322a1.483 1.483 0 0 1-1.255 2.687z");
}

.lzy-46bcu {
  d: path("m5.263 19.656l1.234.472l.16 1.75a45 45 0 0 1-1.715 1.633c-.427.387-.844.467-1.146.432c-.23-.026-.312-.276-.23-.491L4.94 19.8a.25.25 0 0 1 .323-.145");
}

.m1l7k9jve {
  cx: 0.064px;
  cy: 0.088px;
  rx: 0.064px;
  ry: 0.088px;
}

.mcp5kqb8a {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m12.704 20.225l-.393 1.14a.4.4 0 0 1-.435.266l-4.563-.656");
}

.mcvrg0kam {
  stop-color: var(--svg-color--ffd05b, #FFD05B);
}

.mftxrcb_l {
  cx: 0.63px;
  cy: 0.63px;
  r: 0.63px;
}

.mt6f54ber {
  stop-color: var(--svg-color--ffd558, #FFD558);
  stop-opacity: 0;
}

.n1b4mhj1w {
  stop-color: var(--svg-color--64628c, #64628C);
  stop-opacity: 0;
}

.n8gqlhnrc {
  stop-color: var(--svg-color--9583a6, #9583A6);
  stop-opacity: 0;
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.ni2zhibrz {
  fill: var(--svg-color--ffc538, #FFC538);
  fill-rule: evenodd;
  d: path("M12.296 10.225a1.85 1.85 0 0 1 1.873-.285l2.687 1.092l.866-2.13l-2.687-1.093a4.15 4.15 0 0 0-4.2.64l-2.997 2.508a.65.65 0 0 0-.085.912l.635.772a.65.65 0 0 0 .92.085z");
}

.nkql81bxe {
  stop-color: var(--svg-color--f3953d, #F3953D);
}

.ns62sbcru {
  d: path("M22.003 2.663a1.025 1.025 0 0 0-.984-.579c-.86.047-.977.344-1.754.184c-.822-.17-1.227-.12-1.578.039l-.007.003c-.346.158-1.063.483-1.063 1.95c0 1.352.482 2.065.715 2.32l-.046.017c-.232.084-.327.33-.244.562c.072.197.322.31.637.261c.36-.056.625-.106.832-.147a.25.25 0 0 0 .2-.244V5.916a.99.99 0 0 1 .476-.832c.015-.484.164-.707.406-.824c.401-.194.526-.098 1.485-.156c.965-.059 1.222-.832.925-1.441");
}

.ny4tm1bic {
  fill: var(--svg-color--534e8c, #534E8C);
  d: path("m26.961 27.139l-2.46.07l-1.048 1.39l.623 1.184a.25.25 0 0 0 .336.106l3.41-1.749c.196-.1.317-.328.197-.513c-.247-.381-.74-.488-1.058-.488");
}

.osaguabiz {
  stop-color: var(--svg-color--917ea3, #917EA3);
}

.ot1utkb0u {
  fill: var(--svg-color--918996, #918996);
  d: path("M14.649 14.31s4.125 3.032 6.023 4.704a17.7 17.7 0 0 1-2.544 2.853a.92.92 0 0 1-1.23-.012c-.921-.81-1.78-1.6-2.617-2.552c-1.375-1.562-1.046-2.663-.765-3.312c.244-.563.857-1.355 1.133-1.68");
}

.q-30hhb4p {
  stop-color: var(--svg-color--ffd05b, #FFD05B);
  stop-opacity: 0;
}

.q2m7j_fif {
  stop-color: var(--svg-color--ffd558, #FFD558);
}

.qi0ilhbio {
  stop-color: var(--svg-color--ff9b2a, #FF9B2A);
}

.r1i9tc3bx {
  stop-color: var(--svg-color--f05c24, #F05C24);
}

.r61kt0-4u {
  d: path("M22.378 5.979a1 1 0 0 1-.258-.457h-.18v1.125c.215.137.523.115.614-.09c.078-.176.02-.394-.176-.578");
}

.re8izvbqw {
  stop-color: var(--svg-color--ffa526, #FFA526);
}

.rmzq06bzd {
  stop-color: var(--svg-color--64628c, #64628C);
}

.roa1y3bvy {
  stop-color: var(--svg-color--9b92a1, #9B92A1);
  stop-opacity: 0;
}

.rshq-s3st {
  stop-color: var(--svg-color--ffc235, #FFC235);
}

.ruyfycb4r {
  stop-color: var(--svg-color--444367, #444367);
}

.rvpou-b_v {
  stop-color: var(--svg-color--ffc443, #FFC443);
}

.rz90b38rn {
  stop-color: var(--svg-color--ffb657, #FFB657);
}

.snqm-cbpd {
  stop-color: var(--svg-color--e9b636, #E9B636);
  stop-opacity: 0;
}

.sq7_rccwx {
  stop-color: var(--svg-color--885fa7, #885FA7);
}

.ss0-anvgm {
  stop-color: var(--svg-color--ff9459, #FF9459);
  stop-opacity: 0;
}

.ssz2hzbxz {
  stop-color: var(--svg-color--ff9b2a, #FF9B2A);
  stop-opacity: 0;
}

.sted03b1z {
  stop-color: var(--svg-color--4c438d, #4C438D);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.sum3tedvm {
  fill: var(--svg-color--ff7534, #FF7534);
  d: path("m18.864 8.963l-.74-.39a1 1 0 0 0-.584-.106l-2.003 1.774c.229 1.789-.13 3.007-.9 4.077l4.253 3.23c1.517-2.636 1.93-5.073 1.556-6.354c-.318-1.229-1.051-1.899-1.582-2.23");
}

.suyap8bzv {
  stop-color: var(--svg-color--eba544, #EBA544);
}

.t5jak8x3h {
  stop-color: var(--svg-color--e4af34, #E4AF34);
}

.txwnmebwl {
  stop-color: var(--svg-color--ff9231, #FF9231);
  stop-opacity: 0;
}

.u0-djrvhx {
  stop-color: var(--svg-color--ffd537, #FFD537);
}

.u9s7qvbon {
  width: 1.484px;
  height: 1.324px;
  fill: var(--svg-color--ffc039, #FFC039);
  rx: 0.662px;
}

.ubkqlww9x {
  stop-color: var(--svg-color--4c438d, #4C438D);
  stop-opacity: 0;
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.umrurxb6b {
  stop-color: var(--svg-color--d77364, #D77364);
  stop-opacity: 0;
}

.v1sha93vg {
  stop-color: var(--svg-color--746484, #746484);
}

.v615_eb3w {
  d: path("m14.063 22.701l.652-1.277l-2.613-1.683l-.344 1.015l-5.836-.687l.625 1.773c1.422.445 4.465 1.408 5.504 1.68c1.074.281 1.848-.434 2.012-.82");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vht_kx7pc {
  fill: var(--svg-color--87014d, #87014D);
  fill-rule: evenodd;
  d: path("M20.902 6.923a.125.125 0 0 0 .002.176c.238.234.582.294.692.305a.125.125 0 1 0 .026-.249c-.094-.01-.367-.061-.543-.234a.125.125 0 0 0-.177.002");
}

.vly_b_ldb {
  stop-color: var(--svg-color--fb643e, #FB643E);
  stop-opacity: 0;
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

.w-qkhy6mm {
  fill: var(--svg-color--97919e, #97919E);
  d: path("m14.774 21.639l.914-2.148l-1.793-3.844c-1.258 1.754-1.738 2.664-1.98 3.054c-.269.433-.297.922.062 1.282c.637.568 2.13 1.34 2.797 1.656");
}

.w7ehj54kn {
  fill: var(--svg-color--af5247, #AF5247);
  fill-rule: evenodd;
  d: path("M21.135 4.776a.8.8 0 0 1 .217-.015a.15.15 0 0 0 .037-.298a1 1 0 0 0-.313.019a1 1 0 0 0-.408.173a.15.15 0 0 0 .178.241c.085-.062.19-.1.289-.12");
}

.wlrmkubjk {
  stop-color: var(--svg-color--cd7f1a, #CD7F1A);
}

.wwugowm5b {
  d: path("M21.042 5.81v-.005c0-.32.138-.58.307-.58c.17 0 .307.26.307.58v.004z");
}

.wzetdubiu {
  fill: var(--svg-color--ffc439, #FFC439);
  d: path("m14.063 22.701l.652-1.277l-2.613-1.683l-.344 1.015l-5.836-.687l.625 1.773c1.422.445 4.465 1.408 5.504 1.68c1.074.281 1.848-.434 2.012-.82");
}

.x_83z2b6u {
  fill: var(--svg-color--ffb93c, #FFB93C);
  d: path("M28.239 11.881c.285-.363.293-.871.07-1.293s-.547-.832-1.016-.812c-.328.013-.598.275-.711.619a1 1 0 0 0-.207.076l-3 1.447a1.6 1.6 0 0 1-1.638-.148l-2.223-1.623a1.15 1.15 0 1 0-1.356 1.858l2.224 1.623a3.9 3.9 0 0 0 3.993.362l2.918-1.421c.246-.122.72-.4.945-.688");
}

.xh4g4qbuv {
  stop-color: var(--svg-color--e0a531, #E0A531);
  stop-opacity: 0;
}

.y_4ptxbzf {
  stop-color: var(--svg-color--ec8b4b, #EC8B4B);
}

.y5luhbaev {
  stop-color: var(--svg-color--e17e4b, #E17E4B);
}

.yeyqi9phi {
  stop-color: var(--svg-color--fea724, #FEA724);
}

.yf8z_2acj {
  stop-color: var(--svg-color--ff985a, #FF985A);
  stop-opacity: 0;
}

.ygjc6ybks {
  stop-color: var(--svg-color--fea73c, #FEA73C);
}

.yx3aab4wz {
  stop-color: var(--svg-color--ff8750, #FF8750);
}

.z-p3-w_an {
  stop-color: var(--svg-color--534f8c, #534F8C);
  stop-opacity: 0;
}

.z8jy9-b3h {
  d: path("M0 0h1.946v3.44H0z");
}

.zhwoohbuw {
  stop-color: var(--svg-color--ffc247, #FFC247);
}

</style>
