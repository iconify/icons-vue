<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x23l4nbxg"/><path class="uvz_7pbbi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:microphone-lines" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uvz_7pbbi {
  d: path("M4.5 11.5a7.5 7.5 0 0 0 15 0M12 19v2.5");
}

.x23l4nbxg {
  d: path("M12 2.5za4 4 0 0 1 4 4v4a4 4 0 0 1-4 4a4 4 0 0 1-4-4v-4a4 4 0 0 1 4-4m-4 4h2M8 10h2m4-3.5h2M14 10h2");
}

</style>
