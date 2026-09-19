<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="r509e5b3f"/><path fill="url(#iC7qbJd)" class="sa95oibtq"/><path fill="url(#iLUcr2c)" class="sa95oibtq"/><path fill="url(#iSg4voe)" class="sa95oibtq"/><g filter="url(#iqS64nz)"><path fill="url(#i68Aupd)" class="fjea4fbtt"/><path fill="url(#irXKHib)" class="fjea4fbtt"/></g><path fill="url(#iiMzd0d)" class="ey_reuboo"/><path fill="url(#i4xKTTd)" class="ey_reuboo"/><path fill="url(#iYggzyb)" class="ey_reuboo"/><path fill="url(#iooqwue)" class="ey_reuboo"/><g filter="url(#iJRGCBL)"><path fill="url(#iecvMkU)" class="d7jcb8byk"/><path fill="url(#it2Lyje)" class="d7jcb8byk"/><path fill="url(#iR2RgBD)" class="d7jcb8byk"/><path fill="url(#iiYfg3b)" class="d7jcb8byk"/></g><g filter="url(#iWCyhpb)"><path stroke="url(#iOwksxb)" class="vyq02sbqa"/></g><defs><radialGradient id="irXKHib" cx="0" cy="0" r="1" gradientTransform="rotate(136.081 10.959 9.587)scale(1.17135 7.48692)" gradientUnits="userSpaceOnUse"><stop class="faz3ekbqr"/><stop offset="1" class="xek4tolix"/></radialGradient><radialGradient id="i4xKTTd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.5735 6.72649 -1.60417 -1.56769 11.166 18.672)" gradientUnits="userSpaceOnUse"><stop class="r1v1qcbkx"/><stop offset="1" class="kywreebvg"/></radialGradient><radialGradient id="iYggzyb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.98122 6.98122 -1.52874 -1.52874 12.644 21.014)" gradientUnits="userSpaceOnUse"><stop offset=".157" class="w9zr430ul"/><stop offset="1" class="vpu1fbcjl"/></radialGradient><radialGradient id="iooqwue" cx="0" cy="0" r="1" gradientTransform="matrix(-3.71993 12.01418 -6.15336 -1.90525 6.987 17.551)" gradientUnits="userSpaceOnUse"><stop offset=".899" class="do8ek5bkq"/><stop offset="1" class="qhvv1ib5a"/></radialGradient><radialGradient id="it2Lyje" cx="0" cy="0" r="1" gradientTransform="rotate(131.424 4.144 12.45)scale(2.83395 7.45916)" gradientUnits="userSpaceOnUse"><stop offset=".151" class="rmqttqb0w"/><stop offset="1" class="xuvqukbzq"/></radialGradient><radialGradient id="iR2RgBD" cx="0" cy="0" r="1" gradientTransform="matrix(11.81248 2.125 -3.27442 18.20192 9.784 19.454)" gradientUnits="userSpaceOnUse"><stop offset=".717" class="mg7a9ac3d"/><stop offset="1" class="ohjw6ub0y"/></radialGradient><radialGradient id="iiYfg3b" cx="0" cy="0" r="1" gradientTransform="rotate(-133.794 12.974 7.036)scale(13.6954)" gradientUnits="userSpaceOnUse"><stop offset=".816" class="uffnhdbel"/><stop offset="1" class="r2cy8ccqp"/></radialGradient><linearGradient id="iC7qbJd" x1="14.784" x2="18.972" y1="9.579" y2="13.954" gradientUnits="userSpaceOnUse"><stop class="nl36ax-xa"/><stop offset="1" class="rrsg0bc3m"/></linearGradient><linearGradient id="iLUcr2c" x1="22.378" x2="19.378" y1="17.298" y2="14.454" gradientUnits="userSpaceOnUse"><stop class="jejkt2l-i"/><stop offset="1" class="x7fbe1gtj"/></linearGradient><linearGradient id="iSg4voe" x1="22.503" x2="21.44" y1="11.236" y2="12.329" gradientUnits="userSpaceOnUse"><stop offset=".208" class="lgrw-hbrt"/><stop offset="1" class="geplocbrx"/></linearGradient><linearGradient id="i68Aupd" x1="16.533" x2="28.222" y1="3.142" y2="14.329" gradientUnits="userSpaceOnUse"><stop class="psad9pbir"/><stop offset="1" class="wv86i9yxv"/></linearGradient><linearGradient id="iiMzd0d" x1="5.509" x2="7.65" y1="24.023" y2="25.908" gradientUnits="userSpaceOnUse"><stop class="plycqz2ac"/><stop offset=".867" class="ns3-mwbdf"/></linearGradient><linearGradient id="iecvMkU" x1="9.972" x2="20.597" y1="11.267" y2="23.954" gradientUnits="userSpaceOnUse"><stop class="o7y48acyj"/><stop offset="1" class="u78u42bhf"/></linearGradient><linearGradient id="iOwksxb" x1="3.267" x2="10.197" y1="28.405" y2="21.653" gradientUnits="userSpaceOnUse"><stop class="ws3obnbpz"/><stop offset="1" class="wovqfccbp"/></linearGradient><filter id="iqS64nz" width="14.044" height="14.044" x="16.533" y=".935" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.109804 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23113"/></filter><filter id="iJRGCBL" width="16.308" height="16.308" x="5.835" y="9.369" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.133333 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23113"/></filter><filter id="iWCyhpb" width="8.427" height="8.453" x="2.442" y="20.573" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23113" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:pushpin" /></template>
<style>
.d7jcb8byk {
  d: path("M6.318 12.217a1.65 1.65 0 0 0 0 2.334l10.643 10.643a1.65 1.65 0 0 0 2.334 0l.676-.677a4 4 0 0 0 0-5.657l-7.32-7.32a4 4 0 0 0-5.656 0z");
}

