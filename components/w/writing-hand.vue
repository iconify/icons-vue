<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#icnsbxe)"><path fill="url(#ilTFbub)" class="ajl0ikidv"/><path fill="url(#iWMQ8kd)" class="ajl0ikidv"/></g><path fill="url(#iw6Jd1c)" class="tn3edfbno"/><path fill="url(#iUSp1qc)" class="tn3edfbno"/><rect fill="url(#ilI362d)" class="q7h9g6bki"/><rect fill="url(#ipPdonb)" class="q7h9g6bki"/><rect fill="url(#iTb1axe)" class="q7h9g6bki"/><path fill="url(#iACgHre)" class="fzcwmf9bu"/><path fill="url(#i3ZwzCv)" class="fzcwmf9bu"/><g filter="url(#izJCuXb)"><path class="wpsp30-0v"/></g><g filter="url(#iGmRTdd)"><path fill="url(#i65ZPnd)" class="ftokoof_m"/><path fill="url(#iLB6xSA)" class="ftokoof_m"/><path fill="url(#i3v7hqb)" class="ftokoof_m"/><path fill="url(#iAJSgVc)" class="ftokoof_m"/></g><path fill="url(#iefnYQd)" class="ftokoof_m"/><path fill="url(#ifRX7tb)" class="ftokoof_m"/><path fill="url(#i1cOVae)" class="v37qiyrdg"/><path fill="url(#i1cOVae)" class="ri12kgbds"/><path fill="url(#itbOJxd)" class="e4svvibki"/><path fill="url(#iHKjnxd)" class="e4svvibki"/><path fill="url(#i2hKNCS)" class="w79k2acia"/><path fill="url(#iWzfYGd)" class="w79k2acia"/><path fill="url(#ir3KG8c)" class="w79k2acia"/><path fill="url(#i3mTYAe)" class="n22n_obox"/><g filter="url(#iWQWW2c)"><path class="nc-ufo_mt"/></g><path fill="url(#i0CnC1b)" class="dd0jy3bvw"/><path fill="url(#ilbEgVd)" class="dd0jy3bvw"/><defs><linearGradient id="ilTFbub" x1="11.914" x2="4.985" y1="10.071" y2="21.98" gradientUnits="userSpaceOnUse"><stop class="e_uz1ccsd"/><stop offset="1" class="pde7wp_cs"/></linearGradient><linearGradient id="iw6Jd1c" x1="16.529" x2="20.534" y1="24.288" y2="29.334" gradientUnits="userSpaceOnUse"><stop class="b_hnrobne"/><stop offset="1" class="roy0h0bsx"/></linearGradient><linearGradient id="iUSp1qc" x1="30.064" x2="28.992" y1="29.985" y2="29.985" gradientUnits="userSpaceOnUse"><stop class="kfmc1sbdc"/><stop offset="1" class="wswbpgmku"/></linearGradient><linearGradient id="i65ZPnd" x1="17.139" x2="28.784" y1="13.161" y2="24.614" gradientUnits="userSpaceOnUse"><stop class="c9hzilbuh"/><stop offset="1" class="dmp-mg7ih"/></linearGradient><linearGradient id="iAJSgVc" x1="24.112" x2="23.758" y1="14.368" y2="15.468" gradientUnits="userSpaceOnUse"><stop class="hhhr5pb_v"/><stop offset="1" class="w48b-cdvb"/></linearGradient><linearGradient id="iefnYQd" x1="23.814" x2="22.001" y1="14.125" y2="17.875" gradientUnits="userSpaceOnUse"><stop class="bxojc456f"/><stop offset="1" class="webj0_bpa"/></linearGradient><linearGradient id="ifRX7tb" x1="30.376" x2="27.814" y1="21.188" y2="21.188" gradientUnits="userSpaceOnUse"><stop class="bxojc456f"/><stop offset="1" class="webj0_bpa"/></linearGradient><linearGradient id="itbOJxd" x1="16.345" x2="20.896" y1="5.063" y2="7.563" gradientUnits="userSpaceOnUse"><stop class="w97l3zkii"/><stop offset="1" class="x6g_n69lf"/></linearGradient><linearGradient id="iHKjnxd" x1="20.454" x2="20.126" y1="7.211" y2="7.031" gradientUnits="userSpaceOnUse"><stop class="j8s0uwfjz"/><stop offset="1" class="bf59mn5sh"/><stop offset="1" class="rphdcwbhu"/></linearGradient><linearGradient id="i2hKNCS" x1="4.939" x2="7.595" y1="27.964" y2="28.563" gradientUnits="userSpaceOnUse"><stop class="lp_1nfnub"/><stop offset="1" class="qa3j86b_z"/></linearGradient><linearGradient id="iWzfYGd" x1="7.69" x2="6.257" y1="29.509" y2="28.682" gradientUnits="userSpaceOnUse"><stop class="cbd7-j3cx"/><stop offset="1" class="qam400kgw"/></linearGradient><linearGradient id="ir3KG8c" x1="6.474" x2="6.353" y1="27.093" y2="27.32" gradientUnits="userSpaceOnUse"><stop class="i8x2ytb4x"/><stop offset="1" class="i2mp3ny5q"/></linearGradient><linearGradient id="i3mTYAe" x1="4.942" x2="5.44" y1="29.424" y2="29.824" gradientUnits="userSpaceOnUse"><stop class="itudfnbzj"/><stop offset="1" class="wq3kgrbvi"/></linearGradient><linearGradient id="i0CnC1b" x1="10.564" x2="13.345" y1="19.781" y2="22.65" gradientUnits="userSpaceOnUse"><stop class="o53kwvbya"/><stop offset="1" class="bxvzi7g4t"/></linearGradient><radialGradient id="iWMQ8kd" cx="0" cy="0" r="1" gradientTransform="rotate(151.144 5.744 6.939)scale(2.4229 2.39271)" gradientUnits="userSpaceOnUse"><stop class="dzdsl0mec"/><stop offset="1" class="wi1sqm47n"/></radialGradient><radialGradient id="ilI362d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.7323 1.68053 -2.0249 -2.08727 13.972 26.384)" gradientUnits="userSpaceOnUse"><stop class="lrjmfbpfe"/><stop offset="1" class="grg3q37ve"/></radialGradient><radialGradient id="ipPdonb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.66523 -4.10231 0 12.349 25.55)" gradientUnits="userSpaceOnUse"><stop offset=".776" class="kc7ykhbib"/><stop offset="1" class="xw9lkcbkl"/></radialGradient><radialGradient id="iTb1axe" cx="0" cy="0" r="1" gradientTransform="matrix(1.5309 1.62182 -2.36979 2.23692 9.933 26.75)" gradientUnits="userSpaceOnUse"><stop class="i104-lbhq"/><stop offset="1" class="l34lt5mia"/></radialGradient><radialGradient id="iACgHre" cx="0" cy="0" r="1" gradientTransform="rotate(-60.819 24.957 5.412)scale(22.0482 16.0052)" gradientUnits="userSpaceOnUse"><stop class="k9cdp4y8v"/><stop offset="1" class="y4su1hbhi"/></radialGradient><radialGradient id="i3ZwzCv" cx="0" cy="0" r="1" gradientTransform="matrix(2.78125 -4.4375 3.06055 1.91824 12.442 21.745)" gradientUnits="userSpaceOnUse"><stop class="yo5qxhbmi"/><stop offset="1" class="zvxmjroaa"/></radialGradient><radialGradient id="iLB6xSA" cx="0" cy="0" r="1" gradientTransform="matrix(-6.99141 -6.95223 4.42821 -4.45317 22.776 30.354)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="vpkiefhxu"/><stop offset="1" class="f9dpzacts"/></radialGradient><radialGradient id="i3v7hqb" cx="0" cy="0" r="1" gradientTransform="rotate(149.931 11.96 13)scale(5.17395 1.57367)" gradientUnits="userSpaceOnUse"><stop class="mkdu6zbgz"/><stop offset="1" class="hkig96m7k"/></radialGradient><radialGradient id="i1cOVae" cx="0" cy="0" r="1" gradientTransform="rotate(-45.605 30.782 -5.494)scale(7.31574 8.64406)" gradientUnits="userSpaceOnUse"><stop offset=".249" class="ztplpabxo"/><stop offset="1" class="fam_wqb4o"/></radialGradient><radialGradient id="ilbEgVd" cx="0" cy="0" r="1" gradientTransform="matrix(3.73694 -2.5625 3.33108 4.85777 8.67 25.969)" gradientUnits="userSpaceOnUse"><stop class="o53kwvbya"/><stop offset="1" class="bxvzi7g4t"/></radialGradient><filter id="icnsbxe" width="15.189" height="15.507" x="1.465" y="8.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy="-1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.435294 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6291"/></filter><filter id="izJCuXb" width="12.051" height="18.937" x="6.69" y="6.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6291" stdDeviation=".5"/></filter><filter id="iGmRTdd" width="21.213" height="16.921" x="8.671" y="11.419" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.509804 0 0 0 0 0.65098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6291"/></filter><filter id="iWQWW2c" width="20.805" height="10.441" x="9.824" y="18.26" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6291" stdDeviation="1"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:writing-hand" /></template>
<style>
.ajl0ikidv {
  d: path("m6.784 12.051l.359-.576a5 5 0 0 1 6.632-1.75l2.88 1.565l-4.306 7.08l-1.415-3.54l-4.317 7.519a2.535 2.535 0 0 1-3.49.922l-.116-.069a2.535 2.535 0 0 1-.88-3.494l3.62-5.986l-.005-.004l.281-.451l.583-.964q.08-.133.174-.252");
}

