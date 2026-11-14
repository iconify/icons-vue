<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ri04qubdn"/><path class="kgpmh5bmr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:valve-oil" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kgpmh5bmr {
  d: path("M11.879 10h.242a1.5 1.5 0 0 0 1.463-1.832l-.668-2.937A.94.94 0 0 0 12 4.5a.94.94 0 0 0-.916.731l-.668 2.937A1.5 1.5 0 0 0 11.879 10M12 4.5v-2m-2.5 13h5");
}

.ri04qubdn {
  d: path("M10.5 10h3a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5h-3A3.5 3.5 0 0 1 7 18v-4.5a3.5 3.5 0 0 1 3.5-3.5");
}

</style>
