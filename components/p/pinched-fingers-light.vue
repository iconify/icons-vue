<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="e0y7-dsvj"/><path fill="url(#irIZ8wd)" class="flq3nbb8o"/><path fill="url(#ihXxIXc)" class="flq3nbb8o"/><path fill="url(#iGjrVLe)" class="flq3nbb8o"/><path fill="url(#i57pugd)" class="flq3nbb8o"/><g filter="url(#ivxBeDc)"><path class="o4_z5jpur"/><path fill="url(#iA3UPve)" class="zuxhdrb3z"/><path fill="url(#iwMbLpe)" class="zuxhdrb3z"/><path fill="url(#i5MBjQd)" class="zuxhdrb3z"/><path fill="url(#iYXVSQd)" class="zuxhdrb3z"/><path fill="url(#i7Aos4c)" class="zuxhdrb3z"/></g><path fill="url(#itQmWHe)" class="s19yjkp9b"/><path fill="url(#itLCWDd)" class="s19yjkp9b"/><path fill="url(#ir9fBgb)" class="s19yjkp9b"/><path fill="url(#if9DBIY)" class="udviifhky"/><path fill="url(#irW7kbb)" class="udviifhky"/><path fill="url(#i4XWCke)" class="udviifhky"/><g filter="url(#iv3O5cb)"><path stroke="url(#i8M5WGd)" class="ltqgp4bmv"/></g><g filter="url(#iaoFrNc)"><path stroke="url(#il8vXHH)" class="nruxfdbuf"/></g><path fill="url(#iCA74ze)" class="zuxhdrb3z"/><path fill="url(#iEvHWxb)" class="zuxhdrb3z"/><path fill="url(#igfpCMr)" class="zuxhdrb3z"/><defs><radialGradient id="irIZ8wd" cx="0" cy="0" r="1" gradientTransform="matrix(5.18033 -.49959 .67843 7.03473 20.57 3.593)" gradientUnits="userSpaceOnUse"><stop class="rxffi0b3x"/><stop offset="1" class="mg9an1l_o"/></radialGradient><radialGradient id="ihXxIXc" cx="0" cy="0" r="1" gradientTransform="rotate(-32.25 29.657 -37.222)scale(4.48566 10.4433)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="rxffi0b3x"/><stop offset="1" class="mg9an1l_o"/></radialGradient><radialGradient id="iGjrVLe" cx="0" cy="0" r="1" gradientTransform="rotate(-66.919 30.528 -10.618)scale(9.934 3.0918)" gradientUnits="userSpaceOnUse"><stop class="ftbr74blt"/><stop offset="1" class="sfz2lkbxr"/></radialGradient><radialGradient id="i57pugd" cx="0" cy="0" r="1" gradientTransform="matrix(-11.375 -15.87497 8.3679 -5.9959 32.148 17.12)" gradientUnits="userSpaceOnUse"><stop offset=".914" class="mg9an1l_o"/><stop offset="1" class="rxffi0b3x"/></radialGradient><radialGradient id="iA3UPve" cx="0" cy="0" r="1" gradientTransform="rotate(-23.656 59.029 10.748)scale(30.9972 29.5828)" gradientUnits="userSpaceOnUse"><stop offset=".869" class="tkh6xyo4b"/><stop offset="1" class="ovy1v8_tl"/></radialGradient><radialGradient id="iwMbLpe" cx="0" cy="0" r="1" gradientTransform="matrix(10.414 0 0 5.43789 3.21 23.355)" gradientUnits="userSpaceOnUse"><stop class="tb_5r4b6x"/><stop offset="1" class="rjiejmb4i"/></radialGradient><radialGradient id="i5MBjQd" cx="0" cy="0" r="1" gradientTransform="matrix(2.05479 3.5407 -3.62102 2.1014 9.98 16.265)" gradientUnits="userSpaceOnUse"><stop class="ja_2ksmsh"/><stop offset="1" class="i4eucgbcy"/></radialGradient><radialGradient id="iYXVSQd" cx="0" cy="0" r="1" gradientTransform="rotate(129.359 6.686 13.757)scale(7.19429 5.0654)" gradientUnits="userSpaceOnUse"><stop offset=".293" class="tpoihzh7j"/><stop offset="1" class="flzwrkbii"/></radialGradient><radialGradient id="i7Aos4c" cx="0" cy="0" r="1" gradientTransform="rotate(129.401 7.494 13.267)scale(4.72239 3.60623)" gradientUnits="userSpaceOnUse"><stop offset=".05" class="k-e0w5tuc"/><stop offset="1" class="c_7ctbb7o"/></radialGradient><radialGradient id="itQmWHe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.08366 1.91115 -3.16721 -1.79587 21.53 7.87)" gradientUnits="userSpaceOnUse"><stop class="ovy1v8_tl"/><stop offset="1" class="tkh6xyo4b"/></radialGradient><radialGradient id="itLCWDd" cx="0" cy="0" r="1" gradientTransform="matrix(-.125 2.28125 -2.84207 -.15573 19.382 5.39)" gradientUnits="userSpaceOnUse"><stop class="xhtzk0_cp"/><stop offset="1" class="x37czab2f"/></radialGradient><radialGradient id="if9DBIY" cx="0" cy="0" r="1" gradientTransform="matrix(3.77932 1.1332 -1.36518 4.55298 21.601 14.181)" gradientUnits="userSpaceOnUse"><stop class="amfjtxqsw"/><stop offset="1" class="w-i4kdpxb"/><stop offset="1" class="p63pyfb7u"/></radialGradient><radialGradient id="irW7kbb" cx="0" cy="0" r="1" gradientTransform="matrix(3.52645 -.84408 1.07229 4.47988 20.581 9.765)" gradientUnits="userSpaceOnUse"><stop offset=".457" class="rln5lpdkn"/><stop offset="1" class="ih8rksblz"/></radialGradient><radialGradient id="i4XWCke" cx="0" cy="0" r="1" gradientTransform="rotate(13.65 -10.836 80.38)scale(4.50217 3.60618)" gradientUnits="userSpaceOnUse"><stop class="tpsmx4boc"/><stop offset="1" class="bcartlbzx"/></radialGradient><linearGradient id="ir9fBgb" x1="15.242" x2="17.496" y1="9.437" y2="10.978" gradientUnits="userSpaceOnUse"><stop class="u9xfx_bpd"/><stop offset="1" class="a78kh11td"/></linearGradient><linearGradient id="i8M5WGd" x1="27.867" x2="25.499" y1="15.696" y2="25.776" gradientUnits="userSpaceOnUse"><stop class="mla4tgzzc"/><stop offset="1" class="ms07w1btv"/></linearGradient><linearGradient id="il8vXHH" x1="21.431" x2="21.101" y1="8.627" y2="15.722" gradientUnits="userSpaceOnUse"><stop class="a5lkoibji"/><stop offset="1" class="sfjtufb3d"/></linearGradient><linearGradient id="iCA74ze" x1="8.384" x2="8.384" y1="35.437" y2="24.437" gradientUnits="userSpaceOnUse"><stop class="w-qrplcno"/><stop offset="1" class="lsx3x8b8t"/></linearGradient><linearGradient id="iEvHWxb" x1="3.116" x2="4.313" y1="24.004" y2="24.004" gradientUnits="userSpaceOnUse"><stop class="wpgm2acor"/><stop offset="1" class="bjk-ti1qh"/></linearGradient><linearGradient id="igfpCMr" x1="2.827" x2="3.518" y1="24.004" y2="24.004" gradientUnits="userSpaceOnUse"><stop class="pch09l44u"/><stop offset="1" class="g7hc_ybgm"/></linearGradient><filter id="ivxBeDc" width="26.58" height="27.521" x="2.96" y="2.005" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.709804 0 0 0 0 0.478431 0 0 0 0 0.596078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_1916"/></filter><filter id="iv3O5cb" width="11.961" height="16.255" x="17.894" y="9.274" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1916" stdDeviation=".75"/></filter><filter id="iaoFrNc" width="7.832" height="10.645" x="14.581" y="7.355" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1916" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:pinched-fingers-light" /></template>
<style>
.a5lkoibji {
  stop-color: var(--svg-color--ffe2c8, #FFE2C8);
}

.a78kh11td {
  stop-color: var(--svg-color--dcaa90, #DCAA90);
  stop-opacity: 0;
}

.amfjtxqsw {
  stop-color: var(--svg-color--e89e87, #E89E87);
}

.bcartlbzx {
  stop-color: var(--svg-color--d7a88d, #D7A88D);
  stop-opacity: 0;
}

.bjk-ti1qh {
  stop-color: var(--svg-color--d49992, #D49992);
  stop-opacity: 0;
}

.c_7ctbb7o {
  stop-color: var(--svg-color--e3a588, #E3A588);
  stop-opacity: 0;
}

.e0y7-dsvj {
  fill: var(--svg-color--ffe6c7, #FFE6C7);
  d: path("M24.2 1.926c-.42-.25-.9-.4-1.42-.4a2.659 2.659 0 0 0-1.08 5.09c.35.3.89.79 1.41 1.47c1.09 1.4 1.64 2.93 1.64 4.52c0 2.31-1.18 4.21-2.18 5.39c-1.43 1.7-3.12 2.7-4.12 3.04a2.625 2.625 0 0 0 .84 5.11c.28 0 .56-.04.84-.14c2.24-.75 4.66-2.49 6.47-4.64c1.56-1.85 3.41-4.87 3.41-8.77c-.02-6.77-5.58-10.52-5.81-10.67");
}

.flq3nbb8o {
  d: path("M24.2 1.926c-.42-.25-.9-.4-1.42-.4a2.659 2.659 0 0 0-1.08 5.09c.35.3.89.79 1.41 1.47c1.09 1.4 1.64 2.93 1.64 4.52c0 2.31-1.18 4.21-2.18 5.39c-1.43 1.7-3.12 2.7-4.12 3.04a2.625 2.625 0 0 0 .84 5.11c.28 0 .56-.04.84-.14c2.24-.75 4.66-2.49 6.47-4.64c1.56-1.85 3.41-4.87 3.41-8.77c-.02-6.77-5.58-10.52-5.81-10.67");
}

.flzwrkbii {
  stop-color: var(--svg-color--ffe2c4, #FFE2C4);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.ftbr74blt {
  stop-color: var(--svg-color--e4b8a9, #E4B8A9);
}

.g7hc_ybgm {
  stop-color: var(--svg-color--e8b09d, #E8B09D);
  stop-opacity: 0;
}

.i4eucgbcy {
  stop-color: var(--svg-color--d5aa92, #D5AA92);
  stop-opacity: 0;
}

.ih8rksblz {
  stop-color: var(--svg-color--df927e, #DF927E);
  stop-opacity: 0;
}

.ja_2ksmsh {
  stop-color: var(--svg-color--d5aa92, #D5AA92);
}

.k-e0w5tuc {
  stop-color: var(--svg-color--e3a588, #E3A588);
}

.lsx3x8b8t {
  stop-color: var(--svg-color--b67a95, #B67A95);
  stop-opacity: 0;
}

.ltqgp4bmv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M27.306 11.774c.514 4.95-3.035 10.087-6.911 11.254");
}

.mg9an1l_o {
  stop-color: var(--svg-color--e0ac8f, #E0AC8F);
  stop-opacity: 0;
}

.mla4tgzzc {
  stop-color: var(--svg-color--ffe3c8, #FFE3C8);
}

.ms07w1btv {
  stop-color: var(--svg-color--ffe3c8, #FFE3C8);
  stop-opacity: 0;
}

.nruxfdbuf {
  stroke-linecap: round;
  d: path("M20.413 9.355L16.58 16");
}

.o4_z5jpur {
  fill: var(--svg-color--f5beae, #F5BEAE);
  d: path("M23.25 3.406c-.39-.24-.85-.38-1.33-.4a2.68 2.68 0 0 0-2.74 2.52c-.01.15 0 .29.01.44c-.84.14-1.6.64-2.04 1.44l-5.32 9.15c-.7 1.22-2 1.97-3.41 1.97H3.96c-.55 0-1 .45-1 1v9c0 .55.45 1 1 1h7.58c3.72 0 7.37-1.12 10.4-3.28c.64-.45 1.27-.97 1.88-1.55c.64-.56 1.25-1.18 1.81-1.84c1.56-1.85 3.41-4.87 3.41-8.77c.01-6.77-5.55-10.52-5.79-10.68m-4.26 12.92c0-.24.06-.47.18-.68l3.01-5.45c.07-.12.12-.25.17-.37c.96 1.33 1.44 2.76 1.44 4.26c0 .19-.01.37-.02.56c-.14 1.75-1.62 3.09-3.38 3.09c-.77 0-1.4-.63-1.4-1.41");
}

.ovy1v8_tl {
  stop-color: var(--svg-color--ffe1c3, #FFE1C3);
}

.p63pyfb7u {
  stop-color: var(--svg-color--e89e87, #E89E87);
  stop-opacity: 0;
}

.pch09l44u {
  stop-color: var(--svg-color--e8b09d, #E8B09D);
}

.rjiejmb4i {
  stop-color: var(--svg-color--fccaaf, #FCCAAF);
  stop-opacity: 0;
}

.rln5lpdkn {
  stop-color: var(--svg-color--df927e, #DF927E);
}

.rxffi0b3x {
  stop-color: var(--svg-color--e0ac8f, #E0AC8F);
}

.s19yjkp9b {
  d: path("M17.17 7.369a2.886 2.886 0 0 1 4.995 2.892l-4.314 7.718c-.799 1.38-2.557 1.573-3.937.775c-1.38-.799-1.897-2.517-1.098-3.896z");
}

.sfjtufb3d {
  stop-color: var(--svg-color--ffe2c8, #FFE2C8);
  stop-opacity: 0;
}

.sfz2lkbxr {
  stop-color: var(--svg-color--e4b8a9, #E4B8A9);
  stop-opacity: 0;
}

.tb_5r4b6x {
  stop-color: var(--svg-color--fccaaf, #FCCAAF);
}

.tkh6xyo4b {
  stop-color: var(--svg-color--ffe1c3, #FFE1C3);
  stop-opacity: 0;
}

.tpoihzh7j {
  stop-color: var(--svg-color--ffe2c4, #FFE2C4);
}

.tpsmx4boc {
  stop-color: var(--svg-color--d7a88d, #D7A88D);
}

.u9xfx_bpd {
  stop-color: var(--svg-color--dcaa90, #DCAA90);
}

.udviifhky {
  d: path("M29.04 14.086a12.4 12.4 0 0 1-.566 3.69l-5.608 6.03l-2.562-6.03l-.017-.044q.051.003.103.004c1.76 0 3.24-1.34 3.38-3.09l.001-.028c.01-.18.019-.351.019-.532c0-1.493-.475-2.916-1.426-4.24a2.89 2.89 0 0 0-1.25-3.53c-.67-.387-1.263-.415-1.924-.35l-.001-.014a2.682 2.682 0 0 1 2.731-2.946c.48.02.94.16 1.33.4c.24.16 5.8 3.91 5.79 10.68");
}

.w-i4kdpxb {
  stop-color: var(--svg-color--d08872, #D08872);
  stop-opacity: 0;
}

.w-qrplcno {
  stop-color: var(--svg-color--b67a95, #B67A95);
}

.wpgm2acor {
  stop-color: var(--svg-color--d49992, #D49992);
}

.x37czab2f {
  stop-color: var(--svg-color--e1baa2, #E1BAA2);
  stop-opacity: 0;
}

.xhtzk0_cp {
  stop-color: var(--svg-color--e1baa2, #E1BAA2);
}

.zuxhdrb3z {
  d: path("M23.25 3.406c-.39-.24-.85-.38-1.33-.4a2.68 2.68 0 0 0-2.74 2.52c-.01.15 0 .29.01.44c-.84.14-1.6.64-2.04 1.44l-5.32 9.15c-.7 1.22-2 1.97-3.41 1.97H3.96c-.55 0-1 .45-1 1v9c0 .55.45 1 1 1h7.58c3.72 0 7.37-1.12 10.4-3.28c.64-.45 1.27-.97 1.88-1.55c.64-.56 1.25-1.18 1.81-1.84c1.56-1.85 3.41-4.87 3.41-8.77c.01-6.77-5.55-10.52-5.79-10.68m-4.26 12.92c0-.24.06-.47.18-.68l3.01-5.45c.07-.12.12-.25.17-.37c.96 1.33 1.44 2.76 1.44 4.26c0 .19-.01.37-.02.56c-.14 1.75-1.62 3.09-3.38 3.09c-.77 0-1.4-.63-1.4-1.41");
}

</style>
