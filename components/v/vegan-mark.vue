<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lcs9-h7ja"/><path class="qj8vrgbne"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:vegan-mark" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lcs9-h7ja {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0m9.5 5v-7");
}

.qj8vrgbne {
  d: path("M12 14c-2 0-3.5-1.25-3.5-3.5c2 0 3.5 1.25 3.5 3.5m0-2c2 0 3.5-1.25 3.5-3.5c-2 0-3.5 1.25-3.5 3.5");
}

</style>
