<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iQTg8Lg)"><path fill="url(#ipBTmEe)" class="krn_cvbaj"/></g><path fill="url(#i87pBur)" class="krn_cvbaj"/><path fill="url(#iY2lswc)" class="krn_cvbaj"/><path fill="url(#ivKCi9l)" class="krn_cvbaj"/><g filter="url(#iU4BOrh)"><path class="mtx4l6ddk"/></g><g filter="url(#ii0E7Fe)"><path class="y737dyb-e"/></g><rect fill="url(#i2P5sNc)" transform="rotate(-90 6.703 21.013)" class="ak1scibmc"/><rect fill="url(#i5uwuPd)" transform="rotate(-90 6.703 21.013)" class="ak1scibmc"/><rect fill="url(#iNI4FDc)" transform="rotate(-90 6.703 21.013)" class="ak1scibmc"/><rect fill="url(#iFu5oKe)" transform="rotate(-90 6.703 21.013)" class="ak1scibmc"/><rect fill="url(#itiffYc)" transform="rotate(-90 6.703 21.013)" class="ak1scibmc"/><rect fill="url(#il6BTye)" transform="rotate(-90 7 7.81)" class="ofln3ei7x"/><rect fill="url(#i7va8yd)" transform="rotate(-90 7 7.81)" class="ofln3ei7x"/><rect fill="url(#iecxEyc)" transform="rotate(-90 7 7.81)" class="ofln3ei7x"/><rect fill="url(#idGlvyb)" transform="rotate(-90 7 7.81)" class="ofln3ei7x"/><rect fill="url(#iwoSApa)" transform="rotate(-90 5.71 12.064)" class="r0z2q7brs"/><rect fill="url(#iFahNFd)" transform="rotate(-90 5.71 12.064)" class="r0z2q7brs"/><rect fill="url(#ifZ63Ib)" transform="rotate(-90 5.71 12.064)" class="r0z2q7brs"/><rect fill="url(#iteUb5c)" transform="rotate(-90 5.71 12.064)" class="r0z2q7brs"/><rect fill="url(#i03KMuc)" transform="rotate(-90 5.756 16.486)" class="wrbe9si2s"/><rect fill="url(#inGyoCD)" transform="rotate(-90 5.756 16.486)" class="wrbe9si2s"/><rect fill="url(#ivNeccb)" transform="rotate(-90 5.756 16.486)" class="wrbe9si2s"/><rect fill="url(#iMdFiNc)" transform="rotate(-90 5.756 16.486)" class="wrbe9si2s"/><defs><radialGradient id="i87pBur" cx="0" cy="0" r="1" gradientTransform="matrix(-6.09874 3.46893 -3.9808 -6.99866 24.495 7.567)" gradientUnits="userSpaceOnUse"><stop class="gyb4_5noa"/><stop offset="1" class="cv7wwgeqb"/></radialGradient><radialGradient id="iY2lswc" cx="0" cy="0" r="1" gradientTransform="matrix(4.64396 0 0 9.96517 19.895 26.084)" gradientUnits="userSpaceOnUse"><stop class="okv9xjb9p"/><stop offset="1" class="nfr6v1bua"/></radialGradient><radialGradient id="ivKCi9l" cx="0" cy="0" r="1" gradientTransform="scale(12.9389 20.0228)rotate(90 .413 .923)" gradientUnits="userSpaceOnUse"><stop offset=".902" class="qjo0o-q3r"/><stop offset="1" class="scg7r2b1k"/></radialGradient><radialGradient id="iNI4FDc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.58086 2.00356 0 10.256 28.655)" gradientUnits="userSpaceOnUse"><stop class="xm34y9b_d"/><stop offset="1" class="iv6sy1bym"/></radialGradient><radialGradient id="iFu5oKe" cx="0" cy="0" r="1" gradientTransform="matrix(-.9313 0 0 -4.89838 11.216 24.948)" gradientUnits="userSpaceOnUse"><stop class="x-nzeubpg"/><stop offset="1" class="isrtqhbgj"/></radialGradient><radialGradient id="itiffYc" cx="0" cy="0" r="1" gradientTransform="matrix(-.17279 -7.31561 8.00204 -.189 9.594 28.328)" gradientUnits="userSpaceOnUse"><stop offset=".808" class="pko18bchz"/><stop offset="1" class="ec8uimbqc"/></radialGradient><radialGradient id="i7va8yd" cx="0" cy="0" r="1" gradientTransform="matrix(1.06838 0 0 4.40184 7.885 12.125)" gradientUnits="userSpaceOnUse"><stop class="g9spz3bnd"/><stop offset="1" class="c71jc1b8j"/></radialGradient><radialGradient id="iecxEyc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.78495 2.38236 0 10.787 14.998)" gradientUnits="userSpaceOnUse"><stop class="p6wb4qngy"/><stop offset="1" class="iv9_edb6r"/></radialGradient><radialGradient id="idGlvyb" cx="0" cy="0" r="1" gradientTransform="matrix(-.16817 -7.16786 7.78679 -.18269 9.815 14.978)" gradientUnits="userSpaceOnUse"><stop offset=".808" class="zjc5vidhp"/><stop offset="1" class="lfi8mbbes"/></radialGradient><radialGradient id="iFahNFd" cx="0" cy="0" r="1" gradientTransform="matrix(1.125 0 0 5.04687 6.642 17.011)" gradientUnits="userSpaceOnUse"><stop class="lrn9-vbzw"/><stop offset="1" class="idax9pm8p"/></radialGradient><radialGradient id="ifZ63Ib" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.68226 2.10732 0 9.236 20.227)" gradientUnits="userSpaceOnUse"><stop class="xm34y9b_d"/><stop offset="1" class="iv6sy1bym"/></radialGradient><radialGradient id="iteUb5c" cx="0" cy="0" r="1" gradientTransform="matrix(-.17705 -8.21822 8.20018 -.17667 8.674 20.282)" gradientUnits="userSpaceOnUse"><stop offset=".808" class="g2ui6gcrz"/><stop offset="1" class="sovlmvb0c"/></radialGradient><radialGradient id="inGyoCD" cx="0" cy="0" r="1" gradientTransform="matrix(2.38035 0 0 7.9345 5.5 20.031)" gradientUnits="userSpaceOnUse"><stop class="o0kqsqbxo"/><stop offset="1" class="exohgcbpw"/></radialGradient><radialGradient id="ivNeccb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.6702 2.06121 0 9.205 24.613)" gradientUnits="userSpaceOnUse"><stop class="rg3n2_b4b"/><stop offset="1" class="dxyp9sb9a"/></radialGradient><radialGradient id="iMdFiNc" cx="0" cy="0" r="1" gradientTransform="matrix(-.17323 -8.18127 8.02085 -.16983 8.655 24.668)" gradientUnits="userSpaceOnUse"><stop offset=".808" class="ahgj_zw-p"/><stop offset="1" class="pe-7wrbwg"/></radialGradient><linearGradient id="ipBTmEe" x1="26.587" x2="12.093" y1="8.105" y2="29.819" gradientUnits="userSpaceOnUse"><stop class="eimafd7la"/><stop offset="1" class="j9gimmeiu"/></linearGradient><linearGradient id="i2P5sNc" x1="9.595" x2="9.595" y1="21.013" y2="30" gradientUnits="userSpaceOnUse"><stop class="lenvnubyg"/><stop offset="1" class="s3xe04bqa"/></linearGradient><linearGradient id="i5uwuPd" x1="6.35" x2="8.227" y1="25.506" y2="25.506" gradientUnits="userSpaceOnUse"><stop class="b_lb4lmpk"/><stop offset="1" class="aiktqqdsj"/></linearGradient><linearGradient id="il6BTye" x1="8.345" x2="10.69" y1="8.718" y2="15.823" gradientUnits="userSpaceOnUse"><stop class="nwmok1m8m"/><stop offset="1" class="qsx826m4r"/></linearGradient><linearGradient id="iwoSApa" x1="7.126" x2="10.001" y1="13.105" y2="21.105" gradientUnits="userSpaceOnUse"><stop class="g75mbmjbv"/><stop offset="1" class="mhcyt_btx"/></linearGradient><linearGradient id="i03KMuc" x1="8.654" x2="8.654" y1="16.486" y2="25.515" gradientUnits="userSpaceOnUse"><stop class="h_5d2c_4d"/><stop offset="1" class="lnrt7jb1q"/></linearGradient><filter id="iQTg8Lg" width="18.933" height="27.637" x="9.18" y="2.181" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.235294 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3052"/></filter><filter id="iU4BOrh" width="12.677" height="20.87" x="5.323" y="1.398" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3052" stdDeviation="1"/></filter><filter id="ii0E7Fe" width="12.088" height="5.26" x="12.203" y="15.224" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3052" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:thumbs-down-dark" /></template>
<style>
.ahgj_zw-p {
  stop-color: var(--svg-color--564642, #564642);
  stop-opacity: 0;
}

.aiktqqdsj {
  stop-color: var(--svg-color--3d2238, #3D2238);
  stop-opacity: 0;
}

.ak1scibmc {
  width: 5.784px;
  height: 8.988px;
  x: 6.703px;
  y: 21.013px;
  rx: 2.892px;
}

.b_lb4lmpk {
  stop-color: var(--svg-color--3d2238, #3D2238);
}

.c71jc1b8j {
  stop-color: var(--svg-color--321c19, #321C19);
  stop-opacity: 0;
}

.cv7wwgeqb {
  stop-color: var(--svg-color--665250, #665250);
  stop-opacity: 0;
}

.dxyp9sb9a {
  stop-color: var(--svg-color--665150, #665150);
  stop-opacity: 0;
}

.ec8uimbqc {
  stop-color: var(--svg-color--554542, #554542);
}

.eimafd7la {
  stop-color: var(--svg-color--523835, #523835);
}

.exohgcbpw {
  stop-color: var(--svg-color--3a1f2d, #3A1F2D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g2ui6gcrz {
  stop-color: var(--svg-color--574744, #574744);
  stop-opacity: 0;
}

.g75mbmjbv {
  stop-color: var(--svg-color--3c2827, #3C2827);
}

.g9spz3bnd {
  stop-color: var(--svg-color--321c19, #321C19);
}

.gyb4_5noa {
  stop-color: var(--svg-color--745e5c, #745E5C);
}

.h_5d2c_4d {
  stop-color: var(--svg-color--3f2c29, #3F2C29);
}

.idax9pm8p {
  stop-color: var(--svg-color--2b1715, #2B1715);
  stop-opacity: 0;
}

.isrtqhbgj {
  stop-color: var(--svg-color--220d0f, #220D0F);
  stop-opacity: 0;
}

.iv6sy1bym {
  stop-color: var(--svg-color--65514f, #65514F);
  stop-opacity: 0;
}

.iv9_edb6r {
  stop-color: var(--svg-color--634f4d, #634F4D);
  stop-opacity: 0;
}

.j9gimmeiu {
  stop-color: var(--svg-color--40292b, #40292B);
}

.krn_cvbaj {
  d: path("M20.307 26.55a3.268 3.268 0 1 1-6.536 0v-3.76q-.001-.482.071-.961q.03-.175.048-.35c.036-.368-.008-.849-.258-1.172l.598-.576a9.28 9.28 0 0 1-5.05-8.275c0-.979.15-1.923.43-2.808l.99-6.467h8.051v.003c4.973.107 8.962 3.35 8.962 9.272c0 3.481-1.667 6.284-4.189 7.864l.006.005c-.172.12-.374.24-.591.371l-.002.001c-.715.429-1.59.953-2.05 1.81c-.4.743-.478 1.948-.478 2.508l-.002-.001z");
}

.lenvnubyg {
  stop-color: var(--svg-color--3d2728, #3D2728);
}

.lfi8mbbes {
  stop-color: var(--svg-color--564744, #564744);
}

.lnrt7jb1q {
  stop-color: var(--svg-color--4d332f, #4D332F);
}

.lrn9-vbzw {
  stop-color: var(--svg-color--2b1715, #2B1715);
}

.mhcyt_btx {
  stop-color: var(--svg-color--553b37, #553B37);
}

.mtx4l6ddk {
  fill: var(--svg-color--35201e, #35201E);
  d: path("M8.432 5.919c0 .468.122.907.336 1.283c-.855.428-1.445 1.34-1.445 2.394c0 .82.357 1.553.917 2.04a2.64 2.64 0 0 0-.878 1.98c0 1.039.585 1.936 1.431 2.35a2.65 2.65 0 0 0-.618 1.71c0 1.431 1.113 2.591 2.486 2.591h2.753c1.373 0 2.486-1.16 2.486-2.59a2.63 2.63 0 0 0-.891-1.988A2.63 2.63 0 0 0 16 13.616c0-.803-.35-1.52-.898-1.997A2.7 2.7 0 0 0 16 9.596c0-.728-.28-1.387-.736-1.867c.454-.458.736-1.1.736-1.81c0-1.393-1.083-2.521-2.419-2.521h-2.73c-1.336 0-2.42 1.128-2.42 2.52");
}

.nfr6v1bua {
  stop-color: var(--svg-color--5b4444, #5B4444);
  stop-opacity: 0;
}

.nwmok1m8m {
  stop-color: var(--svg-color--392726, #392726);
}

.o0kqsqbxo {
  stop-color: var(--svg-color--3a1f2d, #3A1F2D);
}

.ofln3ei7x {
  width: 5.629px;
  height: 8.806px;
  x: 7.001px;
  y: 7.81px;
  rx: 2.814px;
}

.okv9xjb9p {
  stop-color: var(--svg-color--5b4444, #5B4444);
}

.p6wb4qngy {
  stop-color: var(--svg-color--634f4d, #634F4D);
}

.pe-7wrbwg {
  stop-color: var(--svg-color--564642, #564642);
}

.pko18bchz {
  stop-color: var(--svg-color--554542, #554542);
  stop-opacity: 0;
}

.qjo0o-q3r {
  stop-color: var(--svg-color--3f233b, #3F233B);
  stop-opacity: 0;
}

.qsx826m4r {
  stop-color: var(--svg-color--5a423e, #5A423E);
}

.r0z2q7brs {
  width: 5.927px;
  height: 10.097px;
  x: 5.71px;
  y: 12.064px;
  rx: 2.91px;
}

.rg3n2_b4b {
  stop-color: var(--svg-color--665150, #665150);
}

.s3xe04bqa {
  stop-color: var(--svg-color--4d312e, #4D312E);
}

.scg7r2b1k {
  stop-color: var(--svg-color--3f233b, #3F233B);
}

.sovlmvb0c {
  stop-color: var(--svg-color--574744, #574744);
}

.wrbe9si2s {
  width: 5.797px;
  height: 10.051px;
  x: 5.756px;
  y: 16.486px;
  rx: 2.899px;
}

.x-nzeubpg {
  stop-color: var(--svg-color--220d0f, #220D0F);
}

.xm34y9b_d {
  stop-color: var(--svg-color--65514f, #65514F);
}

.y737dyb-e {
  fill: var(--svg-color--402530, #402530);
  d: path("M22.791 18.984c-3.643-2.241-7.3-.668-8.247 0l-.84-1.082c5.38-2.562 8.246-.36 9.087 1.081");
}

.zjc5vidhp {
  stop-color: var(--svg-color--564744, #564744);
  stop-opacity: 0;
}

</style>
