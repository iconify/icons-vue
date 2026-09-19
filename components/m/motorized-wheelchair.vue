<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#itLTTae)" class="fcb_bfb2s"/><path fill="url(#iCOKwkb)" class="fcb_bfb2s"/><path fill="url(#iFIZSwd)" class="i44v0ccyo"/><path fill="url(#ijB2ilb)" class="i44v0ccyo"/><path fill="url(#iFIZSwd)" class="i44v0ccyo"/><path fill="url(#iFn2nNc)" class="i44v0ccyo"/><path fill="url(#iFIZSwd)" class="i44v0ccyo"/><path fill="url(#iFn2nNc)" class="i44v0ccyo"/><g filter="url(#iF6bM8d)"><path fill="url(#iSjJ6tb)" class="rcse30b-s"/><path fill="url(#ioZfbub)" class="rcse30b-s"/></g><path fill="url(#im7UgUd)" class="uu27stiro"/><g filter="url(#iCJpBdC)"><path fill="url(#iavN2yh)" class="fhsm1dbnb"/></g><g filter="url(#iKdOyAb)"><path fill="url(#ikIJoLb)" class="ek3_kacof"/></g><g filter="url(#iBhFXKd)"><path class="x077bxdnn"/></g><g filter="url(#iksKWjb)"><path class="m-e3tybyr"/><path fill="url(#iwilLpc)" class="ysn4ppbcd"/></g><path fill="url(#i9iCp3c)" clip-rule="evenodd" class="sjc-nobph"/><path fill="url(#i5foVid)" clip-rule="evenodd" class="sjc-nobph"/><path fill="url(#ikhsYCc)" clip-rule="evenodd" class="sjc-nobph"/><path class="y_d1hrbzf"/><path fill="url(#iqc6UEb)" class="m5kkxnwqi"/><path class="i8r9u6lxj"/><g filter="url(#iF4LNed)"><path class="dv4b8ooqj"/></g><path fill="url(#itxRnud)" class="c8wjcqbwv"/><path fill="url(#i3v8OGc)" class="c8wjcqbwv"/><g filter="url(#icGVf6d)"><path fill="url(#i9GhkIe)" class="ys3pqlbzw"/></g><g filter="url(#itmCbvt)"><path fill="url(#i2oaxnE)" class="obi00lklp"/></g><path fill="url(#iGs5yZc)" class="obi00lklp"/><path fill="url(#i3gzVqe)" class="obi00lklp"/><g filter="url(#i4useKe)"><path stroke="url(#i24rRHG)" class="tlv2pob-i"/></g><g filter="url(#im3FRBc)"><path fill="url(#iOt0MXR)" class="yd6c5etro"/></g><g filter="url(#ifpOafe)"><path stroke="url(#iDRzlje)" class="xa9v8u8ys"/></g><defs><linearGradient id="iCOKwkb" x1="17.609" x2="17.514" y1="18.734" y2="19.406" gradientUnits="userSpaceOnUse"><stop class="ur4y6bbpz"/><stop offset="1" class="h0d9owbvi"/></linearGradient><linearGradient id="ijB2ilb" x1="23.859" x2="24.531" y1="19.703" y2="19.703" gradientUnits="userSpaceOnUse"><stop class="ur4y6bbpz"/><stop offset="1" class="h0d9owbvi"/></linearGradient><linearGradient id="iFn2nNc" x1="24.344" x2="24.531" y1="18.828" y2="19.703" gradientUnits="userSpaceOnUse"><stop class="ur4y6bbpz"/><stop offset="1" class="h0d9owbvi"/></linearGradient><linearGradient id="iSjJ6tb" x1="15.719" x2="28.003" y1="23.496" y2="23.496" gradientUnits="userSpaceOnUse"><stop class="pvyxg-b_f"/><stop offset="1" class="k7wsgtb3t"/></linearGradient><linearGradient id="im7UgUd" x1="19.413" x2="19.423" y1="6.661" y2="6.661" gradientUnits="userSpaceOnUse"><stop class="usoidibii"/><stop offset="1" class="i5-01cczj"/></linearGradient><linearGradient id="iavN2yh" x1="18.584" x2="25.959" y1="28.438" y2="24.313" gradientUnits="userSpaceOnUse"><stop class="ocru65npv"/><stop offset="1" class="phvxq6b7f"/></linearGradient><linearGradient id="ikIJoLb" x1="4.208" x2="8.407" y1="29.173" y2="26.824" gradientUnits="userSpaceOnUse"><stop class="ocru65npv"/><stop offset="1" class="phvxq6b7f"/></linearGradient><linearGradient id="i9iCp3c" x1="9.281" x2="9.625" y1="26.25" y2="27.25" gradientUnits="userSpaceOnUse"><stop class="ifox0900x"/><stop offset="1" class="wj0bzib7e"/></linearGradient><linearGradient id="i5foVid" x1="14" x2="13.438" y1="25.297" y2="25.484" gradientUnits="userSpaceOnUse"><stop class="afldn7brt"/><stop offset="1" class="wnqmvj5ti"/></linearGradient><linearGradient id="ikhsYCc" x1="6" x2="6.58" y1="27.72" y2="27.484" gradientUnits="userSpaceOnUse"><stop class="zspi2gsaf"/><stop offset="1" class="uhs3ty4ec"/></linearGradient><linearGradient id="iqc6UEb" x1="14.01" x2="22" y1="11.853" y2="11.853" gradientUnits="userSpaceOnUse"><stop class="vyof_-b9h"/><stop offset="1" class="me6vhzjpa"/></linearGradient><linearGradient id="itxRnud" x1="19.961" x2="25.242" y1="25.465" y2="25.465" gradientUnits="userSpaceOnUse"><stop class="kw10tdb5x"/><stop offset="1" class="dfbe15b7i"/></linearGradient><linearGradient id="i3v8OGc" x1="21.772" x2="22.397" y1="28.406" y2="26.188" gradientUnits="userSpaceOnUse"><stop class="xmxau7btf"/><stop offset="1" class="ymr8fbbcl"/></linearGradient><linearGradient id="i9GhkIe" x1="20.926" x2="24.282" y1="27.137" y2="23.781" gradientUnits="userSpaceOnUse"><stop class="h1wb2z3-h"/><stop offset="1" class="svcnqqeqt"/></linearGradient><linearGradient id="i2oaxnE" x1="26.875" x2="18.625" y1="4.687" y2="19.01" gradientUnits="userSpaceOnUse"><stop class="j5futybyx"/><stop offset="1" class="o5-3in8qs"/></linearGradient><linearGradient id="iGs5yZc" x1="28.525" x2="24.905" y1="13.736" y2="13.38" gradientUnits="userSpaceOnUse"><stop class="bfyrlib4i"/><stop offset="1" class="pbrgqcb1k"/></linearGradient><linearGradient id="i24rRHG" x1="26.791" x2="24.394" y1="2.059" y2="17.357" gradientUnits="userSpaceOnUse"><stop class="t5g4_15wp"/><stop offset="1" class="sz8p3ubkl"/></linearGradient><linearGradient id="iOt0MXR" x1="21.496" x2="12.993" y1="11.6" y2="11.6" gradientUnits="userSpaceOnUse"><stop class="k6uh48ddq"/><stop offset="1" class="h63u9ot6n"/></linearGradient><linearGradient id="iDRzlje" x1="13.003" x2="13.132" y1="25.016" y2="26.539" gradientUnits="userSpaceOnUse"><stop class="egjx2q3pw"/><stop offset="1" class="zvjraxbur"/></linearGradient><filter id="iF6bM8d" width="17.79" height="7.45" x="10.6" y="19.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6" dy="-.3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.133333 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11279"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.133333 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_11279" result="effect2_innerShadow_18_11279"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.384314 0 0 0 0 0.517647 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_11279" result="effect3_innerShadow_18_11279"/></filter><filter id="iCJpBdC" width="9.281" height="9.031" x="17.969" y="21.109" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.443137 0 0 0 0 0.376471 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11279"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.12549 0 0 0 0 0.0980392 0 0 0 0 0.14902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_11279" result="effect2_innerShadow_18_11279"/></filter><filter id="iKdOyAb" width="5.5" height="5.25" x="3.75" y="25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.12549 0 0 0 0 0.0980392 0 0 0 0 0.14902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11279"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.443137 0 0 0 0 0.376471 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_11279" result="effect2_innerShadow_18_11279"/></filter><filter id="iBhFXKd" width="4.563" height="4.563" x="4.219" y="25.219" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_11279" stdDeviation=".25"/></filter><filter id="iksKWjb" width="3.15" height="3.2" x="4.85" y="26" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.298039 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11279"/></filter><filter id="iF4LNed" width="6.688" height="6.688" x="19.209" y="22.121" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_11279" stdDeviation=".25"/></filter><filter id="icGVf6d" width="5.147" height="5.147" x="20.028" y="22.891" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_11279" stdDeviation=".1"/></filter><filter id="itmCbvt" width="16.51" height="17.51" x="12.99" y="1.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.439216 0 0 0 0 0.623529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11279"/></filter><filter id="i4useKe" width="4.938" height="17.176" x="24.322" y="1.681" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_11279" stdDeviation=".5"/></filter><filter id="im3FRBc" width="7.97" height="3.801" x="14.526" y="9.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_11279" stdDeviation=".5"/></filter><filter id="ifpOafe" width="8.035" height="3.155" x="6.25" y="24.801" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_11279" stdDeviation=".25"/></filter><radialGradient id="itLTTae" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.87353 -1.23725 0 17.255 19.841)" gradientUnits="userSpaceOnUse"><stop class="ct7xhqbgc"/><stop offset="1" class="gzf1gxbvr"/></radialGradient><radialGradient id="iFIZSwd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.87353 -1.23107 0 25.258 19.841)" gradientUnits="userSpaceOnUse"><stop class="ct7xhqbgc"/><stop offset="1" class="gzf1gxbvr"/></radialGradient><radialGradient id="ioZfbub" cx="0" cy="0" r="1" gradientTransform="matrix(-4.65625 0 0 -4.90625 21 26.219)" gradientUnits="userSpaceOnUse"><stop offset=".658" class="t0qxz0bwh"/><stop offset="1" class="zrmrawbew"/></radialGradient><radialGradient id="iwilLpc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5 .84373 -.1944 -.576 7.5 27.5)" gradientUnits="userSpaceOnUse"><stop offset=".407" class="namu8gbfy"/><stop offset="1" class="ywb-fmxvh"/></radialGradient><radialGradient id="i3gzVqe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8647 -4.61456 0 17.605 14.859)" gradientUnits="userSpaceOnUse"><stop class="b6dbpzbrb"/><stop offset="1" class="ltsx1lxbe"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:motorized-wheelchair" /></template>
<style>
.afldn7brt {
  stop-color: var(--svg-color--d5cbc6, #D5CBC6);
}

.b6dbpzbrb {
  stop-color: var(--svg-color--439db9, #439DB9);
}

.bfyrlib4i {
  stop-color: var(--svg-color--6de7ff, #6DE7FF);
}

.c8wjcqbwv {
  d: path("M22.602 28.106a2.64 2.64 0 1 0 0-5.282a2.64 2.64 0 0 0 0 5.281");
}

.ct7xhqbgc {
  stop-color: var(--svg-color--9f9ca7, #9F9CA7);
}

.dfbe15b7i {
  stop-color: var(--svg-color--d2c8c6, #D2C8C6);
}

.dv4b8ooqj {
  fill: var(--svg-color--2b2030, #2B2030);
  d: path("M22.553 28.309a2.844 2.844 0 1 0 0-5.688a2.844 2.844 0 0 0 0 5.688");
}

.egjx2q3pw {
  stop-color: var(--svg-color--ccc2bf, #CCC2BF);
}

.ek3_kacof {
  d: path("M6.5 30a2.5 2.5 0 1 0 0-5a2.5 2.5 0 0 0 0 5");
}

.fcb_bfb2s {
  d: path("M18 18h-2v4h2z");
}

.fhsm1dbnb {
  d: path("M22.61 29.89a4.39 4.39 0 1 0 0-8.78a4.39 4.39 0 0 0 0 8.78");
}

.ft5dv1b6b {
  fill: none;
}

.gzf1gxbvr {
  stop-color: var(--svg-color--616168, #616168);
}

.h0d9owbvi {
  stop-color: var(--svg-color--4f5059, #4F5059);
  stop-opacity: 0;
}

.h1wb2z3-h {
  stop-color: var(--svg-color--a497a1, #A497A1);
}

.h63u9ot6n {
  stop-color: var(--svg-color--756587, #756587);
  stop-opacity: 0;
}

.i44v0ccyo {
  d: path("M26 18h-1.99v4H26z");
}

.i5-01cczj {
  stop-color: var(--svg-color--ff8213, #FF8213);
}

.i8r9u6lxj {
  fill: var(--svg-color--513469, #513469);
  d: path("M25 17.99a.99.99 0 1 0 0-1.98a.99.99 0 0 0 0 1.98");
}

.ifox0900x {
  stop-color: var(--svg-color--9b9694, #9B9694);
}

.j5futybyx {
  stop-color: var(--svg-color--57daf4, #57DAF4);
}

.k6uh48ddq {
  stop-color: var(--svg-color--6f5d82, #6F5D82);
}

.k7wsgtb3t {
  stop-color: var(--svg-color--634e73, #634E73);
}

.kw10tdb5x {
  stop-color: var(--svg-color--685d6a, #685D6A);
}

.ltsx1lxbe {
  stop-color: var(--svg-color--439db9, #439DB9);
  stop-opacity: 0;
}

.m-e3tybyr {
  fill: var(--svg-color--958a93, #958A93);
  d: path("M6.5 29a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3");
}

.m5kkxnwqi {
  d: path("M20.78 13h-5.55c-.68 0-1.22-.55-1.22-1.22v-.55c0-.68.55-1.22 1.22-1.22h5.55c.68 0 1.22.55 1.22 1.22v.55c0 .67-.55 1.22-1.22 1.22");
}

.me6vhzjpa {
  stop-color: var(--svg-color--524370, #524370);
}

.namu8gbfy {
  stop-color: var(--svg-color--766677, #766677);
}

.o5-3in8qs {
  stop-color: var(--svg-color--45c0f2, #45C0F2);
}

.obi00lklp {
  d: path("M26 2c-1.11 0-2 .95-2 2.5c0 .58.15 1.06.5 1.5c-.63.9-1.28 3.06-1.5 7v2h-8.9c-.61 0-1.11.5-1.11 1.11v1.79c0 .61.5 1.11 1.11 1.11h11.49c.8 0 1.47-.6 1.56-1.39L29 3c0-.5-.45-.99-1-.99h-2z");
}

.ocru65npv {
  stop-color: var(--svg-color--3f3646, #3F3646);
}

.pbrgqcb1k {
  stop-color: var(--svg-color--6de7ff, #6DE7FF);
  stop-opacity: 0;
}

.phvxq6b7f {
  stop-color: var(--svg-color--5a4569, #5A4569);
}

.pvyxg-b_f {
  stop-color: var(--svg-color--423b46, #423B46);
}

.rcse30b-s {
  d: path("M16.69 20h-.1C13.5 20 11 22.5 11 25.59v.1c0 .72.59 1.31 1.31 1.31h14.43c.69 0 1.25-.56 1.25-1.25v-4.49c0-.69-.56-1.25-1.25-1.25H16.69z");
}

.sjc-nobph {
  fill-rule: evenodd;
  d: path("M13.98 25.363a.5.5 0 0 1-.343.618l-7 2a.5.5 0 0 1-.274-.962l7-2a.5.5 0 0 1 .618.344");
}

.svcnqqeqt {
  stop-color: var(--svg-color--b8aab1, #B8AAB1);
}

.sz8p3ubkl {
  stop-color: var(--svg-color--93f9ff, #93F9FF);
  stop-opacity: 0;
}

.t0qxz0bwh {
  stop-color: var(--svg-color--2d2036, #2D2036);
}

.t5g4_15wp {
  stop-color: var(--svg-color--93f9ff, #93F9FF);
}

.tlv2pob-i {
  stroke-linecap: round;
  d: path("m27.76 3.181l-1.938 14.176");
}

.uhs3ty4ec {
  stop-color: var(--svg-color--544d59, #544D59);
  stop-opacity: 0;
}

.ur4y6bbpz {
  stop-color: var(--svg-color--4f5059, #4F5059);
}

.usoidibii {
  stop-color: var(--svg-color--ed088e, #ED088E);
}

.uu27stiro {
  d: path("M19.42 6.66v.01h-.01z");
}

.vyof_-b9h {
  stop-color: var(--svg-color--2f2d30, #2F2D30);
}

.wj0bzib7e {
  stop-color: var(--svg-color--8c788f, #8C788F);
}

.wnqmvj5ti {
  stop-color: var(--svg-color--d5cbc6, #D5CBC6);
  stop-opacity: 0;
}

.x077bxdnn {
  fill: var(--svg-color--34253e, #34253E);
  d: path("M6.5 29.281a1.781 1.781 0 1 0 0-3.562a1.781 1.781 0 0 0 0 3.562");
}

.xa9v8u8ys {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M13.66 25.426L6.875 27.33");
}

.xmxau7btf {
  stop-color: var(--svg-color--705875, #705875);
}

.y_d1hrbzf {
  stroke: var(--svg-color--9b9b9b, #9B9B9B);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m20.4 11.6l4 6");
}

.yd6c5etro {
  d: path("M20.977 10.7a.52.52 0 0 1 .519.519v.762a.52.52 0 0 1-.52.52h-.291a.227.227 0 0 1-.227-.228a.23.23 0 0 0-.211-.227l-4.628-.345c-.124-.009-.124-.19 0-.2l4.618-.327a.237.237 0 0 0 .22-.237c0-.131.107-.237.238-.237z");
}

.ymr8fbbcl {
  stop-color: var(--svg-color--705875, #705875);
  stop-opacity: 0;
}

.ys3pqlbzw {
  d: path("M22.602 27.838a2.373 2.373 0 1 0 0-4.747a2.373 2.373 0 0 0 0 4.747");
}

.ysn4ppbcd {
  d: path("M6.5 29a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3");
}

.ywb-fmxvh {
  stop-color: var(--svg-color--766677, #766677);
  stop-opacity: 0;
}

.zrmrawbew {
  stop-color: var(--svg-color--2d2036, #2D2036);
  stop-opacity: 0;
}

.zspi2gsaf {
  stop-color: var(--svg-color--544d59, #544D59);
}

.zvjraxbur {
  stop-color: var(--svg-color--ccc2bf, #CCC2BF);
  stop-opacity: 0;
}

</style>
