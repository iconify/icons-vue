<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iWUKHMd)" class="f9ubyz98e"/><path fill="url(#iMb3kRc)" class="f9ubyz98e"/><path fill="url(#inJjild)" class="f9ubyz98e"/><path fill="url(#igdGaGc)" class="n1_vkrbga"/><path fill="url(#ikAaZ8c)" class="n1_vkrbga"/><path fill="url(#i0aJkvc)" class="n1_vkrbga"/><g filter="url(#iVuCHMe)"><path fill="url(#imUPqjb)" class="tkjhxlr2i"/><path fill="url(#iDsTLcc)" class="tkjhxlr2i"/><path fill="url(#iqUhHxe)" class="tkjhxlr2i"/><path fill="url(#iwfepwd)" class="tkjhxlr2i"/><path fill="url(#iNWaevd)" class="tkjhxlr2i"/><path fill="url(#iOghaSc)" class="tkjhxlr2i"/></g><g filter="url(#iiPT4ec)"><path fill="url(#iQS2bFc)" class="ts-bd-l-j"/></g><path class="h1sfekdku"/><path fill="url(#i3tWR3c)" class="h-zmh0bzc"/><path fill="url(#i53xM6d)" class="h-zmh0bzc"/><g filter="url(#iOzhPEb)"><path fill="url(#i7Ykmov)" class="t_6sasbpq"/></g><g filter="url(#iYQLo1c)"><path fill="url(#iOsnTDs)" class="vktua4bec"/></g><g filter="url(#iIqggqb)"><path fill="url(#iqZmQxn)" class="ga340ejbl"/></g><defs><radialGradient id="iWUKHMd" cx="0" cy="0" r="1" gradientTransform="matrix(-.41237 10.75 -8.00176 -.30695 13.908 19.385)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="kbfwc1ats"/><stop offset="1" class="lktp6_b5x"/></radialGradient><radialGradient id="iMb3kRc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3125 5.625 -2.4855 -.57995 14.033 27.323)" gradientUnits="userSpaceOnUse"><stop offset=".468" class="ueqw3jbqm"/><stop offset="1" class="ks-esmm5e"/></radialGradient><radialGradient id="inJjild" cx="0" cy="0" r="1" gradientTransform="matrix(-1.50001 6.78125 -2.2996 -.50867 10.408 18.135)" gradientUnits="userSpaceOnUse"><stop class="nt69427qa"/><stop offset="1" class="gtmuv2-cy"/></radialGradient><radialGradient id="igdGaGc" cx="0" cy="0" r="1" gradientTransform="rotate(140.864 11.851 6.718)scale(8.21893 7.91903)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="xstzhi6_p"/><stop offset=".926" class="pi-28hb3o"/></radialGradient><radialGradient id="ikAaZ8c" cx="0" cy="0" r="1" gradientTransform="rotate(-69.102 18.106 -6.167)scale(5.51932 10.3111)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="mqy-2rbyy"/><stop offset="1" class="iw186m8pp"/></radialGradient><radialGradient id="i0aJkvc" cx="0" cy="0" r="1" gradientTransform="matrix(6.93752 -8.71878 8.50493 6.76735 18.69 11.167)" gradientUnits="userSpaceOnUse"><stop offset=".793" class="bon68opzd"/><stop offset="1" class="v3zx2gi2s"/></radialGradient><radialGradient id="imUPqjb" cx="0" cy="0" r="1" gradientTransform="rotate(128.104 9.623 13.308)scale(15.091 16.1232)" gradientUnits="userSpaceOnUse"><stop class="fk-o55byp"/><stop offset="1" class="bglzk7boc"/></radialGradient><radialGradient id="iDsTLcc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.21874 -2.10067 1.30009 -3.22984 11.877 10.292)" gradientUnits="userSpaceOnUse"><stop class="u5dcf2bbi"/><stop offset="1" class="psiel2wbx"/></radialGradient><radialGradient id="iqUhHxe" cx="0" cy="0" r="1" gradientTransform="rotate(-153.688 7.05 4.125)scale(3.9481 .22725)" gradientUnits="userSpaceOnUse"><stop class="b-muogqms"/><stop offset="1" class="yav67rbmp"/></radialGradient><radialGradient id="iwfepwd" cx="0" cy="0" r="1" gradientTransform="matrix(12.44506 5.24999 -1.0644 2.52317 4.4 14.417)" gradientUnits="userSpaceOnUse"><stop class="nupo5abir"/><stop offset="1" class="hkos22v7a"/></radialGradient><radialGradient id="iNWaevd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.9722 4.9375 0 19.22 30.135)" gradientUnits="userSpaceOnUse"><stop class="eb9gn5ava"/><stop offset="1" class="qq8il6a5h"/></radialGradient><radialGradient id="iOghaSc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.125 6.25 0 24.033 30.135)" gradientUnits="userSpaceOnUse"><stop class="ntc53oivj"/><stop offset="1" class="b85qs_bvw"/></radialGradient><radialGradient id="iQS2bFc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.8125 1.78125 -2.21207 -8.46018 17.533 7.448)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="iu1f12bjr"/><stop offset="1" class="f3uwtabvs"/></radialGradient><radialGradient id="i3tWR3c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1875 .625 -.55925 -1.06256 19.127 24.417)" gradientUnits="userSpaceOnUse"><stop class="cw1vrerbd"/><stop offset="1" class="gz278clps"/></radialGradient><radialGradient id="iqZmQxn" cx="0" cy="0" r="1" gradientTransform="rotate(157.049 10.956 9.746)scale(6.65155 2.21973)" gradientUnits="userSpaceOnUse"><stop offset=".21" class="cfuv7bbro"/><stop offset="1" class="u85rlvbnw"/></radialGradient><filter id="iVuCHMe" width="23.545" height="22.044" x="4.401" y="8.091" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.384314 0 0 0 0 0.745098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_5559_20943"/></filter><filter id="iiPT4ec" width="9.688" height="12.353" x="9.077" y="1.615" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.12549 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_5559_20943"/></filter><filter id="iOzhPEb" width="4" height="6.469" x="6.533" y="16.698" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_5559_20943" stdDeviation=".25"/></filter><filter id="iYQLo1c" width="10.714" height="3.813" x="7.226" y="22.823" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_5559_20943" stdDeviation=".5"/></filter><filter id="iIqggqb" width="10.199" height="7.147" x="18.046" y="11.329" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.164706 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_5559_20943"/></filter><linearGradient id="i53xM6d" x1="11.565" x2="11.565" y1="27.198" y2="25.542" gradientUnits="userSpaceOnUse"><stop class="wyqhhtzwk"/><stop offset="1" class="nq20xxbpr"/></linearGradient><linearGradient id="i7Ykmov" x1="7.783" x2="8.752" y1="22.479" y2="17.979" gradientUnits="userSpaceOnUse"><stop class="wruq-9a4m"/><stop offset="1" class="uy461ka4o"/></linearGradient><linearGradient id="iOsnTDs" x1="16.315" x2="7.158" y1="25.135" y2="25.135" gradientUnits="userSpaceOnUse"><stop offset=".563" class="j9oih-bhy"/><stop offset="1" class="hm45clbjp"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:people-hugging" /></template>
<style>
.b-muogqms {
  stop-color: var(--svg-color--937fb7, #937FB7);
}

.b85qs_bvw {
  stop-color: var(--svg-color--856cab, #856CAB);
  stop-opacity: 0;
}

.bglzk7boc {
  stop-color: var(--svg-color--7854b0, #7854B0);
}

.bon68opzd {
  stop-color: var(--svg-color--947cbe, #947CBE);
  stop-opacity: 0;
}

.cfuv7bbro {
  stop-color: var(--svg-color--322c38, #322C38);
}

.cw1vrerbd {
  stop-color: var(--svg-color--2f2c31, #2F2C31);
}

.eb9gn5ava {
  stop-color: var(--svg-color--684c8e, #684C8E);
}

.f3uwtabvs {
  stop-color: var(--svg-color--231433, #231433);
}

.f9ubyz98e {
  d: path("M18.766 15.975H8.226v14.16h10.54z");
}

.fk-o55byp {
  stop-color: var(--svg-color--9f85cb, #9F85CB);
}

.ft5dv1b6b {
  fill: none;
}

.ga340ejbl {
  d: path("M20.246 18.475a2.21 2.21 0 0 1-.79-4.27l5.87-2.26a2.21 2.21 0 0 1 1.59 4.12l-5.87 2.26c-.255.1-.526.15-.8.15");
}

.gtmuv2-cy {
  stop-color: var(--svg-color--1c0c30, #1C0C30);
  stop-opacity: 0;
}

.gz278clps {
  stop-color: var(--svg-color--2f2c31, #2F2C31);
  stop-opacity: 0;
}

.h-zmh0bzc {
  d: path("m6.974 15.256l-1.608 6.31a4.3 4.3 0 0 0 .77 3.74a4.34 4.34 0 0 0 3.43 1.68h8a2.21 2.21 0 0 0 2.21-2.17a2.25 2.25 0 0 0-2.26-2.25h-7.67a.15.15 0 0 1-.15-.19l1.505-5.501c-1.517-.476-2.948-.98-3.796-1.396a11 11 0 0 1-.43-.223");
}

.h1sfekdku {
  fill: var(--svg-color--21182e, #21182E);
  d: path("m6.974 15.256l-1.608 6.31a4.3 4.3 0 0 0 .77 3.74a4.34 4.34 0 0 0 3.43 1.68h8a2.21 2.21 0 0 0 2.21-2.17a2.25 2.25 0 0 0-2.26-2.25h-7.67a.15.15 0 0 1-.15-.19l1.505-5.501c-1.517-.476-2.948-.98-3.796-1.396a11 11 0 0 1-.43-.223");
}

.hkos22v7a {
  stop-color: var(--svg-color--7247ad, #7247AD);
  stop-opacity: 0;
}

.hm45clbjp {
  stop-color: var(--svg-color--2b292e, #2B292E);
  stop-opacity: 0;
}

.iu1f12bjr {
  stop-color: var(--svg-color--372e42, #372E42);
}

.iw186m8pp {
  stop-color: var(--svg-color--614489, #614489);
  stop-opacity: 0;
}

.j9oih-bhy {
  stop-color: var(--svg-color--2b292e, #2B292E);
}

.kbfwc1ats {
  stop-color: var(--svg-color--392b4b, #392B4B);
}

.ks-esmm5e {
  stop-color: var(--svg-color--31253e, #31253E);
  stop-opacity: 0;
}

.lktp6_b5x {
  stop-color: var(--svg-color--3d3746, #3D3746);
}

.mqy-2rbyy {
  stop-color: var(--svg-color--441f6b, #441F6B);
}

.n1_vkrbga {
  d: path("M17.426 5.495a4.42 4.42 0 1 1 8.53 2.28l-.74 2.75a4.66 4.66 0 0 1-3.66 3.38a4.13 4.13 0 0 1-3.38-.91a4.66 4.66 0 0 1-1.49-4.75z");
}

.nq20xxbpr {
  stop-color: var(--svg-color--3e1958, #3E1958);
  stop-opacity: 0;
}

.nt69427qa {
  stop-color: var(--svg-color--1c0c30, #1C0C30);
}

.ntc53oivj {
  stop-color: var(--svg-color--856cab, #856CAB);
}

.nupo5abir {
  stop-color: var(--svg-color--7247ad, #7247AD);
}

.pi-28hb3o {
  stop-color: var(--svg-color--674e8d, #674E8D);
}

.psiel2wbx {
  stop-color: var(--svg-color--8e76b7, #8E76B7);
  stop-opacity: 0;
}

.qq8il6a5h {
  stop-color: var(--svg-color--684c8e, #684C8E);
  stop-opacity: 0;
}

.t_6sasbpq {
  d: path("M7.033 22.667h1.844l1.156-4.625l-1.562-.844z");
}

.tkjhxlr2i {
  d: path("M13.846 19.556a2.55 2.55 0 0 0-1.827-2.43c-1.805-.544-3.614-1.158-4.613-1.647c-2.187-1.07-3.298-2.453-2.938-4.469c.29-1.629 2.016-3.351 6.078-2.664l3.727 3.79h6.573a7 7 0 0 1 7 7v11h-14z");
}

.ts-bd-l-j {
  d: path("M17.846 5.495a4.42 4.42 0 1 0-8.51 2.28l.74 2.75a4.67 4.67 0 0 0 3.66 3.38a4.16 4.16 0 0 0 3.39-.91a4.65 4.65 0 0 0 1.48-4.75z");
}

.u5dcf2bbi {
  stop-color: var(--svg-color--8e76b7, #8E76B7);
}

.u85rlvbnw {
  stop-color: var(--svg-color--221b29, #221B29);
}

.ueqw3jbqm {
  stop-color: var(--svg-color--31253e, #31253E);
}

.uy461ka4o {
  stop-color: var(--svg-color--27232c, #27232C);
}

.v3zx2gi2s {
  stop-color: var(--svg-color--947cbe, #947CBE);
}

.vktua4bec {
  d: path("M8.226 23.823h8.714v1.813H8.226z");
}

.wruq-9a4m {
  stop-color: var(--svg-color--27232d, #27232D);
}

.wyqhhtzwk {
  stop-color: var(--svg-color--3e1958, #3E1958);
}

.xstzhi6_p {
  stop-color: var(--svg-color--a38ad0, #A38AD0);
}

.yav67rbmp {
  stop-color: var(--svg-color--937fb7, #937FB7);
  stop-opacity: 0;
}

</style>
