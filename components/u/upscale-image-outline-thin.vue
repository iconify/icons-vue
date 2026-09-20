<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o72p0hsyz"/><path class="dbejob5iv"/><path class="l-xojxb9d"/><path class="e1z94dboa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:upscale-image-outline-thin" /></template>
<style>
.dbejob5iv {
  d: path("M6 12.5a2 2 0 0 1 2 -2h2.5a2 2 0 0 1 2 2V15a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

.e1z94dboa {
  d: path("M14.5 7H17v2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l-xojxb9d {
  d: path("m13 11 4 -4");
}

.o72p0hsyz {
  d: path("M14 4h4a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V7a3 3 0 0 1 3 -3h4");
}

</style>