.b_hnrobne {
  stop-color: var(--svg-color--dd7828, #DD7828);
}

.bf59mn5sh {
  stop-color: var(--svg-color--d4c5de, #D4C5DE);
  stop-opacity: 0;
}

.bxojc456f {
  stop-color: var(--svg-color--f8d15d, #F8D15D);
}

.bxvzi7g4t {
  stop-color: var(--svg-color--f0a51d, #F0A51D);
  stop-opacity: 0;
}

.c9hzilbuh {
  stop-color: var(--svg-color--ffd142, #FFD142);
}

.cbd7-j3cx {
  stop-color: var(--svg-color--ff8dc2, #FF8DC2);
}

.dd0jy3bvw {
  d: path("m13.118 19.936l1.758-1.103a5.25 5.25 0 0 1 3.498-.757l1.468.2l-1.939 6.723l-.01-.016a.91.91 0 0 0-1.263-.313l-3.53 2.173c-1.33.82-3.169.432-4.005-.89c-.815-1.289-.413-3.048.838-3.922l3.178-2.082z");
}

.dmp-mg7ih {
  stop-color: var(--svg-color--ffd73d, #FFD73D);
}

.dzdsl0mec {
  stop-color: var(--svg-color--d5a047, #D5A047);
}

.e_uz1ccsd {
  stop-color: var(--svg-color--e8b229, #E8B229);
}

.e4svvibki {
  d: path("m16 5.995l1.073-1.869l3.823 2.225l-1.07 1.87z");
}

.f9dpzacts {
  stop-color: var(--svg-color--f1816b, #F1816B);
  stop-opacity: 0;
}

.fam_wqb4o {
  stop-color: var(--svg-color--f19321, #F19321);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.ftokoof_m {
  d: path("M9.933 22.03c-1.251.875-1.653 2.634-.838 3.924c.836 1.321 2.674 1.709 4.005.89l3.53-2.174a.91.91 0 0 1 1.263.313a6.84 6.84 0 0 0 6.588 3.321l3.832-.394a1.75 1.75 0 0 0 1.57-1.741v-7.13a2.81 2.81 0 0 0-1.736-2.585c-2.227-.928-6.282-2.689-10.295-4.785l-4.741 8.28z");
}

.fzcwmf9bu {
  d: path("M18.14 2.266a.5.5 0 0 1 .684-.184l2.963 1.71a.5.5 0 0 1 .184.681L8.43 28.12a.5.5 0 0 1-.211.199l-3.176 1.575c-.162.08-.298 0-.306-.18l-.226-3.541a.5.5 0 0 1 .065-.273z");
}

.grg3q37ve {
  stop-color: var(--svg-color--e37c45, #E37C45);
}

.hhhr5pb_v {
  stop-color: var(--svg-color--f7d160, #F7D160);
}

.hkig96m7k {
  stop-color: var(--svg-color--ffec5d, #FFEC5D);
  stop-opacity: 0;
}

.i104-lbhq {
  stop-color: var(--svg-color--db8838, #DB8838);
}

.i2mp3ny5q {
  stop-color: var(--svg-color--ffa3ae, #FFA3AE);
  stop-opacity: 0;
}

.i8x2ytb4x {
  stop-color: var(--svg-color--ffa3ae, #FFA3AE);
}

.itudfnbzj {
  stop-color: var(--svg-color--46144e, #46144E);
}

.j8s0uwfjz {
  stop-color: var(--svg-color--cabad5, #CABAD5);
}

.k9cdp4y8v {
  stop-color: var(--svg-color--f3752e, #F3752E);
}

.kc7ykhbib {
  stop-color: var(--svg-color--ec85b1, #EC85B1);
  stop-opacity: 0;
}

.kfmc1sbdc {
  stop-color: var(--svg-color--f3ca7e, #F3CA7E);
}

.l34lt5mia {
  stop-color: var(--svg-color--db8838, #DB8838);
  stop-opacity: 0;
}

.lp_1nfnub {
  stop-color: var(--svg-color--e28a85, #E28A85);
}

.lrjmfbpfe {
  stop-color: var(--svg-color--d76b0e, #D76B0E);
}

.mkdu6zbgz {
  stop-color: var(--svg-color--ffec5d, #FFEC5D);
}

.n22n_obox {
  d: path("m5.859 29.488l-.817.405c-.162.08-.298 0-.306-.18l-.058-.906z");
}

.nc-ufo_mt {
  fill: var(--svg-color--ffef64, #FFEF64);
  d: path("m17.818 20.62l-5.632 3.042a.69.69 0 1 0 .66 1.212l4.92-2.694a2 2 0 0 1 1.864-.03l8.999 4.552V20.26h-9.385a3 3 0 0 0-1.426.36");
}

.o53kwvbya {
  stop-color: var(--svg-color--f0a51d, #F0A51D);
}

.pde7wp_cs {
  stop-color: var(--svg-color--ea9d3e, #EA9D3E);
}

.q7h9g6bki {
  width: 4.832px;
  height: 6.985px;
  x: 9.933px;
  y: 22.892px;
  rx: 2.416px;
}

.qa3j86b_z {
  stop-color: var(--svg-color--ff95b3, #FF95B3);
}

.qam400kgw {
  stop-color: var(--svg-color--ff8dc2, #FF8DC2);
  stop-opacity: 0;
}

.ri12kgbds {
  d: path("m16.925 13.287l-3.807 6.65l1.758-1.104a5.25 5.25 0 0 1 3.498-.757l2.431.33z");
}

.roy0h0bsx {
  stop-color: var(--svg-color--ec82aa, #EC82AA);
}

.rphdcwbhu {
  stop-color: var(--svg-color--cabad4, #CABAD4);
  stop-opacity: 0;
}

.tn3edfbno {
  d: path("m15.173 27.117l-.671-1.725l1.352-1.986h14.03v4.579a2 2 0 0 1-2 2h-8.517a4.5 4.5 0 0 1-4.194-2.869");
}

.v37qiyrdg {
  d: path("m12.467 20.343l.53-.354l.083-.029l-.611.384z");
}

.vpkiefhxu {
  stop-color: var(--svg-color--f1816b, #F1816B);
}

.w48b-cdvb {
  stop-color: var(--svg-color--f7d160, #F7D160);
  stop-opacity: 0;
}

.w79k2acia {
  d: path("M8.386 28.182a.5.5 0 0 1-.168.136l-3.176 1.575c-.162.08-.298 0-.306-.18l-.226-3.541a.5.5 0 0 1 .02-.169z");
}

.w97l3zkii {
  stop-color: var(--svg-color--c4a8bc, #C4A8BC);
}

.webj0_bpa {
  stop-color: var(--svg-color--f8d15d, #F8D15D);
  stop-opacity: 0;
}

.wi1sqm47n {
  stop-color: var(--svg-color--d5a047, #D5A047);
  stop-opacity: 0;
}

.wpsp30-0v {
  stroke: var(--svg-color--ff7150, #FF7150);
  stroke-linecap: round;
  d: path("M17.241 8.382L8.19 24.319");
}

.wq3kgrbvi {
  stop-color: var(--svg-color--5a1870, #5A1870);
}

.wswbpgmku {
  stop-color: var(--svg-color--f3ca7e, #F3CA7E);
  stop-opacity: 0;
}

.x6g_n69lf {
  stop-color: var(--svg-color--e5d0fc, #E5D0FC);
}

.xw9lkcbkl {
  stop-color: var(--svg-color--ec85b1, #EC85B1);
}

.y4su1hbhi {
  stop-color: var(--svg-color--fd4e50, #FD4E50);
}

.yo5qxhbmi {
  stop-color: var(--svg-color--d24611, #D24611);
}

.ztplpabxo {
  stop-color: var(--svg-color--c4654e, #C4654E);
}

.zvxmjroaa {
  stop-color: var(--svg-color--d24611, #D24611);
  stop-opacity: 0;
}

</style>
