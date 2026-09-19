<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i3p2dZV)"><path fill="url(#iPc8ioe)" class="quw6xiwtv"/></g><g filter="url(#iNCf9gb)"><path fill="url(#iotArmb)" class="q61oojnqo"/><path fill="url(#iUih2nb)" class="q61oojnqo"/><path fill="url(#iQlqJHc)" class="q61oojnqo"/></g><g filter="url(#iSicPnc)"><path class="p_vzxzl7w"/></g><path fill="url(#i9csAZc)" class="ktih90bru"/><path fill="url(#i80Yy1c)" class="ktih90bru"/><path fill="url(#iQ8yRJe)" class="ktih90bru"/><path fill="url(#iTvqlNb)" class="ktih90bru"/><path fill="url(#igraYYb)" class="ktih90bru"/><path fill="url(#iJR72zc)" class="zym2b_b7a"/><g filter="url(#ijtzBkf)"><path fill="url(#iLGDaxd)" class="bfyzcxbkv"/></g><g filter="url(#idXaXBe)"><path fill="url(#iInJvWd)" class="gwbfmxbrn"/></g><path fill="url(#iv8Hdsc)" class="xre21-bck"/><g filter="url(#iDHFfTb)"><path fill="url(#i7WQBOb)" class="nrzfxplod"/><path fill="url(#iGZGQJc)" class="nrzfxplod"/></g><g filter="url(#iaSaCLd)"><path class="h6ae_ebau"/></g><g filter="url(#iW0Ifqp)"><path fill="url(#iVszdhe)" class="gy_d8rsds"/><path fill="url(#iG3RSFb)" class="gy_d8rsds"/></g><g filter="url(#iPPpgEY)"><path class="zn8k3c62w"/></g><path fill="url(#ixTI4uQ)" class="ylfughb3m"/><path fill="url(#iSnD4be)" class="jrq0kqsft"/><g filter="url(#iYfMvze)"><circle stroke="url(#i6yXJ6c)" class="zw6cjjbnj"/></g><g filter="url(#ivgLC7d)"><circle stroke="url(#iIztIdd)" class="zwthofbla"/></g><g filter="url(#ifXZZve)"><path fill="url(#i7N2ovc)" clip-rule="evenodd" class="w6cr68z_y"/></g><path fill="url(#imgX7vu)" class="laxoglr-v"/><path fill="url(#iWgatyc)" class="laxoglr-v"/><defs><linearGradient id="iPc8ioe" x1="29.997" x2="16.963" y1="18.002" y2="18.002" gradientUnits="userSpaceOnUse"><stop class="s-cxfwbcw"/><stop offset="1" class="yqjepob3n"/></linearGradient><linearGradient id="iotArmb" x1="6.71" x2="17.585" y1="17.25" y2="17.25" gradientUnits="userSpaceOnUse"><stop class="fuozlsfoq"/><stop offset="1" class="m_yfj7riv"/></linearGradient><linearGradient id="iUih2nb" x1="17.272" x2="16.162" y1="17.476" y2="17.476" gradientUnits="userSpaceOnUse"><stop class="r7ye3dckf"/><stop offset="1" class="t-djmqsxt"/></linearGradient><linearGradient id="iQlqJHc" x1="14.54" x2="14.54" y1="19.162" y2="18.597" gradientUnits="userSpaceOnUse"><stop class="ei86f4s5v"/><stop offset="1" class="lxkwg2bvd"/></linearGradient><linearGradient id="i9csAZc" x1="1.963" x2="23.317" y1="23.002" y2="23.002" gradientUnits="userSpaceOnUse"><stop class="u27q232kv"/><stop offset="1" class="dg6o-417s"/></linearGradient><linearGradient id="i80Yy1c" x1="28.96" x2="27.686" y1="22.313" y2="22.313" gradientUnits="userSpaceOnUse"><stop class="uo1k3s37a"/><stop offset="1" class="wc-d6mbxj"/></linearGradient><linearGradient id="iQ8yRJe" x1="1.97" x2="3.408" y1="24.017" y2="24.017" gradientUnits="userSpaceOnUse"><stop class="kqro0z68e"/><stop offset="1" class="lbes99x8o"/></linearGradient><linearGradient id="iTvqlNb" x1="16.725" x2="16.725" y1="27" y2="25.645" gradientUnits="userSpaceOnUse"><stop class="cbkp2v6yl"/><stop offset="1" class="so0onpbdr"/></linearGradient><linearGradient id="iJR72zc" x1="8.21" x2="7.085" y1="22.938" y2="26.156" gradientUnits="userSpaceOnUse"><stop class="nny-7pbbg"/><stop offset="1" class="p8j55unrb"/></linearGradient><linearGradient id="iLGDaxd" x1="4.253" x2="28.2" y1="20.475" y2="20.475" gradientUnits="userSpaceOnUse"><stop class="u249el8pw"/><stop offset="1" class="tszjd4b1r"/></linearGradient><linearGradient id="iInJvWd" x1="11.576" x2="9.413" y1="20.248" y2="18.222" gradientUnits="userSpaceOnUse"><stop class="tejpiac0y"/><stop offset="1" class="wr-il9brv"/></linearGradient><linearGradient id="iv8Hdsc" x1="24.21" x2="23.085" y1="22.938" y2="26.156" gradientUnits="userSpaceOnUse"><stop class="yu72hqbyv"/><stop offset="1" class="gy6dkubkt"/></linearGradient><linearGradient id="i7WQBOb" x1="5.846" x2="11.103" y1="25.62" y2="25.62" gradientUnits="userSpaceOnUse"><stop offset=".239" class="baem9ki2q"/><stop offset="1" class="mmwl-dsmc"/></linearGradient><linearGradient id="iVszdhe" x1="21.846" x2="27.103" y1="25.62" y2="25.62" gradientUnits="userSpaceOnUse"><stop offset=".239" class="baem9ki2q"/><stop offset="1" class="mmwl-dsmc"/></linearGradient><linearGradient id="ixTI4uQ" x1="28.482" x2="27.296" y1="23.057" y2="21.191" gradientUnits="userSpaceOnUse"><stop class="vohhszb1z"/><stop offset=".709" class="ri98u4bhe"/></linearGradient><linearGradient id="i6yXJ6c" x1="9.076" x2="6.013" y1="24.334" y2="28.564" gradientUnits="userSpaceOnUse"><stop offset=".083" class="oeptinb4s"/><stop offset=".391" class="f0k16nibb"/><stop offset=".692" class="f0k16nibb"/><stop offset=".935" class="oeptinb4s"/></linearGradient><linearGradient id="iIztIdd" x1="24.859" x2="21.796" y1="24.334" y2="28.564" gradientUnits="userSpaceOnUse"><stop offset=".083" class="oeptinb4s"/><stop offset=".391" class="f0k16nibb"/><stop offset=".692" class="f0k16nibb"/><stop offset=".935" class="oeptinb4s"/></linearGradient><linearGradient id="i7N2ovc" x1="4.963" x2="12.963" y1="16.002" y2="16.002" gradientUnits="userSpaceOnUse"><stop class="rk6976c5h"/><stop offset="1" class="l6mnr6tok"/></linearGradient><linearGradient id="iWgatyc" x1="11.93" x2="12.246" y1="18.735" y2="18.735" gradientUnits="userSpaceOnUse"><stop class="tmhf1xbml"/><stop offset="1" class="xvzc1tz0c"/></linearGradient><filter id="i3p2dZV" width="13.18" height="2.4" x="16.82" y="16.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.192157 0 0 0 0 0.0196078 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10719"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".25"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333275 0 0 0 0 0.282795 0 0 0 0 0.379167 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10719" result="effect2_innerShadow_18_10719"/></filter><filter id="iNCf9gb" width="27.49" height="15.859" x="1.97" y="11.141" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.156863 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10719"/></filter><filter id="iSicPnc" width="2.694" height="10.13" x="14.666" y="10.935" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10719" stdDeviation=".375"/></filter><filter id="ijtzBkf" width="24.999" height="1.62" x="3.46" y="19.354" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10719" stdDeviation=".25"/></filter><filter id="idXaXBe" width="2.901" height="3.701" x="9.371" y="16.846" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10719" stdDeviation=".15"/></filter><filter id="iDHFfTb" width="7" height="7.15" x="3.96" y="23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0823529 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10719"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.0313726 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10719" result="effect2_innerShadow_18_10719"/></filter><filter id="iaSaCLd" width="3.1" height="3.1" x="5.91" y="24.95" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.364706 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10719"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.764706 0 0 0 0 0.858824 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10719" result="effect2_innerShadow_18_10719"/></filter><filter id="iW0Ifqp" width="7" height="7.15" x="19.96" y="23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0823529 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10719"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.0313726 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10719" result="effect2_innerShadow_18_10719"/></filter><filter id="iPPpgEY" width="3.1" height="3.1" x="21.91" y="24.95" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.364706 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10719"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.764706 0 0 0 0 0.858824 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10719" result="effect2_innerShadow_18_10719"/></filter><filter id="iYfMvze" width="7.392" height="7.392" x="4.006" y="22.639" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10719" stdDeviation=".375"/></filter><filter id="ivgLC7d" width="7.392" height="7.392" x="19.789" y="22.639" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10719" stdDeviation=".375"/></filter><filter id="ifXZZve" width="8.885" height="6.6" x="4.075" y="13" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75" dy="1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.129412 0 0 0 0 0.443137 0 0 0 0 0.768627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10719"/></filter><radialGradient id="igraYYb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.79604 1.4331 -.25344 -.31763 29.102 19)" gradientUnits="userSpaceOnUse"><stop class="hofswmbxh"/><stop offset="1" class="mtp4u2b4v"/></radialGradient><radialGradient id="iGZGQJc" cx="0" cy="0" r="1" gradientTransform="matrix(.79083 -1.73826 1.81555 .826 7.46 26.187)" gradientUnits="userSpaceOnUse"><stop offset=".523" class="ariye-f8h"/><stop offset="1" class="a2peghb2c"/></radialGradient><radialGradient id="iG3RSFb" cx="0" cy="0" r="1" gradientTransform="matrix(.79083 -1.73826 1.81555 .826 23.46 26.187)" gradientUnits="userSpaceOnUse"><stop offset=".523" class="ariye-f8h"/><stop offset="1" class="a2peghb2c"/></radialGradient><radialGradient id="iSnD4be" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.68752 2.25 0 2.647 24)" gradientUnits="userSpaceOnUse"><stop class="r7mtcmb2o"/><stop offset=".756" class="acyrh7w_g"/></radialGradient><radialGradient id="imgX7vu" cx="0" cy="0" r="1" gradientTransform="matrix(1.25 -1.30468 3.4823 3.33637 11.052 19.425)" gradientUnits="userSpaceOnUse"><stop class="mqne358cy"/><stop offset="1" class="tw_6yz59y"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:pickup-truck" /></template>
<style>
.a2peghb2c {
  stop-color: var(--svg-color--2b1249, #2B1249);
  stop-opacity: 0;
}

.acyrh7w_g {
  stop-color: var(--svg-color--f9d963, #F9D963);
}

.ariye-f8h {
  stop-color: var(--svg-color--2d114d, #2D114D);
}

.baem9ki2q {
  stop-color: var(--svg-color--34214f, #34214F);
}

.bfyzcxbkv {
  d: path("M3.96 19.854h23.999v.62H3.96z");
}

.cbkp2v6yl {
  stop-color: var(--svg-color--7a174d, #7A174D);
}

.dg6o-417s {
  stop-color: var(--svg-color--e5393e, #E5393E);
}

.ei86f4s5v {
  stop-color: var(--svg-color--df1a39, #DF1A39);
}

.f0k16nibb {
  stop-color: var(--svg-color--615b6b, #615B6B);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fuozlsfoq {
  stop-color: var(--svg-color--d8445d, #D8445D);
}

.gwbfmxbrn {
  d: path("M9.67 18.697c.006-.292.349-.95.77-1.297c.272-.225.704-.275 1.058-.246c.295.023.474.286.474.573v1.94c0 .287-.179.55-.474.573c-.354.029-.786-.021-1.058-.246c-.503-.327-.764-1.005-.77-1.297");
}

.gy_d8rsds {
  d: path("M23.46 30a3.5 3.5 0 1 0 0-7a3.5 3.5 0 0 0 0 7");
}

.gy6dkubkt {
  stop-color: var(--svg-color--6c1828, #6C1828);
}

.h6ae_ebau {
  fill: var(--svg-color--d9c3f0, #D9C3F0);
  d: path("M7.46 28a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3");
}

.hofswmbxh {
  stop-color: var(--svg-color--ff5755, #FF5755);
}

.jrq0kqsft {
  d: path("M2.87 24h-.91v-3h.91c.6 0 1.09.49 1.09 1.09v.82c0 .6-.49 1.09-1.09 1.09");
}

.kqro0z68e {
  stop-color: var(--svg-color--923545, #923545);
}

.ktih90bru {
  d: path("M28.71 19a.25.25 0 0 1 .25.25v6.4c0 .75-.61 1.35-1.35 1.35H3.32c-.75 0-1.35-.6-1.35-1.35V21c0-1.1.9-2 2-2z");
}

.l6mnr6tok {
  stop-color: var(--svg-color--61bff9, #61BFF9);
}

.laxoglr-v {
  d: path("M10.223 18.491c.005-.292.07-.95.492-1.297c.272-.224.704-.274 1.058-.246c.295.024.473.286.473.573v1.94c0 .288-.178.55-.473.574c-.354.028-.786-.022-1.058-.246c-.422-.348-.487-1.005-.492-1.298");
}

.lbes99x8o {
  stop-color: var(--svg-color--923545, #923545);
  stop-opacity: 0;
}

.lxkwg2bvd {
  stop-color: var(--svg-color--df1a39, #DF1A39);
  stop-opacity: 0;
}

.m_yfj7riv {
  stop-color: var(--svg-color--e24658, #E24658);
}

.mmwl-dsmc {
  stop-color: var(--svg-color--241337, #241337);
}

.mqne358cy {
  stop-color: var(--svg-color--ac2038, #AC2038);
}

.mtp4u2b4v {
  stop-color: var(--svg-color--ff5755, #FF5755);
  stop-opacity: 0;
}

.nny-7pbbg {
  stop-color: var(--svg-color--530817, #530817);
}

.nrzfxplod {
  d: path("M7.46 30a3.5 3.5 0 1 0 0-7a3.5 3.5 0 0 0 0 7");
}

.oeptinb4s {
  stop-color: var(--svg-color--615b6b, #615B6B);
}

.p_vzxzl7w {
  stroke: var(--svg-color--f95963, #F95963);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M15.666 11.936c.291-.014.694.242.694.892v7.237");
}

.p8j55unrb {
  stop-color: var(--svg-color--6d1727, #6D1727);
}

.q61oojnqo {
  d: path("M4.675 19a1 1 0 0 0 .804-.404l4.928-6.647a2 2 0 0 1 1.607-.808h3.49a1.5 1.5 0 0 1 1.499 1.488l.049 6.123a.25.25 0 0 0 .25.248H28.71a.25.25 0 0 1 .25.25V21l-1 1l1 1v2.65c0 .75-.61 1.35-1.35 1.35H3.32c-.75 0-1.35-.6-1.35-1.35V24l1.47-1.4L1.97 21c0-1.1.9-2 2-2z");
}

.quw6xiwtv {
  d: path("M30 18c0 .55-.45 1-1 1H16.97v-2H29c.55 0 1 .45 1 1");
}

.r7mtcmb2o {
  stop-color: var(--svg-color--fffb78, #FFFB78);
}

.r7ye3dckf {
  stop-color: var(--svg-color--d82533, #D82533);
}

.ri98u4bhe {
  stop-color: var(--svg-color--d61049, #D61049);
}

.rk6976c5h {
  stop-color: var(--svg-color--60bdff, #60BDFF);
}

.s-cxfwbcw {
  stop-color: var(--svg-color--3d2e42, #3D2E42);
}

.so0onpbdr {
  stop-color: var(--svg-color--7a174d, #7A174D);
  stop-opacity: 0;
}

.t-djmqsxt {
  stop-color: var(--svg-color--d82533, #D82533);
  stop-opacity: 0;
}

.tejpiac0y {
  stop-color: var(--svg-color--7f0d28, #7F0D28);
}

.tmhf1xbml {
  stop-color: var(--svg-color--d31d2f, #D31D2F);
  stop-opacity: 0;
}

.tszjd4b1r {
  stop-color: var(--svg-color--f94947, #F94947);
}

.tw_6yz59y {
  stop-color: var(--svg-color--fc5760, #FC5760);
}

.u249el8pw {
  stop-color: var(--svg-color--db4663, #DB4663);
}

.u27q232kv {
  stop-color: var(--svg-color--c7385b, #C7385B);
}

.uo1k3s37a {
  stop-color: var(--svg-color--c92725, #C92725);
}

.vohhszb1z {
  stop-color: var(--svg-color--ff406d, #FF406D);
}

.w6cr68z_y {
  fill-rule: evenodd;
  d: path("M5.479 18.596a1 1 0 0 1-.804.404H12.1c.48 0 .86-.38.86-.86V13.9c0-.5-.4-.9-.9-.9H9.628z");
}

.wc-d6mbxj {
  stop-color: var(--svg-color--c92725, #C92725);
  stop-opacity: 0;
}

.wr-il9brv {
  stop-color: var(--svg-color--7f0d28, #7F0D28);
  stop-opacity: 0;
}

.xre21-bck {
  d: path("M19.638 27h7.644a3.87 3.87 0 1 0-7.645 0");
}

.xvzc1tz0c {
  stop-color: var(--svg-color--d31d2f, #D31D2F);
}

.ylfughb3m {
  d: path("M28.96 21h-.5c-.85 0-1.54.71-1.5 1.57c.04.81.74 1.43 1.55 1.43h.45z");
}

.yqjepob3n {
  stop-color: var(--svg-color--3f2d52, #3F2D52);
}

.yu72hqbyv {
  stop-color: var(--svg-color--4d0615, #4D0615);
}

.zn8k3c62w {
  fill: var(--svg-color--d9c3f0, #D9C3F0);
  d: path("M23.46 28a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3");
}

.zw6cjjbnj {
  cx: 7.702px;
  cy: 26.335px;
  r: 2.521px;
  stroke-width: var(--svg-stroke-width--0-85px, 0.85px);
}

.zwthofbla {
  cx: 23.485px;
  cy: 26.335px;
  r: 2.521px;
  stroke-width: var(--svg-stroke-width--0-85px, 0.85px);
}

.zym2b_b7a {
  d: path("M3.637 27h7.646a3.87 3.87 0 1 0-7.645 0");
}

</style>
