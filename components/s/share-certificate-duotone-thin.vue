<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k6x1rnb3p"/><path class="ky4omnbla"/><path class="zwh7a2bjz"/><path class="wg8_ddc1f"/><path class="re2g2xb7o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:share-certificate-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k6x1rnb3p {
  fill: currentColor;
  d: path("m16 11 2 2 -2 2 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ky4omnbla {
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
}

.re2g2xb7o {
  d: path("m16 11 2 2 -2 2 -2 -2Z");
}

.wg8_ddc1f {
  d: path("M6 12h6");
}

.zwh7a2bjz {
  d: path("M6 9h9");
}

</style>
