<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iYa6qVb)"><path fill="url(#iBh7H5d)" class="rw1c-c3fu"/></g><path fill="url(#i1h888c)" class="rw1c-c3fu"/><g filter="url(#iIUAZ0c)"><path fill="url(#ij5XaKc)" class="qx1gswbyf"/></g><g filter="url(#iIUAZ0c)"><path fill="url(#ij5XaKc)" class="qx1gswbyf"/></g><g filter="url(#iNahVIB)"><path fill="url(#ijmogSu)" class="pj8jxv_es"/></g><path fill="url(#iNlwcbe)" class="pj8jxv_es"/><path fill="url(#ihFhfnd)" class="pj8jxv_es"/><circle fill="url(#irrhSIe)" class="bl098bc2e"/><circle fill="url(#iEqiJVb)" class="bl098bc2e"/><circle fill="url(#iJWJLmc)" class="bl098bc2e"/><circle fill="url(#idbZYVb)" class="bl098bc2e"/><circle fill="url(#i6ZL0tb)" class="bl098bc2e"/><circle fill="url(#iXVMhYd)" class="rgp0l8cpf"/><circle fill="url(#inFgw8c)" class="rgp0l8cpf"/><circle fill="url(#i8y2VFP)" class="rgp0l8cpf"/><circle fill="url(#iXtNo5c)" class="rgp0l8cpf"/><circle fill="url(#iWPvJXU)" class="rgp0l8cpf"/><circle fill="url(#ikJUWWo)" class="rdfkyl22w"/><circle fill="url(#i6AI1hc)" class="rdfkyl22w"/><circle fill="url(#iwCAUle)" class="rdfkyl22w"/><circle fill="url(#i9feRUd)" class="rdfkyl22w"/><defs><radialGradient id="i1h888c" cx="0" cy="0" r="1" gradientTransform="matrix(.57205 -.63123 1.76101 1.59592 13.615 22.965)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="avtpu4-jo"/><stop offset="1" class="drg4z-bbo"/></radialGradient><radialGradient id="ihFhfnd" cx="0" cy="0" r="1" gradientTransform="matrix(.65095 -.72 1.72774 1.56206 8.585 13.793)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="avtpu4-jo"/><stop offset="1" class="drg4z-bbo"/></radialGradient><radialGradient id="irrhSIe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.85503 6.67567 0 10.941 29.468)" gradientUnits="userSpaceOnUse"><stop class="tu_1s4p_y"/><stop offset="1" class="hmbeijb1u"/></radialGradient><radialGradient id="iEqiJVb" cx="0" cy="0" r="1" gradientTransform="rotate(130.389 .937 15.26)scale(3.95442)" gradientUnits="userSpaceOnUse"><stop class="ar986sb2l"/><stop offset="1" class="c1-4m7bfx"/></radialGradient><radialGradient id="iJWJLmc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.47337 -1.16883 1.20169 -6.65537 12.537 25.961)" gradientUnits="userSpaceOnUse"><stop offset=".619" class="xms4xuz3x"/><stop offset="1" class="s213z3h9t"/></radialGradient><radialGradient id="idbZYVb" cx="0" cy="0" r="1" gradientTransform="matrix(5.89121 0 0 7.83031 9.971 25.626)" gradientUnits="userSpaceOnUse"><stop offset=".796" class="h180r4ehu"/><stop offset=".955" class="q1wrqn_ko"/></radialGradient><radialGradient id="i6ZL0tb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.85749 -4.92437 0 10.941 25.216)" gradientUnits="userSpaceOnUse"><stop offset=".881" class="diepjho0n"/><stop offset="1" class="kq98n1buf"/></radialGradient><radialGradient id="iXVMhYd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.78181 6.57498 0 6.062 20.309)" gradientUnits="userSpaceOnUse"><stop class="tu_1s4p_y"/><stop offset="1" class="hmbeijb1u"/></radialGradient><radialGradient id="inFgw8c" cx="0" cy="0" r="1" gradientTransform="rotate(130.389 .58 9.582)scale(3.89478)" gradientUnits="userSpaceOnUse"><stop class="ar986sb2l"/><stop offset="1" class="c1-4m7bfx"/></radialGradient><radialGradient id="i8y2VFP" cx="0" cy="0" r="1" gradientTransform="rotate(-169.765 4.572 8.086)scale(6.47883 6.66098)" gradientUnits="userSpaceOnUse"><stop offset=".619" class="xms4xuz3x"/><stop offset="1" class="s213z3h9t"/></radialGradient><radialGradient id="iXtNo5c" cx="0" cy="0" r="1" gradientTransform="matrix(5.80236 0 0 7.71222 5.107 16.525)" gradientUnits="userSpaceOnUse"><stop offset=".796" class="h180r4ehu"/><stop offset=".955" class="q1wrqn_ko"/></radialGradient><radialGradient id="iWPvJXU" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.78423 -4.8501 0 6.062 16.121)" gradientUnits="userSpaceOnUse"><stop offset=".881" class="diepjho0n"/><stop offset="1" class="kq98n1buf"/></radialGradient><radialGradient id="ikJUWWo" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.85503 6.67567 0 21.004 25.263)" gradientUnits="userSpaceOnUse"><stop class="tu_1s4p_y"/><stop offset="1" class="bofu9mg9y"/></radialGradient><radialGradient id="i6AI1hc" cx="0" cy="0" r="1" gradientTransform="rotate(130.389 6.94 15.482)scale(3.95442)" gradientUnits="userSpaceOnUse"><stop class="ar986sb2l"/><stop offset="1" class="c1-4m7bfx"/></radialGradient><radialGradient id="iwCAUle" cx="0" cy="0" r="1" gradientTransform="matrix(5.89121 0 0 7.83031 20.034 21.422)" gradientUnits="userSpaceOnUse"><stop offset=".796" class="h180r4ehu"/><stop offset=".955" class="q1wrqn_ko"/></radialGradient><radialGradient id="i9feRUd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.85749 -4.92437 0 21.004 21.011)" gradientUnits="userSpaceOnUse"><stop offset=".881" class="diepjho0n"/><stop offset="1" class="kq98n1buf"/></radialGradient><linearGradient id="iBh7H5d" x1="16" x2="16" y1="14.475" y2="25.375" gradientUnits="userSpaceOnUse"><stop class="wja7ugbho"/><stop offset="1" class="aten6qr0b"/></linearGradient><linearGradient id="ij5XaKc" x1="26.063" x2="26.063" y1="10.201" y2="21.102" gradientUnits="userSpaceOnUse"><stop class="wja7ugbho"/><stop offset="1" class="aten6qr0b"/></linearGradient><linearGradient id="ijmogSu" x1="11.063" x2="11.063" y1="7.146" y2="16.625" gradientUnits="userSpaceOnUse"><stop class="wja7ugbho"/><stop offset="1" class="aten6qr0b"/></linearGradient><linearGradient id="iNlwcbe" x1="7.332" x2="7.835" y1="10.893" y2="10.893" gradientUnits="userSpaceOnUse"><stop class="vaxvq0aqj"/><stop offset="1" class="ej0vgzb3k"/></linearGradient><filter id="iYa6qVb" width="8.242" height="16.302" x="11.979" y="9.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy=".6"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.211765 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18069"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.317647 0 0 0 0 0.298039 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_18069" result="effect2_innerShadow_18_18069"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.6"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.129412 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_18069" result="effect3_innerShadow_18_18069"/></filter><filter id="iIUAZ0c" width="8.242" height="16.302" x="22.041" y="5.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy=".6"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.211765 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18069"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.317647 0 0 0 0 0.298039 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_18069" result="effect2_innerShadow_18_18069"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.6"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.129412 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_18069" result="effect3_innerShadow_18_18069"/></filter><filter id="iNahVIB" width="8.242" height="14.333" x="7.041" y="2.892" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy=".6"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.211765 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_18069"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.317647 0 0 0 0 0.298039 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_18069" result="effect2_innerShadow_18_18069"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.6"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.129412 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_18069" result="effect3_innerShadow_18_18069"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:musical-notes" /></template>
<style>
.ar986sb2l {
  stop-color: var(--svg-color--5a585c, #5A585C);
}

.aten6qr0b {
  stop-color: var(--svg-color--433d4a, #433D4A);
}

.avtpu4-jo {
  stop-color: var(--svg-color--545058, #545058);
}

.bl098bc2e {
  cx: 10.941px;
  cy: 25.626px;
  r: 4.273px;
}

.bofu9mg9y {
  stop-color: var(--svg-color--2d2931, #2D2931);
}

.c1-4m7bfx {
  stop-color: var(--svg-color--5a585c, #5A585C);
  stop-opacity: 0;
}

.diepjho0n {
  stop-color: var(--svg-color--64487c, #64487C);
  stop-opacity: 0;
}

.drg4z-bbo {
  stop-color: var(--svg-color--545058, #545058);
  stop-opacity: 0;
}

.ej0vgzb3k {
  stop-color: var(--svg-color--5c5a5f, #5C5A5F);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.h180r4ehu {
  stop-color: var(--svg-color--575658, #575658);
  stop-opacity: 0;
}

.hmbeijb1u {
  stop-color: var(--svg-color--302c33, #302C33);
}

.kq98n1buf {
  stop-color: var(--svg-color--64487c, #64487C);
}

.pj8jxv_es {
  d: path("M14.235 7.476a.5.5 0 0 0 .449-.497V3.992a.5.5 0 0 0-.552-.497l-5.794.6a1 1 0 0 0-.897.994v11.536h2.836V8.562a.75.75 0 0 1 .673-.746z");
}

.q1wrqn_ko {
  stop-color: var(--svg-color--575658, #575658);
}

.qx1gswbyf {
  d: path("M29.235 9.984a.5.5 0 0 0 .449-.497V6.5a.5.5 0 0 0-.552-.498l-5.794.6a1 1 0 0 0-.897.995v13.505h2.836V11.07a.75.75 0 0 1 .673-.746z");
}

.rdfkyl22w {
  cx: 21.004px;
  cy: 21.422px;
  r: 4.273px;
}

.rgp0l8cpf {
  cx: 6.062px;
  cy: 16.525px;
  r: 4.209px;
}

.rw1c-c3fu {
  d: path("M19.173 14.257a.5.5 0 0 0 .448-.497v-2.987a.5.5 0 0 0-.551-.497l-5.794.6a1 1 0 0 0-.897.995v13.504h2.836V15.344a.75.75 0 0 1 .673-.746z");
}

.s213z3h9t {
  stop-color: var(--svg-color--828282, #828282);
}

.tu_1s4p_y {
  stop-color: var(--svg-color--442b58, #442B58);
}

.vaxvq0aqj {
  stop-color: var(--svg-color--5c5a5f, #5C5A5F);
}

.wja7ugbho {
  stop-color: var(--svg-color--473b53, #473B53);
}

.xms4xuz3x {
  stop-color: var(--svg-color--5c5c5c, #5C5C5C);
  stop-opacity: 0;
}

</style>
