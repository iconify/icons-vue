<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r8dzomb3z"/><path class="qvq8nib-l"/><path class="wg8_ddc1f"/><path class="zy1jzxj5t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pipeline-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qvq8nib-l {
  d: path("M2 12a4 4 0 0 1 4 -4h12a4 4 0 0 1 4 4 4 4 0 0 1 -4 4H6a4 4 0 0 1 -4 -4");
}

.r8dzomb3z {
  fill: currentColor;
  d: path("M2 12a4 4 0 0 1 4 -4h12a4 4 0 0 1 4 4 4 4 0 0 1 -4 4H6a4 4 0 0 1 -4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.wg8_ddc1f {
  d: path("M6 12h6");
}

.zy1jzxj5t {
  d: path("M12.5 9.5 15 12l-2.5 2.5");
}

</style>
