<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iVBN6ie)"><path fill="url(#i82T6te)" class="sxtt9buwm"/></g><g filter="url(#iBmkdQw)"><path class="chu8rz1zc"/></g><path fill="url(#iME30rd)" class="utk9urtwz"/><path fill="url(#izZkLnd)" class="utk9urtwz"/><path fill="url(#irCD7Md)" class="utk9urtwz"/><g filter="url(#iOU0AMb)"><path class="o_2-xybce"/></g><g filter="url(#ihiijdc)"><path fill="url(#i7yIjve)" class="u7rdqh7_o"/><path fill="url(#iyGlC1c)" class="u7rdqh7_o"/><path fill="url(#iPXQmGc)" class="u7rdqh7_o"/><path fill="url(#iG4qzyb)" class="u7rdqh7_o"/><path fill="url(#iUgVXee)" class="u7rdqh7_o"/><path fill="url(#ihYNawd)" class="u7rdqh7_o"/><path fill="url(#i1xYbFd)" class="u7rdqh7_o"/></g><path fill="url(#i5CJ1od)" class="u7rdqh7_o"/><g filter="url(#iRzBENc)"><path class="mvbdc-4yv"/></g><g filter="url(#iYvCyOd)"><path fill="url(#ic2SzWb)" class="hkhfzrbhi"/><path fill="url(#iDJ9qyo)" class="hkhfzrbhi"/><path fill="url(#ie7pXTd)" class="hkhfzrbhi"/><path fill="url(#inWngqb)" class="hkhfzrbhi"/></g><g filter="url(#iQTursc)"><path stroke="url(#iK1Fbte)" class="gqvi4zbis"/></g><path class="rk01-6bza"/><g filter="url(#iel8Zpe)"><path class="l1akyetgx"/></g><g filter="url(#isy49Jd)"><path class="pr6t7xbfa"/></g><path class="wix70tb9l"/><path fill="url(#i0kMb9c)" class="jcib18ibt"/><path class="r2jcdwb6u"/><g filter="url(#ij4bXIc)"><path fill="url(#ihsee4b)" class="o5axzqomd"/></g><g filter="url(#iETfy9d)"><ellipse transform="rotate(-27.914 11.27 16.163)" class="k0vf4980l"/><ellipse fill="url(#iTB3PYd)" transform="rotate(-27.914 11.27 16.163)" class="d9p065bcv"/></g><path class="h0ca9bcwk"/><path fill="url(#iZyVDet)" class="ec6lcbb4j"/><path class="uqpow5x8p"/><g filter="url(#iahwrpd)"><path class="t6eshb9nv"/><path fill="url(#i83Edld)" class="qsb7cbb4u"/></g><g filter="url(#iXGtA7g)"><path fill="url(#ivzACXc)" class="ufl-llb7p"/></g><g filter="url(#i4llvez)"><path class="x3do7rxua"/></g><g filter="url(#iSUOnDc)"><path class="s2jkbhznw"/></g><g filter="url(#iPC0DAe)"><path fill="url(#iWLky5b)" class="w_2pwxb_c"/></g><defs><filter id="iVBN6ie" width="6.2" height="6" x="3.846" y="14.551" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.639216 0 0 0 0 0.529412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2075"/></filter><filter id="iBmkdQw" width="4.632" height="4.632" x="4.53" y="15.236" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2075" stdDeviation=".25"/></filter><filter id="iOU0AMb" width="4.132" height="4.132" x="22.983" y="15.486" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2075" stdDeviation=".125"/></filter><filter id="ihiijdc" width="20.485" height="26.75" x="6.108" y="3.663" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.627451 0 0 0 0 0.529412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2075"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.682353 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3930_2075" result="effect2_innerShadow_3930_2075"/></filter><filter id="iRzBENc" width="4.5" height="5.836" x="13.358" y="16.488" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2075" stdDeviation=".25"/></filter><filter id="iYvCyOd" width="3.571" height="5.2" x="14.061" y="16.451" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2075" stdDeviation=".05"/></filter><filter id="iQTursc" width="6.619" height="2.54" x="12.537" y="22.532" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2075" stdDeviation=".075"/></filter><filter id="iel8Zpe" width="4.424" height="2.097" x="18.809" y="11.301" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.282353 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2075"/></filter><filter id="isy49Jd" width="4.424" height="2.069" x="9.009" y="11.329" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.462745 0 0 0 0 0.254902 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2075"/></filter><filter id="ij4bXIc" width="1.512" height="1.614" x="12.015" y="15.711" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2075" stdDeviation=".1"/></filter><filter id="iETfy9d" width="1.552" height="1.157" x="10.493" y="15.584" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2075" stdDeviation=".05"/></filter><filter id="iahwrpd" width="1.294" height="1.125" x="18.632" y="15.604" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2075" stdDeviation=".05"/></filter><filter id="iXGtA7g" width="1.316" height="1.357" x="20.284" y="15.831" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2075" stdDeviation=".1"/></filter><filter id="i4llvez" width="4.076" height="1.651" x="9.149" y="11.533" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2075" stdDeviation=".175"/></filter><filter id="iSUOnDc" width="3.97" height="1.737" x="19.087" y="11.533" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2075" stdDeviation=".175"/></filter><filter id="iPC0DAe" width="12.281" height="10.228" x="14" y="5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2075" stdDeviation="1"/></filter><radialGradient id="izZkLnd" cx="0" cy="0" r="1" gradientTransform="matrix(.72585 6.1391 -10.15745 1.20096 22.926 15.034)" gradientUnits="userSpaceOnUse"><stop offset=".739" class="r5djb7b3b"/><stop offset="1" class="sogr63b4w"/></radialGradient><radialGradient id="irCD7Md" cx="0" cy="0" r="1" gradientTransform="matrix(2.1774 -3.3871 2.8542 1.83482 23.924 18.33)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="wvh6w6olb"/><stop offset="1" class="hw3g0j7tn"/></radialGradient><radialGradient id="i7yIjve" cx="0" cy="0" r="1" gradientTransform="rotate(117.759 8.442 10.886)scale(17.7152 15.9561)" gradientUnits="userSpaceOnUse"><stop class="kkdrwb3vn"/><stop offset="1" class="fbc_k3bua"/></radialGradient><radialGradient id="iyGlC1c" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.17105 -8.57064 0 21.872 18.84)" gradientUnits="userSpaceOnUse"><stop class="rr62oxb8b"/><stop offset="1" class="ap20qmlty"/></radialGradient><radialGradient id="iPXQmGc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.36514 10.5925 0 9.405 29.413)" gradientUnits="userSpaceOnUse"><stop class="wi4wz997m"/><stop offset="1" class="mv5owlb7i"/></radialGradient><radialGradient id="iG4qzyb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.05461 19.43755 -18.9858 -2.98362 18.905 10.302)" gradientUnits="userSpaceOnUse"><stop offset=".822" class="pf4-r8bdy"/><stop offset="1" class="cz26r0b-z"/></radialGradient><radialGradient id="iUgVXee" cx="0" cy="0" r="1" gradientTransform="matrix(.53947 -2.38004 2.66131 .60323 11.789 15.023)" gradientUnits="userSpaceOnUse"><stop class="myd1qoqgk"/><stop offset="1" class="pen3j1etd"/></radialGradient><radialGradient id="ihYNawd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.91744 3.21246 0 20.28 15.063)" gradientUnits="userSpaceOnUse"><stop offset=".025" class="gv-oqwpoa"/><stop offset="1" class="k0ycpeb2r"/></radialGradient><radialGradient id="i1xYbFd" cx="0" cy="0" r="1" gradientTransform="matrix(3.75 6.125 -9.05643 5.54475 7.938 1.5)" gradientUnits="userSpaceOnUse"><stop class="k474snbsw"/><stop offset="1" class="l_k5n4ipq"/></radialGradient><radialGradient id="i5CJ1od" cx="0" cy="0" r="1" gradientTransform="matrix(3.61765 5.39474 -14.04102 9.41573 8.742 3.091)" gradientUnits="userSpaceOnUse"><stop class="qjwz04iur"/><stop offset="1" class="xx9gpp2wc"/></radialGradient><radialGradient id="i0kMb9c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.53876 -2.44757 0 11.784 16.344)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="xbuk-xbxm"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="s-ceiepmf"/></radialGradient><radialGradient id="iTB3PYd" cx="0" cy="0" r="1" gradientTransform="matrix(-.01467 -.93704 1.12636 -.01764 11.241 16.76)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iZyVDet" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51263 -2.40601 0 19.914 16.338)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="xbuk-xbxm"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="s-ceiepmf"/></radialGradient><radialGradient id="i83Edld" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 13.784 3.475)scale(.70528 .97101)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iWLky5b" cx="0" cy="0" r="1" gradientTransform="rotate(70.118 4.726 18.1)scale(5.28368 12.8423)" gradientUnits="userSpaceOnUse"><stop class="p9y9cslha"/><stop offset="1" class="fpwlizx-k"/></radialGradient><linearGradient id="i82T6te" x1="4.663" x2="8.195" y1="17.551" y2="17.052" gradientUnits="userSpaceOnUse"><stop class="h63ej3bml"/><stop offset="1" class="mt9ayye9m"/></linearGradient><linearGradient id="iME30rd" x1="27.039" x2="26.751" y1="15.427" y2="20.751" gradientUnits="userSpaceOnUse"><stop offset=".125" class="gmkb3s7ft"/><stop offset="1" class="hye7ay5ht"/></linearGradient><linearGradient id="ic2SzWb" x1="15.846" x2="17.381" y1="19.739" y2="19.739" gradientUnits="userSpaceOnUse"><stop class="f6og14bdq"/><stop offset="1" class="hk633lr2o"/></linearGradient><linearGradient id="iDJ9qyo" x1="13.92" x2="15.848" y1="19.471" y2="19.581" gradientUnits="userSpaceOnUse"><stop class="z_vmdubsa"/><stop offset=".203" class="umam-bfga"/><stop offset="1" class="oanih0n0r"/></linearGradient><linearGradient id="ie7pXTd" x1="15.846" x2="15.846" y1="20.426" y2="21.895" gradientUnits="userSpaceOnUse"><stop class="y-mxywbmo"/><stop offset=".845" class="ed0uty_4k"/></linearGradient><linearGradient id="inWngqb" x1="15.846" x2="15.846" y1="16.551" y2="17.711" gradientUnits="userSpaceOnUse"><stop class="vz54-0-jq"/><stop offset="1" class="vnxv0tbcs"/></linearGradient><linearGradient id="iK1Fbte" x1="14.608" x2="15.139" y1="24.821" y2="23.473" gradientUnits="userSpaceOnUse"><stop class="yzrfim5ub"/><stop offset="1" class="x4seihbeq"/></linearGradient><linearGradient id="ihsee4b" x1="13.195" x2="12.6" y1="16.447" y2="16.813" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ivzACXc" x1="21.365" x2="20.78" y1="16.439" y2="16.799" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-bald-medium-light" /></template>
<style>
.ap20qmlty {
  stop-color: var(--svg-color--fec49f, #FEC49F);
  stop-opacity: 0;
}

.chu8rz1zc {
  fill: var(--svg-color--b57562, #B57562);
  d: path("M6.846 19.367a1.816 1.816 0 1 0 0-3.632a1.816 1.816 0 0 0 0 3.632");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cz26r0b-z {
  stop-color: var(--svg-color--b47093, #B47093);
}

.d9p065bcv {
  cx: 11.27px;
  cy: 16.163px;
  rx: 0.739px;
  ry: 0.374px;
}

.ec6lcbb4j {
  d: path("M19.918 15.449a1.664 1.664 0 0 1 1.603 2.102h-3.214a1.7 1.7 0 0 1-.06-.438a1.67 1.67 0 0 1 1.671-1.664");
}

.ed0uty_4k {
  stop-color: var(--svg-color--cb8685, #CB8685);
}

.f6og14bdq {
  stop-color: var(--svg-color--e1aa8c, #E1AA8C);
}

.fbc_k3bua {
  stop-color: var(--svg-color--cd9681, #CD9681);
}

.fpwlizx-k {
  stop-color: var(--svg-color--ffd3aa, #FFD3AA);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.gmkb3s7ft {
  stop-color: var(--svg-color--fac7a3, #FAC7A3);
}

.gqvi4zbis {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.235 22.77a.34.34 0 0 0-.407.071a.31.31 0 0 0-.034.4a3.65 3.65 0 0 0 3.052 1.63a3.65 3.65 0 0 0 3.052-1.63a.314.314 0 0 0-.035-.404a.34.34 0 0 0-.406-.066a5.6 5.6 0 0 1-2.611.619a5.66 5.66 0 0 1-2.611-.62Z");
}

.gv-oqwpoa {
  stop-color: var(--svg-color--e2a28d, #E2A28D);
}

.h0ca9bcwk {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.304 14.942c1.217 0 2.246.84 2.526 1.974a.51.51 0 0 1-.5.635h-4.16a.43.43 0 0 1-.423-.506a2.606 2.606 0 0 1 2.557-2.103");
}

.h63ej3bml {
  stop-color: var(--svg-color--c58971, #C58971);
}

.hk633lr2o {
  stop-color: var(--svg-color--fecaa8, #FECAA8);
}

.hkhfzrbhi {
  d: path("m15.16 17.078l-.955 3.17c-.195.651.273 1.303.935 1.303h1.412c.662 0 1.13-.662.935-1.304l-.955-3.17a.71.71 0 0 0-1.373 0");
}

.hw3g0j7tn {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
  stop-opacity: 0;
}

.hye7ay5ht {
  stop-color: var(--svg-color--e0a48c, #E0A48C);
}

.jcib18ibt {
  d: path("M11.78 15.44a1.693 1.693 0 0 0-1.63 2.138h3.27q.059-.217.06-.446a1.704 1.704 0 0 0-1.7-1.692");
}

.k0vf4980l {
  cx: 11.27px;
  cy: 16.163px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.739px;
  ry: 0.374px;
}

.k0ycpeb2r {
  stop-color: var(--svg-color--e2a28d, #E2A28D);
  stop-opacity: 0;
}

.k474snbsw {
  stop-color: var(--svg-color--c39877, #C39877);
}

.kkdrwb3vn {
  stop-color: var(--svg-color--ffc9a7, #FFC9A7);
}

.l_k5n4ipq {
  stop-color: var(--svg-color--c39877, #C39877);
  stop-opacity: 0;
}

.l1akyetgx {
  fill: var(--svg-color--996435, #996435);
  d: path("M22.806 12.49c-.327-.284-.707-.585-1.282-.766c-.568-.179-1.278-.227-2.26-.106a.517.517 0 1 0 .125 1.026c.897-.11 1.446-.053 1.824.066c.37.117.62.305.913.56a.517.517 0 0 0 .68-.78");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mt9ayye9m {
  stop-color: var(--svg-color--bf796e, #BF796E);
}

.mv5owlb7i {
  stop-color: var(--svg-color--bc7b83, #BC7B83);
  stop-opacity: 0;
}

.mvbdc-4yv {
  fill: var(--svg-color--c8875f, #C8875F);
  d: path("m15.108 17.515l-1.204 3.005a1.005 1.005 0 0 0 .97 1.304h1.467c.687 0 1.173-.662.97-1.304l-1.125-3.005c-.213-.703-.855-.703-1.078 0");
}

.myd1qoqgk {
  stop-color: var(--svg-color--c1837b, #C1837B);
}

.o_2-xybce {
  fill: var(--svg-color--e5ac8a, #E5AC8A);
  d: path("M25.049 19.367a1.816 1.816 0 1 0 0-3.631a1.816 1.816 0 0 0 0 3.631");
}

.o5axzqomd {
  d: path("M13.327 16.933c0-.547-.445-.911-.565-1.021l-.547.528l.336.686z");
}

.oanih0n0r {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.p9y9cslha {
  stop-color: var(--svg-color--ffd3aa, #FFD3AA);
}

.pen3j1etd {
  stop-color: var(--svg-color--c1837b, #C1837B);
  stop-opacity: 0;
}

.pf4-r8bdy {
  stop-color: var(--svg-color--b47093, #B47093);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pr6t7xbfa {
  fill: var(--svg-color--935e2e, #935E2E);
  d: path("M9.487 12.288a5.17 5.17 0 0 1 3.242-.67a.517.517 0 0 1-.126 1.026a4.14 4.14 0 0 0-2.585.53a3 3 0 0 0-.171.112l-.005.004a.517.517 0 0 1-.634-.817z");
}

.qjwz04iur {
  stop-color: var(--svg-color--c2987c, #C2987C);
}

.qsb7cbb4u {
  d: path("M19.796 15.8c.118.159-.13.352-.411.563c-.282.21-.491.359-.61.2c-.118-.158.014-.458.296-.668s.606-.253.725-.095");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r2jcdwb6u {
  fill: var(--svg-color--000, #000);
  d: path("M12.75 17.132a.966.966 0 0 0-.97-.97a.966.966 0 0 0-.861 1.416h1.715a.96.96 0 0 0 .116-.446");
}

.r5djb7b3b {
  stop-color: var(--svg-color--d09180, #D09180);
  stop-opacity: 0;
}

.rk01-6bza {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M15.846 23.44a5.7 5.7 0 0 1-2.634-.625c-.26-.132-.54.161-.376.398a3.6 3.6 0 0 0 3.01 1.608a3.6 3.6 0 0 0 3.01-1.608c.164-.246-.116-.53-.376-.398a5.7 5.7 0 0 1-2.634.625");
}

.rr62oxb8b {
  stop-color: var(--svg-color--fec49f, #FEC49F);
}

.s-ceiepmf {
  stop-color: var(--svg-color--654843, #654843);
}

.s2jkbhznw {
  stroke: var(--svg-color--9e693e, #9E693E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M22.582 12.795c-.5-.484-1.695-.918-3.02-.75");
}

.sogr63b4w {
  stop-color: var(--svg-color--d09180, #D09180);
}

.sxtt9buwm {
  d: path("M6.846 20.551a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.t6eshb9nv {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.796 15.8c.118.159-.13.352-.411.563c-.282.21-.491.359-.61.2c-.118-.158.014-.458.296-.668s.606-.253.725-.095");
}

.u7rdqh7_o {
  d: path("M17.912 3.663h-4.147c-5.57 0-8.018 3.75-7.614 8.71l.7 10.69a7.3 7.3 0 0 0 7.244 6.35h3.518a7.3 7.3 0 0 0 7.244-6.35l.67-10.69c.53-4.703-2.115-8.71-7.615-8.71");
}

.ufl-llb7p {
  d: path("M21.4 16.894a1.57 1.57 0 0 0-.431-.863l-.485.532l.219.425z");
}

.umam-bfga {
  stop-color: var(--svg-color--d29879, #D29879);
}

.uqpow5x8p {
  fill: var(--svg-color--000, #000);
  d: path("M18.965 17.113c0-.53.424-.953.953-.953c.53 0 .953.423.953.953a.94.94 0 0 1-.106.438h-1.687a.86.86 0 0 1-.113-.438");
}

.utk9urtwz {
  d: path("M24.846 20.551a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.vnxv0tbcs {
  stop-color: var(--svg-color--f0b795, #F0B795);
  stop-opacity: 0;
}

.vz54-0-jq {
  stop-color: var(--svg-color--f0b795, #F0B795);
}

.w_2pwxb_c {
  d: path("m22.813 7l-5.269 1.232A2 2 0 0 0 16 10.18v1.747a1 1 0 0 0 .495.863l.572.335a.745.745 0 0 0 1.12-.643c0-.353.25-.658.595-.729l5.5-1.128c0-1.5-1.042-3.208-1.47-3.625");
}

.wi4wz997m {
  stop-color: var(--svg-color--bc7b83, #BC7B83);
}

.wix70tb9l {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.388 14.924a2.65 2.65 0 0 0-2.57 2.008a.52.52 0 0 0 .508.646h4.232a.436.436 0 0 0 .43-.515a2.66 2.66 0 0 0-2.6-2.139");
}

.wvh6w6olb {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
}

.x3do7rxua {
  stroke: var(--svg-color--9f6a40, #9F6A40);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M9.624 12.709c.408-.303 1.689-.808 3.126-.681");
}

.x4seihbeq {
  stop-color: var(--svg-color--d49c91, #D49C91);
  stop-opacity: 0;
}

.xbuk-xbxm {
  stop-color: var(--svg-color--7f584b, #7F584B);
}

.xx9gpp2wc {
  stop-color: var(--svg-color--c2987c, #C2987C);
  stop-opacity: 0;
}

.y-mxywbmo {
  stop-color: var(--svg-color--cb8685, #CB8685);
  stop-opacity: 0;
}

.yzrfim5ub {
  stop-color: var(--svg-color--d49c91, #D49C91);
}

.z_vmdubsa {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0.915;
}

</style>
