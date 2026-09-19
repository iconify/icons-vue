<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ire0K7b)"><path fill="url(#idOX8Ne)" class="w3zyrevmb"/><path fill="url(#iMbCaJe)" class="w3zyrevmb"/><path fill="url(#iUU4vcc)" class="w3zyrevmb"/></g><g filter="url(#i4WegOd)"><path fill="url(#i0JYYFe)" class="sr_binb6j"/><path fill="url(#i2j0Gze)" class="sr_binb6j"/><path fill="url(#iOHAEsc)" class="sr_binb6j"/></g><g filter="url(#ifz6LXc)"><path fill="url(#i9KjLzb)" class="sn6bgujlv"/><path fill="url(#iQi9uqb)" class="sn6bgujlv"/><path fill="url(#iDWqZ2b)" class="sn6bgujlv"/></g><g filter="url(#iATo2Je)"><path fill="url(#iAH1w8c)" class="rl20futjn"/><path fill="url(#iapFu6b)" class="rl20futjn"/><path fill="url(#iDbewkc)" class="rl20futjn"/></g><g filter="url(#iKsc7fd)"><path fill="url(#ip5MnRd)" class="a2tpt009z"/><path fill="url(#iloNN1t)" class="a2tpt009z"/><path fill="url(#iMXJvOG)" class="a2tpt009z"/><path fill="url(#inf2a7Q)" class="a2tpt009z"/></g><g filter="url(#iEGmUOc)"><path class="m3rk8s9sq"/></g><g filter="url(#iJoS3Zb)"><path class="qwz5dtq4u"/></g><g filter="url(#iJzj2Pb)"><path class="jnfvec8dm"/></g><g filter="url(#iZTDFEq)"><path fill="url(#ilqlAkK)" class="mw26q37mx"/></g><path fill="url(#iLTkmcd)" class="mw26q37mx"/><g filter="url(#iBwAKpc)"><path fill="url(#iucXdre)" class="jd_st8kmv"/><path fill="url(#i9Y8xfb)" class="jd_st8kmv"/><path fill="url(#i8Xhsbc)" class="jd_st8kmv"/></g><g filter="url(#iDFHYRb)"><path fill="url(#in7QGFe)" class="b_aiflbgl"/><path fill="url(#iHajK4b)" class="b_aiflbgl"/><path fill="url(#io5sllc)" class="b_aiflbgl"/></g><g filter="url(#ifD1MFd)"><path fill="url(#irlrUSd)" class="oa0zuj1tg"/><path fill="url(#iicRtPe)" class="oa0zuj1tg"/><path fill="url(#iD4iURb)" class="oa0zuj1tg"/></g><defs><linearGradient id="idOX8Ne" x1="21.711" x2="30.398" y1="18.375" y2="18.375" gradientUnits="userSpaceOnUse"><stop class="htem4gq_o"/><stop offset="1" class="etlos9d4n"/></linearGradient><linearGradient id="iMbCaJe" x1="30.084" x2="29.436" y1="23.802" y2="23.802" gradientUnits="userSpaceOnUse"><stop offset=".286" class="c7ptkzbpw"/><stop offset="1" class="xvxr44s8n"/></linearGradient><linearGradient id="iUU4vcc" x1="15.086" x2="15.086" y1="29.906" y2="27.657" gradientUnits="userSpaceOnUse"><stop class="e0_9gxb1p"/><stop offset="1" class="e7y1mzb2t"/></linearGradient><linearGradient id="i0JYYFe" x1="6.039" x2="6.039" y1="8.984" y2="27.805" gradientUnits="userSpaceOnUse"><stop class="pfkaq23_t"/><stop offset=".571" class="e3a64guun"/></linearGradient><linearGradient id="i2j0Gze" x1="6.252" x2="6.252" y1="28.954" y2="27.62" gradientUnits="userSpaceOnUse"><stop offset=".083" class="qln2-rwjd"/><stop offset="1" class="ywjar6iuu"/></linearGradient><linearGradient id="i9KjLzb" x1="12.685" x2="12.685" y1="8.984" y2="27.805" gradientUnits="userSpaceOnUse"><stop class="pfkaq23_t"/><stop offset=".571" class="e3a64guun"/></linearGradient><linearGradient id="iQi9uqb" x1="12.898" x2="12.898" y1="28.954" y2="27.62" gradientUnits="userSpaceOnUse"><stop offset=".083" class="qln2-rwjd"/><stop offset="1" class="ywjar6iuu"/></linearGradient><linearGradient id="iAH1w8c" x1="19.331" x2="19.331" y1="8.984" y2="27.805" gradientUnits="userSpaceOnUse"><stop class="pfkaq23_t"/><stop offset=".571" class="e3a64guun"/></linearGradient><linearGradient id="iapFu6b" x1="19.544" x2="19.544" y1="28.954" y2="27.62" gradientUnits="userSpaceOnUse"><stop offset=".083" class="qln2-rwjd"/><stop offset="1" class="ywjar6iuu"/></linearGradient><linearGradient id="ip5MnRd" x1="25.977" x2="25.977" y1="8.984" y2="27.805" gradientUnits="userSpaceOnUse"><stop class="pfkaq23_t"/><stop offset=".571" class="e3a64guun"/></linearGradient><linearGradient id="iMXJvOG" x1="29.417" x2="27.787" y1="23.951" y2="23.951" gradientUnits="userSpaceOnUse"><stop class="ffmeisu_c"/><stop offset="1" class="upluejbfs"/></linearGradient><linearGradient id="inf2a7Q" x1="26.19" x2="26.19" y1="28.954" y2="27.62" gradientUnits="userSpaceOnUse"><stop offset=".083" class="qln2-rwjd"/><stop offset="1" class="ywjar6iuu"/></linearGradient><linearGradient id="ilqlAkK" x1="16" x2="16" y1="2.602" y2="8.984" gradientUnits="userSpaceOnUse"><stop class="gl1063iwt"/><stop offset="1" class="xsu38db8g"/></linearGradient><linearGradient id="iLTkmcd" x1="19.707" x2="19.707" y1="8.984" y2="8.504" gradientUnits="userSpaceOnUse"><stop class="ne4lhab9k"/><stop offset="1" class="urwhw_fuy"/></linearGradient><linearGradient id="iucXdre" x1="9.445" x2="9.445" y1="8.984" y2="21.594" gradientUnits="userSpaceOnUse"><stop offset=".334" class="flvl09qdd"/><stop offset="1" class="j0w2jl33w"/></linearGradient><linearGradient id="i9Y8xfb" x1="11.404" x2="10.644" y1="18.873" y2="18.873" gradientUnits="userSpaceOnUse"><stop offset=".488" class="ybchdtbwu"/><stop offset="1" class="dt1ucgsrl"/></linearGradient><linearGradient id="i8Xhsbc" x1="9.445" x2="9.445" y1="8.791" y2="9.866" gradientUnits="userSpaceOnUse"><stop offset=".172" class="hx6as-bar"/><stop offset="1" class="h952uiqmu"/></linearGradient><linearGradient id="in7QGFe" x1="16" x2="16" y1="8.984" y2="21.594" gradientUnits="userSpaceOnUse"><stop offset=".334" class="flvl09qdd"/><stop offset="1" class="j0w2jl33w"/></linearGradient><linearGradient id="iHajK4b" x1="17.959" x2="17.199" y1="18.873" y2="18.873" gradientUnits="userSpaceOnUse"><stop offset=".488" class="ybchdtbwu"/><stop offset="1" class="dt1ucgsrl"/></linearGradient><linearGradient id="io5sllc" x1="16" x2="16" y1="8.791" y2="9.866" gradientUnits="userSpaceOnUse"><stop offset=".172" class="hx6as-bar"/><stop offset="1" class="h952uiqmu"/></linearGradient><linearGradient id="irlrUSd" x1="22.555" x2="22.555" y1="8.984" y2="21.594" gradientUnits="userSpaceOnUse"><stop offset=".334" class="flvl09qdd"/><stop offset="1" class="j0w2jl33w"/></linearGradient><linearGradient id="iicRtPe" x1="24.514" x2="23.754" y1="18.873" y2="18.873" gradientUnits="userSpaceOnUse"><stop offset=".488" class="ybchdtbwu"/><stop offset="1" class="dt1ucgsrl"/></linearGradient><linearGradient id="iD4iURb" x1="22.555" x2="22.555" y1="8.791" y2="9.866" gradientUnits="userSpaceOnUse"><stop offset=".172" class="hx6as-bar"/><stop offset="1" class="h952uiqmu"/></linearGradient><filter id="ire0K7b" width="27.959" height="21.022" x="2.07" y="8.884" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 0.552941 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18699"/></filter><filter id="i4WegOd" width="6.169" height="19.766" x="3.055" y="8.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.654902 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18699"/></filter><filter id="ifz6LXc" width="6.169" height="19.766" x="9.701" y="8.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.654902 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18699"/></filter><filter id="iATo2Je" width="6.169" height="19.766" x="16.346" y="8.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.654902 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18699"/></filter><filter id="iKsc7fd" width="6.169" height="19.766" x="22.992" y="8.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.654902 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18699"/></filter><filter id="iEGmUOc" width="4.787" height="13.761" x="6.089" y="8.234" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18699" stdDeviation=".375"/></filter><filter id="iJoS3Zb" width="4.787" height="13.761" x="12.797" y="8.234" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18699" stdDeviation=".375"/></filter><filter id="iJzj2Pb" width="4.787" height="13.761" x="19.506" y="8.234" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_18699" stdDeviation=".375"/></filter><filter id="iZTDFEq" width="28.609" height="7.156" x="1.57" y="2.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.4 0 0 0 0 0.360784 0 0 0 0 0.447059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18699"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.239216 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_18699" result="effect2_innerShadow_18_18699"/></filter><filter id="iBwAKpc" width="4.006" height="12.859" x="7.617" y="8.734" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".35" dy="-.25"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.188235 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18699"/></filter><filter id="iDFHYRb" width="4.006" height="12.859" x="14.172" y="8.734" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".35" dy="-.25"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.188235 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18699"/></filter><filter id="ifD1MFd" width="4.006" height="12.859" x="20.727" y="8.734" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".35" dy="-.25"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.188235 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18699"/></filter><radialGradient id="iOHAEsc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.48474 0 0 -14.2264 9.591 16.723)" gradientUnits="userSpaceOnUse"><stop class="z5s0yzqsp"/><stop offset="1" class="y8va1peun"/></radialGradient><radialGradient id="iDWqZ2b" cx="0" cy="0" r="1" gradientTransform="matrix(-4.48474 0 0 -14.2264 16.237 16.723)" gradientUnits="userSpaceOnUse"><stop class="z5s0yzqsp"/><stop offset="1" class="y8va1peun"/></radialGradient><radialGradient id="iDbewkc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.48474 0 0 -14.2264 22.883 16.723)" gradientUnits="userSpaceOnUse"><stop class="z5s0yzqsp"/><stop offset="1" class="y8va1peun"/></radialGradient><radialGradient id="iloNN1t" cx="0" cy="0" r="1" gradientTransform="matrix(-4.48474 0 0 -14.2264 29.529 16.723)" gradientUnits="userSpaceOnUse"><stop class="z5s0yzqsp"/><stop offset="1" class="y8va1peun"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:musical-keyboard" /></template>
<style>
.a2tpt009z {
  d: path("M22.992 8.984h5.969V27.75a1 1 0 0 1-1 1h-3.969a1 1 0 0 1-1-1z");
}

.b_aiflbgl {
  d: path("M14.172 8.984h3.656v11.61a1 1 0 0 1-1 1h-1.656a1 1 0 0 1-1-1z");
}

.c7ptkzbpw {
  stop-color: var(--svg-color--cac7ce, #CAC7CE);
}

.dt1ucgsrl {
  stop-color: var(--svg-color--5a4d68, #5A4D68);
  stop-opacity: 0;
}

.e0_9gxb1p {
  stop-color: var(--svg-color--a088b8, #A088B8);
}

.e3a64guun {
  stop-color: var(--svg-color--e3d6f2, #E3D6F2);
}

.e7y1mzb2t {
  stop-color: var(--svg-color--a092b0, #A092B0);
  stop-opacity: 0;
}

.etlos9d4n {
  stop-color: var(--svg-color--c3bfc7, #C3BFC7);
}

.ffmeisu_c {
  stop-color: var(--svg-color--f5effd, #F5EFFD);
}

.flvl09qdd {
  stop-color: var(--svg-color--58426c, #58426C);
}

.ft5dv1b6b {
  fill: none;
}

.gl1063iwt {
  stop-color: var(--svg-color--473856, #473856);
}

.h952uiqmu {
  stop-color: var(--svg-color--5a436e, #5A436E);
  stop-opacity: 0;
}

.htem4gq_o {
  stop-color: var(--svg-color--948f99, #948F99);
}

.hx6as-bar {
  stop-color: var(--svg-color--42285c, #42285C);
}

.j0w2jl33w {
  stop-color: var(--svg-color--443c4b, #443C4B);
}

.jd_st8kmv {
  d: path("M7.617 8.984h3.656v11.61a1 1 0 0 1-1 1H8.617a1 1 0 0 1-1-1z");
}

.jnfvec8dm {
  fill: var(--svg-color--c8bbd7, #C8BBD7);
  d: path("M20.256 8.984h3.287v11.289c0 .537-.403.972-.9.972h-1.488c-.497 0-.899-.435-.899-.972z");
}

.m3rk8s9sq {
  fill: var(--svg-color--c8bbd7, #C8BBD7);
  d: path("M6.839 8.984h3.287v11.289c0 .537-.403.972-.9.972H7.739c-.497 0-.9-.435-.9-.972z");
}

.mw26q37mx {
  d: path("M2.07 3.078a1 1 0 0 1 1-1h25.86a1 1 0 0 1 1 1v5.906H2.07z");
}

.ne4lhab9k {
  stop-color: var(--svg-color--372646, #372646);
}

.oa0zuj1tg {
  d: path("M20.727 8.984h3.656v11.61a1 1 0 0 1-1 1h-1.656a1 1 0 0 1-1-1z");
}

.pfkaq23_t {
  stop-color: var(--svg-color--c3b8cf, #C3B8CF);
}

.qln2-rwjd {
  stop-color: var(--svg-color--b9a1d1, #B9A1D1);
}

.qwz5dtq4u {
  fill: var(--svg-color--c8bbd7, #C8BBD7);
  d: path("M13.547 8.984h3.287v11.289c0 .537-.402.972-.899.972h-1.489c-.496 0-.899-.435-.899-.972z");
}

.rl20futjn {
  d: path("M16.346 8.984h5.97V27.75a1 1 0 0 1-1 1h-3.97a1 1 0 0 1-1-1z");
}

.sn6bgujlv {
  d: path("M9.7 8.984h5.97V27.75a1 1 0 0 1-1 1H10.7a1 1 0 0 1-1-1z");
}

.sr_binb6j {
  d: path("M3.055 8.984h5.968V27.75a1 1 0 0 1-1 1H4.055a1 1 0 0 1-1-1z");
}

.upluejbfs {
  stop-color: var(--svg-color--e2d5f0, #E2D5F0);
  stop-opacity: 0;
}

.urwhw_fuy {
  stop-color: var(--svg-color--372646, #372646);
  stop-opacity: 0;
}

.w3zyrevmb {
  d: path("M2.07 28.906a1 1 0 0 0 1 1h25.86a1 1 0 0 0 1-1V8.984H2.07z");
}

.xsu38db8g {
  stop-color: var(--svg-color--41374b, #41374B);
}

.xvxr44s8n {
  stop-color: var(--svg-color--cac7ce, #CAC7CE);
  stop-opacity: 0;
}

.y8va1peun {
  stop-color: var(--svg-color--ece3f6, #ECE3F6);
  stop-opacity: 0;
}

.ybchdtbwu {
  stop-color: var(--svg-color--5a4d68, #5A4D68);
}

.ywjar6iuu {
  stop-color: var(--svg-color--e1d1f2, #E1D1F2);
  stop-opacity: 0;
}

.z5s0yzqsp {
  stop-color: var(--svg-color--ece3f6, #ECE3F6);
}

</style>
