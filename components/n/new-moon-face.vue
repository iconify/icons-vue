<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<radialGradient id="SVGu26KQcKw" cx="63.55" cy="56.074" r="68.672" gradientUnits="userSpaceOnUse"><stop offset=".306" class="sg0ufbcjk"/><stop offset=".472" class="f0litgtuj"/><stop offset=".749" class="ln474abdv"/><stop offset=".843" class="qphb2bcvg"/></radialGradient><circle fill="url(#SVGu26KQcKw)" class="wa-xljbbr"/><radialGradient id="SVGK3frkbdG" cx="63.702" cy="50.155" r="85.604" gradientUnits="userSpaceOnUse"><stop offset=".762" class="vhzm_fb8w"/><stop offset="1" class="y6l_wgbrq"/></radialGradient><circle fill="url(#SVGK3frkbdG)" class="wa-xljbbr"/><path class="yb-_gp-6z"/><path class="gcojaibqx"/><radialGradient id="SVGRIBXWciY" cx="91.892" cy="62.842" r="16.37" gradientTransform="matrix(.9201 -.3918 .3131 .7354 -12.333 52.628)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="fs8l-kj-i"/></radialGradient><path fill="url(#SVGRIBXWciY)" class="m7434abwm"/><radialGradient id="SVGMnGldvDm" cx="-2357.148" cy="63.126" r="16.135" gradientTransform="matrix(-.9201 -.3918 -.3131 .7354 -2108.489 -906.767)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="fs8l-kj-i"/></radialGradient><path fill="url(#SVGMnGldvDm)" class="mjn72g35l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:new-moon-face" /></template>
<style>
.f0litgtuj {
  stop-color: var(--svg-color--5989a1, #5989a1);
}

.fs8l-kj-i {
  stop-color: var(--svg-color--fff9b9, #fff9b9);
  stop-opacity: 0;
}

.gcojaibqx {
  fill: var(--svg-color--274c5e, #274c5e);
  d: path("M61.8 93.24c-.72.21-1.57.75-1.39 1.48c.06.24.22.43.4.6c.57.52 1.31.82 2.05 1.01c2.09.53 4.36.17 6.25-.85c1.09-.59 4.57-3.19 3.8-4.83c-.62-1.33-3.01.52-3.94.91c-2.31.97-4.77.99-7.17 1.68m-3.12-20.98c-1.44-1.62-.11-2.46 1.47-1.98c2 .61 5.2.32 6.02-1.48c1.58-3.46-.39-5.41-2.84-11.39c-2.56-6.25.65-13.06 4.35-13.41c2.97-.28 1.98 1.27 1.05 1.93c-1.82 1.3-3.73 5.6-.8 10.42c4.99 8.19 5.4 12.12 2.42 15.98c-1.85 2.4-7.62 4.49-11.67-.07");
}

.ln474abdv {
  stop-color: var(--svg-color--457287, #457287);
}

.m7434abwm {
  d: path("M82.57 72.92c1.55 3.75 7.63 4.79 13.58 2.32c5.95-2.46 9.52-7.5 7.97-11.24c-1.55-3.75-7.63-4.79-13.58-2.32c-5.95 2.46-9.52 7.49-7.97 11.24");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.mjn72g35l {
  d: path("M49.43 72.92c-1.55 3.75-7.63 4.79-13.58 2.32c-5.95-2.46-9.52-7.5-7.97-11.24c1.55-3.75 7.63-4.79 13.58-2.32c5.95 2.46 9.52 7.49 7.97 11.24");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.qphb2bcvg {
  stop-color: var(--svg-color--3d687d, #3d687d);
}

.sg0ufbcjk {
  stop-color: var(--svg-color--6092ab, #6092ab);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vhzm_fb8w {
  stop-color: var(--svg-color--b2ebf2, #b2ebf2);
  stop-opacity: 0;
}

.wa-xljbbr {
  cx: 64px;
  cy: 64px;
  r: 60px;
}

.y6l_wgbrq {
  stop-color: var(--svg-color--e0f7fa, #e0f7fa);
}

.yb-_gp-6z {
  fill: var(--svg-color--212121, #212121);
  d: path("M85.49 59.81c1.53 1.25 4.18 1.39 6.42.44c2.66-1.14 3.87-2.9 3.91-5.65c.04-3.41-2.8-7.05-8.42-7.41c-9.26-.59-12.82 7.71-12.92 8.02c-.22.65.1 1.58 1.95.12c5.63-4.45 7.65-3.71 7.65-3.71s-3.24 4.37 1.41 8.19m-42.23 0c1.53 1.25 4.18 1.39 6.42.44c2.66-1.14 3.87-2.9 3.91-5.65c.04-3.41-2.8-7.05-8.42-7.41c-9.26-.59-12.82 7.71-12.92 8.02c-.22.65.1 1.58 1.95.12c5.63-4.45 7.65-3.71 7.65-3.71s-3.24 4.37 1.41 8.19m36.78 18.13l-.12-.07c-.6-.36-1.39-.29-1.92.16c-1.57 1.34-8.08 3.82-14.01 3.94c-5.93-.12-12.44-2.6-14.01-3.94c-.53-.45-1.31-.53-1.92-.16l-.12.07c-.76.46-.9 1.4-.37 2.08c2.06 2.58 7.52 6.46 16.41 6.59c8.89-.12 14.34-4.01 16.41-6.59c.56-.68.41-1.62-.35-2.08");
}

</style>
