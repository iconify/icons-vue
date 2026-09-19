<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iNL63Dc)"><path fill="url(#i2V8gUc)" class="zal6rzb4g"/><path fill="url(#itL8nzd)" class="zal6rzb4g"/></g><g filter="url(#iT35k8b)"><path class="o-87xdcfh"/><path fill="url(#i3ALmkc)" class="gzijw2msn"/><path fill="url(#iPZk2De)" class="gzijw2msn"/></g><g filter="url(#itTFGSc)"><path fill="url(#iP1z2Mb)" class="nhij6gb6h"/></g><g filter="url(#iVSSLNb)"><path fill="url(#i7KUjVb)" class="nhij6gb6h"/></g><g filter="url(#itFNe6d)"><path fill="url(#iXtoddd)" class="comlzxbct"/></g><g filter="url(#ifQEUWd)"><path fill="url(#iBxddSb)" class="qd1f4bcmu"/><path fill="url(#iuVaLLd)" class="qd1f4bcmu"/><path fill="url(#ieGYgvc)" class="qd1f4bcmu"/><path fill="url(#ikcpide)" class="qd1f4bcmu"/><path fill="url(#iNjsHNc)" class="qd1f4bcmu"/><path fill="url(#igACNac)" class="qd1f4bcmu"/><path fill="url(#ijq8gLd)" class="qd1f4bcmu"/><path fill="url(#i6P8kpe)" class="qd1f4bcmu"/></g><path fill="url(#idzIsec)" class="qd1f4bcmu"/><g filter="url(#iu7QWAb)"><path fill="url(#iUOCMxc)" class="l7uz-vsxs"/></g><g filter="url(#ilhxdqe)"><path class="slkqr4dxe"/></g><g filter="url(#iMsJ9Ob)"><path class="f3mb20zwg"/><path fill="url(#iKmJrxb)" class="gmu2-kb6q"/><path fill="url(#iFYCQ4d)" class="gmu2-kb6q"/><path fill="url(#iM93BBe)" class="gmu2-kb6q"/></g><path class="m7a3_-bjh"/><path fill="url(#ils0gwb)" class="cmcdn-was"/><path fill="url(#iCSH9rb)" class="cmcdn-was"/><g filter="url(#iDendLb)"><path class="jeq3aabgf"/><path fill="url(#iqBO7cd)" class="jikm2ebxt"/><path fill="url(#iiKafSd)" class="jikm2ebxt"/><path fill="url(#iLGRdpc)" class="jikm2ebxt"/></g><path stroke="url(#ibsGGcb)" class="nt56v0bmc"/><path class="nah151h4l"/><path class="dqwtbwb7i"/><rect fill="url(#in55Gob)" class="hp1-lntzo"/><rect fill="url(#iHSvplb)" class="y3litn8ss"/><path class="rkvck2l4b"/><path fill="url(#iNIBBAb)" class="isd0anbsl"/><path class="v8e-ilb6v"/><g filter="url(#igI1X7t)"><path fill="url(#insFE5c)" class="kvwu28b_k"/></g><g filter="url(#iiaTRCd)"><ellipse transform="rotate(-27.914 11.516 16.875)" class="yxdp9q17q"/><ellipse fill="url(#iQz6usc)" transform="rotate(-27.914 11.516 16.875)" class="yjv_htq2r"/></g><path class="cm10kuboo"/><path fill="url(#igDh59b)" class="o1byjzbjo"/><path class="h7858pb_e"/><g filter="url(#i8IfhAe)"><path class="af_cnho3e"/><path fill="url(#iIYMBmd)" class="ufdsuhd5x"/></g><g filter="url(#il2jiNc)"><path fill="url(#i5auCwc)" class="f20kne-xq"/></g><g filter="url(#i5tsa5d)"><path class="m47w7ma-t"/></g><g filter="url(#iWP2gkc)"><path stroke="url(#i20Td9c)" class="ttkzf-b9r"/></g><g filter="url(#i2Ds02F)"><path class="pakas2bpr"/></g><g filter="url(#i5Dytqc)"><path stroke="url(#i9Gejwd)" class="cntyspjmk"/></g><defs><radialGradient id="itL8nzd" cx="0" cy="0" r="1" gradientTransform="rotate(-36.06 39.95 -30.582)scale(1.93052 2.20343)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="g7lt91bhf"/><stop offset="1" class="ze1cb0iau"/></radialGradient><radialGradient id="i3ALmkc" cx="0" cy="0" r="1" gradientTransform="matrix(1.64694 -3.0292 1.773 .96396 24.87 19.803)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ezktjkbgg"/><stop offset="1" class="j3anadbkm"/></radialGradient><radialGradient id="iPZk2De" cx="0" cy="0" r="1" gradientTransform="matrix(.51997 .5147 -.66351 .67031 24.954 18.156)" gradientUnits="userSpaceOnUse"><stop class="i4pfhbczn"/><stop offset="1" class="xjk10obil"/></radialGradient><radialGradient id="iP1z2Mb" cx="0" cy="0" r="1" gradientTransform="matrix(3.31277 0 0 5.79738 4.067 18.156)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="n91c-gs8j"/><stop offset="1" class="qo7u-3bcf"/></radialGradient><radialGradient id="i7KUjVb" cx="0" cy="0" r="1" gradientTransform="matrix(3.31277 0 0 5.79738 4.067 18.156)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="aik_z9b6i"/><stop offset="1" class="k1mq2zvhc"/></radialGradient><radialGradient id="iBxddSb" cx="0" cy="0" r="1" gradientTransform="rotate(152.026 9.325 10.324)scale(17.0552 31.3253)" gradientUnits="userSpaceOnUse"><stop offset=".15" class="b941pszbd"/><stop offset=".84" class="an2z3bh_n"/></radialGradient><radialGradient id="iuVaLLd" cx="0" cy="0" r="1" gradientTransform="rotate(158.66 12.358 6.796)scale(9.9616 12.7935)" gradientUnits="userSpaceOnUse"><stop class="qu138u1vx"/><stop offset="1" class="ymass5xxg"/></radialGradient><radialGradient id="ieGYgvc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.625 3.09375 0 20.935 15.848)" gradientUnits="userSpaceOnUse"><stop class="tdf8y8b-o"/><stop offset="1" class="i8l41_vns"/></radialGradient><radialGradient id="ikcpide" cx="0" cy="0" r="1" gradientTransform="rotate(-90 13.94 2.19)scale(3.3125)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="exp0x4b7y"/><stop offset="1" class="defr8xbsy"/></radialGradient><radialGradient id="iNjsHNc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.35307 -1.63196 1.28997 -1.85996 24.971 10.414)" gradientUnits="userSpaceOnUse"><stop offset=".584" class="kkvxk5bgp"/><stop offset="1" class="hqnmvfy3x"/></radialGradient><radialGradient id="igACNac" cx="0" cy="0" r="1" gradientTransform="rotate(127.136 .692 7.037)scale(2.8667 2.49422)" gradientUnits="userSpaceOnUse"><stop offset=".476" class="f6rartb0p"/><stop offset="1" class="cr41qy9nb"/></radialGradient><radialGradient id="ijq8gLd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.75 -4.63513 0 17.688 4.192)" gradientUnits="userSpaceOnUse"><stop class="js4qrv-5b"/><stop offset="1" class="rxz03eb9j"/></radialGradient><radialGradient id="i6P8kpe" cx="0" cy="0" r="1" gradientTransform="matrix(3.97576 4.25652 -7.55572 7.05734 9.467 6.299)" gradientUnits="userSpaceOnUse"><stop class="zj_ftnbtm"/><stop offset="1" class="o6tju3brk"/></radialGradient><radialGradient id="idzIsec" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.8125 26.0906 0 16.125 30.067)" gradientUnits="userSpaceOnUse"><stop class="n4ctu3bta"/><stop offset="1" class="hnfwuncqv"/></radialGradient><radialGradient id="ils0gwb" cx="0" cy="0" r="1" gradientTransform="rotate(139.273 2.441 6.064)scale(4.16691 7.99724)" gradientUnits="userSpaceOnUse"><stop class="rlhs-hbwc"/><stop offset="1" class="xi80kbc0k"/></radialGradient><radialGradient id="iCSH9rb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.04688 -.9516 0 7.09 14.91)" gradientUnits="userSpaceOnUse"><stop offset=".237" class="l9fk14bxd"/><stop offset="1" class="uyez41bsl"/></radialGradient><radialGradient id="iqBO7cd" cx="0" cy="0" r="1" gradientTransform="matrix(1.98438 -2.09375 .72837 .69032 24.622 13.348)" gradientUnits="userSpaceOnUse"><stop offset=".231" class="aq7827bba"/><stop offset="1" class="tco_4qs8v"/></radialGradient><radialGradient id="iiKafSd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46875 2.625 -2.01353 -1.12662 25.904 9.192)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="wgw2105cx"/><stop offset="1" class="fj_enu3ru"/></radialGradient><radialGradient id="iLGRdpc" cx="0" cy="0" r="1" gradientTransform="matrix(.32886 -4.54687 .85753 .06202 26.841 16.442)" gradientUnits="userSpaceOnUse"><stop class="bddxqszam"/><stop offset="1" class="bwtw0srgi"/></radialGradient><radialGradient id="iNIBBAb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68433 -1.993 0 12.021 17.675)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="xbuk-xbxm"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="zs1u76b3p"/></radialGradient><radialGradient id="iQz6usc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.34 3.077)scale(.92129 1.10743)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="igDh59b" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68424 -1.9929 0 20.158 17.676)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="xbuk-xbxm"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="zs1u76b3p"/></radialGradient><radialGradient id="iIYMBmd" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 14.08 3.773)scale(.70528 .97101)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iNL63Dc" width="6.553" height="6.553" x="21.802" y="14.754" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.529412 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20107"/></filter><filter id="iT35k8b" width="4.991" height="4.991" x="22.459" y="15.661" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20107" stdDeviation=".25"/></filter><filter id="itTFGSc" width="6.503" height="6.303" x="4.067" y="15.004" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.470588 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20107"/></filter><filter id="iVSSLNb" width="6.503" height="6.303" x="4.067" y="15.004" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.643137 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20107"/></filter><filter id="itFNe6d" width="4.991" height="4.991" x="4.723" y="15.661" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20107" stdDeviation=".25"/></filter><filter id="ifQEUWd" width="20.793" height="25.5" x="6.104" y="4.567" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.615686 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20107"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.941176 0 0 0 0 0.745098 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_20107" result="effect2_innerShadow_3987_20107"/></filter><filter id="iu7QWAb" width="11.918" height="9.719" x="15.036" y="6.637" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20107" stdDeviation="1"/></filter><filter id="ilhxdqe" width="4.796" height="6.408" x="13.272" y="16.693" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20107" stdDeviation=".375"/></filter><filter id="iMsJ9Ob" width="3.796" height="5.408" x="14.272" y="16.917" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20107" stdDeviation=".125"/></filter><filter id="iDendLb" width="4.3" height="9.2" x="23.17" y="7.867" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.580392 0 0 0 0 0.568627 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20107"/></filter><filter id="igI1X7t" width="1.493" height="1.594" x="12.245" y="16.428" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20107" stdDeviation=".1"/></filter><filter id="iiaTRCd" width="1.529" height="1.141" x="10.751" y="16.305" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20107" stdDeviation=".05"/></filter><filter id="i8IfhAe" width="1.294" height="1.125" x="18.875" y="16.32" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20107" stdDeviation=".05"/></filter><filter id="il2jiNc" width="1.316" height="1.357" x="20.528" y="16.546" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20107" stdDeviation=".1"/></filter><filter id="i5tsa5d" width="5.214" height="3" x="18.514" y="11.754" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.305882 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20107"/></filter><filter id="iWP2gkc" width="4.458" height="2.061" x="18.789" y="12.144" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20107" stdDeviation=".2"/></filter><filter id="i2Ds02F" width="5.214" height="3" x="8.912" y="11.754" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.305882 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20107"/></filter><filter id="i5Dytqc" width="4.458" height="2.061" x="9.093" y="12.144" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20107" stdDeviation=".2"/></filter><linearGradient id="i2V8gUc" x1="27.005" x2="25.459" y1="16.095" y2="20.883" gradientUnits="userSpaceOnUse"><stop class="kwz3apblc"/><stop offset="1" class="gx0xrfbie"/></linearGradient><linearGradient id="iXtoddd" x1="7.218" x2="5.934" y1="18.715" y2="18.715" gradientUnits="userSpaceOnUse"><stop class="s236rjbsc"/><stop offset="1" class="o6sle6pni"/></linearGradient><linearGradient id="iUOCMxc" x1="15.727" x2="30.915" y1="14.286" y2="8.848" gradientUnits="userSpaceOnUse"><stop class="yxv2rcevr"/><stop offset="1" class="krb9qn5ow"/></linearGradient><linearGradient id="iKmJrxb" x1="14.652" x2="16.3" y1="20.126" y2="20.126" gradientUnits="userSpaceOnUse"><stop class="gs643vbjw"/><stop offset="1" class="v4v-qb7kx"/></linearGradient><linearGradient id="iFYCQ4d" x1="17.818" x2="16.017" y1="20.716" y2="20.692" gradientUnits="userSpaceOnUse"><stop class="sbp9bz1ap"/><stop offset="1" class="xrkexibub"/></linearGradient><linearGradient id="iM93BBe" x1="16.512" x2="16.512" y1="22.075" y2="21.026" gradientUnits="userSpaceOnUse"><stop class="rxh459f4v"/><stop offset="1" class="lemuo5beu"/></linearGradient><linearGradient id="ibsGGcb" x1="14.236" x2="15.047" y1="25.016" y2="23.734" gradientUnits="userSpaceOnUse"><stop class="pn2_jabhi"/><stop offset=".663" class="z9945l-5h"/></linearGradient><linearGradient id="in55Gob" x1="13.17" x2="17.938" y1="8.21" y2="8.21" gradientUnits="userSpaceOnUse"><stop class="h03qp6b7q"/><stop offset="1" class="fe41ylbea"/></linearGradient><linearGradient id="iHSvplb" x1="13.313" x2="19.844" y1="10.59" y2="10.59" gradientUnits="userSpaceOnUse"><stop class="nuncsrbux"/><stop offset="1" class="bybo9k6dd"/></linearGradient><linearGradient id="insFE5c" x1="13.408" x2="12.823" y1="17.154" y2="17.515" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i5auCwc" x1="21.608" x2="21.023" y1="17.154" y2="17.515" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i20Td9c" x1="22.646" x2="19.154" y1="13.606" y2="13.606" gradientUnits="userSpaceOnUse"><stop class="kwz2g5lgk"/><stop offset="1" class="mv5v459od"/></linearGradient><linearGradient id="i9Gejwd" x1="13.147" x2="9.693" y1="12.744" y2="14.088" gradientUnits="userSpaceOnUse"><stop class="kwz2g5lgk"/><stop offset="1" class="mv5v459od"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:old-man-medium-light" /></template>
<style>
.af_cnho3e {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M20.04 16.516c.118.159-.13.352-.412.562s-.49.36-.609.2c-.119-.158.014-.457.296-.668c.281-.21.606-.253.724-.094");
}

.aik_z9b6i {
  stop-color: var(--svg-color--c28775, #C28775);
}

.an2z3bh_n {
  stop-color: var(--svg-color--c68e7c, #C68E7C);
}

.aq7827bba {
  stop-color: var(--svg-color--8f8286, #8F8286);
}

.b941pszbd {
  stop-color: var(--svg-color--fac39e, #FAC39E);
}

.bddxqszam {
  stop-color: var(--svg-color--b1adb0, #B1ADB0);
}

.bwtw0srgi {
  stop-color: var(--svg-color--b1adb0, #B1ADB0);
  stop-opacity: 0;
}

.bybo9k6dd {
  stop-color: var(--svg-color--d7a78c, #D7A78C);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cm10kuboo {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.547 15.658c1.218 0 2.247.839 2.526 1.973a.51.51 0 0 1-.499.636h-4.16a.43.43 0 0 1-.423-.507a2.606 2.606 0 0 1 2.556-2.103");
}

.cmcdn-was {
  d: path("M8.356 11.615a2 2 0 1 0-3.245-1.26l.407 5.714c.04.563.508.99 1.072.99V13.54a1 1 0 0 1 .366-.773l1.403-1.15z");
}

.cntyspjmk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M12.951 12.762c-.883-.07-2.195.04-3.258.844");
}

.comlzxbct {
  d: path("M7.218 20.151a1.995 1.995 0 1 0 0-3.99a1.995 1.995 0 0 0 0 3.99");
}

.cr41qy9nb {
  stop-color: var(--svg-color--af7861, #AF7861);
  stop-opacity: 0;
}

.defr8xbsy {
  stop-color: var(--svg-color--c0827a, #C0827A);
  stop-opacity: 0;
}

.dqwtbwb7i {
  fill: var(--svg-color--c78d7d, #C78D7D);
  d: path("M13.335 18.878a.5.5 0 0 1 .724.69l-.001.001l-.002.002l-.004.004l-.011.012a2 2 0 0 1-.169.15a3.56 3.56 0 0 1-2.255.806a.5.5 0 1 1 0-1a2.56 2.56 0 0 0 1.718-.665");
}

.exp0x4b7y {
  stop-color: var(--svg-color--c0827a, #C0827A);
}

.ezktjkbgg {
  stop-color: var(--svg-color--d79a76, #D79A76);
  stop-opacity: 0;
}

.f20kne-xq {
  d: path("M21.644 17.609a1.57 1.57 0 0 0-.432-.863l-.484.532l.218.426z");
}

.f3mb20zwg {
  fill: var(--svg-color--e4ac8f, #E4AC8F);
  d: path("m15.567 17.675l-1 3.1c-.2.6.3 1.3.9 1.3h1.4c.7 0 1.1-.6.9-1.3l-.956-3.1c-.226-.655-.944-.7-1.244 0");
}

.f6rartb0p {
  stop-color: var(--svg-color--af7861, #AF7861);
}

.fe41ylbea {
  stop-color: var(--svg-color--d3a485, #D3A485);
}

.fj_enu3ru {
  stop-color: var(--svg-color--c0bfc0, #C0BFC0);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g7lt91bhf {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
}

.gmu2-kb6q {
  d: path("m15.567 17.675l-1 3.1c-.2.6.3 1.3.9 1.3h1.4c.7 0 1.1-.6.9-1.3l-.956-3.1c-.226-.655-.944-.7-1.244 0");
}

.gs643vbjw {
  stop-color: var(--svg-color--cb9173, #CB9173);
}

.gx0xrfbie {
  stop-color: var(--svg-color--dca189, #DCA189);
}

.gzijw2msn {
  d: path("M24.954 20.151a1.995 1.995 0 1 0 0-3.99a1.995 1.995 0 0 0 0 3.99");
}

.h03qp6b7q {
  stop-color: var(--svg-color--c19479, #C19479);
}

.h7858pb_e {
  fill: var(--svg-color--000, #000);
  d: path("M19.209 17.828c0-.53.423-.953.953-.953s.953.424.953.953a.94.94 0 0 1-.106.439h-1.687a.86.86 0 0 1-.113-.439");
}

.hnfwuncqv {
  stop-color: var(--svg-color--c68a84, #C68A84);
  stop-opacity: 0;
}

.hp1-lntzo {
  width: 6px;
  height: 1px;
  x: 13.17px;
  y: 7.21px;
  rx: 0.5px;
}

.hqnmvfy3x {
  stop-color: var(--svg-color--d59e71, #D59E71);
  stop-opacity: 0;
}

.i4pfhbczn {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
}

.i8l41_vns {
  stop-color: var(--svg-color--e1a18c, #E1A18C);
  stop-opacity: 0;
}

.isd0anbsl {
  d: path("M12.018 16.164a1.664 1.664 0 0 0-1.604 2.103h3.215c.037-.144.06-.288.06-.439a1.675 1.675 0 0 0-1.671-1.664");
}

.j3anadbkm {
  stop-color: var(--svg-color--d79a76, #D79A76);
}

.jeq3aabgf {
  fill: var(--svg-color--9f9aa1, #9F9AA1);
  d: path("M23.904 11.615a2 2 0 1 1 3.246-1.26l-.409 5.714c-.04.563-.508.998-1.071.998V13.54a1 1 0 0 0-.366-.773l-1.403-1.15z");
}

.jikm2ebxt {
  d: path("M23.904 11.615a2 2 0 1 1 3.246-1.26l-.409 5.714c-.04.563-.508.998-1.071.998V13.54a1 1 0 0 0-.366-.773l-1.403-1.15z");
}

.js4qrv-5b {
  stop-color: var(--svg-color--dfb48e, #DFB48E);
}

.k1mq2zvhc {
  stop-color: var(--svg-color--ba7867, #BA7867);
}

.kkvxk5bgp {
  stop-color: var(--svg-color--d59e71, #D59E71);
}

.krb9qn5ow {
  stop-color: var(--svg-color--fcc7a6, #FCC7A6);
  stop-opacity: 0;
}

.kvwu28b_k {
  d: path("M13.538 17.633c0-.538-.437-.896-.556-1.005l-.537.52l.33.674z");
}

.kwz2g5lgk {
  stop-color: var(--svg-color--a8a7a9, #A8A7A9);
}

.kwz3apblc {
  stop-color: var(--svg-color--f5c8a5, #F5C8A5);
}

.l7uz-vsxs {
  d: path("m24.11 8.637l-5.739 1.913a1.953 1.953 0 0 0 .877 3.788l5.706-.764z");
}

.l9fk14bxd {
  stop-color: var(--svg-color--735551, #735551);
}

.lemuo5beu {
  stop-color: var(--svg-color--c98583, #C98583);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.m47w7ma-t {
  stroke: var(--svg-color--8a8a8a, #8A8A8A);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-75px, 1.75px);
  d: path("M19.389 13.067c.71-.094 2.086-.078 3.164.812");
}

.m7a3_-bjh {
  fill: var(--svg-color--7f7680, #7F7680);
  d: path("M8.356 11.615a2 2 0 1 0-3.245-1.26l.407 5.714c.04.563.508.99 1.072.99V13.54a1 1 0 0 1 .366-.773l1.403-1.15z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mv5v459od {
  stop-color: var(--svg-color--a8a7a9, #A8A7A9);
  stop-opacity: 0;
}

.n4ctu3bta {
  stop-color: var(--svg-color--b46d8a, #B46D8A);
}

.n91c-gs8j {
  stop-color: var(--svg-color--865d5f, #865D5F);
}

.nah151h4l {
  fill: var(--svg-color--e5a890, #E5A890);
  d: path("M18.11 18.85a.5.5 0 0 1 .706.04c.195.218.377.37.612.473c.24.106.575.18 1.095.18a.5.5 0 0 1 0 1c-.612 0-1.094-.086-1.499-.265c-.409-.18-.701-.44-.954-.721a.5.5 0 0 1 .04-.706");
}

.nhij6gb6h {
  d: path("M7.218 21.308a3.152 3.152 0 1 0 0-6.304a3.152 3.152 0 0 0 0 6.304");
}

.nt56v0bmc {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.61 23.243a.335.335 0 0 0-.4.07a.305.305 0 0 0-.034.392a3.58 3.58 0 0 0 2.994 1.6a3.58 3.58 0 0 0 2.994-1.6a.31.31 0 0 0-.034-.396a.34.34 0 0 0-.4-.066a5.5 5.5 0 0 1-2.56.607c-.938 0-1.82-.221-2.56-.607Z");
}

.nuncsrbux {
  stop-color: var(--svg-color--be8f77, #BE8F77);
}

.o-87xdcfh {
  fill: var(--svg-color--d79e81, #D79E81);
  d: path("M24.954 20.151a1.995 1.995 0 1 0 0-3.99a1.995 1.995 0 0 0 0 3.99");
}

.o1byjzbjo {
  d: path("M20.162 16.164a1.664 1.664 0 0 1 1.603 2.103h-3.214a1.7 1.7 0 0 1-.06-.439a1.67 1.67 0 0 1 1.67-1.664");
}

.o6sle6pni {
  stop-color: var(--svg-color--b87862, #B87862);
}

.o6tju3brk {
  stop-color: var(--svg-color--c29778, #C29778);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.pakas2bpr {
  stroke: var(--svg-color--8a8a8a, #8A8A8A);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-75px, 1.75px);
  d: path("M12.951 13.067c-.71-.094-2.086-.078-3.164.812");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pn2_jabhi {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
}

.qd1f4bcmu {
  d: path("M15.27 4.567c-5.2 0-9.2 4.4-8.9 9.5l.8 10.4c.3 3.3 2.8 5.6 6 5.6h6c3.1 0 5.7-2.3 6-5.6l.7-10.4c.4-5.2-3.7-9.5-8.9-9.5z");
}

.qo7u-3bcf {
  stop-color: var(--svg-color--76594a, #76594A);
}

.qu138u1vx {
  stop-color: var(--svg-color--fbca9f, #FBCA9F);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.rkvck2l4b {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.632 15.658a2.6 2.6 0 0 0-2.526 1.974a.51.51 0 0 0 .499.635h4.16a.43.43 0 0 0 .423-.507a2.61 2.61 0 0 0-2.556-2.103");
}

.rlhs-hbwc {
  stop-color: var(--svg-color--bbb6b3, #BBB6B3);
}

.rxh459f4v {
  stop-color: var(--svg-color--c98583, #C98583);
}

.rxz03eb9j {
  stop-color: var(--svg-color--dfb48e, #DFB48E);
  stop-opacity: 0;
}

.s236rjbsc {
  stop-color: var(--svg-color--af6f5d, #AF6F5D);
}

.sbp9bz1ap {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
}

.slkqr4dxe {
  fill: var(--svg-color--c68378, #C68378);
  d: path("m15.638 17.95l-1.571 3.1c-.2.6.3 1.3.9 1.3h1.4c.7 0 1.1-.6.9-1.3l-.9-3.1c-.227-.654-.429-.7-.729 0");
}

.tco_4qs8v {
  stop-color: var(--svg-color--8f8286, #8F8286);
  stop-opacity: 0;
}

.tdf8y8b-o {
  stop-color: var(--svg-color--e1a18c, #E1A18C);
}

.ttkzf-b9r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M19.389 12.762c.883-.07 2.195.04 3.258.844");
}

.ufdsuhd5x {
  d: path("M20.04 16.516c.118.159-.13.352-.412.562s-.49.36-.609.2c-.119-.158.014-.457.296-.668c.281-.21.606-.253.724-.094");
}

.uyez41bsl {
  stop-color: var(--svg-color--735551, #735551);
  stop-opacity: 0;
}

.v4v-qb7kx {
  stop-color: var(--svg-color--cb9173, #CB9173);
  stop-opacity: 0;
}

.v8e-ilb6v {
  fill: var(--svg-color--000, #000);
  d: path("M12.97 17.828a.95.95 0 0 0-.952-.953a.95.95 0 0 0-.953.953c0 .16.037.31.106.439h1.686a.95.95 0 0 0 .114-.439");
}

.wgw2105cx {
  stop-color: var(--svg-color--c0bfc0, #C0BFC0);
}

.xbuk-xbxm {
  stop-color: var(--svg-color--7f584b, #7F584B);
}

.xi80kbc0k {
  stop-color: var(--svg-color--807680, #807680);
  stop-opacity: 0;
}

.xjk10obil {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
  stop-opacity: 0;
}

.xrkexibub {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
  stop-opacity: 0;
}

.y3litn8ss {
  width: 10px;
  height: 1px;
  x: 11.126px;
  y: 9.59px;
  rx: 0.5px;
}

.yjv_htq2r {
  cx: 11.516px;
  cy: 16.875px;
  rx: 0.726px;
  ry: 0.368px;
}

.ymass5xxg {
  stop-color: var(--svg-color--fbca9f, #FBCA9F);
  stop-opacity: 0;
}

.yxdp9q17q {
  cx: 11.516px;
  cy: 16.875px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.726px;
  ry: 0.368px;
}

.yxv2rcevr {
  stop-color: var(--svg-color--fcc7a6, #FCC7A6);
}

.z9945l-5h {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
  stop-opacity: 0;
}

.zal6rzb4g {
  d: path("M24.954 21.308a3.152 3.152 0 1 0 0-6.304a3.152 3.152 0 0 0 0 6.304");
}

.ze1cb0iau {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
  stop-opacity: 0;
}

.zj_ftnbtm {
  stop-color: var(--svg-color--c29778, #C29778);
}

.zs1u76b3p {
  stop-color: var(--svg-color--5d4139, #5D4139);
}

</style>
