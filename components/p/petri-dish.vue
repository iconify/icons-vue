<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="l-eh3gcpp"/><path class="iv_38pb1w"/><linearGradient id="SVGbyp5ceno" x1="58.437" x2="148.641" y1="109.998" y2="109.998" gradientUnits="userSpaceOnUse"><stop offset="0" class="thwcjab1s"/><stop offset="1" class="d-qlar4kc"/></linearGradient><path fill="url(#SVGbyp5ceno)" class="sinrdmbqv"/><ellipse class="oi813ebtn"/><path class="j-87xdbng"/><radialGradient id="SVGF7nDdo2O" cx="70.472" cy="92.716" r="11.755" gradientTransform="matrix(1 0 0 .3944 0 53.42)" gradientUnits="userSpaceOnUse"><stop offset=".559" class="zs84mcc3v"/><stop offset="1" class="rdxiesd1b"/></radialGradient><path fill="url(#SVGF7nDdo2O)" class="whw3-wj_w"/><radialGradient id="SVGvSnaneen" cx="30.571" cy="100.457" r="14.461" gradientTransform="matrix(1 0 0 .3944 0 55.812)" gradientUnits="userSpaceOnUse"><stop offset=".555" class="zs84mcc3v"/><stop offset="1" class="rdxiesd1b"/></radialGradient><path fill="url(#SVGvSnaneen)" class="cwgpt0boh"/><path class="p9ehwthwo"/><radialGradient id="SVGyfKF4dRw" cx="92.622" cy="95.968" r="20.835" gradientTransform="matrix(.9185 0 0 .3707 5.59 57.796)" gradientUnits="userSpaceOnUse"><stop offset=".632" class="tvckc8boy"/><stop offset="1" class="shkucpbrb"/></radialGradient><path fill="url(#SVGyfKF4dRw)" class="jduwy8ygk"/><path class="p7koy0qtt"/><ellipse class="qjfsanbob"/><ellipse class="glnuovb2w"/><ellipse class="tvv9xhb5m"/><path class="cfe16tbje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:petri-dish" /></template>
<style>
.cfe16tbje {
  fill: var(--svg-color--fff, #fff);
  d: path("M31.62 121.11c-13.72-2.13-19.26-4.87-19.26-4.87V78.15s8.79 2.09 19.26 2.94z");
  opacity: var(--svg-opacity--0-46, 0.46);
}

.cwgpt0boh {
  d: path("M42.53 98.89c0 2.13-5.37 2.73-11.99 2.73s-11.99-.6-11.99-2.73s5.37-4.99 11.99-4.99s11.99 2.86 11.99 4.99");
}

.d-qlar4kc {
  stop-color: var(--svg-color--b02424, #b02424);
}

.glnuovb2w {
  cx: 51.17px;
  cy: 104.64px;
  fill: var(--svg-color--ffebee, #ffebee);
  rx: 3.66px;
  ry: 1.17px;
}

.iv_38pb1w {
  fill: var(--svg-color--fff, #fff);
  d: path("M63.94 63.77c34.1 0 56.84 3.47 56.84 7.75s-25.97 7.75-56.84 7.75S7.22 75.8 7.22 71.52s20.2-7.75 56.72-7.75m0-3.23c-17.48 0-32.19.8-42.52 2.3C9.05 64.65 4 67.17 4 71.52c0 3.61 3.33 6.47 19.57 8.68c10.91 1.48 25.25 2.3 40.36 2.3c15.13 0 29.48-.82 40.42-2.3c16.3-2.21 19.64-5.07 19.64-8.68c0-4.32-5.33-6.83-18.4-8.68c-10.52-1.48-25.31-2.3-41.65-2.3");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.j-87xdbng {
  fill: var(--svg-color--e8f5e9, #e8f5e9);
  d: path("M42.5 98.72c-.27-2.11-5.51-4.82-11.97-4.82c-5.03 0-9.33 1.65-11.11 3.37c0 0-3.47.54-5.4 1.07c-1.21.33-1.59 1.39-.35 1.87c1.66.64 3.21.17 5 .99c.8.37 1.07 1.63 4.98 1.97c1.06.09 2.13.12 3.19.14c1.25.03 2.53.05 3.75.37c.48.13 2.63.96 4.26.7c3.04-.5 3.05-1.16 3.76-1.51c.68-.33 2.18-.72 2.93-.76c1.29-.07 5.49-.99 5.49-1.97c-.01-.87-2.05-.69-4.53-1.42m36.95-7.26c-1.47-1.39-4.94-2.71-9-2.71c-3.74 0-6.98 1.12-8.62 2.38c-2.45.5-4 1.22-4 2.03c0 1.51 5.43 2.74 12.13 2.74s12.13-1.22 12.13-2.74c-.01-.65-1-1.24-2.64-1.7");
}

.jduwy8ygk {
  d: path("M105.85 97.33c0 2.77-6.82 5.01-15.23 5.01s-15.23-2.24-15.23-5.01s6.82-6.18 15.23-6.18s15.23 3.42 15.23 6.18");
}

.l-eh3gcpp {
  fill: var(--svg-color--4fc3f7, #4fc3f7);
  d: path("M124 71.52c0-4.32-5.33-6.83-18.4-8.68c-10.53-1.48-25.32-2.3-41.66-2.3c-17.48 0-32.19.8-42.52 2.3C9.05 64.65 4 67.17 4 71.52l.01 37.69c0 7.33 26.83 14.29 59.92 14.29c33.1 0 59.92-6.96 59.92-14.29c.01 0 .15-37.29.15-37.69");
  opacity: var(--svg-opacity--0-6, 0.6);
}

.oi813ebtn {
  cx: 63.94px;
  cy: 100.11px;
  fill: var(--svg-color--ff5252, #ff5252);
  rx: 57.17px;
  ry: 9.32px;
}

.p7koy0qtt {
  fill: none;
  stroke: var(--svg-color--fff, #fff);
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--3-067px, 3.067px);
  d: path("M11.99 76.29s5.61 1.91 17.82 3.1");
}

.p9ehwthwo {
  fill: var(--svg-color--f3e5f5, #f3e5f5);
  d: path("M111.34 98.68c-.2.16-.45.29-.58.46c-.14.18-.14.38-.2.58c-.28.96-2.02 1.64-3.78 1.97s-3.67.44-5.38.85c-1.82.44-3.4 1.21-5.38 1.33c-1.9.12-3.75-.33-5.66-.32c-1.95.01-3.91-.14-5.88-.15c-2.09-.01-3.17.49-6.36.04c-1.47-.21-2.29-1.65-3.8-1.97c-1.25-.26-3.69-.58-4.37-1.72c-.65-1.09.22-1.96 2.34-2.89c1.28-.56 2.83-1.17 4.45-1.55c4.46-1.05 9.53-1.4 14.38-1.4c4.56 0 9.26.32 13.51 1.21c2.07.43 8.53 2.01 6.76 3.53c-.02 0-.04.01-.05.03");
}

.qjfsanbob {
  cx: 48.4px;
  cy: 95.02px;
  fill: var(--svg-color--ffebee, #ffebee);
  rx: 4.28px;
  ry: 1.37px;
}

.rdxiesd1b {
  stop-color: var(--svg-color--00bfa5, #00bfa5);
  stop-opacity: 0;
}

.shkucpbrb {
  stop-color: var(--svg-color--ea80fc, #ea80fc);
  stop-opacity: 0;
}

.sinrdmbqv {
  d: path("M121.11 100.47v6.39c0 6.99-25.6 12.66-57.17 12.66s-57.17-5.67-57.17-12.66v-6.39z");
}

.thwcjab1s {
  stop-color: var(--svg-color--c62828, #c62828);
}

.tvckc8boy {
  stop-color: var(--svg-color--ea80fc, #ea80fc);
}

.tvv9xhb5m {
  cx: 60.69px;
  cy: 101.3px;
  fill: var(--svg-color--ffebee, #ffebee);
  rx: 6.65px;
  ry: 2.13px;
}

.whw3-wj_w {
  d: path("M80.19 92.8c0 1.73-4.36 2.22-9.75 2.22s-9.75-.49-9.75-2.22s4.36-4.05 9.75-4.05s9.75 2.32 9.75 4.05");
}

.zs84mcc3v {
  stop-color: var(--svg-color--00bfa5, #00bfa5);
}

</style>
