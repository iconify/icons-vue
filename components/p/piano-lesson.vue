<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mtuecs9vi"/><path class="vng0ey4sg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:piano-lesson" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mtuecs9vi {
  d: path("M6 5h12a3.5 3.5 0 0 1 3.5 3.5v7A3.5 3.5 0 0 1 18 19H6a3.5 3.5 0 0 1-3.5-3.5v-7A3.5 3.5 0 0 1 6 5");
}

.vng0ey4sg {
  d: path("M7.25 5za1 1 0 0 1 1 1v5.5a1 1 0 0 1-1 1a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1M12 5za1 1 0 0 1 1 1v5.5a1 1 0 0 1-1 1a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1m4.75 0za1 1 0 0 1 1 1v5.5a1 1 0 0 1-1 1a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1m-9.5 7.5V19M12 12.5V19m4.75-6.5V19");
}

</style>
