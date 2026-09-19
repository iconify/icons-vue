<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iesLCec)"><path fill="url(#iI66fQe)" class="xm2_kbbxu"/><path fill="url(#iRcDfPe)" class="xm2_kbbxu"/></g><path fill="url(#iiUR6wc)" class="xm2_kbbxu"/><path fill="url(#iBOSKye)" class="xm2_kbbxu"/><path fill="url(#iK2TItc)" class="xm2_kbbxu"/><path fill="url(#i3oJ0He)" class="xm2_kbbxu"/><path fill="url(#i7tXjle)" class="og_xgdpfc"/><path fill="url(#iAUb8Oc)" class="r0s91qbeb"/><path fill="url(#iIexnor)" class="r0s91qbeb"/><path fill="url(#ilcmygb)" class="spatiubwr"/><path fill="url(#ibQQhce)" class="spatiubwr"/><path fill="url(#iGZZfzE)" class="i77ur4w2w"/><g filter="url(#if4Z2Eb)"><path fill="url(#i4ZTILc)" class="tts6r1bbl"/></g><g filter="url(#iSUZr0R)"><path fill="url(#iB5TLZb)" class="fqen9etra"/></g><defs><linearGradient id="iI66fQe" x1="23.713" x2="23.713" y1="6.305" y2="16.59" gradientUnits="userSpaceOnUse"><stop class="ab-nrvl3q"/><stop offset="1" class="o-on8ubcr"/></linearGradient><linearGradient id="iiUR6wc" x1="28.724" x2="24.408" y1="11.495" y2="13.31" gradientUnits="userSpaceOnUse"><stop class="fl4j_6jnh"/><stop offset="1" class="hsyj-en7u"/></linearGradient><linearGradient id="iK2TItc" x1="23.713" x2="21.881" y1="5.172" y2="9.399" gradientUnits="userSpaceOnUse"><stop class="j-kgqt6yn"/><stop offset="1" class="h53a6hkdh"/></linearGradient><linearGradient id="i7tXjle" x1="10.466" x2="3.903" y1="15.627" y2="29.252" gradientUnits="userSpaceOnUse"><stop class="ru-95ot8w"/><stop offset="1" class="mwulmjvsd"/></linearGradient><linearGradient id="iAUb8Oc" x1="6.887" x2="-.88" y1="13.384" y2="28.256" gradientUnits="userSpaceOnUse"><stop class="jk_l4wbgy"/><stop offset="1" class="ssypcwb8f"/></linearGradient><linearGradient id="iIexnor" x1="2.751" x2="2.751" y1="30.22" y2="28.939" gradientUnits="userSpaceOnUse"><stop class="spdv55oom"/><stop offset="1" class="ipebggb9z"/></linearGradient><linearGradient id="ilcmygb" x1="7.227" x2="11.041" y1="29.335" y2="16.547" gradientUnits="userSpaceOnUse"><stop class="ys3qhnron"/><stop offset="1" class="noihk-gwr"/></linearGradient><linearGradient id="ibQQhce" x1="5.778" x2="6.466" y1="25.158" y2="25.377" gradientUnits="userSpaceOnUse"><stop class="eujtlcb1v"/><stop offset="1" class="qmktddcvi"/></linearGradient><linearGradient id="iGZZfzE" x1="10.497" x2="12.829" y1="23.876" y2="29.881" gradientUnits="userSpaceOnUse"><stop class="rzmxw855z"/><stop offset="1" class="wvtjtuk8v"/></linearGradient><linearGradient id="i4ZTILc" x1="15.161" x2="21.047" y1="13.752" y2="29.876" gradientUnits="userSpaceOnUse"><stop class="ffylae8cd"/><stop offset="1" class="nxwi4ib-b"/></linearGradient><linearGradient id="iB5TLZb" x1="16.778" x2="21.215" y1="18.564" y2="21.251" gradientUnits="userSpaceOnUse"><stop class="x-f_x2_km"/><stop offset="1" class="rmdevrbhr"/></linearGradient><radialGradient id="iRcDfPe" cx="0" cy="0" r="1" gradientTransform="matrix(-.73504 .33772 -.33568 -.7306 23.422 5.923)" gradientUnits="userSpaceOnUse"><stop class="bg12h8riz"/><stop offset="1" class="krihpvb0q"/></radialGradient><radialGradient id="iBOSKye" cx="0" cy="0" r="1" gradientTransform="matrix(-.57883 .40314 -.34938 -.50164 28.724 12.417)" gradientUnits="userSpaceOnUse"><stop class="ezqf9zbwy"/><stop offset="1" class="kr139vbew"/></radialGradient><radialGradient id="i3oJ0He" cx="0" cy="0" r="1" gradientTransform="rotate(137.121 10.503 7.411)scale(.83264 .60737)" gradientUnits="userSpaceOnUse"><stop class="mkdkzebig"/><stop offset="1" class="qweqosb-i"/></radialGradient><filter id="iesLCec" width="10.522" height="10.745" x="18.452" y="5.302" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.792157 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7505"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.4 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_7505" result="effect2_innerShadow_18_7505"/></filter><filter id="if4Z2Eb" width="22.328" height="16.497" x="7.812" y="13.384" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.168627 0 0 0 0 0.6 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7505"/></filter><filter id="iSUZr0R" width="5.862" height="4.772" x="16.17" y="17.108" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".05"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.619608 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7505"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.05"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.619608 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_7505" result="effect2_innerShadow_18_7505"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:tent" /></template>
<style>
.ab-nrvl3q {
  stop-color: var(--svg-color--ffbd2a, #FFBD2A);
}

.bg12h8riz {
  stop-color: var(--svg-color--ffdf59, #FFDF59);
}

.eujtlcb1v {
  stop-color: var(--svg-color--117605, #117605);
}

.ezqf9zbwy {
  stop-color: var(--svg-color--ffab5c, #FFAB5C);
}

.ffylae8cd {
  stop-color: var(--svg-color--4dd84e, #4DD84E);
}

.fl4j_6jnh {
  stop-color: var(--svg-color--ff8b32, #FF8B32);
}

.fqen9etra {
  d: path("m17.128 20.244l-.758-1.957c-.168-.452.105-1.07.586-1.081l2.106-.048a2 2 0 0 1 1.913 1.286l.825 2.253c.281.781-.203 1.133-.727 1.133H18.94c-.751 0-1.523-.766-1.812-1.586");
}

.ft5dv1b6b {
  fill: none;
}

.h53a6hkdh {
  stop-color: var(--svg-color--ffc81c, #FFC81C);
  stop-opacity: 0;
}

.hsyj-en7u {
  stop-color: var(--svg-color--ff8b32, #FF8B32);
  stop-opacity: 0;
}

.i77ur4w2w {
  d: path("M9.495 16.748L9.34 29.88h6.981z");
}

.ipebggb9z {
  stop-color: var(--svg-color--54a193, #54A193);
  stop-opacity: 0;
}

.j-kgqt6yn {
  stop-color: var(--svg-color--ffc81c, #FFC81C);
}

.jk_l4wbgy {
  stop-color: var(--svg-color--2b9a25, #2B9A25);
}

.kr139vbew {
  stop-color: var(--svg-color--ffab5c, #FFAB5C);
  stop-opacity: 0;
}

.krihpvb0q {
  stop-color: var(--svg-color--ffdf59, #FFDF59);
  stop-opacity: 0;
}

.mkdkzebig {
  stop-color: var(--svg-color--ffde55, #FFDE55);
}

.mwulmjvsd {
  stop-color: var(--svg-color--1a680b, #1A680B);
}

.noihk-gwr {
  stop-color: var(--svg-color--0b7f0c, #0B7F0C);
}

.nxwi4ib-b {
  stop-color: var(--svg-color--56be4d, #56BE4D);
}

.o-on8ubcr {
  stop-color: var(--svg-color--ff6e30, #FF6E30);
}

.og_xgdpfc {
  d: path("M2.06 28.526L7.782 13.45l8.538 16.43H2.994c-.7 0-1.165-.407-.934-1.355");
}

.qmktddcvi {
  stop-color: var(--svg-color--117605, #117605);
  stop-opacity: 0;
}

.qweqosb-i {
  stop-color: var(--svg-color--ffde55, #FFDE55);
  stop-opacity: 0;
}

.r0s91qbeb {
  d: path("M7.805 13.384L2.06 28.526c-.231.948.234 1.355.934 1.355h.344c-.7 0-1.165-.407-.935-1.355l5.625-14.833z");
}

.rmdevrbhr {
  stop-color: var(--svg-color--64a858, #64A858);
}

.ru-95ot8w {
  stop-color: var(--svg-color--104803, #104803);
}

.rzmxw855z {
  stop-color: var(--svg-color--1c361b, #1C361B);
}

.spatiubwr {
  d: path("M4.361 29.881h11.96L9.39 16.547z");
}

.spdv55oom {
  stop-color: var(--svg-color--54a193, #54A193);
}

.ssypcwb8f {
  stop-color: var(--svg-color--2c8127, #2C8127);
}

.tts6r1bbl {
  d: path("M29.34 29.881H14.962a2 2 0 0 1-1.89-1.343l-5.26-15.154h15.407a1 1 0 0 1 .937.651l5.652 15.172a.5.5 0 0 1-.469.674");
}

.wvtjtuk8v {
  stop-color: var(--svg-color--233b24, #233B24);
}

.x-f_x2_km {
  stop-color: var(--svg-color--5da74c, #5DA74C);
}

.xm2_kbbxu {
  d: path("M28.662 12.995c.211-.43-.14-.921-.618-.876q-.21.02-.422.02c-2.278-.05-4.647-1.539-4.55-4.413c0-.473.106-.924.265-1.33c.193-.494-.287-.926-.652-.83c-2.314.606-3.983 2.54-3.983 5.027c0 2.925 2.347 5.205 5.272 5.205c2.086 0 3.794-.987 4.688-2.803");
}

.ys3qhnron {
  stop-color: var(--svg-color--287a1f, #287A1F);
}

</style>
