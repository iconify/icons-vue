<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iuBDQIo)"><path fill="url(#iveYzqb)" class="wohptmbnk"/></g><path fill="url(#iLrMuQt)" class="wohptmbnk"/><path fill="url(#ikVi9lr)" class="wohptmbnk"/><path fill="url(#i8JUuld)" class="wohptmbnk"/><g filter="url(#iMzCA8d)"><path class="jdud5-leg"/></g><g filter="url(#ifoj0Kr)"><path class="yg8v-7bcr"/></g><rect fill="url(#i2ptMQd)" transform="rotate(-90 6.703 21.013)" class="ak1scibmc"/><rect fill="url(#ibuhCpc)" transform="rotate(-90 6.703 21.013)" class="ak1scibmc"/><rect fill="url(#iAJR3fc)" transform="rotate(-90 6.703 21.013)" class="ak1scibmc"/><rect fill="url(#iDNbLIk)" transform="rotate(-90 6.703 21.013)" class="ak1scibmc"/><rect fill="url(#iVyT0vd)" transform="rotate(-90 6.703 21.013)" class="ak1scibmc"/><rect fill="url(#iMxM6Xb)" transform="rotate(-90 7 7.81)" class="ofln3ei7x"/><rect fill="url(#ilSZIac)" transform="rotate(-90 7 7.81)" class="ofln3ei7x"/><rect fill="url(#idYb0Yd)" transform="rotate(-90 7 7.81)" class="ofln3ei7x"/><rect fill="url(#imcq1Ad)" transform="rotate(-90 7 7.81)" class="ofln3ei7x"/><rect fill="url(#iieDZQc)" transform="rotate(-90 5.71 12.064)" class="r0z2q7brs"/><rect fill="url(#iBAAgie)" transform="rotate(-90 5.71 12.064)" class="r0z2q7brs"/><rect fill="url(#ivPd7Nc)" transform="rotate(-90 5.71 12.064)" class="r0z2q7brs"/><rect fill="url(#ilKaO5n)" transform="rotate(-90 5.71 12.064)" class="r0z2q7brs"/><rect fill="url(#ir88KPe)" transform="rotate(-90 5.756 16.486)" class="wrbe9si2s"/><rect fill="url(#i33HL3c)" transform="rotate(-90 5.756 16.486)" class="wrbe9si2s"/><rect fill="url(#iO2y47d)" transform="rotate(-90 5.756 16.486)" class="wrbe9si2s"/><rect fill="url(#iy0WbMe)" transform="rotate(-90 5.756 16.486)" class="wrbe9si2s"/><path fill="url(#i3YTIfd)" class="ew73jabtg"/><path fill="url(#iG8pHBb)" class="ew73jabtg"/><defs><radialGradient id="iLrMuQt" cx="0" cy="0" r="1" gradientTransform="matrix(-6.38547 3.48292 -3.99685 -7.3277 25.507 7.314)" gradientUnits="userSpaceOnUse"><stop class="j9m4xybel"/><stop offset="1" class="q9uq8fznr"/></radialGradient><radialGradient id="ikVi9lr" cx="0" cy="0" r="1" gradientTransform="matrix(4.64396 0 0 9.96517 19.896 26.084)" gradientUnits="userSpaceOnUse"><stop class="ji-3ejbnq"/><stop offset="1" class="qyeklgbxy"/></radialGradient><radialGradient id="i8JUuld" cx="0" cy="0" r="1" gradientTransform="scale(12.9389 20.0228)rotate(90 .413 .923)" gradientUnits="userSpaceOnUse"><stop offset=".902" class="yvv0xrtpr"/><stop offset=".993" class="a44etnbom"/></radialGradient><radialGradient id="iAJR3fc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.58086 2.00356 0 10.256 28.655)" gradientUnits="userSpaceOnUse"><stop class="noia57awg"/><stop offset="1" class="nzk0xib5y"/></radialGradient><radialGradient id="iDNbLIk" cx="0" cy="0" r="1" gradientTransform="matrix(-.9313 0 0 -4.89838 11.216 24.948)" gradientUnits="userSpaceOnUse"><stop class="rkcfwccvv"/><stop offset="1" class="zdwn_kbqs"/></radialGradient><radialGradient id="iVyT0vd" cx="0" cy="0" r="1" gradientTransform="matrix(-.17279 -7.31561 8.00204 -.189 9.594 28.328)" gradientUnits="userSpaceOnUse"><stop offset=".808" class="ru9-1db2p"/><stop offset="1" class="hzikybb2w"/></radialGradient><radialGradient id="ilSZIac" cx="0" cy="0" r="1" gradientTransform="matrix(1.06838 0 0 4.40184 7.885 12.125)" gradientUnits="userSpaceOnUse"><stop class="tufmqx57s"/><stop offset="1" class="pi1jg_b_e"/></radialGradient><radialGradient id="idYb0Yd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.78495 2.38236 0 10.787 14.998)" gradientUnits="userSpaceOnUse"><stop class="pvzn4cc5o"/><stop offset="1" class="tn9ad54yi"/></radialGradient><radialGradient id="imcq1Ad" cx="0" cy="0" r="1" gradientTransform="matrix(-.16817 -7.16786 7.78679 -.18269 9.815 14.978)" gradientUnits="userSpaceOnUse"><stop offset=".808" class="ru9-1db2p"/><stop offset="1" class="hzikybb2w"/></radialGradient><radialGradient id="iBAAgie" cx="0" cy="0" r="1" gradientTransform="matrix(1.125 0 0 5.04687 6.642 17.011)" gradientUnits="userSpaceOnUse"><stop class="tufmqx57s"/><stop offset="1" class="pi1jg_b_e"/></radialGradient><radialGradient id="ivPd7Nc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.68226 2.10732 0 9.236 20.227)" gradientUnits="userSpaceOnUse"><stop class="pvzn4cc5o"/><stop offset="1" class="tn9ad54yi"/></radialGradient><radialGradient id="ilKaO5n" cx="0" cy="0" r="1" gradientTransform="matrix(-.17705 -8.21822 8.20018 -.17667 8.674 20.282)" gradientUnits="userSpaceOnUse"><stop offset=".808" class="ru9-1db2p"/><stop offset="1" class="hzikybb2w"/></radialGradient><radialGradient id="i33HL3c" cx="0" cy="0" r="1" gradientTransform="matrix(2.38035 0 0 7.9345 5.5 20.031)" gradientUnits="userSpaceOnUse"><stop class="d1t1l3d8i"/><stop offset="1" class="xbkpm9uuu"/></radialGradient><radialGradient id="iO2y47d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.6702 2.06121 0 9.205 24.613)" gradientUnits="userSpaceOnUse"><stop class="pvzn4cc5o"/><stop offset="1" class="tn9ad54yi"/></radialGradient><radialGradient id="iy0WbMe" cx="0" cy="0" r="1" gradientTransform="matrix(-.17323 -8.18127 8.02085 -.16983 8.655 24.668)" gradientUnits="userSpaceOnUse"><stop offset=".808" class="ru9-1db2p"/><stop offset="1" class="hzikybb2w"/></radialGradient><radialGradient id="iG8pHBb" cx="0" cy="0" r="1" gradientTransform="matrix(1.49778 1.02092 -2.22839 3.26927 18.6 27.254)" gradientUnits="userSpaceOnUse"><stop offset=".55" class="zbidbobyw"/><stop offset="1" class="d01sm8_dc"/></radialGradient><linearGradient id="iveYzqb" x1="26.587" x2="12.093" y1="8.105" y2="29.819" gradientUnits="userSpaceOnUse"><stop class="cj8vqlbqv"/><stop offset="1" class="eil8rtsaf"/></linearGradient><linearGradient id="i2ptMQd" x1="9.595" x2="9.595" y1="21.013" y2="30" gradientUnits="userSpaceOnUse"><stop class="cxkpetd4t"/><stop offset="1" class="wq0-0ttrn"/></linearGradient><linearGradient id="ibuhCpc" x1="6.35" x2="8.227" y1="25.506" y2="25.506" gradientUnits="userSpaceOnUse"><stop class="qjwlz_y8r"/><stop offset="1" class="t9w0ocbqr"/></linearGradient><linearGradient id="iMxM6Xb" x1="8.345" x2="10.69" y1="8.718" y2="15.823" gradientUnits="userSpaceOnUse"><stop class="jx2xxduir"/><stop offset="1" class="yg9w17bun"/></linearGradient><linearGradient id="iieDZQc" x1="7.126" x2="10.001" y1="13.105" y2="21.105" gradientUnits="userSpaceOnUse"><stop class="jx2xxduir"/><stop offset="1" class="yg9w17bun"/></linearGradient><linearGradient id="ir88KPe" x1="8.654" x2="8.654" y1="16.486" y2="25.515" gradientUnits="userSpaceOnUse"><stop class="jx2xxduir"/><stop offset="1" class="yg9w17bun"/></linearGradient><linearGradient id="i3YTIfd" x1="20.307" x2="20.307" y1="26.044" y2="29.547" gradientUnits="userSpaceOnUse"><stop class="azvc5abwu"/><stop offset="1" class="nzk-vg2do"/></linearGradient><filter id="iuBDQIo" width="18.933" height="27.637" x="9.18" y="2.182" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.584314 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3042"/></filter><filter id="iMzCA8d" width="12.677" height="20.87" x="5.323" y="1.398" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3042" stdDeviation="1"/></filter><filter id="ifoj0Kr" width="12.088" height="5.26" x="12.203" y="15.224" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3042" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:thumbs-down" /></template>
<style>
.a44etnbom {
  stop-color: var(--svg-color--d87e83, #D87E83);
}

.ak1scibmc {
  width: 5.784px;
  height: 8.988px;
  x: 6.703px;
  y: 21.013px;
  rx: 2.892px;
}

.azvc5abwu {
  stop-color: var(--svg-color--fff598, #FFF598);
}

.cj8vqlbqv {
  stop-color: var(--svg-color--ffdb34, #FFDB34);
}

.cxkpetd4t {
  stop-color: var(--svg-color--ec9b2a, #EC9B2A);
}

.d01sm8_dc {
  stop-color: var(--svg-color--f4bbc8, #F4BBC8);
}

.d1t1l3d8i {
  stop-color: var(--svg-color--e48747, #E48747);
}

.eil8rtsaf {
  stop-color: var(--svg-color--e99a30, #E99A30);
}

.ew73jabtg {
  d: path("M19.107 29.082c.732-.6 1.2-1.511 1.2-2.532v-.19H18.83c-.005.196.005.7.085 1.14l.017.092c.082.444.176.953.175 1.49");
}

.ft5dv1b6b {
  fill: none;
}

.hzikybb2w {
  stop-color: var(--svg-color--d8a96f, #D8A96F);
}

.j9m4xybel {
  stop-color: var(--svg-color--fff163, #FFF163);
}

.jdud5-leg {
  fill: var(--svg-color--e69e12, #E69E12);
  d: path("M8.432 5.919c0 .468.122.907.336 1.283c-.855.428-1.445 1.34-1.445 2.394c0 .82.357 1.554.917 2.04a2.64 2.64 0 0 0-.878 1.98c0 1.04.585 1.936 1.431 2.35a2.65 2.65 0 0 0-.618 1.71c0 1.431 1.113 2.591 2.486 2.591h2.753c1.373 0 2.486-1.16 2.486-2.59a2.63 2.63 0 0 0-.891-1.988A2.63 2.63 0 0 0 16 13.616c0-.803-.35-1.52-.898-1.996c.55-.487.898-1.213.898-2.024c0-.728-.28-1.387-.736-1.866c.454-.459.736-1.1.736-1.811c0-1.393-1.083-2.521-2.419-2.521h-2.73c-1.336 0-2.42 1.128-2.42 2.52");
}

.ji-3ejbnq {
  stop-color: var(--svg-color--ffe14f, #FFE14F);
}

.jx2xxduir {
  stop-color: var(--svg-color--f2a430, #F2A430);
}

.noia57awg {
  stop-color: var(--svg-color--ffe160, #FFE160);
}

.nzk-vg2do {
  stop-color: var(--svg-color--ffc99f, #FFC99F);
}

.nzk0xib5y {
  stop-color: var(--svg-color--ffe160, #FFE160);
  stop-opacity: 0;
}

.ofln3ei7x {
  width: 5.629px;
  height: 8.806px;
  x: 7.001px;
  y: 7.81px;
  rx: 2.814px;
}

.pi1jg_b_e {
  stop-color: var(--svg-color--e69510, #E69510);
  stop-opacity: 0;
}

.pvzn4cc5o {
  stop-color: var(--svg-color--ffee65, #FFEE65);
}

.q9uq8fznr {
  stop-color: var(--svg-color--fff163, #FFF163);
  stop-opacity: 0;
}

.qjwlz_y8r {
  stop-color: var(--svg-color--d58191, #D58191);
}

.qyeklgbxy {
  stop-color: var(--svg-color--ffe14f, #FFE14F);
  stop-opacity: 0;
}

.r0z2q7brs {
  width: 5.927px;
  height: 10.097px;
  x: 5.71px;
  y: 12.064px;
  rx: 2.91px;
}

.rkcfwccvv {
  stop-color: var(--svg-color--df7f02, #DF7F02);
}

.ru9-1db2p {
  stop-color: var(--svg-color--d8a96f, #D8A96F);
  stop-opacity: 0;
}

.t9w0ocbqr {
  stop-color: var(--svg-color--d67f8d, #D67F8D);
  stop-opacity: 0;
}

.tn9ad54yi {
  stop-color: var(--svg-color--ffee65, #FFEE65);
  stop-opacity: 0;
}

.tufmqx57s {
  stop-color: var(--svg-color--e69510, #E69510);
}

.wohptmbnk {
  d: path("M20.307 26.55a3.268 3.268 0 1 1-6.536 0v-3.76q-.001-.482.071-.96q.03-.177.048-.35c.036-.369-.008-.85-.258-1.173l.598-.576a9.28 9.28 0 0 1-5.05-8.275c0-.979.15-1.922.43-2.808l.99-6.466h8.051v.002c4.973.107 8.962 3.35 8.962 9.272c0 3.481-1.667 6.284-4.189 7.864l.006.005c-.172.12-.374.24-.591.371l-.002.001c-.715.429-1.59.953-2.05 1.81c-.4.743-.478 1.949-.478 2.508l-.002-.001z");
}

.wq0-0ttrn {
  stop-color: var(--svg-color--ffc043, #FFC043);
}

.wrbe9si2s {
  width: 5.797px;
  height: 10.051px;
  x: 5.756px;
  y: 16.486px;
  rx: 2.899px;
}

.xbkpm9uuu {
  stop-color: var(--svg-color--e48747, #E48747);
  stop-opacity: 0;
}

.yg8v-7bcr {
  fill: var(--svg-color--f8a047, #F8A047);
  d: path("M22.791 18.984c-3.643-2.241-7.3-.668-8.247 0l-.84-1.082c5.38-2.562 8.246-.36 9.087 1.081");
}

.yg9w17bun {
  stop-color: var(--svg-color--ffce27, #FFCE27);
}

.yvv0xrtpr {
  stop-color: var(--svg-color--d87e83, #D87E83);
  stop-opacity: 0;
}

.zbidbobyw {
  stop-color: var(--svg-color--f4bbc8, #F4BBC8);
  stop-opacity: 0;
}

.zdwn_kbqs {
  stop-color: var(--svg-color--df7f02, #DF7F02);
  stop-opacity: 0;
}

</style>
