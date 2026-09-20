<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVGExDjCbKO" cx="63.57" cy="23.33" r="56.96" fx="63.57" fy="23.33" gradientTransform="matrix(1 0 0 -1 0 88)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="r_-r4-l8z"/><stop offset=".92" class="pilgl2bji"/><stop offset="1" class="m_j2at8le"/></radialGradient><radialGradient id="SVGzaduJdxB" cx="14.75" cy="339.25" r="19.44" fx="14.75" fy="339.25" gradientTransform="matrix(.98 0 0 .93 12.78 -250.94)" gradientUnits="userSpaceOnUse"><stop offset="0" class="yoxk-9bbp"/><stop offset=".08" class="f1onapbfe"/><stop offset=".22" class="z57g3krpe"/><stop offset=".39" class="jvczk2bjd"/><stop offset=".59" class="vtpyccc7v"/><stop offset=".81" class="v0r8aumlw"/><stop offset=".9" class="gg0prabeh"/></radialGradient><radialGradient id="SVGdYy33bIM" cx="89.82" r="19.44" fx="89.82" href="#SVGzaduJdxB"/></defs><path fill="url(#SVGExDjCbKO)" class="k6eoohdss"/><path class="fbbgsnb2b"/><g class="wj4kgr0on"><circle fill="url(#SVGzaduJdxB)" class="fmib-qh5v"/><circle fill="url(#SVGdYy33bIM)" class="u7_hoo7oq"/></g><path class="gu0ny3bkm"/><g class="wj4kgr0on"><path class="x1_d8196i"/><path class="b7tcxpzwa"/><path class="yzamclbdy"/></g><g class="wj4kgr0on"><path class="pbkokowfa"/><path class="nfb-u02po"/><path class="msjsqdb5f"/></g><g class="wj4kgr0on"><path class="nhl06vckr"/><path class="g9qkclbna"/><path class="gfy1ttqyv"/></g><path class="maiooqbnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:smiling-face-with-hearts" /></template>
<style>
.b7tcxpzwa {
  fill: var(--svg-color--c62828, #c62828);
  d: path("M110.74 2.99s-1.73.71-2.41 1.38c0 0 4.76-.49 9.07 1.97c2.84 1.62 5.48 4.52 6.44 9.69c2.07 11.2-6.77 25.9-7.45 26.98c.91-1.21 12.4-16.79 10.73-29.26C125.71 3.2 116.08.85 110.74 2.99m-7.01 11.75c-.69-.83-1.51-1.55-2.01-1.95c-2.52-2.02-4.62-2.53-7.34-2.29s-5.15 1.76-5.15 1.76s2.64-1 6.39.79c1.97.94 3.7 2.34 5.15 3.98c.52.59 1.04 1.23 1.74 1.58s1.68.3 2.16-.33c.76-1.02.04-2.39-.93-3.54Z");
}

.f1onapbfe {
  stop-color: var(--svg-color--rgba-237-119-112-96, rgba(237, 119, 112, .96));
  stop-opacity: 0.96;
}

.fbbgsnb2b {
  fill: var(--svg-color--eb8f00, #eb8f00);
  d: path("M111.46 31.44c5.33 8.6 8.11 18.84 8.11 30.23c0 16.9-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5c-18.06 0-37.04-7.35-48.18-22.94c10.76 17.66 30.99 25.94 50.18 25.94c15.4 0 29.8-5.2 40.4-14.5c11.5-10.2 17.6-24.5 17.6-41.4c0-12.74-3.47-24.06-10.11-33.23");
}

.fmib-qh5v {
  cx: 27.22px;
  cy: 64.6px;
  r: 17.5px;
  opacity: var(--svg-opacity--0-8, 0.8);
}

.g9qkclbna {
  fill: var(--svg-color--c62828, #c62828);
  d: path("M27.95 61.54s-1.74.68-2.44 1.33c0 0 4.77-.38 9.03 2.17c2.8 1.68 5.38 4.64 6.22 9.83c1.82 11.25-7.34 25.75-8.04 26.81c.93-1.19 12.77-16.52 11.37-29.02c-1.18-10.58-10.75-13.14-16.14-11.12m-7.26 11.59c-.67-.84-1.47-1.58-1.97-1.99c-2.48-2.07-4.57-2.63-7.29-2.45s-5.19 1.65-5.19 1.65s2.66-.94 6.37.93c1.95.98 3.65 2.42 5.06 4.09c.51.6 1.01 1.25 1.71 1.61s1.68.34 2.16-.28c.78-1 .09-2.39-.85-3.56");
}

.gfy1ttqyv {
  fill: var(--svg-color--ff847a, #ff847a);
  d: path("M4.19 79.94c.12-2.65 1.15-5.87 4.35-5.95c1.7-.04 3.34 2.17 2.7 4.18c-1.07 3.4-.36 4.59.06 5.71c.51 1.35 1.28 2.83.68 4.14s-1.93 1.37-3.62.19c-.35-.25-4.41-2.86-4.18-8.27Z");
}

.gg0prabeh {
  stop-color: var(--svg-color--ed7770, #ed7770);
  stop-opacity: 0;
}

.gu0ny3bkm {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M100.66 66.81C90.39 72.77 77.7 76.3 63.97 76.3s-26.42-3.53-36.69-9.49c-1.89-1.09-3.87 1.27-2.46 2.92c9.3 10.87 23.38 17.8 39.15 17.8s29.85-6.93 39.15-17.8c1.42-1.66-.57-4.02-2.46-2.92");
}

.jvczk2bjd {
  stop-color: var(--svg-color--rgba-237-119-112-68, rgba(237, 119, 112, .68));
  stop-opacity: 0.68;
}

.k6eoohdss {
  d: path("M63.57 120.57c-27.9 0-58-17.5-58-55.9s30.1-55.9 58-55.9c15.5 0 29.8 5.1 40.4 14.4c11.5 10.2 17.6 24.6 17.6 41.5s-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5");
}

.m_j2at8le {
  stop-color: var(--svg-color--f4a223, #f4a223);
}

.maiooqbnk {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M49.38 45.65c-1.08-1.32-2.53-3.18-4.3-3.54c-.04 0-.08-.01-.12 0h-.04h.27c-1.53-.22-3.63 2.19-4.7 3.48c-1.3 1.76-3.92 2.18-5.73.86c-2.55-2.05-1.34-4.63.04-7.35c1.52-2.96 5.54-5.93 9.31-6.04c.92-.09 1.88-.01 2.79.15c4.97.84 8.8 5.23 9.59 9.75c.69 3.89-4.89 5.72-7.11 2.69m37.83 0c-.13-.18-.34-.44-.57-.73c-1.01-1.05-2.23-2.55-3.73-2.81c-.04 0-.08-.01-.12 0h-.04h.27l-.54.02c-.14 0-.04.01-.04.01h.07c.08-.03 0 0-.02 0c-.03 0-.07 0-.11.02c-1.72.47-3.24 2.51-4.28 3.69c-2.27 2.82-7.61.94-6.95-2.81c.75-4.74 5.38-9.76 10.8-9.98c5.96-.59 11.51 4.46 12.38 9.91c.69 3.89-4.89 5.72-7.11 2.69Z");
}

.msjsqdb5f {
  fill: var(--svg-color--ff847a, #ff847a);
  d: path("M87.35 89.84c2.2-1.48 5.4-2.56 7.37-.04c1.04 1.34.24 3.97-1.75 4.66c-3.37 1.15-3.91 2.44-4.56 3.44c-.78 1.21-1.52 2.71-2.93 3s-2.24-.74-2.3-2.8c-.01-.43-.32-5.24 4.17-8.27Z");
}

.nfb-u02po {
  fill: var(--svg-color--c62828, #c62828);
  d: path("M116.27 98.03s-1.58-1-2.52-1.18c0 0 3.14 3.61 3.62 8.55c.31 3.26-.54 7.09-4.21 10.85c-7.96 8.15-25.07 9.4-26.34 9.46c1.51.05 20.87.46 30.1-8.09c7.81-7.24 4.18-16.45-.65-19.59m-13.64 1.05c.28-1.04.4-2.12.44-2.76c.19-3.22-.6-5.24-2.36-7.32c-1.77-2.08-4.41-3.2-4.41-3.2s2.33 1.58 3.03 5.68c.37 2.15.22 4.37-.29 6.5c-.18.77-.41 1.55-.28 2.33s.72 1.55 1.51 1.57c1.27.03 1.97-1.34 2.36-2.8");
}

.nhl06vckr {
  fill: var(--svg-color--f44336, #f44336);
  d: path("M27.96 61.54c-7.12 2.67-7.92 10.68-7.92 10.68s-4.52-5.11-10.83-3.14C1.62 71.45-2.34 79.45 3.57 88.3c6.76 10.12 29.09 13.45 29.09 13.45s12.89-16.09 11.44-29.1c-1.18-10.58-10.75-13.14-16.14-11.12Z");
}

.pbkokowfa {
  fill: var(--svg-color--f44336, #f44336);
  d: path("M116.27 98.03c-6.38-4.14-13.3-.02-13.3-.02s1.43-6.67-3.91-10.58c-6.41-4.7-15.2-3.13-18.81 6.88c-4.13 11.45 6.46 31.39 6.46 31.39s20.6.81 30.2-8.09c7.81-7.24 4.18-16.45-.65-19.59Z");
}

.pilgl2bji {
  stop-color: var(--svg-color--f7c02b, #f7c02b);
}

.r_-r4-l8z {
  stop-color: var(--svg-color--fde030, #fde030);
}

.u7_hoo7oq {
  cx: 100.72px;
  cy: 64.6px;
  r: 17.5px;
  opacity: var(--svg-opacity--0-8, 0.8);
}

.v0r8aumlw {
  stop-color: var(--svg-color--rgba-237-119-112-13, rgba(237, 119, 112, .13));
  stop-opacity: 0.13;
}

.vtpyccc7v {
  stop-color: var(--svg-color--rgba-237-119-112-43, rgba(237, 119, 112, .43));
  stop-opacity: 0.43;
}

.wj4kgr0on {
  stroke-width: var(--svg-stroke-width--0px, 0px);
}

.x1_d8196i {
  fill: var(--svg-color--f44336, #f44336);
  d: path("M110.74 2.99c-7.06 2.83-7.68 10.86-7.68 10.86s-4.63-5.01-10.9-2.9c-7.53 2.54-11.32 10.62-5.22 19.34c6.98 9.97 29.38 12.81 29.38 12.81s12.53-16.37 10.79-29.35C125.7 3.2 116.07.85 110.73 2.99Z");
}

.yoxk-9bbp {
  stop-color: var(--svg-color--ed7770, #ed7770);
}

.yzamclbdy {
  fill: var(--svg-color--ff847a, #ff847a);
  d: path("M87.38 21.91c.06-2.65 1.03-5.89 4.22-6.04c1.7-.08 3.39 2.1 2.8 4.12c-1 3.42-.26 4.6.19 5.71c.53 1.34 1.34 2.8.77 4.12s-1.9 1.41-3.61.27c-.36-.24-4.47-2.76-4.36-8.17Z");
}

.z57g3krpe {
  stop-color: var(--svg-color--rgba-237-119-112-85, rgba(237, 119, 112, .85));
  stop-opacity: 0.85;
}

</style>
