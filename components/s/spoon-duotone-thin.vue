<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wsfzahu1x"/><path class="cenf9z9qb"/><path class="e7fjltb5i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:spoon-duotone-thin" /></template>
<style>
.cenf9z9qb {
  d: path("M8 5a4 4 0 0 1 8 0c0 5 -2 8 -4 8s-4 -3 -4 -8");
}

.e7fjltb5i {
  d: path("M12 13v8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wsfzahu1x {
  fill: currentColor;
  d: path("M8 5a4 4 0 0 1 8 0c0 5 -2 8 -4 8s-4 -3 -4 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
