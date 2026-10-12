<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rv4a1xb0g"/><path class="eonp48qtu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:umbrella" /></template>
<style>
.eonp48qtu {
  d: path("M12 11v7.75a1.75 1.75 0 0 1-3.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rv4a1xb0g {
  d: path("M3.25 12.25a8.75 8.75 0 0 1 17.5 0a3.75 3.75 0 0 0-5.83 0a3.75 3.75 0 0 0-5.84 0a3.75 3.75 0 0 0-5.83 0");
}

</style>
