<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="m1l1ahg7x"/><path fill="url(#iUtk3qU)" class="qpfv_ubtz"/><path fill="url(#iLwmZ0d)" class="qpfv_ubtz"/><path fill="url(#iTEbOed)" class="qpfv_ubtz"/><path fill="url(#iQxr8Le)" class="qpfv_ubtz"/><g filter="url(#igwJZgf)"><path class="vcvslrhnv"/><path fill="url(#i24kIsy)" class="s65cwx2jf"/><path fill="url(#iNKOEEc)" class="s65cwx2jf"/><path fill="url(#iWdQoLc)" class="s65cwx2jf"/><path fill="url(#iPKmTlx)" class="s65cwx2jf"/><path fill="url(#iNPCUhB)" class="s65cwx2jf"/></g><path fill="url(#iMOjadc)" class="g0loe0jun"/><path fill="url(#ic8wf5c)" class="g0loe0jun"/><path fill="url(#iyqMZ0c)" class="q11npeh-k"/><path fill="url(#if0joye)" class="q11npeh-k"/><g filter="url(#iNOjTSc)"><path stroke="url(#isg3vGb)" class="ge56phbgp"/></g><g filter="url(#iYXJJ7b)"><path stroke="url(#iHBk2sC)" class="nbj0hxrbe"/></g><defs><radialGradient id="iUtk3qU" cx="0" cy="0" r="1" gradientTransform="matrix(3.32781 -.20826 .28281 4.51907 19.908 4.016)" gradientUnits="userSpaceOnUse"><stop class="nzaohjzxa"/><stop offset="1" class="t-w3o5dyq"/></radialGradient><radialGradient id="iLwmZ0d" cx="0" cy="0" r="1" gradientTransform="rotate(-32.25 30.056 -35.863)scale(4.48566 10.4433)" gradientUnits="userSpaceOnUse"><stop class="coioqjb4u"/><stop offset=".948" class="wd9tvvbzs"/></radialGradient><radialGradient id="iTEbOed" cx="0" cy="0" r="1" gradientTransform="rotate(-65.731 31.551 -8.914)scale(8.57053 2.66744)" gradientUnits="userSpaceOnUse"><stop class="coioqjb4u"/><stop offset="1" class="wd9tvvbzs"/></radialGradient><radialGradient id="iQxr8Le" cx="0" cy="0" r="1" gradientTransform="matrix(-11.375 -15.87497 8.3679 -5.9959 31.484 17.542)" gradientUnits="userSpaceOnUse"><stop offset=".914" class="gtizkg5nt"/><stop offset="1" class="w-xse48pu"/></radialGradient><radialGradient id="i24kIsy" cx="0" cy="0" r="1" gradientTransform="rotate(-23.656 59.705 12.543)scale(30.9972 29.5828)" gradientUnits="userSpaceOnUse"><stop offset=".869" class="bf8wustri"/><stop offset="1" class="rh7z--bgm"/></radialGradient><radialGradient id="iNKOEEc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.50242 5.60395 -3.9277 -2.45478 19.264 17.753)" gradientUnits="userSpaceOnUse"><stop offset=".141" class="r_lxi8pyn"/><stop offset="1" class="wjlvsp5-k"/></radialGradient><radialGradient id="iWdQoLc" cx="0" cy="0" r="1" gradientTransform="matrix(10.414 0 0 5.43789 2.546 23.777)" gradientUnits="userSpaceOnUse"><stop class="y329gtbxo"/><stop offset="1" class="r026toxhj"/></radialGradient><radialGradient id="iPKmTlx" cx="0" cy="0" r="1" gradientTransform="matrix(2.05479 3.5407 -3.62102 2.1014 9.318 16.687)" gradientUnits="userSpaceOnUse"><stop class="bibnaxnjs"/><stop offset="1" class="w85876bbm"/></radialGradient><radialGradient id="iNPCUhB" cx="0" cy="0" r="1" gradientTransform="rotate(95.412 2.404 18.17)scale(4.62847 4.5136)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="h_wxqlmxu"/><stop offset="1" class="e3s-mkb3s"/></radialGradient><radialGradient id="iMOjadc" cx="0" cy="0" r="1" gradientTransform="matrix(-.75998 1.43553 -2.195 -1.16205 20.632 8.53)" gradientUnits="userSpaceOnUse"><stop class="mw5vlrbvk"/><stop offset="1" class="ut-a4zo6y"/></radialGradient><radialGradient id="ic8wf5c" cx="0" cy="0" r="1" gradientTransform="matrix(-.125 2.28125 -2.84207 -.15573 18.719 5.813)" gradientUnits="userSpaceOnUse"><stop class="kkmfbvbin"/><stop offset="1" class="phfukacxx"/></radialGradient><radialGradient id="iyqMZ0c" cx="0" cy="0" r="1" gradientTransform="matrix(5.03125 .0625 -.06485 5.22067 20.265 13.604)" gradientUnits="userSpaceOnUse"><stop class="wvz3n0nun"/><stop offset="1" class="q7nxujbqf"/></radialGradient><radialGradient id="if0joye" cx="0" cy="0" r="1" gradientTransform="matrix(3.08216 -.98069 1.24583 3.91547 19.918 10.188)" gradientUnits="userSpaceOnUse"><stop offset=".36" class="oocyb0shp"/><stop offset="1" class="ca7ajslci"/></radialGradient><filter id="igwJZgf" width="26.58" height="27.521" x="2.297" y="2.427" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.304167 0 0 0 0 0.169826 0 0 0 0 0.298793 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_1886"/></filter><filter id="iNOjTSc" width="11.961" height="16.255" x="17.231" y="9.696" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1886" stdDeviation=".75"/></filter><filter id="iYXJJ7b" width="7.832" height="10.645" x="13.917" y="7.777" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1886" stdDeviation=".75"/></filter><linearGradient id="isg3vGb" x1="27.203" x2="24.836" y1="16.119" y2="26.199" gradientUnits="userSpaceOnUse"><stop class="u0a3bubhy"/><stop offset="1" class="iyh04pbcs"/></linearGradient><linearGradient id="iHBk2sC" x1="20.768" x2="20.438" y1="9.05" y2="16.144" gradientUnits="userSpaceOnUse"><stop class="l_3w1myze"/><stop offset="1" class="cv7wwgeqb"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:pinched-fingers-dark" /></template>
<style>
.bf8wustri {
  stop-color: var(--svg-color--614b48, #614B48);
  stop-opacity: 0;
}

.bibnaxnjs {
  stop-color: var(--svg-color--493b39, #493B39);
}

.ca7ajslci {
  stop-color: var(--svg-color--2b1617, #2B1617);
  stop-opacity: 0;
}

.coioqjb4u {
  stop-color: var(--svg-color--3e2c29, #3E2C29);
}

.cv7wwgeqb {
  stop-color: var(--svg-color--665250, #665250);
  stop-opacity: 0;
}

.e3s-mkb3s {
  stop-color: var(--svg-color--503632, #503632);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g0loe0jun {
  d: path("M16.507 7.791a2.886 2.886 0 0 1 4.995 2.892L17.187 18.4c-.798 1.38-2.557 1.574-3.936.775c-1.38-.798-1.897-2.516-1.099-3.896z");
}

.ge56phbgp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M26.643 12.196c.514 4.95-3.036 10.087-6.912 11.255");
}

.gtizkg5nt {
  stop-color: var(--svg-color--4d4240, #4D4240);
  stop-opacity: 0;
}

.h_wxqlmxu {
  stop-color: var(--svg-color--503632, #503632);
}

.iyh04pbcs {
  stop-color: var(--svg-color--644f4e, #644F4E);
  stop-opacity: 0;
}

.kkmfbvbin {
  stop-color: var(--svg-color--503e3b, #503E3B);
}

.l_3w1myze {
  stop-color: var(--svg-color--665250, #665250);
}

.m1l1ahg7x {
  fill: var(--svg-color--624f4c, #624F4C);
  d: path("M23.537 2.348c-.42-.25-.9-.4-1.42-.4a2.659 2.659 0 0 0-1.08 5.09c.35.3.89.79 1.41 1.47c1.09 1.4 1.64 2.93 1.64 4.52c0 2.31-1.18 4.21-2.18 5.39c-1.43 1.7-3.12 2.7-4.12 3.04a2.625 2.625 0 0 0 .84 5.11c.28 0 .56-.04.84-.14c2.24-.75 4.66-2.49 6.47-4.64c1.56-1.85 3.41-4.87 3.41-8.77c-.02-6.77-5.58-10.52-5.81-10.67");
}

.mw5vlrbvk {
  stop-color: var(--svg-color--685351, #685351);
}

.nbj0hxrbe {
  stroke-linecap: round;
  d: path("m19.75 9.777l-3.833 6.645");
}

.nzaohjzxa {
  stop-color: var(--svg-color--3f2a27, #3F2A27);
}

.oocyb0shp {
  stop-color: var(--svg-color--2b1617, #2B1617);
}

.phfukacxx {
  stop-color: var(--svg-color--503e3b, #503E3B);
  stop-opacity: 0;
}

.q11npeh-k {
  d: path("M28.377 14.508a12.4 12.4 0 0 1-.567 3.69l-5.607 6.031l-2.563-6.031l-.016-.044q.05.004.103.004c1.76 0 3.24-1.34 3.38-3.09l.001-.027c.01-.18.019-.352.019-.533c0-1.493-.476-2.916-1.426-4.24a2.89 2.89 0 0 0-1.25-3.529c-.67-.388-1.264-.416-1.924-.351l-.001-.014c-.01-.145-.02-.28-.01-.426c.08-1.43 1.3-2.56 2.74-2.52c.48.02.94.16 1.33.4c.24.16 5.8 3.91 5.79 10.68");
}

.q7nxujbqf {
  stop-color: var(--svg-color--311c1f, #311C1F);
  stop-opacity: 0;
}

.qpfv_ubtz {
  d: path("M23.537 2.348c-.42-.25-.9-.4-1.42-.4a2.659 2.659 0 0 0-1.08 5.09c.35.3.89.79 1.41 1.47c1.09 1.4 1.64 2.93 1.64 4.52c0 2.31-1.18 4.21-2.18 5.39c-1.43 1.7-3.12 2.7-4.12 3.04a2.625 2.625 0 0 0 .84 5.11c.28 0 .56-.04.84-.14c2.24-.75 4.66-2.49 6.47-4.64c1.56-1.85 3.41-4.87 3.41-8.77c-.02-6.77-5.58-10.52-5.81-10.67");
}

.r_lxi8pyn {
  stop-color: var(--svg-color--6f5654, #6F5654);
}

.r026toxhj {
  stop-color: var(--svg-color--5f4141, #5F4141);
  stop-opacity: 0;
}

.rh7z--bgm {
  stop-color: var(--svg-color--614b48, #614B48);
}

.s65cwx2jf {
  d: path("M22.587 3.828c-.39-.24-.85-.38-1.33-.4a2.68 2.68 0 0 0-2.74 2.52c-.01.15 0 .29.01.44c-.84.14-1.6.64-2.04 1.44l-5.32 9.15c-.7 1.22-2 1.97-3.41 1.97h-4.46c-.55 0-1 .45-1 1v9c0 .55.45 1 1 1h7.58c3.72 0 7.37-1.12 10.4-3.28c.64-.45 1.27-.97 1.88-1.55c.64-.56 1.25-1.18 1.81-1.84c1.56-1.85 3.41-4.87 3.41-8.77c.01-6.77-5.55-10.52-5.79-10.68m-4.26 12.92c0-.24.06-.47.18-.68l3.01-5.45c.07-.12.12-.25.17-.37c.96 1.33 1.44 2.76 1.44 4.26c0 .19-.01.37-.02.56c-.14 1.75-1.62 3.09-3.38 3.09c-.77 0-1.4-.63-1.4-1.41");
}

.t-w3o5dyq {
  stop-color: var(--svg-color--3f2a27, #3F2A27);
  stop-opacity: 0;
}

.u0a3bubhy {
  stop-color: var(--svg-color--644f4e, #644F4E);
}

.ut-a4zo6y {
  stop-color: var(--svg-color--685351, #685351);
  stop-opacity: 0;
}

.vcvslrhnv {
  fill: var(--svg-color--483031, #483031);
  d: path("M22.587 3.828c-.39-.24-.85-.38-1.33-.4a2.68 2.68 0 0 0-2.74 2.52c-.01.15 0 .29.01.44c-.84.14-1.6.64-2.04 1.44l-5.32 9.15c-.7 1.22-2 1.97-3.41 1.97h-4.46c-.55 0-1 .45-1 1v9c0 .55.45 1 1 1h7.58c3.72 0 7.37-1.12 10.4-3.28c.64-.45 1.27-.97 1.88-1.55c.64-.56 1.25-1.18 1.81-1.84c1.56-1.85 3.41-4.87 3.41-8.77c.01-6.77-5.55-10.52-5.79-10.68m-4.26 12.92c0-.24.06-.47.18-.68l3.01-5.45c.07-.12.12-.25.17-.37c.96 1.33 1.44 2.76 1.44 4.26c0 .19-.01.37-.02.56c-.14 1.75-1.62 3.09-3.38 3.09c-.77 0-1.4-.63-1.4-1.41");
}

.w-xse48pu {
  stop-color: var(--svg-color--4d4240, #4D4240);
}

.w85876bbm {
  stop-color: var(--svg-color--493b39, #493B39);
  stop-opacity: 0;
}

.wd9tvvbzs {
  stop-color: var(--svg-color--3e2c29, #3E2C29);
  stop-opacity: 0;
}

.wjlvsp5-k {
  stop-color: var(--svg-color--6f5654, #6F5654);
  stop-opacity: 0;
}

.wvz3n0nun {
  stop-color: var(--svg-color--311c1f, #311C1F);
}

.y329gtbxo {
  stop-color: var(--svg-color--5f4141, #5F4141);
}

</style>
