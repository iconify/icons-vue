<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ieesmec)"><rect fill="url(#in8dRtc)" class="v7sf8qkpr"/><rect fill="url(#i580kXd)" class="v7sf8qkpr"/></g><rect fill="url(#iEObTcU)" class="v7sf8qkpr"/><rect fill="url(#iOTpmvc)" class="v7sf8qkpr"/><rect fill="url(#iiSeg4D)" class="v7sf8qkpr"/><g filter="url(#ipcNONe)"><path fill="url(#iXib1Ht)" class="kqchtbrql"/><path fill="url(#iakCOBF)" class="kqchtbrql"/><path fill="url(#iV1jfId)" class="kqchtbrql"/><path fill="url(#iZNMIVc)" class="kqchtbrql"/><path fill="url(#iyYdm7b)" class="kqchtbrql"/><path fill="url(#i6bcQBc)" class="kqchtbrql"/><path fill="url(#iwYy4ra)" class="kqchtbrql"/><path fill="url(#iLkYK4X)" class="kqchtbrql"/><path fill="url(#iP9neYr)" class="kqchtbrql"/></g><g filter="url(#io45aac)"><path fill="url(#igKaLVb)" class="sff6y-blh"/></g><g filter="url(#iujMkOe)"><path fill="url(#ipmehee)" clip-rule="evenodd" class="e9q3oacjz"/></g><rect fill="url(#i7rH0ys)" class="ifkud3bhb"/><rect fill="url(#i7I4lXd)" class="ifkud3bhb"/><rect fill="url(#igLOByc)" class="sy2c21bmd"/><rect fill="url(#iTR8jnb)" class="sy2c21bmd"/><defs><radialGradient id="i580kXd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.93083 3.16161 0 28.427 21.93)" gradientUnits="userSpaceOnUse"><stop class="op9jvk8wd"/><stop offset="1" class="rs4rg2b_o"/></radialGradient><radialGradient id="iiSeg4D" cx="0" cy="0" r="1" gradientTransform="matrix(-3.21787 2.5028 -2.54611 -3.27357 29.319 3.145)" gradientUnits="userSpaceOnUse"><stop class="i4hef-h9u"/><stop offset="1" class="xfq2zf0ze"/></radialGradient><radialGradient id="iakCOBF" cx="0" cy="0" r="1" gradientTransform="matrix(-1.89515 1.69714 -1.4974 -1.6721 17.754 6.62)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="q3m8m7bhy"/><stop offset="1" class="vxrp39aul"/></radialGradient><radialGradient id="iV1jfId" cx="0" cy="0" r="1" gradientTransform="matrix(1.52743 3.74482 -3.30409 1.34767 11.135 5.817)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="uhy_-rb7u"/><stop offset="1" class="gsrhrkoli"/></radialGradient><radialGradient id="iZNMIVc" cx="0" cy="0" r="1" gradientTransform="rotate(-164.745 11.64 3.322)scale(1.61253 2.23276)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="pud-xubcs"/><stop offset="1" class="ku2pfdbii"/></radialGradient><radialGradient id="iyYdm7b" cx="0" cy="0" r="1" gradientTransform="rotate(154.195 11.258 8.861)scale(2.8591 2.11165)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="pud-xubcs"/><stop offset="1" class="ku2pfdbii"/></radialGradient><radialGradient id="i6bcQBc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.168 -.36773 .20723 -1.78527 25.872 16.775)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="pud-xubcs"/><stop offset="1" class="ku2pfdbii"/></radialGradient><radialGradient id="iwYy4ra" cx="0" cy="0" r="1" gradientTransform="matrix(2.08227 -2.00829 1.93475 2.00602 23.015 20.48)" gradientUnits="userSpaceOnUse"><stop class="kypg0578v"/><stop offset="1" class="yiqe49k2f"/></radialGradient><radialGradient id="iLkYK4X" cx="0" cy="0" r="1" gradientTransform="rotate(-127.747 9.66 7.545)scale(2.21786 2.13665)" gradientUnits="userSpaceOnUse"><stop class="kypg0578v"/><stop offset="1" class="yiqe49k2f"/></radialGradient><radialGradient id="iP9neYr" cx="0" cy="0" r="1" gradientTransform="rotate(25.278 -24.149 20.828)scale(2.25223 2.72214)" gradientUnits="userSpaceOnUse"><stop class="mulvig9sp"/><stop offset="1" class="a_xm9geyk"/></radialGradient><radialGradient id="igKaLVb" cx="0" cy="0" r="1" gradientTransform="rotate(117.739 6.725 11.58)scale(12.9062 18.5583)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="m_kdo_bhg"/><stop offset="1" class="hemkrl1wk"/><stop offset="1" class="j756vz6_d"/></radialGradient><linearGradient id="in8dRtc" x1="9.351" x2="16.015" y1="5.961" y2="21.93" gradientUnits="userSpaceOnUse"><stop class="i32-af5jf"/><stop offset="1" class="y8skcxtgz"/></linearGradient><linearGradient id="iEObTcU" x1="16.015" x2="16.015" y1=".698" y2="4.905" gradientUnits="userSpaceOnUse"><stop class="mz6senizl"/><stop offset="1" class="sm2_-gbcq"/></linearGradient><linearGradient id="iOTpmvc" x1="30.788" x2="27.107" y1="14.476" y2="14.476" gradientUnits="userSpaceOnUse"><stop class="bjii42v4j"/><stop offset="1" class="igiwlmbkz"/></linearGradient><linearGradient id="iXib1Ht" x1="21.632" x2="11.297" y1="8.93" y2="22.115" gradientUnits="userSpaceOnUse"><stop class="sp-1hjj_t"/><stop offset="1" class="b-eeydb1k"/></linearGradient><linearGradient id="ipmehee" x1="8.806" x2="27.212" y1="25" y2="25" gradientUnits="userSpaceOnUse"><stop class="r4udeabtg"/><stop offset="1" class="utj_swlmf"/></linearGradient><linearGradient id="i7rH0ys" x1="16.015" x2="16.015" y1="23" y2="24" gradientUnits="userSpaceOnUse"><stop class="kcnqohhmo"/><stop offset="1" class="h5xwibcad"/></linearGradient><linearGradient id="i7I4lXd" x1="24.344" x2="22.69" y1="24" y2="24" gradientUnits="userSpaceOnUse"><stop class="bqikzab5h"/><stop offset="1" class="opr268drx"/></linearGradient><linearGradient id="igLOByc" x1="16.015" x2="16.015" y1="26" y2="27" gradientUnits="userSpaceOnUse"><stop class="kcnqohhmo"/><stop offset="1" class="h5xwibcad"/></linearGradient><linearGradient id="iTR8jnb" x1="20.179" x2="19.352" y1="27" y2="27" gradientUnits="userSpaceOnUse"><stop class="bqikzab5h"/><stop offset="1" class="opr268drx"/></linearGradient><filter id="ieesmec" width="29.5" height="28" x="2.015" y="2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.5"/><feGaussianBlur stdDeviation="1.125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.301961 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8062"/></filter><filter id="ipcNONe" width="21.166" height="21.856" x="4.182" y="5.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.25" dy=".8"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.8 0 0 0 0 0.180392 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_8062"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_8062" result="shape"/></filter><filter id="io45aac" width="15.066" height="15.066" x="8.167" y="7.974" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.921569 0 0 0 0 0.47451 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_8062"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_8062" result="shape"/></filter><filter id="iujMkOe" width="30" height="11" x="1.015" y="19.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1" dy=".5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.894118 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_8062"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.329412 0 0 0 0 0.756863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_8062" result="effect2_innerShadow_18_8062"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:sunrise" /></template>
<style>
.a_xm9geyk {
  stop-color: var(--svg-color--f0851d, #F0851D);
  stop-opacity: 0;
}

.b-eeydb1k {
  stop-color: var(--svg-color--e46e2d, #E46E2D);
}

.bjii42v4j {
  stop-color: var(--svg-color--ff755a, #FF755A);
}

.bqikzab5h {
  stop-color: var(--svg-color--f0ccff, #F0CCFF);
}

.e9q3oacjz {
  fill-rule: evenodd;
  d: path("M6.012 30a4 4 0 0 1-3.997-4v-5.5c.375-.25.75-.5 1.5-.5s1.125.25 1.5.5s.75.5 1.5.5s1.125-.25 1.5-.5s.75-.5 1.5-.5s1.25.25 1.75.5s1 .5 1.75.5s1.125-.25 1.5-.5s.75-.5 1.5-.5s1.125.25 1.5.5s.75.5 1.5.5s1.25-.25 1.75-.5s1-.5 1.75-.5s1.125.25 1.5.5s.75.5 1.5.5s1.125-.25 1.5-.5s.75-.5 1.5-.5s1.125.25 1.5.5V26a4 4 0 0 1-3.997 4z");
}

.ft5dv1b6b {
  fill: none;
}

.gsrhrkoli {
  stop-color: var(--svg-color--ff942a, #FF942A);
  stop-opacity: 0;
}

.h5xwibcad {
  stop-color: var(--svg-color--ffe8ff, #FFE8FF);
}

.hemkrl1wk {
  stop-color: var(--svg-color--dca21c, #DCA21C);
}

.i32-af5jf {
  stop-color: var(--svg-color--ff4b4b, #FF4B4B);
}

.i4hef-h9u {
  stop-color: var(--svg-color--ff6a64, #FF6A64);
}

.ifkud3bhb {
  width: 16px;
  height: 1px;
  x: 8.015px;
  y: 23px;
  rx: 0.5px;
}

.igiwlmbkz {
  stop-color: var(--svg-color--ff755a, #FF755A);
  stop-opacity: 0;
}

.j756vz6_d {
  stop-color: var(--svg-color--d89a29, #D89A29);
}

.kcnqohhmo {
  stop-color: var(--svg-color--ffd8ff, #FFD8FF);
}

.kqchtbrql {
  d: path("M14.304 6.55a2.263 2.263 0 0 1 3.332-.001l.582.633a.91.91 0 0 0 .743.29l1.098-.093a2.263 2.263 0 0 1 2.444 2.055l.045.503c.028.316.22.594.504.734l.763.372a2.263 2.263 0 0 1 .826 3.38l-.202.273a.905.905 0 0 0-.002 1.074l.221.302a2.263 2.263 0 0 1-.952 3.427l-.756.316a.9.9 0 0 0-.543.679l-.215 1.225a1.81 1.81 0 0 1-2.037 1.48l-1.28-.181a.9.9 0 0 0-.756.246l-.93.9a1.81 1.81 0 0 1-2.519 0l-.929-.9a.9.9 0 0 0-.756-.246l-1.305.185a1.81 1.81 0 0 1-2.033-1.455l-.23-1.214a.9.9 0 0 0-.507-.652l-.67-.312a2.263 2.263 0 0 1-.977-3.229l.35-.575a.9.9 0 0 0-.022-.977l-.268-.397a2.263 2.263 0 0 1 1.182-3.42l.317-.101a.905.905 0 0 0 .624-.79l.07-.888a2.263 2.263 0 0 1 2.915-1.986l.447.136a.9.9 0 0 0 .93-.254z");
}

.ku2pfdbii {
  stop-color: var(--svg-color--ffa13d, #FFA13D);
  stop-opacity: 0;
}

.kypg0578v {
  stop-color: var(--svg-color--e0762a, #E0762A);
}

.m_kdo_bhg {
  stop-color: var(--svg-color--ffd83e, #FFD83E);
}

.mulvig9sp {
  stop-color: var(--svg-color--f0851d, #F0851D);
}

.mz6senizl {
  stop-color: var(--svg-color--eb5551, #EB5551);
}

.op9jvk8wd {
  stop-color: var(--svg-color--ff8d58, #FF8D58);
}

.opr268drx {
  stop-color: var(--svg-color--f0ccff, #F0CCFF);
  stop-opacity: 0;
}

.pud-xubcs {
  stop-color: var(--svg-color--ffa13d, #FFA13D);
}

.q3m8m7bhy {
  stop-color: var(--svg-color--ffa13a, #FFA13A);
}

.r4udeabtg {
  stop-color: var(--svg-color--5087ff, #5087FF);
}

.rs4rg2b_o {
  stop-color: var(--svg-color--ff8d58, #FF8D58);
  stop-opacity: 0;
}

.sff6y-blh {
  d: path("M16 22.44a7.233 7.233 0 1 0 0-14.466a7.233 7.233 0 0 0 0 14.466");
}

.sm2_-gbcq {
  stop-color: var(--svg-color--eb5551, #EB5551);
  stop-opacity: 0;
}

.sp-1hjj_t {
  stop-color: var(--svg-color--ff8e28, #FF8E28);
}

.sy2c21bmd {
  width: 8px;
  height: 1px;
  x: 12.015px;
  y: 26px;
  rx: 0.5px;
}

.uhy_-rb7u {
  stop-color: var(--svg-color--ff942a, #FF942A);
}

.utj_swlmf {
  stop-color: var(--svg-color--63b9ff, #63B9FF);
}

.v7sf8qkpr {
  width: 28px;
  height: 28px;
  x: 2.015px;
  y: 2px;
  rx: 4px;
}

.vxrp39aul {
  stop-color: var(--svg-color--ffa13a, #FFA13A);
  stop-opacity: 0;
}

.xfq2zf0ze {
  stop-color: var(--svg-color--ff6a64, #FF6A64);
  stop-opacity: 0;
}

.y8skcxtgz {
  stop-color: var(--svg-color--ff7a45, #FF7A45);
}

.yiqe49k2f {
  stop-color: var(--svg-color--e0762a, #E0762A);
  stop-opacity: 0;
}

</style>
