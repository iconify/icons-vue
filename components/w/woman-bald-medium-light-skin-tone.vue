<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<linearGradient id="SVGnbrtHc8z" x1="64" x2="64" y1="35.675" y2="3.021" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="xb94qyb-t"/><stop offset=".705" class="ci_fo_bpd"/><stop offset="1" class="u3kz4vb7l"/></linearGradient><path fill="url(#SVGnbrtHc8z)" class="tur50ibnn"/><path class="zdf6xpx0m"/><path class="bobtrp_3e"/><g class="qp89kubki"><ellipse class="i2mcs1bjm"/><ellipse class="rk6i4zb5x"/></g><path class="qbbym3b8e"/><path class="xkw39pb1a"/><path class="axgzgbc8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:woman-bald-medium-light-skin-tone" /></template>
<style>
.axgzgbc8x {
  fill: var(--svg-color--6d4c41, #6d4c41);
  d: path("M72.31 76.14c-3.15 1.87-13.46 1.87-16.61 0c-1.81-1.07-3.65.57-2.9 2.21c.74 1.61 6.37 5.36 11.23 5.36c4.87 0 10.42-3.75 11.16-5.36c.75-1.64-1.07-3.29-2.88-2.21");
}

.bobtrp_3e {
  fill: var(--svg-color--e0bb95, #e0bb95);
  d: path("M64.18 11.91c-21 0-33.31 14.79-33.31 41.91c0 21.79 13.49 35.67 25.23 39.83c2.8.99 5.5 1.49 7.9 1.49c2.38 0 5.07-.49 7.85-1.47c11.76-4.14 25.28-18.03 25.28-39.84c0-27.13-11.95-41.92-32.95-41.92");
}

.ci_fo_bpd {
  stop-color: var(--svg-color--5914f2, #5914f2);
}

.i2mcs1bjm {
  cx: 47.57px;
  cy: 58.87px;
  rx: 4.87px;
  ry: 5.04px;
}

.qbbym3b8e {
  fill: var(--svg-color--c48e6a, #c48e6a);
  d: path("M67.82 68.05c-.1-.04-.21-.07-.32-.08h-6.99c-.11.01-.21.04-.32.08c-.63.26-.98.91-.68 1.61s1.69 2.66 4.49 2.66s4.19-1.96 4.49-2.66c.31-.69-.04-1.35-.67-1.61");
}

.qp89kubki {
  fill: var(--svg-color--5d4037, #5d4037);
}

.rk6i4zb5x {
  cx: 80.43px;
  cy: 58.87px;
  rx: 4.87px;
  ry: 5.04px;
}

.tur50ibnn {
  d: path("M64.12 94.45h-.13c-25.65.03-51.46 7.55-51.46 25.44v4.07h102.93v-4.07c0-16.87-25.56-25.44-51.34-25.44");
}

.u3kz4vb7l {
  stop-color: var(--svg-color--530eeb, #530eeb);
}

.xb94qyb-t {
  stop-color: var(--svg-color--651fff, #651fff);
}

.xkw39pb1a {
  fill: var(--svg-color--ab872f, #ab872f);
  d: path("M55.16 49.82c-.93-1.23-3.07-3.01-7.23-3.01s-6.31 1.79-7.23 3.01c-.41.54-.31 1.17-.02 1.55c.26.35 1.04.68 1.9.39s2.54-1.16 5.35-1.18c2.81.02 4.49.89 5.35 1.18s1.64-.03 1.9-.39c.29-.38.39-1.01-.02-1.55m32.14 0c-.93-1.23-3.07-3.01-7.23-3.01s-6.31 1.79-7.23 3.01c-.41.54-.31 1.17-.02 1.55c.26.35 1.04.68 1.9.39s2.54-1.16 5.35-1.18c2.81.02 4.49.89 5.35 1.18s1.64-.03 1.9-.39c.28-.38.39-1.01-.02-1.55");
}

.zdf6xpx0m {
  fill: var(--svg-color--c48e6a, #c48e6a);
  d: path("M73.07 90.08H54.91v9.98c0 4.51 3.7 8.17 8.26 8.17h1.65c4.56 0 8.26-3.66 8.26-8.17v-9.98zm-36.4-17.82c-5.36 0-9.71-4.67-9.71-10.41s4.36-10.41 9.71-10.41h54.65c5.36 0 9.71 4.67 9.71 10.41s-4.36 10.41-9.71 10.41z");
}

</style>
