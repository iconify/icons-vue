<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ieD3B7b)"><path fill="url(#iD9Kiae)" class="f0ntlvvnf"/><path fill="url(#itjIslb)" class="f0ntlvvnf"/><path fill="url(#iXWouDe)" class="f0ntlvvnf"/></g><g filter="url(#iaEb15d)"><path fill="url(#ieZO0mg)" class="hvrtb0q1t"/><path fill="url(#iwf8Yqb)" class="hvrtb0q1t"/><path fill="url(#iVd5Mie)" class="hvrtb0q1t"/></g><g filter="url(#ieoSend)"><path fill="url(#ifJrvcd)" class="kdx_lqbxl"/></g><g filter="url(#iIdRWzd)"><rect fill="url(#ifO9OGK)" class="owb110pfp"/></g><g filter="url(#iCWJQoe)"><rect fill="url(#iBGQqbb)" class="zpoflqb7v"/></g><g filter="url(#iLLjrLZ)"><rect fill="url(#iurNged)" class="jmrh9tb_y"/></g><g filter="url(#iuhJOtb)"><rect fill="url(#i61w5ZI)" class="s52cavrnv"/><rect fill="url(#i2jB1De)" class="s52cavrnv"/></g><g filter="url(#iCFe4De)"><rect fill="url(#igl9xib)" class="dyuyfyukg"/><rect fill="url(#iLmq1Ic)" class="dyuyfyukg"/></g><g filter="url(#ib9bdBd)"><rect fill="url(#i88x15C)" class="k0_5dv25g"/><rect fill="url(#ioZLlHb)" class="k0_5dv25g"/></g><g filter="url(#iEtLb8A)"><path fill="url(#iksEhvc)" class="ii56wubry"/><path fill="url(#iqrRgte)" class="ii56wubry"/></g><path fill="url(#ir3QSHm)" class="p5si3yf1j"/><path fill="url(#iAMmQce)" class="p5si3yf1j"/><g filter="url(#iq1x2uO)" class="omlm15gvn"><path stroke="url(#iQbFuTc)" class="j573vpbrh"/><path stroke="url(#iF5QSCb)" class="j573vpbrh"/></g><g filter="url(#idtOXRs)"><path stroke="url(#iw1oLNc)" class="wpcpogybu"/></g><g filter="url(#iqmh23d)"><path stroke="url(#i3eNMcc)" class="hhfvjgsyj"/></g><g filter="url(#ipple1P)"><path stroke="url(#ii7I7Sc)" class="v1xjzibhg"/></g><defs><linearGradient id="iXWouDe" x1="16.57" x2="17.883" y1="10.193" y2="8.412" gradientUnits="userSpaceOnUse"><stop offset=".066" class="spguxfi5u"/><stop offset="1" class="dp1f_fbxr"/></linearGradient><linearGradient id="ieZO0mg" x1="22.664" x2="10.164" y1="26.974" y2="4.037" gradientUnits="userSpaceOnUse"><stop class="opxq3yblh"/><stop offset="1" class="i5si7f0ju"/></linearGradient><linearGradient id="iwf8Yqb" x1="8.727" x2="14.289" y1="3.474" y2="8.537" gradientUnits="userSpaceOnUse"><stop class="t7h6sn-yo"/><stop offset="1" class="my06rabqv"/></linearGradient><linearGradient id="iVd5Mie" x1="7.914" x2="9.07" y1="3.506" y2="4.599" gradientUnits="userSpaceOnUse"><stop class="rmgkmrb5v"/><stop offset="1" class="rl8smccjf"/></linearGradient><linearGradient id="ifJrvcd" x1="19.977" x2="26.914" y1="11.537" y2="27.381" gradientUnits="userSpaceOnUse"><stop class="cx1nwzfuw"/><stop offset="1" class="ae-6ay-gj"/></linearGradient><linearGradient id="ifO9OGK" x1="18.482" x2="20.481" y1="14.104" y2="14.597" gradientUnits="userSpaceOnUse"><stop class="iovsg9bsk"/><stop offset="1" class="l0jgy-b7h"/></linearGradient><linearGradient id="iBGQqbb" x1="20.076" x2="22.075" y1="17.471" y2="17.964" gradientUnits="userSpaceOnUse"><stop class="iovsg9bsk"/><stop offset="1" class="l0jgy-b7h"/></linearGradient><linearGradient id="iurNged" x1="21.412" x2="23.41" y1="21.01" y2="21.503" gradientUnits="userSpaceOnUse"><stop class="iovsg9bsk"/><stop offset="1" class="l0jgy-b7h"/></linearGradient><linearGradient id="iksEhvc" x1="18.664" x2="3.477" y1="27.724" y2="11.537" gradientUnits="userSpaceOnUse"><stop class="lopfqnbka"/><stop offset="1" class="nw7dhd_uk"/></linearGradient><linearGradient id="iqrRgte" x1="2.977" x2="6.977" y1="8.599" y2="12.599" gradientUnits="userSpaceOnUse"><stop class="nguzbtbql"/><stop offset="1" class="gvc1og_nn"/></linearGradient><linearGradient id="ir3QSHm" x1="9.736" x2="10.539" y1="8.162" y2="16.599" gradientUnits="userSpaceOnUse"><stop class="k7hgfhb3g"/><stop offset=".599" class="srtabsdxx"/></linearGradient><linearGradient id="iAMmQce" x1="5.976" x2="6.726" y1="6.162" y2="6.849" gradientUnits="userSpaceOnUse"><stop class="bga_evdcv"/><stop offset="1" class="kje2nacdj"/></linearGradient><linearGradient id="iw1oLNc" x1="19.68" x2="24.32" y1="13.537" y2="13.537" gradientUnits="userSpaceOnUse"><stop class="ly5meghmu"/><stop offset="1" class="hh1-2y7ew"/></linearGradient><linearGradient id="i3eNMcc" x1="21.273" x2="25.914" y1="16.865" y2="16.865" gradientUnits="userSpaceOnUse"><stop class="ly5meghmu"/><stop offset="1" class="hh1-2y7ew"/></linearGradient><linearGradient id="ii7I7Sc" x1="22.398" x2="27.039" y1="20.412" y2="20.412" gradientUnits="userSpaceOnUse"><stop class="ly5meghmu"/><stop offset="1" class="hh1-2y7ew"/></linearGradient><filter id="ieD3B7b" width="6.577" height="6.297" x="14.15" y="6.499" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 0.623529 0 0 0 0 0.756863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17222"/></filter><filter id="iaEb15d" width="28.262" height="28.016" x="1.857" y="2.067" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.521569 0 0 0 0 0.505882 0 0 0 0 0.564706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17222"/></filter><filter id="ieoSend" width="13.844" height="19.781" x="16.758" y="9.396" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17222" stdDeviation=".75"/></filter><filter id="iIdRWzd" width="4.789" height="2.641" x="18.063" y="12.303" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17222" stdDeviation=".125"/></filter><filter id="iCWJQoe" width="4.789" height="2.641" x="19.656" y="15.67" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17222" stdDeviation=".125"/></filter><filter id="iLLjrLZ" width="4.789" height="2.641" x="20.992" y="19.209" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17222" stdDeviation=".125"/></filter><filter id="iuhJOtb" width="5" height="2.206" x="18.445" y="12.396" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".05"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.654902 0 0 0 0 0.619608 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17222"/></filter><filter id="iCFe4De" width="5" height="2.206" x="20.055" y="15.74" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".05"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.654902 0 0 0 0 0.619608 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17222"/></filter><filter id="ib9bdBd" width="5" height="2.206" x="21.305" y="19.287" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".05"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.654902 0 0 0 0 0.619608 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17222"/></filter><filter id="iEtLb8A" width="27.613" height="23.323" x="1.857" y="6.61" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.54902 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17222"/></filter><filter id="iq1x2uO" width="9.13" height="9.812" x="11.494" y="1.798" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17222" stdDeviation=".25"/></filter><filter id="idtOXRs" width="4.169" height="1.45" x="19.158" y="12.578" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17222" stdDeviation=".2"/></filter><filter id="iqmh23d" width="4.169" height="1.45" x="20.752" y="15.906" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17222" stdDeviation=".2"/></filter><filter id="ipple1P" width="4.169" height="1.45" x="21.877" y="19.453" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17222" stdDeviation=".2"/></filter><radialGradient id="iD9Kiae" cx="0" cy="0" r="1" gradientTransform="rotate(160.534 9.291 6.245)scale(3.84477 5.45574)" gradientUnits="userSpaceOnUse"><stop class="yfl6lnbww"/><stop offset="1" class="xb1va7bcb"/></radialGradient><radialGradient id="itjIslb" cx="0" cy="0" r="1" gradientTransform="rotate(159.605 8.368 7.396)scale(2.60052 2.14125)" gradientUnits="userSpaceOnUse"><stop offset=".501" class="spguxfi5u"/><stop offset="1" class="dp1f_fbxr"/></radialGradient><radialGradient id="i61w5ZI" cx="0" cy="0" r="1" gradientTransform="matrix(4.28125 0 0 2.0188 18.914 14.553)" gradientUnits="userSpaceOnUse"><stop class="av8gnub5k"/><stop offset="1" class="ojabw_bso"/></radialGradient><radialGradient id="i2jB1De" cx="0" cy="0" r="1" gradientTransform="matrix(1.59375 .95313 -1.04382 1.7454 18.633 12.88)" gradientUnits="userSpaceOnUse"><stop class="u6tc6zf_q"/><stop offset="1" class="xlt2g64fk"/></radialGradient><radialGradient id="igl9xib" cx="0" cy="0" r="1" gradientTransform="matrix(4.28125 0 0 2.0188 20.523 17.896)" gradientUnits="userSpaceOnUse"><stop class="av8gnub5k"/><stop offset="1" class="ojabw_bso"/></radialGradient><radialGradient id="iLmq1Ic" cx="0" cy="0" r="1" gradientTransform="matrix(1.59375 .95313 -1.04382 1.7454 20.242 16.224)" gradientUnits="userSpaceOnUse"><stop class="u6tc6zf_q"/><stop offset="1" class="xlt2g64fk"/></radialGradient><radialGradient id="i88x15C" cx="0" cy="0" r="1" gradientTransform="matrix(4.28125 0 0 2.0188 21.773 21.443)" gradientUnits="userSpaceOnUse"><stop class="av8gnub5k"/><stop offset="1" class="ojabw_bso"/></radialGradient><radialGradient id="ioZLlHb" cx="0" cy="0" r="1" gradientTransform="matrix(1.59375 .95313 -1.04382 1.7454 21.492 19.771)" gradientUnits="userSpaceOnUse"><stop class="u6tc6zf_q"/><stop offset="1" class="xlt2g64fk"/></radialGradient><radialGradient id="iQbFuTc" cx="0" cy="0" r="1" gradientTransform="matrix(.59375 3.85937 -3.42982 .52767 12.914 3.1)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="bex9q9kau"/><stop offset="1" class="jjr3vobdj"/></radialGradient><radialGradient id="iF5QSCb" cx="0" cy="0" r="1" gradientTransform="rotate(-147.031 11.383 2.735)scale(8.26916 7.34879)" gradientUnits="userSpaceOnUse"><stop class="qxytcbciy"/><stop offset="1" class="jjr3vobdj"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:running-shoe" /></template>
<style>
.ae-6ay-gj {
  stop-color: var(--svg-color--dbd7e5, #DBD7E5);
}

.av8gnub5k {
  stop-color: var(--svg-color--ca98f6, #CA98F6);
}

.bex9q9kau {
  stop-color: var(--svg-color--bab2c4, #BAB2C4);
}

.bga_evdcv {
  stop-color: var(--svg-color--73738b, #73738B);
}

.cx1nwzfuw {
  stop-color: var(--svg-color--c9c5d2, #C9C5D2);
}

.dp1f_fbxr {
  stop-color: var(--svg-color--5d4786, #5D4786);
  stop-opacity: 0;
}

.dyuyfyukg {
  width: 4.75px;
  height: 2.156px;
  x: 20.055px;
  y: 15.74px;
  rx: 1.078px;
}

.f0ntlvvnf {
  d: path("m14.722 7.696l-.472.528l3.336 4.422l3.14-1.64c-.165-.994-.499-1.971-.897-2.863c-.928-2.076-3.593-2.142-5.107-.447");
}

.ft5dv1b6b {
  fill: none;
}

.gvc1og_nn {
  stop-color: var(--svg-color--beb4cd, #BEB4CD);
  stop-opacity: 0;
}

.hh1-2y7ew {
  stop-color: var(--svg-color--f3e7ff, #F3E7FF);
  stop-opacity: 0;
}

.hhfvjgsyj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-65px, 0.65px);
  d: path("M21.477 16.63h2.718");
}

.hvrtb0q1t {
  d: path("m9.445 2.818l-3.61 3.604l-.218 1.568l-1.588.234l-1.805 1.801a1.24 1.24 0 0 0-.027 1.734c2.446 2.569 7.124 7.347 11.412 11.458c6.774 6.492 12.32 6.601 13.086 6.695c.523.064 1.016-.031 1.14-.094c.767-.383 2.206-1.364 2.017-2.375c-.235-1.25-.99-1.61-2.344-2.64c-.815-.62-1.459-1.81-1.64-2.258l-4.95-11.663a1.5 1.5 0 0 0-2.158-.697l-.339.206a1 1 0 0 1-1.234-.157l-4.451-4.56a1 1 0 0 1-.235-1.01l.28-.854c.151-.453.177-1.417-.898-1.68s-2.073.35-2.438.688");
}

.i5si7f0ju {
  stop-color: var(--svg-color--a591ba, #A591BA);
}

.ii56wubry {
  d: path("M29.32 28.746c-3.271-.405-7.296-1.297-10.593-4.21c-1.826-1.693-2.358-2.89-3-4.33c-.502-1.13-1.072-2.41-2.383-4.196c-2.432-3.314-5.384-6.21-7.195-7.99c-.341-.335-.642-.63-.892-.881a.1.1 0 0 0-.142 0l-2.891 2.885a1.24 1.24 0 0 0-.027 1.733c2.446 2.57 7.124 7.348 11.412 11.459c6.357 6.092 11.633 6.564 12.891 6.676q.124.01.195.019c.523.064 1.016-.031 1.14-.094c.42-.21 1.04-.598 1.485-1.072");
}

.iovsg9bsk {
  stop-color: var(--svg-color--8e6aae, #8E6AAE);
}

.j573vpbrh {
  d: path("M12.07 2.396c.235.183.644.706.407 1.344c-.095.255-.183.51-.26.744a1.5 1.5 0 0 0 .343 1.496l4.321 4.538a1.5 1.5 0 0 0 2.03.132l.16-.129c.145-.12.546-.287.984 0");
}

.jjr3vobdj {
  stop-color: var(--svg-color--bab2c4, #BAB2C4);
  stop-opacity: 0;
}

.jmrh9tb_y {
  width: 4.289px;
  height: 2.141px;
  x: 21.242px;
  y: 19.459px;
  rx: 1.07px;
}

.k0_5dv25g {
  width: 4.75px;
  height: 2.156px;
  x: 21.305px;
  y: 19.287px;
  rx: 1.078px;
}

.k7hgfhb3g {
  stop-color: var(--svg-color--5f5796, #5F5796);
}

.kdx_lqbxl {
  d: path("m23.25 24.108l-4.992-13.055l2.062-.157l5.692 13.709c.18.43.503.785.917 1c.432.226.955.495 1.36.697c.65.326.813 1.053.813 1.375l-4.27-1.9a3 3 0 0 1-1.581-1.669");
}

.kje2nacdj {
  stop-color: var(--svg-color--73738b, #73738B);
  stop-opacity: 0;
}

.l0jgy-b7h {
  stop-color: var(--svg-color--827c8d, #827C8D);
}

.lopfqnbka {
  stop-color: var(--svg-color--e5c7ff, #E5C7FF);
}

.ly5meghmu {
  stop-color: var(--svg-color--f3e7ff, #F3E7FF);
}

.my06rabqv {
  stop-color: var(--svg-color--77757a, #77757A);
  stop-opacity: 0;
}

.nguzbtbql {
  stop-color: var(--svg-color--a3a2a5, #A3A2A5);
}

.nw7dhd_uk {
  stop-color: var(--svg-color--d1bee6, #D1BEE6);
}

.ojabw_bso {
  stop-color: var(--svg-color--dfdee6, #DFDEE6);
}

.omlm15gvn {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
}

.opxq3yblh {
  stop-color: var(--svg-color--c0a6dc, #C0A6DC);
}

.owb110pfp {
  width: 4.289px;
  height: 2.141px;
  x: 18.313px;
  y: 12.553px;
  rx: 1.07px;
}

.p5si3yf1j {
  d: path("M5.248 7.007a.1.1 0 0 0 .001.143l.044.042c.364.352.702.679.856.83c1.812 1.778 4.763 4.674 7.195 7.987c.371.507.683.973.951 1.406l-.19-3.392a6 6 0 0 0-1.744-3.902L7.255 5.004z");
}

.qxytcbciy {
  stop-color: var(--svg-color--cfcbd5, #CFCBD5);
}

.rl8smccjf {
  stop-color: var(--svg-color--8b8b8c, #8B8B8C);
  stop-opacity: 0;
}

.rmgkmrb5v {
  stop-color: var(--svg-color--8b8b8c, #8B8B8C);
}

.s52cavrnv {
  width: 4.75px;
  height: 2.156px;
  x: 18.445px;
  y: 12.396px;
  rx: 1.078px;
}

.spguxfi5u {
  stop-color: var(--svg-color--5d4786, #5D4786);
}

.srtabsdxx {
  stop-color: var(--svg-color--714699, #714699);
}

.t7h6sn-yo {
  stop-color: var(--svg-color--77757a, #77757A);
}

.u6tc6zf_q {
  stop-color: var(--svg-color--b9a5d0, #B9A5D0);
}

.v1xjzibhg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-65px, 0.65px);
  d: path("M22.602 20.178h2.718");
}

.wpcpogybu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-65px, 0.65px);
  d: path("M19.883 13.303h2.719");
}

.xb1va7bcb {
  stop-color: var(--svg-color--67579a, #67579A);
}

.xlt2g64fk {
  stop-color: var(--svg-color--b9a5d0, #B9A5D0);
  stop-opacity: 0;
}

.yfl6lnbww {
  stop-color: var(--svg-color--8379b9, #8379B9);
}

.zpoflqb7v {
  width: 4.289px;
  height: 2.141px;
  x: 19.906px;
  y: 15.92px;
  rx: 1.07px;
}

</style>