.do8ek5bkq {
  stop-color: var(--svg-color--826f91, #826F91);
  stop-opacity: 0;
}

.ey_reuboo {
  d: path("M13.296 16.38a1.298 1.298 0 0 1 1.836 1.836L4.163 29.185a1.298 1.298 0 1 1-1.836-1.836z");
}

.faz3ekbqr {
  stop-color: var(--svg-color--ff688c, #FF688C);
}

.fjea4fbtt {
  d: path("M18.02 2.375a1.5 1.5 0 0 1 2.122 0l8.996 8.995a1.5 1.5 0 0 1 0 2.122l-.668.667a2.8 2.8 0 0 1-3.96 0l-7.157-7.157a2.8 2.8 0 0 1 0-3.96z");
}

.ft5dv1b6b {
  fill: none;
}

.geplocbrx {
  stop-color: var(--svg-color--b14162, #B14162);
  stop-opacity: 0;
}

.jejkt2l-i {
  stop-color: var(--svg-color--9c475f, #9C475F);
}

.kywreebvg {
  stop-color: var(--svg-color--8c6e76, #8C6E76);
  stop-opacity: 0;
}

.lgrw-hbrt {
  stop-color: var(--svg-color--a72249, #A72249);
}

.mg7a9ac3d {
  stop-color: var(--svg-color--ff6773, #FF6773);
  stop-opacity: 0;
}

.nl36ax-xa {
  stop-color: var(--svg-color--a7404e, #A7404E);
}

.ns3-mwbdf {
  stop-color: var(--svg-color--9b8ea4, #9B8EA4);
}

.o7y48acyj {
  stop-color: var(--svg-color--e72f7b, #E72F7B);
}

.ohjw6ub0y {
  stop-color: var(--svg-color--ff6773, #FF6773);
}

.plycqz2ac {
  stop-color: var(--svg-color--9d9798, #9D9798);
}

.psad9pbir {
  stop-color: var(--svg-color--e52c70, #E52C70);
}

.qhvv1ib5a {
  stop-color: var(--svg-color--826f91, #826F91);
}

.r1v1qcbkx {
  stop-color: var(--svg-color--8c6e76, #8C6E76);
}

.r2cy8ccqp {
  stop-color: var(--svg-color--c95179, #C95179);
}

.r509e5b3f {
  fill: var(--svg-color--d93965, #D93965);
  d: path("m11.534 12.626l7.352 7.352l6.523-6.524l-7.351-7.351z");
}

.rmqttqb0w {
  stop-color: var(--svg-color--ff678c, #FF678C);
}

.rrsg0bc3m {
  stop-color: var(--svg-color--a7404e, #A7404E);
  stop-opacity: 0;
}

.sa95oibtq {
  d: path("m11.534 12.626l7.352 7.352l6.523-6.524l-7.351-7.351z");
}

.u78u42bhf {
  stop-color: var(--svg-color--f63352, #F63352);
}

.uffnhdbel {
  stop-color: var(--svg-color--c95179, #C95179);
  stop-opacity: 0;
}

.vpu1fbcjl {
  stop-color: var(--svg-color--7c547b, #7C547B);
  stop-opacity: 0;
}

.vyq02sbqa {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-65px, 0.65px);
  d: path("m3.267 28.201l6.778-6.803");
}

.w9zr430ul {
  stop-color: var(--svg-color--7c547b, #7C547B);
}

.wovqfccbp {
  stop-color: var(--svg-color--a9a1ac, #A9A1AC);
  stop-opacity: 0;
}

.ws3obnbpz {
  stop-color: var(--svg-color--a9a1ac, #A9A1AC);
}

.wv86i9yxv {
  stop-color: var(--svg-color--fc3154, #FC3154);
}

.x7fbe1gtj {
  stop-color: var(--svg-color--d32a60, #D32A60);
  stop-opacity: 0;
}

.xek4tolix {
  stop-color: var(--svg-color--ff688c, #FF688C);
  stop-opacity: 0;
}

.xuvqukbzq {
  stop-color: var(--svg-color--ff678c, #FF678C);
  stop-opacity: 0;
}

</style>
