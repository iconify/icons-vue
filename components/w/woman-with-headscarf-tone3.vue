<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<linearGradient id="SVGhDuP1cTZ" x1="64.005" x2="64.005" y1="33.621" y2="-35.893" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="aplh-7tkj"/><stop offset=".782" class="car3btb1d"/><stop offset="1" class="wk_lp_wlk"/></linearGradient><path fill="url(#SVGhDuP1cTZ)" class="w6ltpr7fz"/><path class="t31-ip77z"/><g class="h3iawzbwl"><ellipse class="plon4fbvg"/><ellipse class="kt8gv4bop"/></g><path class="htxrg_7to"/><path class="kfi577bhp"/><path class="h15irknot"/><linearGradient id="SVGloFL8dLY" x1="64.37" x2="64.37" y1="116.53" y2="19.398" gradientTransform="translate(0 2)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="obetxer3p"/><stop offset=".533" class="rewhw8dsf"/><stop offset="1" class="f5oqg0b0c"/></linearGradient><path fill="url(#SVGloFL8dLY)" class="l_pe3ab9o"/><path class="m5hyceb-x"/><path class="ofcg3bcvz"/><path class="ht4rcil5t"/><path class="wg3zsj1nt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:woman-with-headscarf-tone3" /></template>
<style>
.aplh-7tkj {
  stop-color: var(--svg-color--616161, #616161);
}

.car3btb1d {
  stop-color: var(--svg-color--323232, #323232);
}

.f5oqg0b0c {
  stop-color: var(--svg-color--8a29b0, #8a29b0);
}

.h15irknot {
  fill: var(--svg-color--5d4037, #5d4037);
  d: path("M72.05 76.14c-3.15 1.87-13.46 1.87-16.61 0c-1.81-1.07-3.65.57-2.9 2.21c.74 1.61 6.37 5.36 11.23 5.36c4.87 0 10.42-3.75 11.16-5.36c.75-1.64-1.07-3.29-2.88-2.21");
}

.h3iawzbwl {
  fill: var(--svg-color--49362e, #49362e);
}

.ht4rcil5t {
  fill: var(--svg-color--a23dc9, #a23dc9);
  d: path("M65.59 16.43S51.34 12 38.34 26c-12.47 13.43-8.58 39.09-8.58 39.09s-.14-21.42 14.58-35.42c12.87-12.25 21.25-13.24 21.25-13.24");
}

.htxrg_7to {
  fill: var(--svg-color--99674f, #99674f);
  d: path("M67.96 68.05c-.1-.04-.21-.07-.32-.08h-6.99c-.11.01-.21.04-.32.08c-.63.26-.98.91-.68 1.61s1.69 2.66 4.49 2.66s4.19-1.96 4.49-2.66c.31-.69-.04-1.35-.67-1.61");
}

.kfi577bhp {
  fill: var(--svg-color--613e31, #613e31);
  d: path("M55.78 49.82c-.93-1.23-3.07-3.01-7.23-3.01s-6.31 1.79-7.23 3.01c-.41.54-.31 1.17-.02 1.55c.26.35 1.04.68 1.9.39s2.54-1.16 5.35-1.18c2.81.02 4.49.89 5.35 1.18s1.64-.03 1.9-.39c.29-.38.39-1.01-.02-1.55m32.14 0c-.93-1.23-3.07-3.01-7.23-3.01s-6.31 1.79-7.23 3.01c-.41.54-.31 1.17-.02 1.55c.26.35 1.04.68 1.9.39s2.54-1.16 5.35-1.18c2.81.02 4.49.89 5.35 1.18s1.64-.03 1.9-.39c.28-.38.39-1.01-.02-1.55");
}

.kt8gv4bop {
  cx: 80.58px;
  cy: 58.87px;
  rx: 4.87px;
  ry: 5.04px;
}

.l_pe3ab9o {
  d: path("M24.5 108.51c.96 7.03 5.72 12.21 13.67 15.45h43.06c29.16-15.63 24.38-71.5 23.99-76.45C103.36 23.55 92.06 4.01 64.03 4C35.99 4.01 23 23.68 23 47.17c0 21.99 4.06 37.42 10.97 47.5c-6.38 2.8-10.22 8.34-9.47 13.84m39.53-71.82s25.76 12.63 29.89 31.25c0 0-8.89 24.4-29.89 24.4s-29.89-24.4-29.89-24.4c3.55-18.74 29.89-31.25 29.89-31.25");
}

.m5hyceb-x {
  fill: var(--svg-color--541e69, #541e69);
  d: path("M32.85 98.13s.47 12.25 14.16 18.94c17.53 8.57 33.59.78 40.69-7.18c9.93-11.14 9.35-30.83 9.35-30.83s-1.34 19.51-15.75 29.63c-10.11 7.1-22.17 8.03-32.99 3.75c-13.49-5.33-15.46-14.31-15.46-14.31");
}

.obetxer3p {
  stop-color: var(--svg-color--792d96, #792d96);
}

.ofcg3bcvz {
  fill: var(--svg-color--48145c, #48145c);
  d: path("M46.77 100.28c-12.6-4.18-21.23-26.71-21.23-26.71s4.52 32.34 29.65 36.64c31.49 5.38 46.15-27.46 48.76-39.72c6.4-35.65-8.89-52.95-8.89-52.95s14.16 29.28 3.6 54.96c-6 14.62-18.61 38.83-51.89 27.78");
}

.plon4fbvg {
  cx: 47.72px;
  cy: 58.87px;
  rx: 4.87px;
  ry: 5.04px;
}

.rewhw8dsf {
  stop-color: var(--svg-color--842aa6, #842aa6);
}

.t31-ip77z {
  fill: var(--svg-color--ba8d68, #ba8d68);
  d: path("M63.82 94.45c-2.38 0-5.07-.52-7.81-1.48c-11.72-4.14-25.39-16.89-25.39-39.16c0-29.68 17.89-40.21 33.21-40.21s33.21 10.53 33.21 40.21c0 22.3-13.7 35.03-25.43 39.17c-2.75.96-5.43 1.47-7.79 1.47");
}

.w6ltpr7fz {
  d: path("M64.13 94.45H64c-25.65.03-51.46 7.55-51.46 25.44v4.07h102.93v-4.07c-.01-16.87-25.57-25.44-51.34-25.44");
}

.wg3zsj1nt {
  fill: var(--svg-color--541e69, #541e69);
  d: path("M88.23 38.05c9.86 13.59 9.05 31.86 9.05 31.86s5.17-20.84-4.83-34.76c-7.88-10.97-20.64-11.41-20.64-11.41s7.15 1.53 16.42 14.31M43.83 87.6c16.09 12.82 34.91 6.88 34.91 6.88s-20.9 11.66-38.14-3.77c-10.08-9.02-10.45-24.07-10.45-24.07s3.88 13.14 13.68 20.96");
}

.wk_lp_wlk {
  stop-color: var(--svg-color--212121, #212121);
}

</style>
