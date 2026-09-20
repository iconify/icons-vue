<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="z-q1eh5iu"/><path class="b_5y93rik"/><path class="xucfzr8ng"/><path class="zy54a7bml"/><path class="i2-ny_bzf"/><path class="ffs26fbkv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:transit-gateway-duotone-bold" /></template>
<style>
.b_5y93rik {
  d: path("m12 8.5 3.5 3.5 -3.5 3.5L8.5 12Z");
}

.ffs26fbkv {
  d: path("M12 17v4");
}

.i2-ny_bzf {
  d: path("M12 3v4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xucfzr8ng {
  d: path("M3 12h4");
}

.z-q1eh5iu {
  fill: currentColor;
  d: path("m12 8.5 3.5 3.5 -3.5 3.5L8.5 12Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zy54a7bml {
  d: path("M17 12h4");
}

</style>
