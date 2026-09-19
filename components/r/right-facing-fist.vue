<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iUIRazd)" transform="matrix(-1 0 0 1 24.164 15.788)" class="njm0dpb1e"/><path fill="url(#inzHADe)" transform="matrix(-1 0 0 1 24.164 15.788)" class="njm0dpb1e"/><g filter="url(#i2KWIkc)"><path fill="url(#iXoaA4b)" class="m71vu6bpu"/></g><g filter="url(#iWkkYxb)"><path fill="url(#iPvaK8b)" clip-rule="evenodd" class="d9if-8h7l"/><path fill="url(#i7zRuJb)" clip-rule="evenodd" class="d9if-8h7l"/></g><path fill="url(#ir8MdGj)" class="pfz0k1gnw"/><path fill="url(#iDyNtvd)" class="pfz0k1gnw"/><path fill="url(#ir8MdGj)" class="pbm7cxbby"/><path fill="url(#iDyNtvd)" class="pbm7cxbby"/><g filter="url(#iSzxsEb)"><path stroke="url(#iFCSRTd)" class="m-rw2kg9g"/></g><g filter="url(#iOm2u8d)"><path stroke="url(#is7pCce)" class="gbrplqq8w"/></g><g filter="url(#i37rFPc)"><path fill="url(#i1DShwb)" class="rns7vo48j"/></g><defs><radialGradient id="iUIRazd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.13776 -2.69583 2.11672 -3.2489 6.783 4.15)" gradientUnits="userSpaceOnUse"><stop class="u56b295zl"/><stop offset="1" class="gfwxr4bdd"/></radialGradient><radialGradient id="inzHADe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .78125 -4.67188 0 6.14 1.281)" gradientUnits="userSpaceOnUse"><stop class="p7pu2tlgw"/><stop offset="1" class="z2ap9e_re"/></radialGradient><radialGradient id="iXoaA4b" cx="0" cy="0" r="1" gradientTransform="matrix(3.34023 1.05914 -1.73617 5.4754 19.024 20.546)" gradientUnits="userSpaceOnUse"><stop class="i3i6am4qn"/><stop offset="1" class="vxlss6lph"/></radialGradient><radialGradient id="iPvaK8b" cx="0" cy="0" r="1" gradientTransform="matrix(-26.38668 9.81731 -15.15853 -40.74266 28.441 12.488)" gradientUnits="userSpaceOnUse"><stop class="itt9z7bbf"/><stop offset="1" class="p2w580b5m"/></radialGradient><radialGradient id="i7zRuJb" cx="0" cy="0" r="1" gradientTransform="rotate(164.932 8.88 15.261)scale(2.8424 3.59605)" gradientUnits="userSpaceOnUse"><stop class="fj0llis_o"/><stop offset="1" class="t6n1lgw1y"/></radialGradient><radialGradient id="ir8MdGj" cx="0" cy="0" r="1" gradientTransform="matrix(2.15167 0 0 3.16327 18.597 22.908)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="fggepab1c"/><stop offset="1" class="xrex5jqbs"/></radialGradient><linearGradient id="iDyNtvd" x1="22.769" x2="22.769" y1="24.678" y2="26.32" gradientUnits="userSpaceOnUse"><stop class="wlzu37ymd"/><stop offset="1" class="y371o2e7j"/></linearGradient><linearGradient id="iFCSRTd" x1="18.728" x2="19.442" y1="25.614" y2="15.359" gradientUnits="userSpaceOnUse"><stop class="st3dxnbfu"/><stop offset="1" class="jom_o-liu"/></linearGradient><linearGradient id="is7pCce" x1="17.146" x2="12.737" y1="14.546" y2="17.727" gradientUnits="userSpaceOnUse"><stop class="st3dxnbfu"/><stop offset="1" class="jom_o-liu"/></linearGradient><linearGradient id="i1DShwb" x1="23.216" x2="30.394" y1="16.552" y2="18.61" gradientUnits="userSpaceOnUse"><stop class="r5k0wkurm"/><stop offset="1" class="y_-y85jzu"/></linearGradient><filter id="i2KWIkc" width="8.486" height="7.397" x="16.653" y="16.898" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.7875 0 0 0 0 0.278313 0 0 0 0 0.0328125 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3313"/></filter><filter id="iWkkYxb" width="28.641" height="22.295" x="2.055" y="7.71" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.25"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.933333 0 0 0 0 0.486275 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3313"/></filter><filter id="iSzxsEb" width="13.066" height="17.613" x="10.219" y="11.835" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3313" stdDeviation="1.25"/></filter><filter id="iOm2u8d" width="9.696" height="11.342" x="10.37" y="11.772" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3313" stdDeviation="1.25"/></filter><filter id="i37rFPc" width="8.381" height="12.34" x="21.585" y="10.382" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3313" stdDeviation="1"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:right-facing-fist" /></template>
<style>
.d9if-8h7l {
  fill-rule: evenodd;
  d: path("M24.445 7.96a5.5 5.5 0 0 1 5.5 5.5v5.625h-.004v.398c.01.724-.205 2.58-1.043 3.805c-1.046 1.531-2.859 2.75-4.64 2.75h-2.104c.075.28.102.573.134.921l.001.017c0 1.023-.437 2.562-2.64 3c-.985.148-2-.274-2.829-.93a95 95 0 0 1-1.961-1.64c-.27-.229-.515-.437-.703-.594l-.129-.11c-.357-.31-.862-.747-1.472-.789c-.835-.058-2.42-.38-4.352-2.219c-.78-.742-1.4-1.748-1.755-2.322a9 9 0 0 0-.221-.35q-.08-.116-.138-.211c-.235-.375-.328-.523-1.331-.523l.007-.008h-.71a2 2 0 0 1-2-2V9.96a2 2 0 0 1 2-2zm-7.302 12.3c-.273-.474-.686-1.272-.87-1.917c-.273-.961.24-1.071.485-1.117c.37-.07.942-.062 1.536-.053c.201.003.405.006.604.006q.357 0 .758.005c1.227.012 2.667.026 3.399-.193c.133.065.398.317.398.805v.1c.002.582.004 1.208-.476 1.533c-.178.12-.531.147-.965.18c-.487.036-1.075.08-1.631.273h-.002l-.062.023c-.245.09-.482.21-.701.373a3.33 3.33 0 0 0-1.228 1.743c-.702-.82-1.131-1.54-1.228-1.752z");
}

.fggepab1c {
  stop-color: var(--svg-color--cf6e1c, #CF6E1C);
}

.fj0llis_o {
  stop-color: var(--svg-color--ffea49, #FFEA49);
}

.ft5dv1b6b {
  fill: none;
}

.gbrplqq8w {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.565 15.285c-.492-.07-1.647.085-2.322 1.267c-.676 1.182-.282 2.533 0 3.061");
}

.gfwxr4bdd {
  stop-color: var(--svg-color--aa3a0e, #AA3A0E);
}

.i3i6am4qn {
  stop-color: var(--svg-color--e67e16, #E67E16);
}

.itt9z7bbf {
  stop-color: var(--svg-color--ffe848, #FFE848);
}

.jom_o-liu {
  stop-color: var(--svg-color--ffea47, #FFEA47);
  stop-opacity: 0;
}

.m-rw2kg9g {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13.72 15.335c-.05 1.769 1.684 7.867 6.065 10.612");
}

.m71vu6bpu {
  d: path("M22.308 18.721a4.8 4.8 0 0 0-.066-1.823h2.797v7.296h-6.703c-1.078 0-1.898-1.609-1.633-2.843c.266-1.235 1.432-2.277 2.711-2.203c.963.055 1.893.016 2.524-.074a.43.43 0 0 0 .37-.353");
}

.njm0dpb1e {
  d: path("M0 0h9.563v7.109H0z");
}

.p2w580b5m {
  stop-color: var(--svg-color--e69728, #E69728);
}

.p7pu2tlgw {
  stop-color: var(--svg-color--8d2602, #8D2602);
}

.pbm7cxbby {
  d: path("m22.939 17.023l-.036.008l.011-.008z");
}

.pfz0k1gnw {
  d: path("M29.945 17.023v2.062h-.004v.398c.01.724-.205 2.58-1.043 3.805c-.818 1.197-2.105 2.204-3.479 2.586c-.372.1-.75.155-1.126.155h-2.141c-.082-.293-.328-.887-.968-1.465a14 14 0 0 0-.62-.531c-.692-.578-1.642-1.268-2.181-2.007c.141-.47.509-1.231 1.233-1.747a2.8 2.8 0 0 1 .763-.397h.002c.556-.193 1.144-.237 1.631-.274c.434-.032.787-.059.965-.18c.48-.324.478-.95.476-1.532v-.1c0-.43-.206-.676-.346-.773z");
}

.r5k0wkurm {
  stop-color: var(--svg-color--f69d30, #F69D30);
}

.rns7vo48j {
  d: path("m25.697 12.382l-2.112 3.932c1.135 1.373.599 3.563.264 4.408h4.117v-8.34z");
}

.st3dxnbfu {
  stop-color: var(--svg-color--ffea47, #FFEA47);
}

.t6n1lgw1y {
  stop-color: var(--svg-color--ffea49, #FFEA49);
  stop-opacity: 0;
}

.u56b295zl {
  stop-color: var(--svg-color--d96127, #D96127);
}

.vxlss6lph {
  stop-color: var(--svg-color--af4204, #AF4204);
}

.wlzu37ymd {
  stop-color: var(--svg-color--eb755c, #EB755C);
  stop-opacity: 0;
}

.xrex5jqbs {
  stop-color: var(--svg-color--cf6e1c, #CF6E1C);
  stop-opacity: 0;
}

.y_-y85jzu {
  stop-color: var(--svg-color--f69d30, #F69D30);
  stop-opacity: 0;
}

.y371o2e7j {
  stop-color: var(--svg-color--eb755c, #EB755C);
}

.z2ap9e_re {
  stop-color: var(--svg-color--8d2602, #8D2602);
  stop-opacity: 0;
}

</style>
