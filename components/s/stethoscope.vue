<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#isZgyES)"><path fill="url(#iyEESPd)" class="zb2n29x5m"/><path fill="url(#ifaJ1Pd)" class="zb2n29x5m"/></g><g filter="url(#icV19Sc)"><path fill="url(#izCbnlL)" class="bry-itm2l"/></g><g filter="url(#ixRIoqd)"><path fill="url(#iOSc1Pd)" class="k985o3biz"/></g><g filter="url(#i6VMvtd)"><path class="nzo6xvbdn"/></g><g filter="url(#iMFuIML)" class="arv8vqxqi"><path stroke="url(#iUJ7jjf)" class="rnr52xbxy"/><path stroke="url(#iVrru8b)" class="rnr52xbxy"/></g><g filter="url(#iHsPDqe)"><path stroke="url(#iF56rUd)" class="fmb7l5b6o"/></g><g filter="url(#iO1yDne)"><circle fill="url(#irGxfAF)" class="w8yqgrxxl"/><circle fill="url(#in694ze)" class="w8yqgrxxl"/></g><g filter="url(#iJzekDd)"><circle fill="url(#ij3nkid)" class="poi9qxiiq"/></g><g filter="url(#iWjUSVd)" class="e6yvllmya"><path stroke="url(#iXKiRpe)" class="q6ib54bga"/><path stroke="url(#iVxH4Dc)" class="q6ib54bga"/></g><path class="qycw52axk"/><path fill="url(#ifV9Guf)" class="n5ojhjfwk"/><path fill="url(#igxPcec)" class="n5ojhjfwk"/><g filter="url(#i2xd4Iz)"><path stroke="url(#i52aSMb)" class="tpiqjsd9i"/></g><path class="c2mb0kbnr"/><path fill="url(#ilJfxTb)" class="e2vkb8boi"/><path fill="url(#ikZ5qWd)" class="e2vkb8boi"/><g filter="url(#i03Eyae)"><path stroke="url(#izPpaae)" class="ecq7i7l7a"/></g><defs><filter id="isZgyES" width="4.522" height="10.244" x="2.341" y="2.381" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.227451 0 0 0 0 0.490196 0 0 0 0 0.823529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_25364"/></filter><filter id="icV19Sc" width="5.166" height="9.213" x="12.707" y="2.381" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.192157 0 0 0 0 0.494118 0 0 0 0 0.980392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_25364"/></filter><filter id="ixRIoqd" width="15.532" height="8.246" x="2.341" y="10.672" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.172549 0 0 0 0 0.415686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_25364"/></filter><filter id="i6VMvtd" width="20.708" height="14.96" x="8.601" y="15.004" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.168627 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_25364"/></filter><filter id="iMFuIML" width="17.469" height="13.594" x="9.238" y="15.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_25364" stdDeviation=".25"/></filter><filter id="iHsPDqe" width="4.246" height="4.949" x="24.492" y="15.145" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_25364" stdDeviation=".25"/></filter><filter id="iO1yDne" width="6.662" height="6.662" x="23.95" y="18.515" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.74902 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_25364"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.384314 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_25364" result="effect2_innerShadow_18_25364"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.301961 0 0 0 0 0.427451 0 0 0 0 0.807843 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_25364" result="effect3_innerShadow_18_25364"/></filter><filter id="iJzekDd" width="3.21" height="3.209" x="25.626" y="20.291" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.392157 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_25364"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_25364" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.592157 0 0 0 0 0.960784 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_25364"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.290196 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_25364" result="effect3_innerShadow_18_25364"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.290196 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="effect3_innerShadow_18_25364" result="effect4_innerShadow_18_25364"/></filter><filter id="iWjUSVd" width="14.271" height="7.947" x="2.867" y="10.469" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_25364" stdDeviation=".25"/></filter><filter id="i2xd4Iz" width="3.011" height="7.672" x="14.29" y="2.703" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_25364" stdDeviation=".25"/></filter><filter id="i03Eyae" width="2.133" height="7.414" x="2.77" y="3.305" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_25364" stdDeviation=".25"/></filter><radialGradient id="ifaJ1Pd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 -.9375 .55356 -.75654 5.55 5.281)" gradientUnits="userSpaceOnUse"><stop class="t54_-hbue"/><stop offset="1" class="fv2zchbzz"/></radialGradient><radialGradient id="iUJ7jjf" cx="0" cy="0" r="1" gradientTransform="matrix(7.01117 8.46879 -8.21244 6.79894 8.488 19.406)" gradientUnits="userSpaceOnUse"><stop offset=".729" class="l2obedbet"/><stop offset="1" class="vt9xg_bxj"/></radialGradient><radialGradient id="iVrru8b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.83638 6.18748 -6.05481 -2.77556 20.28 19.625)" gradientUnits="userSpaceOnUse"><stop offset=".196" class="l2obedbet"/><stop offset="1" class="vt9xg_bxj"/></radialGradient><radialGradient id="in694ze" cx="0" cy="0" r="1" gradientTransform="rotate(135 9.603 16.554)scale(3.88909)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="zbkpolbyt"/><stop offset=".996" class="myxcp_2xl"/></radialGradient><radialGradient id="iXKiRpe" cx="0" cy="0" r="1" gradientTransform="matrix(7.84305 8.25725 -4.919 4.67226 3.692 10.41)" gradientUnits="userSpaceOnUse"><stop offset=".499" class="p92q8cc8c"/><stop offset="1" class="kiljfi1pv"/></radialGradient><radialGradient id="iVxH4Dc" cx="0" cy="0" r="1" gradientTransform="rotate(113.604 4.859 10.77)scale(7.77555 4.86216)" gradientUnits="userSpaceOnUse"><stop class="w9u8y1buf"/><stop offset="1" class="q7bofwz3e"/></radialGradient><radialGradient id="igxPcec" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09375 .28125 -.19937 -.7753 7.254 3.813)" gradientUnits="userSpaceOnUse"><stop class="oqe98cr1a"/><stop offset="1" class="iutqvubrr"/></radialGradient><radialGradient id="i52aSMb" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 5.03125 -3.14267 -.01952 16.613 3.844)" gradientUnits="userSpaceOnUse"><stop class="qquv5ccpk"/><stop offset="1" class="qj-gr8d_r"/></radialGradient><radialGradient id="ilJfxTb" cx="0" cy="0" r="1" gradientTransform="rotate(-134.071 7.89 -.317)scale(2.18373 2.67308)" gradientUnits="userSpaceOnUse"><stop offset=".335" class="d5h4agjxl"/><stop offset=".968" class="r-0xrd8kt"/></radialGradient><radialGradient id="ikZ5qWd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.43787 .0138 -.00786 -.81912 13.884 3.7)" gradientUnits="userSpaceOnUse"><stop class="eb-wkvqqm"/><stop offset="1" class="clhtixahj"/></radialGradient><linearGradient id="iyEESPd" x1="4.38" x2="4.38" y1="5.67" y2="9.848" gradientUnits="userSpaceOnUse"><stop class="luce_f11d"/><stop offset="1" class="nyakmcb-h"/></linearGradient><linearGradient id="izCbnlL" x1="15.504" x2="15.504" y1="6" y2="10.672" gradientUnits="userSpaceOnUse"><stop class="a6kc4fyip"/><stop offset="1" class="qynu5acwe"/></linearGradient><linearGradient id="iOSc1Pd" x1="6.481" x2="17.123" y1="15.216" y2="15.105" gradientUnits="userSpaceOnUse"><stop class="yuqlnqbml"/><stop offset="1" class="lfo-fcc1x"/></linearGradient><linearGradient id="iF56rUd" x1="28.145" x2="23.113" y1="19.156" y2="15.563" gradientUnits="userSpaceOnUse"><stop offset=".307" class="zqk0iia8m"/><stop offset="1" class="dl8jicbaa"/></linearGradient><linearGradient id="irGxfAF" x1="30.511" x2="24.863" y1="19.844" y2="24.531" gradientUnits="userSpaceOnUse"><stop class="p3il5nbaw"/><stop offset="1" class="fbv__ibtq"/></linearGradient><linearGradient id="ij3nkid" x1="28.863" x2="25.876" y1="21.845" y2="21.845" gradientUnits="userSpaceOnUse"><stop class="k69anf4sy"/><stop offset=".9" class="c_ui9pbcw"/></linearGradient><linearGradient id="ifV9Guf" x1="6.207" x2="6.207" y1="2.766" y2="4.453" gradientUnits="userSpaceOnUse"><stop class="uytww2ldt"/><stop offset="1" class="vp13jv05g"/></linearGradient><linearGradient id="izPpaae" x1="4.207" x2="6.521" y1=".594" y2="1.247" gradientUnits="userSpaceOnUse"><stop class="qquv5ccpk"/><stop offset="1" class="qj-gr8d_r"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:stethoscope" /></template>
<style>
.a6kc4fyip {
  stop-color: var(--svg-color--4bdcff, #4BDCFF);
}

.arv8vqxqi {
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
}

.bry-itm2l {
  d: path("M12.707 5.08c0 .028.022.05.05.05h1.99c.07 0 .126.057.126.126v6.338h2.25V5.256a2.375 2.375 0 0 0-2.375-2.375h-1.99a.05.05 0 0 0-.05.05z");
}

.c_ui9pbcw {
  stop-color: var(--svg-color--3571e6, #3571E6);
}

.c2mb0kbnr {
  fill: var(--svg-color--541b8d, #541B8D);
  d: path("M13.884 2.88v2.25h-1.018a1.125 1.125 0 0 1 0-2.25z");
}

.clhtixahj {
  stop-color: var(--svg-color--4f3276, #4F3276);
  stop-opacity: 0;
}

.d5h4agjxl {
  stop-color: var(--svg-color--3c2b5c, #3C2B5C);
  stop-opacity: 0;
}

.dl8jicbaa {
  stop-color: var(--svg-color--7a62a0, #7A62A0);
  stop-opacity: 0;
}

.e2vkb8boi {
  d: path("M13.884 2.88v2.25h-1.018a1.125 1.125 0 0 1 0-2.25z");
}

.e6yvllmya {
  stroke-width: var(--svg-stroke-width--0-65px, 0.65px);
}

.eb-wkvqqm {
  stop-color: var(--svg-color--4f3276, #4F3276);
}

.ecq7i7l7a {
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M4.207 4.125a1.29 1.29 0 0 0-.562 1.063v5.03");
}

.fbv__ibtq {
  stop-color: var(--svg-color--3690ff, #3690FF);
}

.fmb7l5b6o {
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M25.113 16c.917.313 2.75 1.469 2.75 3.594");
}

.ft5dv1b6b {
  fill: none;
}

.fv2zchbzz {
  stop-color: var(--svg-color--4984ff, #4984FF);
  stop-opacity: 0;
}

.iutqvubrr {
  stop-color: var(--svg-color--705d91, #705D91);
  stop-opacity: 0;
}

.k69anf4sy {
  stop-color: var(--svg-color--3677ef, #3677EF);
}

.k985o3biz {
  d: path("M2.341 10.672v.69a7.39 7.39 0 0 0 6.088 7.275a.3.3 0 0 1 .173.281h.77v-.175a8 8 0 0 0 .71 0v.175h.77c0-.158.094-.243.166-.277a7.39 7.39 0 0 0 6.105-7.28v-.69h-2.25v.69a5.14 5.14 0 1 1-10.282 0v-.69z");
}

.kiljfi1pv {
  stop-color: var(--svg-color--7567b7, #7567B7);
  stop-opacity: 0;
}

.l2obedbet {
  stop-color: var(--svg-color--6f52a9, #6F52A9);
}

.lfo-fcc1x {
  stop-color: var(--svg-color--592793, #592793);
}

.luce_f11d {
  stop-color: var(--svg-color--42c5ff, #42C5FF);
}

.myxcp_2xl {
  stop-color: var(--svg-color--3386ff, #3386FF);
}

.n5ojhjfwk {
  d: path("M5.56 5.13V2.88h1.018a1.125 1.125 0 0 1 0 2.25z");
}

.nyakmcb-h {
  stop-color: var(--svg-color--58b3ff, #58B3FF);
}

.nzo6xvbdn {
  fill: var(--svg-color--5e209e, #5E209E);
  d: path("M20.778 20.02a2.766 2.766 0 0 1 5.53 0h2.25a5.016 5.016 0 0 0-10.03 0v3.456a3.838 3.838 0 1 1-7.677 0v-4.884a.5.5 0 0 0-.169-.374l-.625-.553a.5.5 0 0 0-.662 0l-.625.553a.5.5 0 0 0-.169.374v4.884a6.088 6.088 0 1 0 12.177 0z");
}

.oqe98cr1a {
  stop-color: var(--svg-color--705d91, #705D91);
}

.p3il5nbaw {
  stop-color: var(--svg-color--3595ff, #3595FF);
}

.p92q8cc8c {
  stop-color: var(--svg-color--7567b7, #7567B7);
}

.poi9qxiiq {
  cx: 27.28px;
  cy: 21.845px;
  r: 1.405px;
}

.q6ib54bga {
  d: path("M3.692 10.969v.312a6.31 6.31 0 0 0 12.62 0v-.312");
}

.q7bofwz3e {
  stop-color: var(--svg-color--6d4d9b, #6D4D9B);
  stop-opacity: 0;
}

.qj-gr8d_r {
  stop-color: var(--svg-color--65e8ff, #65E8FF);
  stop-opacity: 0;
}

.qquv5ccpk {
  stop-color: var(--svg-color--65e8ff, #65E8FF);
}

.qycw52axk {
  fill: var(--svg-color--53208d, #53208D);
  d: path("M5.56 5.13V2.88h1.018a1.125 1.125 0 0 1 0 2.25z");
}

.qynu5acwe {
  stop-color: var(--svg-color--54a4ff, #54A4FF);
}

.r-0xrd8kt {
  stop-color: var(--svg-color--3c2b5c, #3C2B5C);
}

.rnr52xbxy {
  d: path("M10.113 18.344v5.01a4.864 4.864 0 0 0 4.865 4.865h1.38a3.483 3.483 0 0 0 3.484-3.484v-5.177a3.183 3.183 0 0 1 3.182-3.183h3.183");
}

.t54_-hbue {
  stop-color: var(--svg-color--4984ff, #4984FF);
}

.tpiqjsd9i {
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M14.8 3.578c.543.016 1.626.372 1.626 1.672v4.625");
}

.uytww2ldt {
  stop-color: var(--svg-color--483264, #483264);
}

.vp13jv05g {
  stop-color: var(--svg-color--483264, #483264);
  stop-opacity: 0;
}

.vt9xg_bxj {
  stop-color: var(--svg-color--6f52a9, #6F52A9);
  stop-opacity: 0;
}

.w8yqgrxxl {
  cx: 27.28px;
  cy: 21.845px;
  r: 3.231px;
}

.w9u8y1buf {
  stop-color: var(--svg-color--6d4d9b, #6D4D9B);
}

.yuqlnqbml {
  stop-color: var(--svg-color--5728a8, #5728A8);
}

.zb2n29x5m {
  d: path("M6.363 2.88H4.716a2.375 2.375 0 0 0-2.375 2.376v5.807l2.25 1.562v-7.37c0-.068.056-.124.125-.124h1.647z");
}

.zbkpolbyt {
  stop-color: var(--svg-color--3386ff, #3386FF);
  stop-opacity: 0;
}

.zqk0iia8m {
  stop-color: var(--svg-color--7a62a0, #7A62A0);
}

</style>
