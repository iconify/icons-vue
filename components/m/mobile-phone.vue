<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#iJKkw0d)" class="avymp6bxa"/><rect fill="url(#iTK0Vyb)" class="avymp6bxa"/><g filter="url(#iEKMMmc)"><path class="dbt-gfunk"/><path fill="url(#iTQQOPd)" class="d5perj03q"/></g><g filter="url(#i2VtsRb)"><path class="xsnl2cbnd"/></g><g filter="url(#ijBwGDc)"><path class="s0dxp3i6m"/></g><g filter="url(#iF1xhxe)"><path class="ldhx43b9p"/></g><g filter="url(#iK92VCb)"><path class="xwfbhzbjg"/><path fill="url(#i9bNZQd)" class="l7_jii1ul"/></g><g filter="url(#i5Bx6Pb)"><path class="tb9h17b9q"/></g><g filter="url(#ifRpqMd)"><path class="r6mkghbwh"/></g><g filter="url(#ipqwVRV)"><path class="ymipoknoz"/><path fill="url(#igGUWyd)" class="sx7s_nbpv"/></g><g filter="url(#idpqsId)"><path class="yyc-7zm-w"/></g><g filter="url(#ivZZx1b)"><path fill="url(#iKRuIhb)" class="rkd_v8rho"/></g><g filter="url(#i98wUgc)"><path fill="url(#iZRZSsG)" class="x32mj1zzk"/><path fill="url(#ixKcW5E)" class="x32mj1zzk"/><path fill="url(#ikw3a1d)" class="x32mj1zzk"/><path fill="url(#iDpqwhe)" class="x32mj1zzk"/><path fill="url(#i9ISead)" class="x32mj1zzk"/></g><path fill="url(#iPRfUdb)" class="ezvnbtbrk"/><path fill="url(#ixdXeTr)" class="ezvnbtbrk"/><path fill="url(#infnmxe)" class="ezvnbtbrk"/><path fill="url(#iYRhNEd)" class="ezvnbtbrk"/><defs><linearGradient id="iJKkw0d" x1="16" x2="16" y1="7.441" y2="26.003" gradientUnits="userSpaceOnUse"><stop class="mxpm9wbyq"/><stop offset="1" class="ybphyjb-s"/></linearGradient><linearGradient id="iTK0Vyb" x1="6.031" x2="8.344" y1="21.816" y2="21.878" gradientUnits="userSpaceOnUse"><stop offset=".031" class="veun7cb3s"/><stop offset="1" class="idv7f0bli"/></linearGradient><linearGradient id="iTQQOPd" x1="9.359" x2="10.406" y1="10.957" y2="10.957" gradientUnits="userSpaceOnUse"><stop offset=".333" class="h_fr6gbhe"/><stop offset="1" class="nn3wdhnkh"/></linearGradient><linearGradient id="i9bNZQd" x1="9.359" x2="10.406" y1="22.675" y2="22.675" gradientUnits="userSpaceOnUse"><stop offset=".333" class="h_fr6gbhe"/><stop offset="1" class="nn3wdhnkh"/></linearGradient><linearGradient id="igGUWyd" x1="19.641" x2="20.688" y1="16.816" y2="16.816" gradientUnits="userSpaceOnUse"><stop offset=".333" class="h_fr6gbhe"/><stop offset="1" class="nn3wdhnkh"/></linearGradient><linearGradient id="iKRuIhb" x1="24.453" x2="24.453" y1="5.597" y2="27.441" gradientUnits="userSpaceOnUse"><stop class="rm61x3idb"/><stop offset="1" class="rfn3a3l7h"/></linearGradient><linearGradient id="iZRZSsG" x1="16" x2="16" y1="2.035" y2="6.16" gradientUnits="userSpaceOnUse"><stop class="z613fsbfq"/><stop offset="1" class="b462nc3ap"/></linearGradient><linearGradient id="ixKcW5E" x1="17.156" x2="17.156" y1="6.316" y2="5.628" gradientUnits="userSpaceOnUse"><stop class="i0k5pcbic"/><stop offset="1" class="ke7h_0nog"/></linearGradient><linearGradient id="ikw3a1d" x1="6.031" x2="9.25" y1="6.16" y2="6.16" gradientUnits="userSpaceOnUse"><stop offset=".136" class="zhmf_hb6m"/><stop offset="1" class="dtkgx-g_z"/></linearGradient><linearGradient id="iDpqwhe" x1="25.969" x2="23.031" y1="6.16" y2="6.16" gradientUnits="userSpaceOnUse"><stop offset=".128" class="u6z2bmfhr"/><stop offset="1" class="bxwl5sscl"/></linearGradient><linearGradient id="iPRfUdb" x1="16" x2="16" y1="25.878" y2="29.956" gradientUnits="userSpaceOnUse"><stop class="zf56z5fxh"/><stop offset="1" class="jhar9mbzr"/></linearGradient><linearGradient id="ixdXeTr" x1="6.031" x2="8.438" y1="27.128" y2="27.128" gradientUnits="userSpaceOnUse"><stop offset=".164" class="zfjq88vrv"/><stop offset="1" class="n866a4bbg"/></linearGradient><linearGradient id="iYRhNEd" x1="15.688" x2="15.688" y1="25.597" y2="26.191" gradientUnits="userSpaceOnUse"><stop offset=".158" class="o-u9ei9cl"/><stop offset="1" class="p7igwxbie"/></linearGradient><filter id="iEKMMmc" width="3.913" height="3.913" x="8.903" y="8.18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy="-.3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.384314 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19048"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.498039 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_19048" result="effect2_innerShadow_18_19048"/></filter><filter id="i2VtsRb" width="3.913" height="3.913" x="14.044" y="8.18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0980392 0 0 0 0 0.572549 0 0 0 0 0.866667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19048"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0745098 0 0 0 0 0.709804 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_19048" result="effect2_innerShadow_18_19048"/></filter><filter id="ijBwGDc" width="3.913" height="3.913" x="19.184" y="8.18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.752941 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19048"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.858824 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_19048" result="effect2_innerShadow_18_19048"/></filter><filter id="iF1xhxe" width="3.913" height="3.913" x="8.903" y="14.039" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0980392 0 0 0 0 0.572549 0 0 0 0 0.866667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19048"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0745098 0 0 0 0 0.709804 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_19048" result="effect2_innerShadow_18_19048"/></filter><filter id="iK92VCb" width="3.913" height="3.913" x="8.903" y="19.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy="-.3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.384314 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19048"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.498039 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_19048" result="effect2_innerShadow_18_19048"/></filter><filter id="i5Bx6Pb" width="3.913" height="3.913" x="14.044" y="14.039" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.752941 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19048"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.858824 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_19048" result="effect2_innerShadow_18_19048"/></filter><filter id="ifRpqMd" width="3.913" height="3.913" x="14.044" y="19.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0980392 0 0 0 0 0.572549 0 0 0 0 0.866667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19048"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0745098 0 0 0 0 0.709804 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_19048" result="effect2_innerShadow_18_19048"/></filter><filter id="ipqwVRV" width="3.913" height="3.913" x="19.184" y="14.039" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy="-.3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.384314 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19048"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.498039 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_19048" result="effect2_innerShadow_18_19048"/></filter><filter id="idpqsId" width="3.913" height="3.913" x="19.184" y="19.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.752941 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19048"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.858824 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_19048" result="effect2_innerShadow_18_19048"/></filter><filter id="ivZZx1b" width="3.531" height="23.844" x="22.688" y="4.597" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19048" stdDeviation=".5"/></filter><filter id="i98wUgc" width="19.938" height="4.225" x="6.031" y="2.035" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.407843 0 0 0 0 0.666667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19048"/></filter><radialGradient id="i9ISead" cx="0" cy="0" r="1" gradientTransform="matrix(-.65625 0 0 -3.17187 25.969 5.878)" gradientUnits="userSpaceOnUse"><stop class="ojzy8gu1i"/><stop offset="1" class="tg-jatb9a"/></radialGradient><radialGradient id="infnmxe" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.09375 -1.625 0 24.313 25.535)" gradientUnits="userSpaceOnUse"><stop class="pil3f0bpq"/><stop offset="1" class="iukqjcxpk"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:mobile-phone" /></template>
<style>
.avymp6bxa {
  width: 19.938px;
  height: 27.922px;
  x: 6.031px;
  y: 2.035px;
  rx: 2.6px;
}

