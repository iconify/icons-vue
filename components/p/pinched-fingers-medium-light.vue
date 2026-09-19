<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="s7fardqlw"/><path fill="url(#ilwmujd)" class="flq3nbb8o"/><path fill="url(#ihPVx1r)" class="flq3nbb8o"/><path fill="url(#iKbCARF)" class="flq3nbb8o"/><path fill="url(#iQkaAcc)" class="flq3nbb8o"/><g filter="url(#iuMjshb)"><path class="zfp7q8bzy"/><path fill="url(#ii1zFHd)" class="zuxhdrb3z"/><path fill="url(#i5cgkAd)" class="zuxhdrb3z"/><path fill="url(#i0gV3qc)" class="zuxhdrb3z"/><path fill="url(#iHdTLec)" class="zuxhdrb3z"/><path fill="url(#iHpNRod)" class="zuxhdrb3z"/></g><path fill="url(#iwkGIqe)" class="s19yjkp9b"/><path fill="url(#iSqK9ne)" class="s19yjkp9b"/><path fill="url(#i4zIT4b)" class="s19yjkp9b"/><path fill="url(#igYMlAb)" class="udviifhky"/><path fill="url(#iEIrbnt)" class="udviifhky"/><path fill="url(#iqe6ejd)" class="udviifhky"/><g filter="url(#iifk4md)"><path stroke="url(#iLKGkEi)" class="ltqgp4bmv"/></g><g filter="url(#id5Gq6d)"><path stroke="url(#iWALM6i)" class="nruxfdbuf"/></g><path fill="url(#iEqcR4b)" class="zuxhdrb3z"/><path fill="url(#iMH32Pc)" class="zuxhdrb3z"/><path fill="url(#i1kCARc)" class="zuxhdrb3z"/><defs><radialGradient id="ilwmujd" cx="0" cy="0" r="1" gradientTransform="matrix(3.32781 -.20824 .28278 4.51907 20.57 3.593)" gradientUnits="userSpaceOnUse"><stop class="qm1l72l3r"/><stop offset="1" class="z22_4zyml"/></radialGradient><radialGradient id="ihPVx1r" cx="0" cy="0" r="1" gradientTransform="rotate(-32.25 29.657 -37.222)scale(4.48566 10.4433)" gradientUnits="userSpaceOnUse"><stop class="qm1l72l3r"/><stop offset="1" class="z22_4zyml"/></radialGradient><radialGradient id="iKbCARF" cx="0" cy="0" r="1" gradientTransform="rotate(-65.731 31.556 -9.639)scale(8.57053 2.66744)" gradientUnits="userSpaceOnUse"><stop class="qm1l72l3r"/><stop offset="1" class="z22_4zyml"/></radialGradient><radialGradient id="iQkaAcc" cx="0" cy="0" r="1" gradientTransform="matrix(-11.375 -15.87497 8.3679 -5.9959 32.148 17.12)" gradientUnits="userSpaceOnUse"><stop offset=".914" class="z22_4zyml"/><stop offset="1" class="qm1l72l3r"/></radialGradient><radialGradient id="ii1zFHd" cx="0" cy="0" r="1" gradientTransform="rotate(-23.656 59.029 10.748)scale(30.9972 29.5828)" gradientUnits="userSpaceOnUse"><stop offset=".869" class="n4d5fmx6y"/><stop offset="1" class="i_tft3bcw"/></radialGradient><radialGradient id="i5cgkAd" cx="0" cy="0" r="1" gradientTransform="matrix(10.414 0 0 5.43789 3.21 23.355)" gradientUnits="userSpaceOnUse"><stop class="m2cmtvb-l"/><stop offset="1" class="y4ehxiqtz"/></radialGradient><radialGradient id="i0gV3qc" cx="0" cy="0" r="1" gradientTransform="matrix(2.05479 3.5407 -3.62102 2.1014 9.98 16.265)" gradientUnits="userSpaceOnUse"><stop class="mn9d5tbzn"/><stop offset="1" class="ppxvq-5dg"/></radialGradient><radialGradient id="iHdTLec" cx="0" cy="0" r="1" gradientTransform="rotate(120.056 5.886 14.694)scale(6.52613 4.58823)" gradientUnits="userSpaceOnUse"><stop offset=".544" class="iam39hbjh"/><stop offset="1" class="lkabkabyq"/></radialGradient><radialGradient id="iHpNRod" cx="0" cy="0" r="1" gradientTransform="matrix(-2.42065 4.92201 -4.03635 -1.98508 21.546 17.17)" gradientUnits="userSpaceOnUse"><stop offset=".05" class="lavkwmb1v"/><stop offset="1" class="u1hlw9nep"/></radialGradient><radialGradient id="iwkGIqe" cx="0" cy="0" r="1" gradientTransform="matrix(-.75998 1.43553 -2.195 -1.16205 21.296 8.108)" gradientUnits="userSpaceOnUse"><stop class="icjbfbcsz"/><stop offset="1" class="l9j77zbpn"/></radialGradient><radialGradient id="iSqK9ne" cx="0" cy="0" r="1" gradientTransform="matrix(-.125 2.28125 -2.84207 -.15573 19.382 5.39)" gradientUnits="userSpaceOnUse"><stop class="nrlx8326l"/><stop offset="1" class="uy0b49bqf"/></radialGradient><radialGradient id="igYMlAb" cx="0" cy="0" r="1" gradientTransform="matrix(3.77932 1.1332 -1.36518 4.55298 21.601 14.181)" gradientUnits="userSpaceOnUse"><stop class="e52_9gbss"/><stop offset="1" class="w-i4kdpxb"/></radialGradient><radialGradient id="iEIrbnt" cx="0" cy="0" r="1" gradientTransform="matrix(3.52645 -.84408 1.07229 4.47988 20.581 9.765)" gradientUnits="userSpaceOnUse"><stop offset=".457" class="iio8p1btm"/><stop offset="1" class="wsg3sgbga"/></radialGradient><radialGradient id="iqe6ejd" cx="0" cy="0" r="1" gradientTransform="rotate(13.65 -10.836 80.38)scale(4.50217 3.60618)" gradientUnits="userSpaceOnUse"><stop class="ikn_plbqz"/><stop offset="1" class="q4ps6lbpq"/></radialGradient><linearGradient id="i4zIT4b" x1="15.242" x2="17.496" y1="9.437" y2="10.978" gradientUnits="userSpaceOnUse"><stop class="wp787zbtk"/><stop offset="1" class="x_-0w0b7p"/></linearGradient><linearGradient id="iLKGkEi" x1="27.867" x2="25.499" y1="15.696" y2="25.776" gradientUnits="userSpaceOnUse"><stop class="y8_6svbfy"/><stop offset="1" class="hc1xmbcsr"/></linearGradient><linearGradient id="iWALM6i" x1="21.431" x2="21.101" y1="8.627" y2="15.722" gradientUnits="userSpaceOnUse"><stop class="l5qeerbqx"/><stop offset="1" class="yd86phbnw"/></linearGradient><linearGradient id="iEqcR4b" x1="8.384" x2="8.384" y1="32.559" y2="23.433" gradientUnits="userSpaceOnUse"><stop class="vxves1bdk"/><stop offset="1" class="ye3m2mbga"/></linearGradient><linearGradient id="iMH32Pc" x1="3.116" x2="4.313" y1="24.004" y2="24.004" gradientUnits="userSpaceOnUse"><stop class="p1urlbbvr"/><stop offset="1" class="cai6xuoes"/></linearGradient><linearGradient id="i1kCARc" x1="2.827" x2="3.518" y1="24.004" y2="24.004" gradientUnits="userSpaceOnUse"><stop class="kgvko21zs"/><stop offset="1" class="fu2e7-bkw"/></linearGradient><filter id="iuMjshb" width="26.58" height="27.521" x="2.96" y="2.005" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.439216 0 0 0 0 0.576471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_1908"/></filter><filter id="iifk4md" width="11.961" height="16.255" x="17.894" y="9.274" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1908" stdDeviation=".75"/></filter><filter id="id5Gq6d" width="7.832" height="10.645" x="14.581" y="7.355" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1908" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:pinched-fingers-medium-light" /></template>
<style>
.cai6xuoes {
  stop-color: var(--svg-color--ce927f, #CE927F);
  stop-opacity: 0;
}

.e52_9gbss {
  stop-color: var(--svg-color--d08872, #D08872);
}

.flq3nbb8o {
  d: path("M24.2 1.926c-.42-.25-.9-.4-1.42-.4a2.659 2.659 0 0 0-1.08 5.09c.35.3.89.79 1.41 1.47c1.09 1.4 1.64 2.93 1.64 4.52c0 2.31-1.18 4.21-2.18 5.39c-1.43 1.7-3.12 2.7-4.12 3.04a2.625 2.625 0 0 0 .84 5.11c.28 0 .56-.04.84-.14c2.24-.75 4.66-2.49 6.47-4.64c1.56-1.85 3.41-4.87 3.41-8.77c-.02-6.77-5.58-10.52-5.81-10.67");
}

.ft5dv1b6b {
  fill: none;
}

.fu2e7-bkw {
  stop-color: var(--svg-color--e3ab89, #E3AB89);
  stop-opacity: 0;
}

.hc1xmbcsr {
  stop-color: var(--svg-color--ffcea9, #FFCEA9);
  stop-opacity: 0;
}

.i_tft3bcw {
  stop-color: var(--svg-color--f9cba2, #F9CBA2);
}

.iam39hbjh {
  stop-color: var(--svg-color--ffcaa4, #FFCAA4);
}

.icjbfbcsz {
  stop-color: var(--svg-color--ffd0aa, #FFD0AA);
}

.iio8p1btm {
  stop-color: var(--svg-color--c57c6a, #C57C6A);
}

.ikn_plbqz {
  stop-color: var(--svg-color--c69875, #C69875);
}

.kgvko21zs {
  stop-color: var(--svg-color--e3ab89, #E3AB89);
}

.l5qeerbqx {
  stop-color: var(--svg-color--fac6a5, #FAC6A5);
}

.l9j77zbpn {
  stop-color: var(--svg-color--ffd0aa, #FFD0AA);
  stop-opacity: 0;
}

.lavkwmb1v {
  stop-color: var(--svg-color--c79577, #C79577);
}

.lkabkabyq {
  stop-color: var(--svg-color--ffcaa4, #FFCAA4);
  stop-opacity: 0;
}

.ltqgp4bmv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M27.306 11.774c.514 4.95-3.035 10.087-6.911 11.254");
}

.m2cmtvb-l {
  stop-color: var(--svg-color--f2c4a7, #F2C4A7);
}

.mn9d5tbzn {
  stop-color: var(--svg-color--c49a7c, #C49A7C);
}

.n4d5fmx6y {
  stop-color: var(--svg-color--f9cba2, #F9CBA2);
  stop-opacity: 0;
}

.nrlx8326l {
  stop-color: var(--svg-color--cfa685, #CFA685);
}

.nruxfdbuf {
  stroke-linecap: round;
  d: path("M20.413 9.355L16.58 16");
}

.p1urlbbvr {
  stop-color: var(--svg-color--ce927f, #CE927F);
}

.ppxvq-5dg {
  stop-color: var(--svg-color--c49a7c, #C49A7C);
  stop-opacity: 0;
}

.q4ps6lbpq {
  stop-color: var(--svg-color--c69875, #C69875);
  stop-opacity: 0;
}

.qm1l72l3r {
  stop-color: var(--svg-color--c39a7c, #C39A7C);
}

.s19yjkp9b {
  d: path("M17.17 7.369a2.886 2.886 0 0 1 4.995 2.892l-4.314 7.718c-.799 1.38-2.557 1.573-3.937.775c-1.38-.799-1.897-2.517-1.098-3.896z");
}

.s7fardqlw {
  fill: var(--svg-color--fecea5, #FECEA5);
  d: path("M24.2 1.926c-.42-.25-.9-.4-1.42-.4a2.659 2.659 0 0 0-1.08 5.09c.35.3.89.79 1.41 1.47c1.09 1.4 1.64 2.93 1.64 4.52c0 2.31-1.18 4.21-2.18 5.39c-1.43 1.7-3.12 2.7-4.12 3.04a2.625 2.625 0 0 0 .84 5.11c.28 0 .56-.04.84-.14c2.24-.75 4.66-2.49 6.47-4.64c1.56-1.85 3.41-4.87 3.41-8.77c-.02-6.77-5.58-10.52-5.81-10.67");
}

.u1hlw9nep {
  stop-color: var(--svg-color--c79577, #C79577);
  stop-opacity: 0;
}

.udviifhky {
  d: path("M29.04 14.086a12.4 12.4 0 0 1-.566 3.69l-5.608 6.03l-2.562-6.03l-.017-.044q.051.003.103.004c1.76 0 3.24-1.34 3.38-3.09l.001-.028c.01-.18.019-.351.019-.532c0-1.493-.475-2.916-1.426-4.24a2.89 2.89 0 0 0-1.25-3.53c-.67-.387-1.263-.415-1.924-.35l-.001-.014a2.682 2.682 0 0 1 2.731-2.946c.48.02.94.16 1.33.4c.24.16 5.8 3.91 5.79 10.68");
}

.uy0b49bqf {
  stop-color: var(--svg-color--cfa685, #CFA685);
  stop-opacity: 0;
}

.vxves1bdk {
  stop-color: var(--svg-color--b77189, #B77189);
}

.w-i4kdpxb {
  stop-color: var(--svg-color--d08872, #D08872);
  stop-opacity: 0;
}

.wp787zbtk {
  stop-color: var(--svg-color--c8997a, #C8997A);
}

.wsg3sgbga {
  stop-color: var(--svg-color--c57c6a, #C57C6A);
  stop-opacity: 0;
}

.x_-0w0b7p {
  stop-color: var(--svg-color--c8997a, #C8997A);
  stop-opacity: 0;
}

.y4ehxiqtz {
  stop-color: var(--svg-color--f2c4a7, #F2C4A7);
  stop-opacity: 0;
}

.y8_6svbfy {
  stop-color: var(--svg-color--ffcea9, #FFCEA9);
}

.yd86phbnw {
  stop-color: var(--svg-color--fac6a5, #FAC6A5);
  stop-opacity: 0;
}

.ye3m2mbga {
  stop-color: var(--svg-color--b77189, #B77189);
  stop-opacity: 0;
}

.z22_4zyml {
  stop-color: var(--svg-color--c39a7c, #C39A7C);
  stop-opacity: 0;
}

.zfp7q8bzy {
  fill: var(--svg-color--e4ab94, #E4AB94);
  d: path("M23.25 3.406c-.39-.24-.85-.38-1.33-.4a2.68 2.68 0 0 0-2.74 2.52c-.01.15 0 .29.01.44c-.84.14-1.6.64-2.04 1.44l-5.32 9.15c-.7 1.22-2 1.97-3.41 1.97H3.96c-.55 0-1 .45-1 1v9c0 .55.45 1 1 1h7.58c3.72 0 7.37-1.12 10.4-3.28c.64-.45 1.27-.97 1.88-1.55c.64-.56 1.25-1.18 1.81-1.84c1.56-1.85 3.41-4.87 3.41-8.77c.01-6.77-5.55-10.52-5.79-10.68m-4.26 12.92c0-.24.06-.47.18-.68l3.01-5.45c.07-.12.12-.25.17-.37c.96 1.33 1.44 2.76 1.44 4.26c0 .19-.01.37-.02.56c-.14 1.75-1.62 3.09-3.38 3.09c-.77 0-1.4-.63-1.4-1.41");
}

.zuxhdrb3z {
  d: path("M23.25 3.406c-.39-.24-.85-.38-1.33-.4a2.68 2.68 0 0 0-2.74 2.52c-.01.15 0 .29.01.44c-.84.14-1.6.64-2.04 1.44l-5.32 9.15c-.7 1.22-2 1.97-3.41 1.97H3.96c-.55 0-1 .45-1 1v9c0 .55.45 1 1 1h7.58c3.72 0 7.37-1.12 10.4-3.28c.64-.45 1.27-.97 1.88-1.55c.64-.56 1.25-1.18 1.81-1.84c1.56-1.85 3.41-4.87 3.41-8.77c.01-6.77-5.55-10.52-5.79-10.68m-4.26 12.92c0-.24.06-.47.18-.68l3.01-5.45c.07-.12.12-.25.17-.37c.96 1.33 1.44 2.76 1.44 4.26c0 .19-.01.37-.02.56c-.14 1.75-1.62 3.09-3.38 3.09c-.77 0-1.4-.63-1.4-1.41");
}

</style>
