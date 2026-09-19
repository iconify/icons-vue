<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iz4o4Ee)" class="wmr5pvbzz"/><path fill="url(#iiuIbdb)" class="wmr5pvbzz"/><g filter="url(#itrPD9b)"><path fill="url(#ixBzUjc)" class="qo3hv3b5m"/></g><path fill="url(#il1dNBi)" class="qo3hv3b5m"/><g filter="url(#idUUfBs)"><path fill="url(#iags27d)" class="z4jutjb1z"/></g><path fill="url(#iq6eKxb)" class="z4jutjb1z"/><path fill="url(#isy1bNc)" class="z4jutjb1z"/><path fill="url(#iOSUJ8d)" class="is2fa58tt"/><path fill="url(#iIxFjUd)" class="u_k81sb_t"/><path fill="url(#i6AZkNd)" class="y7gwke7gs"/><path fill="url(#iLAjALL)" class="bi6ngbbor"/><path fill="url(#iDp2uwm)" class="e7mfmx4zk"/><path fill="url(#icONWJc)" class="pf7rsbcuq"/><g filter="url(#i20QKbd)"><path fill="url(#i3mXy7b)" class="irrk0ibyv"/><path fill="url(#iUrW7mB)" class="irrk0ibyv"/></g><g filter="url(#itqM6jc)"><path fill="url(#iSXvmdb)" class="chlrddbfj"/><path fill="url(#inLgEKd)" class="chlrddbfj"/></g><defs><radialGradient id="iiuIbdb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.5625 1.55303 0 16.746 26.687)" gradientUnits="userSpaceOnUse"><stop class="wkks4rbzy"/><stop offset="1" class="tego45b8c"/></radialGradient><radialGradient id="ixBzUjc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.59853 9.93119 0 21.058 29.942)" gradientUnits="userSpaceOnUse"><stop class="x7hzf_bmt"/><stop offset="1" class="mny0uvsrw"/></radialGradient><radialGradient id="iags27d" cx="0" cy="0" r="1" gradientTransform="matrix(0 11.9063 -7.34787 0 16 12.781)" gradientUnits="userSpaceOnUse"><stop class="n0epus43l"/><stop offset="1" class="rnm0ksbdp"/></radialGradient><radialGradient id="iq6eKxb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.93753 4.18747 -5.89101 -6.9462 19.746 4.625)" gradientUnits="userSpaceOnUse"><stop class="qiy8_fa6k"/><stop offset="1" class="d47h2n8pu"/></radialGradient><radialGradient id="isy1bNc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.94995 7.5 0 15.496 22.012)" gradientUnits="userSpaceOnUse"><stop class="zd6edsbzm"/><stop offset="1" class="opr-2bb0a"/></radialGradient><radialGradient id="iIxFjUd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.34375 -7.37072 0 12.758 10.906)" gradientUnits="userSpaceOnUse"><stop offset=".427" class="e4vc1lulh"/><stop offset="1" class="bkwu7aclq"/></radialGradient><radialGradient id="i6AZkNd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.34375 -7.37072 0 12.758 14.057)" gradientUnits="userSpaceOnUse"><stop offset=".427" class="e4vc1lulh"/><stop offset="1" class="bkwu7aclq"/></radialGradient><radialGradient id="iLAjALL" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.46957 -4.62157 0 19.242 8.135)" gradientUnits="userSpaceOnUse"><stop offset=".355" class="e4vc1lulh"/><stop offset="1" class="lwe_if4nl"/></radialGradient><radialGradient id="iDp2uwm" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.03125 -6.38796 0 19.242 10.906)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="e4vc1lulh"/><stop offset="1" class="bkwu7aclq"/></radialGradient><radialGradient id="icONWJc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.34375 -7.37072 0 19.242 14.057)" gradientUnits="userSpaceOnUse"><stop offset=".427" class="e4vc1lulh"/><stop offset="1" class="bkwu7aclq"/></radialGradient><radialGradient id="iUrW7mB" cx="0" cy="0" r="1" gradientTransform="matrix(1.93317 7.77202 -3.91825 .9746 10.84 16.174)" gradientUnits="userSpaceOnUse"><stop offset=".384" class="q_t8gxb3t"/><stop offset="1" class="w1s1_e3do"/></radialGradient><radialGradient id="iSXvmdb" cx="0" cy="0" r="1" gradientTransform="rotate(99.112 6.812 17.256)scale(15.5586 7.78551)" gradientUnits="userSpaceOnUse"><stop class="tewj9u1jx"/><stop offset="1" class="anz40jbrg"/></radialGradient><radialGradient id="inLgEKd" cx="0" cy="0" r="1" gradientTransform="matrix(9.38295 13.83722 -3.98567 2.70267 8.676 13.1)" gradientUnits="userSpaceOnUse"><stop class="r4ssbdbke"/><stop offset="1" class="v7_0mxbpd"/></radialGradient><linearGradient id="iz4o4Ee" x1="14.277" x2="18.496" y1="25.948" y2="25.948" gradientUnits="userSpaceOnUse"><stop class="ccop9ib7d"/><stop offset="1" class="oxvv3yblh"/></linearGradient><linearGradient id="il1dNBi" x1="16.277" x2="16.277" y1="30.281" y2="29.313" gradientUnits="userSpaceOnUse"><stop offset=".145" class="iszj2jb8g"/><stop offset="1" class="evxjx3vhw"/></linearGradient><linearGradient id="iOSUJ8d" x1="12.758" x2="15.522" y1="8.312" y2="9.605" gradientUnits="userSpaceOnUse"><stop class="klagitd1t"/><stop offset="1" class="o7q6inbxo"/></linearGradient><linearGradient id="i3mXy7b" x1="8.551" x2="24.608" y1="21.223" y2="21.223" gradientUnits="userSpaceOnUse"><stop class="jopl09lzp"/><stop offset="1" class="myq5vyb6s"/></linearGradient><filter id="itrPD9b" width="16.484" height="4.195" x="7.996" y="25.948" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.611765 0 0 0 0 0.631373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18081"/></filter><filter id="idUUfBs" width="12.263" height="20.232" x="9.993" y="1.78" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.678431 0 0 0 0 0.678431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18081"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.556863 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_18081" result="effect2_innerShadow_18_18081"/></filter><filter id="i20QKbd" width="17.939" height="12.101" x="7.031" y="12.845" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.709804 0 0 0 0 0.682353 0 0 0 0 0.737255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18081"/></filter><filter id="itqM6jc" width="17.849" height="12.247" x="7.379" y="12.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18081" stdDeviation=".325"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:studio-microphone" /></template>
<style>
.anz40jbrg {
  stop-color: var(--svg-color--dfdae4, #DFDAE4);
  stop-opacity: 0;
}

.bi6ngbbor {
  d: path("M22.007 8.135v1.47h-4.794a.735.735 0 1 1 0-1.47z");
}

.bkwu7aclq {
  stop-color: var(--svg-color--543f68, #543F68);
}

.ccop9ib7d {
  stop-color: var(--svg-color--a29fa5, #A29FA5);
}

.chlrddbfj {
  d: path("M24.578 13.649a.325.325 0 1 0-.65 0zm-15.9 0a.325.325 0 1 0-.65 0zm15.25 0v4.12h.65v-4.12zm-5.66 9.972h-3.93v.65h3.93zm-9.59-5.853v-4.12h-.65v4.12zm5.66 5.853c-3.116 0-5.66-2.61-5.66-5.853h-.65c0 3.582 2.816 6.503 6.31 6.503zm9.59-5.853c0 3.242-2.544 5.853-5.66 5.853v.65c3.494 0 6.31-2.921 6.31-6.503z");
}

.d47h2n8pu {
  stop-color: var(--svg-color--d1ced4, #D1CED4);
  stop-opacity: 0;
}

.e4vc1lulh {
  stop-color: var(--svg-color--2e223b, #2E223B);
}

.e7mfmx4zk {
  d: path("M22.007 11.287v1.47h-4.794a.735.735 0 1 1 0-1.47z");
}

.evxjx3vhw {
  stop-color: var(--svg-color--9e87b4, #9E87B4);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.irrk0ibyv {
  d: path("M24.97 13.945a1 1 0 1 0-2 0zm-15.94 0a1 1 0 1 0-2 0zm13.94 0v4h2v-4zm-5 9h-3.94v2h3.94zm-8.94-5v-4h-2v4zm5 5a5 5 0 0 1-5-5h-2a7 7 0 0 0 7 7zm8.94-5a5 5 0 0 1-5 5v2a7 7 0 0 0 7-7z");
}

.is2fa58tt {
  d: path("M9.993 9.605v-1.47h4.794a.735.735 0 0 1 0 1.47z");
}

.iszj2jb8g {
  stop-color: var(--svg-color--b697d5, #B697D5);
}

.jopl09lzp {
  stop-color: var(--svg-color--a9a3b1, #A9A3B1);
}

.klagitd1t {
  stop-color: var(--svg-color--2e213a, #2E213A);
}

.lwe_if4nl {
  stop-color: var(--svg-color--473a55, #473A55);
}

.mny0uvsrw {
  stop-color: var(--svg-color--afa9b5, #AFA9B5);
}

.myq5vyb6s {
  stop-color: var(--svg-color--c7c1ce, #C7C1CE);
}

.n0epus43l {
  stop-color: var(--svg-color--b1a9ba, #B1A9BA);
}

.o7q6inbxo {
  stop-color: var(--svg-color--382549, #382549);
}

.opr-2bb0a {
  stop-color: var(--svg-color--a89ab7, #A89AB7);
  stop-opacity: 0;
}

.oxvv3yblh {
  stop-color: var(--svg-color--b2afb5, #B2AFB5);
}

.pf7rsbcuq {
  d: path("M22.007 14.438v1.47h-4.794a.735.735 0 1 1 0-1.47z");
}

.q_t8gxb3t {
  stop-color: var(--svg-color--959199, #959199);
}

.qiy8_fa6k {
  stop-color: var(--svg-color--f3f1f5, #F3F1F5);
}

.qo3hv3b5m {
  d: path("M9.082 27.234a2.5 2.5 0 0 1 2.185-1.286H20.7a2.5 2.5 0 0 1 2.18 1.277l1.023 1.824a.6.6 0 0 1-.524.893H8.597a.6.6 0 0 1-.525-.891z");
}

.r4ssbdbke {
  stop-color: var(--svg-color--b8adc4, #B8ADC4);
}

.rnm0ksbdp {
  stop-color: var(--svg-color--c7c4ca, #C7C4CA);
}

.tego45b8c {
  stop-color: var(--svg-color--b9b6bd, #B9B6BD);
  stop-opacity: 0;
}

.tewj9u1jx {
  stop-color: var(--svg-color--dfdae4, #DFDAE4);
}

.u_k81sb_t {
  d: path("M9.993 12.756v-1.47h4.794a.735.735 0 0 1 0 1.47z");
}

.v7_0mxbpd {
  stop-color: var(--svg-color--b8adc4, #B8ADC4);
  stop-opacity: 0;
}

.w1s1_e3do {
  stop-color: var(--svg-color--959199, #959199);
  stop-opacity: 0;
}

.wkks4rbzy {
  stop-color: var(--svg-color--b9b6bd, #B9B6BD);
}

.wmr5pvbzz {
  d: path("M13.658 23.946h4.675v2.002h-4.675z");
}

.x7hzf_bmt {
  stop-color: var(--svg-color--e1d9eb, #E1D9EB);
}

.y7gwke7gs {
  d: path("M9.993 15.907v-1.47h4.794a.735.735 0 0 1 0 1.47z");
}

.z4jutjb1z {
  d: path("M9.993 7.03a5 5 0 0 1 5-5h2.013a5 5 0 0 1 5 5v9.983a5 5 0 0 1-5 5h-2.013a5 5 0 0 1-5-5z");
}

.zd6edsbzm {
  stop-color: var(--svg-color--a89ab7, #A89AB7);
}

</style>
