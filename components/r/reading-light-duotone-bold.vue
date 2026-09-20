<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="svccqbc_g"/><path class="y--9wccrh"/><path class="pkfzzlbbg"/><path class="jwxgs0b2c"/><path class="v4hj5197o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:reading-light-duotone-bold" /></template>
<style>
.jwxgs0b2c {
  d: path("m11 9 4 -4");
}

.pkfzzlbbg {
  d: path("M11 9v11");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.svccqbc_g {
  fill: currentColor;
  d: path("M10 9h8l-4 4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.v4hj5197o {
  d: path("M10 9h8l-4 4Z");
}

.y--9wccrh {
  d: path("M5 20h12");
}

</style>