.b462nc3ap {
  stop-color: var(--svg-color--6c6ebe, #6C6EBE);
}

.bxwl5sscl {
  stop-color: var(--svg-color--7277c8, #7277C8);
  stop-opacity: 0;
}

.d5perj03q {
  d: path("M9.203 9.08a.6.6 0 0 1 .6-.6h2.113a.6.6 0 0 1 .6.6v2.113a.6.6 0 0 1-.6.6H9.803a.6.6 0 0 1-.6-.6z");
}

.dbt-gfunk {
  fill: var(--svg-color--ff9544, #FF9544);
  d: path("M9.203 9.08a.6.6 0 0 1 .6-.6h2.113a.6.6 0 0 1 .6.6v2.113a.6.6 0 0 1-.6.6H9.803a.6.6 0 0 1-.6-.6z");
}

.dtkgx-g_z {
  stop-color: var(--svg-color--5e61ad, #5E61AD);
  stop-opacity: 0;
}

.ezvnbtbrk {
  d: path("M25.969 25.878v1.479a2.6 2.6 0 0 1-2.6 2.6H8.63a2.6 2.6 0 0 1-2.6-2.6v-1.479z");
}

.ft5dv1b6b {
  fill: none;
}

.h_fr6gbhe {
  stop-color: var(--svg-color--ff945c, #FF945C);
}

.i0k5pcbic {
  stop-color: var(--svg-color--6062b1, #6062B1);
}

.idv7f0bli {
  stop-color: var(--svg-color--412c4c, #412C4C);
  stop-opacity: 0;
}

.iukqjcxpk {
  stop-color: var(--svg-color--6b5094, #6B5094);
  stop-opacity: 0;
}

.jhar9mbzr {
  stop-color: var(--svg-color--76509e, #76509E);
}

.ke7h_0nog {
  stop-color: var(--svg-color--6062b1, #6062B1);
  stop-opacity: 0;
}

.l7_jii1ul {
  d: path("M9.203 20.799a.6.6 0 0 1 .6-.6h2.113a.6.6 0 0 1 .6.6v2.112a.6.6 0 0 1-.6.6H9.803a.6.6 0 0 1-.6-.6z");
}

.ldhx43b9p {
  fill: var(--svg-color--38c6ff, #38C6FF);
  d: path("M9.203 14.94a.6.6 0 0 1 .6-.6h2.113a.6.6 0 0 1 .6.6v2.112a.6.6 0 0 1-.6.6H9.803a.6.6 0 0 1-.6-.6z");
}

.mxpm9wbyq {
  stop-color: var(--svg-color--62326d, #62326D);
}

.n866a4bbg {
  stop-color: var(--svg-color--6e4693, #6E4693);
  stop-opacity: 0;
}

.nn3wdhnkh {
  stop-color: var(--svg-color--ff945c, #FF945C);
  stop-opacity: 0;
}

.o-u9ei9cl {
  stop-color: var(--svg-color--5e3d7f, #5E3D7F);
}

.ojzy8gu1i {
  stop-color: var(--svg-color--6c6fb4, #6C6FB4);
}

.p7igwxbie {
  stop-color: var(--svg-color--5e3d7f, #5E3D7F);
  stop-opacity: 0;
}

.pil3f0bpq {
  stop-color: var(--svg-color--6b5094, #6B5094);
}

.r6mkghbwh {
  fill: var(--svg-color--38c6ff, #38C6FF);
  d: path("M14.344 20.799a.6.6 0 0 1 .6-.6h2.112a.6.6 0 0 1 .6.6v2.112a.6.6 0 0 1-.6.6h-2.112a.6.6 0 0 1-.6-.6z");
}

.rfn3a3l7h {
  stop-color: var(--svg-color--555187, #555187);
}

.rkd_v8rho {
  d: path("M23.688 5.597h1.531v21.844h-1.531z");
}

.rm61x3idb {
  stop-color: var(--svg-color--674876, #674876);
}

.s0dxp3i6m {
  fill: var(--svg-color--ffec58, #FFEC58);
  d: path("M19.484 9.08a.6.6 0 0 1 .6-.6h2.113a.6.6 0 0 1 .6.6v2.113a.6.6 0 0 1-.6.6h-2.113a.6.6 0 0 1-.6-.6z");
}

.sx7s_nbpv {
  d: path("M19.484 14.94a.6.6 0 0 1 .6-.6h2.113a.6.6 0 0 1 .6.6v2.112a.6.6 0 0 1-.6.6h-2.113a.6.6 0 0 1-.6-.6z");
}

.tb9h17b9q {
  fill: var(--svg-color--ffec58, #FFEC58);
  d: path("M14.344 14.94a.6.6 0 0 1 .6-.6h2.112a.6.6 0 0 1 .6.6v2.112a.6.6 0 0 1-.6.6h-2.112a.6.6 0 0 1-.6-.6z");
}

.tg-jatb9a {
  stop-color: var(--svg-color--6c6fb4, #6C6FB4);
  stop-opacity: 0;
}

.u6z2bmfhr {
  stop-color: var(--svg-color--7277c8, #7277C8);
}

.veun7cb3s {
  stop-color: var(--svg-color--412c4c, #412C4C);
}

.x32mj1zzk {
  d: path("M25.969 6.16H6.03V4.635a2.6 2.6 0 0 1 2.6-2.6h14.74a2.6 2.6 0 0 1 2.6 2.6z");
}

.xsnl2cbnd {
  fill: var(--svg-color--38c6ff, #38C6FF);
  d: path("M14.344 9.08a.6.6 0 0 1 .6-.6h2.112a.6.6 0 0 1 .6.6v2.113a.6.6 0 0 1-.6.6h-2.112a.6.6 0 0 1-.6-.6z");
}

.xwfbhzbjg {
  fill: var(--svg-color--ff9544, #FF9544);
  d: path("M9.203 20.799a.6.6 0 0 1 .6-.6h2.113a.6.6 0 0 1 .6.6v2.112a.6.6 0 0 1-.6.6H9.803a.6.6 0 0 1-.6-.6z");
}

.ybphyjb-s {
  stop-color: var(--svg-color--434486, #434486);
}

.ymipoknoz {
  fill: var(--svg-color--ff9544, #FF9544);
  d: path("M19.484 14.94a.6.6 0 0 1 .6-.6h2.113a.6.6 0 0 1 .6.6v2.112a.6.6 0 0 1-.6.6h-2.113a.6.6 0 0 1-.6-.6z");
}

.yyc-7zm-w {
  fill: var(--svg-color--ffec58, #FFEC58);
  d: path("M19.484 20.799a.6.6 0 0 1 .6-.6h2.113a.6.6 0 0 1 .6.6v2.112a.6.6 0 0 1-.6.6h-2.113a.6.6 0 0 1-.6-.6z");
}

.z613fsbfq {
  stop-color: var(--svg-color--636ab6, #636AB6);
}

.zf56z5fxh {
  stop-color: var(--svg-color--6b4390, #6B4390);
}

.zfjq88vrv {
  stop-color: var(--svg-color--4f3d6c, #4F3D6C);
}

.zhmf_hb6m {
  stop-color: var(--svg-color--484b86, #484B86);
}

</style>
